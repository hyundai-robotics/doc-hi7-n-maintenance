# 4.3.2.6. Safety Input Wiring

{% hint style="warning" %}
When performing safety input wiring, ensure that the controller power is turned OFF before starting the wiring work.
{% endhint %}

The figure below shows a photograph of the Servo/Safety Module(BD642) and the location of the safety input connector(CNSI1) as viewed from the front during actual installation.   

![](../../../_assets/BD642_전면사진_안전입력.png)   
Figure 4.3.2.6-1 Photograph of the Servo/Safety Module(BD642) and Location of the Safety Input Connector(CNSI1)

(1) Safety Input Factory Default State(When Not Used)   
If the safety input signals are not used, they must be connected as NC(Normally Closed, B-contact) by default.
The figure below shows the wiring configuration when the safety inputs are not used(factory default wiring state).

![](../../../_assets/BD642_안전입력_사용안함.png)   
Figure 4.3.2.6-2 Factory Default Wiring State of Safety Inputs - Servo/Safety Module(BD642)

When wiring the safety inputs, the wiring method differs depending on whether an internal power supply or an external power supply is used. It also varies according to the NPN/PNP type configuration. The following figures show the wiring examples for each case.

(2) When Using the Internal Power Supply
* NPN-TYPE(: Active Low)   
In the figure below, red indicates the A channel, and blue indicates the B channel.
When using the internal power supply for the A-channel, connect the following pins of connector CNSI1 for the corresponding channel as shown in the figure below:
17-18, 21-22, 25-26, and 29-30.
When using the internal power supply for the B-channel, connect the following pins of connector CNSI1 for the corresponding channel as shown in the figure below:
19-20, 23-24, 27-28, and 31-32.
For connection to external devices, refer to the wiring example shown below.

![](../../../_assets/BD642_안전입력_내부전원_NPN.png)   
Figure 4.3.2.6-3 Safety Input Wiring Diagram(Internal Power Supply, NPN Type) - Servo/Safety Module(BD642)

* PNP-TYPE(: Active High)   
In the figure below, red indicates the A-channel, and blue indicates the B-channel.
When using the internal power supply for the A-channel, connect the following pin pairs of connector CNSI1 for the corresponding channel as shown in the figure below:
1-2, 5-6, 9-10, and 13-14.
When using the internal power supply for the B-channel, connect the following pin pairs of connector CNSI1 for the corresponding channel as shown in the figure below:
3-4, 7-8, 11-12, and 15-16.
For connection to external devices, refer to the wiring example shown below.   

![](../../../_assets/BD642_안전입력_내부전원_PNP.png)   
Figure 4.3.2.6-4 Safety Input Wiring Diagram(Internal Power Supply, PNP Type) - Servo/Safety Module(BD642)

{% hint style="warning" %}
When connecting the internal power supply to an external device, it must not be used as the power source for the device.   
{% endhint %}

(3) When Using an External Power Supply
* NPN-TYPE(: Active Low)   
In the figure below, red indicates the A-channel, and blue indicates the B-channel.
When using an external power supply for the A-channel, do not connect the following pins of connector CNSI1 as shown in the figure below:
1, 17, 5, 21, 9, 25, 13, and 29.
When using an external power supply for the B-channel, do not connect the following pins of connector CNSI1 as shown in the figure below:
4, 20, 8, 24, 12, 28, 16, and 32.
For connection to external devices, refer to the wiring example shown below.

![](../../../_assets/BD642_안전입력_외부전원_NPN.png)   
Figure 4.3.2.6-5 Wiring Diagram for Safety Input(External Power Supply, NPN Type) - Servo/Safety Module(BD642)

* PNP-TYPE(: Active High)   
In the figure below, red represents the A-channel and blue represents the B-channel.
When using an external power supply for the A channel, do not connect pins 1, 17, 5, 21, 9, 25, 13, and 29 of connector CNSI1 as shown.
When using an external power supply for the B channel, do not connect pins 4, 20, 8, 24, 12, 28, 16, and 32 of connector CNSI1 as shown.
Connections to external devices should follow the wiring example shown below.

![](../../../_assets/BD642_안전입력_외부전원_PNP.png)   
Figure 4.3.2.6-6 Wiring Diagram for Safety Input(External Power Supply, PNP Type) - Servo/Safety Module(BD642)

