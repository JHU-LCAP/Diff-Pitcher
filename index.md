## DiffPitcher: Diffusion-based Singing Voice Pitch Correction

### Framework

![Framework](Difftuner.drawio.png)

😊[DiffPitcher is available!](https://github.com/DiffPitcher/DiffPitcher/tree/main)

### Template-based Automatic Pitch Correction Examples

Here are examples of template-based automatic pitch correction where the pitch curve of a template audio is transferred to the out-of-tune audio. A Dynamic Time Warping algorithm based on MCEP is applied to further align template pitch curve and the target audio. 

<small><font color="gray">*The degree of off-key singing is notably higher in Chinese examples. Furthermore, these Chinese examples are recorded by mobile devices, mirroring the typical usage scenario of a karaoke app.</font></small>

<small><font color="gray">*The paired English recordings are from PopBuTFy, which focuses more on fine-grained vocal techniques such as Vibrato rather than extreme off-key.</font></small>

#### Sample 1 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/c_f1_0.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/c_f1_0.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_c_f1_0.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/c_f1_0_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/c_f1_0_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/c_f1_0_pw.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

#### Sample 2 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/c_f3_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/c_f3_4.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>Diff-Pitcher-WORLD</b></td>
      <td>Diff-Pitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_c_f3_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/c_f3_4_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/c_f3_4_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/c_f3_4_pw.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>
#### Sample 3 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/c_f4_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/c_f4_4.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_c_f4_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/c_f4_4_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/c_f4_4_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/c_f4_4_pw.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>


#### Sample 4 (CH/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/c_m2_16.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/c_m2_16.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_c_m2_16.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/c_m2_16_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/c_m2_16_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/c_m2_16_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>
#### Sample 5 (CH/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/c_m2_31.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/c_m2_31.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_c_m2_31.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/c_m2_31_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/c_m2_31_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/c_m2_31_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>


#### Sample 6 (EN/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/e_f2_5.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/e_f2_5.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_e_f2_5.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/e_f2_5_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/e_f2_5_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/e_f2_5_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>

#### Sample 7 (EN/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/e_f7_9.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/e_f7_9.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_e_f7_9.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/e_f7_9_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/e_f7_9_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/e_f7_9_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>
#### Sample 8 (EN/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/e_f9_3.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/e_f9_3.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_e_f9_3.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/e_f9_3_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/e_f9_3_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/e_f9_3_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>

#### Sample 9 (EN/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/e_m2_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/e_m2_1.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_e_m2_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/e_m2_1_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/e_m2_1_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/e_m2_1_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>


#### Sample 10 (EN/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>Template audio</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal_detune/e_m4_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/vocal/e_m4_1.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
        <td><b>DiffPitcher-WORLD</b></td>
      <td>DiffPitcher-LPC</td>
      <td>SiFi-GAN</td>
      <td>WORLD Vocoder</td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_world/dw_e_m4_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/diff_lpc/e_m4_1_lpc.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/sifigan/e_m4_1_sifi.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/world/e_m4_1_pw.wav" type="audio/wav" /></audio></td>
      </tr>
      </tbody>
      </table>
<hr>

### Score-based Automatic Pitch Correction Examples

Here are examples of score-based automatic pitch correction where the pitch curve predicted by the pitch predictor is transferred to the out-of-tune audio. The pitch predictor takes MIDI notes and the vocal spectrum of the out-of-tune audio as inputs.

<small><font color="gray">*Compared with Templated-based APC, score-based APC offers great flexibility and diversity at the cost of a small degradation of naturalness.</font></small>

<small><font color="gray">*We are collecting English acapella examples.</font></small>

#### Sample 1 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/f1_0.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/f1_0.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/f1_0.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/f1_0.wav" type="audio/wav" /></audio></td>
    </tr>
</tbody>
</table>
<hr>

#### Sample 2 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/f1_8.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/f1_8.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/f1_8.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/f1_8.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

#### Sample 3 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/f2_4.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/f2_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/f2_4.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/f2_4.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

#### Sample 4 (CH/Female)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/f3_16.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/f3_16.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/f3_16.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/f3_16.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

#### Sample 5 (CH/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/m2_1.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/m2_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/m2_1.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/m2_1.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

#### Sample 6 (CH/Male)

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
       <img style="width: 600px;height: 450px" src="samples/pitch_predictor/pic/m2_9.wav.png" class="center">
    </tr>
</tbody>
</table>
<hr>

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Out-of-tune audio</td>
      <td>MIDI Notes</td>
        <td><b>Tuned Audio</b></td>
    </tr>
    <tr>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/detuned/m2_9.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/midi/m2_9.wav" type="audio/wav" /></audio></td>
        <td><audio controls="" style="width: 180px;height: 50px"><source src="samples/pitch_predictor/tuned/m2_9.wav" type="audio/wav" /></audio></td>
      </tr>
</tbody>
</table>
<hr>

### Appendix
#### Objective Experiment: 

- Log RMSE of Pitch Shifting

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Approach</td>
      <td>-6 Semitones</td>
      <td>-3 Semitones</td>
      <td>Reconstruction</td>
      <td>+3 Semitones</td>
      <td>+6 Semitones</td>
    </tr>
    <tr>
      <td>WORLD</td>
      <td>0.03</td>
      <td>0.03</td>
      <td>0.03</td>
      <td>0.03</td>
      <td>0.03</td>
    </tr>
      <tr>
      <td>SiFi-GAN</td>
      <td>0.05</td>
      <td>0.04</td>
      <td>0.04</td>
      <td>0.05</td>
      <td>0.04</td>
    </tr>
      <tr>
      <td>DiffPitcher-WORLD</td>
      <td>0.04</td>
      <td>0.03</td>
      <td>0.04</td>
      <td>0.04</td>
      <td>0.06</td>
    </tr>
</tbody>
</table>
<hr>

- Word Error Rate of Pitch Shifting

<table align="center" style="margin: 0px auto;">
  <tbody>
    <tr>
      <td>Approach</td>
      <td>-6 Semitones</td>
      <td>-3 Semitones</td>
      <td>Reconstruction</td>
      <td>+3 Semitones</td>
      <td>+6 Semitones</td>
    </tr>
    <tr>
      <td>WORLD</td>
      <td>2.00%</td>
      <td>2.68%</td>
      <td>3.23%</td>
      <td>3.04%</td>
      <td>2.17%</td>
    </tr>
      <tr>
      <td>SiFi-GAN</td>
      <td>2.98%</td>
      <td>2.85%</td>
      <td>3.35%</td>
      <td>2.98%</td>
      <td>3.61%</td>
    </tr>
      <tr>
      <td>DiffPitcher-WORLD</td>
      <td>2.57%</td>
      <td>2.41%</td>
      <td>2.88%</td>
      <td>2.64%</td>
      <td>2.23%</td>
    </tr>
</tbody>
</table>
<hr>

