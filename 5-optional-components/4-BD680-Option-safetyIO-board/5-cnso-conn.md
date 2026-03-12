# 5.4.5. Safety Output Wiring

{% hint style="warning" %}
When wiring the safety outputs, always ensure that the controller power is turned OFF before performing any wiring work.
{% endhint %}

The figure below shows the actual optional Safety IO Module(BD680) and the location of the safety output connector as seen from the front during installation.

![](../../_assets/BD680_전면사진_안전출력.png)   
Figure 5.4.5-1 Optional Safety IO Module(BD680)–Front view and safety output connector location

The wiring method differs depending on whether internal power or external power is used. The following sections illustrate the wiring for each case.

(1) Using Internal Power   
In the figure below, red represents A-Channel and blue represents B-Channel.
A-Channel(Internal Power): Connect pins 1–2 and 11–12 of connector CNSO2 as shown.
B-Channel(Internal Power): Connect pins 13–14 and 23–24 of connector CNSO2 as shown.
Refer to the wiring examples below for connections to external devices.

![](../../_assets/BD680_안전출력_내부전원.png)  
Figure 5.4.5-2 Optional Safety IO Module(BD680)–Safety Output Wiring with Internal Power

(2) Using External Power
In the figure below, red represents A-Channel and blue represents B-Channel.
Connector CNSO2 pins 1, 12, 13, and 24 are not connected.
A-Channel(External Power): Connect EX_AV(24V) to pin 2 and EX_AG(GND) to pin 11.
B-Channel(External Power): Connect EX_BV(24V) to pin 14 and EX_BG(GND) to pin 23.
Refer to the wiring examples below for connections to external devices.

![](../../_assets/BD680_안전출력_외부전원.png)
Figure 5.4.5-3 Optional Safety IO Module(BD680)–Safety Output Wiring Using External Power
