---
layout: default
title: "Root finding algorithms for nonlinear physical circuits"
---

# Root finding algorithms for nonlinear physical circuits

The MATLAB code for several multivariate root finding algorithms are provided in the below gist, entitled `numericalsolver`. Four methods are implemented:

- Newton's method
- Damped Newton's method
- Chord method
- Capped step

For the New Iterate, the iterate must be found prior to running the function and then used with Newton's method. The limitation of the capped step must also be calculated prior to running the function.

# numericalsolver

<script src="https://gist.github.com/bholmesqub/27d5cc295287820bf9f84f32694b2a82.js"></script>
