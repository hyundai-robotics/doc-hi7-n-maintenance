# 5.4.1 개요

Hi6a 제어기에서 '사용자 DIO 보드(BD681)'와 '확장 DIO 보드(BD682)'를 활용하여 범용 IO 신호와 컨베이어 엔코더 동기를 진행할 수 있습니다.

'확장 DIO 보드(BD682)'는 단독으로는 사용할 수 없으며 '사용자 DIO 보드(BD681)'와 같이 사용해야 합니다.

<br>
표 5-9 보드 사양

<table>
<thead>
    <tr>
        <th style="width: 50px; text-align: center;">No.</th>
        <th style="width: 110px; text-align: center;">
            보드명<br>
            (보드 식별자)
        </th>
        <th style="width: 300px; text-align: center;">보드 기능 정보</th>
    </tr>
</thead>
<tbody>
    <tr>
        <td style="text-align: center;"><strong>1</strong></td>
        <td style="text-align: center;">
            사용자 DIO 보드<br>
            ( BD681 )
        </td>
        <td> - 범용 입력 16 채널 <br>
             - 범용 출력 16 채널 <br>
             - 단독 사용 가능</td>
    </tr>
    <tr>
        <td style="text-align: center;"><strong>2</strong></td>
        <td style="text-align: center;">
            확장 DIO 보드<br>
            ( BD682 )
        </td>
        <td> - 범용 입력 16 채널 <br>
             - 범용 출력 16 채널 <br> 
             - 컨베이어 엔코더 2채널 <br> 
             - 단독 사용 불가 (BD681과 같이 사용 필요)</td>
    </tr>
</tbody>
</table>

<br>
{% hint style="info" %}
사용자 DIO를 정상적으로 사용하기 위해서는 아래 항목들에 대한 설정 및 확인이 필요합니다.<br><br>

1. 이더캣 통신 연결<br>
2. FB 블록 설정<br>
3. 내부 PLC 사용 여부 확인<br><br>

따라서 ‘5.4.3. 사용자 DIO 설정 방법’을 참고하여 설정을 진행하시기 바랍니다.
{% endhint %}