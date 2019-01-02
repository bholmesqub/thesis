---
layout: default
title: "Calibration of the Dallas Rangemaster model"
---

# Calibration of the Dallas Rangemaster model

To demonstrate the audible differences between the Rangemaster models and circuit measurements, this page features sound examples of both the Germanium and Silicon Rangemasters. The selected sound is a single chord and can be listened to with and without an amp simulation after the effect.

The original sound examples were presented on [the companion pages for the DAFx 16 publication](https://bholmesqub.github.io/DAFx16/), but have been updated with the new identified parameters for this page.

## Germanium Rangemaster comparison

Inspecting the difference between the circuit and the model output when processing the guitar chord the error is low, as seen in the below figure. The most significant error appears to be an inability to match the negative swing of the circuit, which is most prominent at the highest amplitude section at the beginning of the signal.

![Difference between Rangemaster outputs](../../images/calibration/germanium_audio_comparison.png)

Sound examples clearly demonstrate the difference between nominal and calibrated models, with the calibrated model sounding more similar to the circuit.

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>Dry</th>
    <th>Nominal</th>
    <th>Calibrated</th>
    <th>Circuit</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-germanium-nominal.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-germanium-identified.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-germanium-circuit.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster -> Amp Sim</td>
    <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_germanium_nominal.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_germanium_identified.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_germanium_circuit.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
    </td>
  </tr>
</table>

## Silicon Rangemaster comparison

A larger amount of error is observed between circuit and model output for the Silicon Rangemaster, displayed in the figure below. Error exists in both negative and positive portions of the signal, and is still present as the chord decays.

![Difference between Rangemaster outputs](../../images/calibration/silicon_audio_comparison.png)

Despite the error in the waveform view, sound examples reveal a similar degree of fidelity with the calibrated model as with the Germanium instance.

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>Dry</th>
    <th>Nominal</th>
    <th>Calibrated</th>
    <th>Circuit</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-silicon-nominal.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-silicon-identified.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/calibration/direct/chord-silicon-circuit.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster -> Amp Sim</td>
    <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_silicon_nominal.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_silicon_identified.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
  </td>
  <td>
    <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
      <source src="{{ site.baseurl }}/audio/calibration/sim/chord_silicon_circuit.wav" type="audio/wav">
    Your browser does not support the audio element.
    </audio>
    </td>
  </tr>
</table>
