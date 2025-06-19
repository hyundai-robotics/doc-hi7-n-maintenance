# 4.3.4.1. H6D6X (Medium-Sized 6 Axes Integrated Drive Module)

The drive module performs a power amplification function that allows the current to flow to the individual phases of the motor according to the current command from the servo board. The six axes integrated drive module can drive six motors at the same time and is configured as follows.

The three-phase current entered from the power supply module is rectified through a diode module and then converted into direct current and stored in a smoothing capacitor. When the motor speed of the robot is decelerated, the electric power generated from the motor will be consumed through IGBT and resistors. The relevant configuration is as follows. 

Table 4-14 Configuration of H6D6X (Medium-Sized 6 Axes Integrated Drive Module)


<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD651<br>(Power Board)</td>
    <td>Gate drive circuit</td>
    <td>Generates the IPM gate signal</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Transmit the gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td>Regenerative control</td>
    <td>Drives the IGBT when the PN voltage rises</td>
  </tr>
  <tr>
    <td>Error detection part</td>
    <td>Detects the PN overvoltage, regenerative discharge resistor overheating, and PN undervoltage errors</td>
  </tr>
  <tr>
    <td>High voltage capacitor</td>
    <td>Smooths the direct current</td>
  </tr>
  <tr>
    <td rowspan="2">BD652<br>(Iterface Board)</td>
    <td>Sequence interlocking part</td>
    <td>Interlocks between the sequence status and the servo on signal</td>
  </tr>
  <tr>
    <td>Dedicated IO Terminal Blocks</td>
    <td>Reserved IO port inside the controller</td>
  </tr>
  <tr>
    <td rowspan="4">Other parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated from power elements to the outside</td>
  </tr>
  <tr>
    <td>Rectification part</td>
    <td>Rectify the AC input power to generate DC power for driving the motor</td>
  </tr>
  <tr>
    <td>Regenerative IGBT</td>
    <td>Performs regenerative discharge</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>Convert the power for driving a three-phase motor</td>
  </tr>
</tbody>
</table>

■  **Configuration of the Type Number of the Medium-Sized 6 Axes Integrated Drive Module**

![](../../../_assets/중형_6축_일체형_드라이브모듈_형번_구성.png  )

Table 4-15 Type Symbol of the Medium-Sized 6 Axes Integrated Drive Module 

<table>
<tbody>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p><strong>Type symbol</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 Medium-Sized 6 Axes drive module</strong></p></td>
<td><p>H6D6X</p></td>
</tr>
</tbody>
</table>

Table 4-16 Specification of the Medium-Sized 6 Axes Integrated Drive Module

<table>
<thead>
  <tr>
    <th>Configuration</th>
    <th colspan="2">Classification</th>
    <th colspan="2">Application </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">IPM capacity</td>
    <td>3X</td>
    <td>3Y</td>
    <td>HS180, HS220, HH300, HH050</td>
    <td rowspan="2">6 axes integrated </td>
  </tr>
  <tr>
    <td>4X</td>
    <td>2Y</td>
    <td>HC2502B2D, HC2503B2D</td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000~2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January~December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~999</td>
  </tr>
</tbody>
</table>

Table 4-17 Symbols of the IPM of the medium-sized 6 axes drive module 

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>IPM symbol</th>
    <th>IPM Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the medium-sized 6 axes</td>
    <td>X</td>
    <td>(IPM current rating) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM current rating) 75A</td>
  </tr>
   <tr>
    <td>Z</td>
    <td>(IPM current rating) 50A</td>
  </tr>
</tbody>
</table>

Table 4-18 Symbols of the Hall Sensors of the medium-sized 6 axes drive module 

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall sensor symbol (Specification)</th>
    <th>Full-scalecurrent (Im)</th>
    <th>IPM specification<br>(Rated current)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the medium-sized 6 axes</td>
  </tr>
  <tr>
    <td>1 (4V/50A)</td>
    <td>93.75Apeak</td>
    <td rowspan="5">PM100CG1APL065 202G (100A)<br>PM75CG1APL065 202G (75A)<br>PM50CG1APL065 202G (50A)</td>
  </tr>
  <tr>
    <td>2 (4V/25A)</td>
    <td>46.87Apeak</td>
  </tr>
  <tr>
    <td>3 (4V/15A)</td>
    <td>28.12Apeak</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.75Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/ 5A)</td>
    <td>9.37Apeak</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}


![](../../../_assets/그림_4.39_BD651_부품_배치도.png  )

Figure 4.20 Parts Placement Diagram of BD651</br></br>

Table 4-19 Description of the Connectors of BD651

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals</p></td>
<td><p>Board-to-board connectors of the BD652</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>3-phase power input</p></td>
<td><p>CNRST for the electronic module</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of the BD652</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>Regenerative discharge power output</p></td>
<td><p>Regenerative discharge resistor</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>Regenerative discharge resistor overheating detection</p></td>
<td><p>Regenerative discharge resistor temperature sensor</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~3</strong></p></td>
<td><p>Motor drive output for axis 1 to axis 3</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~6</strong></p></td>
<td><p>Motor drive output for axis 4 to axis 6</p></td>
<td><p>CMC2</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>Direct current power for the drive module of the additional axis</p></td>
<td><p>CNPN for the drive module for an optional additional axis.</p></td>
</tr>
<tr class="even">
<td><p><strong>CNFG1</strong></p></td>
<td><p>Frame ground for axis 1 to axis 3</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG2</strong></p></td>
<td><p>Frame ground for axis 4 to axis 6</p></td>
<td><p>CMC2</p></td>
</tr>
</tbody>
</table>

Table 4-20 Description of LEDs of BD651

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status Display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control voltage of the converter part is normal</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on the regenerative discharge is operating</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on when the PN voltage is higher than 42V</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned off when the PN discharge is operating</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4.40_BD652_부품_배치도.png  )

Figure 4.21 Parts Placement Diagram of BD652

Table 4-21 Description of the Connectors of BD652

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>PWM signals and IPM error signals for 8 axes<br>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals for individual axes</p></td>
<td><p>Board-to-board connectors of BD651</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>PWM signal and IPM error signal for the additional axis</p></td>
<td><p>CNPWM of the drive module (BD658 or BD659) of the additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD651</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>Reserved only for the IO terminal block</p></td>
<td><p>Reserved</p></td>
</tr>
</tbody>
</table>

Table 4-22 Description of the LEDs of BD652

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status Display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control power is normal</p></td>
</tr>
</tbody>
</table>
