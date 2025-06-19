# 4.3.2.4. Setting Devices

![](../../../_assets/그림_4.31_BD632(Safety_IO_Board)의_설정장치_설명.png  )

Figure 4.11 Description of the Setting Devices of the BD632 (Safety IO Board)

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}


Table 4-9 Description of the SW1, SW2, SW3, SW4 and SW7 setting devices of BD632 (Safety IO Module)


<table>
<thead>
  <tr>
    <th colspan="2">Switch</th>
    <th rowspan="2">SW1</th>
    <th rowspan="2">SW2</th>
    <th rowspan="2">SW3</th>
    <th rowspan="2">SW4</th>
    <th rowspan="2">SW7</th>
  </tr>
  <tr>
    <th colspan="2">number</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">Usage</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 1)</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 2)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 1)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 2)</td>
    <td>Sets whether to install the PLC ES, SG(Chain 1, Chain 2)
</td>
  </tr>
  <tr>
    <td rowspan="2">Contents of setting</td>
    <td>OFF</td>
    <td>Non-installation</td>
    <td>Non-installation</td>
    <td>1: Installation of OVT6</br>2: Installation of LS<br>3: Installation of OVT7</br>4: Installation of OVT8
</td>
    <td>1: Installation of OVT6</br>2: Installation of LS</br>3: Installation of OVT7</br>4: Installation of OVT8</br>
</td>
    <td>1: Installation of ES(Chain 1)</br>2: Installation of SG(Chain 1)</br>3: Installation of ES(Chain 2)</br>4: Installation of SG(Chain 2)</br>
</td>
  </tr>
  <tr>
    <td>ON</td>
    <td>Installation</td>
    <td>Installation</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation of ES(Chain 1)</br>2: No installation of SG(Chain 1)</br>3: No installation of ES(Chain 2)</br>4: No installation of SG(Chain 2)</br>
</td>
  </tr>
  <tr>
    <td colspan="2">Setting when shipped from the factory</td>
    <td>Non-installation (OFF)</td>
    <td>Non-installation (OFF)</td>
    <td>1: OFF</br>2: OFF</br>3: On (OFF when an additional axis OVT is connected)</br>4: On (OFF when an extended axis OVT is connected)</br>
</td>
    <td>1: OFF</br>2: OFF</br>3: On (OFF when an additional axis OVT is connected)</br>4: On (OFF when an extended axis OVT is connected)</br>
</td>
    <td>1: No installation of ES(Chain 1)</br>2: No installation of SG(Chain 1)</br>3: No installation of ES(Chain 2)</br>4: No installation of SG(Chain 2)</br>
</td>
  </tr>
</tbody>
</table>
