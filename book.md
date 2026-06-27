
[__SOURCE](README.md)
# Hi7-N Controller Maintenance Manual

## Overview

本章旨在阐述面向工业机器人用户、维护及操作人员的安全要求事项。<br>
Every worker who installs, replaces, adjusts, operate, preserves and maintains the robot system must carefully read and fully understand the operation manual and maintenance manual. 此外，请将手册就近保管，以便需要时随时查看。<br>

Our company plans and implements the preservation, maintenance and operation trainings so the person using the robot should ensure that the workers working in the robot system should receive the relevant trainings.<br>
It must be ensured that only those who have completed this course can handle the robot.<br>

为确保在机器人系统中工作的人员安全，我司工业机器人用户有责任充分理解并遵守适用于相关国家的安全法律，并负责正确设计、安装和运行安全装置。<br>

The dangerous areas of the robot system, in other words, the areas where the robot, tools and peripheral devices are operating, should be equipped with safety devices according to ANSI/RIA R15.06-2012 to prevent an object, other than the workers and the workpiece, from entering the dangerous areas.<br>

The robot system should be configured in a way that it can be stopped immediately by an emergency stop device when a worker or object needs to enter the dangerous area in spite of possible danger.<br>

The workers are responsible for installing, checking and operating these safety devices.<br>
This manual has been created based on standard specifications, so some contents may differ depending on the options and model of the product that you have purchased. In addition, the contents and specifications of this manual are subject to change without prior notice to improve the performance of the product, and HD Hyundai Robotics is not responsible for situations that could be caused by inaccuracies or typos in the manual.<br>

For detailed information on the revision of the manual, you need to visit our internet website (https://www.hd-hyundairobotics.com/zh/main).<br>


## Safety Cautions

Before using the product, you must fully understand the following safety cautions for proper use, user safety, and prevention of property damage.

### Danger

{% hint style="danger" %}
Imminent danger: Incompliance may cause the death of or serious injuries to the worker.
{% endhint %}

* Make sure that the safety circuit is never ignored, modified or altered in any way.<br>
* Considering that additional problems may occur due to gravity or brake release, you must take 
a measure, before carrying out works, such as using a rope and crane that are to be used for 
transport of individual robots to prevent the brake from running down or additional accidents 
from taking place during the release of the brake.<br>

### Warning

{% hint style="warning" %}
Potential danger: Incompliance may cause injuries to the worker or damage to property, such as significant damage to the product.
{% endhint %}

* Any act of damaging the safety labels, such as relocating the name plates, warning markings, 
safety symbols, name markings and wire markings or painting over them or blocking them with 
a cover is prohibited.
* When the robot is operating, there is a risk of collision between the robot and the worker. 
Therefore, install a safety fence to prevent the worker from getting close to the robot. 
* The robot should be installed and operated according to the guidelines of ISO10218-2. In
addition, it is required to comply with the relevant requirements of international standards and national laws. Our company(or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and 
national laws or due to not reviewing the "risk assessment".
* Must observe the safety work procedures to prevent safety accidents. Do not change or ignore
safety devices or circuits under any circumstances, and pay attention to possible electric shock. In auto mode, all normal works should be performed outside the safety guard. Before carrying out works, make sure that there are no people in the operation area of the robot.
* Sufficiently check under your feet when teaching. In particular, you must perform the teaching work outside the safety guard when teaching at a high speed(250mm/s or above). 
* When it comes to changing of components or addition of optional equipment(both hardware
and software) to the robot both of which may affect safety-related functions, you must check 
whether the functions are in normal conditions, by paying attention to the items described in 
"1.11 Safety Works When Operating the Robot". 
* When installing and operating an end effector, you must perform application, maintenance and 
operation according to ISO/TR 20218-1:2018.
* When transporting the product by using lifting equipment, you should comply with the relevant 
national and local safety regulations and equipment usage guidelines. When moving the product 
using a crane, you must make sure that that no workers are under the product. Also, never work or walk under a crane or the product. 
* If a general safety guard is to be installed and used, the robot should be operated after confirming that the emergency stop operates normally. Also, check if the emergency stop input 
is disabled. This is an essential measure that must be taken in advance for the safety of workers.  
* If an automatic safety guard is to be installed and used, the robot should be operated after 
confirming that the emergency stop operates normally. Also, check if the emergency stop input 
is disabled. This is an essential measure that must be taken in advance for the safety of workers. 
* If a safety input is to be installed and used, the robot should be operated after confirming that the input function operates normally. This is an essential measure that must be taken in advance for the safety of workers. 
* The robot should be installed and operated according to the guidelines of ISO10218-2. In 
addition, it is required to comply with the relevant requirements of international standards and
national laws. Our company(or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not following the above "caution". 
* If a safety-related input is installed and enabled, you must check whether the function operates normally by referring to "1.11 Safety Measures When Operating the Robot". 
* If an emergency stop output is to be installed and used, the robot should be operated after 
confirming that the emergency stop output operates normally. This is an essential measure that 
must be taken in advance for the safety of workers. 

### Caution 

{% hint style="info" %}
Low-level danger factor: Incompliance may result in minor injury to the worker or damage to property, such as damage to the product.
{% endhint %}

* Mark the installation and dangerous areas of the robot in a way that they can be clearly
differentiated from other facilities and devices in terms of type, color and style. 
* As the emergency stop function immediately cuts off the motor power, so reckless use of the 
function may result in accumulation of fatigue that affects the durability of the robot. The 
function must be used only in emergency situations. 
* Our company is not responsible if the jogging operation does not work due to the failure of the hardware limit switch. You must check it periodically. For the measure to take in case of a failure, please refer to the troubleshooting manual. 
* You should not be negligent in paying attention to sudden movements while entry is made 
possible. Under any circumstances, you must avoid approaching the robot without preparing for 
possible emergency situation. 
* In the case of trial-operation, there may be a design error, teaching error or defect in
manufacturing  with  regard  to  the  entire  system  including  the  teaching  program,  jigs, and sequencing. For this reason, you should work with elevated safety awareness in trial-operation. Multiple factors can contribute to safety accidents. Observe the following measures considering that safety is very important when trial-operating the robot. 
* During maintenance and inspection of the manipulator, the robot arm may fall, or there could 
be a different type of danger. So, you must proceed with the work according to the instructed 
procedures.
* When moving the axis of the robot that has no driving force applied, there is a risk of the axis dropping due to gravity and also an additional risk due to the release of the brake system. So, you must proceed with the work according to the instructed procedures.
* Before turning on the power, check that there is no worker inside the robot operation area and you are in a safe place. 
* Before installing the product, you must perform a sufficient risk assessment and then set the 
safety functions based on the assessment results. For details on safety functions, refer to "1. 
Safety" section. 
* When installing and repairing the product, contact the customer support team and ask an expert. 
* Do not install and use the product in an area that has lots of dust or is dirty. Dust or foreign substances may cause product failure or performance problems.  
* Mark the installation and dangerous areas of the robot in a way that they can be clearly
differentiated from other facilities and devices in terms of type, color and style. 
* If the product is not installed in the recommended locations, the performance and service life of the product may be reduced. Install and use the product according to the recommendations. 
  - Before connecting the cables, turn "off" the controller's main power switch and then lock it by using a padlock.  
  - The controller has DC400V charged energy. Be careful. Wait at least 5 minutes after turning 
"off" the power switch, and then wait 5 minutes at least to discharge the charged energy. 
  - When handling the PCB, take precautions not to allow static electricity to damage it 
  - Wiring and connection of wires must be performed by qualified personnel. 
* Since the contact part of the connector for each robot may be different from the figure above, you must read the relevant robot maintenance manual carefully before connecting the wire 
harness. 
  - When performing the wiring work for the controller and manipulator, separate the signal line and the power line. In addition, use a separate duct for the high power line and the signal line respectively. 
  - Use a protective cover for the wiring, as a measure to prevent the wiring from getting
damaged when people are passing nearby. 
  - Before supplying the primary power, you must check again the relationship with regard to 
connection, the power specification and power supply specification of the controller. 
* The person in charge of maintenance should work after understanding the placement of various 
devices and parts and their functions inside the controller. 
* The DIP switch is set to OFF mode when shipped from the factory, and the setting should not 
be changed arbitrarily by the user. 
* The user cannot change the following items arbitrarily, and needs to refer to them only when 
required to reprogram through FPGA JTAG. 
* The drive module differs depending on the type of the robot, so you must check the type when 
replacing it.
  - Do not release more than two axes at the same time. 
  - Must keep a safe distance from the robot first before using the brake release unit. 
  - Use the brake release unit after preparing for the dropping of the robot's axis by using
equipment such as a crane. 
  - Check the safety matters while working in a group of at least 2 people.
* When using the brake release unit, follow the procedures below. 
  - Turn off the AC220V power switch and check that the DC24V power switch is turned off. 
  - Connect the AC power cable to the AC power connector. 
  - Turn on the AC220V power switch.  
  - Turn on the DC24V power switch. 
* When the use of the brake release unit is finished, follow the procedures below. 
  - Turn off the DC24V power switch.
  - 关闭 AC220V 电源开关。
  - 断开 AC 电源电缆。
  - 不要同时使用 AC220V 电源和 DC24V 电池电源。
* 要使用商业远程 IO，必须提供现场总线通信。因此，您应该参考上述第 5.1 节配置 PCI 通信卡。
* 驱动单元因机器人的类型而异，因此在更换驱动单元时必须检查类型。
* 在运输产品时，您应保持正确的姿势，并至少由两名工人一起操作。否则，可能会导致后背、手臂和腿部等身体部位受伤。
* 如果您使用起重设备运输产品，您应遵守相关国家和地方的安全法规及设备使用指南。
* 在运输产品时，您应充分了解手册中与运输相关的内容并遵循说明。我们公司对因客户运输产品而造成的任何损坏或破损不承担责任。
* 这些是日常维护和检查需要准备的重要部分。
* 这些是购买多个单元时需要准备的维护部件。
[__SOURCE](0-about-this-manual/README.md)
# 关于手册
[__SOURCE](0-about-this-manual/precautions.md)
# 注意事项

{% include file="zh/precautions.md" %}
[__SOURCE](0-about-this-manual/safety-notice.md)
# 安全警告

{% include file="zh/safety-notice.md" %}
[__SOURCE](1-safety/README.md)
# 1. 安全
[__SOURCE](1-safety/1-applied-standard.md)
# 1.1. 适用标准

适用于该产品的安全标准如下。
* ANSI/RIA/ISO 10218-1:2011 机器人和机器人设备 - 工业机器人安全要求 - 第 1 部分：机器人

* ANSI/RIA R15.06-2012 - 工业机器人和机器人系统 - 安全要求

* ISO 10218-2:2011 机器人和机器人设备 - 工业机器人安全要求 - 第 2 部分：机器人系统和集成

* IEC 61508-1:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 1 部分：一般要求

* IEC 61508-2:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 2 部分：电气/电子/可编程电子安全相关系统的要求

* IEC 61508-3:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 3 部分：软件要求

* IEC 61508-4:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 4 部分：定义和缩略语

* IEC 61508-5:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 5 部分：确定安全完整性等级的方法示例

* IEC 61508-6:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 6 部分：IEC 61508-2 和 IEC 61508-3 应用的指南

* IEC 61508-7:2010 电气/电子/可编程电子安全相关系统的功能安全 - 第 7 部分：技术和措施概述

* IEC 61800-5-1:2007/A1:2017 可调速电力驱动系统 - 第 5-1 部分：安全要求 - 电气、热和能量

* IEC 61800-5-2:2015 可调速电力驱动系统 - 第 2 部分：一般要求 - 低压可调速交流电力驱动系统的额定规格

* ISO 13849-1:2015 机械的安全性 - 控制系统的安全相关部分 - 第 1 部分：设计的一般原则

* ISO 13849-2:2012 机械的安全性 - 控制系统的安全相关部分 - 第 2 部分：验证

* IEC 62061:2005/A2:2015 机械的安全性。安全相关电气、电子和可编程电子控制系统的功能安全

* IEC 61800-3:2017 可调速电力驱动系统 - 第 3 部分：EMC 要求和特定测试方法

* IEC 61000-6-7:2014 电磁兼容性 (EMC) - 第 6-7 部分：通用标准 - 针对在工业地点安全相关系统 (功能安全) 中执行功能的设备的抗扰度要求

* IEC 61326-3-1:2017 测量、控制和实验室用电气设备。EMC 要求。第 3-1 部分：安全相关系统和旨在执行安全相关功能的设备的抗扰度要求 (功能安全) - 一般工业应用

* IEC 60204-1:2016 机械的安全性 - 机器的电气设备 - 第 1 部分：一般要求

* ISO 11161:2007 机械的安全性 - 集成制造系统 - 基本要求
[__SOURCE](1-safety/2-safety-performance.md)
# 1.2. 安全性能

工业机器人安全模块的性能如下。

SafeSpace2.0 的紧急停止和外部设备接口（基本安全 I/O, PROFIsafe）的安全性能如下。

表 1-1 安全模块的安全性能
|            **项目**          | **安全性能** |         **适用标准**         |
| :--------------------------: | :-------: | :-----------------------: |
|              HFT             |     1     | IEC 61508/62061/61800-5-2 |
| SIL (安全完整性等级)       |     3     | IEC 61508/62061/61800-5-2 |
|           类别              |     4     |        ISO 13849-1        |
|    PL (性能等级)            |     e     |        ISO 13849-1        |
|    		PFH    			   |1.34217E-08|        ISO 13849-1        |

其他安全功能的安全性能如下。
|            **项目**          | **安全性能** |         **适用标准**         |
| :--------------------------: | :-------: | :-----------------------: |
|              HFT             |     1     | IEC 61508/62061/61800-5-2 |
| SIL (安全完整性等级)       |     2     | IEC 61508/62061/61800-5-2 |
|           类别              |     3     |        ISO 13849-1        |
|    PL (性能等级)            |     d     |        ISO 13849-1        |
[__SOURCE](1-safety/3-safety-edu.md)
# 1.3. 安全培训

为了有效地使用产品的功能，您必须完全理解手册的内容，然后正确安装、使用和维护产品。产品用户负责充分理解并遵守机器人安装和使用地区的安全法律，并且还负责正确设计、安装和操作安全设备，以确保在机器人系统中工作的用户的安全。

* 所有安装、使用和维护机器人系统的工作人员必须仔细阅读手册并完全理解其内容。特别是，他们必须充分理解安全警告(![img](../_assets/삼각형1.png))。
* 我们公司计划并实施产品的安装、使用和维护培训。因此，产品用户和工作人员必须在使用产品之前完成相关培训课程。
* 负责教授和检查机器人的工作人员必须在使用机器人之前完成机器人使用和安全培训。安全培训课程覆盖的内容包括以下项目。
  - 安全的概念，以及安全设备的目的和功能
  - 机器人安全处理的程序
  - 机器人的性能和潜在危险以及机器人系统
  - 包括与机器人特定应用相关工作的项目
[__SOURCE](1-safety/4-risk-assess.md)
# 1.4. 风险评估  

在配置包括机器人在内的集成系统时，风险评估是大多数国家作为法律要求处理的最关键因素之一。集成系统的风险评估不能仅针对单个机器人进行，因为机器人的安全评估将取决于机器人如何集成到系统中。

系统管理员应根据ISO 12100和ISO 10218-2的指南配置和操作系统，以进行风险评估。<br>
您应考虑整个集成系统的过程，包括机器人，进行风险评估。风险评估的主要目标如下：
* 机器人使用的基本设置和机器人的教学 
* 故障诊断和维护 
* 已安装机器人的正常操作

在安装机器人并配置系统后，必须进行风险评估。风险评估主要确定机器人集成系统中安全设备的适当性，以及额外紧急停止设备和其他安全设备的必要性。<br>
了解适当的安全设备并正确配置机器人集成系统非常重要。您应根据手册中的相关信息配置集成系统。<br>
有关配置安全功能的详细信息，请参阅“1.8. 安全功能”。此外，在特定位置安装机器人或使用安全I/O配置安全相关功能时，机器人集成系统风险评估中的重要事项如下：
* 严重性 
* 接触风险的频率 
* 可能的发生 
* 可能的避免<br>

在配置集成系统的过程中，如果机器人的安全相关功能未能充分消除风险因素，则在风险评估期间可以检查额外保护设备的必要性。
[__SOURCE](1-safety/5-potential_risk.md)
# 1.5. 潜在风险

如果与机器人连接的集成系统的风险评估结果显示，仅依靠机器人的安全相关功能未能充分消除风险因素，则必须采取额外的保护措施。<br>
建立额外保护措施时需要考虑的事项如下：
* 安装过程中，手指可能会夹在机器人底座和安装桌之间。
* 由于操作区域内障碍物或工具的锋利边缘或尖部导致的伤害（刺伤、穿透伤等）。
* 由于与机器人碰撞造成的伤害（瘀伤、摔倒、骨折等）。
* 由于机器人周围的障碍物造成的伤害（刺伤、穿透伤、骨折等）。
* 由于固定部件没有完全固定而可能发生的伤害。
* 在与有毒和危险物质一起工作时可能发生的伤害（皮肤损伤、呼吸急促等）。
* 由于突然停电，工件与工具分离。
* 由于混淆其他设备的紧急停止开关而导致的错误。
* 由于随意更改安全相关功能设置而导致的错误。

可能发生的风险类型取决于系统配置，因此在使用集成系统之前，必须进行风险评估。
[__SOURCE](1-safety/6-validity-responsibility.md)
# 1.6. 有效性和责任 

必须根据机器人安装和使用所在国家和地区的安全法规和法律遵守安全要求。机器人集成系统的供应商和用户有多种责任，包括以下项目。
* 机器人集成系统的风险评估
* 根据风险评估结果增加和移除安全设备
* 检查集成系统是否正确配置、安装和设置
* 建立使用集成系统的方法和指南，并为用户提供培训
* 安全设备的管理（禁止用户自行更改和操作安全设备）
* 提供与产品使用和安全相关的重要信息，以及联系信息
* 提供包括手册在内的各种技术文件

本手册中的安全信息并未涵盖使用产品时可能出现的所有风险因素和情况。
[__SOURCE](1-safety/7-safety-label.md)
# 1.7. 安全标签

姓名牌、警告标记、安全符号等贴在控制器的内外。任何破坏安全标签的行为，如移动姓名牌、警告标记、安全符号、姓名标记和电线标记或者在其上涂漆或用盖子遮挡，都是禁止的。<br> 以可以与其他设施和设备在类型、颜色和样式上区别开来的方式标记机器人的安装和危险区域。 

![](../_assets/fig_1.1_safety_label.png)<br>
图 1.1 安全标签<br>

表 1-2 安全标签<br>
![](../_assets/1.7._안전_라벨(Hi6)_en.png)<br>

{% hint style="warning" %}
任何破坏安全标签的行为，如移动姓名牌、警告标记、安全符号、姓名标记和电线标记或者在其上涂漆或用盖子遮挡，都是禁止的。 
{% endhint %}

{% hint style="info" %}
以可以与其他设施和设备在类型、颜色和样式上区别开来的方式标记机器人的安装和危险区域。
{% endhint %}
[__SOURCE](1-safety/8-safety-function/README.md)
# 1.8. 安全功能
 
机器人的安全系统采用双重配置设计（HFT=1），以满足[ISO13849-1:2015]的安全性能（PL）= d Cat3 和[IEC62061:2005]的安全完整性级别（SIL）2，并持续监控安全相关设备的状态。当自我诊断检测到错误或输入安全相关信号时，安全功能将根据基于风险评估确定的停止情况分类停止机器人。<br>
此外，当安全电路的任意双重开关被激活时，安全功能将切断电动机驱动功率和刹车驱动功率，以确保安全状态。相关状态的信息可以通过教学挂件检查。 

{% hint style="danger" %}
确保安全电路绝不被忽视、修改或以任何方式改变。
{% endhint %}

机器人的安全相关主要功能如下。
[__SOURCE](1-safety/8-safety-function/1-key-safety-function.md)
# 1.8.1. 主要安全功能  

* 紧急停止 (IEC 60204-1,10,7)<br>
控制器和教学挂件上各有一个紧急停止按钮。如有必要，可以将额外的紧急按钮连接到机器人的安全链电路中。<br>
紧急停止功能的优先级高于机器人的所有其他控制功能。该功能会立即切断机器人各个轴电机的电源，停止机器人并使机器人控制的安全相关功能无法使用。  

{% hint style="info" %}
由于紧急停止功能会立即切断电机电源，因此随意使用该功能可能会导致疲劳积累，从而影响机器人的耐用性。该功能仅能在紧急情况下使用。 
{% endhint %}

![](../../_assets/그림_1.2_제어기,_티칭펜던트_비상정지_스위치_en.png)<br>
图 1.2 控制器和教学挂件上的紧急停止按钮

![](../../_assets/그림_1.3_추가_비상정지_장치_연결.png)<br>
图 1.3 附加紧急停止装置的连接<br>

* 保护停止 (ISO 10218-1:2011)<br>
机器人应具有多个安全输入，以便与外部安全设备如安全护栏、安全垫和安全灯一起使用。当机器人自身和外围设备发出输入时，这些安全输入将使机器人停止，确保安全状态。<br>
有关连接安全输入的详细信息，请参阅 "4.3.2. 安全模块 (BD642)"。 

* 速度限制 (EN ISO 10218-1:2011)<br>
在手动操作模式下，机器人的速度限制为最大 250 mm/s。速度限制不仅适用于 TCP（工具中心点），还适用于所有在手动模式下操作的机器人其他部分。还应能够监测安装在机器人上的设备的速度。 

* 操作区域限制 (ANSI/RIA R15.06-2012)<br>
在应用机器人时，为确保足够的安全区域，可以通过使用硬件限制或挡块来限制机器人的操作范围。此功能可以在机器人与外部安全设备如安全护栏发生碰撞时，最小化损害。轴 1、2 和 3 主要通过挡块或硬件限制来限制。如果由于机械挡块或硬件限制而改变操作范围，则应在软件中更改操作范围限制参数。有关更改，请参阅操作手册。<br>
每个轴的操作区域限制可以由用户更改，发货时设置为机器人的最大操作范围。Hi7 控制器的安全系统可选择支持最多 4 个硬件限位开关。有关连接事宜，请参阅 "4.3.2. 安全模块 (BD642)"。

* 操作模式选择 (ANSI/RIA R15.06-2012)

您可以在手动、自动或远程模式下操作机器人。手动模式下的最大速度限制为 250 mm/s，您只能使用教学挂件进行操作。此外，可以通过将模式开关配置为选项，额外安装在控制面板上。 
有关操作的详细信息，请参阅操作手册。
[__SOURCE](1-safety/8-safety-function/2-related-other-func.md)
# 1.8.2. 其他相关功能
了解以下事项并采取措施，如果因机器人手臂导致意外而夹到人。

* 手动刹车释放

{% hint style="danger" %}
考虑到由于重力或刹车释放可能会发生额外问题，请在进行作业之前采取措施，例如使用用于运输单个机器人的绳索和起重机，以防止刹车松动或在释放刹车时发生额外事故。
{% endhint %}

  - 从控制器中断开电源后，将刹车释放单元连接到机器人的指定连接器或控制器的内部板连接器，然后根据需要释放每个轴的手动刹车。
  - 请参考每个机器人的维护手册，了解每个机器人的各个轴的信息，以及每个机器人的指定运输设备（例如，绳索、起重机）。

当机器人被限位开关停止时，可以通过在常量设置模式下使用教学挂件来移动机器人。在根据现场情况指定软限位后，确保由经过培训的工作人员进行安装。

{% hint style="info" %}
如果由于硬件限位开关故障而导致操作无法进行，我公司不承担责任。
您必须定期检查。有关故障情况下应采取的措施，请参考故障排除手册。
{% endhint %}
[__SOURCE](1-safety/9-stop.md)
# 1.9. 停止
Hi7 控制器的安全系统可以处理如下所示的停止操作。安全输入可以根据 IEC 60204-1 中指定的停止分类标准进行分类。

* 停止分类 立即去除机器执行器的电源时发生停止（非控制停止）。<br>
→ 紧急停止按钮

* 停止分类 1：控制停止，在该情况下，机器执行器仍然具有可以用于实现停止的电源。停止实现后将移除电源。<br>
→ 除紧急停止按钮外的安全输入
[__SOURCE](1-safety/10-safety-measures-install/README.md)
# 1.10. 安装时的安全措施
[__SOURCE](1-safety/10-safety-measures-install/1-safety-guard-install.md)
# 1.10.1. 安装安全围栏 

{% hint style="warning" %}
当机器人运行时，机器人与工人之间存在碰撞风险。因此，安装安全围栏以防止工人靠近机器人。
{% endhint %}

当机器人运行时，机器人与工人之间存在碰撞风险。因此，根据 ISO 13855:2010 安装安全围栏，以防止工人靠近机器人。<br>
配置系统，以确保在机器人运行期间，当工人打开安全围栏的门并接近设备时，无论出于何种原因，例如检查机器人或焊接夹具、进行刀具磨尖或更换刀具等，机器人都会停止。<br>

![](../../_assets/그림_1.4_안전펜스_연결.png)<br>
图 1.4 安全围栏的连接<br>

来源：ISO 13855:2010 机械安全 - 关于人体部位接近速度的安全防护装置的定位
 
表 1-3 安全围栏的安装标准
![](../../_assets/표_1-3_안전펜스_설치_규격.png)<br>

来源：ISO 13855:2010 机械安全 - 关于人体部位接近速度的安全防护装置的定位

* 安全围栏应覆盖机器人的操作区域，并应确保足够的空间，以便工人在进行教学、维护等工作时不会干扰。
安全围栏应制作坚固，以防止其轻易被移动，并应结构设计成不允许人们越过安全围栏进入围栏内。
* 原则上，要求安装和使用没有不平或锋利部件的固定类型安全围栏。
* 应安装入口门，以允许人员进入安全围栏，并且在门上必须安装安全插头，以确保门在未拆除插头时不会打开。<br>
此外，布线应配置为在安全插头被拆除或安全围栏被打开时，使电机关闭且制动处于保持状态。
* 如果想在安全插头拆除时仍操作机器人，则应配置布线使机器人以低速回放运行。
* 将机器人的紧急停止按钮安装在操作员可以快速按压的位置。
* 如果不安装安全围栏，则应安装光电开关和垫开关等安全装置，覆盖在安全防护范围内机器人的整个区域，作为安全围栏的替代设备，使机器人在有人进入安全围栏时能自动停机。
* 确保机器人的操作区域（危险区）可以通过某种方式识别，例如在地面上涂漆。
[__SOURCE](1-safety/10-safety-measures-install/2-place-robots-peripherals.md)
# 1.10.2. 机器人的放置及外围设备

{% hint style="warning" %}
机器人应根据ISO 10218-2的指南进行安装和操作。
此外，还需遵守国际标准和国家法律的相关要求。<br>
我们公司（或制造商）将不对因不遵守国际标准和国家法律的相关要求或未审查“风险评估”而发生的任何事故负责。
{% endhint %}

产品的安装应由符合相关国家和地方法规和法律的合格安装人员进行。

* 解包产品时，请检查在运输或拆包时可能发生的损坏。
* 在拆包后安装产品之前，您必须检查安全规定、说明、与产品安装和使用环境相关的信息，并充分了解安装方法。
* 连接控制器或外围设备的主电源时，请在检查供电侧电源是否关闭后再进行连接。由于主电源使用高电压，存在电击风险。
* 在安全围栏入口处张贴“操作期间禁止进入”标志，并通知工作人员注意事项。
* 将控制器、联锁面板和其他控制面板放置在可以从安全围栏外操作的位置。
* 安装操作台时，也要附加一个紧急停止按钮。无论您在哪里操作机器人，都应能够在紧急情况下停止机器人。
* 不要让操纵器、控制器、联锁面板、计时器等的接线或管道被工人的脚绊倒或直接被叉车踩到。否则，工人可能会遭遇电击或电线断开的事故风险。

* 将控制器、联锁面板和操作台放置在可以充分看到操纵器操作的位置。如果机器人在观察不到机器人操作的区域异常操作，或者工人在该区域处理某些事情，则在操作期间可能会发生重大事故的风险。
* 如果所需的机器人操作区域小于允许的机器人操作区域，则应限制机器人操作区域。可以通过软限制、硬限制、机械挡块等来限制。即使由于机器人操作失误等异常操作导致机器人偏离正常操作区域，操作区域限制功能也会提前停止机器人。
* 在焊接期间，飞溅物可能会落到工人身上或附近，导致烧伤或火灾。在能够充分看到操纵器运动范围的地方安装光挡板、罩等。
* 对于显示机器人自动和手动操作模式的装置，应安装易于从远处识别状态的设备。在启动自动模式操作时，蜂鸣器或警报将很有用。
* 确保机器人外围设备上没有突起部分。如有必要，请在其上放置保护罩。否则，通常情况下，工人与突起部分接触可能会发生事故，而在机器人突然移动时，工人可能会因惊讶而跌倒，导致重大事故发生。
* 不要设计需要工人将手伸入安全围栏内进行工件进出操作的系统。

![](../../_assets/그림_1.5_LCD핸들링_로봇의_빔형_안전펜스.png  )<br>
图 1.5 用于LCD处理机器人的梁型安全围栏<br>

工业机器人外围设备和工人的放置

![](../../_assets/그림_1.6_산업용_로봇의_원통형_안전펜스.png  )<br>
图 1.6 用于工业机器人的圆柱型安全围栏<br>
[__SOURCE](1-safety/10-safety-measures-install/3-robot-install.md)
# 1.10.3. 安装机器人

{% hint style="info" %}
机器人应根据ISO 10218-2的指南进行安装和操作。此外，必须遵守国际标准和国家法律的相关要求。<br>
我们的公司（或制造商）将不对因未遵守国际标准和国家法律的相关要求或未审查“风险评估”而发生的任何事故负责。
{% endhint %}

产品的安装应由合格的安装人员根据相关国家和地方的规定和法律进行。
* 拆包时，检查产品在运输或拆包过程中可能发生的损坏。
* 在拆包后安装产品之前，必须检查与产品安装和使用环境相关的安全规定、说明和信息，并充分理解安装方法。
* 使用机器人的工人应充分了解应用和辅助手册中描述的内容，并熟练操作和处理工业机器人。
* 安装机器人的工人应能够在安装过程中应用安全说明，如果出现问题。
* 系统供应商应保证用于安全功能的所有电路确实执行其功能。
* 机器人的主电源应安装在可以从机器人操作区域外部切断的方式。
* 系统供应商应确保所有用于安全功能的电路安全地执行其功能。
* 急停按钮应位于工人能够轻松接近其以紧急停止机器人的位置。
* 考虑到操纵器的尺寸和操作范围，确保与周围设备没有干扰。
* 避免将机器人安装在直接阳光照射、高湿度、周围有油或化学品以及空气中有大量金属粉末或爆炸性气体的地方。
* 在环境温度为0 - 45 ℃的区域安装机器人。
* 确保有足够的空间以便于拆卸和检查机器人。
* 安装安全围栏，防止他人进入机器人操作范围。
* 确保机器人操作区域内没有障碍物。
* 在将机器人安装在直接阳光照射的区域或靠近加热元件时，应根据控制器的热力学状态采取措施。
* 在将机器人安装在空气中有大量灰尘（例如金属粉末）的区域时采取额外措施。
* 以不让焊接电流流入机器人的方式进行安装。换句话说，点焊枪与机器人手腕之间应有绝缘。
* 由于接地对于防止因噪音和电击引起的故障很重要，应按照以下方式安装机器人。
  - 在设置为3型接地时安装专用接地端子。
  - 将接地线连接到控制面板内部的接地母线。
  - 当操纵器直接由锚等接地到地面时，控制器侧和操纵器侧将形成两点接地，形成闭合电路，这反而可能因噪声等原因导致故障。在这种情况下，将接地线连接到操纵器的底座部件，但不连接到控制器侧。此外，如果机器人停止时有晃动，可能是接地不完整或存在闭合电路。需再次检查接地。
  - 如果使用带内置变压器的枪，则有掉落的风险，因为主电源电缆直接连接到点焊枪。在这种情况下，为了保护控制面板并防止电击，将接地线直接连接到操纵器的底座部件，而不连接到控制器。
* 根据每台机器人的维修手册进行安装。
* 在指定适合现场情况的软极限后，硬限制的定位和调整必须由经过培训的工人执行。安装后，必须检查功能是否正常。
[__SOURCE](1-safety/11-robot-safety-measures-op/README.md)
# 1.11. 安全操作机器人时的工作

{% hint style="warning" %}
必须遵守安全工作程序以防止安全事故。在任何情况下都不得更改或忽视安全设备或电路，并注意可能的电击。<br>
在自动模式下，所有正常工作应在安全护栏外进行。在进行工作之前，必须确保机器人操作区域内没有人。 
{% endhint %}
[__SOURCE](1-safety/11-robot-safety-measures-op/1-robot-safety-measures-op.md)
# 1.11.1. 操作机器人时的安全措施

在操作机器人时，请注意以下措施，因为安全至关重要。

* 操作或可能操作机器人劳动者和监督者应接受一定的培训。除了那些完全了解机器人安全和功能并被相应认可的人外，任何不合格的人不得操作机器人。
* 在操作机器人之前，必须检查产品是否由合格的安装人员按照相关国家和地区的规定和法律进行安装。
* 在操作机器人之前，检查安全功能是否正常工作。
* 必须佩戴安全头盔、护目镜和安全鞋。
* 两个人必须一起工作。一人应进行示教，另一人应在操作面板上监控。两人中应有一人随时准备按下紧急停止开关，另一个应在操作区域内保持足够小心地快速完成工作。此外，在开始工作之前检查撤离通道。
* 在确认安全护栏内没有工作人员后再通电。
* 教学等工作原则上应在机器人安全护栏外进行。然而，当需要在操作范围内停止系统并工作时，工作人员应在进入时携带模式开关钥匙（或切换到自动模式的开关）或安全插头。这样的行为是为了确保没有其他工作人员意外地将机器人切换到自动操作模式。此外，要特别注意机器人操作的方向，以防止机器人故障或在错误条件下操作。<br>
* 监督者应注意以下事项。
  - 监督者应位于可以完全看到机器人的位置，并应专注于监督职责。
  - 如果发现任何问题，请立即按下紧急停止按钮。
  - 除了参与工作的人以外，其他人不得留在操作范围内。

* 在手动操作模式下，速度应限制为最大250 mm/sec。在此期间，您应与安全护栏外的工作人员一起做好准备，如果发生问题随时按下紧急停止开关。
* 在高速度模式下手动操作机器人时，应从安全护栏外继续操作。
* 在进行教学工作时，应悬挂标志【教学进行中】。
* 当需要进入安全护栏内时，工作人员应拔出安全插头或同等设备，并在进入时携带。
* 不要在教学地点或其周围使用可能产生噪音的设备。
* 在观察教学点时，切勿仅凭手感操作教学挂件上的机器人操作按钮。相反，应在用肉眼检查时操作按钮。

{% hint style="warning" %}
在教学时，务必仔细检查脚下。特别是，当以高速度（250mm/s或更高）进行教学时，必须在安全护栏外进行教学工作。
{% endhint %}

* 当发生异常时采取以下措施。
  - 如果发现异常操作，请立即按下紧急停止按钮。
  - 如果在紧急停止后需要检查异常，必须检查相关设施的停止状态。
  - 如果机器人因电源异常自动停止，首先检查机器人是否完全停止，然后调查原因并采取措施。
  - 如果紧急停止装置无法正常工作，请立即切断主电源，然后调查原因并采取措施。
  - 异常原因的调查不得由指定以外的人员进行。在紧急停止后，必须在充分确定异常原因并采取相应措施后重新启动系统。

* 针对机器人操作和操作方法以及发生异常时的处理措施，应根据安装位置和工作细节制定适当的工作规定。此外，工作应按照工作规定进行。
* 机器人停机时应采取的预防措施
  - 必须避免在认为机器人已停止的情况下鲁莽接近机器人。当您接近认为已停止的机器人时，机器人可能会突然移动，造成事故。机器人将在以下情况下处于停止状态。

表1-4 机器人在停止模式下的状态
<table>
<tbody>
<tr class="odd">
<td><p>编号</td>
<td><p>机器人状态</p></td>
<td><p>驱动源</p></td>
<td><p>进入</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>处于临时停止模式</p>
<p>（轻微异常，临时停止开关）</p></td>
<td><p>开</p></td>
<td><p>X</p></td>
</tr>
<tr class="odd">
<td><p>2</p></td>
<td><p>处于紧急停止模式</p>
<p>（重大异常，紧急停止开关和安全门）</p></td>
<td><p>关</p></td>
<td><p>O</p></td>
</tr>
<tr class="even">
<td><p>3</p></td>
<td><p>等待来自外围设备的输入信号</p>
<p>（启动联锁）</p></td>
<td><p>开</p></td>
<td><p>X</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>播放完成</p></td>
<td><p>开</p></td>
<td><p>X</p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>等待中</p></td>
<td><p>开</p></td>
<td><p>X</p></td>
</tr>
</tbody>
</table>

{% hint style="info" %}
即使在进入可能的情况下，也不能忽视对突然动作的注意。在任何情况下都必须避免毫无准备地靠近以应对可能的紧急情况。
{% endhint %}

* 如果在临时停止期间需要打开入口门以采取对轻微异常的措施（如喷嘴接触、沉积检测和弧异常），应采取与进入时相同的措施。

* 在完成机器人操作后，请清理安全护栏内，以确保没有工具、油或异物遗留。如果操作区域被油污染，或有工具遗留在操作区域，可能会导致如摔倒等事故。确保始终进行整理和组织。
[__SOURCE](1-safety/11-robot-safety-measures-op/2-robot-safety-measures-test-run.md)
# 1.11.2. 机器人试运行时的安全措施

{% hint style="info" %}
在试运行的情况下，可能存在设计错误、教学错误或制造缺陷，包括教学程序、夹具和排序等整个系统。因此，在试运行时应提高安全意识。多个因素可能导致安全事故。考虑到安全在试运行机器人时非常重要，请遵循以下措施。
{% endhint %}

* 在操作机器人之前，检查紧急停止按钮和停止按钮等按钮的功能，以及相关信号的功能。之后，检查与异常检测相关的操作。首先，检查所有使机器人停止的信号非常重要。当预计会发生事故时，最重要的是停止机器人。

* 在进行机器人的试运行时，首先将其设置为手动模式，输入一个可以测试所有轴的作业程序，然后重复每个步骤超过 1 次循环以检查操作。当机器人移动时，打开安全防护罩或移除启用开关（教学挂件上的启用开关）以检查机器人是否停止。如果发现问题，请按下紧急停止按钮以检查机器人是否停止。如果紧急停止装置未能正常工作，请立即关闭主电源。之后，应联系负责的售后人员。如果没有问题，则依次增加速度（50% → 75% → 100%），并通过重复每个循环超过 1 次来检查操作。开头以高速运行可能会导致重大事故。

* 无法预测试运行期间会发生什么问题。在试运行期间，切勿进入安全围栏。由于可靠性低，发生意外事故的可能性很大。
[__SOURCE](1-safety/11-robot-safety-measures-op/3-robot-safety-measures-auto-run.md)
# 1.11.3. 自动操作的安全措施

在自动模式下操作机器人时，请考虑安全非常重要，遵守以下措施。

* 在安全围栏入口处放置标志 [操作期间禁止进入] 并要求工作人员在操作期间 refrain from entering。 如果机器人停止，您可以在判断情况后进入安全围栏内。
* 在启动自动操作之前，必须检查安全围栏内是否有工作人员。如果您在未检查内部是否有工作人员的情况下工作，可能会导致涉及人员的事故。
* 在启动自动操作时，首先检查程序编号、步骤编号、模式、启动选择等是否处于自动操作的正确状态。如果在选择了不相关的程序或步骤时启动机器人，机器人可能会产生意外行为，导致事故。
* 在启动自动操作之前，提前检查机器人处于可以启动自动操作的位置。还要检查程序编号或步骤编号是否与机器人位置匹配。即使程序或步骤是正确的，如果机器人在不同的位置，由于与正常操作不同的操作可能会发生事故。
* 在开始自动操作时，随时准备立即按下紧急停止按钮。如果发生意外的机器人操作或意外情况，请立即按下紧急停止按钮。
* 检查机器人的操作路径、操作状态和操作声音等，以判断是否存在任何异常状态。机器人可能会突然造成故障等异常，但在故障发生之前可能会出现一些症状。为了提前预测这一点，需要很好地理解机器人的正常操作状态。
* 如果发现任何异常，立即进行紧急停止并采取适当措施。没有采取适当措施使用机器人可能导致严重故障，可能导致生产中断和涉及人员的重大事故。
* 在完成措施并在异常发生后检查操作时，不要在工作人员仍在安全围栏内时操作机器人。由于可靠性低，可能会发生其他异常等意外事故。
* 在选择自动模式之前，如果有已停止的安全装置功能，应在恢复该功能至完全正常状态后再进行工作。
[__SOURCE](1-safety/12-enter-fence-safety-measure.md)
# 1.12. 进入安全防护区域或围栏内的安全措施

当需要进入机器人操作区域的安全门时，接受过特定培训的工人和监督员应成对进行工作。此外，他们必须佩戴安全头盔、防护眼镜和安全鞋。监督员应随时准备按下紧急停止开关，工人在进入时必须携带操作手柄，以便其他人无法操作机器人。必须在控制面板上张贴标志，指示机器人正在操作中。

当您进入机器人操作区域时，必须充分了解以下事项。

* 除教学人员外，任何人不得进入机器人操作区域。
* 控制器的操作设置模式应为手动模式。
* 始终穿着经过认证的工作服。
* 操作控制器时，请勿戴手套。
* 不要让内衣、衬衫、领带等露出工作服。
* 不要佩戴大型珠宝，如耳环、戒指或项链。
* 必须穿戴安全鞋、安全头盔和防护眼镜，并在必要时应佩戴安全装备，如安全手套。
* 在操作机器人之前，检查紧急停止电路是否正常工作，以便在按下控制面板或操作手柄上的紧急停止按钮时能关闭电机。
* 在面朝操作者的位置工作。
* 遵循预定的工作程序。
* 考虑到机器人可能会意外向您冲来，您应准备好撤离的方法或地点。

{% hint style="info" %}
即使在可以进入的情况下，您也不应该忽视对突然移动的注意。无论如何，必须避免在没有准备应对可能紧急情况的情况下接近。
{% endhint %}
[__SOURCE](1-safety/13-maintenance-safety-measures/README.md)
# 1.13. 维护和检查时的安全措施
[__SOURCE](1-safety/13-maintenance-safety-measures/1-controller-maintenance-safety-measures.md)
# 1.13.1. 维护和检查控制器时的安全措施

在维护和检查机器人控制器时，请遵守以下安全措施。 
* 维护和检查工作应仅由经过特殊维护培训且完全理解相关内容的人执行。 
* 按照控制器维护和检查程序进行工作。 
* 对于维护和检查工作，必须检查周围的安全情况，并确保有通道或地点以避免危险，然后安全地进行工作。 
* 在执行日常检查或维护机器人或更换零件之前，必须先切断电源。此外，为了防止其他工人无意间开启电源，请在主电源上放置类似“[禁止开机]”的警示标记。 
* 始终使用指定的替换零件。 
* 如果需要打开控制器门，必须先切断电源，然后等待大约3分钟再开始工作。 
* 当在控制器内部进行维护和检查工作时，如果未确保足够的照明，请使用外部照明。 
* 不要触摸伺服放大器的散热器和再生电阻，因为它们会产生过多的热量。维护后，检查工具、异物等是否遗留在控制器内部，然后再安全地关闭门。 
* 在没有关闭电源或实施锁定程序的情况下进行维护工作，可能会导致操作人员因机器人突然、意外启动而造成严重伤害或死亡。
[__SOURCE](1-safety/13-maintenance-safety-measures/2-robot-maintenance-safety-measures.md)
# 1.13.2. 维护与检查机器人系统和操纵器时的安全措施

在维护和检查机器人系统及操纵器时，请遵守以下安全措施。
* 请参考控制器维护和检查的安全措施。
* 在维护和检查机器人系统及操纵器时，按照指示的程序进行工作。
* 必须切断控制器的主电源。为了防止其他工作人员重新启动电源，请在主电源上放置类似[禁止通电]的警告标记。

{% hint style="info" %}
在维护和检查操纵器时，机器人手臂可能会掉落，或可能会有其他类型的危险。因此，必须按照指示的程序进行工作。
{% endhint %}

{% hint style="info" %}
在未施加驱动力的情况下移动机器人轴时，由于重力有轴掉落的风险，并且由于制动系统释放可能会有额外风险。因此，必须按照指示的程序进行工作。
{% endhint %}
[__SOURCE](1-safety/13-maintenance-safety-measures/3-measures-after-maintenance.md)
# 1.13.3. 维护和检查后的措施

观察维护和检查后的以下行动。
* 检查控制器内部的电线或部件是否正常连接。
* 维护后，检查控制器、操纵器或机器人系统内部及周围是否遗留任何工具，并确保将其整理和组织好。必须关闭每扇门。
* 如果发现任何问题或致命缺陷，请勿开启机器人的电源。
* 打开控制面板中的主开关。
* 检查机器人的当前位置和状态。
* 以低速操作机器人。

{% hint style="info" %}
在开启电源之前，请检查机器人操作区域内没有工人，并确保您处于安全的地方
{% endhint %}

{% hint style="warning" %}
在更改组件或添加影响安全相关功能的可选设备（包括硬件和软件）时，必须检查功能是否正常，关注在“1.11 操作机器人时的安全工作”中描述的项目。
{% endhint %}
[__SOURCE](1-safety/14-end-effector-safety/README.md)
# 1.14. 与末端执行器相关的安全  

{% hint style="warning" %}
安装和操作末端执行器时，您必须遵守 ISO 10218-1:2018 
在应用、维护和操作它们方面的规定。  
{% endhint %}


有关末端执行器安装的详细规范，请参考每个机器人的维护手册。
[__SOURCE](1-safety/14-end-effector-safety/1-gripper.md)
# 1.14.1. Gripper 

* 当夹头用于固定工件时，应采取措施防止工件突然掉落。 
* 在将设备安装到末端执行器或臂上时，应使用规定尺寸的螺栓和规定数量的螺栓，并根据规定的扭矩使用扭矩扳手完全拧紧。应使用未生锈或沾染的螺栓。 
* 在制造末端执行器时，应考虑其可以在机器人的腕关节的允许负载值内使用。末端执行器应具有一个结构，即使在电源或气源中断时，也不会释放或掉落夹持的材料，并且应确保处理好角落和突出部分，以防止人员或物体受到损害。
[__SOURCE](1-safety/14-end-effector-safety/2-tool-work.md)
# 1.14.2. 工具/工件 

* 应该能够安全更换诸如铣刀之类的工具。在刀具停止旋转之前，安全装置应该确保正常工作。 
* 工具的设计应确保在发生突然断电或控制故障时，工件不会出现任何异常。在手动操作中，应该能够分离工件。
[__SOURCE](1-safety/14-end-effector-safety/3-pneumatic-hydraulic-system.md)
# 1.14.3. 气动 / 液压系统

* 特殊安全法律将适用于气动和液压系统。  
* 在此类系统中，由于在系统关闭后可能仍会残留能量，您应特别注意。在修理气动或液压系统之前，您必须排除设备内部的压力。
[__SOURCE](2-details/README.md)
# 2. 详细配置
[__SOURCE](2-details/1-detail-spec-controller-model.md)
# 2.1. 各控制器型号的详细配置

Table 2-1 Details of Specification of Each Controller Model 
<table>
<thead>
  <tr>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>Model&nbsp;&nbsp;&nbsp;</th>
    <th><br>Hi7-N00-A0<br>Hi7-N30-A0<br>Hi7-N80-A0&nbsp;&nbsp;&nbsp;</th>
    <th><br>Hi7-N00U-A0<br>Hi7-N30U-A0<br>Hi7-N80U-A0</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>CPU&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>2.7GHz双核&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>程序执行方式&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>教学与回放&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>操作方式&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>基于菜单&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>插值类型&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>PTP，线性与圆形&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>内存备份方式&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>电池备份IC内存&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>编码器类型&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>绝对编码器&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>伺服驱动单元&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>6轴集成，数字伺服&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>最大单元数量&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>最大32轴同时&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>步数&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>10,000,000步&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>程序选择&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>255（按位） / 8（离散）&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>教学挂板显示&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>7英寸彩色TFT-LCD（800x480）&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>现场总线接口（可选）&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>DeviceNet,&nbsp;&nbsp;&nbsp;ProfiNET, Modbus TCP/UDP, EtherCAT &nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>数字I/O（可选）&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br> 输入：36点（最多44点） / 输出：36点（最多44点） &nbsp;&nbsp;&nbsp;</td>
  </tr>
   <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>传送带脉冲计数器（可选）&nbsp;&nbsp;&nbsp;(선택사양)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>线路驱动器 / 开放集&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>通信接口&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br> 3以太网端口/ 2 USB 2.0端口/ 2 RS232端口&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td rowspan="4">&nbsp;&nbsp;&nbsp;<br>电路板 &nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>主模块&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H6COM-T&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>伺服安全板&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>BD642&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>背板&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>BD604&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>电源模块&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H7PSM(BD6C3)&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td rowspan="2">&nbsp;&nbsp;&nbsp;<br>驱动模块&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>适用于中型6轴&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2"><br>N00(U)-A0 : H7D6X<br>N80(U)-A0 : H7D6X<br>N30(U)-A0 : H7D6A</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>适用于一个附加轴&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H7D1X, H7D1Z&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>线束&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>CMC1, CMC2, CEC1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>教学挂板&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>TP630&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>额定供电电压&nbsp;&nbsp;&nbsp;</td>
    <td><br>三相220V(50/60 Hz)±10% 选项：三相380V，400V，415V和440V </td>
    <td>&nbsp;&nbsp;&nbsp;<br>三相220V(50/60 Hz)±10% 选项：三相460V和480V</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>最大功耗&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2"><br>Hi7-N80(U)-A0 : 10.5KVA<br>Hi7-N00(U)-A0 : 7.8KVA<br>Hi7-N30(U)-A0 : 4.4KVA</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>工作温度&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>0 ~ 45 ℃&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>工作湿度&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>75%&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>防护等级&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>IP54&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>噪音水平&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>最大68dB&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>外部尺寸*1(WxHxD)<br>(WxHxD)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>W680xD520xH550(mm) 滚轮100mm 不包括&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>重量&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">标准规格（不包括TR）<br>Hi7-N30(U): 80kg<br>Hi7-N00(U): 80kg<br>Hi7-N80(U): 90kg<br><br>可选规格（包括TR）<br>Hi7-N30(U): 140kg<br>Hi7-N00(U): 160kg<br>Hi7-N80(U): 170kg</td>
  </tr>
</tbody>
</table>

Table 2-2 Power Requirements

<table>
<thead>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>Controller type&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Capacity*1)<br>[KVA]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br> Input voltage*2)<br>[V]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br> Frequency<br>[Hz]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Peak current<br>[A] &nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N30&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大4.4 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>15 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N00&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大7.8 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>30 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N80&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大10.5 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N30U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大4.4 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>15 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N00U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大7.8 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>30 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi7-N80U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>最大10.5 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
</tbody>
</table>
Note 1) 功率容量：指控制器的供电能力。有关各机器人功率容量，参见机器人维护手册。<br>
Note 2) 电压范围：±10%（在控制器的电源端子上）
[__SOURCE](2-details/2-controller-appearance.md)
# 2.2. 控制器外观

![](../_assets/2.2._제어기_외관(Hi6a).png )<br>
图 2.1 控制器正面外观<br>
[__SOURCE](3-installation/README.md)
# 3. 控制器的安装

如果您在安装的位置和方向以及周围空间的大小方面正确安装、运输和存储产品，则可以确保产品的使用寿命，并防止其性能退化。
* 检查安装和使用环境
* 控制器的运输
* 控制器的存储
* 控制器的处置

{% hint style="info" %}
在安装产品之前，您必须充分进行风险评估，然后根据评估结果设置安全功能。有关安全功能的详细信息，请参考“1. 安全”。
{% endhint %}
[__SOURCE](3-installation/1-configuration/README.md)
# 3.1. 配置
[__SOURCE](3-installation/1-configuration/1-basic-configuration.md)
# 3.1.1. 基本配置

![](../../_assets/그림_3.1_산업용_로봇_설치의_기본_구성_en.png)<br>
Figure 3.1 工业机器人安装的基本配置<br>

* Hi7 controller 
* 教学报警器 
* 线路束(Hi7 controller ↔ robot) 
* 机器人 
[__SOURCE](3-installation/1-configuration/2-various-name-plates.md)
# 3.1.2. 检查各种名称牌

![](../../_assets/fig_1.1_safety_label.png  )<br>
图3.2 控制器的标签<br>

表3-1 标签类型<br>
![](../../_assets/표3-1_라벨_종류-1_en.png  )

![](../../_assets/표3-1_라벨_종류-2_2.png  )

![](../../_assets/표3-1_라벨_종류-3.png  )


{% hint style="warning" %}
禁止任何损坏安全标签的行为，例如重新定位名称牌、警告标记、安全符号、名称标记和电线标记，或在其上涂漆或用盖子遮挡它们。
{% endhint %}

{% hint style="info" %}
以能够从类型、颜色和样式上与其他设施和设备区分开的方式标记机器人的安装和危险区域。
{% endhint %}
[__SOURCE](3-installation/2-install-use-env.md)
# 3.2. 安装和使用环境 

在考虑安装和使用环境和条件的情况下，将产品安装在适当的位置。  
* 产品的适宜使用温度为 0℃ - 45℃，适宜存储湿度为 20 至 85%RH。  
* 移动或使用时，请勿将产品掉落或施加强烈冲击。  
* 根据产品的重量，安全地运输和安装产品。  
* 在坚固、平坦且无振动的区域安装和使用产品，确保产品不易翻倒。  
* 请勿在有水、潮湿、气体、灰尘等大量外来物质的区域或肮脏的地方安装和使用产品。  
* 请勿在有易燃和腐蚀性物质或气体的区域，或在产生热量的区域，或靠近火源的地方安装或使用产品。  
* 请勿在有强电噪声源或受到其影响的区域安装或使用产品。  
* 请参考“1.10 安装时的安全措施”，在安全区域安装控制器。  
* 请参考“1.13 维护和检查时的安全措施”，进行控制器的维护工作。  
* 在进行焊接作业的区域安装产品时，应将其安装在不会受到焊接飞溅和冷却水影响的位置。  
* 安装控制器时，如果附近有墙壁或障碍物，请保持至少 500mm 的距离。  
* 有关机器人的安装事项，请参考各自的机器人维护手册。  

{% hint style="info" %}
如果产品未在推荐位置安装，产品的性能和使用寿命可能会降低。请根据建议安装和使用产品。
{% endhint %}  

{% hint style="warning" %}
机器人应根据 ISO 10218-2 的指南进行安装和操作。此外，还需遵守国际标准和国家法律的相关要求。<br>
我们的公司（或制造商）对于因未遵守国际标准和国家法律的相关要求或未审查“风险评估”而发生的任何事故不承担责任。  
{% endhint %}
[__SOURCE](3-installation/3-controller-transport/README.md)
# 3.3. 控制器的运输

以下项目描述了在打包、运输和拆卸Hi7控制器时应采取的预防措施。<br>
有关机器人打包和运输的事项，请参阅机器人维护手册。
[__SOURCE](3-installation/3-controller-transport/1-packaging.md)
# 3.3.1. 包装

* 将模型铭牌附加到箱子上。
* 用防尘盖或聚氯乙烯保护所有暴露的连接器。
* 当教学挂件被包装在盒子里时，使用充气缓冲材料以防止LCD因外部冲击而受损。
* 将防水的装箱清单附加在箱子外部。
[__SOURCE](3-installation/3-controller-transport/2-carrying-weight-modi.md)
# 3.3.2. 运输（修改重量）

* 检查控制器的前门是否完全锁定。
* 移除控制器上未固定的任何物品。
* 检查控制器上的眼螺栓是否牢固固定。
* 由于控制器是精密设备，注意运输时防止其受到强烈冲击。
* 控制器的重量最大为170kg。使用起重机时，采取预防措施以防止控制器上的物体被电缆损坏。
* 关于控制器的重量，请参考“2. 详细配置”。
* 使用叉车时，以防控制器晃动的方式固定控制器。
* 通过车辆移动产品时，使用水母固定操作器和控制器。
* 运输产品时，充分了解与包装和运输相关的内容，并遵循说明。由于客户的疏忽、操作经验不足或疏忽造成的产品损坏或破损，我公司不承担任何责任。
* 使用起重机运输控制器时，请检查以下事项。
  - 一般来说，控制器应使用眼螺栓所用的起重机电缆进行运输。
  - 检查电缆是否具有足够的强度以承受控制器的重量。
  - 检查眼螺栓是否紧固。

![](../../_assets/그림_3.3_제어기_와이어_연결_위치.png  )<br>
图 3.3 控制器电缆连接位置<br>

* 使用叉车运输控制器时，请检查以下事项，
  - 使用电缆绳运输产品时，请使用可以承受控制器重量的电缆。
  - 检查眼螺栓是否牢固固定。
  - 运输控制器时尽量保持其尽可能低的位置。

![](../../_assets/그림_3.4_지게차를_이용한_제어기_운반.png  )<br>
图 3.4 使用叉车运输控制器<br>

{% hint style="warning" %}
如果使用提升设备运输产品，应遵守相关国家和地方安全法规及设备使用指南。使用起重机移动产品时，必须确保没有工人在产品下方。同时，切勿在起重机或产品下方工作或走动。
{% endhint %}
[__SOURCE](3-installation/3-controller-transport/3-unpackaging.md)
# 3.3.3. 拆包

* 在拆包和安装机器人之前，必须仔细了解安全规定和其他指导方针。
* 根据拆包说明拆开产品
* 检查位置是否为机器人和控制器可以安全安装的区域
* 检查是否已确保允许机器人和控制器安全移动的路径
* 机器人运输应由合格人员进行
* 在拆包产品时，检查在运输或拆包过程中是否有可能发生的损坏。
[__SOURCE](3-installation/4-keep-controller.md)
# 3.4. 控制器的存放

当存放控制器时，请参考以下事项，而不是安装它。 
* 在打包状态下存放控制器，并将电源和通信连接部分密封紧密。 
* 长时间存放控制器时，必须采取防止其倾倒的安全措施。 
* 将控制器包裹在包装材料中存放时，需用干燥剂包装或存放在干燥的地方。如果存放在湿度较高的地方，包装材料内部可能会形成水分，从而损坏产品。 
* 避免温度和湿度可能容易变化的地方（发生冷凝的地方），并将控制器存放在温度范围为-15 ℃ 到 40 ℃ 的凉爽干燥处。 
* 不要将控制器存放在有化学产品、酸碱产品、电池、断路器等的地方。
[__SOURCE](3-installation/5-disposal-controller.md)
# 3.5. 控制器的废弃

为了确保用户安全和保护环境，某些部件应按照指定方法进行管理和废弃，如果它们包含工业废物，则绝不能与一般工业或家庭废物一起丢弃。在废弃全部或部分机器人系统时，必须遵守相关的国家或地方规定和法律。有关产品的废弃和处理的详细信息，请联系客户支持团队。
[__SOURCE](3-installation/6-connection/README.md)
# 3.6. 连接

{% hint style="info" %}
1. 在连接电缆之前，关闭控制器的主电源开关，并使用挂锁将其锁定。
2. 控制器具有 DC400V 的带电能量。请小心。<BR>
关闭电源开关，至少等待 5 分钟以放电带电能量。
3. 处理 PCB 时，请采取预防措施，避免静电损坏它。
4. 接线和连接电缆必须由合格人员执行。
{% endhint %}
[__SOURCE](3-installation/6-connection/1-teach-pendant-conn.md)
# 3.6.1. 教学挂件的连接

将教学挂件的电缆连接器连接到控制器的CNRTP插座。

![](../../_assets/그림_3.5_Hi6a-N_(U)_티칭펜던트의_접속_en.png  )<br>
图3.5 Hi7-N**(U) 教学挂件的连接 <br>
[__SOURCE](3-installation/6-connection/2-robot-controller.md)
# 3.6.2. 操作臂与控制器的连接

通过使用线束连接操作臂和控制器。在连接时检查各个插座的名称。

![](../../_assets/3.6.2._로봇_본체와_제어기의_접속-1.png  )<br>
图 3.6 操作臂与控制器的连接 (Hi7-N**(U))<br>

<table>
<thead>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>Hi7-N 控制器&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>机器人&nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>CMC1&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>CMR1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>CMC2&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>CMR2&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>CEC1&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>CER1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>AMC1&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>AMR1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>AMC2&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>AMR2&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>AEC1&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>AER1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>AEC2&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>AER2&nbsp;&nbsp;&nbsp;</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
由于每个机器人的连接部分可能与上图不同，因此在连接线束之前，您必须仔细阅读相关的机器人维护手册。 
{% endhint %}
[__SOURCE](3-installation/6-connection/3-controller-1st-power/README.md)
# 3.6.3. 控制器与主电源的连接

检查主电源和断路器（NFB）是否已断电。 
在 Hi7-N** 控制器的情况下，通过电源入口插入电源电缆，然后将其连接到断路器（NFB）。 
此时，请使用适当尺寸的端子插座用于主电源电缆的末端。 

![](../../../_assets/그림_3.8_Hi6a-N__U__제어기에_1차_전원_접속부_en.png  )<br>
![](../../../_assets/그림_3.8_Hi6a-N__U__제어기에_1차_전원_접속부_2.png  )<br>
图 3.7 Hi7-N**(U) 控制器的主电源连接部分<br>
[__SOURCE](3-installation/6-connection/3-controller-1st-power/1-req-power.md)
# 3.6.3.1. 电源要求

Table 3-2 电源要求
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>控制器类型</strong></p></td>
<td><p><strong>容量<sup>*1)</sup> [KVA]</strong></p></td>
<td><p><strong> 输入电压<sup>*2)</sup> [V]</strong></p></td>
<td><p><strong>频率<br>[Hz]</strong></p></td>
<td><p><strong>峰值电流<br>[A]</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>Hi7-N00</p></td>
<td><p>最大 7.8KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>30A</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>Hi7-N30</p></td>
<td><p>最大 4.4KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>15A</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>Hi7-N80</p></td>
<td><p>最大 10.5KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>50A</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>Hi7-N00U</p></td>
<td><p>最大 7.8KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>30A</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>Hi7-N30U</p></td>
<td><p>最大 4.4KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>15A</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>Hi7-N80U</p></td>
<td><p>最大 10.5KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>50A</p></td>
</tr>
</tbody>
</table>

Note 1) 功率容量：指控制器的电源容量。有关每个机器人的功率容量，请参考“操纵器维护手册”。<br> 
Note 2) 电压范围：±10%（在控制器的电源端子处）
[__SOURCE](3-installation/6-connection/3-controller-1st-power/2-power-wire-thick.md)
# 3.6.3.2. 电缆厚度

表3-3 推荐的最小电缆厚度<br>
<table>
<thead>
  <tr>
    <th rowspan="2">&nbsp;&nbsp;&nbsp;<br>编号&nbsp;&nbsp;&nbsp;</th>
    <th rowspan="2">&nbsp;&nbsp;&nbsp;<br>电缆长度<br>米(英尺)&nbsp;&nbsp;&nbsp;</th>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>电缆厚度<br>(Hi7-N00(U), Hi7-N80(U))&nbsp;&nbsp;&nbsp;</th>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>电缆厚度<br>(Hi7-N30(U), Hi7-N20(U))&nbsp;&nbsp;&nbsp;</th>
  </tr>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>mm2&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>AWG&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>mm2&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>AWG&nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>1&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>0 ~ 50(0 ~ 160)&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>5.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>10&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>3.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>12&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>2&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50 ~ 100(160 ~ 320)&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>5.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>10&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>3.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>12&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>3&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>100 ~ 180(320 ~ 590)&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>8&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>8&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>5.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>10&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>4&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>180 ~ 300(520 ~ 980)&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>8&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>8&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>5.5&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>10&nbsp;&nbsp;&nbsp;</td>
  </tr>
</tbody>
</table>
[__SOURCE](3-installation/6-connection/4-controller-ground.md)
# 3.6.4. 控制器和接地

为了安全使用控制器，将接地线连接到控制器。使用5.5 ㎟或更高规格的接地线。（第3类接地）。
控制器的接地点位置如图3.9所示。

![](../../_assets/그림_3.9_Hi6a-N__U__제어기에_FG_케이블_연결_en.png)<br>
图3.9 控制器的电源接地端子<br>
[__SOURCE](3-installation/6-connection/5-other-caution.md)
# 3.6.5. 其他注意事项 

{% hint style="info" %}
1. 在连接控制器和机械臂时，请将信号线和电源线分开。此外，高功率线路和信号线应分别使用独立的管道。 
2. 为了防止在人员经过时电线受到损坏，使用电线的保护罩。 
3. 在供电主电源之前，您必须再次检查控制器的连接关系、电源规格和电源供应规格。 
{% endhint %}
[__SOURCE](3-installation/6-connection/6-user-eth-port-conn.md)
# 3.6.6. 用户以太网端口的连接

用户的以太网端口位于控制器的前门。引脚描述和与 Pc 的连接如下。

Table 3-4 引脚描述（RJ45 连接器规格；RJ 45P 屏蔽）<br>
<table>
<tbody>
<tr class="odd">
<td><p><strong>RJ45 引脚编号</strong></p></td>
<td><p><strong>名称</strong></p></td>
<td><p><strong>缩写</strong></p></td>
<td><p><strong>方向</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>传输数据 +</p></td>
<td><p>TX +</p></td>
<td><p>输出</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>传输数据 -</p></td>
<td><p>TX -</p></td>
<td><p>输出</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>接收数据 +</p></td>
<td><p>RX +</p></td>
<td><p>输入</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>接收数据 -</p></td>
<td><p>RX -</p></td>
<td><p>输入</p></td>
</tr>
</tbody>
</table>
[__SOURCE](4-basic-components/README.md)
# 4. 控制器的基本配置
[__SOURCE](4-basic-components/1-config.md)
# 4.1. 配置

控制器包括主机和教学挂件。

![](../_assets/그림_4.1_Hi6a-N_(U)_제어기.png  )<br>
图 4.1 Hi7-N**(U) 控制器<br>

![](../_assets/그림_4.2_티칭펜던트_TP630_Hi6a.png)<br>
图 4.2 教学挂件 TP630<br>
[__SOURCE](4-basic-components/2-part-layout.md)
# 4.2. 组件的放置

Hi7-N00/N30/N80 控制器的主要组件及其名称如下表 4-1 所示，并按图 4.3 到图 4.5 所示的方式排列。

表 4-1 Hi7-N00/N30/N80 控制器各部件名称 
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>类型</strong></p></td>
<td><p><strong>部件名称</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>H6COM-T</p></td>
<td><p>主控制模块</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>BD642</p></td>
<td><p>伺服安全板</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>BD604</p></td>
<td><p>背板</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>H7PSM</p></td>
<td><p>电源模块</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>H7D6X(大/中型)</p>
<p>/H7D6A(小型)</p></td>
<td><p>适用于大/中/小型6轴的驱动模块</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>H7D1X(可选)</p></td>
<td><p>适用于1轴100A的驱动模块</p></td>
</tr>
<tr class="even">
<td><p><strong>6-1</strong></p></td>
<td><p>H7D1Z(可选)</p></td>
<td><p>适用于1轴50A的驱动模块</p></td>
</tr>
<tr class="odd">
<td><p><strong>7</strong></p></td>
<td><p>OP EM. SW.</p></td>
<td><p>控制面板上的紧急开关</p></td>
</tr>
<tr class="even">
<td><p><strong>8</strong></p></td>
<td><p>NFB</p></td>
<td><p>无熔断器断路器</p></td>
</tr>
<tr class="odd">
<td><p><strong>9</strong></p></td>
<td><p>FAN2</p></td>
<td><p>驱动模块内部冷却风扇</p></td>
</tr>
<tr class="even">
<td><p><strong>10~12</strong></p></td>
<td><p>FAN3~5</p></td>
<td><p>驱动模块外部冷却风扇</p></td>
</tr>
<tr class="odd">
<td><p><strong>13</strong></p></td>
<td><p>NFT1</p></td>
<td><p>线路噪声过滤器</p></td>
</tr>
<tr class="even">
<td><p><strong>14</strong></p></td>
<td><p>RDR1</p></td>
<td><p>小/中/大型再生放电电阻 
(CE/UL 认证产品)</p></td>
</tr>
<tr class="odd">
<td><p><strong>15</strong></p></td>
<td><p>TR</p></td>
<td><p>选项输入电源变压器</p></td>
</tr>
<tr class="even">
<td><p><strong>16</strong></p></td>
<td><p>CMC1</p></td>
<td><p>电机驱动电源电缆入口连接</p></td>
</tr>
<tr class="odd">
<td><p><strong>17</strong></p></td>
<td><p>CMC2</p></td>
<td><p>电机驱动电源电缆入口连接</p>
<p>(不安装 CMC2 的小型控制器)</p></td>
</tr>
<tr class="even">
<td><p><strong>18</strong></p></td>
<td><p>AMC1(选项)</p></td>
<td><p>选项1的电机驱动电源电缆入口连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>19</strong></p></td>
<td><p>AMC2(选项)</p></td>
<td><p>选项2的电机驱动电源电缆入口连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>20</strong></p></td>
<td><p>CEC1</p></td>
<td><p>编码器通信电缆入口连接</p></td>
</tr>
<tr class="odd">
<td><p><strong>21</strong></p></td>
<td><p>AEC1</p></td>
<td><p>选项1的电机编码器电缆入口连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>22</strong></p></td>
<td><p>AEC2</p></td>
<td><p>选项2的电机编码器电缆入口连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>23</strong></p></td>
<td><p>CNRTP</p></td>
<td><p>教导挂件电缆入口连接器</p></td>
</tr>
</tbody>
</table>

![](../_assets/그림_4.3_Hi6a-N00(U),N30(U),N80(U)_제어기_전면_외부의_부품배치.png)<br>
图 4.3 Hi7-N00(U)/N30(U)/N80(U) 控制器前面外部组件的放置<br>

![](../_assets/그림_4.4_Hi6a-N00(U),N30(U),N80(U)_제어기_전면_내부의_부품배치.png  )<br>
图 4.4 Hi7-N00(U)/N30(U)/N80(U) 控制器前面内部组件的放置<br>

![](../_assets/그림_4.5_Hi6a-N00(U),N30(U),N80(U)_제어기_후면_부품배치.png  )<br>
图 4.5 Hi7-N00(U)/N30(U)/N80(U) 控制器后面组件的放置<br>

![](../_assets/그림_4.6_Hi6a-N00(U),N30(U),N80(U)_제어기_트랜스포머함.png  )<br>
图 4.6 Hi7-N00(U),N30(u),N80(U) 控制器变压器箱<br>
[__SOURCE](4-basic-components/3-component-func/README.md)
# 4.3. 各个组件的功能

Table 4-2 各个组件功能的总结
<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">控制模块</td>
    <td>主控制模块(H6COM-T)</td>
    <td>- 记录记录点并计算操作路径<br>- 保存程序和机器人整数<br>- 教学终端(T/P)通信<br>- LAN、USB和串行(RS232)通信的连接</td>
  </tr>
  <tr>
    <td>伺服板(BD642)</td>
    <td>- 用于伺服控制的DSP<br>- 编码器连接（串行I/F）<br>- 伺服电机的开/关输出<br>- 功能安全功能<br>- 顺序控制<br>- 系统I/O<br>- 安全链路电路</td>    
  </tr>
  <tr>
    <td>背板(BD604)</td>
    <td>- 每个板的控制电源<br>- 与伺服安全板(BD642)的AMP信号连接<br>- 前充电/风扇继电器操作信号传输</td></td>
  </tr>
  <tr>
    <td>驱动模块<br>(驱动模块)</td>
    <td>大型/中型6轴: H7D6X<br>小型6轴: H7D6A<br>附加轴: H7D1X, H7D1Z</td>
    <td>- 生成电机驱动功率<br>- 再生放电<br>- 伺服电机功率放大电路<br>- 各种错误输出</td>
  </tr>
  <tr>
    <td>T/P<br>(教学终端)</td>
    <td>TP630</td>
    <td>- 显示各种信息（LCD）<br>- 按钮输入和开关输入（功能/步进等）<br>- 紧急停止、使能和T/P开/关输入</td>
  </tr>
  <tr>
    <td>冷却设备</td>
    <td>风扇</td>
    <td>- 面板内部空气循环<br>- 驱动模块的冷却</td>
  </tr>
  <tr>
    <td>电源模块</td>
    <td>H7PSM</td>
    <td>- 电机驱动功率的开/关<br>- 各种电源的分配</td>
  </tr>
</tbody>
</table>

* 有关各控制器组件类型，请参考“2.1 各控制器型号的详细配置。” 

![](../../_assets/그림_4_3_구성품%20위치.png)<br>
Figure 4.7 控制模块的组件<br>
[__SOURCE](4-basic-components/3-component-func/1-main-module-H6COM-T/README.md)
# 4.3.1. 主模块(H6COM-T)
[__SOURCE](4-basic-components/3-component-func/1-main-module-H6COM-T/1-overview.md)
# 4.3.1.1. 概述

H6COM-T 的结构如图 4.9 所示，主 CPU 板和载体板相结合。主 CPU 板由 SSD 插槽、CPU 插槽、内存卡插槽、USB 端口、COM 端口和连接到载体板的总线连接器组成。载体板包含三个用于外部系统的 LAN 端口，两个用于内部系统的 LAN 端口，两个 USB 端口，一个 GPIO 端口，两个 PCI 连接器，一个 PCI-e 连接器和一个 DC 24V 电源连接器。用于内部系统的 LAN 端口用于 EtherCAT 通信，以及与教导挂件的接口，GPIO 端口用于检测电源系统的电源故障信号。SB用于调试。提供一个 PCI 扩展插槽和三个用于外部系统的备用 LAN 端口，以支持其他通用总线接口。与 EtherCAT 以外的其他通信接口的连接可以通过相关插槽进行。

![](../../../_assets/그림_4_1_1_메인모듈이미지.png)<br>
图 4.8 H6COM-T<br>
[__SOURCE](4-basic-components/3-component-func/1-main-module-H6COM-T/2-connector.md)
# 4.3.1.2. 连接器

Table 4-3 描述了连接器的使用和外部设备的连接。

Table 4-3 H6COM-T 的连接器类型和使用
<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备的连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>DC IN 24V</strong></p></td>
<td><p>DC24V 主电源</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>COM 1,2</strong></p></td>
<td><p>串行端口(RS232/RS422/RS485)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>GIO</strong></p></td>
<td><p>电源单元的电源故障应用</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 4</strong></p></td>
<td><p>EtherCAT 主连接器端口</p></td>
<td><p>EtherCAT 连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>LAN 5</strong></p></td>
<td><p>以太网端口：用于教学挂件之间的通信</p></td>
<td><p>TP 连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 1</strong></p></td>
<td><p>以太网端口：供用户使用 (PC I/F)</p></td>
<td><p> 可选 EtherCAT 连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>LAN 2</strong></p></td>
<td><p>以太网端口：供用户使用 (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 3</strong></p></td>
<td><p>以太网端口：供用户使用 (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>PCI, PCIe</strong></p></td>
<td><p>可选扩展板插槽</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>USB1,2</strong></p></td>
<td><p>USB 端口：供用户使用 (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/README.md)
# 4.3.2. 伺服/安全模块(BD642)
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/1-overview.md)
# 4.3.2.1. 概述

伺服/安全模块(BD642)在机器人控制器中执行伺服控制和安全功能。伺服控制功能支持最多八个轴的同时控制，包括六个主要机器人轴和两个辅助轴。

伺服控制系统由几个功能模块组成。这些模块包括接收电机控制所需反馈信号的输入阶段（例如电流传感器信号和位置反馈信号）、由MCU和FPGA组成的处理单元，该单元执行电机控制算法（包括位置、速度、扭矩和电流控制），以及控制和监视用于伺服操作的电力设备的电源控制阶段，如IPM、整流二极管、直流连接和制动电路。

除了运动控制外，该模块提供机器人控制器所需的安全功能。为了实现安全，MCU被配置为双通道架构，以确保安全功能的可靠处理。这种架构支持安全扭矩关闭（STO）处理以及安全相关的输入和输出信号的处理。

该模块还提供与机器人控制器系统的其他组件集成所需的通信和信号接口。这些接口包括用于T/P（教导 pendant）、BD671（PROFIsafe）板、主COM、BD604（背板）板、BD680（可选安全I/O）板和BD6C3（电力分配）板的接口。
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/2-connector.md)
# 4.3.2.2. 连接器

下图显示了 Servo/Safety Module(BD642) 外部连接所需的连接器位置。下表描述了每个连接器的名称和功能。

![](../../../_assets/BD642_PCB_커넥터명.png)<br>
图 4.3.2.2-1 Servo/Safety Module(BD642) 的连接器布局

表 4.3.2.2-1 Servo/Safety Module(BD642) 的连接器名称、功能和外部连接设备
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>连接器</strong></th>
    <th><strong>功能</strong></th>
    <th><strong>外部设备</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>A</td>
    <td>J4</td>
    <td>EtherCAT 通信接口</td>
    <td>H6COM/LAN4</td>
  </tr>
  <tr>
    <td>B</td>
    <td>CNSO1</td>
    <td>安全输出端子</td>
    <td>外部设备</td>
  </tr>
  <tr>
    <td>C</td>
    <td>CNSI1</td>
    <td>安全输入端子</td>
    <td>外部设备</td>
  </tr>
  <tr>
    <td>D</td>
    <td>CNEM</td>
    <td>外部紧急开关接口</td>
    <td>紧急开关</td>
  </tr>
  <tr>
    <td>E</td>
    <td>CNTP</td>
    <td>教学挂件接口（电源、紧急停止、模式切换、启用开关）</td>
    <td>连接器 CNRTP</td>
  </tr>
  <tr>
    <td>F</td>
    <td>CNMC</td>
    <td>磁性接触 I/O 信号</td>
    <td>电源分配板(BD6C3) CNMC</td>
  </tr>
  <tr>
    <td>G</td>
    <td>CNEN8</td>
    <td>辅助轴 8 编码器信号</td>
    <td>连接器 AEC2</td>
  </tr>
  <tr>
    <td>H</td>
    <td>CNEN7</td>
    <td>辅助轴 7 编码器信号</td>
    <td>连接器 AEC1</td>
  </tr>
  <tr>
    <td>J</td>
    <td>CNEN46</td>
    <td>轴 4~6 编码器信号</td>
    <td>连接器 CEC1</td>
  </tr>
  <tr>
    <td>K</td>
    <td>CNEN13</td>
    <td>轴 1~3 编码器信号</td>
    <td>连接器 CEC1</td>
  </tr>
  <tr>
    <td>M</td>
    <td>CNBRK78</td>
    <td>辅助轴 7、8 刹车信号</td>
    <td>连接器 AMC1, AMC2</td>
  </tr>
  <tr>
    <td>N</td>
    <td>CNBRK16</td>
    <td>轴 1~6 刹车信号</td>
    <td>连接器 CMC1, CMC2</td>
  </tr>
  <tr>
    <td>P</td>
    <td>J12</td>
    <td>刹车电源</td>
    <td>电源分配板(BD6C3) CNOBK</td>
  </tr>
  <tr>
    <td>Q</td>
    <td>CNBS1</td>
    <td>驱动接口信号</td>
    <td>背板板(BD604) CNBS1</td>
  </tr>
  <tr>
    <td>R</td>
    <td>CNBS2</td>
    <td>驱动接口信号</td>
    <td>背板板(BD604) CNBS2</td>
  </tr>
</tbody>
</table>
      
{% hint style="info" %}
如果连接并激活了与安全相关的输入，请参阅“1.11 机器人操作安全注意事项”，并确认功能正常运行。
{% endhint %}
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/3-display.md)
# 4.3.2.3. 指示灯

(1) 主板顶部指示灯

下图显示了Servo/Safety模块(BD642)顶部的指示灯(LED和7段显示器)的位置。
下表描述了每个指示灯的功能。

![](../../../_assets/BD642_PCB_상태.png)   
图 4.3.2.3-1 Servo/Safety模块(BD642)的主板顶部指示灯布局

表 4.3.2.3-1 Servo/Safety模块(BD642)主板顶部指示灯描述   
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>指示灯</strong></th>
    <th><strong>描述</strong></th>
    <th><strong>颜色</strong></th>
    <th><strong>正常状态</strong></th>
    <th><strong>异常情况下的措施</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)<br>(2)</td>
    <td>LED1<br>LED2</td>
    <td>输入电源限制功能</td>
    <td>红色</td>
    <td>关闭</td>
    <td>
      症状: 红色LED亮
      <br>原因: 输入电压过低或过高
      <br>措施: 检查输入电压(24 V)
    </td>
  </tr>
  <tr>
    <td>(3)</td>
    <td>LED3</td>
    <td>外部A通道电源</td>
    <td>黄色</td>
    <td>开启</td>
    <td>
      症状: 黄色LED关闭
      <br>原因: 外部A通道电源过流或外部接线错误
      <br>措施: 检查保险丝(FS2)
    </td>
  </tr>
  <tr>
    <td>(4)</td>
    <td>LED4</td>
    <td>外部B通道电源</td>
    <td>黄色</td>
    <td>开启</td>
    <td>
      症状: 黄色LED关闭
      <br>原因: 外部B通道电源过流或外部接线错误
      <br>措施: 检查保险丝(FS3)
    </td>
  </tr>
  <tr>
    <td>(5)</td>
    <td>LED5</td>
    <td>A通道MCU电源</td>
    <td>黄色</td>
    <td>开启</td>
    <td>
      症状: 黄色LED关闭
      <br>原因: A通道MCU电源异常(3.3V, 1.2V)
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(6)</td>
    <td>LED6</td>
    <td>B通道MCU电源</td>
    <td>黄色</td>
    <td>开启</td>
    <td>
      症状: 黄色LED关闭
      <br>原因: B通道MCU电源异常(3.3V, 1.2V)
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(7)</td>
    <td>LED7</td>
    <td>A通道MCU状态指示灯</td>
    <td>红色
      <br>绿色
      <br>蓝色
    </td>
    <td>RGB闪烁</td>
    <td>
      症状: 所有LED关闭且无闪烁
      <br>原因1: A通道MCU电源异常(3.3V, 1.2V)
      <br>原因2: A通道MCU程序故障
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(8)</td>
    <td>LED8</td>
    <td>B通道MCU状态指示灯</td>
    <td>红色
      <br>绿色
      <br>蓝色
    </td>
    <td>RGB闪烁</td>
    <td>
      症状: 所有LED关闭且无闪烁
      <br>原因1: B通道MCU电源异常(3.3V, 1.2V)
      <br>原因2: B通道MCU程序故障
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(9)
      <br>(10)</td>
    <td>LED9
      <br>LED10</td>
    <td>A通道MCU EtherCAT LINK0状态
      <br>A通道MCU EtherCAT LINK1状态
    </td>
    <td>绿色
      <br>绿色
    </td>
    <td>绿色闪烁
      <br>绿色闪烁
    </td>
    <td>
      症状: 无闪烁
      <br>原因: A通道MCU EtherCAT故障
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(11)
      <br>(12)</td>
    <td>LED13
      <br>LED14</td>
    <td>FPGA EtherCAT LINK0状态
      <br>FPGA EtherCAT LINK1状态
    </td>
    <td>绿色
      <br>绿色
    </td>
    <td>绿色闪烁
      <br>绿色闪烁
    </td>
    <td>
      症状: 无闪烁
      <br>原因: FPGA EtherCAT故障
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(13)</td>
    <td>LED17</td>
    <td>FPGA电源状态</td>
    <td>黄色</td>
    <td>开启</td>
    <td>
      症状: 黄色LED关闭
      <br>原因: FPGA电源异常(5V, 3.3V, 1.8V, 1.35V, 1V)
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(14)</td>
    <td>LED18</td>
    <td>FPGA状态指示灯</td>
    <td>红色
      <br>绿色
      <br>蓝色</td>
    <td>RGB闪烁</td>
    <td>
      症状: 所有LED关闭且无闪烁
      <br>原因1: FPGA电源异常(5V, 3.3V, 1.8V, 1.35V, 1V)
      <br>原因2: FPGA程序故障
      <br>措施: 更换主板(BD642)
    </td>
  </tr>
  <tr>
    <td>(15)</td>
    <td>LED19
      <br>LED21
      <br>LED23
      <br>LED25
      <br>LED20
      <br>LED22
      <br>LED24
      <br>LED26
      </td>
    <td>  轴 1 刹车状态
      <br>轴 2 刹车状态
      <br>轴 3 刹车状态
      <br>轴 4 刹车状态
      <br>轴 5 刹车状态
      <br>轴 6 刹车状态
      <br>轴 7 刹车状态
      <br>轴 8 刹车状态
      </td>
    <td>橙色</td>
    <td>刹车释放(开启)
      <br>刹车保持(关闭)
    </td>
    <td>
      症状: 刹车状态不匹配
      <br>原因1: 刹车电源异常
      <br>原因2: 线束故障或接线问题
      <br>措施: 更换主板(BD642)
    </td>
  </tr>

  <tr>
    <td>(16)<br>
        (17)<br>
        (18)
    </td>
    <td>LED27
      <br>LED28
      <br>SEG1
    </td>
    <td>  
    </td>
    <td></td>
    <td></td>
    <td>
      请参阅以下部分：前面板指示灯
    </td>
  </tr>

</table>
</tbody>

(2) 前面板指示灯
下图显示了Servo/Safety模块(BD642)的前面板指示灯。下表描述了每个指示灯的功能。

![](../../../_assets/BD642_전면표시장치.png)   
图 4.3.2.3-2 Servo/Safety模块(BD642)前面板指示灯布局

表 4.3.2.3-2 Servo/Safety模块(BD642)前面板指示灯描述
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>指示灯</strong></th>
    <th><strong>描述</strong></th>
    <th><strong>颜色</strong></th>
    <th><strong>状态</strong></th>
    <th><strong>状态描述</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">(1)</td>
    <td>A_SO1</td>
    <td>A通道安全输出1状态指示灯</td>
    <td rowspan="2">绿色 </td>
    <td rowspan="2">开启<br>关闭</td>
    <td rowspan="2">A通道安全输出1开启状态<br>
                    A通道安全输出1关闭状态</td>
  </tr>
  <tr>
    <td>B_SO1</td>
    <td>B通道安全输出1开启状态</td>
  </tr>
  <tr>
    <td rowspan="2">(2)</td>
    <td>A_SIx<br>
        (x=1~4)</td>
    <td>A通道安全输入x状态指示灯</td>
    <td rowspan="2">绿色</td>
    <td rowspan="2">开启<br>关闭</td>
    <td rowspan="2">A通道安全输入x开启状态<br>
                    A通道安全输入x关闭状态</td>
  </tr>
  <tr>
    <td>B_SIn<br>
        (n=1~4)</td>
    <td>B通道安全输入n状态指示灯</td>
  </tr>

  <tr>
    <td rowspan="10">(3)</td>
    <td>LED27 (1)</td>
    <td>LED27 (1)指示灯</td>
    <td rowspan="5">绿色</td>
    <td>
    <td> LED27 (1) MCU_A MOD</td>
  </tr>
  <tr>
    <td>LED27 (2)</td>
    <td>LED27 (2)指示灯</td>
    <td>
    <td>LED27 (2) MCU_B MOD</td>
  </tr>
  <tr>
    <td>LED27 (3)</td>
    <td>LED27 (3)指示灯</td>
    <td>
    <td>LED27 (3) ZYNQ MOD</td>
  </tr>
  <tr>
    <td>LED27 (4)</td>
    <td>LED27 (4)指示灯</td>
    <td>
    <td>LED27 (4) DSP_RUN</td>
  </tr>
  <tr>
    <td>LED27 (5)</td>
    <td>LED27 (5)指示灯</td>
    <td>
    <td>LED27 (5) ZYNQ_RUN</td>
  </tr>
  <tr>
    <td>LED28 (1)</td>
    <td>LED28 (1)指示灯</td>
    <td rowspan="5">红色</td>
    <td>
    <td>LED28 (1) MCU_A STA</td>
  </tr>
  <tr>
    <td>LED28 (2)</td>
    <td>LED28 (2)指示灯</td>
    <td>
    <td>LED28 (2) MCU_B STA</td>
  </tr>
  <tr>
    <td>LED28 (3)</td>
    <td>LED28 (3)指示灯</td>
    <td>
    <td>LED28 (3) ZYNQ STA</td>
  </tr>
  <tr>
    <td>LED28 (4)</td>
    <td>LED28 (4)指示灯</td>
    <td>
    <td>LED28 (4) DSP ERR</td>
  </tr>
  <tr>
    <td>LED28 (5)</td>
    <td>LED28 (5)指示灯</td>
    <td>
    <td>LED28 (5) ZYNQ ERR</td>
  </tr>
  <tr>
    <td>(4)</td>
    <td>SEG1</td>
    <td>BD642主板状态指示灯</td>
    <td rowspan="2">红色 </td>
    <td>             </td>
    <td>显示启动状态</td>
  </tr>
</table>

表 4.3.2.3-3 前LED状态描述(BD642)
![](../../../_assets/표_4_3_2_3_LED_상태표시.png)  


![](../../../_assets/그림_4_3_2_3_Segment_상태표시_r1.png)  
图 4.3.2.3-3 段状态指示
</tbody>
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/4-setting.md)
# 4.3.2.4. 配置设备

下图显示了伺服/安全模块(BD642)上的配置(开关)设备的位置。
下表描述了每个配置设置的功能。

![](../../../_assets/BD642_PCB_설정_r1.png)   
图 4.3.2.4-1 伺服/安全模块(BD642)的配置设备布局

{% hint style="info" %}
以下设置不得由用户更改。
仅在通过JTAG接口需要FPGA重新编程时参考本节。
{% endhint %}

表 4.3.2.4-1 SW1 配置设置说明(BD642)
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>设置状态</strong></th>
    <th><strong>描述</strong></th>
    <th><strong>备注</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">①</td>
    <td rowspan="2">SW1</td>
    <td><img src="../../../_assets/BD642_플래쉬메모리_부팅모드.png" width="100"></td>
    <td>闪存启动模式</td>
    <td>出厂默认设置</td>
  </tr>
  <tr>
    <td><img src="../../../_assets/BD642_JTAG프로그램_다운로드모드.png" width="100"></td>
    <td>JTAG程序下载模式</td>
    <td>-</td>
  </tr>
</table>
</tbody>
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/5-cnso-conn.md)
# 4.3.2.5. 安全输出接线

{% hint style="warning" %}
在进行安全输出接线时，确保在开始接线工作之前控制器电源已关闭。
{% endhint %}

下图显示了伺服/安全模块(BD642)的照片以及在实际安装时从前面看到的安全输出连接器(CNSO1)的位置。

![](../../../_assets/BD642_전면사진_안전출력.png)<br>
图4.3.2.5-1 伺服/安全模块(BD642)的照片及安全输出连接器(CNSO1)的位置

在接线安全输出时，根据是使用内部电源还是外部电源，接线方法有所不同。同时，NPN或PNP类型配置也会有所不同。以下图示显示了每种情况的接线示例。

(1) 使用内部电源时  
* NPN-TYPE(: 低激活)  
在下图中，红色表示A通道，蓝色表示B通道。  
当为A通道使用内部电源时，如下图所示连接连接器CNSO1的引脚1和2。  
当为B通道使用内部电源时，如下图所示连接连接器CNSO1的引脚3和4。  
有关外部设备的连接，请参阅下面的接线示例。

![](../../../_assets/BD642_안전출력_내부전원_NPN.png)   
图4.3.2.5-2 安全输出接线图（内部电源，NPN类型） - 伺服/安全模块(BD642)   

* PNP-TYPE(: 高激活)  
在下图中，红色表示A通道，蓝色表示B通道。  
当为A通道使用内部电源时，如下图所示连接连接器CNSO1的引脚5和6。  
当为B通道使用内部电源时，如下图所示连接连接器CNSO1的引脚7和8。  
有关外部设备的连接，请参阅下面的接线示例。

![](../../../_assets/BD642_안전출력_내부전원_PNP.png)   
图4.3.2.5-3 安全输出接线图（内部电源，PNP类型） - 伺服/安全模块(BD642)   

(2) 使用外部电源时  
* NPN-TYPE(: 低激活)  
在下图中，红色表示A通道，蓝色表示B通道。  
连接器CNSO1的引脚1、4、5和8不得连接。  
当为A通道使用外部电源时，如下图所示将EX_AG (GND)连接至连接器CNSO1的引脚2。  
当为B通道使用外部电源时，如下图所示将EX_BG (GND)连接至连接器CNSO1的引脚3。  
有关外部设备的连接，请参阅下面的接线示例。

![](../../../_assets/BD642_안전출력_외부전원_NPN.png)   
图4.3.2.5-4 安全输出接线图（外部电源，NPN类型） - 伺服/安全模块(BD642)   

* PNP-TYPE(: 高激活)  
在下图中，红色表示A通道，蓝色表示B通道。  
当为A通道使用外部电源时，如下图所示将EX_AV(24V)连接至连接器CNSO1的引脚2。  
当为B通道使用外部电源时，如下图所示将EX_BV(24V)连接至连接器CNSO1的引脚3。  
有关外部设备的连接，请参阅下面的接线示例。

![](../../../_assets/BD642_안전출력_외부전원_PNP.png)   
图4.3.2.5-5 安全输出接线图（外部电源，PNP类型） - 伺服/安全模块(BD642)
[__SOURCE](4-basic-components/3-component-func/2-BD642-Servo-safety-board/6-cnsi-conn.md)
# 4.3.2.6. 安全输入接线

{% hint style="warning" %}
在进行安全输入接线时，请确保在开始接线工作之前，控制器电源已关闭。
{% endhint %}

下图显示了伺服/安全模块（BD642）的照片以及在实际安装过程中从前方查看的安全输入连接器（CNSI1）位置。

![](../../../_assets/BD642_전면사진_안전입력.png)   
图 4.3.2.6-1 伺服/安全模块（BD642）和安全输入连接器（CNSI1）位置的照片

(1) 安全输入出厂默认状态（未使用时）   
如果不使用安全输入信号，必须默认连接为 NC（常闭，B触点）。
下图显示了当安全输入未使用时的接线配置（出厂默认接线状态）。

![](../../../_assets/BD642_안전입력_사용안함.png)   
图 4.3.2.6-2 安全输入的出厂默认接线状态 - 伺服/安全模块（BD642）

在接线安全输入时，接线方式因使用内部电源或外部电源而异。它还根据 NPN/PNP 类型配置而不同。以下图显示了每种情况的接线示例。

(2) 使用内部电源时
* NPN-TYPE（: 有效低）   
下图中，红色表示 A 通道，蓝色表示 B 通道。
使用内部电源进行 A 通道时，按照下图所示连接连接器 CNSI1 的以下引脚：
17-18、21-22、25-26 和 29-30。
使用内部电源进行 B 通道时，按照下图所示连接连接器 CNSI1 的以下引脚：
19-20、23-24、27-28 和 31-32。
有关连接外部设备的信息，请参阅下方的接线示例。

![](../../../_assets/BD642_안전입력_내부전원_NPN.png)   
图 4.3.2.6-3 安全输入接线图（内部电源，NPN 类型） - 伺服/安全模块（BD642）

* PNP-TYPE（: 有效高）   
下图中，红色表示 A 通道，蓝色表示 B 通道。
使用内部电源进行 A 通道时，按照下图所示连接连接器 CNSI1 的以下引脚对：
1-2、5-6、9-10 和 13-14。
使用内部电源进行 B 通道时，按照下图所示连接连接器 CNSI1 的以下引脚对：
3-4、7-8、11-12 和 15-16。
有关连接外部设备的信息，请参阅下方的接线示例。   

![](../../../_assets/BD642_안전입력_내부전원_PNP.png)   
图 4.3.2.6-4 安全输入接线图（内部电源，PNP 类型） - 伺服/安全模块（BD642）

{% hint style="warning" %}
当将内部电源连接到外部设备时，不能作为设备的电源使用。   
{% endhint %}

(3) 使用外部电源时
* NPN-TYPE（: 有效低）   
下图中，红色表示 A 通道，蓝色表示 B 通道。
使用外部电源进行 A 通道时，请勿按照下图所示连接连接器 CNSI1 的以下引脚：
1、17、5、21、9、25、13 和 29。
使用外部电源进行 B 通道时，请勿按照下图所示连接连接器 CNSI1 的以下引脚：
4、20、8、24、12、28、16 和 32。
有关连接外部设备的信息，请参阅下方的接线示例。

![](../../../_assets/BD642_안전입력_외부전원_NPN.png)   
图 4.3.2.6-5 安全输入接线图（外部电源，NPN 类型） - 伺服/安全模块（BD642）

* PNP-TYPE（: 有效高）   
下图中，红色表示 A 通道，蓝色表示 B 通道。
当使用外部电源进行 A 通道时，请勿如图所示连接连接器 CNSI1 的引脚 1、17、5、21、9、25、13 和 29。
当使用外部电源进行 B 通道时，请勿如图所示连接连接器 CNSI1 的引脚 4、20、8、24、12、28、16 和 32。
对外部设备的连接应遵循下方的接线示例。

![](../../../_assets/BD642_안전입력_외부전원_PNP.png)   
图 4.3.2.6-6 安全输入接线图（外部电源，PNP 类型） - 伺服/安全模块（BD642）
[__SOURCE](4-basic-components/3-component-func/3-backplane-board-BD604/README.md)
# 4.3.3. 后板电路板(BD604)
[__SOURCE](4-basic-components/3-component-func/3-backplane-board-BD604/1-overview.md)
# 4.3.3.1. 概述

背板电路板 (BD604)，如图 4.50 所示，为 Hi7 电路板提供控制电源，并通过 AMP 接口板 (BD652/BD654) 传输从 BD642 生成的与 AMP 相关的信号。<br>
它还用于安装主要的可选电路板，并在它们之间传输信号。 

![](../../../_assets/그림_4.50_Backplan_구조.png )<br>
图 4.25 背板电路板结构<br>

![](../../../_assets/그림_4.52_Backplan_커넥터.png )<br>
图 4.26 背板电路板连接器<br>
[__SOURCE](4-basic-components/3-component-func/3-backplane-board-BD604/2-connector.md)
# 4.3.3.2. 连接器

表 4-9 描述了每个连接器的功能及其与外部设备的连接。

表 4-9 母板连接器的类型和功能
<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>功能</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CN24VIN</strong></p></td>
<td><p>直流 24V 主电源</p></td>
<td><p>电源分配板上的 CNOCM 连接器(BD6C3)</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPRC</strong></p></td>
<td><p>预充电继电器和风扇继电器的控制和监控</p></td>
<td><p>电源分配板上的 CNPRC 连接器(BD6C3)</p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1, CNBS2</strong></p></td>
<td><p>伺服安全板的电源和信号连接器(BD642)</p></td>
<td><p>伺服安全板上的 CNBS1 和 CNBS2 连接器(BD642) </p></td>
</tr>
<tr class="odd">
<td><p><strong>CNBS3, CNBS4</strong></p></td>
<td><p>AMP 接口板的电源和信号连接器(BD652/BD654)</p></td>
<td><p>AMP 接口板上的 CNBS1 和 CNBS2 连接器(BD652/BD654) </p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS5, CNBS6</strong></p></td>
<td><p>AMP 接口板的电源和信号电缆连接器(BD652/BD654)</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>CON1</strong></p></td>
<td><p>安全通信板的电源和信号连接器(BD671)</p></td>
<td><p>安全通信板上的 CN1 连接器(BD671)</p></td>
</tr>
<tr class="even">
<td><p><strong>CON2, CON3</strong></p></td>
<td><p>用户 IO 板的电源和信号连接器(BD681)</p></td>
<td><p>用户 IO 板上的 CN3 和 CN4 连接器(BD681)</p></td>
</tr>
<tr class="odd">
<td><p><strong>CON4, CON5</strong></p></td>
<td><p>用户 IO 扩展板的电源和信号连接器(BD682)</p></td>
<td><p>用户 IO 扩展板上的 CN4 和 CN5 连接器(BD682)</p></td>
</tr>
</tbody>
</table>

上述连接器配置如图 4.27 所示。

![](../../../_assets/그림_4.51_Backplan_커넥터_연결구조.png  )<br>
图 4.27 母板连接器配置<br>
[__SOURCE](4-basic-components/3-component-func/4-drive-module/README.md)
# 4.3.4. 驱动模块
[__SOURCE](4-basic-components/3-component-func/4-drive-module/1-H6DX-middle-6ax-drive-module.md)
# 4.3.4.1. H7D6X (中型6轴集成驱动模块)

驱动模块执行功率放大功能，使电流能够根据伺服板的电流指令流向电机的各个相。该六轴集成驱动模块可以同时驱动六个电机，配置如下。

从电源模块进入的三相电流经过二极管模块整流后，转换为直流电并存储在平滑电容器中。当机器人的电机速度减速时，电机产生的电能将通过IGBT和电阻被消耗。相关配置如下。

表4-14 H7D6X（中型6轴集成驱动模块）的配置


<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD651<br>(电源板)</td>
    <td>栅极驱动电路</td>
    <td>生成IPM栅极信号</td>
  </tr>
  <tr>
    <td>栅极电源模块</td>
    <td>传输栅极电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流经电机的电流</td>
  </tr>
  <tr>
    <td>再生控制</td>
    <td>当PN电压上升时驱动IGBT</td>
  </tr>
  <tr>
    <td>错误检测部分</td>
    <td>检测PN过电压、再生放电电阻过热和PN欠电压错误</td>
  </tr>
  <tr>
    <td>高压电容器</td>
    <td>平滑直流电</td>
  </tr>
  <tr>
    <td rowspan="2">BD652<br>(接口板)</td>
    <td>顺序联锁部分</td>
    <td>在顺序状态和伺服开启信号之间进行联锁</td>
  </tr>
  <tr>
    <td>专用IO端子排</td>
    <td>控制器内部保留的IO端口</td>
  </tr>
  <tr>
    <td rowspan="4">其他部分</td>
    <td>散热器</td>
    <td>将电源元件产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>整流部分</td>
    <td>将交流输入电源整流为驱动电机的直流电</td>
  </tr>
  <tr>
    <td>再生IGBT</td>
    <td>执行再生放电</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换三相电动机的驱动电源</td>
  </tr>
</tbody>
</table>

### 中型6轴集成驱动模块的型号配置

![](../../../_assets/중형_6축_일체형_드라이브모듈_형번_구성_en_2.png  )

表4-15 中型6轴集成驱动模块的类型符号

<table>
<tbody>
<tr class="odd">
<td><p><strong>类别</strong></p></td>
<td><p><strong>类型符号</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi7 中型6轴驱动模块</strong></p></td>
<td><p>H7D6X</p></td>
</tr>
</tbody>
</table>

表4-16 中型6轴集成驱动模块的规格

<table>
<thead>
  <tr>
    <th>配置</th>
    <th colspan="2">分类</th>
    <th colspan="2">应用</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">IPM容量</td>
    <td>3X</td>
    <td>3Y</td>
    <td>HS180, HS220, HH300, HH050</td>
    <td rowspan="2">6轴集成</td>
  </tr>
  <tr>
    <td>4X</td>
    <td>2Y</td>
    <td>HC2502B2D, HC2503B2D</td>
  </tr>
  <tr>
    <td>年份</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">生产年份：2000~2099</td>
  </tr>
  <tr>
    <td>月份</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">生产月份：一月~十二月</td>
  </tr>
  <tr>
    <td>序列号</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">每月生产数量：1~999</td>
  </tr>
</tbody>
</table>

表4-17 中型6轴驱动模块IPM的符号

<table>
<thead>
  <tr>
    <th>驱动型号</th>
    <th>IPM符号</th>
    <th>IPM规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">中型6轴驱动模块</td>
    <td>X</td>
    <td>(IPM电流等级) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM电流等级) 75A</td>
  </tr>
   <tr>
    <td>Z</td>
    <td>(IPM电流等级) 50A</td>
  </tr>
</tbody>
</table>

表4-18 中型6轴驱动模块霍尔传感器的符号

<table>
<thead>
  <tr>
    <th>驱动型号</th>
    <th>霍尔传感器符号（规格）</th>
    <th>满标电流（Im）</th>
    <th>IPM规格<br>(额定电流)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">中型6轴驱动模块</td>
  </tr>
  <tr>
    <td>1 (4V/50A)</td>
    <td>93.75Apeak</td>
    <td rowspan="5">PM100CG1APL065 202G (100A)<br>PM75CG1APL065 202G (75A)<br>PM50CG1APL065 202G (50A)</td>
  </tr>
  <tr>
    <td>2 (4V/25A)</td>
    <td>46.87Apeak</td>
  </tr>
  <tr>
    <td>3 (4V/15A)</td>
    <td>28.12Apeak</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.75Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/ 5A)</td>
    <td>9.37Apeak</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
驱动模块因机器人的类型而异，因此更换时必须检查类型。
{% endhint %}


![](../../../_assets/그림_4_20_BD651V60_부품_배치도.PNG  )</br></br>
![](../../../_assets/그림_4_21_BD651V70_부품_배치도.PNG  )</br></br>

图4.20 BD651V60、BD651V70的部件布局图</br></br>

表4-19 BD651连接器的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM信号和IPM错误信号</p></td>
<td><p>BD652的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>三相电源输入</p></td>
<td><p>电子模块的CNRST</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>变换器部分错误信号</p></td>
<td><p>BD652的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>再生放电功率输出</p></td>
<td><p>再生放电电阻</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>再生放电电阻过热检测</p></td>
<td><p>再生放电电阻温度传感器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~3</strong></p></td>
<td><p>1至3轴的电机驱动输出</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~6</strong></p></td>
<td><p>4至6轴的电机驱动输出</p></td>
<td><p>CMC2</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>额外轴驱动模块的直流电源</p></td>
<td><p>选用额外轴驱动模块的CNPN。</p></td>
</tr>
<tr class="even">
<td><p><strong>CNFG1</strong></p></td>
<td><p>1至3轴的框架接地</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG2</strong></p></td>
<td><p>4至6轴的框架接地</p></td>
<td><p>CMC2</p></td>
</tr>
</tbody>
</table>

表4-20 BD651LED的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>颜色</strong></p></td>
<td><p><strong>状态显示</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>黄</p></td>
<td><p>当磁接触驱动时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿</p></td>
<td><p>当变换器部分的控制电压正常时将被点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>红</p></td>
<td><p>当再生放电正在进行时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>红</p></td>
<td><p>当PN电压高于42V时将被点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>红</p></td>
<td><p>当PN放电进行时将熄灭</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4_22_BD652V60_부품_배치도.PNG  ) </br></br>

![](../../../_assets/그림_4_23_BD652V70_부품_배치도.PNG  ) </br></br>

图4.21 BD652V60、BD652V70的部件布局图

表4-21 BD652连接器的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>8轴的PWM信号和IPM错误信号<br>变换器部分错误信号</p></td>
<td><p>BD642的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>各个轴的PWM信号和IPM错误信号</p></td>
<td><p>BD651的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>额外轴的PWM信号和IPM错误信号</p></td>
<td><p>额外轴驱动模块（BD658或BD659）的CNPWM</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>变换器部分错误信号</p></td>
<td><p>BD651的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>仅保留用于IO端子块</p></td>
<td><p>保留</p></td>
</tr>
</tbody>
</table>

表4-22 BD652LED的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>颜色</strong></p></td>
<td><p><strong>状态显示</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>黄</p></td>
<td><p>当磁接触驱动时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿</p></td>
<td><p>当控制电源正常时将被点亮</p></td>
</tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/4-drive-module/2-H6D6A-small-6ax-drive-module.md)
# 4.3.4.2. H7D6A (小型 6 轴集成驱动模块)

驱动模块执行功率放大功能，使电流根据伺服板的电流命令流向电机的各个相位。六轴集成驱动模块可以同时驱动六个电机，其配置如下。

从电源模块输入的三相电流通过二极管模块整流，然后转换为直流电并存储在平滑电容中。当机器人的电机速度减速时，电机产生的电力通过IGBT和电阻消耗。相关配置如下。

表 4-23 H7D6A (小型 6 轴集成驱动模块) 的配置

<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>组件</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD653<br>(电源板)</td>
    <td>门驱动电路</td>
    <td>生成 IPM 门信号</td>
  </tr>
  <tr>
    <td>门电源模块</td>
    <td>生成门电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流过电机的电流</td>
  </tr>
  <tr>
    <td>再生控制</td>
    <td>当PN电压上升时开启IGBT</td>
  </tr>
  <tr>
    <td>错误检测部分</td>
    <td>检测过电压、再生电阻过热和欠电压错误</td>
  </tr>
  <tr>
    <td>高电压电容</td>
    <td>平滑直流电</td>
  </tr>
  <tr>
    <td rowspan="2">BD654<br>(接口板)</td>
    <td>序列联锁部分</td>
    <td>序列状态与伺服开启信号之间的联锁</td>
  </tr>
  <tr>
    <td>专用IO终端块</td>
    <td>控制器内部保留的IO端口</td>
  </tr>
  <tr>
    <td rowspan="4">其他部件</td>
    <td>散热器</td>
    <td>将功率元件中产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>整流部分</td>
    <td>将交流输入电源整流以产生驱动电机的直流电</td>
  </tr>
  <tr>
    <td>再生IGBT</td>
    <td>执行再生放电</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换驱动三相电机的电力</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
驱动模块因机器人类型而异，更换时必须检查类型。
{% endhint %}

### 小型 6 轴集成驱动模块的类型编号配置

![](../../../_assets/소형_6축_일체형_드라이브모듈_형번_구성_en_2.png)

表 4-24 小型 6 轴集成驱动模块的类型符号

<table>
<tbody>
<tr class="odd">
<td><p><strong>类别 </strong></p></td>
<td><p><strong>类型符号</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi7 小型 6 轴驱动模块</strong></p></td>
<td><p>H7D6A</p></td>
</tr>
</tbody>
</table>

表 4-25 小型 6 轴集成驱动模块的规格

<table>
<thead>
  <tr>
    <th>配置</th>
    <th colspan="2">分类</th>
    <th colspan="2">应用</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>IPM 容量</td>
    <td>3A</td>
    <td>3D</td>
    <td>HA006B, HH020</td>
    <td>6 轴集成 </td>
  </tr>
  <tr>
    <td>年份</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">生产年份：2000-2099</td>
  </tr>
  <tr>
    <td>月份</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">生产月份：一月至十二月</td>
  </tr>
  <tr>
    <td>序列号</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">每月生产单位数量：1~999</td>
  </tr>
</tbody>
</table>

表 4-26 小型 IPM 的容量

<table>
<thead>
  <tr>
    <th>驱动模型</th>
    <th>IPM 符号</th>
    <th>IPM 规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">小型 6 轴的驱动模块</td>
    <td>A</td>
    <td>(IPM 允许电流额定值) 30A</td>
  </tr>
  <tr>
    <td>D</td>
    <td>(IPM 允许电流额定值) 10A</td>
  </tr>
</tbody>
</table>

表 4-27 小型 IPM 的霍尔传感器符号

<table>
<thead>
  <tr>
    <th>驱动模型</th>
    <th>霍尔传感器符号 (规格)</th>
    <th>满量程电流 (Im)</th>
    <th>IPM 规格 (允许电流额定值)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">小型 6 轴的驱动模块</td>
    <td>3 (4V/15A)</td>
    <td>27.27Apeak</td>
    <td rowspan="2">6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.18Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/5A)</td>
    <td>9.19Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>6 (4V/3A)</td>
    <td>5.45Apeak</td>
  </tr>
  <tr>
    <td>7 (4V/6A)</td>
    <td>10.91Apeak</td>
    <td>6MBP50VAA060 (30A)</td>
  </tr>
  <tr>
    <td>8 (4V/2A)</td>
    <td>3.64Apeak</td>
    <td rowspan="2">6MBP20VAA060 (10A)</td>
  </tr>
  <tr>
    <td>9 (4V/1A)</td>
    <td>1.82Apeak</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
驱动模块因机器人类型而异，更换时必须检查类型。
{% endhint %}

![](../../../_assets/그림_4_24_BD653V60_부품_배치도.PNG  )

图 4.22 BD653V60 的部件布置图

表 4-28 BD653 连接器的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM 信号和 IPM 错误信号</p></td>
<td><p>BD654 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>三相电源输入</p></td>
<td><p>用于电子模块的 CNRST</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换部分错误信号</p></td>
<td><p>BD654 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>再生放电功率输出 </p></td>
<td><p>再生放电电阻</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>再生放电电阻过热检测</p></td>
<td><p>再生放电电阻温度传感器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~6</strong></p></td>
<td><p>电机驱动输出</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>用于附加轴的驱动模块的直流电</p></td>
<td><p>可选附加轴的驱动模块的 CNPN</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG1, CNFG4</strong></p></td>
<td><p>电机的框架接地</p></td>
<td><p>CMC1</p></td>
</tr>
</tbody>
</table>

表 4-29 BD653 的 LED 说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>颜色</strong></p></td>
<td><p><strong>状态显示</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>黄色</p></td>
<td><p>当磁体接触驱动时将点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当转换部分的控制电压正常时将点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>红色</p></td>
<td><p>当再生放电工作时将点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>红色</p></td>
<td><p>当 PN 电压高于 42V 时将点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>红色</p></td>
<td><p>当 PN 放电操作开始时将熄灭</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4_25_BD654V60_부품_배치도.PNG  )

图 4.23 BD654 的部件布置图</br></br>

表 4-30 BD654 连接器的说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>8 轴的 PWM 信号和 IPM 错误信号<br>转换部分错误信号</p></td>
<td><p>BD642 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>各个轴的 PWM 信号和 IPM 错误信号</p></td>
<td><p>BD653 的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>附加轴的 PWM 信号和 IPM 错误信号</p></td>
<td><p>附加轴驱动模块 (BD 658 或 BD 659) 的 CNPWM</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换部分错误信号</p></td>
<td><p>BD653 的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>仅限保留 IO 端子块</p></td>
<td><p>保留</p></td>
</tr>
</tbody>
</table>

表 4-31 BD654 的 LED 说明

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>颜色</strong></p></td>
<td><p><strong>状态显示</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>黄色</p></td>
<td><p>当磁体接触驱动时将点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当控制电源正常时将点亮</p></td>
</tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/4-drive-module/3-optional-drive-module-spec.md)
# 4.3.4.3. 可选驱动模块的规格

### 可选驱动模块的类型编号配置

![](../../../_assets/선택사양_드라이브모듈의_형번_구성_en_2.png  )

表 4-32 可选驱动模块的类型符号

<table>
<thead>
  <tr>
    <th>类别</th>
    <th>类型符号</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Hi7 1 轴驱动模块</td>
    <td>H7D1</td>
  </tr>
</tbody>
</table>

表 4-33 可选驱动模块的IPM容量

<table>
<thead>
  <tr>
    <th>驱动模型</th>
    <th>IPM符号</th>
    <th>IPM规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">附加轴的驱动模块</td>
    <td>X</td>
    <td>(IPM电流等级) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM电流等级) 75A</td>
  </tr>
  <tr>
    <td>Z</td>
    <td>(IPM电流等级) 50A</td>
  </tr>
</tbody>
</table>

表 4-34 可选驱动模块的霍尔传感器符号

<table>
<thead>
  <tr>
    <th>驱动模型</th>
    <th>霍尔传感器符号(规格)</br>满量程电流 (Im)</th>
    <th>满量程电流(Im)</th>
    <th>IPM规格</br>(额定电流</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">附加轴的驱动模块</td>
  </tr>
  <tr>
    <td>1 (4V/50A)</td>
    <td>93.75Apeak</td>
    <td rowspan="5">PM100CG1APL065 202G (100A)<br>PM75CG1APL065 202G (75A)<br>PM50CG1APL065 202G (50A)</td>
  </tr>
  <tr>
    <td>2 (4V/25A)</td>
    <td>46.87Apeak</td>
  </tr>
  <tr>
    <td>3 (4V/15A)</td>
    <td>28.12Apeak</td>
  </tr>
  <tr>
    <td>4 (4V/10A)</td>
    <td>18.75Apeak</td>
  </tr>
  <tr>
    <td>5 (4V/5A)</td>
    <td>9.37Apeak</td>
  </tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/4-drive-module/4-H6D1X-carriage-drive-module-spec.md)
# 4.3.4.4. H7D1X (载体驱动模块；可选)

驱动模块执行功率放大功能，允许电流根据伺服板的电流命令流向电机的各个相。载体驱动模块可以驱动100A或以下的一台电机，配置如下。

![](../../../_assets/그림_4_26_BD658V60_부품_배치도.PNG  )

图 4.24 H7D1X 的 BD658V60 部件布置图</br></br>

表 4-35 H7D1X 的配置

<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD658</br>(IPM 板)
</td>
    <td>逻辑部分</td>
    <td>将从驱动模块接收的六轴 PWM 信号转换为 IPM 的上下侧驱动信号，并处理错误</td>
  </tr>
  <tr>
    <td>栅极电源模块</td>
    <td>生成 IPM 栅极电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流经电机的电流</td>
  </tr>
  <tr>
    <td rowspan="2">其他部件</td>
    <td>散热器</td>
    <td>将 IPM 产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换用于驱动三相电机的电源</td>
  </tr>
</tbody>
</table>

表 4-36 H7D1X 的连接器描述

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用法</th>
    <th>外部设备连接</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM 信号和错误信号</td>
    <td>驱动模块 (BD652 或 BD654) 的 CNPWM7 或 CNPWM8，用于六轴</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>电机驱动输出</td>
    <td>AMC1 或 AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>电机的框架接地</td>
    <td>AMC1 或 AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>驱动直流电源输入</td>
    <td>驱动模块 (BD651 或 BD653) 的 CNPN7 或 CNPN8，用于六轴</td>
  </tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/4-drive-module/5-H6D1Z_servogun-drive-module-spec.md)
# 4.3.4.5. H7D1Z (伺服枪驱动模块; 可选)

驱动模块执行功率放大功能，使电流根据伺服板的当前命令流向电机的各个相。伺服枪驱动模块可以驱动一个50A或以下的电机，配置如下。

![](../../../_assets/그림_4_27_BD659V60_부품_배치도.PNG  )

图4.25 H7D1Z的BD659V60部件布置图</br></br>

表4-37 H7D1Z的配置

<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD659<br>(IPM板)</td>
    <td>逻辑部分</td>
    <td>将从驱动模块接收的六个轴的PWM信号转换为IPM的上下两侧驱动信号，并处理错误</td>
  </tr>
  <tr>
    <td>门电源模块</td>
    <td>生成IPM门电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流经电机的电流</td>
  </tr>
  <tr>
    <td rowspan="2">其他部分</td>
    <td>散热器</td>
    <td>将IPM中产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>为驱动三相电机转换电源</td>
  </tr>
</tbody>
</table>

表4-38 H7D1Z连接器的描述

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用途</th>
    <th>外部设备连接</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM信号和错误信号</td>
    <td>驱动模块（BD652或BD654）的CNPWM7或CNPWM8，用于6个轴</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>电机驱动输出</td>
    <td>AMC1或AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>电机的框架接地</td>
    <td>AMC1或AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>驱动直流电源输入</td>
    <td>驱动模块（BD651或BD653）的CNPN7或CNPN8，用于6个轴</td>
  </tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/5-power-supply-module-H6APSM/README.md)
# 4.3.5. 电源模块(H7PSM)
[__SOURCE](4-basic-components/3-component-func/5-power-supply-module-H6APSM/1-H6APSM-power-dist-bd-BD6C3.md)
# 4.3.5.1. H7PSM 和电源分配板(BD6C3)

H7PSM (Hi7-N 控制器电源模块) 模块负责控制器供电的开闭和分配。以下图展示了电气模块的内部和外部，其配有各种连接器和保险丝。

![](../../../_assets/그림_4.26_H6APSM(Hi6a-N_제어기_전원공급모듈)_외부_en.png  )<br>
图 4.34 H7PSM (Hi7-N 控制器电源模块) 外部<br>

以下图展示了与电机电源的三相交流电开闭、制动电源的生成及风扇驱动相关的交流控制电源的电源系统图。图中的电路图还展示了电源分配，例如供给控制模块的直流电源的 SMPS 电源。每个电源都连接了断路器 (CP) 或保险丝，以保护单独电路免受过流的影响。

![](../../../_assets/그림_4.27_Hi6a-N_제어기의_전원계통_en.png)<br>
图 4.35 Hi7-N 控制器的电源系统

表 4-35 电子模块保险丝的类型和使用
<table>
<thead>
  <tr>
    <th>名称</th>
    <th>功能</th>
    <th>规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>F1, F2, F3</td>
    <td>控制电源过流保护的保险丝(AC 220V)</td>
    <td>AC220V 8A</td>
  </tr>
  <tr>
    <td>FS17</td>
    <td>CMDCFAN 和 DCFAN2-5 GND 过流保护的保险丝</td>
    <td>7VAC/60VDC 7A</td>
  </tr>
  <tr>
    <td>FS18</td>
    <td>DCFAN2-5 过流保护的保险丝</td>
    <td>125VAC/125VDC 6.3A</td>
  </tr>
  <tr>
    <td>FS19</td>
    <td>控制模块冷却的直流风扇过流保护的保险丝</td>
    <td>125VAC/125VDC 0.315A</td>
  </tr>
</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/5-power-supply-module-H6APSM/2-BD6C3-connector.md)
# 4.3.5.2. BD6C3的连接器

电气板(BD6C3)的连接器布局如下面的图所示。每个连接器的功能和连接设备列在表4-40中。

![](../../../_assets/그림_4.28_전장보드(BD6C3)의_커넥터.png)<br>
图4.36 电子板(BD6C3)的连接器<br>

表4-36 BD6C3连接器的类型和功能 
<table>
<thead>
  <tr>
    <th>名称</th>
    <th>功能</th>
    <th>规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNAC1</td>
    <td>控制用的三相电源输入</td>
    <td>三相220V</td>
  </tr>
    <tr>
    <td>CNAC2</td>
    <td>控制16轴或更多的三相电源输出</td>
    <td>三相220V</td>
  </tr>
   <tr>
    <td>CNPR1</td>
    <td>冲击电流限制电路输入</td>
    <td>三相220V, MC1输入端子</td>
  </tr>
  <tr>
    <td>CNPR2</td>
    <td>冲击电流限制电路输出</td>
    <td>三相220V, MC2输出端子</td>
  </tr>
  <tr>
    <td>CNACOUT1</td>
    <td>用户的220 VAC电源输出1</td>
    <td>单相220V</td>
  </tr>
  <tr>
    <td>CNACOUT2</td>
    <td>用户的220 VAC电源输出2</td>
    <td>单相220V</td>
  </tr>
    <tr>
    <td>CNPFS1</td>
    <td>CMSMPS电源故障检测信号输出1</td>
    <td>H6COM DIO</td>
  </tr>
   <tr>
    <td>CNMC</td>
    <td>接触器控制和监测</td>
    <td>BD642 CNMC</td>
  </tr>
  <tr>
    <td>CNPRC</td>
    <td>冲击电流限制电路、风扇故障和风扇电源的控制和监测</td>
    <td>BD642 CNPRC</td>
  </tr>
  <tr>
    <td>CNFN1</td>
    <td>控制模块的直流风扇电源输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNFN2~5</td>
    <td>直流风扇电源输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOCM</td>
    <td>控制模块的SMPS 24VDC输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOH6COM</td>
    <td>H6COM的SMPS 24VDC输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOBK</td>
    <td>电机刹车的SMPS 24VDC输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNORO</td>
    <td>机器人的SMPS 24VDC输出</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNOUS</td>
    <td>用户的SMPS 24VDC输出</td>
    <td>24VDC</td>
  </tr>

  <tr>
    <td>CNCMSM</td>
    <td>控制模块的SMPS 220VAC输入</td>
    <td>单相220V</td>
  </tr>
  <tr>
    <td>CNBKSM</td>
    <td>电机刹车的SMPS 220VAC输入</td>
    <td>单相220V</td>
  </tr>
  <tr>
    <td>CNUSSM</td>
    <td>用户的SMPS 220VAC输入</td>
    <td>单相220V</td>
  </tr>
  <tr>
    <td>CNROSM</td>
    <td>机器人的SMPS 220VAC输入</td>
    <td>单相220V</td>
  </tr>

  <tr>
    <td>CNI24CM</td>
    <td>公共模块的SMPS 24VDC分配输入</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24BK</td>
    <td>制动器的SMPS 24VDC分配输入</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24RO</td>
    <td>机器人的SMPS 24VDC分配输入</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNI24US</td>
    <td>用户的SMPS 24VDC分配输入</td>
    <td>24VDC</td>
  </tr>
  
  <tr>
    <td>CNMC1</td>
    <td>磁接触器1的开/关电源输入和反馈，以及刹车控制信号控制</td>
    <td>MC1</td>
  </tr>
  <tr>
    <td>CNMC2</td>
    <td>磁接触器2的开/关电源输入和反馈，以及刹车控制信号控制</td>
    <td>MC2</td>
  </tr>
</tbody>
</table>

### 4.3.5.3. BD6C3 LED

电气板(BD6C3)的LED布局如下面的图所示。每个LED的功能、连接电源和颜色列在表4-41中。

![](../../../_assets/그림_4.29_전장보드(BD6C3)의_LED.png)<br>
图4.37 BD6C3的LED<br>

表4-37 BD6C3 LED的类型和功能
<table>
<thead>
  <tr>
    <th>名称</th>
    <th>功能</th>
    <th>规格</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>LDFNFLT</td>
    <td>当FAN 1-5中发生故障时点亮</td>
    <td>风扇故障, 红色</td>
  </tr>
  <tr>
    <td>LEDFAN</td>
    <td>当给风扇供电的24VDC继电器处于开启状态时点亮</td>
    <td>风扇电源继电器, 绿色</td>
  </tr>
  <tr>
    <td>LEDCM</td>
    <td>当控制模块的SMPS 24VDC正常供电时点亮</td>
    <td>CMSMPS, 绿色</td>
  </tr>
  <tr>
    <td>LEDBK</td>
    <td>当刹车的SMPS 24VDC正常供电时点亮</td>
    <td>BKSMPS, 绿色</td>
  </tr>
  <tr>
    <td>LEDUS</td>
    <td>当用户的SMPS 24VDC正常供电时点亮</td>
    <td>USSMPS, 绿色</td>
  </tr>
  <tr>
    <td>LEDRO</td>
    <td>当机器人的SMPS 24VDC正常供电时点亮</td>
    <td>ROSMPS, 绿色</td>
  </tr>
  <tr>
    <td>MC1LED</td>
    <td>当磁接触器1的开电源正常供电时点亮</td>
    <td>BD642, 绿色</td>
  </tr>
  <tr>
    <td>MC2LED</td>
    <td>当磁接触器2的开电源正常供电时点亮</td>
    <td>BD642, 绿色</td>
  </tr>
  <tr>
    <td>RYPRC1</td>
    <td>当预充电继电器开关信号被提供时，内部继电器点亮</td>
    <td>BD604, 绿色</td>
  </tr>
  <tr>
    <td>RYPRC2</td>
    <td>当风扇电源继电器开关信号被提供时，内部继电器点亮</td>
    <td>BD604, 绿色</td>
  </tr>

</tbody>
</table>
[__SOURCE](4-basic-components/3-component-func/6-teach-pendant-TP630/README.md)
# 4.3.6. 教导挂件(TP630)
[__SOURCE](4-basic-components/3-component-func/6-teach-pendant-TP630/1-overview.md)
# 4.3.6.1. 概述

教导手柄(TP630)通过以太网与控制器的主模块(H6COM-T)进行通信，允许用户直接操作以下功能。  
* 监控 : 工作程序 / 各轴的数据 / 输入和输出信号 / 机器人的状态等。  
* 日志管理 : 系统版本、运行时间、错误日志、停止日志等。  
* 文件管理 : 版本和教导程序的上/下传  
* 各种变量的设置 : 用户环境 / 控制 / 机器人 / 应用 / 自动整数等。  
* 机器人教学 : Jog 和教导程序注册  
* 机器人操作 : 电机开启 / 启动 / 停止 / 模式设置  

教导手柄还配备了三级使能开关和紧急停止开关，以确保用户安全。  
此外，在教导手柄底部的橡胶盖下安装了一个USB A型连接器，允许用户上传/下载必要的文件，如数据和教学程序，以及各种类型板的版本，使用USB存储器。

![](../../../_assets/그림_4.2_티칭펜던트_TP630_Hi6a.png)<br>
图 4.38 教导手柄 TP630 的外观<br>
[__SOURCE](4-basic-components/3-component-func/6-teach-pendant-TP630/2-USB-cover.md)
# 4.3.6.2. USB Cover

在教学挂件底部的橡胶盖下安装了一个USB A型连接器，允许用户使用USB闪存驱动器上传/下载必要的文件，例如各种类型电路板的版本以及数据和教学程序。
[__SOURCE](5-optional-components/README.md)
# 5. 控制器的可选组件

Table 5-1 可选配置摘要
<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">控制选项</td>
    <td>扩展安全信号板(BD680)</td>
    <td>- 8通道安全数字输入<br>- 8通道安全数字输出</td>
  </tr>
  <tr>
    <td>用户DIO板 (BD681)<br>扩展DIO板 (BD682)</td>
    <td>- 可支持48个数字输入通道<br>- 可支持48个数字输出通道<br>- - NPN/PNP可切换<br>- 8个继电器输出频道可在数字输出中选择<br>- 输送机I/F 2通道</td>    
  </tr>
  <tr>
    <td>安全通信板(BD671)</td>
    <td>- PROFiSafe/PROFiNET</td>
  </tr>
  <tr>
    <td rowspan="3">通信选项</td>
    <td>以太网/IP 主/从</td>
        <td>- 支持H6COM-T LAN端口<br>- 可在TP630中配置</td>
  </tr>
  <tr>
    <td>第二个EtherCAT主机</td>
  </tr>
  <tr>
    <td>CIP安全</td>
  </tr>  
  <tr>
    <td>PCI通信卡</td>
    <td>15种PC卡CIFX 50系列</td>
    <td>- 以太网主/从<br>- CC-Link从<br>- DeviceNET主/从<br>- PROFIBUS主/从<br>- CC-Link IE Fileld</td>
  </tr>
  <tr>
    <td>制动释放单元</td>
    <td>-</td>
    <td>- 当每个机器人轴需要释放电机制动时使用</td>
  </tr>
  <tr>
    <td>远程IO模块</td>
    <td>通信模块IO模块</td>
    <td>- 超出用户DIO信号时需要额外使用</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/1-PCI-comm-card/README.md)
# 5.1. PCI 通信卡
[__SOURCE](5-optional-components/1-PCI-comm-card/1-overview.md)
# 5.1.1. 概述

要在 Hi7 控制器中使用工业通信，可以使用 PCI 通信卡。以下描述基于以太网的 PCI 通信卡，这是一个通用型号。有关详细信息，请参阅文档 "PC Cards CIFX 50 50E 70E 100EH UM 51 EN" 中关于 PC Cards CIFX 50 型号的内容。

表 5-2 PCI 通信卡的部件名称
<table>
<thead>
  <tr>
    <th>No.</th>
    <th>型号名称</th>
    <th>通信类型</th>
    <th>接口连接器</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>CIFX 50-RE/ML-HRC</td>
    <td>HRC 实时 Ethernet 主 PCI</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>2</td>
    <td>CIFX 50-RE-HRC</td>
    <td>HRC 实时 Ethernet 从 PCI</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>3</td>
    <td>CIFX 50E-RE/ML-HRC</td>
    <td>HRC 实时 Ethernet 主 PCIe</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>4</td>
    <td>CIFX 50E-RE-HRC</td>
    <td>HRC 实时 Ethernet 从 PCIe</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>5</td>
    <td>CIFX 50-CC-HRC</td>
    <td>CC-Link 从 PCI</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>6</td>
    <td>CIFX 50E-CC-HRC</td>
    <td>CC-Link 从 PCIe</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>7</td>
    <td>CIFX 50-DN/ML-HRC</td>
    <td>DeviceNet 主 PCI</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>8</td>
    <td>CIFX 50-DN-HRC</td>
    <td>DeviceNet 从 PCI</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>9</td>
    <td>CIFX 50E-DN/ML-HRC</td>
    <td>DeviceNet 主 PCIe</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>10</td>
    <td>CIFX 50E-DN-HRC</td>
    <td>DeviceNet 从 PCIe</td>
    <td>CombiCon 雄性, 5 针</td>
  </tr>
  <tr>
    <td>11</td>
    <td>CIFX 50-DP/ML-HRC</td>
    <td>PROFIBUS 主 PCI</td>
    <td>Dsub 雌性, 9 针</td>
  </tr>
  <tr>
    <td>12</td>
    <td>CIFX 50-DP-HRC</td>
    <td>PROFIBUS 从 PCI</td>
    <td>Dsub 雌性, 9 针</td>
  </tr>
  <tr>
    <td>13</td>
    <td>CIFX 50E-DP/ML-HRC</td>
    <td>PROFIBUS 主 PCIe</td>
    <td>Dsub 雌性, 9 针</td>
  </tr>
  <tr>
    <td>14</td>
    <td>CIFX 50E-DP-HRC</td>
    <td>PROFIBUS 从 PCIe</td>
    <td>Dsub 雌性, 9 针</td>
  </tr>
  <tr>
    <td>15</td>
    <td>CIFX 50E-CCIES-HRC</td>
    <td>CC-Link IE Fileld PCIe</td>
    <td>RJ45</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/1-PCI-comm-card/2-PCI-comm-card-config.md)
# 5.1.2. PCI通信卡的配置

PCI通信卡的基本配置如下所示（当使用基于以太网的通信时），并根据工业通信的类型而有所不同的连接器和LED数量。 

![](../../_assets/그림_5.1_PCI통신_카드_외관.png  )<br>
图5.1 PCI通信卡的外观<br>

表5-3 PCI通信卡外观描述
<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用途</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>旋转开关</td>
    <td>根据槽位ID设置通信</td>
  </tr>
  <tr>
    <td>LED</td>
    <td>显示系统和通信状态</td>
  </tr>
  <tr>
    <td>通信端口</td>
    <td>通信连接端口</td>
  </tr>
  <tr>
    <td>PCI总线</td>
    <td>PC连接总线</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/1-PCI-comm-card/3-PCI-comm-card-front.md)
# 5.1.3. PCI通信卡的前面部分 

您可以通过PCI通信卡的前面部分检查通信设置、通信电缆连接和通信状态。基本上，您可以通过将旋转开关按位置顺序设置为1-4来使用该卡，具体顺序取决于H6COM-T PCI插槽的位置。

![](../../_assets/그림_5.2_PCI통신_카드_전면부.png)<br>
图5.2 PCI通信卡的前面部分<br>

表5-4 PCI通信卡前面部分的配置及功能描述 
<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用途</th>
    <th>功能描述</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>旋转开关</td>
    <td>设置每个插槽编号的通信</td>
    <td>H6COM-T PCI插槽从顶部开始依次固定为#1~#4（所设置的通信从TP开始）。</td>
  </tr>
  <tr>
    <td>系统LED</td>
    <td>系统状态检查LED</td>
    <td>绿色：系统运行中<br>黄色：引导加载程序等待</td>
  </tr>
  <tr>
    <td>通信状态LED</td>
    <td>通信状态检查LED</td>
    <td>绿色：通信正常<br>红色：通信错误</td>
  </tr>
  <tr>
    <td>通信接口</td>
    <td>通信电缆连接端口</td>
    <td>使用适合通信的连接器</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/2-brake-release-unit/README.md)
# 5.2. 刹车释放单元
[__SOURCE](5-optional-components/2-brake-release-unit/1-overview.md)
# 5.2.1. 概述

制动释放单元可用于在需要释放机器人每个轴的电机制动时。它可以帮助在机器人初始安装期间设置机器人姿态。释放制动时，必须充分理解“1.8.2 其他相关功能”中“手动制动释放”的安全信息，然后才能使用机器人。

{% hint style="info" %}
1. 不要同时释放超过两个轴。
2. 使用制动释放单元之前，保持与机器人之间的安全距离。
3. 使用制动释放单元之前，准备好使用起重机等设备降低机器人的轴。
4. 在至少两人小组中工作时检查安全事项。
{% endhint %}

{% hint style="warning" %}
机器人应根据 ISO 10218-2 的指南进行安装和操作。此外，必须遵守国际标准和国家法律的相关要求。
我们公司（或制造商）不对因未遵守国际标准和国家法律的相关要求或未遵循上述“注意事项”而发生的任何事故负责。
{% endhint %}
[__SOURCE](5-optional-components/2-brake-release-unit/2-brake-release-switch.md)
# 5.2.2. 刹车释放开关

刹车释放单元开关的放置如图5.3所示，其各自的使用和操作在表5-4中描述。要释放目标轴的刹车，首先按下启用按钮，然后在按住启用按钮的同时，同时按下B1-B8中的一个按钮。然后，相关轴将被释放。

![](../../_assets/그림_5.3_브레이크_해제유닛_스위치_및_상태확인_LED_en.png  )

图5.3 刹车释放单元的开关和状态检查LED</br></br>

表5-4 刹车释放单元开关的使用 

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>使用</th>
    <th>在操作期间</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>E</td>
    <td>刹车释放启用</td>
    <td>黄色启用LED亮</td>
  </tr>
  <tr>
    <td>B1</td>
    <td>轴1刹车释放</td>
    <td>绿色D1 LED亮</td>
  </tr>
  <tr>
    <td>B2</td>
    <td>轴2刹车释放</td>
    <td>绿色D2 LED亮</td>
  </tr>
  <tr>
    <td>B3</td>
    <td>轴3刹车释放</td>
    <td>绿色D3 LED亮</td>
  </tr>
  <tr>
    <td>B4</td>
    <td>轴4刹车释放</td>
    <td>绿色D4 LED亮</td>
  </tr>
  <tr>
    <td>B5</td>
    <td>轴5刹车释放</td>
    <td>绿色D5 LED亮</td>
  </tr>
  <tr>
    <td>B6</td>
    <td>轴6刹车释放</td>
    <td>绿色D6 LED亮</td>
  </tr>
  <tr>
    <td>B7</td>
    <td>轴7刹车释放</td>
    <td>绿色D7 LED亮</td>
  </tr>
  <tr>
    <td>B8</td>
    <td>轴8刹车释放</td>
    <td>绿色D8 LED亮</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/2-brake-release-unit/3-power-connector.md)
# 5.2.3. 电源和连接器 

刹车释放单元的电源和连接器的放置如下图5.4所示，其各自的使用和连接设备如下表5-5所示。

{% hint style="info" %}
- 使用刹车释放单元时，请遵循以下步骤。
1. 关闭AC220V电源开关，并检查DC24V电源开关是否关闭。
2. 将交流电源电缆连接到交流电源连接器。
3. 打开AC220V电源开关。
4. 打开DC24V电源开关。

- 使用刹车释放单元结束后，请遵循以下步骤。
1. 关闭DC24V电源开关。
2. 关闭AC220V电源开关。
4. 拔掉交流电源电缆。

- 请勿同时使用AC220V电源和DC24V电池电源。
{% endhint %}

{% hint style="warning" %}
我们公司（或制造商）对于因未遵循上述“注意事项”而发生的任何事故概不负责。
{% endhint %}


![](../../_assets/그림_5.4_브레이크_해제_유닛_스위치_및_커넥터_en.png)<br>
图5.4 刹车释放单元的开关和连接器</br></br>

表5-5 刹车释放单元连接器的类型和用法

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用途</th>
    <th>外部设备连接</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>AC 220V电源连接器和开关</td>
    <td>交流电源的应用</td>
    <td>100V AC~240V AC 单相</td>
  </tr>
  <tr>
    <td>刹车释放电缆连接连接器</td>
    <td>刹车释放单元与控制器的连接</td>
    <td>CNBRK16, CNB78的BD642</td>
  </tr>
  <tr>
    <td>DC24V电池电源连接器</td>
    <td>便携式24V电池的电源连接</td>
    <td>便携式24V电池</td>
  </tr>
  <tr>
    <td>DC24V电源开关</td>
    <td>刹车释放单元驱动开/关</td>
    <td>无</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/2-brake-release-unit/4-brake-release-unit-status-LED.md)
# 5.2.4. 刹车释放单元状态显示LED
用于显示刹车释放单元状态的LED如图5.3所示，其各自的使用和操作状态如下表5-6。

Table 5--6 刹车释放单元状态LED的使用和操作


<table>
<thead>
  <tr>
    <th>名称</th>
    <th>使用</th>
    <th>LED开启操作</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>启用</td>
    <td>通过按下启用开关进行检查</td>
    <td>当启用开关被按下时，</br>黄色的启用LED将亮起。</td>
  </tr>
  <tr>
    <td>D1</td>
    <td>通过按下轴1的开关进行检查</td>
    <td>当轴1的开关被按下时，绿色的D1 LED将亮起。</td>
  </tr>
  <tr>
    <td>D2</td>
    <td>通过按下轴2的开关进行检查</td>
    <td>当轴2的开关被按下时，绿色的D2 LED将亮起。</td>
  </tr>
  <tr>
    <td>D3</td>
    <td>通过按下轴3的开关进行检查</td>
    <td>当轴3的开关被按下时，绿色的D3 LED将亮起。</td>
  </tr>
  <tr>
    <td>D4</td>
    <td>通过按下轴4的开关进行检查</td>
    <td>当轴4的开关被按下时，绿色的D4 LED将亮起。</td>
  </tr>
  <tr>
    <td>D5</td>
    <td>通过按下轴5的开关进行检查</td>
    <td>当轴5的开关被按下时，绿色的D5 LED将亮起。</td>
  </tr>
  <tr>
    <td>D6</td>
    <td>通过按下轴6的开关进行检查</td>
    <td>当轴6的开关被按下时，绿色的D6 LED将亮起。</td>
  </tr>
  <tr>
    <td>D7</td>
    <td>通过按下轴7的开关进行检查</td>
    <td>当轴7的开关被按下时，绿色的D7 LED将亮起。</td>
  </tr>
  <tr>
    <td>D8</td>
    <td>通过按下轴8的开关进行检查</td>
    <td>当轴8的开关被按下时，绿色的D8 LED将亮起。</td>
  </tr>
</tbody>
</table>
[__SOURCE](5-optional-components/3-remote-io/README.md)
# 5.3. 远程 IO
[__SOURCE](5-optional-components/3-remote-io/1-overview.md)
# 5.3.1. 概述 
要在 Hi7 控制器中使用通用 IO 信号，您需要商业远程 IO。基本上，商业远程 IO 可以通过将用户选择的 "IO 模块" 连接到一个 "通信模块" 来使用。下面介绍的模块是 Crevis 的商业远程 IO 模块，您可以购买并使用其他公司的商业远程 IO。有关如何使用每个模块的详细信息，您需要向您购买的 IO 模块的公司询问。 

{% hint style="info" %}
要使用商业远程 IO，必须具备现场总线通信。因此，您应该参考上述 "5.1 PCI 通信卡" 配置 PCI 通信卡。 
{% endhint %}

![](../../_assets/그림_5.5상용_리모트_IO_구성_예시_en.png )<br>
图 5.5 商业远程 IO 配置示例<br>
[__SOURCE](5-optional-components/3-remote-io/2-comm-module-crevis.md)
# 5.3.2. 通信模块 (Crevis的)

通信模块的类型如下所示，可以根据所需的通信进行使用。

表 5-8 通信模块 (Crevis的)
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M9212</p></td>
<td><p>DeviceNet 网络适配器</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M9287</p></td>
<td><p>ProfiNet 网络适配器</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>M9289</p></td>
<td><p>ModbusTCP/UDP, EthernetIP 网络适配器</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>M9386</p></td>
<td><p>EtherCAT ID 网络适配器, 1452 字节</p></td>
</tr>
</tbody>
</table>
[__SOURCE](5-optional-components/3-remote-io/3-io-other-module-crevis.md)
# 5.3.3. IO 和其他模块 (Crevis)

IO 和其他模块的类型如下所示，可以根据所需的操作进行配置和使用。

Table 5-9 IO 模块 (Crevis)
<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M12DF</p></td>
<td><p>数字输入 16 点，通用（Sink 或</p>
<p>Source），24Vdc，18RTB</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M12FA</p></td>
<td><p>数字输入 32 点，通用（Sink 或</p>
<p>Source），24Vdc，Hirose 40P</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>M225F</p></td>
<td><p>数字输出 16 点，Sink，24Vdc/0.3A，</p>
<p>18RTB</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>M226F</p></td>
<td><p>数字输出 16 点，Source，24Vdc/0.3A，</p>
<p>18RTB</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>M22BA</p></td>
<td><p>数字输出 32 点，Sink，24Vdc/0.3A，</p>
<p>Hirose 40P</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>M2618</p></td>
<td><p>数字输出 8 点，Sink，24Vdc/1A，最大</p>
<p>8A，18RTB</p></td>
</tr>
<tr class="even">
<td><p><strong>7</strong></p></td>
<td><p>M2628</p></td>
<td><p>数字输出 8 点，Source，24Vdc/1A，最大</p>
<p>8A，18RTB</p></td>
</tr>
</tbody>
</table>

Table 5-9 IO 模块 (Crevis) 
<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M2788</p></td>
<td><p>MOS 继电器，8 点，110Vdc/ac，1A，18RTB</p></td>
</tr>
</tbody>
</table>

Table 5-10 继电器模块 (Crevis) 
<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M3534</p></td>
<td><p>模拟输入 4ch 电压，-10~10Vdc，14位</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M4534</p></td>
<td><p>模拟输出 4ch 电压，-10~10Vdc，</p>
<p>14位</p></td>
</tr>
</tbody>
</table>

Table 5-11 模拟 IO 模块 (Crevis) 
<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M5112</p></td>
<td><p>高速计数器，2 通道，24Vdc，</p>
<p>18RTB（开集电极）</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M5102</p></td>
<td><p>高速计数器，2 通道，5Vdc，</p>
<p>18RTB（RS422 差分）</p></td>
</tr>
</tbody>
</table>

Table 5-12 脉冲测量模块 (Crevis)
<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>型号名称</strong></p></td>
<td><p><strong>规格</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M5212</p></td>
<td><p>RS232 串行接口，2 通道全双工</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M5232</p></td>
<td><p>RS485 串行接口，2 通道全双工</p></td>
</tr>
</tbody>
</table>
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/README.md)
# 5.4. 选项安全IO模块(BD680)
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/1-overview.md)
# 5.4.1. 概述

可选安全 I/O 模块(BD680)在需要时提供额外的安全 I/O 信号。

当机器人控制器的现场部署需要额外的安全 I/O 信号时，该模块通过安装在伺服/安全模块(BD642)上进行操作。BD680 模块不能独立使用，必须通过板对板连接器连接到 BD642，该连接器提供操作所需的电源、控制信号和接口连接。

安全 I/O 信号由 8 个数字输入信号和 8 个数字输出信号组成。
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/2-connector.md)
# 5.4.2. 连接器

下图显示了可选安全I/O模块(BD680)所需外部连接的连接器位置。下表描述了每个连接器的名称和功能。

![](../../_assets/BD680_PCB_커넥터.png)   
图 5.4.2-1 可选安全I/O模块(BD680)上的连接器布局   

表 5.4.2-1 BD680连接器的名称、功能和外部连接设备
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>功能</strong></th>
    <th><strong>外部连接设备</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>A</td>
    <td>CNSO2</td>
    <td>安全输出端子</td>
    <td>外部设备</td>
  </tr>
  <tr>
    <td>B</td>
    <td>CNSI2</td>
    <td>安全输入端子</td>
    <td>外部设备</td>
  </tr>
  <tr>
    <td>C</td>
    <td>J1
      <br>J2</td>
    <td>BD642连接（板对板）（板对板）</td>
    <td>伺服/安全模块(BD642)</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
当安全相关输入连接并激活时，请始终参考“1.11. 机器人操作期间的安全措施”以验证正确功能。
{% endhint %}
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/3-display.md)
# 5.4.3. 指示设备

(1) 主板顶面指示灯   

下图显示了Option安全IO模块(BD680)上指示LED的位置。下表描述了每个指示灯的含义。

![](../../_assets/BD680_PCB_상태.png)   
图5.4.3-1 Option安全IO模块(BD680)上指示LED的布局

表5.4.3-1 Option安全IO模块(BD680)的指示描述
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>指示</strong></th>
    <th><strong>颜色</strong></th>
    <th><strong>正常状态</strong></th>
    <th><strong>异常 / 操作</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)</td>
    <td>LED1</td>
    <td>安全输出通道A状态</td>
    <td>黄色</td>
    <td>开</td>
    <td>
      症状: LED熄灭
      <br>原因: A通道输入电源异常
      <br>操作1: 检查A通道输入电源(24V)
      <br>操作2: 检查保险丝(FS1)
    </td>
  </tr>
  <tr>
    <td>(2)</td>
    <td>LED2</td>
    <td>安全输出通道B状态</td>
    <td>黄色</td>
    <td>开</td>
    <td>
      症状: LED熄灭
      <br>原因: B通道输入电源异常
      <br>操作1: 检查B通道输入电源(24V)
      <br>操作2: 检查保险丝(FS2)
    </td>
</table>
</tbody>

(2) 前面板指示灯   

下图显示了Option安全I/O模块(BD680)的前面板指示灯。下表描述了每个指示灯的功能和含义。

![](../../_assets/BD680_전면표시장치.png)   
图5.4.3-2 Option安全I/O模块(BD680)前面板指示灯布局   

表5.4.3-2 Option安全I/O模块(BD680)前面板指示灯描述 
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>指示</strong></th>
    <th><strong>颜色</strong></th>
    <th><strong>显示状态</strong></th>
    <th><strong>描述 / 操作</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>(1)</td>
    <td>SW1</td>
    <td></td>
    <td></td>
    <td></td>
    <td>保留</td>
  </tr>
  <tr>
    <td rowspan="2">(2)</td>
    <td>A_SOx<br>
        (x=1~8)</td>
    <td>A通道安全输出x状态</td>
    <td rowspan="2">绿色</td>
    <td rowspan="2">开<br>关</td>
    <td rowspan="2">每个通道的安全输出x为开。<br>
                    每个通道的安全输出x为关。</td>
  </tr>
  <tr>
    <td>B_SOx<br>
        (x=1~8)</td>
    <td>B通道安全输出x状态</td>
  </tr>

  <tr>
    <td rowspan="2">(3)</td>
    <td>A_SIx<br>
        (x=1~8)</td>
    <td>A通道安全输入x状态</td>
    <td rowspan="2">绿色 </td>
    <td rowspan="2">开<br>关</td>
    <td rowspan="2">每个通道的安全输入x为开。<br>
                    每个通道的安全输入x为关。</td>
  </tr>
  <tr>
    <td>B_SIx<br>
        (x=1~8)</td>
    <td>B通道安全输入x状态</td>
  </tr>
</table>
</tbody>
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/4-setting.md)
# 5.4.4. 设置设备

以下图显示了可选安全 IO 模块 (BD680) 上设置（开关）设备的位置。下表描述了每个设置的目的。

![](../../_assets/BD680_PCB_설정.png)   
图 5.4.4-1 可选安全 IO 模块 (BD680) 上的设置设备布局

表 5.4.4-1 设置设备 (SW1) 描述 - 可选安全 IO 模块 (BD680)
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>设置状态</strong></th>
    <th><strong>设置功能</strong></th>
    <th><strong>备注</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>①</td>
    <td>SW1</td>
    <td>-</td>
    <td>-</td>
    <td>保留以备将来使用</td>
  </tr>
</table>
</tbody>
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/5-cnso-conn.md)
# 5.4.5. 安全输出接线

{% hint style="warning" %}
在接线安全输出时，始终确保控制器电源在进行任何接线工作之前处于关闭状态。
{% endhint %}

下图显示了实际的可选安全IO模块(BD680)以及在安装时从前方看到的安全输出连接器的位置。

![](../../_assets/BD680_전면사진_안전출력.png)  
图5.4.5-1 可选安全IO模块(BD680)-前视图和安全输出连接器位置

接线方法取决于使用内部电源或外部电源。以下部分说明了每种情况的接线方式。

(1) 使用内部电源  
下图中，红色代表A通道，蓝色代表B通道。  
A通道(内部电源)：如图所示，将连接器CNSO2的引脚1-2和11-12连接。  
B通道(内部电源)：如图所示，将连接器CNSO2的引脚13-14和23-24连接。  
有关连接到外部设备的接线示例，请参见下面的接线示例。

![](../../_assets/BD680_안전출력_내부전원.png)  
图5.4.5-2 可选安全IO模块(BD680)-使用内部电源的安全输出接线

(2) 使用外部电源  
下图中，红色代表A通道，蓝色代表B通道。  
连接器CNSO2的引脚1、12、13和24未连接。  
A通道(外部电源)：将EX_AV(24V)连接到引脚2，将EX_AG(GND)连接到引脚11。  
B通道(外部电源)：将EX_BV(24V)连接到引脚14，将EX_BG(GND)连接到引脚23。  
有关连接到外部设备的接线示例，请参见下面的接线示例。

![](../../_assets/BD680_안전출력_외부전원.png)  
图5.4.5-3 可选安全IO模块(BD680)-使用外部电源的安全输出接线
[__SOURCE](5-optional-components/4-BD680-Option-safetyIO-board/6-cnsi-conn.md)
# 5.4.6. 安全输入接线

{% hint style="warning" %}
在进行安全输入接线时，请确保控制器电源在开始接线工作之前已关闭。
{% endhint %}

下图显示了可选安全 IO 模块（BD680）的实际外观以及从正面视图看到的安全输入连接器（CNSI2）的位置。

![](../../_assets/BD680_전면사진_안전입력.png)  
图 5.4.6-1 可选安全 IO 模块（BD680）-物理视图和安全输入连接器（CNSI2）位置

安全输入的接线因使用内部电源或外部电源以及信号类型（NPN/PNP）而异。以下图示说明了每种情况下的接线配置。

(1) 使用内部电源时  
* NPN-TYPE(: 低电平有效)  
在下图中，红色代表 A 通道，蓝色代表 B 通道。  
A 通道：使用内部电源时，如图所示连接连接器 CNSI2 上的引脚 1-3。  
B 通道：使用内部电源时，如图所示连接连接器 CNSI2 上的引脚 13-15。  
有关连接外部设备的示例，请参见下方接线示例。

![](../../_assets/BD680_안전입력_내부전원_NPN.png)  
图 5.4.6-2 可选安全 IO 模块（BD680）-使用内部电源的安全输入接线（NPN-TYPE）

* PNP-TYPE(: 高电平有效)  
在下图中，红色代表 A 通道，蓝色代表 B 通道。  
A 通道：使用内部电源时，如图所示连接连接器 CNSI2 上的引脚 3-12。  
B 通道：使用内部电源时，如图所示连接连接器 CNSI2 上的引脚 15-24。  
有关连接外部设备的示例，请参见下方接线示例。

![](../../_assets/BD680_안전입력_내부전원_PNP.png)  
图 5.4.6-3 可选安全 IO 模块（BD680）-使用内部电源的安全输入接线（PNP-TYPE）

{% hint style="warning" %}
在连接外部设备时，切勿将内部电源用作外部设备的电源。
{% endhint %}  

(2) 使用外部电源时  
* NPN-TYPE(: 低电平有效)  
图中的红色表示 A 通道，蓝色表示 B 通道。  
A 通道：使用外部电源时，请勿连接连接器 CNSI2 上的引脚 1 和 12。将外部电源 EX_AV 连接到引脚 3。  
B 通道：使用外部电源时，请勿连接连接器 CNSI2 上的引脚 13 和 24。将外部电源 EX_BV 连接到引脚 15。  
有关与外部设备连接的示例，请参见下方接线示例。

![](../../_assets/BD680_안전입력_외부전원_NPN.png)  
图 5.4.6-4 使用外部电源的安全输入接线图（NPN-TYPE）适用于可选安全 I/O 模块（BD680）

* PNP-TYPE(: 高电平有效)  
图中的红色表示 A 通道，蓝色表示 B 通道。  
A 通道：使用外部电源时，请勿连接连接器 CNSI2 上的引脚 1 和 12。将外部电源 EX_AG 连接到引脚 3。  
B 通道：使用外部电源时，请勿连接连接器 CNSI2 上的引脚 13 和 24。将外部电源 EX_BG 连接到引脚 15。  
有关与外部设备连接的示例，请参见下方接线示例。

![](../../_assets/BD680_안전입력_외부전원_PNP.png)  
图 5.4.6-5 使用外部电源的安全输入接线图（PNP-TYPE）适用于可选安全 I/O 模块（BD680）
[__SOURCE](5-optional-components/5-UserDIO/README.md)
# 5.5. 用户 DIO
[__SOURCE](5-optional-components/5-UserDIO/1-overview.md)
# 5.5.1 概述 

在 Hi7 中，'用户 DIO 板 (BD681)' 和 '扩展 DIO 板 (BD682)' 可以用于处理通用 I/O 信号并同步传送带编码器。

{% hint style="info" %}
在本手册中，DIO 指数字输入和输出。
{% endhint %}

'扩展 DIO 板 (BD682)' 不能单独使用，必须与 '用户 DIO 板 (BD681)' 一起使用。

表 5-18 板规范 
<table>
<thead>
    <tr>
        <th style="width: 50px; text-align: center;">
            No.
        </th>
        <th style="width: 110px; text-align: center;">
             板名称<br>
            (板标识符)
        </th>
        <th style="width: 300px; text-align: center;">
            板功能
        </th>
    </tr>
</thead>
<tbody>
    <tr>
        <td style="text-align: center;">
            <strong>1</strong>
        </td>
        <td style="text-align: center;">
            用户 DIO 板<br>
            (BD681)
        </td>
        <td> 
             - 16 通道通用输入<br>
             - 16 通道通用输出
        </td>
    </tr>
    <tr>
        <td style="text-align: center;">
            <strong>2</strong>
        </td>
        <td style="text-align: center;">
            用户 DIO 板<br>
            (BD682)
        </td>
        <td> 
             - 16 通道通用输入<br>
             - 16 通道通用输出<br> 
             - 2 通道传送带编码器<br> 
             - 不能独立使用（必须与 BD681 一起使用）
        </td>
    </tr>
</tbody>
</table>

<br>
通过使用两个 BD681 和一个 BD682，最多可以控制 48 个输入/输出通道。
<br><br>
[__SOURCE](5-optional-components/5-UserDIO/2-HW-Inform.md)
# 5.5.2 硬件信息
用户 IO 模块 (BD681) 允许通过数字输入/输出端口与各种设备进行连接和配置。  
此外，扩展 IO 模块 (BD682) 允许添加数字 I/O 端口并与传送带系统同步。<br>
板的基本硬件配置如下：

![](../../_assets/그림_5_31_BD681_BD682_HW_및_커넥터_정보_en.png)<br>

### 5.5.2.1 数字输入
以下图形和表格显示了数字输入端子块的引脚配置。每个端子块可以接收 16 个输入信号，支持 NPN 或 PNP 类型的输入，具体取决于应用。当附加安装 BD682 时，增加 16 个数字输入。有关如何配置 NPN 和 PNP 信号的详细信息，请参见功能手册。

![](../../_assets/그림_5.34_BD681_디지털_입력_커넥터_핀맵_en.png)<br>
| No. | 信号名称   | 描述   |No. | 信号名称 | 描述 |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_IN_A |COM 信号<br>(1~8)    | 11 | COM_IN_B | COM 信号<br>(9~16) |        
| 2    |A1|数字输入 1| 12 | B1 |数字输入 9    |
| 3    |A2|数字输入 2| 13 | B2 |数字输入 10   |
| 4    |A3|数字输入 3| 14 | B3 |数字输入 11   |
| 5    |A4|数字输入 4| 15 | B4 |数字输入 12   |
| 6    |A5|数字输入 5| 16 | B5 |数字输入 13   |
| 7    |A6|数字输入 6| 17 | B6 |数字输入 14   |
| 8    |A7|数字输入 7| 18 | B7 |数字输入 15   |
| 9    |A8|数字输入 8| 19 | B8 |数字输入 16   |
| 10   | COM_IN_A| COM 信号<br>(1~8)  |  20 | COM_IN_B  | COM 信号<br>(9~16)| <br>

当附加安装扩展 DIO 板 (BD682) 时，引脚图如下所示：<br>

![](../../_assets/그림_5.35_BD682_디지털_입력_커넥터_핀맵_en.png)<br>
| No. | 信号名称   | 描述   |No. | 信号名称 | 描述 |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_IN_A |COM 信号<br>(1~8)    | 11 | COM_IN_B | COM 信号<br>(9~16) |        
| 2    |A9|数字输入 1| 12 | B1 |数字输入 9    |
| 3    |A10|数字输入 2| 13 | B2 |数字输入 10   |
| 4    |A11|数字输入 3| 14 | B3 |数字输入 11   |
| 5    |A12|数字输入 4| 15 | B4 |数字输入 12   |
| 6    |A13|数字输入 5| 16 | B5 |数字输入 13   |
| 7    |A14|数字输入 6| 17 | B6 |数字输入 14   |
| 8    |A7|数字输入 7| 18 | B7 |数字输入 15   |
| 9    |A8|数字输入 8| 19 | B8 |数字输入 16   |
| 10   | COM_IN_A| COM 信号<br>(1~8)  |  20 | COM_IN_B  | COM 信号<br>(9~16)| <br>

### 5.5.2.2 数字输出
以下图形和表格显示了数字输出端子块的引脚配置。每个端子块可以传输 16 个输出信号，支持 NPN 或 PNP 类型的输出，具体取决于应用。<br>
当附加安装 BD682 时，增加 16 个数字输出。<br>

![](../../_assets/그림_5.33_BD681_디지털_출력_커넥터_핀맵_en.png)<br>

| No. | 信号名称   | 描述   |No. | 信号名称 | 描述 |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_OUT_A |COM 信号<br>(1~8)    | 11 | COM_OUT_B | COM 信号<br>(9~16) |        
| 2    |A1|数字输出 1| 12 | B1 |数字输出 9    |
| 3    |A2|数字输出 2| 13 | B2 |数字输出 10   |
| 4    |A3|数字输出 3| 14 | B3 |数字输出 11   |
| 5    |A4|数字输出 4| 15 | B4 |数字输出 12   |
| 6    |A5|数字输出 5| 16 | B5 |数字输出 13   |
| 7    |A6|数字输出 6| 17 | B6 |数字输出 14   |
| 8    |A7|数字输出 7| 18 | B7 |数字输出 15   |
| 9    |A8|数字输出 8| 19 | B8 |数字输出 16   |
| 10   | COM_OUT_A| COM 信号<br>(1~8)  |  20 | COM_OUT_B  | COM 信号<br>(9~16)| <br>

扩展DIO板(BD682) 追加安装时，引脚图如下：<br>
![](../../_assets/그림_5.36_BD682_디지털_출력_커넥터_핀맵_en.png)<br>
| No. | 信号名称   | 描述   |No. | 信号名称 | 描述 |
|------|---------|---------- |-----|-------- |----------|
| 1    |COM_OUT_A |COM 信号<br>(17~24)    | 11 | COM_OUT_B | COM 信号<br>(25~32) |        
| 2    |A9|数字输出 17| 12 | B9 |数字输出 25    |
| 3    |A10|数字输出 18| 13 | B10 |数字输出 26   |
| 4    |A11|数字输出 19| 14 | B11 |数字输出 27   |
| 5    |A12|数字输出 20| 15 | B12 |数字输出 28   |
| 6    |A13|数字输出 21| 16 | B13 |数字输出 29   |
| 7    |A14|数字输出 22| 17 | B14 |数字输出 30   |
| 8    |A15|数字输出 23| 18 | B15 |数字输出 31   |
| 9    |A16|数字输出 24| 19 | B16 |数字输出 32   |
| 10   | COM_OUT_A| COM 信号<br>(17~24)  |  20 | COM_OUT_B  | COM 信号<br>(25~32)| <br>

### 5.5.2.3 传送带
以下图形显示了与编码器输入和限位开关同步的传送带配置。  
其包含两个输入通道。每个通道支持两种类型的编码器（开路集电极/线路驱动）。<br>

![](../../_assets/그림_5.37_BD682_컨베이어_커넥터_핀맵_en.png)<br>

| No. | 信号名称   | 描述   |No. | 信号名称 | 描述 |
|------|---------|---------- |-----|-------- |----------|
| 1    |PA2_P    |通道 2 线路驱动类型编码器<br> A 信号输入正极| 11 | PA1_P |通道 1 线路驱动类型编码器 <br> A 信号输入正极|        
| 2    |PA2_N    |通道 2 线路驱动类型编码器<br> A 信号输入负极| 12 | PA1_N |通道 1 线路驱动类型编码器 <br> A 信号输入负极|
| 3    |PB2_P    |通道 2 线路驱动类型编码器<br> B 信号输入正极| 13 | PB1_P |通道 1 线路驱动类型编码器 <br> B 信号输入正极 |
| 4    |PB2_N    |通道 2 线路驱动类型编码器<br> B 信号输入负极| 14 | PB1_N |通道 2 线路驱动类型编码器<br> B 信号输入负极 |
| 5    |LDLS2    |通道 2 线路驱动类型编码器<br> 限位开关  | 15 | LDLS1 |通道 1 线路驱动类型编码器 <br> 限位开关 
| 6    |GND      |接地  | 16 | GND |接地 |
| 7    |P2+      |通道 2 开路集电极编码器电源  | 17 | P1+ |通道 1 开路集电极编码器电源    |
| 8    |A2       |通道 2 开路集电极类型编码器 <br> A 信号输入| 18 | A1 |通道 1 开路集电极类型编码器 <br> A 信号输入  |
| 9    |B2       |通道 2 开路集电极类型编码器 <br> B 信号输入| 19 | B1 |通道 1 开路集电极类型编码器  <br> B 信号输入   |
| 10   |OCLS2    |通道 2 开路集电极类型编码器 <br> 限位开关   |  20 | OCLS1  | 通道 1 开路集电极类型编码器  <br> 限位开关 | <br>
[__SOURCE](5-optional-components/6-PROFIsafe-Board/README.md)
# 5.6. 安全通信板(BD671)
[__SOURCE](5-optional-components/6-PROFIsafe-Board/1-overview.md)
### 5.6.1. 概述

在 Hi7 中，使用 **'PROFIsafe board (BD671)'** 允许处理与安全相关的信号。此板基于 PROFIsafe 通信协议，并支持在标准现场总线网络（例如，PROFINET）上传输安全信号。
PROFIsafe 是一个国际安全通信标准，能够在 PROFIBUS/PROFINET 网络上同时传输与安全相关的数据和标准数据。
[__SOURCE](5-optional-components/6-PROFIsafe-Board/2-HW-Inform.md)
# 5.6.2. 连接器

下图显示了用于外部连接可选安全通信板 (BD671) 的连接器的位置。此外，下表描述了每个连接器的名称和用途。

![](../../_assets/그림_6.2_안전통신보드이미지.png)<br>
图 6.2-1 安全通信板 (BD671) 连接器布局<br>

表 6.2-1 安全通信板(BD671) 连接器名称及应用
<table>
<tbody>
  <tr>
    <td><strong>编号</strong></td>
    <td><strong>名称</strong></td>
    <td><strong>功能</strong></td>
    
  </tr>
  <tr>
    <td>A</td>
    <td>状态 LED</td>
    <td>EtherCAT, PROFIsafe 通信状态 LED </td>
    
  </tr>
  <tr>
    <td>B</td>
    <td>EtherCAT RJ45 连接器 IN/OUT </td>
    <td>内部 EtherCAT 通信连接器</td>
    
  </tr>
  <tr>
    <td>C</td>
    <td>PROFIsafe RJ45 连接器 </td>     
    <td>用户 PROFIsafe 通信</td>
    
  </tr>
    <tr>
    <td>D</td>
    <td>背板连接连接器</td>     
    <td>与 BD642(安全)板的通信和电源供应</td>
    
  </tr>
</tbody>
</table>


表 6.2-2 部件 A 中状态 LED 的名称和用途
<table>
<tbody>
  <tr>
    <td><strong>名称</strong></td>
    <td><strong>M1 状态</strong></td>
    <td><strong>诊断 LED</strong></td>
    <td><strong>维护 LED</strong></td>
    <td><strong>미삽</strong></td>
    <td><strong>EtherCAT 诊断 LED</strong></td>
    
  </tr>
  <tr>
    <td>LEDS1</td>
    <td>绿色 (运行)</td>
    <td>橙色 </td>
    <td>黄色 </td>
    <td>- </td>
    <td>绿色 (运行) </td>
    
  </tr>
  <tr>
    <td>LEDS2</td>
    <td>红色 (错误)</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>红色(错误) </td>
    
  </tr>

</tbody>
</table>
[__SOURCE](6-regular-inspection/README.md)
# 6. 定期检查

对控制器的定期检查旨在最小化故障的发生并持续维护性能。本节描述了定期检查期间的注意事项和工作内容。
[__SOURCE](6-regular-inspection/1-inspection-schedule.md)
# 6.1. 检查计划

检查应根据下图所示的计划进行。定期检查旨在提前防止故障，并在控制器和操作器长期使用时确保安全和维持准确性。定期检查是绝对必要的，即使在正常操作期间也必须进行。

![](../_assets/그림_6.1_점검_일정_en.png )<br>
图 6.1 检查计划<br>
[__SOURCE](6-regular-inspection/2-regular-insp-general-cautions.md)
# 6.2. 定期检查的一般注意事项

* 检查工作应由已完成我公司机器人培训中心实施的课程的人进行。
* 在进行检查工作之前，检查所需的零件、工具、图纸等。
* 使用我公司指定的专用替换零件。
* 检查操作器时请关闭电源。
* 在门打开的情况下进行工作时，请关闭主电源，并采取措施以禁止灰尘等飞入周围区域。
* 当需要触摸控制器的部件时，您应特别小心，防止静电损坏IC（在接触连接器时也要小心）。
* 在操作操作器的同时进行定期检查时，请采取措施禁止任何人进入操作范围内。
* 您应在指定地点测量电压，并采取措施防止电击和短路。
* 不要同时检查机器人和控制器。
* 检查后，必须执行试运行以检查机器人的操作，然后才能进行正常操作。
[__SOURCE](6-regular-inspection/3-general-inspection.md)
# 6.3. 一般检查

Table 6-1 每日检查 
<table>
<thead>
  <tr>
    <th>No.</th>
    <th>要检查的元素</th>
    <th>要检查的项目</th>
    <th>备注 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">1</td>
    <td rowspan="3">控制器</td>
    <td>显示灯正常吗?</td>
    <td>亲自检查。</td>
  </tr>
  <tr>
    <td>门关闭得好吗?</td>
    <td>亲自检查。</td>
  </tr>
  <tr>
    <td>教学挂件的屏幕有问题吗?</td>
    <td>亲自检查。</td>
  </tr>
  <tr>
    <td rowspan="4">2</td>
    <td rowspan="4">操纵器</td>
    <td>操作时有噪音吗?</td>
    <td>亲耳倾听。</td>
  </tr>
  <tr>
    <td>前端连接部分的螺丝有松动吗?</td>
    <td>紧固。</td>
  </tr>
  <tr>
    <td>操纵器的电线和线束有划痕、污染或损坏吗?</td>
    <td>亲自检查。</td>
  </tr>
  <tr>
    <td>操纵器上有造成损坏的污垢或障碍物吗?</td>
    <td>亲自检查，然后清理。</td>
  </tr>
  <tr>
    <td>3</td>
    <td>其他</td>
    <td>控制器和操纵器周围的区域有干扰吗?</td>
    <td>亲自检查。</td>
  </tr>
</tbody>
</table>
[__SOURCE](6-regular-inspection/4-first-inspection-750-hour.md)
# 6.4. 首次检查（达到750小时时的检查）  

Table 6-2 首次检查 
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>检查项目</strong></p></td>
<td><p><strong>待检查项</strong></p></td>
<td><p><strong>备注</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p> 外部和主要螺丝 </p></td>
<td><p>螺丝松动 </p></td>
<td><p>紧固</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>电气接线连接器和机械手的线束</p></td>
<td><p>连接器松动</p></td>
<td><p>紧固</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>固定犬和限位开关的螺丝</p></td>
<td><p>连接器松动 </p></td>
<td><p>紧固</p></td>
</tr>
</tbody>
</table>
[__SOURCE](6-regular-inspection/5-periodic-inspection.md)
# 6.5. 循环检查 

Table 6-3 循环检查 
<table>
<thead>
  <tr>
    <th rowspan="2">编号</th>
    <th colspan="3">周期<br>(月份)</th>
    <th rowspan="2">检查要素</th>
    <th rowspan="2">检查项目</th>
    <th rowspan="2">备注</th>
  </tr>
  <tr>
    <th>3</th>
    <th>6</th>
    <th>12</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>门的包装</td>
    <td>检查变形和脱落</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4">2</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">后部</td>
    <td>检查冷却风扇叶片部件上的灰尘和旋转</td>
    <td></td>
  </tr>
  <tr>
    <td>检查再生放电电阻器的损坏和灰尘</td>
    <td></td>
  </tr>
  <tr>
    <td>使用触觉检查变压器室的热量，然后清理该房间</td>
    <td></td>
  </tr>
  <tr>
    <td>检查变压器接线端子是否松动和损坏</td>
    <td></td>
  </tr>
  <tr>
    <td>3</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>线束</td>
    <td>检查连接器是否松动和损坏</td>
    <td></td>
  </tr>
  <tr>
    <td>4</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>电机驱动</td>
    <td>检查连接器和接线端子是否松动和损坏</td>
    <td></td>
  </tr>
  <tr>
    <td>5</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>各个板的连接器</td>
    <td>使用触觉检查是否松动</td>
    <td></td>
  </tr>
  <tr>
    <td>6</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>操作面板</td>
    <td>检查按钮和开关的状态</td>
    <td></td>
  </tr>
  <tr>
    <td>7</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>整个控制器</td>
    <td>清理灰尘</td>
    <td></td>
  </tr>
  <tr>
    <td>8</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>铭牌</td>
    <td>检查各种铭牌</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4">9</td>
    <td rowspan="4"></td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">电压测量</td>
    <td>主电源电压</td>
    <td rowspan="4"></td>
  </tr>
  <tr>
    <td>CNFN1 B2-C2</td>
  </tr>
  <tr>
    <td>CNPB1 PB-MB</td>
  </tr>
  <tr>
    <td> CN24VB1 P24B-24GND</td>
  </tr>
  <tr>
    <td>10</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>接地</td>
    <td>检查接线端子是否松动和脱落</td>
    <td></td>
  </tr>
  <tr>
    <td>11</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>电池</td>
    <td>检查电压并定期更换电池</td>
    <td>主板LED</td>
  </tr>
  <tr>
    <td rowspan="4">12</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">教导手柄</td>
    <td>检查外部并检查连接器连接部分</td>
    <td></td>
  </tr>
  <tr>
    <td>LCD显示检查LCD显示的状态</td>
    <td></td>
  </tr>
  <tr>
    <td>检查LED的显示</td>
    <td></td>
  </tr>
  <tr>
    <td>检查按钮、开关和LED的状态</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="5">13</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td rowspan="5">安全相关部件</td>
    <td>检查紧急停止开关（在控制器和教导手柄上）</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>检查主电源断路器开关（NFB1）</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>检查教导手柄的启用装置</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>检查电路保护器（CP1）</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>检查磁簧开关（MC1,2）</td>
    <td></td>
  </tr>
  <tr>
    <td>14</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>安全相关电路板</td>
    <td>检查BD642（连接器，LED）</td>
    <td></td>
  </tr>
</tbody>
</table>
[__SOURCE](6-regular-inspection/6-long-vacation-inspection.md)
# 6.6. 长假前的检查

在长假之前，您应首先检查以下项目，然后再关闭机器人的控制器。

(1) 检查主板上用于电池放电检测的黄色 LED （BATLOW）是否已开启。如果电池出现问题，黄色 LED 将会开启。在这种情况下，请用额定容量的电池替换电池。如果在电池出现问题时关闭控制器输入电源，主板上的各种程序和整数数据将在大约七天后被删除。因此，您必须使用 HRView 或 USB 存储器备份它们。

(2) 检查控制器的门是否已固定。
[__SOURCE](6-regular-inspection/7-repare-part-item.md)
# 6.7. 维护零件

以下是各个零件的特性。   

类别A的维护零件

{% hint style="info" %}
这些是日常维护和检查时需要准备的重要零件。
{% endhint %}


为了保持正常操作，类别A-2和类别A-3的零件是最低限度的必要零件，每组至少应准备一套。 

表6-4 类别A的维护零件检查 
<table>
<thead>
  <tr>
    <th>类型 </th>
    <th>内容  </th>
    <th>备注 (参考)  </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>类别A-1的维护零件</td>
    <td>标准零件的备件</td>
    <td></td>
  </tr>
  <tr>
    <td>类别A-2的维护零件</td>
    <td>重要备份零件</td>
    <td></td>
  </tr>
  <tr>
    <td>类别A-3的维护零件</td>
    <td>定期更换零件</td>
    <td></td>
  </tr>
</tbody>
</table>

表6-5 类别A-1的维护零件（标准零件的备件） 
<table>
<thead>
  <tr>
    <th>编号</th>
    <th>零件名称 </th>
    <th>类型 </th>
    <th>制造商</th>
    <th>数量(EA)</th>
    <th>备注 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>熔断器 (F1,F2)</td>
    <td>GP75(250V, 7.5A)</td>
    <td>Daito</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
  <tr>
    <td>2</td>
    <td>熔断器 (F3,F4)</td>
    <td>GP75(250V, 7.5A)</td>
    <td>Daito</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
  <tr>
    <td>3</td>
    <td>熔断器 (F5,F6)</td>
    <td>GP75(250V, 7.5A)</td>
    <td>Daito</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
  <tr>
    <td>4</td>
    <td>熔断器 (F1)</td>
    <td>0458007.DR(63V, 7A)</td>
    <td>Littelfuse</td>
    <td>1</td>
    <td>BD604</td>
  </tr>
</tbody>
</table>

表6-6 类别A-2的维护零件（重要备份零件） 
<table>
<thead>
  <tr>
    <th>编号</th>
    <th>零件名称 </th>
    <th>类型 </th>
    <th>制造商</th>
    <th>数量(EA) </th>
    <th>备注 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>电动机驱动 </td>
    <td>H7D6X<br>H7D6A</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>中型机器人 小型机器人</td>
  </tr>
  <tr>
    <td>2</td>
    <td>主控制模块</td>
    <td>H6COM-T</td>
    <td>现代机器人</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td>3</td>
    <td>教导手柄</td>
    <td>TP630</td>
    <td>现代机器人</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td>4</td>
    <td> 电源模块 </td>
    <td>H7PSM30<br>H7PSM15</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>大型机器人 中型机器人 小型机器人</td>
  </tr>
  <tr>
    <td rowspan="3">5</td>
    <td rowspan="3">电路板</td>
    <td>BD642</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>伺服/安全电路板</td>
  </tr>
  <tr>
    <td>BD604</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>背板电路板</td>
  </tr>
</tbody>
</table>

表6-7 类别A-3的维护零件（定期更换零件）
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>零件名称 </strong></p></td>
<td><p><strong>类型 </strong></p></td>
<td><p><strong>制造商</strong></p></td>
<td><p><strong> 数量(EA) </strong></p></td>
<td><p><strong>备注 </strong></p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>电池 (3.6V AA 型号)</p></td>
<td><p>ER6V-T1</p></td>
<td><p>TOSHIBA (日本)</p></td>
<td><p>1</p></td>
<td><p>每两年更换一次</p></td>
</tr>
</tbody>
</table>

类别B的维护零件

{% hint style="info" %}
这些是用于购买多个单元时需要准备的维护零件。
{% endhint %}


表6-8 类别B的维护零件 
<table>
<tbody>
<tr class="odd">
<td><p><strong>类型</strong></p></td>
<td><p><strong>内容</strong></p></td>
<td><p><strong>备注(参考)</strong></p></td>
</tr>
<tr class="even">
<td><p>类别B-1的维护零件 </p></td>
<td><p>应从现代机器人购买的零件</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>类别B-2的维护零件 </p></td>
<td><p>可以直接从零件制造商购买的零件</p></td>
<td></td>
</tr>
</tbody>
</table>

表6-9 类别B-1的维护零件（应从现代机器人购买的零件） 
<table>
<thead>
  <tr>
    <th>编号</th>
    <th>零件名称 </th>
    <th>类型 </th>
    <th>制造商</th>
    <th> 数量(EA)</th>
    <th>备注 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">1</td>
    <td rowspan="3">线束 </td>
    <td>CMC1</td>
    <td>现代机器人 </td>
    <td>1</td>
    <td>大型/中型/小型</td>
  </tr>
  <tr>
    <td>CMC2</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>大型/中型</td>
  </tr>
  <tr>
    <td>CEC1</td>
    <td>现代机器人</td>
    <td>1</td>
    <td>大型/中型/小型</td>
  </tr>
</tbody>
</table>

表6-10 表6 10 类别B-2的维护零件（可以直接从零件制造商购买的零件） 
<table>
<tbody>
<tr class="odd">
<td><p><strong>编号</strong></p></td>
<td><p><strong>零件名称 </strong></p></td>
<td><p><strong>类型 </strong></p></td>
<td><p><strong>制造商</strong></p></td>
<td><p><strong>数量(EA)</strong></p></td>
<td><p><strong>备注 </strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>无熔断器(NFB)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>1</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>磁性接触 (MC1,2)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>2</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>电路保护器(CP1)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>1</p></td>
<td></td>
</tr>
</tbody>
</table>

![](../_assets/6.7._보수_부품_항목-보존온도.png  )
[__SOURCE](appendices/README.md)
# 附录
[__SOURCE](appendices/rules-occupational-safety.md)
# 职业安全与健康标准的规则，以及安全检查的通知

工业机器人应根据职业安全与健康标准的规则以及安全检查的通知（如果需要检查）进行安装，考虑检查标准。

"[职业安全与健康标准的规则](https://hrbook-hrc.web.app/#/view/rules-on-occupational-safety-and-health-standards/zh/README)"
[__SOURCE](quality-assurance.md)
# 质量保证 

"[质量保证](https://hrbook-hrc.web.app/#/view/quality-assurance/zh/README)"