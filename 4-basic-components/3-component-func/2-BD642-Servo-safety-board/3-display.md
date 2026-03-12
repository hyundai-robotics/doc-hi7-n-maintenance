# 4.3.2.3. Indicators

(1) Board Top Indicators

The figure below shows the locations of the indicators(LEDs and 7-segment display) on the top side of the Servo/Safety Module(BD642).
The table below describes the function of each indicator.

![](../../../_assets/BD642_PCB_상태.png)   
Figure 4.3.2.3-1 Board Top Indicator Layout of the Servo/Safety Module(BD642)

Table 4.3.2.3-1 Description of Board Top Indicators of the Servo/Safety Module(BD642)   
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Indicator</strong></th>
    <th><strong>Description</strong></th>
    <th><strong>Color</strong></th>
    <th><strong>Normal Status</strong></th>
    <th><strong>Action in Case of Abnormal</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)<br>(2)</td>
    <td>LED1<br>LED2</td>
    <td>Input power limiting function</td>
    <td>RED</td>
    <td>OFF</td>
    <td>
      Symptom: Red LED ON
      <br>Cause: Input voltage under- or over-voltage
      <br>Action: Check the input voltage(24 V)
    </td>
  </tr>
  <tr>
    <td>(3)</td>
    <td>LED3</td>
    <td>External A-channel power</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: Yellow LED OFF
      <br>Cause: Overcurrent in the external A-channel power or incorrect external wiring
      <br>Action: Check fuse (FS2)
    </td>
  </tr>
  <tr>
    <td>(4)</td>
    <td>LED4</td>
    <td>External B-channel power</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: Yellow LED OFF
      <br>Cause: Overcurrent in the external B-channel power or incorrect external wiring
      <br>Action: Check fuse(FS3)
    </td>
  </tr>
  <tr>
    <td>(5)</td>
    <td>LED5</td>
    <td>A-channel MCU power</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: Yellow LED OFF
      <br>Cause: Abnormal A-channel MCU power(3.3V, 1.2V)
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(6)</td>
    <td>LED6</td>
    <td>B-channel MCU power</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: Yellow LED OFF
      <br>Cause: Abnormal B-channel MCU power(3.3V, 1.2V)
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(7)</td>
    <td>LED7</td>
    <td>A-channel MCU status indicator</td>
    <td>RED
      <br>GREEN
      <br>BLUE
    </td>
    <td>RGB blinking</td>
    <td>
      Symptom: All LEDs OFF and no blinking
      <br>Cause 1: Abnormal A-channel MCU power(3.3V, 1.2V)
      <br>Cause 2: A-channel MCU program malfunction
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(8)</td>
    <td>LED8</td>
    <td>B-channel MCU status indicator</td>
    <td>RED
      <br>GREEN
      <br>BLUE
    </td>
    <td>RGB blinking</td>
    <td>
      Symptom: All LEDs OFF and no blinking
      <br>Cause 1: Abnormal B-channel MCU power(3.3V, 1.2V)
      <br>Cause 2: B-channel MCU program malfunction
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(9)
      <br>(10)</td>
    <td>LED9
      <br>LED10</td>
    <td>A-channel MCU EtherCAT LINK0 status
      <br>A-channel MCU EtherCAT LINK1 status
    </td>
    <td>GREEN
      <br>GREEN
    </td>
    <td>GREEN blinking
      <br>GREEN blinking
    </td>
    <td>
      Symptom: No blinking
      <br>Cause: A-channel MCU EtherCAT malfunction
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(11)
      <br>(12)</td>
    <td>LED13
      <br>LED14</td>
    <td>FPGA EtherCAT LINK0 status
      <br>FPGA EtherCAT LINK1 status
    </td>
    <td>GREEN
      <br>GREEN
    </td>
    <td>GREEN blinking
      <br>GREEN blinking
    </td>
    <td>
      Symptom: No blinking
      <br>Cause: FPGA EtherCAT malfunction
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(13)</td>
    <td>LED17</td>
    <td>FPGA power status</td>
    <td>YELLOW</td>
    <td>ON</td>
    <td>
      Symptom: Yellow LED OFF
      <br>Cause: Abnormal FPGA power(5V, 3.3V, 1.8V, 1.35V, 1V)
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(14)</td>
    <td>LED18</td>
    <td>FPGA status indicator</td>
    <td>RED
      <br>GREEN
      <br>BLUE</td>
    <td>RGB blinking</td>
    <td>
      Symptom: All LEDs OFF and no blinking
      <br>Cause 1: Abnormal FPGA power (5V, 3.3V, 1.8V, 1.35 V, 1V)
      <br>Cause 2: FPGA program malfunction
      <br>Action: Replace the board(BD642)
    </td>
  </tr>
  <tr>
    <td>(15)</td>
    <td>LED19
      <br>LED21
      <br>LED23
      <br>LED25
      <br>LED20
      <br>LED22
      <br>LED24
      <br>LED26
      </td>
    <td>  Axis 1 brake status
      <br>Axis 2 brake status
      <br>Axis 3 brake status
      <br>Axis 4 brake status
      <br>Axis 5 brake status
      <br>Axis 6 brake status
      <br>Axis 7 brake status
      <br>Axis 8 brake status
      </td>
    <td>ORANGE</td>
    <td>Brake released(ON)
      <br>Brake hold (OFF)
    </td>
    <td>
      Symptom: Brake status mismatch
      <br>ause 1: Abnormal brake power supply
      <br>Cause 2: Harness failure or wiring issue
      <br>Action: Replace the board(BD642)
    </td>
  </tr>

  <tr>
    <td>(16)<br>
        (17)<br>
        (18)
    </td>
    <td>LED27
      <br>LED28
      <br>SEG1
    </td>
    <td>  
    </td>
    <td></td>
    <td></td>
    <td>
      Refer to the following section: Front panel indicators
    </td>
  </tr>

</table>
</tbody>

(2) Front Panel Indicators
The figure below shows the front panel indicators of the Servo/Safety Module(BD642). The table below describes the function of each indicator.

![](../../../_assets/BD642_전면표시장치.png)   
Figure 4.3.2.3-2 Front Panel Indicator Layout of the Servo/Safety Module(BD642)

Table 4.3.2.3-2 Description of Front Panel Indicators of the Servo/Safety Module(BD642)
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>Indicator</strong></th>
    <th><strong>Description</strong></th>
    <th><strong>Color</strong></th>
    <th><strong>Status</strong></th>
    <th><strong>Status Description</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">(1)</td>
    <td>A_SO1</td>
    <td>A-channel Safety Output 1 status indicator</td>
    <td rowspan="2">GREEN </td>
    <td rowspan="2">ON<br>OFF</td>
    <td rowspan="2">Safety Output 1 ON state for the A-channel<br>
                    Safety Output 1 OFF state for the A-channel</td>
  </tr>
  <tr>
    <td>B_SO1</td>
    <td>Safety Output 1 ON state for the B-channel</td>
  </tr>
  <tr>
    <td rowspan="2">(2)</td>
    <td>A_SIx<br>
        (x=1~4)</td>
    <td>A-channel Safety Input x status indicator</td>
    <td rowspan="2">GREEN</td>
    <td rowspan="2">ON<br>OFF</td>
    <td rowspan="2">Safety Input x ON state for the A-channel<br>
                    Safety Input x OFF state for the A-channel</td>
  </tr>
  <tr>
    <td>B_SIn<br>
        (n=1~4)</td>
    <td>B-channel Safety Input n status indicator</td>
  </tr>

  <tr>
    <td rowspan="10">(3)</td>
    <td>LED27 (1)</td>
    <td>LED27 (1) indicator</td>
    <td rowspan="5">GREEN</td>
    <td>
    <td> LED27 (1) MCU_A MOD</td>
  </tr>
  <tr>
    <td>LED27 (2)</td>
    <td>LED27 (2) indicator</td>
    <td>
    <td>LED27 (2) MCU_B MOD</td>
  </tr>
  <tr>
    <td>LED27 (3)</td>
    <td>LED27 (3) indicator</td>
    <td>
    <td>LED27 (3) ZYNQ MOD</td>
  </tr>
  <tr>
    <td>LED27 (4)</td>
    <td>LED27 (4) indicator</td>
    <td>
    <td>LED27 (4) DSP_RUN</td>
  </tr>
  <tr>
    <td>LED27 (5)</td>
    <td>LED27 (5) indicator</td>
    <td>
    <td>LED27 (5) ZYNQ_RUN</td>
  </tr>
  <tr>
    <td>LED28 (1)</td>
    <td>LED28 (1) indicator</td>
    <td rowspan="5">RED</td>
    <td>
    <td>LED28 (1) MCU_A STA</td>
  </tr>
  <tr>
    <td>LED28 (2)</td>
    <td>LED28 (2) indicator</td>
    <td>
    <td>LED28 (2) MCU_B STA</td>
  </tr>
  <tr>
    <td>LED28 (3)</td>
    <td>LED28 (3) indicator</td>
    <td>
    <td>LED28 (3) ZYNQ STA</td>
  </tr>
  <tr>
    <td>LED28 (4)</td>
    <td>LED28 (4) indicator</td>
    <td>
    <td>LED28 (4) DSP ERR</td>
  </tr>
  <tr>
    <td>LED28 (5)</td>
    <td>LED28 (5) indicator</td>
    <td>
    <td>LED28 (5) ZYNQ ERR</td>
  </tr>
  <tr>
    <td>(4)</td>
    <td>SEG1</td>
    <td>BD642 board status indicator</td>
    <td rowspan="2">RED </td>
    <td>             </td>
    <td>Displays the boot status</td>
  </tr>
</table>

Table 4.3.2.3-3 Description of Front LED Status(BD642)
![](../../../_assets/표_4_3_2_3_LED_상태표시.png)  


![](../../../_assets/그림_4_3_2_3_Segment_상태표시_r1.png)  
Figure 4.3.2.3-3 Segment Status Indication
</tbody>