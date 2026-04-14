# 4.3.2.2. Connectors

The figure below shows the locations of the connectors required for external connections of the Servo/Safety Module(BD642). The table below describes the name and function of each connector.

![](../../../_assets/BD642_PCB_커넥터명.png)<br>
Figure 4.3.2.2-1 Connector Layout of the Servo/Safety Module(BD642)

Table 4.3.2.2-1 Connector Names, Functions, and External Connection Devices of the Servo/Safety Module(BD642)
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Connector</strong></th>
    <th><strong>Function</strong></th>
    <th><strong>Ext. Device</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>A</td>
    <td>J4</td>
    <td>EtherCAT Communication interface</td>
    <td>H6COM/LAN4</td>
  </tr>
  <tr>
    <td>B</td>
    <td>CNSO1</td>
    <td>Safety Output Terminal</td>
    <td>External Device</td>
  </tr>
  <tr>
    <td>C</td>
    <td>CNSI1</td>
    <td>Safety Input Terminal</td>
    <td>External Device</td>
  </tr>
  <tr>
    <td>D</td>
    <td>CNEM</td>
    <td>External emergency switch interface</td>
    <td>Emergency switch</td>
  </tr>
  <tr>
    <td>E</td>
    <td>CNTP</td>
    <td>Teach pendant interface (power, emergency stop, mode switch, enable switch)</td>
    <td>Connector CNRTP</td>
  </tr>
  <tr>
    <td>F</td>
    <td>CNMC</td>
    <td>Magnet Contact I/O signal</td>
    <td>Power Distribution Board(BD6C3) CNMC</td>
  </tr>
  <tr>
    <td>G</td>
    <td>CNEN8</td>
    <td>Auxiliary axis 8 encoder signal</td>
    <td>Connector AEC2</td>
  </tr>
  <tr>
    <td>H</td>
    <td>CNEN7</td>
    <td>Auxiliary axis 7 encoder signal</td>
    <td>Connector AEC1</td>
  </tr>
  <tr>
    <td>J</td>
    <td>CNEN46</td>
    <td>Axis 4~6 encoder signals</td>
    <td>Connector CEC1</td>
  </tr>
  <tr>
    <td>K</td>
    <td>CNEN13</td>
    <td>Axis 1~3 encoder signals</td>
    <td>Connector CEC1</td>
  </tr>
  <tr>
    <td>M</td>
    <td>CNBRK78</td>
    <td>Auxiliary axis 7, 8 brake signals</td>
    <td>Connectors AMC1, AMC2</td>
  </tr>
  <tr>
    <td>N</td>
    <td>CNBRK16</td>
    <td>Axis 1~6 brake signals</td>
    <td>Connectors CMC1, CMC2</td>
  </tr>
  <tr>
    <td>P</td>
    <td>J12</td>
    <td>Brake power supply</td>
    <td>Power Distribution Board(BD6C3) CNOBK</td>
  </tr>
  <tr>
    <td>Q</td>
    <td>CNBS1</td>
    <td>Drive interface signals</td>
    <td>Backplane Board(BD604) CNBS1</td>
  </tr>
  <tr>
    <td>R</td>
    <td>CNBS2</td>
    <td>Drive interface signals</td>
    <td>Backplane Board(BD604) CNBS2</td>
  </tr>
</tbody>
</table>
      
{% hint style="info" %}
If safety-related inputs are connected and activated, refer to “1.11 Safety Precautions for Robot Operation” and verify that the functions operate correctly.
{% endhint %}
