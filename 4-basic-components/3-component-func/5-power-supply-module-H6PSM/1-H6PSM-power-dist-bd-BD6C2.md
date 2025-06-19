# 4.3.5.1. H6PSM and Power Distribution Board (BD6C2) 

The H6PSM (Hi6-N controller power supply module) module is responsible for the opening and closing and distribution of various power supplied to the controller. The following figures show the interior and exterior of the electrical module with diverse connectors and fuses.

![](../../../_assets/그림_4.45_H6PSM(Hi6-N_제어기_전원공급모듈)_외부.png  )

Figure 4.26 Exterior of H6PSM (Hi6-N Controller Power Supply Module)

The following figure shows the power system diagram for the AC control power related to the opening and closing of the 3-phase AC power for the motor power, the generation of the brake power, and the driving of the fan. The diagram in the figure also shows the power distribution, such as the SMPS power for the DC power supply to the control module. A circuit breaker (CP) or fuse is connected to each power to protect individual circuits against overcurrent.

![](../../../_assets/그림_4.47_Hi6-N_제어기의_전원계통.png  )

Figure 4.27 Power System of the Hi6-N Controller</br></br>

Table 4-39 Types and Usage of the Fuses of the Electronic Module 

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>F1, F2</td>
    <td>Overcurrent protection fuse for the cooling fan power (AC220V)</td>
    <td>AC220V 5A</td>
  </tr>
  <tr>
    <td>F3, F4</td>
    <td>Overcurrent protection fuse for the CMSMPS power (AC220V) </td>
    <td>AC220V 5A</td>
  </tr>
  <tr>
    <td>F5, F6</td>
    <td>Overcurrent protection fuse for the BKSMPS power (AC220V) </td>
    <td>AC220V 5A</td>
  </tr>
</tbody>
</table>
