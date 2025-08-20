# 5.5.3.3 FB 블럭 설정

FB 블럭 설정은 다음 메뉴에서 진행할 수 있습니다.

- 메뉴 위치1: [시스템] - [2:제어 파라미터] - [11:산업용 통신] - [6:fb블럭 할당]
- 메뉴 위치2: [시스템] - [2:제어 파라미터] - [2:입출력 신호 설정] - [6:fb블럭 할당]

![](../../../_assets/그림_5.18_FB블럭할당.png)<br>
그림 5.18 FB 블럭 할당 메뉴<br><br>

할당하고 싶은 fb 블럭을 선택하여 '사용자 DIO'로 설정을 진행하면 됩니다.

![](../../../_assets/그림_5.19_fb1_사용자DIO할당.png)<br>
그림 5.19 fb1에 사용자DIO 할당 예시<br><br>

자세한 사항은 "[FB 블록 할당](https://hrbook-hrc.web.app/#/view/doc-hi6-operation/korean-tp630/7-system/3-control-parameter/2-io-signal-setting/9-dio-block-assign)" 을 참고하시기 바랍니다.

사용자 DIO에 대한 FB블럭이 할당 되었는지는 [6:fb블럭 할당] 및 [사용자DIO 보드 설정] 메뉴에서 확인 가능합니다.

![](../../../_assets/그림_5.20_사용자DIO_FB_미할당.png)<br>
그림 5.20 사용자DIO FB블록 미할당<br><br>

![](../../../_assets/그림_5.21_사용자DIO_FB3_할당.png)<br>
그림 5.21 사용자DIO fb3 할당<br>

{% hint style="warning" %}
사용자DIO를 여러 FB블럭에 할당하여도 가장 번호가 낮은 FB블럭에서 사용 가능하며, 나머지 할당된 FB블럭은 제어가 무시 됩니다.
{% endhint %}

아래 그림과 같이 FB블럭이 할당 되었을 경우, fb2에서 사용자 DIO 제어가 가능하며, fb5에 입력된 값은 무시됩니다.

![](../../../_assets/그림_5.22_사용자DIO_FB_다중할당.png)<br>
그림 5.22 사용자DIO fb 다중 할당 예시<br>
