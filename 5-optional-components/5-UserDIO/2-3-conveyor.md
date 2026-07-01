# 5.5.2.3 Conveyor 

The following figure shows the configuration for conveyor synchronization with encoder inputs and limit switches. 
It consists of a total of two input channels. Each channel supports two types of encoders(open collector/line driver).<br> 

![](../../_assets/그림_5.37_BD682_컨베이어_커넥터_핀맵_en.png)<br>

| No. | Signal Name   | Description   |No. | Signal Name | Description |
|------|---------|---------- |-----|-------- |----------|
| 1    |PA2_P    |Channel 2 line driver type encoder<br> A signal input positive| 11 | PA1_P |Channel 1 line driver type encoder <br> A signal input positive|        
| 2    |PA2_N    |Channel 2 line driver type encoder<br> A signal input negative| 12 | PA1_N |Channel 1 line driver type encoder <br> A signal input negative|
| 3    |PB2_P    |Channel 2 line driver type encoder<br> B signal input Positive| 13 | PB1_P |Channel 1 line driver type encoder <br> B signal input Positive |
| 4    |PB2_N    |Channel 2 line driver type encoder<br> B signal input negative| 14 | PB1_N |Channel 2 line driver type encoder<br> B signal input negative |
| 5    |LDLS2    |Channel 2 line driver type encoder<br> Limit switch  | 15 | LDLS1 |Channel 1 line driver type encoder <br> Limit switch 
| 6    |GND      |Ground  | 16 | GND |Ground |
| 7    |P2+      |Channel 2 open collector encoder power  | 17 | P1+ |Channel 1 open collector encoder power    |
| 8    |A2       |Channel 2 open collector type encoder <br> A Signal input| 18 | A1 |Channel 1 open collector type encoder <br> A Signal input  |
| 9    |B2       |Channel  2  open  collector type encoder <br> B Signal input| 19 | B1 |Channel 1 open collector type encoder  <br> B Signal input   |
| 10   |OCLS2    |Channel  2  open  collector type encoder <br> Limit switch   |  20 | OCLS1  | Channel 1 open collector type encoder  <br> Limit switch | <br>


