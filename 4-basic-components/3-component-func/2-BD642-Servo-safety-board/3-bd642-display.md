# 4.3.2.3. 표시장치

아래 그림은 서보/안전모듈(BD642)의 표시장(LED, 7세그먼트)장치 위치를 보여줍니다. 아래 표는 각 표시의 내용을 기술합니다.   

![](../../../_assets/BD642_PCB_상태.png)   
그림 4.3.2.3-1 서보/안전모듈(BD642)의 표시장치 배치

표 4.3.2.3-1 서보/안전모듈(BD642) 표시장치 설명   
<table>
<tbody>
  <tr>
    <td><strong>번호</strong></td>
    <td><strong>명칭</strong></td>
    <td><strong>표시내용</strong></td>
    <td><strong>색상</strong></td>
    <td><strong>정상시</strong></td>
    <td><strong>이상시 조치내용</strong></td>
  </tr>
  <tr>
    <td>(1)<br>(2)</td>
    <td>LED1<br>LED2</td>
    <td>입력전원 제한기능</td>
    <td>적색</td>
    <td>소등</td>
    <td>
      현상 : 적색 점등
      <br>원인 : 입력전압 저전압 또는 과전압 발생
      <br>조치 : 입력전압(24V) 확인
    </td>
  </tr>
  <tr>
    <td>(3)</td>
    <td>LED3</td>
    <td>외부 A채널 전원</td>
    <td>노란색</td>
    <td>점등</td>
    <td>
      현상: 노란색 소등
      <br>원인 : 외부 A채널 전원 과전류 및 외부결선 오작업 등
      <br>조치 : 퓨즈(FS2) 확인
    </td>
  </tr>
  <tr>
    <td>(4)</td>
    <td>LED4</td>
    <td>외부 B채널 전원</td>
    <td>노란색</td>
    <td>점등</td>
    <td>
      현상: 노란색 소등
      <br>원인 : 외부 B채널 전원 과전류 및 외부결선 오작업 등
      <br>조치 : 퓨즈(FS3) 확인
    </td>
  </tr>
  <tr>
    <td>(5)</td>
    <td>LED5</td>
    <td>A채널 MCU 전원</td>
    <td>노란색</td>
    <td>점등</td>
    <td>
      현상 : 노란색 소등
      <br>원인 : A채널 MCU 전원(3.3V, 1.2V) 이상
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(6)</td>
    <td>LED6</td>
    <td>B채널 MCU 전원</td>
    <td>노란색</td>
    <td>점등</td>
    <td>
      현상 : 노란색 소등
      <br>원인 : B채널 MCU 전원(3.3V, 1.2V) 이상
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(7)</td>
    <td>LED7</td>
    <td>A채널 MCU 상태 표시</td>
    <td>적색
      <br>녹색
      <br>파란색
    </td>
    <td>RGB 깜박임</td>
    <td>
      현상 : 전체 소등 및 깜박임 없음
      <br>원인1 : A채널 MCU 전원(3.3V, 1.2V) 이상
      <br>원인2 : A채널 MCU 프로그램 이상 등
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(8)</td>
    <td>LED8</td>
    <td>B채널 MCU 상태 표시</td>
    <td>적색
      <br>녹색
      <br>파란색
    </td>
    <td>RGB 깜박임</td>
    <td>
      현상 : 전체 소등 및 깜박임 없음
      <br>원인1 : B채널 MCU 전원(3.3V, 1.2V) 이상
      <br>원인2 : B채널 MCU 프로그램 이상 등
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(9)
      <br>(10)</td>
    <td>LED9
      <br>LED10</td>
    <td>A채널 MCU EtherCAT LINK0 상태
      <br>A채널 MCU EtherCAT LINK1 상태
    </td>
    <td>녹색
      <br>녹색
    </td>
    <td>녹색 깜박임
      <br>녹색 깜박임
    </td>
    <td>
      현상 : 깜박임 없음
      <br>원인 : A채널 MCU EtherCAT 이상
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(11)
      <br>(12)</td>
    <td>LED13
      <br>LED14</td>
    <td>FPGA EtherCAT LINK0 상태
      <br>FPGA EtherCAT LINK1 상태
    </td>
    <td>녹색
      <br>녹색
    </td>
    <td>녹색 깜박임
      <br>녹색 깜박임
    </td>
    <td>
      현상 : 깜박임 없음
      <br>원인 : FPGA EtherCAT 이상
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(13)</td>
    <td>LED17</td>
    <td>FPGA 전원 상태</td>
    <td>노란색</td>
    <td>점등</td>
    <td>
      현상 : 노락색 소등
      <br>원인 : FPGA 전원(5V,3.3V,1.8V,1.35V,1V) 이상
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
  <tr>
    <td>(14)</td>
    <td>LED18</td>
    <td>FPGA 상태 표시</td>
    <td>적색
      <br>녹색
      <br>파란색</td>
    <td>RGB 깜박임</td>
    <td>
      현상 : 전체 소등 및 깜박임 없음
      <br>원인1 : FPGA 전원(5V,3.3V,1.8V,1.35V,1V) 이상
      <br>원인2 : FPGA 프로그램 이상 등
      <br>조치 : 보드(BD642) 교체
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
    <td>  1축 브레이크 상태
      <br>2축 브레이크 상태
      <br>3축 브레이크 상태
      <br>4축 브레이크 상태
      <br>5축 브레이크 상태
      <br>6축 브레이크 상태
      <br>7축 브레이크 상태
      <br>8축 브레이크 상태
      </td>
    <td>주황식</td>
    <td>브레이크 릴리스(점등)
      <br>브레이크 홀드(소등)
    </td>
    <td>
      현상 : 브레이크 상태 불일치
      <br>원인1 : 브레이크 전원 이상
      <br>원인2 : 하네스 불량 등
      <br>조치 : 보드(BD642) 교체
    </td>
  </tr>
</table>
</tbody>

