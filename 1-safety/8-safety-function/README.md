# 1.8 Safety Functions

The safety system of the robot is designed in dual configuration (HFT=1) to satisfy the safety performance (PL) = d Cat3 of [ISO13849-1:2015] and the safety integrity level (SIL) 2 of [IEC62061:2005], and continuously monitors the status of safety related devices. When an error is detected by self-diagnosis, or a safety related signal is inputted, the safety functions will stop the robot according to the classification of stop situations determined based on the risk assessment. Also, when any of the dual switches of the safety circuit is activated, the motor drive power and brake drive power will be cut off by the sfety functions to secure a safe state. Information on the relevant status can be checked through the teaching pendant.

{% hint style="danger" %}
Make sure that the safety circuit is never ignored, modified or altered in any way.
{% endhint %}


The safety-related main functions of the robot are as follows.
