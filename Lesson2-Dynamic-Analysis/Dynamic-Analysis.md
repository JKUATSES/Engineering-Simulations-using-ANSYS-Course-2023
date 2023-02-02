# Introduction to Vibration Analysis

The importance of vibrations in structures is well known among engineers. When structures are not designed for vibrations and dynamic integrity the result can be catastrphic failure or breakdown. Simulation therefore plays an integral role in our ability to understand a structure's dynamic behavior. 
Three main types of problems for structural and dynamic analysis:
1. Modal analysis:  *f(t) = 0*
2. Frequency response analysis:  *f(t) = F.sin(w.t)*
3. Transient response analysis:  *f(t) = Arbitrary*


## 1.Modal Analysis
Modal analysis is used to determine the **vibration characteristics** of linear elastic structures. It is also typically the starting point for many other dynamic simulations. In this analysis, two major characteristics of a structure are investigated:
- Natural frequencies 
- Normal modes (shapes)

The understanding of natural frequencies helps in the avoidance of **resonance** while the study of the structures normal modes helps engineers to understand more complex **dynamic behavior.**

### Governing Equation of Modal Analysis
The general equation of motion is used for solving the dynamic response of a structure

![image](https://user-images.githubusercontent.com/74782784/216244499-8cc41716-ba03-4624-8ce9-52626c5428e5.png)

By setting the external loads to zero (natural frequency and mode shapes are independent of loads) and ignoring damping effects, our equation of motion reduces further. 

![image](https://user-images.githubusercontent.com/74782784/216245297-64dc19e7-47c4-47d5-aa9c-7aa6ad911728.png)

The equation now describes a body sitting somewhere without motion or a body moving with a constant velocity. However, the equation is still in the time domain. Even though vibrations at natural frequencies are initiated by forces acting on a structures, they are are an inherent property of the structure and independent of the forces causing them. In order to get rid of the forces (i.e. *ma & kx*) we need to shift from a time domain to a frequency domain. To do this, let's assume every point in the structure is undergoing harmonic motion. 

![image](https://user-images.githubusercontent.com/74782784/216246979-8ecc854e-f008-427b-b297-c00b30deb31a.png)

The displacement and acceleration can now be described in a harmonic format

![image](https://user-images.githubusercontent.com/74782784/216250140-82713abf-41c3-40a8-889b-6ee52319a949.png)

![image](https://user-images.githubusercontent.com/74782784/216250208-c2b045fe-c4da-4002-bcf8-d73ba02e8d91.png)

Substituting harmonic expressions of {𝒖} and {𝒖''} into the governing equation

![image](https://user-images.githubusercontent.com/74782784/216250396-ed5880f7-fb19-4689-bdf6-4ea93fc2e3ff.png)

This is an **eigenvalue problem** and the unknowns change from {𝒖} and {𝒖''} to *𝜔* and *𝜙.*



