# 4.3.2.4. Configuration Devices

The figure below shows the location of the configuration(switch) devices on the Servo/Safety Module(BD642).
The table below describes the function of each configuration setting.

![](../../../_assets/BD642_PCB_설정_r1.png)   
Figure 4.3.2.4-1 Configuration Device Layout of the Servo/Safety Module(BD642)

{% hint style="info" %}
The following settings must not be changed by the user.
Refer to this section only when FPGA reprogramming via the JTAG interface is required.
{% endhint %}

Table 4.3.2.4-1 Description of SW1 Configuration Settings(BD642)
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Name</strong></th>
    <th><strong>Setting State</strong></th>
    <th><strong>Description</strong></th>
    <th><strong>Remarks</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">①</td>
    <td rowspan="2">SW1</td>
    <td><img src="../../../_assets/BD642_플래쉬메모리_부팅모드.png" width="100"></td>
    <td>Flash Memory Boot Mode</td>
    <td>Factory default setting</td>
  </tr>
  <tr>
    <td><img src="../../../_assets/BD642_JTAG프로그램_다운로드모드.png" width="100"></td>
    <td>JTAG Program Download Mode</td>
    <td>-</td>
  </tr>
</table>
</tbody>

