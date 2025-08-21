# 5.5.3.4 내장 PLC 설정 확인

FB블럭을 사용하여 정상적으로 사용자 DIO를 연동하기 위해서는 내장 PLC 설정 확인이 필요합니다.

**- 내장 PLC off (미사용)**<br>

로봇제어기의 논리적 출력(Logical Output)인 FB0.DO0~FB9.DO959이 물리적 출력(Physical Output)인 FB0.Y0~FB9.Y959로 자동 출력(bypass)되고, 물리적 입력인 FB0.X0~FB9.X959가 논리적 입력인 FB0.DI0~FB9.DI595로 자동 입력되어 사용자 DIO를 정상적으로 사용가능 합니다.<br><br>

**- 내장 PLC 사용**

내장 PLC에서 불러오는 래더 로직(Ladder Logic)이 FB블럭 입출력에 영향을 주게 되므로 주의가 필요합니다.

![](../../../_assets/그림_5.23_래더로직_FB_입출력_연결.png)<br>
그림 5.23 래더 로직의 fb1 논리적/물리적 입출력 연결 예시<br>

내장 PLC에 대한 자세한 사항은 "[내장 PLC](https://hrbook-hrc.web.app/#/view/doc-hi6-embedded-plc/korean/README)" 를 참고하시기 바랍니다.
