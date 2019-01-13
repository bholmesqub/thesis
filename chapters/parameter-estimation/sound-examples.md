---
layout: default
title: "Sound examples of the two case studies"
---

# Sound examples of the two case studies

Here simulated and measured sound examples of the tone stack and common-emitter amplifier are compared. The simulated sets are generated with the optimised parameters presented in the thesis. The objective of these sound examples are to provide some subjective context for readers.

**Measured sound examples have not yet been created, tentative upload date of 21/01/2019.**

The same sample is used for each circuit, the dry sound of which is:

<audio controls style="width: 100%; text-align: center; vertical-align: middle;">
  <source src="{{ site.baseurl }}/audio/bjt/direct/ChordsPicking.wav" type="audio/wav">
Your browser does not support the audio element.
</audio>

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

## Common-emitter amplifier

### Simulated

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>V<sub>p</sub> = 0.5 V</th>
    <th>V<sub>p</sub> = 1 V</th>
    <th>V<sub>p</sub> = 2 V</th>
    <th>V<sub>p</sub> = 4 V</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/ce_audio_0.5V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/ce_audio_1.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/ce_audio_2.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/clean/ce_audio_4.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Tone stack -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_model/ce_audio_0.5V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_model/ce_audio_1.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_model/ce_audio_2.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/parameter-estimation/common-emitter/sim/amp_model/ce_audio_4.0V.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>
