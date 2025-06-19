# 4.3.4.4. H6D1X (캐리지용 드라이브모듈; 선택사양)

드라이브모듈(Drive Module)은 서보보드로부터의 전류지령에 따라 모터 각 상에 전류를 흘려주는 전력증폭기능을 수행합니다. 캐리지용 드라이브모듈은 100A 이하의 1개의 모터를 구동시킬 수 있으며, 다음과 같이  성되어 있습니다.

![](../../../_assets/그림_4.43_H6D1X용BD658_부품_배치도.png  )

그림 4.24 H6D1X용BD658 부품 배치도

표 4-35 H6D1X의 구성

<table>
<thead>
  <tr>
    <th colspan="2">구성품</th>
    <th>기능</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD658<br>(IPM보드)</td>
    <td>로직부</td>
    <td>6축 드라이브모듈로부터 수신한 PWM신호를 IPM의 상하단 구동신호로 변환하며, 에러처리 수행</td>
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
    <td rowspan="2">기타부품</td>
    <td>방열판(Heat Sink)</td>
    <td>IPM에서 발생하는 열을 외부로 방출</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>3상 모터 구동용 전력 변환</td>
  </tr>
</tbody>
</table>

표 4-36 H6D1X 커넥터 설명

<table>
<thead>
  <tr>
    <th>명칭</th>
    <th>용도</th>
    <th>외부 장치 접속</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM신호, 에러신호</td>
    <td>6축 드라이브모듈(BD652 또는 BD654)의 CNPWM7 또는  CNPWM8</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>모터 구동 출력</td>
    <td>AMC1 또는  AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>모터 Frame Ground</td>
    <td>AMC1 또는  AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>구동 직류전원 입력</td>
    <td>6축 드라이브모듈(BD651 또는 BD653)의 CNPN7 또는  CNPN8</td>
  </tr>
</tbody>
</table>
