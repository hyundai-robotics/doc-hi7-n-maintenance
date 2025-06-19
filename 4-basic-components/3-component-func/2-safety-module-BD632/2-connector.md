# 4.3.2.2. 커넥터

다음 그림은 BD632(Safety IO Module)에 있는 각종 커넥터의 위치와 용도를 나타낸 것입니다.

![](../../../_assets/그림_4.24_BD632(Safety_IO_Board)의_커넥터_및_스위치_배치.png  )

그림 4.7 BD632(Safety IO Board)의 커넥터 및 스위치 배치

표 4-4 BD632(Safety IO Board)커넥터 종류 및 용도

<table>
<tbody>
<tr class="odd">
<td><p><strong>번호</strong></p></td>
<td><p><strong>명칭</strong></p></td>
<td><p><strong>용도</strong></p></td>
<td><p><strong>외부장치접속</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS1</strong></p></td>
<td><p>SMPS DC24V전원 공급</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="odd">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS2</strong></p></td>
<td><p>SMPS DC24V전원 공급</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="even">
<td><p><strong>B</strong></p></td>
<td><p><strong>CNTP</strong></p></td>
<td><p>티칭 펜던트의 전원, 비상정지, 모드스위치, 인에이블링 스위치
입력</p></td>
<td><p>티칭펜던트</p></td>
</tr>
<tr class="odd">
<td><p><strong>C</strong></p></td>
<td><p><strong>CNMC</strong></p></td>
<td><p>MC(Magnet Contact) 입출력신호 접속</p></td>
<td><p>MC(Magnet Contact)</p></td>
</tr>
<tr class="even">
<td><p><strong>D</strong></p></td>
<td><p><strong>CNLS</strong></p></td>
<td><p>Arm간섭, Over-travel검지용 리밋스위치 입력</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>E</strong></p></td>
<td><p><strong>CNLS7</strong></p></td>
<td><p>부가 7축 Over-travel검지용 리밋스위치 입력</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>F</strong></p></td>
<td><p><strong>CNLS8</strong></p></td>
<td><p>부가 8축 Over-travel검지용 리밋스위치 입력</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>G</strong></p></td>
<td><p><strong>CNSV</strong></p></td>
<td><p>서보시퀀스보드(BD640) I/F</p>
<p>(모터온오프, 피드백, 서보시퀀스보드 상태, 안전보드 상태)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>H</strong></p></td>
<td><p><strong>CNEMSW</strong></p></td>
<td><p>OP(Operational Panel)의 비상정지 입력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>I</strong></p></td>
<td><p><strong>CNOPSW</strong></p></td>
<td><p>OP(Operational Panel)의 모드스위치, 키입력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="even">
<td><p><strong>J</strong></p></td>
<td><p><strong>CNOPLP</strong></p></td>
<td><p>OP(Operational Panel)의 LAMP 출력</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>K</strong></p></td>
<td><p><strong>TBEM</strong></p></td>
<td><p>외부 안전 입력</p>
<p>(비상정지, AUTO모드 안전가드1, AUTO모드 안전가드2, 일반안전가드
입력)</p></td>
<td><p>유저 IO</p></td>
</tr>
<tr class="even">
<td><p><strong>L</strong></p></td>
<td><p><strong>EXMON</strong></p></td>
<td><p>외부모터온</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>M</strong></p></td>
<td><p><strong>TBPLC</strong></p></td>
<td><p>안전 PLC용 안전신호 접속</p></td>
<td><p>Safety PLC</p></td>
</tr>
<tr class="even">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ1</strong></p></td>
<td><p>이더켓 통신 연결(INPUT)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ2</strong></p></td>
<td><p>이더켓 통신 연결(OUTPUT)</p></td>
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
<td><p>OP INSTALL 입력(enable, disable)</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Q</strong></p></td>
<td><p><strong>A_JTAG1,B_JTAG1</strong></p></td>
<td><p>J-TAG커넥터(프로그램 다운로드)</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>R</strong></p></td>
<td><p><strong>SW7</strong></p></td>
<td><p>ES, SG  입력(enable, disable)</p></td>
<td></td>
</tr>
</tbody>
</table>

\(1\) BD632 외부안전신호용 터미널블럭: TBEM

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

그림 4.8 BD632(Safety IO Board) TBEM

{% hint style="info" %}
안전관련 입력을 연결하여 활성화를 한경우 반드시 “1.11. 로봇 조작시 안전대책”을 참고하여 기능 정상 동작 여부를 확인하여 주십시오.
{% endhint %}

표 4-5 BD632(Safety IO Board) TBEM 설명

<table>
<thead>
  <tr>
    <th>단자번호</th>
    <th>단자명</th>
    <th>용도</th>
    <th>기타</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>16</td>
    <td>SGG1+</td>
    <td rowspan="2">일반안전가드 체인1입력</td>
    <td rowspan="2">일반안전가드 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SGG2+</td>
    <td rowspan="2">일반안전가드 체인2입력</td>
    <td rowspan="2">일반안전가드 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>7</td>
    <td>SGG2-</td>
  </tr>
  <tr>
    <td>14</td>
    <td>SGA11+</td>
    <td rowspan="2">자동안전가드1 체인1입력</td>
    <td rowspan="2">자동안전가드1 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>6</td>
    <td>SGA11-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>SGA21+</td>
    <td rowspan="2">자동안전가드1 체인2입력</td>
    <td rowspan="2">자동안전가드1 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>5</td>
    <td>SGA21-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>SGA12+</td>
    <td rowspan="2">자동안전가드2 체인1입력</td>
    <td rowspan="2">자동안전가드2 체인1 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SGA12-</td>
  </tr>
  <tr>
    <td>11</td>
    <td>SGA22+</td>
    <td rowspan="2">자동안전가드2 체인2입력</td>
    <td rowspan="2">자동안전가드2 체인2 을 사용하지 않을 경우 쇼트시킵니다</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SGA22-</td>
  </tr>
  <tr>
    <td>10</td>
    <td>EMEX1+</td>
    <td rowspan="2">외부비상정지 체인1 입력</td>
    <td rowspan="2">외부장치의 비상정지 체인1을 사용하지 않을 경우 쇼트시킵니다.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
    <td>9</td>
    <td>EMEX2+</td>
    <td rowspan="2">외부비상정지 체인2 입력</td>
    <td rowspan="2">외부장치의 비상정지 체인2을 사용하지 않을 경우 쇼트시킵니다.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
</tbody>
</table>


\(2\)   BD632 안전 PLC 연결용 터미널블럭: TBPLC

![](../../../_assets/그림_4.26_BD632(Safety_IO_Board)_TBPLC.png  )

그림 4.9 BD632(Safety IO Board) TBPLC

![](../../../_assets/4.3.2.2._커넥터(Hi6)-경고.png  )

표 4-6 BD632(Safety IO Board) TBPLC 설명

<table>
<thead>
  <tr>
    <th>단자번호</th>
    <th>단자명</th>
    <th>용도</th>
    <th>기타</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>12</td>
    <td>PLC_P</td>
    <td>안전 PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>6</td>
    <td>PLC_G</td>
    <td>안전 PLC GND</td>
    <td>SG/ES신호의 Common역할을 함.</td>
  </tr>
  <tr>
    <td>11</td>
    <td>PLC_TO1</td>
    <td>Safety IO의 모니터링용 출력에 대한 입력단자</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>Safety IO의 T0에 대한 피드백신호 출력</td>
  </tr>
  <tr>
    <td>10</td>
    <td>SG1</td>
    <td>안전PLC로부터의 안전가드 입력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>안전PLC로부터의 안전가드 입력 체인 2</td>
  </tr>
  <tr>
    <td>9</td>
    <td>ES1</td>
    <td>안전PLC로부터의 비상정지 입력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>안전PLC로부터의 비상정지 입력 체인 2</td>
  </tr>
  <tr>
    <td>8</td>
    <td>EMOUT11+</td>
    <td rowspan="2">내부 비상정지 출력 체인 1</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>7</td>
    <td>EMOUT21+</td>
    <td rowspan="2">내부 비상정지 출력 체인 2</td>
    <td rowspan="2">PNP출력 타입만 적용가능</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>
</tbody>
</table>

\(3\)    외부 모터온 커넥터

![](../../../_assets/외부_모터온_커넥터.png  )

표 4-7 BD632 외부 모터온 스위치

<table>
<tbody>
<tr class="odd">
<td><p><strong>단자번호</strong></p></td>
<td><p><strong>단자명</strong></p></td>
<td><p><strong>용도</strong></p></td>
<td><p><strong>기타</strong></p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>EXMON_C1+</p></td>
<td><p>외부 모터온(접점type)</p></td>
<td><p>사용하지 않을 경우 EXMON_C1+와<br>EXMON_C1-를 쇼트시킵니다.</p></td>
</tr>
<tr class="odd">
<td><p>1</p></td>
<td><p>EXMON_C1-</p></td>
<td><p>외부 모터온(접점type)</p></td>
<td><p>사용하지 않을 경우 EXMON_C1+와<br>EXMON_C1-를 쇼트시킵니다.</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p>EXMON_C2+</p></td>
<td><p>외부 모터온(접점type)</p></td>
<td><p>사용하지 않을 경우 EXMON_C2+와<br>EXMON_C2-를 쇼트시킵니다.</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>EXMON_C2-</p></td>
<td><p>외부 모터온(접점type)</p></td>
<td><p>사용하지 않을 경우 EXMON_C2+와<br>EXMON_C2-를 쇼트시킵니다.</p></td>
</tr>
</tbody>
</table>
