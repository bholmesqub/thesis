---
layout: default
title: "Circuit modelling and identification"
---

# Circuit modelling and identification

## Black box modelling

Below is a video demonstrating the amplitude-dependent nature of nonlinearities, exemplified through the nonlinear impulse response of a diode clipper. The input voltage to the diode clipper increases logarithmically over time and back again. A guitar chord is repeated demonstrating the sound of the different input levels. The guitar sound uses an equivalent amplitude as the sine sweep but has been normalised afterward to place the focus on the sound of the distortion and not the amplitude of the signal.

The video was generated using MATLAB and code from

> *A. Novak, P. Lotton, and L. Simon, “Synchronized Swept-Sine: Theory, Application, and Implementation,” Journal of the Audio Engineering Society, vol. 63, pp. 786–798, Nov. 2015*.

As the input amplitude increases the output becomes more distorted and the first harmonic deviates from the ideal linear transfer function.

### Left plot

The black dashed line marks the hypothetical linear transfer function of a diode clipper should the input signal be sufficiently small. The remaining lines represent the amplitude response of a given harmonic. Over time the amplitude increases and the presence of the higher harmonics increase as well. Vp notes the peak input voltage

### Right plot

The time domain visualisation of a sine wave being processed by the diode clipper at the given amplitude. f0 marks the fundamental frequency of the sine wave.

<video width="100%" controls>
 <source src="{{ site.baseurl }}/files/diodeClipperSSS_video.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
