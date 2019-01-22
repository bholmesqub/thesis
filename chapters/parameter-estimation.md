---
layout: default
title: "Parameter estimation of tone stack and common-emitter circuits"
---

# Parameter estimation of tone stack and common-emitter circuits

# Sound examples of the two case studies

Here simulated and measured sound examples of the tone stack and common-emitter amplifier are compared. The simulated sets are generated with the optimised parameters presented in the thesis. The objective of these sound examples is to provide some subjective context for readers.

The same sample is used for each circuit, the dry sound of which is:

<audio controls style="width: 100%; text-align: center; vertical-align: middle;">
  <source src="{{ site.baseurl }}/audio/bjt/direct/ChordsPicking.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

Each measured sample present on this page was recorded using a different Data Acquisition device (DAQ) than was used for those samples used in the identification procedure. These samples used the NI myDAQ, a budget-friendly DAQ, which unfortunately features markedly higher noise which is clear in the recordings of the common-emitter amplifier.

Circuits and models were modified to use different load components, the tone stack not using any load other than the capacitance of the DAQ, and the common-emitter amplifier using a 1 Meg resistor as the high impedance of the myDAQ input caused the output capacitor to float up towards the power rail.

A 9V battery was used for the common-emitter amplifier due to the limitations of the myDAQ, meaning that the power supply voltage was not a known quantity and therefore the may be slight audible differences.

## Tone stack

### Simulated

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>t<sub>h</sub>, b<sub>h</sub></th>
    <th>t<sub>h</sub>, b<sub>l</sub></th>
    <th>t<sub>l</sub>, b<sub>h</sub></th>
    <th>t<sub>l</sub>, b<sub>l</sub></th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/clean/tonestack_audio_t_h-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/clean/tonestack_audio_t_h-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/clean/tonestack_audio_t_l-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/clean/tonestack_audio_t_l-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_h-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_h-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_l-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_l-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>

### Measured

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>t<sub>h</sub>, b<sub>h</sub></th>
    <th>t<sub>h</sub>, b<sub>l</sub></th>
    <th>t<sub>l</sub>, b<sub>h</sub></th>
    <th>t<sub>l</sub>, b<sub>l</sub></th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/meas/clean/tonestack_audio_t_h-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/meas/clean/tonestack_audio_t_h-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/meas/clean/tonestack_audio_t_l-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/meas/clean/tonestack_audio_t_l-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_h-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_h-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_l-b_h.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/tonestack/sim/amp_model/tonestack_audio_t_l-b_l.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>

## Common-emitter amplifier

### Simulated

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>V<sub>p</sub> = 0.1 V</th>
    <th>V<sub>p</sub> = 0.5 V</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> CE Amplifier</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/commonemitter_0V1.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/commonemitter_0V5.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> CE Amplifier -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_mod/commonemitter_0V1.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_mod/commonemitter_0V5.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>

### Measured

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>V<sub>p</sub> = 0.1 V</th>
    <th>V<sub>p</sub> = 0.5 V</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> CE Amplifier</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/meas/clean/commonemitter_0V1.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/meas/clean/commonemitter_0V5.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> CE Amplifier -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/meas/amp_mod/commonemitter_0V1.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/meas/amp_mod/commonemitter_0V5.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>
