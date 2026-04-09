# 4.3. Functions of the Individual Components

Table 4-2 Summary of Functions of the Individual Components
<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">Control module</td>
    <td>Main control module(H6COM-T)</td>
    <td>- Recording the record points and calculating the operation paths<br>- Preservation of the programs and robot integers<br>- Teach pendant(T/P) communication<br>- Connection of the LAN, USB, and the serial (RS232) communication</td>
  </tr>
  <tr>
    <td>Servo board(BD642)</td>
    <td>- DSP for servo control<br>- Encoder connection (Serial I/F)<br>- Open/close outputs for the servo motor<br>- Function of Functional Safety<br> - Sequence Control<br>- System I/O<br>- Circuit of Safety-Chain</td>    
  </tr>
  <tr>
    <td>Backplane Board (BD604)</td>
    <td>- Control power supply per board<br>- AMP signal connection with Servo Safety Board(BD642)<br>- Precharge/FAN relay operation signal transmission</td></td>
  </tr>
  <tr>
    <td>Drive module<br>(Drive Module)</td>
    <td>Large/Medium-sized 6axes: H6D6X<br>Small-sized 6axes: H6D6A<br>Additional axis: H6D1X, H6D1Z</td>
    <td>- Generation of the motor drive power<br>- Regenerative discharge<br>- Servo motor power amplification circuit<br>- Various error outputs</td>
  </tr>
  <tr>
    <td>T/P<br>(Teach Pendant)</td>
    <td>TP630</td>
    <td>- Display of various information (LCD)<br>- Button inputs and switch inputs (function/jog, etc.)<br>- Emergency stop, enable, and T/P On/Off inputs</td>
  </tr>
  <tr>
    <td>Cooling device</td>
    <td>Fan</td>
    <td>- Air circulation inside the panel<br>- Cooling of the drive module</td>
  </tr>
  <tr>
    <td>Power supply module</td>
    <td>H6PSM</td>
    <td>- Opening/closing of the motor drive power<br>- Distribution of various power</td>
  </tr>
</tbody>
</table>

※ For the types of components of each controller, refer to “2.1 Details of Specifications of Each Controller Model.” 

![](../../_assets/그림_4_3_구성품%20위치.png)<br>
Figure 4.7 Components of the Control module<br>
