# 4.3.2.2. Connectors

The following figure shows the positions and usage of various connectors installed on BD632 (Safety IO Module).

![](../../../_assets/그림_4.24_BD632(Safety_IO_Board)의_커넥터_및_스위치_배치.png  )

Figure 4.7 Placement of the Connectors and Switches of the BD632 (Safety IO Board)</br></br>

Table 4-4 Types and Usage of the Connectors of the BD632 (Safety IO Board)

<table>
<tbody>
<tr class="odd">
<td><p><strong></strong></p></td>
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS1</strong></p></td>
<td><p>SMPS DC24V power supply</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="odd">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS2</strong></p></td>
<td><p>SMPS DC24V power supply</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="even">
<td><p><strong>B</strong></p></td>
<td><p><strong>CNTP</strong></p></td>
<td><p>Inputs of the emergency stop switch, mode switch, and enable switch of the teaching pendant</p></td>
<td><p>Teaching Pendant</p></td>
</tr>
<tr class="odd">
<td><p><strong>C</strong></p></td>
<td><p><strong>CNMC</strong></p></td>
<td><p>Connection of the Magnet Contact (MC) input and output signals</p></td>
<td><p>MC(Magnet Contact)</p></td>
</tr>
<tr class="even">
<td><p><strong>D</strong></p></td>
<td><p><strong>CNLS</strong></p></td>
<td><p>Limit switch input for the detection of arm interference and over-travel</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>E</strong></p></td>
<td><p><strong>CNLS7</strong></p></td>
<td><p>Limit switch input for the detection of the over-travel of the additional axis 7</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>F</strong></p></td>
<td><p><strong>CNLS8</strong></p></td>
<td><p>Limit switch input for the detection of the over-travel of the additional axis 8</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>G</strong></p></td>
<td><p><strong>CNSV</strong></p></td>
<td><p>Servo sequence board (BD640) I/F</p>
<p>(Status related to motor on/off, feedback, the servo sequence board, and the safety board)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>H</strong></p></td>
<td><p><strong>CNEMSW</strong></p></td>
<td><p>Emergency stop input of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>I</strong></p></td>
<td><p><strong>CNOPSW</strong></p></td>
<td><p>Inputs of the mode switch and keys of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="even">
<td><p><strong>J</strong></p></td>
<td><p><strong>CNOPLP</strong></p></td>
<td><p>Lamp output of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>K</strong></p></td>
<td><p><strong>TBEM</strong></p></td>
<td><p>External safety inputs</p>
<p>(Emergency stop, auto mode safety guard 1, auto mode safety guard 2, and general safety guard input)</p></td>
<td><p>User IO</p></td>
</tr>
<tr class="even">
<td><p><strong>L</strong></p></td>
<td><p><strong>EXMON</strong></p></td>
<td><p>External motor on signal input</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>M</strong></p></td>
<td><p><strong>TBPLC</strong></p></td>
<td><p>Connection of the safety PLC safety signals</p></td>
<td><p>Safety PLC</p></td>
</tr>
<tr class="even">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ1</strong></p></td>
<td><p>EtherCat communication connection (INPUT)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ2</strong></p></td>
<td><p>EtherCat communication connection (OUTPUT)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>O</strong></p></td>
<td><p><strong>SW3,SW4</strong></p></td>
<td><p>limit&OVT On/OFF SW</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>P</strong></p></td>
<td><p><strong>SW1,SW2</strong></p></td>
<td><p>OP INSTALL input (enable, disable)</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Q</strong></p></td>
<td><p><strong>A_JTAG1,B_JTAG1</strong></p></td>
<td><p>J-TAG connector (Program download)</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>R</strong></p></td>
<td><p><strong>SW7</strong></p></td>
<td><p>ES, SG input (enable, disable)</p></td>
<td></td>
</tr>
</tbody>
</table>

\(1\) External Safety Signal Terminal Block of the BD632: TBEM

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.8 BD632(Safety IO Board) TBEM

{% hint style="info" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}

Table 4-5 Description of TBEM of the BD632 (Safety IO Board) 

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>16</td>
    <td>SGG1+</td>
    <td rowspan="2">General safety guard chain 1 input</td>
    <td rowspan="2">If the general safety guard chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SGG2+</td>
    <td rowspan="2">General safety guard chain 2 input</td>
    <td rowspan="2">If the general safety guard chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>SGG2-</td>
  </tr>
  <tr>
    <td>14</td>
    <td>SGA11+</td>
    <td rowspan="2">Automatic safety guard 1 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>SGA11-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>SGA21+</td>
    <td rowspan="2">Automatic safety guard 1 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>5</td>
    <td>SGA21-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>SGA12+</td>
    <td rowspan="2">Automatic safety guard 2 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SGA12-</td>
  </tr>
  <tr>
    <td>11</td>
    <td>SGA22+</td>
    <td rowspan="2">Automatic safety guard 2 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SGA22-</td>
  </tr>
  <tr>
    <td>10</td>
    <td>EMEX1+</td>
    <td rowspan="2">External emergency stop chain 1 input</td>
    <td rowspan="2">If the external emergency stop chain 1 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
    <td>9</td>
    <td>EMEX2+</td>
    <td rowspan="2">External emergency stop chain 2 input</td>
    <td rowspan="2">If the external emergency stop chain 2 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
</tbody>
</table>


\(2\) Safety PLC Connection Terminal Block of the BD632: TBPLC

![](../../../_assets/그림_4.26_BD632(Safety_IO_Board)_TBPLC.png  )

Figure 4.9 BD632(Safety IO Board) TBPLC

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}


Table 4-6 Description of TBPLC of BD632 (Safety IO Board)

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>12</td>
    <td>PLC_P</td>
    <td>Safety PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>6</td>
    <td>PLC_G</td>
    <td>Safety PLC GND</td>
    <td>To function as Common for the SG/ES signal </td>
  </tr>
  <tr>
    <td>11</td>
    <td>PLC_TO1</td>
    <td>Input terminal for the monitoring output of the safety IO</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>Feedback signal output for T0 of the safety IO</td>
  </tr>
  <tr>
    <td>10</td>
    <td>SG1</td>
    <td>Chain 1 for the safety guard input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>Chain 2 for the safety guard input from the safety PLC</td>
  </tr>
  <tr>
    <td>9</td>
    <td>ES1</td>
    <td>Chain 1 for the emergency stop input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>Chain 2 for the emergency stop input from the safety PLC</td>
  </tr>
  <tr>
    <td>8</td>
    <td>EMOUT11+</td>
    <td rowspan="2">Internal emergency stop output chain 1</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>7</td>
    <td>EMOUT21+</td>
    <td rowspan="2">Internal emergency stop output chain 2</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>
</tbody>
</table>

\(3\)  External Motor On connecter

![](../../../_assets/외부_모터온_커넥터.png  )

Table 4-7 BD632 external motor on switch 

<table>
<tbody>
<tr class="odd">
<td><p><strong>Terminal no. </strong></p></td>
<td><p><strong>Terminal name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Others</strong></p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>EXMON_C1+</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C1+ should be short-circuited with EXMON_C1-.</p></td>
</tr>
<tr class="odd">
<td><p>1</p></td>
<td><p>EXMON_C1-</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C1+ should be short-circuited with EXMON_C1-.</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p>EXMON_C2+</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C2+ should be short-circuited with EXMON_C2-.</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>EXMON_C2-</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C2+ should be short-circuited with EXMON_C2-.</p></td>
</tr>
</tbody>
</table>
