# 5.4.3. Indicator Devices

(1) Board TOP-side Indicators   

The following figure shows the location of the indicator LEDs on the Option Safety IO Module(BD680). The table below describes the meaning of each indicator.

![](../../_assets/BD680_PCB_상태.png)   
Figure 5.4.3-1 Layout of indicator LEDs on the Option Safety IO Module(BD680)

Table 5.4.3-1 Indicator description of the Option Safety IO Module(BD680)
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Name</strong></th>
    <th><strong>Indication</strong></th>
    <th><strong>Color</strong></th>
    <th><strong>Normal Status</strong></th>
    <th><strong>Abnormal / Action</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)</td>
    <td>LED1</td>
    <td>Safety Output Channel A Status</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: LED off
      <br>Cause: A channel input power abnormal
      <br>Action 1: Check A-channel input power(24V)
      <br>Action 2: Check fuse(FS1)
    </td>
  </tr>
  <tr>
    <td>(2)</td>
    <td>LED2</td>
    <td>Safety Output Channel B Status</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: LED off
      <br>Cause: B channel input power abnormal
      <br>Action 1: Check B channel input power(24V)
      <br>Action 2: Check fuse(FS2)
    </td>
</table>
</tbody>

(2) Front Panel Indicators   

The following figure shows the front panel indicators of the Option Safety I/O Module(BD680). The table below describes the function and meaning of each indicator.

![](../../_assets/BD680_전면표시장치.png)   
Figure 5.4.3-2 Layout of Front Panel Indicators–Option Safety I/O Module(BD680)   

Table 5.4.3-2 Front Panel Indicator Description–Option Safety I/O Module(BD680) 
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Name</strong></th>
    <th><strong>Indication</strong></th>
    <th><strong>Color</strong></th>
    <th><strong>Display Status</strong></th>
    <th><strong>Description / Action</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)</td>
    <td>SW1</td>
    <td></td>
    <td></td>
    <td></td>
    <td>Reserved</td>
  </tr>
  <tr>
    <td rowspan="2">(2)</td>
    <td>A_SOx<br>
        (x=1~8)</td>
    <td>A-Channel Safety Output x status</td>
    <td rowspan="2">GREEN</td>
    <td rowspan="2">ON<br>OFF</td>
    <td rowspan="2">Safety output x of each channel is ON.<br>
                    Safety output x of each channel is OFF.</td>
  </tr>
  <tr>
    <td>B_SOx<br>
        (x=1~8)</td>
    <td>B-Channel Safety Output x status</td>
  </tr>

  <tr>
    <td rowspan="2">(3)</td>
    <td>A_SIx<br>
        (x=1~8)</td>
    <td>A-Channel Safety Input x status</td>
    <td rowspan="2">GREEN </td>
    <td rowspan="2">ON<br>OFF</td>
    <td rowspan="2">Safety input x of each channel is ON.<br>
                    Safety input x of each channel is OFF.</td>
  </tr>
  <tr>
    <td>B_SIx<br>
        (x=1~8)</td>
    <td>B-Channel Safety Input x status</td>
  </tr>
</table>
</tbody>
