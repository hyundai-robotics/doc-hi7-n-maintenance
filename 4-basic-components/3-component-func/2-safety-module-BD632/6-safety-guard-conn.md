# 4.3.2.6. Connection of the Safety Guard 

(1\) General Safety Guard

The general safety guard operates regardless of the controller's mode (automatic or manual). In other words, when a person enters inside the installed safety guard or when the guard is broken, the controller will immediately shut off the motor power. The safety guard that can be used should be in the form of contact output. In the terminal block TBEM, terminals are configured in a way that they connect the contact outputs of the safety guard to the dual safety chain, as shown in the figure below.



![](../../../_assets/그림_4.34_터미널블록_TBRMT에_일반_안전가드를_연결하는_방법.png  )

Figure 4.14 Method to Connect a General Safety Guard to the Terminal Block TBRMT

If the general safety guard is not to be used, connect the terminals (pins 15-7 and 16-8) of the terminal block TBEM, as shown below, to disable the input.

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.15 Method to Perform When Not Using a General Safety Guard

{% hint style="warning" %}
If a general safety guard is to be installed and used, the robot should be operated after confirming that the emergency stop operates normally. In addition, check if the emergency stop input is disabled. This is an essential measure that must be taken in advance for the safety of workers.
{% endhint %}


\(2\) Automatic Safety Guard of Contact Input Type 

The automatic safety guard operates only when the controller is in the automatic mode and provides two inputs, as shown below. Like a general safety guard, the automatic safety guard should be in the form of contact output. In the terminal block TBEM, terminals are configured in a way that they connect the contact outputs of the safety guard to the dual safety chain, as shown in the figure below.

![](../../../_assets/그림_4.36_터미널블록_TBEM에_접점입력_자동_안전가드를_연결하는_방법.png  )

Figure 4.16 Method to Connect an Automatic Safety Guard of Contact Input Type to the Terminal Block TBEM

If the automatic safety guard is not to be used, connect the terminals of the terminal block TBEM((pins 11-3, 12-4, 13-5 and 14-6), as shown below, to disable the input.

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.17 Method to Perform When Not Using an Automatic Safety Guard of Contact Input Type

{% hint style="warning" %}
If an automatic safety guard is to be installed and used, the robot should be operated after confirming that the emergency stop works normally. In addition, check if the emergency stop input is disabled. This is an essential measure that must be taken in advance for the safety of workers.
{% endhint %}

