---
menuPre: " "
title: 'Induction'
description: 'Induction'
weight: 500
---

## Electromagnetic Induction

### Faraday's Law

- Whenever the flux of magnetic field through the area bounded by a closed conducting loop changes, and emf in produced in the loop.

- EMF induced $(\mathcal{E})$:  
  $\mathcal{E} = -\dfrac{d\Phi}{dt}$

- Flux ($\Phi$):  
  $\Phi = \int{\vec{B}\cdot \vec{dS}} = BA \cos \theta$

### Lenz's Law

- The direction of induced current is such theat it opposes the change that has induced it.

### Motional EMF
- EMF in a conductor moving with velocity $v$ in magnetic field $B$:  
  $\mathcal{E} = vBl$

### Induced Electric Field

- Induced electric field $E$ around a loop:
  $\oint E \, dl = -\dfrac{d\Phi}{dt}$

### Eddy Current

- Electromagnetic damping.
- Circular currents induced in conductors due to changing magnetic flux.
- $\left|i\right| \propto -\dfrac{d\Phi}{dt}$.

### Self-Induction

- $\Phi = Li$

- Induced EMF $(\mathcal{E})$ in coil due to its own current $I$:  
  $\mathcal{E} = -L \dfrac{di}{dt}$

## Inductors

### Self-Inductance of a Long Solenoid

- $L = \mu_0\:n^2Al$  

- $n$: Turns per unit length,  
  $A$: Cross-sectional area,  
  $l$: Length of solenoid.

### Growth and Decay of Current in an LR Circuit

1. Growth:  
  $i = i_0 \biggr(1 - e^{-t/\tau} \biggr)$  
2. Decay:  
  $i = i_0\: e^{-t/\tau}$  
3. Time constant ($\tau$):  
  $\tau = \dfrac{L}{R}$

At $t = \tau$,  
Growth: $i = i_0 (1-\dfrac{1}{e}) = 0.63 i_0$  
Decay: $i = i_0 \dfrac{1}{e} = 0.37 i_0$

### Energy Stored in an Inductor

- Energy $(U)$:
  $U = \dfrac{1}{2} L i^2$

### Energy Density in a Magnetic Field

- $B = \mu_0\:ni$

- $u =  \dfrac{B^2}{2 \mu_0}$  

### Mutual Induction

- Mutual Inductance $(M)$:  
  $M = \dfrac{\mu_0 N_1 N_2 A}{l}$

- Induced EMF $\mathcal{E}_2$ in $\text{coil}_2$ due to change in current $i_1$ in $\text{coil}_1$:  
  $\mathcal{E}_2 = -M \dfrac{di_1}{dt}$
