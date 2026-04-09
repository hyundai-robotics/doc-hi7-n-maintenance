# 5.5.2 Information of hardware 
The user IO module (BD681) allows connection and configuration with various devices through digital input/output ports. 
In addition, the extended IO module(BD682) allows the addition of digital I/O ports and synchronization with conveyor systems.<br>
The basic hardware configuration of the boards is as follows: 

![](../../_assets/그림_5_31_BD681_BD682_HW_및_커넥터_정보_en.png)<br>

### 5.5.2.1 Digital Imput
The following figure and table show the pin configuration of the terminal blocks for digital inputs. Each terminal block can receive 16 input signals, supporting NPN or PNP type inputs depending on the application. When BD682 is additionally mounted, 16 digital inputs are added. Refer to the function manual for how to configure NPN and PNP signals. 

![](../../_assets/그림_5.34_BD681_디지털_입력_커넥터_핀맵_en.png)<br>
| No. | Signal Name   | Description   |No. | Signal Name | Description |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_IN_A |COM Signal<br>(1~8)    | 11 | COM_IN_B | COM Signal<br>(9~16) |        
| 2    |A1|Digital input 1| 12 | B1 |Digital input 9    |
| 3    |A2|Digital input 2| 13 | B2 |Digital input 10   |
| 4    |A3|Digital input 3| 14 | B3 |Digital input 11   |
| 5    |A4|Digital input 4| 15 | B4 |Digital input 12   |
| 6    |A5|Digital input 5| 16 | B5 |Digital input 13   |
| 7    |A6|Digital input 6| 17 | B6 |Digital input 14   |
| 8    |A7|Digital input 7| 18 | B7 |Digital input 15   |
| 9    |A8|Digital input 8| 19 | B8 |Digital input 16   |
| 10   | COM_IN_A| COM Signal<br>(1~8)  |  20 | COM_IN_B  | COM Signal<br>(9~16)| <br>

When extended DIO board (BD682) is additionally mounted, the pin map is as follows:<br>

![](../../_assets/그림_5.35_BD682_디지털_입력_커넥터_핀맵_en.png)<br>
| No. | Signal Name   | Description   |No. | Signal Name | Description |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_IN_A |COM Signal<br>(1~8)    | 11 | COM_IN_B | COM Signal<br>(9~16) |        
| 2    |A9|Digital input 1| 12 | B1 |Digital input 9    |
| 3    |A10|Digital input 2| 13 | B2 |Digital input 10   |
| 4    |A11|Digital input 3| 14 | B3 |Digital input 11   |
| 5    |A12|Digital input 4| 15 | B4 |Digital input 12   |
| 6    |A13|Digital input 5| 16 | B5 |Digital input 13   |
| 7    |A14|Digital input 6| 17 | B6 |Digital input 14   |
| 8    |A7|Digital input 7| 18 | B7 |Digital input 15   |
| 9    |A8|Digital input 8| 19 | B8 |Digital input 16   |
| 10   | COM_IN_A| COM Signal<br>(1~8)  |  20 | COM_IN_B  | COM Signal<br>(9~16)| <br>
           
### 5.5.2.2 Digital Output 
The following figure and table show the pin configuration of the terminal blocks for digital outputs. Each terminal block can transmit 16 output signals, supporting NPN or PNP type outputs depending on the application.<br>
When BD682 is additionally mounted, 16 digital outputs are added.<br>

![](../../_assets/그림_5.33_BD681_디지털_출력_커넥터_핀맵_en.png)<br>

| No. | Signal Name   | Description   |No. | Signal Name | Description |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_OUT_A |COM Signal<br>(1~8)    | 11 | COM_OUT_B | COM Signal<br>(9~16) |        
| 2    |A1|Digital output 1| 12 | B1 |Digital output 9    |
| 3    |A2|Digital output 2| 13 | B2 |Digital output 10   |
| 4    |A3|Digital output 3| 14 | B3 |Digital output 11   |
| 5    |A4|Digital output 4| 15 | B4 |Digital output 12   |
| 6    |A5|Digital output 5| 16 | B5 |Digital output 13   |
| 7    |A6|Digital output 6| 17 | B6 |Digital output 14   |
| 8    |A7|Digital output 7| 18 | B7 |Digital output 15   |
| 9    |A8|Digital output 8| 19 | B8 |Digital output 16   |
| 10   | COM_OUT_A| COM Signal<br>(1~8)  |  20 | COM_OUT_B  | COM Signal<br>(9~16)| <br>

확장DIO보드(BD682) 추가 장착 시 핀맵 은 아래와 같습니다.<br>
![](../../_assets/그림_5.36_BD682_디지털_출력_커넥터_핀맵_en.png)<br>
| No. | Signal Name   | Description   |No. | Signal Name | Description |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_OUT_A |COM Signal<br>(17~24)    | 11 | COM_OUT_B | COM Signal<br>(25~32) |        
| 2    |A9|Digital output 17| 12 | B9 |Digital output 25    |
| 3    |A10|Digital output 18| 13 | B10 |Digital output 26   |
| 4    |A11|Digital output 19| 14 | B11 |Digital output 27   |
| 5    |A12|Digital output 20| 15 | B12 |Digital output 28   |
| 6    |A13|Digital output 21| 16 | B13 |Digital output 29   |
| 7    |A14|Digital output 22| 17 | B14 |Digital output 30   |
| 8    |A15|Digital output 23| 18 | B15 |Digital output 31   |
| 9    |A16|Digital output 24| 19 | B16 |Digital output 32   |
| 10   | COM_OUT_A| COM Signal<br>(17~24)  |  20 | COM_OUT_B  | COM Signal<br>(25~32)| <br>

### 5.5.2.3 Conveyor 
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


