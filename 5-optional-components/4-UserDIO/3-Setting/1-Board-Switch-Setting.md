# 5.4.3.1 보드 스위치 확인

보드 스위치 위치는 아래 사진과 같습니다.<br>

![](../../../_assets/그림_5.6사용자DIO_보드_스위치_위치.png)<br>
그림 5.6 사용자DIO 보드 스위치 위치

<br>
{% hint style="warning" %}
보드를 분리할때는 반드시 제어기 전원을 OFF 하고 보드 전원이 OFF 되었는지 확인 후 분리하시기 바랍니다.
{% endhint %}

<br>
아래와 같은 TP화면에서도 내부 스위치 상태를 확인할 수 있습니다.<br><br>

![](../../../_assets/그림_5.7사용자DIO_보드_설정_TP.png)<br>
그림 5.7 사용자DIO 보드 설정 TP UI


- 메뉴 위치 : [시스템] - [옵션장치] - [사용자DIO 보드 설정]

'사용자DIO 목록' 에서 '사용자DIO 모드' 항목으로 확인할 수 있습니다.<br>

<br>
표 5-10 사용자DIO 모드 항목

<table>
<thead>
    <tr>
        <th style="width: 20px; text-align: center;">No.</th>
        <th style="width: 110px; text-align: center;">
            사용자DIO 모드
        </th>
        <th style="width: 30px; text-align: center;">
            스위치 <br>
            ON/OFF
        </th>
        <th style="width: 250px; text-align: center;">비고</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td style="text-align: center;"><strong>1</strong></td>
        <td style="text-align: center;">
            Use Ext_DIO <br>
            (BD681 + BD682)
        </td>
        <td style="text-align: center;">OFF</td>
        <td> - 확장DIO (BD682) 연동 모드<br>
             - 기본 구성시 (BD681 + BD682) 사용<br>
    </tr>
    <tr>
        <td style="text-align: center;"><strong>2</strong></td>
        <td style="text-align: center;">
            Only UserDIO <br>
        </td>
        <td style="text-align: center;">ON</td>
        <td> - 사용자DIO (BD681) 단독 모드 <br>
             - 확장DIO (BD682) 연동 불가<br>
             - 기본 구성에 BD681 추가시 사용<br> 
             - 추가된 2번째 BD681에 적용 필요 <br></td>
    </tr>
</tbody>
</table>
<br><br>

![](../../../_assets/그림_5.8사용자DIO_보드_스위치_ON_OFF.png)<br>
그림 5.8 사용자DIO 보드 스위치 ON/OFF