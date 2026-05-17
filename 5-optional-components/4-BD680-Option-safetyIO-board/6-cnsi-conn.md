# 5.4.6. Safety Input Wiring

{% hint style="warning" %}
When performing safety input wiring, ensure the controller power is turned OFF before starting the wiring work.
{% endhint %}

The figure below shows the actual appearance of the Optional Safety IO Module(BD680) and the location of the safety input connector(CNSI2) when viewed from the front.   

![](../../_assets/BD680_전면사진_안전입력.png)  
Figure 5.4.6-1 Optional Safety IO Module(BD680) - Physical View and Safety Input Connector(CNSI2) Location

The wiring for safety inputs differs depending on whether internal or external power is used and the type of signal(NPN/PNP). The following diagrams show the wiring configuration for each case.

(1) When Using Internal Power   
* NPN-TYPE(: Active Low)   
In the figure below, red represents A-Channel and blue represents B-Channel.
A-Channel: When using internal power, connect pins 1-3 on connector CNSI2 as shown in the figure.
B-Channel: When using internal power, connect pins 13-15 on connector CNSI2 as shown in the figure.
For connection to external devices, refer to the wiring example below.

![](../../_assets/BD680_안전입력_내부전원_NPN.png)   
Figure 5.4.6-2 Optional Safety IO Module(BD680)-Safety Input Wiring Using Internal Power(NPN-TYPE)

* PNP-TYPE(: Active High)   
In the figure below, red represents A-Channel and blue represents B-Channel.
A-Channel: When using internal power, connect pins 3-12 on connector CNSI2 as shown in the figure.
B-Channel: When using internal power, connect pins 15-24 on connector CNSI2 as shown in the figure.
For connection to external devices, refer to the wiring example below.

![](../../_assets/BD680_안전입력_내부전원_PNP.png)   
Figure 5.4.6-3 Optional Safety IO Module(BD680)-Safety Input Wiring Using Internal Power(PNP-TYPE)

{% hint style="warning" %}
Do not use the internal power as the power supply for external devices when connecting to them.
{% endhint %}  

(2) When Using External Power   
* NPN-TYPE(: Active Low)  
The red color in the figure represents A-Channel, and the blue color represents B-Channel.
A-Channel: When using external power, do not connect pins 1 and 12 of connector CNSI2. Connect the external power EX_AV to pin 3.
B-Channel: When using external power, do not connect pins 13 and 24 of connector CNSI2. Connect the external power EX_BV to pin 15.
Refer to the wiring example below for connections to external devices.

![](../../_assets/BD680_안전입력_외부전원_NPN.png)   
Figure 5.4.6-4 Wiring Diagram of Safety Inputs Using External Power(NPN-TYPE) for Option Safety I/O Module(BD680)

* PNP-TYPE(: Active High)   
he red color in the figure represents A-Channel, and the blue color represents B-Channel.
A-Channel: When using external power, do not connect pins 1 and 12 of connector CNSI2. Connect the external power EX_AG to pin 3.
B-Channel: When using external power, do not connect pins 13 and 24 of connector CNSI2. Connect the external power EX_BG to pin 15.
Refer to the wiring example below for connections to external devices.

![](../../_assets/BD680_안전입력_외부전원_PNP.png)   
Figure 5.4.6-5 Wiring Diagram of Safety Inputs Using External Power(PNP-TYPE) for Option Safety I/O Module(BD680)

