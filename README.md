# Stride - A modelling and optimisation framework for medical ultrasound

Stride is an open-source library for medical ultrasound modelling and tomography. 

We provide high-performance, finite-difference, time-domain solvers for modelling ultrasound propagation in the human body, 
including:

- Variable speed of sound, density, and attenuation.
- Off-grid sources and receivers.
- A variety of absorbing boundary conditions.
- Targeting both CPUs and GPUs with the same code.

Solvers in Stride are written in [Devito](https://www.devitoproject.org/), using math-like symbolic expressions. This means
that anyone can easily add new physics to Stride, which will also run on both CPUs and GPUs.

Stride also lets users easily prototype medical tomography algorithms with only a few lines of Python code by providing:
 
- Composable, automatic gradient calculations. 
- State-of-the-art reconstruction algorithms. 
- The flexibility to (re)define every step of the optimisation. 

Stride can scale seamlessly from a Jupyter notebook in a local workstation, to a multi-node CPU cluster or a GPU cluster 
with production-grade performance.
