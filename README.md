Download Link: https://assignmentchef.com/product/solved-ee316-laboratory-05
<br>






<h1>Basic Filters and Frequency Response</h1>

Purpose

The goal of this laboratory is to study the frequency characteristics of Low and High Pass Filters. Specifically, signal amplitude, signal phase, and how they are related to input frequency. In addition, the concept of cutoff frequency will be introduced.

Theoretical Background

A filter is a device or configuration that allows a specific range of input frequencies to pass and rejects signals whose frequency is outside of the specified range. Among the many types of filters, in this laboratory you will be introduced to basic Low and High Pass Filters. These filters consist of nothing more than a configuration made up of a single resistor and capacitor.




Low Pass Filter

Low Pass Filters allow low frequencies to pass and block high frequencies. The ideal Low Pass Filter should allow all frequencies below some specified frequency, call it f<sub>c </sub>(cutoff), to pass and allow no frequencies above f<sub>c</sub> to pass. It is not possible to design an ideal Low Pass Filter. Therefore the design characteristics of the filters used in this laboratory will be nonideal. It is important to be aware there are more sophisticated filtering devices on the market that approach the ideal case.




Figure 5.1, on the next page, shows a typical configuration for a Low Pass Filter. The mathematical development to follow will show that the circuit is acting as a Low Pass Filter at the output terminal A-B. The input frequency and amplitude, E, will directly influence the magnitude and phase of V<sub>C</sub>. In other words, at certain input frequencies the Low Pass Filter will operate on the input E to produce V<sub>c</sub>. The frequency where this action occurs is determined by values chosen for the resistor (R) and the capacitor (C).

<h1>Figure 5.1 LPF</h1>

<h1>Figure 5.2 HPF</h1>




The voltage across the resistor, in Figure 5.2, can be written as










Using the definition of X<sub>c</sub>, and making substitutions, allows the equation to be rewritten as










Using the definition of gain and taking the magnitude gives the final form of










Noticing that 2RC in above Equation is a constant for any given circuit leads to










This equation is recognizable as an increasing function of frequency that approaches unity as the frequency increases. Therefore, the circuit in Figure 5.2 works as a High Pass Filter. The phase angle for the High Pass Filter can be expressed as










Note the phase is initially at π/2 radians, where ideal gain is zero. It shows that the phase of the output will approach zero radians as the frequency increases.




<h1>Cutoff Frequency</h1>




The cutoff frequency, denoted by f<sub>C</sub>, is defined as the frequency at which the magnitude of gain is equal to







Considering the Low Pass Filter configuration










Replacing f with f<sub>c</sub>, and then solving for the cutoff frequency yields










This is true for both Low and High Pass Filters. You determine the cutoff frequency by setting the product value of (RC). Keeping in mind that a low pass configuration will pass frequencies below f<sub>c</sub> and the high pass configuration will pass frequencies above f<sub>c</sub>.




Theoretical Analysis




Let the input signal be a 4V peak-to-peak sinusoid with R = 1 kΩ, and C = 1µF for both the Low and High Pass Filter sections.




<h1>Low Pass Filter</h1>




Referring to circuit in Figure 5.1:




<ul>

 <li>Fill up a table similar to the one given below. (Table 5.1).</li>

 <li>Plot gain in dB vs. frequency. Use data from Table 5.1.</li>

 <li>Plot phase vs. frequency. Use data from Table 5.1.</li>

 <li>Determine the cutoff frequency from your tabulated data you made in step 1. Compare it with the theoretical value. Mark the cutoff frequency on your magnitude plot.</li>

</ul>










<h2>Table 5.1</h2>

<table width="270">

 <tbody>

  <tr>

   <td width="91"></td>

   <td colspan="2" width="179">Theoretical</td>

  </tr>

  <tr>

   <td width="91">f (HZ)</td>

   <td width="88">Gain (dB)</td>

   <td width="91">Phase Angle (Degree)</td>

  </tr>

  <tr>

   <td width="91">25</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">50</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">75</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">100</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">150</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">200</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">300</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">500</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">600</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">700</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">800</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">900</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">1000</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

 </tbody>

</table>







<h1>High Pass Filter</h1>




Referring to circuit in Figure 5.2:




<ul>

 <li>Fill up a table similar to the one given below. (Table 5.2).</li>

 <li>Plot gain in dB vs. frequency. Use data from Table 5.2.</li>

 <li>Plot phase vs. frequency. Use data from Table 5.2.</li>

 <li>Determine the cutoff frequency from your tabulated data you made in step 1. Compare it with the theoretical value. Mark the cutoff frequency on your magnitude plot.</li>

 <li>Table 5.2</li>

</ul>

<table width="270">

 <tbody>

  <tr>

   <td width="91"></td>

   <td colspan="2" width="179">Theoretical</td>

  </tr>

  <tr>

   <td width="91">f (HZ)</td>

   <td width="88">Gain (dB)</td>

   <td width="91">Phase Angle (Degree)</td>

  </tr>

  <tr>

   <td width="91">25</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">50</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">75</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">100</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">150</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">200</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">300</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">500</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">600</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">700</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">800</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">900</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

  <tr>

   <td width="91">1000</td>

   <td width="88"></td>

   <td width="91"></td>

  </tr>

 </tbody>

</table>

Simulation




<h1>Low Pass Filter</h1>

Draw the circuit as shown in Figure 5.3. Note the connection of a new instrument. This instrument is called a Bode Plotter. The Bode Plotter produces a graph of a circuit’s frequency response. It is capable of measuring a signal’s voltage gain and phase shift. Both gain and phase are plotted against frequency on the screen. The vertical and horizontal scales, F and I, should be preset to display the area of interest on the Bode screen.




For the simulation section let your input signal be 4 V peak-to-peak sinusoid, f = 25-1000 H<sub>Z</sub>, R = 1 kΩ, and C = 1µF.




<h2>Figure 5.3</h2>

<ul>

 <li>Open the Bode Plotter. Set the plotter for a magnitude reading by depressing the Magnitude button. Then depress Log buttons under both the Vertical and Horizontal headings. Set the I and F parameters as needed. See Figure 5.4 below.</li>

 <li>Set up your function generator with the defined inputs and simulate the circuit. Make a printout of the Bode Plotter output. Interpret the output of the plot. Does it show Low Pass or High Pass Filter characteristics?</li>

 <li>Determine the cutoff frequency by moving the cursor line. Position the cursor line by clicking on the left and right arrows. The cursor position is displayed in the windows next to the arrows. Recall the cutoff frequency occurs when the output magnitude is 0.707 (or -3dB), the magnitude of the input. Make a print of the output with the cursor line positioned at the cutoff frequency on the screen.</li>

 <li>Make the necessary changes in settings on the Bode Plotter in order to get Phase characteristic. Depress the Phase button. Then simulate the circuit and make a printout of the output.</li>

</ul>














