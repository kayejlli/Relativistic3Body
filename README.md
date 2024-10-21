# Relativistic3Body
This repository contain the mathematic script of the paper (with arXiv link:). Please refer to the file Manual.nb for how to use this. 

## Correspondance
$K_{(b), 1, 0} == \text{HInner1PN}$ 

$K_{(b), 1, 2} == \text{HOuter1PN}$

$K_{(0), 0, 3} == \text{Hquad0PN}$

$K_{(0), 0, 4} == \text{Hoct0PN}$

$K_{(1), 0, 9/2} == \text{C09CS0606}$

$K_{(0), 1, 1/2} == \text{Hoct1PN05}$

$K_{(0), 1, 1} == \text{Hquad1PN1}$

$K_{(0), 1, 2} == \text{Hoct1PN2}$

$K_{(0), 1, 5/2} == \text{Hquad1PN25}$

$K_{(1), 1, 3/2} == \text{C13CS1006}$

$K_{(1), 1, 5/2} == \text{C15CS1008}$

## Special ones
The generating functions of the cross term contain special symbols:
```math
\text{Fn1m2k3lP4} =  \bigg\{ \frac{ \log^1 (1- e \cos u)  \sin^2 u  \bigg[ \tan^{-1} \bigg( \frac{e  \sin (u)}{1+\sqrt{1-e^2}-e  \cos (u)} \bigg) \bigg]^3}{(1-e \cos u)^4} \bigg\}_{l}
```
and similarly, we have
```math
\text{Fn2m3k4lN5} =  \bigg\{  \log^2 (1- e \cos u)  \sin^3 u  \bigg[ \tan^{-1} \bigg( \frac{e  \sin (u)}{1+\sqrt{1-e^2}-e  \cos (u)} \bigg) \bigg]^4 (1-e \cos u)^5  \bigg\}_{l}
```
