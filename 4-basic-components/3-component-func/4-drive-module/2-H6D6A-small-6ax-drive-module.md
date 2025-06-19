# 4.3.4.2. H6D6A (소형 6축 일체형 드라이브모듈)

드라이브모듈(Drive Module)은 서보보드로부터의 전류지령에 따라 모터 각 상에 전류를 흘려주는 전력증폭기능을 수행합니다. 6축 일체형 드라이브모듈은 6개의 모터를 동시에 구동시킬 수 있으며, 다음과 같이 구성되어 있습니다.

전원공급모듈로부터 입력되는 3상 전류를 다이오드 모듈로 정류하여 직류로 변화하여 평활용 커패시터에 저장합니다. 로봇의 감속 시에 모터로부터 발생하는 전력은 IGBT와 저항을 통하여 소비하며, 다음과 같이 구성되어 있습니다.

표 4-23 H6D6A (소형 6축 일체형 드라이브모듈)의 구성

<table>
<thead>
  <tr>
    <th colspan="2">구성품</th>
    <th>기능</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD653<br>(Power Board)</td>
    <td>게이트 드라이브 회로</td>
    <td>IPM 게이트 신호 전달</td>
  </tr>
  <tr>
    <td>게이트 전원 모듈</td>
    <td>IPM 게이트 전원 생성</td>
  </tr>
  <tr>
    <td>전류 검출부</td>
    <td>모터에 흐르는 전류를 검출</td>
  </tr>
  <tr>
    <td>회생 제어</td>
    <td>PN전압의 상승 시 IGBT 구동</td>
  </tr>
  <tr>
    <td>에러검출부</td>
    <td>PN 과전압, 회생방전 저항 과열, PN 저전압 에러 검지</td>
  </tr>
  <tr>
    <td>고전압 커패시터</td>
    <td>직류 전원 평활</td>
  </tr>
  <tr>
    <td rowspan="2">BD654<br>(Interface Board)</td>
    <td>시퀀스 연동부</td>
    <td>전용 IO 터미널블록</td>
  </tr>
  <tr>
    <td>시스템용 DIO 입출력</td>
    <td>제어기 내부의 예비 IO 포트</td>
  </tr>
  <tr>
    <td rowspan="4">기타부품</td>
    <td>방열판(Heat Sink)</td>
    <td>전력소자에서 발생하는 열을 외부로 방출</td>
  </tr>
  <tr>
    <td>정류부</td>
    <td>교류입력 전원을 정류하여 모터 구동용 직류 전원 생성</td>
  </tr>
  <tr>
    <td>회생 IGBT</td>
    <td>회생방전 수행</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>3상 모터 구동용 전력 변환</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
구동장치는 로봇에 따라 다르므로 교환할 때에는 형식을 반드시 확인하시기 바랍니다.
{% endhint %}

■  **소형 6축 일체형 드라이브모듈 형번 구성**

![](../../../_assets/소형_6축_일체형_드라이브모듈_형번_구성.png  )

표 4-24 소형 6축 일체형 드라이브모듈의 형식기호

<table>
<tbody>
<tr class="odd">
<td><p><strong>구분</strong></p></td>
<td><p><strong>형식기호</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 소형 6축 드라이브모듈</strong></p></td>
<td><p>H6D6A</p></td>
</tr>
</tbody>
</table>

표 4-25 소형 6축 일체형 드라이브모듈의 사양

<table>
<thead>
  <tr>
    <th>구성</th>
    <th colspan="2">분류</th>
    <th colspan="2">적용</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>IPM용량</td>
    <td>3A</td>
    <td>3D</td>
    <td>HA006B, HH020</td>
    <td>6축 일체형</td>
  </tr>
  <tr>
    <td>년도</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">생산년도 : 2000년 ~ 2099년</td>
  </tr>
  <tr>
    <td>월</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">생산월 : 1월 ~ 12월</td>
  </tr>
  <tr>
    <td>일련번호</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">월 생산대수 : 1대 ~ 999대</td>
  </tr>
</tbody>
</table>

표 4-26 소형 6축 드라이브모듈의 IPM 기호

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>IPM 기호</th>
    <th>IPM 사양</th>
    </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">소형 6축 드라이브모듈</td>
    <td>A</td>
    <td>(IPM 허용 전류정격) 30A</td>
  </tr>
  <tr>
    <td>D</td>
    <td>(IPM 허용 전류정격) 10A</td>
  </tr>
</tbody>
</table>

표 4-27 소형 6축 드라이브모듈의 홀센서(Hall Sensor) 기호

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall Sensor기호(사양)</th>
    <th>Full Scale 전류(Im)</th>
    <th>IPM 사양 (허용 전류정격)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">소형<br>드라이브모듈</td>
    <td>3 (4V/15A)</td>
    <td>27.27Apeak</td>
    <td rowspan="2">6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.18Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/5A)</td>
    <td>9.19Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>6 (4V/3A)</td>
    <td>5.45Apeak</td>
  </tr>
  <tr>
    <td>7 (4V/6A)</td>
    <td>10.91Apeak</td>
    <td>6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>8 (4V/2A)</td>
    <td>3.64Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>9 (4V/1A)</td>
    <td>1.82Apeak</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
드라이브 모듈은 로봇에 따라 다르므로 교환할 때에는 형식을 반드시 확인하시기 바랍니다.
{% endhint %}

![](../../../_assets/그림_4.41_BD653_부품_배치도.png  )

그림 4.22 BD653 부품 배치도

표 4-28 BD653 커넥터 설명

<table>
<tbody>
<tr class="odd">
<td><p><strong>명칭</strong></p></td>
<td><p><strong>용도</strong></p></td>
<td><p><strong>외부장치접속</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM신호, IPM에러 신호</p></td>
<td><p>BD654 Board to Board 커넥터</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>3상 전원 입력</p></td>
<td><p>전장 모듈 CNRST</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>컨버터부 에러 신호</p></td>
<td><p>BD654 Board to Board 커넥터</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>회생방전 출력</p></td>
<td><p>회생방전 저항</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>회생방전 저항 과열 검지</p></td>
<td><p>회생방전 저항 온도센서</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~6</strong></p></td>
<td><p>모터 구동 출력</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>부가축 드라이브모듈 직류전원</p></td>
<td><p>선택사양 부가축 드라이브모듈 CNPN</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG1, CNFG4</strong></p></td>
<td><p>모터의 Frame Ground</p></td>
<td><p>CMC1</p></td>
</tr>
</tbody>
</table>

표 4-29 BD653 LED 설명

<table>
<tbody>
<tr class="odd">
<td><p><strong>명칭</strong></p></td>
<td><p><strong>색상</strong></p></td>
<td><p><strong>상태표시</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>황색</p></td>
<td><p>전자접촉기 구동 시 점등</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>녹색</p></td>
<td><p>컨버터부 제어전압 정상 시 점등</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>적색</p></td>
<td><p>회생방전 동작 시 점등</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>적색</p></td>
<td><p>PN전압이 42V이상 시 점등</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>적색</p></td>
<td><p>PN방전 동작 시 소등</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4.42_BD654_부품_배치도.png  )

그림 4.23 BD654 부품 배치도

표 4-30 BD654 커넥터 설명

<table>
<tbody>
<tr class="odd">
<td><p><strong>명칭</strong></p></td>
<td><p><strong>용도</strong></p></td>
<td><p><strong>외부 장치 접속</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>8축 PWM신호, IPM에러 신호<br>컨버터부 에러 신호</p></td>
<td><p>BD640 Board to Board 커넥터</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>축별 PWM신호, IPM에러 신호</p></td>
<td><p>BD653 Board to Board 커넥터</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>부가축 PWM신호, IPM에러 신호</p></td>
<td><p>부가축 드라이브모듈(BD658 또는 BD659)의 CNPWM</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>컨버터부 에러 신호</p></td>
<td><p>BD653 Board to Board 커넥터</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>예비 전용IO 터미널블록</p></td>
<td><p>Reserved</p></td>
</tr>
</tbody>
</table>

표 4-31 BD654 LED 설명

<table>
<tbody>
<tr class="odd">
<td><p><strong>명칭</strong></p></td>
<td><p><strong>색상</strong></p></td>
<td><p><strong>상태 표시</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>황색</p></td>
<td><p>전자접촉기 구동 시 점등</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>녹색</p></td>
<td><p>제어전원 정상 시 점등</p></td>
</tr>
</tbody>
</table>
