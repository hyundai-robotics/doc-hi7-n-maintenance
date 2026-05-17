# 4.3.2.5. Safety Output Wiring

{% hint style="warning" %}
When performing safety output wiring, ensure that the controller power is turned OFF before starting the wiring work.
{% endhint %}

The figure below shows a photograph of the Servo/Safety Module(BD642) and the location of the safety output connector(CNSO1) as viewed from the front during actual installation.

![](../../../_assets/BD642_전면사진_안전출력.png)<br>
Figure 4.3.2.5-1 Photograph of the Servo/Safety Module(BD642) and Location of the Safety Output Connector(CNSO1)

When wiring the safety outputs, the wiring method differs depending on whether an internal power supply or an external power supply is used. It also varies according to the NPN or PNP type configuration.
The following figures show the wiring examples for each case.

(1) When Using the Internal Power Supply   
* NPN-TYPE(: Active Low)   
In the figure below, red indicates the A channel and blue indicates the B channel.
When using the internal power supply for the A channel, connect pins 1 and 2 of connector CNSO1 as shown in the figure below.
When using the internal power supply for the B channel, connect pins 3 and 4 of connector CNSO1 as shown in the figure below.
For connection to external devices, refer to the wiring example below.

![](../../../_assets/BD642_안전출력_내부전원_NPN.png)   
Figure 4.3.2.5-2 Safety Output Wiring Diagram (Internal Power Supply, NPN Type) - Servo/Safety Module(BD642)   

* PNP-TYPE(: Active High)   
In the figure below, red indicates the A channel, and blue indicates the B channel.
When using the internal power supply for the A channel, connect pins 5 and 6 of connector CNSO1 as shown in the figure below.
When using the internal power supply for the B channel, connect pins 7 and 8 of connector CNSO1 as shown in the figure below.
For connection to external devices, refer to the wiring example below.

![](../../../_assets/BD642_안전출력_내부전원_PNP.png)   
Figure 4.3.2.5-3 Safety Output Wiring Diagram (Internal Power Supply, PNP Type) - Servo/Safety Module(BD642)   

(2) When Using an External Power Supply   
* NPN-TYPE(: Active Low)   
In the figure below, red indicates the A channel, and blue indicates the B channel.
Pins 1, 4, 5 and 8 of connector CNSO1 must not be connected.
When using an external power supply for the A channel, connect EX_AG (GND) to pin 2 of connector CNSO1 as shown in the figure below.
When using an external power supply for the B channel, connect EX_BG (GND) to pin 3 of connector CNSO1 as shown in the figure below.
For connection to external devices, refer to the wiring example shown below.

![](../../../_assets/BD642_안전출력_외부전원_NPN.png)   
Figure 4.3.2.5-4 Safety Output Wiring Diagram(External Power Supply, NPN Type)-Servo/Safety Module(BD642)   

* PNP-TYPE(: Active High)   
In the figure below, red indicates the A channel, and blue indicates the B channel.
When using an external power supply for the A channel, connect EX_AV(24V) to pin 2 of connector CNSO1, as shown in the figure below.
When using an external power supply for the B channel, connect EX_BV(24V) to pin 3 of connector CNSO1, as shown in the figure below.
For connection to external devices, refer to the wiring example shown below.

![](../../../_assets/BD642_안전출력_외부전원_PNP.png)   
Figure 4.3.2.5-5 Safety Output Wiring Diagram(External Power Supply, PNP Type)-Servo/Safety Module(BD642)
