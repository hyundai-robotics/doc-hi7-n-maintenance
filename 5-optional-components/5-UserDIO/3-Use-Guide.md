# 5.5.3 사용 가이드
{% hint style="warning" %}
디지털 입력, 디지털 출력 결선 작업 시, 반드시 제어기 전원을 OFF한 상태에서 결선작업 하시기 바랍니다.
{% endhint %}

사용자 DIO모듈, 확장 DIO모듈은 외부 각종 장치들과 디지털 입출력 포트를 이용하여 연계 또는 구성이 가능합니다.

(1) 디지털 입/출력 사양<br>
BD681, BD682 디지털 입력 사양은 동일하며 아래 표와 같습니다.<br>

표 5.5.3-1 BD681 & BD682 디지털 입력 사양
<table>
<thead>
  <tr>
    <th><strong>Items</strong></th>
    <th><strong>Specification</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Inputs per module</td>
    <td>2 x (8 Channels Universal Digital Type)</td>
  </tr>
  <tr>
    <td>Indicators</td>
    <td>16 Green Input State</td>
  </tr>
  <tr>
    <td>ON-state Voltage</td>
    <td>24.0Vdc Nominal, 15.8 ~ 28.3V</td>
  </tr>
  <tr>
    <td>OFF-state Voltage</td>
    <td>7.8Vdc Nominal</td>
  </tr>
  <tr>
    <td>ON-state Current</td>
    <td>4.8mA @24.0Vdc<br>
    5.6mA @28.3Vdc</td>
  </tr>
  <tr>
    <td>Nominal Input Impedance</td>
    <td>5.0 Kohm typical</td>
  </tr>
  <tr>
    <td>Common Type</td>
    <td>2 x (8 Channels / 2 COM)</td>
  </tr>
</tbody>
</table>

BD681 디지털 출력 사양은 아래 표와 같습니다.<br>

표 5.5.3-2 BD681 디지털 출력 사양
<table>
<thead>
  <tr>
    <th><strong>Items</strong></th>
    <th><strong>Specification</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Outputs per module</td>
    <td>2 x (8 Channels) PNP/NPN Type</td>
  </tr>
  <tr>
    <td>Indicators</td>
    <td>16 Green Input State</td>
  </tr>
  <tr>
    <td>Output Voltage Range</td>
    <td>24.0Vdc Nominal, 15.8 ~ 28.3V</td>
  </tr>
  <tr>
    <td>Output Current Rating</td>
    <td>Max. 0.1A Per Channel</td>
  </tr>
  <tr>
    <td>Protection</td>
    <td>Over-Current Protection</td>
  </tr>
  <tr>
    <td>Common Type</td>
    <td>2 x (8 Channels / 2 COM)</td>
  </tr>
</tbody>
</table>

BD682 디지털 출력 사양은 아래 표와 같습니다.<br>

표 5.5.3-3 BD682 디지털 출력 사양
<table>
<thead>
  <tr>
    <th><strong>Items</strong></th>
    <th><strong>Specification</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Outputs per module</td>
    <td>2 x (8 Channels) PNP/NPN Type</td>
  </tr>
  <tr>
    <td>Indicators</td>
    <td>16 Green Input State</td>
  </tr>
  <tr>
    <td>Output Voltage Range</td>
    <td>24.0Vdc Nominal, 15.8 ~ 28.3V</td>
  </tr>
  <tr>
    <td>Output Current Rating</td>
    <td>(1~8channel) Max. 0.1A Per Channel<br>
    (9~16channel) Max. 1.5A Per Channel</td>
  </tr>
  <tr>
    <td>Protection</td>
    <td>Over-Current Protection</td>
  </tr>
  <tr>
    <td>Common Type</td>
    <td>2 x (8 Channels / 2 COM)</td>
  </tr>
</tbody>
</table>

(2) 디지털 입력 결선시<br>
* NPN-TYPE(:Active Low)<BR>
아래 그림의 빨간색은 1~8채널을 나타내고 파란색은 9~16채널을 나타냅니다.<br>
외부 전원 또는 PSM의 전원을 사용할 경우의 전원명은 (+)EX_24V, (-)EX_GND 에 연결합니다.<br>
NPN-TYPE의 경우, BD681 & BD682의 1, 11번핀에 외부 전원 (+)EX_24V를 연결하고 외부 디바이스에 (-)EX_GND를 연결합니다.<br>
외부 디바이스와의 연결은 아래 결선 예를 참조하여 결선합니다.<br>

![](../../_assets/BD681_di_wiring.png)<br>
그림 5.5.3-1 BD681 디지털 입력 NPN-TYPE 사용시 결선도

![](../../_assets/BD682_di_wiring.png)<br>
그림 5.5.3-2 BD682 디지털 입력 NPN-TYPE 사용시 결선도

* PNP-TYPE(:Active High)<br>
아래 그림의 빨간색은 1~8채널을 나타내고 파란색은 9~16채널을 나타냅니다.<br>
외부 전원 또는 PSM의 전원을 사용할 경우의 전원명은 (+)EX_24V, (-)EX_GND 에 연결합니다.<br>
PNP-TYPE의 경우, BD681 & BD682의 1, 11번핀에 외부 전원 (-)EX_GND를 연결하고 외부 디바이스에 (+)EX_24V를 연결합니다.<br>
외부 디바이스와의 연결은 아래 결선 예를 참조하여 결선합니다.<br>

![](../../_assets/BD681_di_wiring_pnp.png)<br>
그림 5.5.3-3 BD681 디지털 입력 PNP-TYPE 사용시 결선도

![](../../_assets/BD682_di_wiring_pnp.png)<br>
그림 5.5.3-4 BD682 디지털 입력 PNP-TYPE 사용시 결선도

(3) 디지털 출력 결선시<br>
* NPN-TYPE(:Active Low)<BR>
아래 그림의 빨간색은 1~8채널을 나타내고 파란색은 9~16채널을 나타냅니다.<br>
외부 전원 또는 PSM의 전원을 사용할 경우의 전원명은 (+)EX_24V, (-)EX_GND 에 연결합니다.<br>
NPN-TYPE의 경우, BD681 & BD682의 1, 11번핀에 외부 전원 (-)EX_GND를 연결하고 외부 디바이스에 (+)EX_24V를 연결합니다.<br>
외부 디바이스와의 연결은 아래 결선 예를 참조하여 결선합니다.<br>

![](../../_assets/BD681_do_wiring_npn.png)<br>
그림 5.5.3-5 BD681 디지털 출력 NPN-TYPE 사용시 결선도

![](../../_assets/BD682_do_wiring_npn.png)<br>
그림 5.5.3-6 BD682 디지털 출력 NPN-TYPE 사용시 결선도

* PNP-TYPE(:Active High)<br>
아래 그림의 빨간색은 1~8채널을 나타내고 파란색은 9~16채널을 나타냅니다.<br>
외부 전원 또는 PSM의 전원을 사용할 경우의 전원명은 (+)EX_24V, (-)EX_GND 에 연결합니다.<br>
PNP-TYPE의 경우, BD681 & BD682의 1, 11번핀에 외부 전원 (+)EX_24V를 연결하고 외부 디바이스에 (-)EX_GND를 연결합니다.<br>
외부 디바이스와의 연결은 아래 결선 예를 참조하여 결선합니다.<br>

![](../../_assets/BD681_do_wiring_pnp.png)<br>
그림 5.5.3-7 BD681 디지털 입력 PNP-TYPE 사용시 결선도

![](../../_assets/BD682_do_wiring_pnp.png)<br>
그림 5.5.3-8 BD682 디지털 입력 PNP-TYPE 사용시 결선도

(4) 디지털 입/출력 결선시 주의사항<br>
* 사례 1<br>
디지털 출력 단자를 용량, 용도 또는 사용 목적에 의해 2단 이상의 제어로 사용하는 경우(아래 그림) 입니다.

![](../../_assets/bd681_bd682_case_one_0.png)<br>
그림 5.5.3-9 BD681 & BD682 디지털 출력 사례1

위와 같이 결선하는 경우, 유도성 부하(Inductive Load) 동작할 경우(OFF시)에 역전압이 필연적으로 발생되고 역전압이 소멸될 수 있는 회로가 구성되어 있지 않아서 역전압에 의해 BD681 또는 BD682에 역전압이 유입되어 Hi7제어기 에러 또는 오동작이 발생될 수 있습니다.<br>

이를 방지하기 위하여 그림 (1) 항목에 역전압 방전을 위한 바리스터 및 다이오드 설계를 하거나 (2) 항목 관련해서 별도의 SMPS를 설계하시기 바랍니다.

![](../../_assets/bd681_bd682_case_one_solution_0.png)<br>
그림 5.5.3-10 BD681 & BD682 디지털 출력 사례1 대책 설계
