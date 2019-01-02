---
layout: default
title: "Bipolar Junction Transistor modelling for Virtual Analogue"
---
# Bipolar Junciton Transistor modelling for Virtual Analogue

## Rangemaster comparison

To further understand the Rangemaster in a real scenario, here guitar signals are compared. The signal is a chord normalised to have a peak value of 1 V. The signal is then processed at 8x oversampling through the Rangemaster for the three models: Ebers-Moll (EM), DC Gummel-Poon (GP), and AC Gummel-Poon. The waveforms are displayed below:
![Difference between Rangemaster outputs](../../images/bjt-modelling/rm-diff.png)

### Sound examples

The three BJT models in the Rangemaster are here compared through sound examples in the below table. The input signal used is a direct recording of a guitar (Gibson Les Paul Junior, P90 pickup) featuring strumming and arpeggiation of some chords. An amp simulation follows the Rangemaster for one set of signals to better represent the a useful sound of the effect. The amp sim used was "Brit and Clean" from GarageBand which, based on the representative image in the software, looks remarkably like a Vox AC30.

A noteable difference between Ebers-Moll and Gummel-Poon can be heard in the transients of the arpeggios, particularly noticeable on the signals without amp simulation

<table style="width:100%; table-layout: fixed">
  <tr>
    <th></th>
    <th>Dry</th>
    <th>Ebers-Moll</th>
    <th>DC Gummel-Poon</th>
    <th>AC Gummel-Poon</th>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/direct/ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/direct/ebers-moll_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/direct/full_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/direct/dynamic_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
  <tr>
    <td style="font-weight: bold;">Guitar -> Rangemaster -> Amp Sim</td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/sim/ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/sim/ebers-moll_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/sim/full_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
    <td>
      <audio controls style="width: 100%; text-align: center; vertical-align: middle;">
        <source src="{{ site.baseurl }}/audio/bjt/sim/dynamic_ChordsPicking.wav" type="audio/wav">
      Your browser does not support the audio element.
      </audio>
    </td>
  </tr>
</table>
