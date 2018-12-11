---
layout: default
title: "Bipolar Junction Transistor modelling for Virtual Analogue"
---
# Bipolar Junciton Transistor modelling for Virtual Analogue

## Rangemaster comparison

To further understand the Rangemaster in a real scenario, here guitar signals are compared. The signal is a chord normalised to have a peak value of 1 V. The signal is then processed at 8x oversampling through the Rangemaster for the three models: Ebers-Moll, DC Gummel-Poon (GP), and AC Gummel-Poon. The waveforms are displayed below:
![Difference between Rangemaster outputs](../../images/rm-diff.png)

### Sound examples

The three BJT models in the Rangemaster are here compared through sound examples, concatenating each signal as **Ebers-Moll -> DC Gummel-Poon -> AC Gummel-Poon**.

The dry chord, unprocessed:
<audio controls>
  <source src="{{ site.baseurl }}/audio/chord.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

After the Rangemaster with an amp simulation:
<audio controls>
  <source src="{{ site.baseurl }}/audio/bjt/bjt-rm-amp.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

After the Rangemaster without an amp simulation:
<audio controls>
  <source src="{{ site.baseurl }}/audio/bjt/bjt-rm-clean.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>
