# 4.3.3.4. 설정장치

{% hint style="info" %}
DIP스위치는 출고 시 모드 OFF로 설정되어 있으며, 사용자가 임의로 변경하면 안됩니다.
{% endhint %}

표 4-12 서보보드(BD640) DIP스위치(DS1) 설정방법

<table>
<thead>
  <tr>
    <th>스위치 번호</th>
    <th>1</th>
    <th>2</th>
    <th>모드</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>출고 시 설정</td>
    <td>OFF</td>
    <td>OFF</td>
    <td>GET MODE</td>
  </tr>
  <tr>
    <td>테스트 시</td>
    <td>ON</td>
    <td>OFF</td>
    <td>WAIT MODE</td>
  </tr>
  <tr>
    <td>스위치 외형</td>
    <td colspan="3"></td>
  </tr>
</tbody>
</table>

![](../../../_assets/표4-11_스위치외형.png)</br></br>

{% hint style="info" %}
다음은 사용자가 임의로 변경할 수 없으며, FPGA JTAG을 통한 재프로그래밍이 필요한 경우에만 참고하세요.
{% endhint %}


표 4-13 서보보드(BD640) 점퍼 (JP1) 설명

<table>
<thead>
  <tr>
    <th colspan="2" rowspan="2">명칭<br>설정내용</th>
    <th colspan="4">JP1</th>
  </tr>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">점퍼 셋팅</td>
    <td>QSPI (플래쉬) 부팅 모드</td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>JTAG 프로그래밍 모드</td>
    <td></td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
  </tr>
  <tr>
    <td>출고 시 설정</td>
    <td colspan="5">1, 2 : short / 3 : open</td>
  </tr>
</tbody>
</table>
