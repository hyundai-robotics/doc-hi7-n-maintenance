# 4.3.5.2. Connectors of BD6C3

The connector layout of the electrical board (BD6C3) is shown in the following figure. The function and connection device for each are listed in Table 4-40. 

![](../../../_assets/그림_4.28_전장보드(BD6C3)의_커넥터.png  )<br>
Figure 4.36 Connectors of the Electronic Board (BD6C3)<br>

Table 4-36 Type and Function of BD6C3 Connector 
<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Function</th>
    <th>Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNAC1</td>
    <td>3-phase power input for control</td>
    <td>3-phase 220V</td>
  </tr>
    <tr>
    <td>CNAC2</td>
    <td>3-phase power output for control of 16 axes or more</td>
    <td>3-phase 220V</td>
  </tr>
   <tr>
    <td>CNPR1</td>
    <td>Inrush current limiting circuit input</td>
    <td>3-phase 220V, MC1 input terminal</td>
  </tr>
  <tr>
    <td>CNPR2</td>
    <td>Inrush current limiting circuit output</td>
    <td>3-phase 220V, MC2 output terminal</td>
  </tr>
  <tr>
    <td>CNACOUT1</td>
    <td>220 VAC power output 1 for users</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNACOUT2</td>
    <td>220 VAC power output 2 for users</td>
    <td>Single-phase 220V</td>
  </tr>
    <tr>
    <td>CNPFS1</td>
    <td>CMSMPS power failure detection signal output 1</td>
    <td>H6COM DIO</td>
  </tr>
   <tr>
    <td>CNMC</td>
    <td>Contactor control and monitoring</td>
    <td>BD642 CNMC</td>
  </tr>
  <tr>
    <td>CNPRC</td>
    <td>Control and monitoring of inrush current limiting circuit, fan fault and fan power</td>
    <td>BD642 CNPRC</td>
  </tr>
  <tr>
    <td>CNFN1</td>
    <td>DC fan power output for control module</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNFN2~5</td>
    <td>DC fan power output</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOCM</td>
    <td>SMPS 24VDC output for control modules</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOH6COM</td>
    <td>SMPS 24VDC output for H6COMs</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOBK</td>
    <td>SMPS 24VDC output for motor brakes</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNORO</td>
    <td>SMPS 24VDC output for robots</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOUS</td>
    <td>SMPS 24VDC output for users</td>
    <td>24VDC</td>
  </tr>


  <tr>
    <td>CNCMSM</td>
    <td>SMPS 220VAC input for control modules</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNBKSM</td>
    <td>SMPS 220VAC input for motor brakes</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNUSSM</td>
    <td>SMPS 220VAC input for users</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNROSM</td>
    <td>SMPS 220VAC input for robots</td>
    <td>Single-phase 220V</td>
  </tr>

  <tr>
    <td>CNI24CM</td>
    <td>Input for SMPS 24VDC distribution for common modules</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24BK</td>
    <td>Input for SMPS 24VDC distribution for brakes</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24RO</td>
    <td>Input for SMPS 24VDC distribution for robots</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24US</td>
    <td>Input for SMPS 24VDC distribution for users</td>
    <td>24VDC</td>
  </tr>
  
  <tr>
    <td>CNMC1</td>
    <td>Magnetic contactor 1 ON/OFF power input and feedback, and brake control signal control</td>
    <td>MC1</td>
  </tr>
  <tr>
    <td>CNMC2</td>
    <td>Magnetic contactor 2 ON/OFF power input and feedback, and brake control signal control</td>
    <td>MC2</td>
  </tr>
</tbody>
</table>

### 4.3.5.3. BD6C3 LED

The LED layout of the electrical board (BD6C3) is shown in the following figure. The function, connected power, and LED color for each are listed in Table 4-41.

![](../../../_assets/그림_4.29_전장보드(BD6C3)의_LED.png)<br>
Figure 4.37 LEDs of BD6C3<br>

Table 4-37 Types and Functions of BD6C3 LEDs
<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Fuction</th>
    <th>Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>LDFNFLT</td>
    <td>ON when a fault occurs in one or more of FAN 1–5</td>
    <td>FAN Fault, Red</td>
  </tr>
  <tr>
    <td>LEDFAN</td>
    <td>ON when the relay for supplying 24VDC to the fan is ON</td>
    <td>FAN Power Relay, Green</td>
  </tr>
  <tr>
    <td>LEDCM</td>
    <td>ON when SMPS 24VDC for control modules is normally supplied</td>
    <td>CMSMPS, Green</td>
  </tr>
  <tr>
    <td>LEDBK</td>
    <td>ON when SMPS 24VDC for brakes is normally supplied</td>
    <td>BKSMPS, Green</td>
  </tr>
  <tr>
    <td>LEDUS</td>
    <td>ON when SMPS 24VDC for users is normally supplied</td>
    <td>USSMPS, Green</td>
  </tr>
  <tr>
    <td>LEDRO</td>
    <td>ON when SMPS 24VDC for robots is normally supplied</td>
    <td>ROSMPS, Green</td>
  </tr>
  <tr>
    <td>MC1LED</td>
    <td>ON when the ON power for magnetic contactor 1 is normally supplied</td>
    <td>BD642, Green</td>
  </tr>
  <tr>
    <td>MC2LED</td>
    <td>ON when the ON power for magnetic contactor 2 is normally supplied</td>
    <td>BD642, Green</td>
  </tr>
  <tr>
    <td>RYPRC1</td>
    <td>ON inside relay when aprecharging relay ON signal is supplied</td>
    <td>BD604, Green</td>
  </tr>
  <tr>
    <td>RYPRC2</td>
    <td>ON inside relay when a fan power relay ON signal is supplied</td>
    <td>BD604, Green</td>
  </tr>

</tbody>
</table>
