# 4.3.4.2. H6D6A (Small-Sized 6 Axes Integrated Drive Module)

The drive module performs a power amplification function that allows the current to flow to individual phases of the motor according to the current command from the servo board. The six axes integrated drive module can drive six motors at the same time and is configured as follows.

The three-phase current entered from the power supply module is rectified through a diode module and then converted into direct current and stored in a smoothing capacitor. When the motor speed of the robot is decelerated, the electric power generated from the motor will be consumed through IGBT and resistors. The relevant configuration is as follows.


Table 4-23 Configuration of H6D6A (Small-Sized 6 Axes Integrated Drive Module)

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Components</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD653<br>(Power Board)</td>
    <td>Gate drive circuit</td>
    <td>Generates the IPM gate signal</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Generates the gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td>Regenerative control</td>
    <td>Turn on the IGBT when the PN voltage rises</td>
  </tr>
  <tr>
    <td>Error detection part</td>
    <td>Detects the overvoltage, regenerative resistor overheating, and undervoltage errors</td>
  </tr>
  <tr>
    <td>High voltage capacitor</td>
    <td>Smooths the direct current</td>
  </tr>
  <tr>
    <td rowspan="2">BD654<br>(Iterface Board)</td>
    <td>Sequence interlocking part</td>
    <td>Interlocks between the sequence status and the servo on signal</td>
  </tr>
  <tr>
    <td>Dedicated IO Terminal Blocks</td>
    <td>Reserved IO port inside the controller</td>
  </tr>
  <tr>
    <td rowspan="4">Other Parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated in power elements to the outside</td>
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

{% hint style="info" %}
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}

■  **Configuration of the Type Number of the Small-Sized 6 Axes Integrated Drive Module**


![](../../../_assets/소형_6축_일체형_드라이브모듈_형번_구성.png  )

Table 4-24 Type Symbol of the Small-Sized 6 Axes Integrated Drive Module

<table>
<tbody>
<tr class="odd">
<td><p><strong>Category </strong></p></td>
<td><p><strong>Type symbol</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 Small-Sized 6 Axes drive module</strong></p></td>
<td><p>H6D6A</p></td>
</tr>
</tbody>
</table>

Table 4-25 Specification of the Small-Sized 6 Axes Integrated Drive Module

<table>
<thead>
  <tr>
    <th>Configuration</th>
    <th colspan="2">Classification</th>
    <th colspan="2">Application</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>IPM capacity</td>
    <td>3A</td>
    <td>3D</td>
    <td>HA006B, HH020</td>
    <td>6 axes integrated </td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000-2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January-December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~999</td>
  </tr>
</tbody>
</table>

Table 4-26 Capacity of the Small-Sized IPM

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
    <td rowspan="7">Drive module of the small-sized 6 axes</td>
    <td>A</td>
    <td>(IPM allowable current rating) 30A</td>
  </tr>
  <tr>
    <td>D</td>
    <td>(IPM allowable current rating) 10A</td>
  </tr>
</tbody>
</table>

Table 4-27 Symbols of the Hall Sensors of the Small-Sized IPM

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall sensor symbol (Specification)</th>
    <th>Full-scale current (Im)</th>
    <th>IPM specification (Allowable current rating)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">Drive module of the small-sized 6 axes</td>
    <td>3 (4V/15A)</td>
    <td>27.27Apeak</td>
    <td rowspan="2">6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.18Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/5A)</td>
    <td>9.19Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>6 (4V/3A)</td>
    <td>5.45Apeak</td>
  </tr>
  <tr>
    <td>7 (4V/6A)</td>
    <td>10.91Apeak</td>
    <td>6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>8 (4V/2A)</td>
    <td>3.64Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>9 (4V/1A)</td>
    <td>1.82Apeak</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}

![](../../../_assets/그림_4_24_BD653V60_부품_배치도.png  )

Figure 4.22 Parts Placement Diagram of BD653V60 

Table 4-28 Description of the Connectors of BD653

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
<td><p>Board-to-board connectors of BD654</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>3-phase power input</p></td>
<td><p>CNRST for the electronic module</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD654</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>Regenerative discharge power output </p></td>
<td><p>Regenerative discharge resistor</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>Regenerative discharge resistor overheating detection</p></td>
<td><p>Regenerative discharge resistor temperature sensor</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~6</strong></p></td>
<td><p>Motor drive output</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>Direct current for the drive module of the additional axis</p></td>
<td><p>CNPN for the drive module for an optional additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG1, CNFG4</strong></p></td>
<td><p>Frame ground for motors</p></td>
<td><p>CMC1</p></td>
</tr>
</tbody>
</table>

Table 4-29 Description of the LEDs of BD653

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status display</strong></p></td>
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
<td><p>Will be turned off when the PN discharge operation starts</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4_25_BD654V60_부품_배치도.png  )

Figure 4.23 Parts Placement Diagram of BD654</br></br>

Table 4-30 Description of the Connectors of BD654

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
<td><p>Board-to-board connectors of BD653</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>PWM signal and IPM error signal for the additional axis</p></td>
<td><p>CNPWM of the drive module (BD 658 or BD 659) of the additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD653</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>Reserved only IO terminal block</p></td>
<td><p>Reserved</p></td>
</tr>
</tbody>
</table>

Table 4-31 Description of the LEDs of BD654

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
