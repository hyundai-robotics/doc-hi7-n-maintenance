# 4.3.2.7. Connection of the Safety PLC/IO

The emergency input signal and monitoring output signal between the safety PLC or IO, and the robot controller should be connected in the following way.

![](../../../_assets/그림_4.38_Safety_PLC,IO의_연결방법.png  )

Figure 4.18 Method to Connect the Safety PLC/IO

\(1\) P-COM Input and Safety Input 

The safety inputs (ES, SG) of the safety PLC are designed in a way that the controller can receive the PNP output, as an input, from the terminal block TBEM. Considering this, you must connect the power (DC24V) of the PLC before using the safety inputs.

{% hint style="warning" %}
If a safety input is to be installed and used, the robot should be operated after confirming that the function works normally. This is an essential measure that must be taken in advance for the safety of workers.
{% endhint %}


\(2\) Emergency Stop Output

Emergency stop output is designed in a way that allows the controller to use the PNP output by turning it on or off when it is necessary for an external device to use the status of the emergency stop switch (on the operation panel, teach pendant, etc.) installed inside the controller.

{% hint style="warning" %}
If an emergency stop output is to be installed and used, the robot should be operated after confirming that the emergency stop output operates normally. This is an essential measure that must be taken in advance for the safety of workers.
{% endhint %}

