---
layout: default
title: "Component tolerances in guitar pedals"
---

## Component tolerances in guitar pedals

To provide a reference for the component tolerances of components in guitar pedals, here 3 images of the Boss DS-1, Dunlop Fuzz Face, and Dallas Rangemaster are presented. Resistors are chosen as a frame of reference as the marking strategy makes the identification of resistance tolerance easy and reliable, and the standard has [existed since 1952](https://webstore.iec.ch/publication/12579).

Analysis of the extracted BJT parameters from Chapter 4 is also provided to determine the range of parameters found in germanium BJTs, though the small number of devices investigated limits the applicability of the results.

### Boss DS-1

The Boss DS-1 is an entry-level, budget guitar pedal, and can be purchased currently for around £50. [It is famed to have been used by Kurt Cobain](https://www.guitarworld.com/gear/archive-definitive-kurt-cobain-gear-guide). Below is an image of the DS-1 PCB. Focus on the resistors was missed resulting in a blurry photo. An attempt to  correct this has been made by sharpening the image to provide a clearer view of the colour bands of the resistors.

Each visible resistor is marked with a gold-band, which according to the standard cannot be used for the resistance value and so must relate to the tolerance. [Gold marks ±5% tolerance](https://en.wikipedia.org/wiki/Electronic_color_code).

![]({{site.baseurl}}/images/ident-design/ds1-pcb.jpg)

### Dunlop Fuzz Face

The Fuzz Face is already covered in the thesis. The pictured version below is of a modern iteration - though still using germanium BJTs. It was purchased for £120 and so is an expensive pedal. This is reflected in the component choices within the circuit. Each resistor is marked with a brown band, separated with a slightly larger gap than the other bands, distinguishing it as the tolerance marking. Brown indicates ±1 % tolerance.

![]({{site.baseurl}}/images/ident-design/fuzzface-pcb.jpg)

### Dallas Rangemaster

Again the Rangemaster is covered thoroughly in the thesis. The original pedal is no longer manufactured and so only second-hand versions or clones are available.

The picture below is from an unmodified original unit. Silver bands mark two of the resistors, indicating ±10%, the remaining resistors not featuring any identifying marks for tolerance.

![]({{site.baseurl}}/images/ident-design/rangemaster-inside.jpg)

### Germanium BJT tolerance

Using the extracted values from the germanium BJTs in Chapter 4, some information of the parameter tolerance can be found. The AC128 is chosen to find parameter tolerances as it was for this BJT that the highest number of devices were measured (4). The Ebers-Moll parameters are chosen as they are used in the calibration in Chapter 6. The extracted parameters are taken from the Gummel-Poon model as this yielded the best fit to measurements.

The metric used to approximate each parameter's tolerance is the range normalised by twice mean of the set, given in percent. By including the additional factor of 2 in the denominator the resulting percentage is effectively expressed as a plus/minus tolerance.

For the saturation current:
<div>
\begin{equation}
  I_\mathrm{s} = [27.77,\ 31.67,\ 29.44,\ 20.66],\quad \mathrm{mean}(I_\mathrm{s}) = 27.39,
\end{equation}
\begin{equation}
  \frac{1}{2} \times 100 \times \frac{\mathrm{max}(I_\mathrm{s}) - \mathrm{min}(I_\mathrm{s})}{\mathrm{mean}(I_\mathrm{s})} = 20.1\% .
\end{equation}
</div>

For the forward current gain:
<div>
\begin{equation}
  \beta_\mathrm{f} = [156.7,\ 125.7,\ 149.9,\ 229.6],\quad \mathrm{mean}(\beta_\mathrm{f}) = 165.48,
\end{equation}
\begin{equation}
  \frac{1}{2} \times 100 \times \frac{\mathrm{max}(\beta_\mathrm{f}) - \mathrm{min}(\beta_\mathrm{f})}{\mathrm{mean}(\beta_\mathrm{f})} = 31.4\% .
\end{equation}
</div>

For the reverse current gain:
<div>
\begin{equation}
  \beta_\mathrm{r} = [54.45,\ 29.18,\ 15.18,\ 14.66],\quad \mathrm{mean}(\beta_\mathrm{r}) = 28.37,
\end{equation}
\begin{equation}
  \frac{1}{2} \times 100 \times \frac{\mathrm{max}(\beta_\mathrm{r}) - \mathrm{min}(\beta_\mathrm{r})}{\mathrm{mean}(\beta_\mathrm{r})} = 70.1\% .
\end{equation}
</div>
For the forward ideality factor:
<div>
\begin{equation}
  N_\mathrm{f} = [1.142,\ 1.152,\ 1.171,\ 1.133],\quad \mathrm{mean}(N_\mathrm{f}) = 1.150,
\end{equation}
\begin{equation}
  \frac{1}{2} \times 100 \times \frac{\mathrm{max}(N_\mathrm{f}) - \mathrm{min}(N_\mathrm{f})}{\mathrm{mean}(N_\mathrm{f})} = 1.7\% .
\end{equation}
</div>

For the reverse ideality factor:
<div>
\begin{equation}
  N_\mathrm{r} = [1.135,\ 1.157,\ 1.176,\ 1.140],\quad \mathrm{mean}(N_\mathrm{r}) = 1.152,
\end{equation}
\begin{equation}
  \frac{1}{2} \times 100 \times \frac{\mathrm{max}(N_\mathrm{r}) - \mathrm{min}(N_\mathrm{r})}{\mathrm{mean}(N_\mathrm{r})} = 1.8\% .
\end{equation}
</div>

### Summary

A variety of different component tolerances may be found in guitar pedals. What can be concluded from the resistor tolerances in the above pedals is that the tolerances can vary up to ±10%, depending on the quality and/or price of the pedal.

From the small set of extracted parameter values of the AC128, nonlinear component tolerances can be up to 70%. Other than the ideality factors, each BJT component parameter has a tolerance worse than that of the resistors in the aforementioned pedals.
