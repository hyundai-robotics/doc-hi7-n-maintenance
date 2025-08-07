# 4.3.2.4. 설정장치

![](../../../_assets/그림_4.31_BD632(Safety_IO_Board)의_설정장치_설명.png  )

그림 4.11 BD632(Safety IO Board)의 설정장치 설명

{% hint style="warning" %}
안전관련 입력을 연결하여 활성화를 한경우 반드시 “1.11. 로봇 조작시 안전대책”을 참고하여 기능 정상 동작 여부를 확인하여 주십시오.
{% endhint %}

표 4-9 BD632(Safety IO Module)의 SW1, SW2, SW3, SW4, SW7 설정장치 설명


<table>
<thead>
  <tr>
    <th colspan="2">스위치</th>
    <th rowspan="2">SW1</th>
    <th rowspan="2">SW2</th>
    <th rowspan="2">SW3</th>
    <th rowspan="2">SW4</th>
    <th rowspan="2">SW7</th>
  </tr>
  <tr>
    <th colspan="2">번호</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">용도</td>
    <td>OP(Operational Panel) 설치 여부 설정 (체인1)</td>
    <td>OP(Operational Panel) 설치 여부 설정 (체인2)</td>
    <td>OVT6,LS, OVT7(부가축), OVT8(확장축) 설치 여부 설정(체인1)</td>
    <td>OVT6, LS, OVT7(부가축), OVT8(확장축) 설치 여부 설정(체인2)</td>
    <td>PLC ES, SG 설치 여부 설정<br>(체인1, 체인2)</td>
  </tr>
  <tr>
    <td rowspan="2">설정</td>
    <td>OFF</td>
    <td>미설치</td>
    <td>미설치</td>
    <td>1: OVT6 설치<br>2: LS 설치<br>3: OVT7 설치<br>4: OVT8 설치</td>
    <td>1: OVT6 설치<br>2: LS 설치<br>3: OVT7 설치<br>4: OVT8 설치</td>
    <td>1: ES설치(체인1)<br>2: SG설치(체인1)<br>3: ES설치(체인2)<br>4: SG설치(체인2)</td>
  </tr>
  <tr>
    <td>ON</td>
    <td>설치</td>
    <td>설치</td>
    <td>1: OVT6 미설치<br>2: LS 미설치<br>3: OVT7 미설치<br>4: OVT8 미설치</td>
    <td>1: OVT6 미설치<br>2: LS 미설치<br>3: OVT7 미설치<br>4: OVT8 미설치</td>
    <td>1: ES미설치(체인1)<br>2: SG미설치(체인1)<br>3: ES미설치(체인2)<br>4: SG미설치(체인2)</td>
  </tr>
  <tr>
    <td colspan="2">출고시</td>
    <td>미설치(OFF)</td>
    <td>미설치(OFF)</td>
    <td>1: OFF<br>2: OFF<br>3: On(부가축OVT연결시 OFF)<br>4: On(확장축OVT연결시 OFF)</td>
    <td>1: OFF<br>2: OFF<br>3: On(부가축OVT연결시 OFF)<br>4: On(확장축OVT연결시 OFF)</td>
    <td>1: ES미설치(체인1)<br>2: SG미설치(체인1)<br>3: ES미설치(체인2)<br>4: SG미설치(체인2)</td>
  </tr>
</tbody>
</table>
