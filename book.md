# Hi6-N Controller Maintenance Manual

## Overview

The main purpose of this chapter is to describe the matters about the safety for the users of the industrial robot and for the workers who maintain and operate the robot.

Every worker who installs, replaces, adjusts, operate, preserves and maintains the robot system must carefully read and fully understand the operation manual and maintenance manual. Also, keep the manuals nearby so that you can view it whenever necessary.

Our company plans and implements the preservation, maintenance and operation trainings so the person using the robot should ensure that the workers working in the robot system should receive the relevant trainings. It must be ensured that only those who have completed this course can handle the robot.

The users of our industrial robots are responsible for surely understanding and complying with safety-related laws applicable in concerned countries and for properly designing, installing, and operating safety devices to protect workers working in robot systems.

The dangerous areas of the robot system, in other words, the areas where the robot, tools and peripheral devices are operating, should be equipped with safety devices according to ANSI / RIA R15.06-2012 to prevent an object, other than the workers and the workpiece, from entering the dangerous areas. The robot system should be configured in a way that it can be stopped immediately by an emergency stop device when a worker or object needs to enter the dangerous area in spite of possible danger. The workers are responsible for installing, checking and operating these safety devices.

This manual has been created based on standard specifications, so some contents may differ depending on the options and model of the product that you have purchased. In addition, the contents and specifications of this manual are subject to change without prior notice to improve the performance of the product, and Hyundai Robotics is not responsible for situations that could be caused by inaccuracies or typos in the manual. For detailed information on the revision of the manual, you need to visit our internet website (www.hyundai-robotics.com).


## Copyrights

The contents covered in this manual are protected by copyright laws and confidentiality agreements. This manual may be provided as reference material for customers who have purchased Hyundai Robotics products or may be used as internal training material. Any activities, such as use, copying, disclosure, or distribution to third parties that are not expressly permitted by Hyundai Robotics, are strictly prohibited.

Copyright ⓒ 2023 HYUNDAI ROBOTICS. All rights reserved.


## Safety Cautions

Before using the product, you must fully understand the following safety cautions for proper use, user safety, and prevention of property damage.

■ 	Danger

{% hint style="danger" %}
Imminent danger: Incompliance may cause the death of or serious injuries to the worker.
{% endhint %}


* Make sure that the safety circuit is never ignored, modified or altered in any way.
* Considering that additional problems may occur due to gravity or brake release, you must take a measure, before carrying out works, such as using a rope and crane that are to be used for transport of individual robots to prevent the brake from running down or additional accidents from taking place during the release of the brake.

■ Warning

{% hint style="warning" %}
Potential danger: Incompliance may cause injuries to the worker or damage to property, such as significant damage to the product.
{% endhint %}


* Any act of damaging the safety labels, such as relocating the name plates, warning markings, safety symbols, name markings and wire markings or painting over them or blocking them with a cover is prohibited.
* When the robot is operating, there is a risk of collision between the robot and the worker. Therefore, install a safety fence to prevent the worker from getting close to the robot.
* The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. Our company (or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not reviewing the “risk assessment”.
* Must observe the safety work procedures to prevent safety accidents. Do not change or ignore safety devices or circuits under any circumstances, and pay attention to possible electric shock. In auto mode, all normal works should be performed outside the safety guard. Before carrying out works, make sure that there are no people in the operation area of the robot.
* Sufficiently check under your feet when teaching. In particular, you must perform the teaching work outside the safety guard when teaching at a high speed (250mm/s or above).
* When it comes to changing of components or addition of optional equipment (both hardware and software) to the robot both of which may affect safety-related functions, you must check whether the functions are in normal conditions, by paying attention to the items described in “1.11 Safety Works When Operating the Robot”.
* When installing and operating an end effector, you must perform application, maintenance and operation according to ISO/TR 20218-1:2018.
* When transporting the product by using lifting equipment, you should comply with the relevant national and local safety regulations and equipment usage guidelines. When moving the product using a crane, you must make sure that that no workers are under the product. Also, never work or walk under a crane or the product.
* If a general safety guard is to be installed and used, the robot should be operated after confirming that the emergency stop operates normally. Also, check if the emergency stop input is disabled. This is an essential measure that must be taken in advance for the safety of workers.
* If an automatic safety guard is to be installed and used, the robot should be operated after confirming that the emergency stop operates normally. Also, check if the emergency stop input is disabled. This is an essential measure that must be taken in advance for the safety of workers.
* If a safety input is to be installed and used, the robot should be operated after confirming that the input function operates normally. This is an essential measure that must be taken in advance for the safety of workers.
* The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. 
Our company (or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not following the above “caution”.
* If a safety-related input is installed and enabled, you must check whether the function operates normally by referring to “1.11 Safety Measures When Operating the Robot”.
* If an emergency stop output is to be installed and used, the robot should be operated after confirming that the emergency stop output operates normally. This is an essential measure that must be taken in advance for the safety of workers.

■ Caution

{% hint style="info" %}
Low-level danger factor: Incompliance may result in minor injury to the worker or damage to property, such as damage to the product.
{% endhint %}


* Mark the installation and dangerous areas of the robot in a way that they can be clearly differentiated from other facilities and devices in terms of type, color and style.
* As the emergency stop function immediately cuts off the motor power, so reckless use of the function may result in accumulation of fatigue that affects the durability of the robot. The function must be used only in emergency situations.
* Our company is not responsible if the jogging operation does not work due to the failure of the hardware limit switch. You must check it periodically. For the measure to take in case of a failure, please refer to the troubleshooting manual.
* You should not be negligent in paying attention to sudden movements while entry is made possible. Under any circumstances, you must avoid approaching the robot without preparing for possible emergency situation.
* In the case of trial-operation, there may be a design error, teaching error, or defect in manufacturing with regard to the entire system including the teaching program, jigs, and sequencing. For this reason, you should work with elevated safety awareness in trial-operation. Multiple factors can contribute to safety accidents. Observe the following measures considering that safety is very important when trial-operating the robot.
* During maintenance and inspection of the manipulator, the robot arm may fall, or there could be a different type of danger. So, you must proceed with the work according to the instructed procedures
* When moving the axis of the robot that has no driving force applied, there is a risk of the axis dropping due to gravity and also an additional risk due to the release of the brake system. So, you must proceed with the work according to the instructed procedures.
* Before turning on the power, check that there is no worker inside the robot operation area and you are in a safe place.
* Before installing the product, you must perform a sufficient risk assessment and then set the safety functions based on the assessment results. For details on safety functions, refer to “1. Safety” section.
* When installing and repairing the product, contact the customer support team and ask an expert.
* Do not install and use the product in an area that has lots of dust or is dirty. Dust or foreign substances may cause product failure or performance problems. 
* Mark the installation and dangerous areas of the robot in a way that they can be clearly differentiated from other facilities and devices in terms of type, color and style.
* If the product is not installed in the recommended locations, the performance and service life of the product may be reduced. Install and use the product according to the recommendations.
1. Before connecting the cables, turn “off” the controller's main power switch and then lock it by using a padlock. 
2. The controller has DC400V charged energy. Be careful. Wait at least 5 minutes after turning “off” the power switch, and then wait 5 minutes at least to discharge the charged energy.
3. When handling the PCB, take precautions not to allow static electricity to damage it
4. Wiring and connection of wires must be performed by qualified personnel.
	Since the contact part of the connector for each robot may be different from the figure above, you must read the relevant robot maintenance manual carefully before connecting the wire harness.
	1. When performing the wiring work for the controller and manipulator, separate the signal line and the power line. In addition, use a separate duct for the high power line and the signal line respectively.
2. Use a protective cover for the wiring, as a measure to prevent the wiring from getting damaged when people are passing nearby.
3. Before supplying the primary power, you must check again the relationship with regard to connection, the power specification and power supply specification of the controller.
* The person in charge of maintenance should work after understanding the placement of various devices and parts and their functions inside the controller.
* The DIP switch is set to OFF mode when shipped from the factory, and the setting should not be changed arbitrarily by the user.
* The user cannot change the following items arbitrarily, and needs to refer to them only when required to reprogram through FPGA JTAG.
* The drive module differs depending on the type of the robot, so you must check the type when replacing it.
1. Do not release more than two axes at the same time.
2. Must keep a safe distance from the robot first before using the brake release unit.
3. Use the brake release unit after preparing for the dropping of the robot’s axis by using equipment such as a crane.
4. Check the safety matters while working in a group of at least 2 people.
* When using the brake release unit, follow the procedures below.
1. Turn off the AC220V power switch and check that the DC24V power switch is turned off.
2. Connect the AC power cable to the AC power connector.
3. Turn on the AC220V power switch. 
4. Turn on the DC24V power switch.
- When the use of the brake release unit is finished, follow the procedures below.
1. Turn off the DC24V power switch.
2. Turn off the AC220V power switch.
3. Disconnect the AC power cable. 
- Do not use AC220V power and DC24V battery power at the same time.
* Fieldbus communication must be available to use commercial remote IO. Therefore, you should configure the PCI communication card together by referring to the Paragraph 5.1 mentioned above.
* The drive unit differs depending on the type of the robot, so you must check the type when replacing the drive unit.
* When transporting the product, you should maintain a proper posture and work in a group of at least two workers. Otherwise, injury to parts of the body such as the back, arms and legs may result.
* If you transport the product by using lifting equipment, you should comply with relevant national and local safety regulations and equipment usage guidelines. 
* When transporting the product, you should fully understand the transport-related contents in the manual and follow the instructions. Our company will not be responsible for any damage to or breaking of the product due to the customer’s transport of the product. 
* These are important parts to be prepared for daily maintenance and inspection.
* These are maintenance parts to be prepared when multiple units are purchased.# 1. Safety

Refer to the maintenance manual of each robot for detailed specifications regarding the installation of end effectors.# 1.1. Applicable Standards

The safety standards applied to the product are as follows

* ANSI/RIA/ISO 10218-1:2011 Robots and robotic devices - Safety requirements for industrial robots - Part 1: Robots

* ANSI/RIA R15.06-2012 - Industrial Robots and Robot Systems - Safety Requirements

* ISO 10218-2:2011 Robots and robotic devices - Safety requirements for industrial robots - Part 2: Robot systems and integration

* IEC 61508-1:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 1: General requirements

* IEC 61508-2:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 2: Requirements for electrical/electronic/programmable electronic safety-related systems

* IEC 61508-3:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 3: Software requirements 
  
* IEC 61508-4:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 4: Definitions and abbreviations

* IEC 61508-5:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 5: Examples of methods for the determination of safety integrity levels

* IEC 61508-6:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 6: Guidelines on the application of IEC 61508-2 and IEC 61508-3 

* IEC 61508-7:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 7: Overview of techniques and measures 
  
* IEC 61800-5-1:2007/A1:2017 Adjustable speed electrical power drive systems - Part 5-1: Safety requirements - Electrical, thermal and energy 

* IEC 61800-5-2:2015 Adjustable speed electrical power drive systems - Part 2: General requirements - Rating specifications for low voltage adjustable speed a.c. power drive systems

* ISO 13849-1:2015 Safety of machinery - Safety-related parts of control systems - Part 1: General principles for design

* ISO 13849-2:2012 Safety of machinery - Safety-related parts of control systems - Part 2: Validation

* IEC 62061:2005/A2:2015 Safety of machinery. Functional safety of safety-related electrical, electronic and programmable electronic control systems

* IEC 61800-3:2017 Adjustable speed electrical power drive systems - Part 3: EMC requirements and specific test methods

* IEC 61000-6-7:2014 Electromagnetic compatibility (EMC) - Part 6-7: Generic standards - Immunity requirements for equipment intended to perform functions in a safety-related system (functional safety) in industrial locations

* IEC 61326-3-1:2017 Electrical equipment for measurement, control and laboratory use. EMC requirements. Part 3-1: Immunity requirements for safety-related systems and for equipment intended to perform safety-related functions (functional safety) - General industrial applications

* IEC 60204-1:2016 Safety of machinery - Electrical equipment of machines - Part 1: General requirements

* ISO 11161:2007 Safety of machinery - Integrated manufacturing systems - Basic requirements
# 1.2. Safety Performance

The performance of the industrial robot's safety modules is as follows.

Table 1-1 Safety Performance of Safety Modules
<table>
<thead>
  <tr>
    <th>Item</th>
    <th>Safety performance</th>
    <th>Applicable standards</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>HFT</td>
    <td>1</td>
    <td rowspan="2">IEC 61508/62061/61800-5-2</td>
  </tr>
  <tr>
    <td>SIL (Safety Integrity Level)</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Category</td>
    <td>3</td>
    <td rowspan="2">ISO 13849-1</td>
  </tr>
  <tr>
    <td>PL (Performance Level)</td>
    <td>d</td>
  </tr>
</tbody>
</table>
# 1.3. Safety Trainings

In order to use the functions of the product effectively, you must fully understand the contents of the manual and then install, use and maintain the product properly. The users of the product are responsible for fully understanding and complying with robot-related safety laws in the area where the robot is installed and used, and also responsible for properly designing, installing, and operating safety devices to ensure the safety of users working in the robot system.

* All the workers who install, use, and maintain the robot system must read the manual carefully and understand the contents completely. In particular, they must fully understand the safety cautions(![](../_assets/삼각형1.png)).

* Our company plans and implements the trainings for the installation, use and maintenance of the product. So, the product users and the workers must complete relevant training courses before using the product.
* The workers responsible for teaching and inspecting the robot must complete the robot use and safety trainings before using the robot. The contents covered in the safety training courses include the following items.
  * The concept of safety. and the purpose and function of the safety devices
  * Procedures for safe handling of the robot
  * Performance and potential danger of the robot and robotic system
  * Items including the works related to specific applications of the robot

# 1.4. Risk Assessment

When it comes to configuring an integrated system including a robot, risk assessment is one of the most critical factors that are handled as legal requirements in most countries. A risk assessment of an integrated system cannot be performed only on a single robot because the safety assessment for the installation of the will differ depending on how the robot is integrated into the system.

The system administrator should configure and operate the system according to the guidelines of ISO 12100 and ISO 10218-2 to conduct a risk assessment.
You should conduct the risk assessment by taking into account the entire process of an integrated system including the robot. The main objectives of the risk assessment are as follows.

* Basic settings for the use of the robot, and teaching of the robot
* Trouble diagnosis, and maintenance
* Normal operation of the installed robot

After installing the robot and configuring the s
ystem, you must conduct a risk assessment. The risk assessment mainly determines the appropriateness of safety devices in the robot integrated system, as well as the necessity for additional emergency stop devices and other safety devices. It is very important to know the appropriate safety devices and properly configure the robot integrated system. You should configure the integrated system by referring to the relevant information in the manual. For details on configuring the safety functions, refer to “1.8. Safety Functions”. In addition, when installing the robot in a specific location or configuring safety-related functions by using the safety I/O, the important items in the risk assessment of an integrated robot system are as follows.

* Severity
* Frequency of exposure to risks
* Possible occurrence
* Possible avoidance

In the process of configuring an integrated system, if the safety-related functions of the robot do not sufficiently eliminate the risk factors, it is possible to check the necessity for additional protective devices during the risk assessment.

# 1.5. Potential Risks

If the results of the risk assessment of an integrated system linked to the robot reveal that the risk factors have not been sufficiently removed only with the safety-related functions of the robot, additional protective measures must be taken.
The items to take into consideration when establishing additional protective measures is as follows.
* During installation, fingers can be pinched (caught) between the robot base and the mounting table.
* Injuries (puncture wound, penetrating injury, etc.) from sharp edges or pointed parts of obstacles or tools in the operation area.
* Injuries (bruise, falling over, fracture, etc.) due to collision with the robot
* Injuries caused (puncture wound, penetrating injury, fracture, etc.) due to obstacles around the robot
* Injuries that may occur because the fastening part is not completely fixed
* Injuries (skin damage, shortness of breath, etc.) that may occur when working with toxic and hazardous substances
* Separation of a workpiece from the tool due to sudden power failure
* A mistake caused by confusing with the emergency stop switch of other equipment
* Errors due to arbitrary change of the setting of safety-related functions.
The type of risk that may occur depends on the system configuration, so you must conduct the risk assessment before using the integrated system.
# 1.6. Effectiveness and Responsibility

It is required to observe the safety requirements according to the safety regulations and laws of the countries and regions where the robot is installed and used. Suppliers and users of the robot integrated systems have a variety of responsibilities, including the following items.
*	Risk assessment of the robot integrated system
*	Addition and removal of safety devices according to the risk assessment results
*	Check whether the integrated system is configured, installed and set up correctly.
*	Establishment of the methods and guidelines to use the integrated system, and trainings for the users
*	Management of safety devices (Prohibition of user's arbitrary change and manipulation of safety devices)
*	Provision of important information, as well as contact information, related to the use and safety of the product
*	Provision of all kinds of technical documents including manuals

The safety information in this manual does not cover all risk factors and situations that may arise while using the product.

# 1.7. Safety Labels 

Name plates, warning markings, safety symbols, etc. are attached on the inside and outside of the controller. Any act of damaging the safety labels, such as relocating the name plates, warning markings, safety symbols, name markings and wire markings or painting over them or blocking them with a cover is prohibited. Mark the installation and dangerous areas of the robot in a way that they can be differentiated from other facilities and devices in terms of type, color and style.

![](../_assets/그림_1.1_안전라벨.png)

Figure 1.1 Safety Labels

Table 1-2 Safety Labels

![](../_assets/1.7._안전_라벨(Hi6).png)

{% hint style="warning" %}
Any act of damaging the safety labels, such as relocating the name plates, warning markings, safety symbols, name markings and wire markings or painting over them or blocking them with a cover is prohibited.
{% endhint %}

{% hint style="info" %}
Mark the installation and dangerous areas of the robot in a way that they can be differentiated from other facilities and devices in terms of type, color and style.
{% endhint %}

# 1.8 Safety Functions

The safety system of the robot is designed in dual configuration (HFT=1) to satisfy the safety performance (PL) = d Cat3 of [ISO13849-1:2015] and the safety integrity level (SIL) 2 of [IEC62061:2005], and continuously monitors the status of safety related devices. When an error is detected by self-diagnosis, or a safety related signal is inputted, the safety functions will stop the robot according to the classification of stop situations determined based on the risk assessment. Also, when any of the dual switches of the safety circuit is activated, the motor drive power and brake drive power will be cut off by the sfety functions to secure a safe state. Information on the relevant status can be checked through the teaching pendant.

{% hint style="danger" %}
Make sure that the safety circuit is never ignored, modified or altered in any way.
{% endhint %}


The safety-related main functions of the robot are as follows.
# 1.8.1. Main Safety Functions

* Emergency stop (IEC 60204-1,10,7)

There is one emergency stop button on the controller and teach pendant respectively. It is possible to connect, if necessary, an additional emergency button to the safety chain circuit of the robot. The emergency stop function is to be applied with higher priority over all other control functions of the robot. The function will immediately cut off the power supply to the motors of individual axes of the robot, stopping the robot and making it impossible to use safety related funtions controlled by the robot. 



{% hint style="info" %}
As the emergency stop function immediately cuts off the motor power, so reckless use of the function may result in accumulation of fatigue that affects the durability of the robot. The functoin must be used only in emergency situations.
{% endhint %}


![](../../_assets/그림_1.2_제어기,_티칭펜던트_비상정지_스위치.png  )

Figure 1.2 Emergency Stop Buttons on the Controller and Teaching Pendant

![](../../_assets/그림_1.3_추가_비상정지_장치_연결.png  )

Figure 1.3 Connection of an Additional Emergency Stop Device

*	Protective stop (ISO 10218-1:2011)

The robot should have multiple safety inputs so that it can be used in connection with external safety devices such as safety guards, safety pads, and safety lamps. These safety inputs will make the robot stop when there is an input from the robot itself and peripheral facilities, securing a safe state. For details on the connection to the safety inputs, refer to “4.3.2. Safety Module (BD632)”.

*   Speed limit (EN ISO 10218-1:2011)

In manual operation mode, the speed of the robot is limited to a maximum of 250 mm / s. The speed limit applies not only to the TCP (Tool Center Point) but also to all other parts of the robot that are to be operated in manual mode. It should be also made possible to monitor the speed of the equipment mounted on the robot.

*  Operaiton area limit (ANSI/RIA R15.06-2012)

When applying a robot, in order to secure a sufficient safety area, the operation range of the robot can be limited by using a hardware limit or a stopper. This function can minimize the damage if the robot collides with an external safety device such as a safety guard. Axis 1, 2, and 3 are mainly limited by a stopper or hardware limit. If the operation range is changed due to a mechanical stopper or hardware limit, the operation range limit parameter should be also changed in software as well. Please refer to the operation manual about the change. The operation area limit of each axis can be changed by the user, and at the time of shipment, it is set to the maximum operation range of the robot. The safety system of the Hi6 controller can support up to 4 hardware limit switches as an option. Refer to “4.3.2. Please refer to “Safety Module (BD632)” for the matters related to the connection.

*  Operaiton mode selection (ANSI/RIA R15.06-2012)

You can operate the robot in manual, automatic or remote mode. The maximum speed in manual mode is limited to 250 mm/s, and you can perform operation only with the teaching pendant. In addition, it is possible to mount a mode switch additionally on the control panel by configuring it as an option. For details on the operation, please refer to the operation manual.

# 1.8.2. Other Related Functions

Required to fully understand the following items and take actions if a person is pinched due to an accident caused by the arm of the robot.

* Release of the manual brake 

{% hint style="danger" %}
Considering that additional problems may occur due to gravity or brake release, you must take a measure, before carrying out works, such as using a rope and crane that are to used for transporation of individual robots to prevent the brake from running down or additional accidents from taking place during the release of the brake.
{% endhint %}


    - After removing power from the controller, connect the brake release unit to the designated connector of the robot or the internal board connector of the controller and then release the manual brake for each axis as needed.

    - Refer to the maintenance manual of each robot for the information on individual axes of each robot, and for the designated transport equipment (eg, rope, crane) for each robot.

When the robot is stopped by the limit switch, it is possible to change the position by jogging the robot with the teaching pendant in the constant setting mode. After designating the soft limit according to the site situation, make sure that it is installed by a trained worker.

{% hint style="info" %}
Our company is not responsible if the jogging operation does not work due to the failure of the hardware limit switch. 
You must check it periodically. For the measure to take in case of a failure, please refer to the troubleshooting manual.
{% endhint %}

# 1.9. Stop

The safety system of Hi6 controller can handle the stop operation as shown below. Safety inputs can be classified as follows according to the stop classification criteria specified in IEC 60204-1.

*  Stop classification Stopping (uncontrolled stoping) occurs as the power to the machine actuator is immediately removed.

    →  Emergency stop button

*  Stop classification 1: Controlled stop in which the machine actuator still has a power that can be used to achieve the stopping. The power will be removd when the stopping is achieved. 

    →  Safety inputs except for the emergency stop button
# 1.10. Safety Measures When Installing
# 1.10.1. Installing the Safety Guard

{% hint style="warning" %}
When the robot is operating, there is a risk of collision between the robot and the worker. Therefore, install a safety fence to prevent a worker from getting close to the robot.
{% endhint %}

When the robot is operating, there is a risk of collision between the robot and the worker. Therefore, install a safety fence to prevent a worker from getting close to the robot according to ISO 13855:2010. Configure the system to ensure that the robot stops when a worker opens the door of the safety fence and approaches the facility, during the robot operation, for any reason, such as inspecting the robot or a welding fixure, performing tip dressing or tip changing, etc.

![](../../_assets/그림_1.4_안전펜스_연결.png  )

Figure 1.4 Connection of the Safety Fence<br/><br/>

Source : ISO 13855:2010 Safety of machinery — Positioning of safeguards with respect to the approach speeds of parts of the human body

![](../../_assets/표_1-3_안전펜스_설치_규격.png  )

Source : ISO 13855:2010 Safety of machinery - Positioning of safeguards with respect to the approach speeds of parts of the human body

*   The safety fence should cover the operation area of the robot, and should secure enough space so that there is no interference when the worker carries out works, such as teaching, maintenance, etc. The safety fence should be made solid to prevent it frome being moved easily and should be structured in a way not to allow people to enter inside the fence by going over the safety fence.

*	In principle, it is required to install and use a fixed type safety fence that does not have dangerous parts such as uneven or sharp parts.

*	An entrance door should be installed to allow people to enter inside the safety fence, and a safety plug must be installed on the door in a way that the door should not open unless the plug is removed. In addition, wiring should be configured in a way that allows the motor to be turned off and the brake to be in hold state when the safety plug is removed or the sfety fence is opened.

*	If you want to operate the robot even when the safety plug is removed, wiring should be configured in a way that allows the robot to play back at low speed.

*	Install the emergency stop button of the robot at a location where the operator can quickly press it.

*	If a safety fence is not to be installed, safety devices such as photoelectric switches and mat switches should be installed covering the entire area that falls within the specification of the safety guard range of the robot, as substitute devices for the safety fence, making it possile for the robot to stop automatically when a person enters inside the safety fence. 

*	Make sure that the robot's operation area (danger area) can be identified in some way, such as painting the floor.

# 1.10.2. Placement of the Robot and Peripheral Devices 

{% hint style="warning" %}
The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. Our company (or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not reviewing the “risk assessment”.
{% endhint %}

Installation of the product should be performed by a qualified installer according to relevant national and local regulations and laws.

*	When unpacking the product, check it for damage that may occur while transporting or unpacka it.

*	Before installing the product after unpacking it, you must check the safety regulations, instructions, information related to the product installation and use environments, and fully undertand the installation methods.

*	When connecting the primary power of the controller or peripheral device, peroform the connection after checking first whether the supply side power is turned off. Since high voltage is used as the primary power source, there is a risk of electric shock.

*	Put up a sign “No entry during operation” at the entrance of the safety fence, and inform the workers of the intents.

*	Place the controller, interlock panels, and other control panels in a way that they can be operated from outside the safety fence.

*	When installing the operation stand, attach an emergency stop button to it also. Wherever you operate the robot, you should be able to stop the robot in an emergency situation.

*	Do not allow the wiring or piping of the manipulator, controller, interlock panel, timer, etc. to get caught on by the workers' feet or to get stepped on directly by the forklift. Otherwise, there is a risk of accidents of the worker getting electric shock or the wires getting disconnected. 

*	Place the controller, interlock panel, and operation stand at a place where the operation of the manipulator can be seen sufficiently. If the robot is operating abnormally in an area from which the robot operation cannot be seen, or the worker is working on something in the area, there is a risk of major accidents taking place during operation.

*	If the required robot operation area is narrower than the allowable robot operation area, you should limit the robot operation area. It can be limited by soft limit, hardware limit, mechanical stopper, etc. Even when the robot operates off the normal operation area due to abnormal operation such as mistakes in the operation of the robot, the robot will be stopped in advance by the operation area limit function. 

*	During welding, spatter may fall on or fall near the worker and cause a burn or fire. Install a light shield plate, cover, etc. in the range where the movement of the manipulator can be seen sufficiently.

*	When it comes to a device that shows the auto and manual operation modes of the robot, an easily visible device should be installed to ensure that the status can be recognized from a distance. In case of starting the operation in auto mode, a buzzer or an alarm will be useful.

*	Make sure there is no protruding part on the peripheral devices of the robot. If necessary, place a cover on them. Otherwise, in general, an accident could occur when the worker comes into contact with a protruding part, and a major accident could occur when a worker surprised over a sudden movement of the robot could fall over. 

*	Do not design a system that requires the worker to put in hands inside the safety fence to carry in and carry out a workpiece.


![](../../_assets/그림_1.5_LCD핸들링_로봇의_빔형_안전펜스.png  )

Figure 1.5 Beam Type Safety Fence for the LCD Handling Robot

Placement of the Peripheral Devices and Workers for the Industrial Robot

![](../../_assets/그림_1.6_산업용_로봇의_원통형_안전펜스.png  )

Figure 1.6 Cylinder Type Safety Fence for the Industrial Robot
# 1.10.3. Installation of the Robot

{% hint style="warning" %}
The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. Our company (or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not reviewing the “risk assessment”.
{% endhint %}

Installation of the product should be performed by a qualified installer according to relevant national and local regulations and laws.
*	When unpacking the pruduct, check it for damage that may occur while transporting or unpacking it.

*	Before installing the product after unpacking it, you must check the safety regulations, instructions, information related to the product installation and use environments, and fully undertand the installation methods.
*	The worker who uses the robot should fully understand the contents described in the application and auxiliary manuals, and operate and handle the industrial robot skillfully.
*	The worker who installs the robot should be able to apply the safety instructions during the installation if there is a problem.
*	The system supplier should guarantee that all circuits used for safety functions perform their functions surely.
*	The main power supply to the robot should be installed in a way that it can be cut off from outside the robot operation area.
*	The system supplier should surely guarantee that all circuits used for safety functions perform their functions safely.
*	The emergency stop button should be located at a place where the worker can easily approach it when required to stop the robot urgently. 
*	By taking into consideration the dimensions of the manipulator and the operation range, make sure that that there is no interference with peripheral devices.
*	Avoid installing the robot in a place that is exposed to direct sunlight, has high level of humidity, has oil or chemicals around and has lots of metal powder or explosive gas in the air.
*	Install the robot in an area where the ambient temperature is 0 - 45 ℃.
*	Secure enough space for disassembling and inspecting the robot easily.
*	Install a safety fence and prevent people from entering the robot operation range.
*	Make sure there is no obstacle in the robot operation area.
*	When installing the robot in an area exposed to direct sunlight or near a heating element, you should take measures in consideration of the thermodynamic state of the controller.
*	Take additional measures when installing the robot in an area that has lots of dust such as metal powder in the air.
*	Carry out installation in a way that welding current never flows to the robot. In other words, there should be insulation between the spot gun and the wrist of the robot. 
*	Since grounding is important for preventing a malfunction due to noise and an electric shock, you should install the robot as shown below.

     - Install the dedicated grounding terminal while setting it as Type 3 Grounding higher.
     - Connect the grounding wire to the grounding bus bar inside the control panel.
     - When the manipulator is installed, if it is directly grounded to the floor by an anchor, etc., the controller side and the manipulator side will make a two-point grounding, forming a closed circuit, which conversely may cause malfunctioning due to some reasons such as noise. In this case, connect the grounding wire to the base part of the manipulator, but not to the controller side. In addition, if there is shaking when the robot stops, there is a high possibility that the grounding is incomplete or there is a closed circuit. It is required to check the grounding again.
     - If you use a gun with an embedded transformer, there is a risk of dropping because the primary power cable is connected directly to the spot gun. In this case, in order to protect the control panel and prevent electric shock, connect the grounding wire directly to the base part of the manipulator and do not connect it to the controller.<br/><br/>

* Carry out the installation by referring to the robot maintenance manual for each robot.
* After designating the soft limit suitable for the site situation, the positionining and adjustment of the hardware limit must be performed by a trained worker. After installation, you must check whether the functions are working well.
# 1.11. Safety Works When Operating the Robot


{% hint style="warning" %}
Must observe safety work procedures to prevent safety accidents. Do not change or ignore safety devices or circuits under any circumstances, and pay attention to possible electric shock. 
In auto mode, all normal works should be performed outside the safety guard. Before carrying out works, you must make sure that there are no people in the operation area of the robot.
{% endhint %}

# 1.11.1. Safety Measures When Operting the Robot 

Observe the following measures considering that safety is very important when operating the robot.
*	The worker who operates or may operate the robot, and the supervisor should take certain trainings. Except for those who are recognized to be fully aware of the safety and functions of the robot and designated accordingly, any unqualified person should not operate the robot.

*	Before operating the robot, you must check whether the product has been installed by a qualified installer in compliance with the relevant national and regional regulations and laws.

*	Before operating the robot, check whether the safety functions are working normally.

*	Must wear a safety helmet, protective glasses and safety shoes. 

*	Two people must work together. One person should be teaching and the other should be monitoring from the operation panel. One of the two should be ready to press the emergency stop switch at any time, and the other should perform the work quickly with sufficient care in the operation area. In addition, check the evacuation route before starting the work. 

*	Supply the power after confirming that there is no worker within the safety guard.

*	Works such as teaching should be performed outside the robot safety guard in principle. However, when required to stop the system and work within the operation range, the worker should bring in the mode switch key (or a switch to change to the auto mode), or the safety plug when going inside. Such action is necessary to make sure that no other worker accidentally changes the robot to the auto operation mode. Also, pay special attention to the direction of the operation of the robot just in preparation for the robot malfunctioning or operating in wrong conditions.

※   The supervisor should observe the followings.
            
    - The supervisor should be positioned at a location where she or he can see the robot entirely and should be dedicated to the duties of supervision.
    - If there is any problem, press the emergency stop button immediately.
    - Other people except for the persons involved in the work should not be allowed to stay within the operation range.

* In manual operation mode, the speed should be limited to a maximum of 250 mm/sec. At this time, you should progress the work while being prepared, together with the worker outide the guard, to press the emergency stop switch at any time if a problem occurs.

*	When operating the robot manually in high-speed mode, you should progress the operation from outside the safety guard.

*	When performing a teaching work, you shoud put up a sign [Teaching in progress]. 

*	When required to enter inside the safety guard, the worker should pull out the safety plug or an equivalent, and then bring it in when going inside.

*	Do not use equipment that could be a source of noise near the teaching place or its surroundings.

*	Do not operate the robot operation buttons on the teach pendant just by using the feeling at the hands while watching the teaching points. Instead, operate the buttons while checking with bare eyes.

{% hint style="warning" %}
Sufficiently check under your feet when teaching. In particular, you must perform the teaching work outside the safety guard when teaching at a high spped (250mm/s or above).
{% endhint %}


* 	Take the following measures when abnormality occurs.
이
     - 	If abnormal operation is found, immediately press the emergency stop button.

     - 	If abnormality is to be checked following an emergency stop, the stop status of the concerned facility must be checked.

     - 	If the robot stops automatically due to abnormality with the power. Check first that the robot is stopped completely, and then investigate the cause and take measures.

     - 	If the emergency stop device does not perform functions properly, immediately shut off the main power, and then investigate the cause and take measures.

     - 	The investigation of the cause of the abnormality should not be performed by any other than the designated person. After the emergency stop, you should restart the system after surely identifying the cause of the abnormality and taking measure accordingly.

* 	Prepare proper work regulations, considering the installation location and work details, with regard to the robot operation and manipulation methods, and actions to take when abnormality occurs. In addition, work should be carried out according to the work regulations.
*	Precautions to take when the robot is stopped

    * Must avoid approaching the robot recklessly while thinking that the robot is stopped. When you approach the robot because you think it is stopped, the robot may suddenly move, causing an accident in many cases. The robot will be in the stopped state in the following cases.<br/><br/>


Table 1-4 Status of the robot when it stop mode
<table>
<tbody>
<tr class="odd">
<td></td>
<td><p>State of the robot</p></td>
<td><p>Source of driving</p></td>
<td><p>Entry</p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>In temporary stop mode</p>
<p>(Minor abnormality, temporary stop switch)</p></td>
<td><p>ON</p></td>
<td><p>X</p></td>
</tr>
<tr class="odd">
<td><p>2</p></td>
<td><p>In emergency stop mode</p>
<p>(Major abnormality, emergency stop switch and safety door)</p></td>
<td><p>OFF</p></td>
<td><p>O</p></td>
</tr>
<tr class="even">
<td><p>3</p></td>
<td><p>Waiting for input signal from peripheral devices</p>
<p>(START INTERLOCK)</p></td>
<td><p>ON</p></td>
<td><p>X</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>Playback being completed</p></td>
<td><p>ON</p></td>
<td><p>X</p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>Waiting in progress</p></td>
<td><p>ON</p></td>
<td><p>X</p></td>
</tr>
</tbody>
</table>

{% hint style="info" %}
You should not be negligent in paying attention to sudden movements even when entry is made possible. Must avoid approaching without preparing for possible emergency situation under any circumstances.
{% endhint %}

  
    - If the entrance door needs to be opened to take measures for minor abnormalities (such as nozzle contact, deposition detection and arc abnormality) during a temporary stop, the same measures as taken for opening the door for the teaching should be taken.

* After completing the robot operation, clean the inside of the safety fence to make sure that no tools, oil or foreign substances remain. If the operation area is stained with oil, or if tools are left in the operation area, it could cause an accident such as falling over. Make sure that arranging and organizing are performed always.
# 1.11.2. Safety Measures When Trial-Operating the Robot

{% hint style="info" %}
In the case of trial-operation, there may be a design error, a teaching error, or a defect in manufacturing with regard to the entire system including the teaching program, jigs, and sequencing. For this reason, you should work with elevated safety awareness in trial-operation. Multiple factors can contribute to safety accidents. Observe the following measures considering that safety is very important when trial-operating the robot.
{% endhint %}

* 	Before operating the robot, check the functions of buttons such as the emergency stop button and the stop button as well as the functions of relevant signals. After that, check the operation related to detection of abnormality. First of all, it is important to check all the signals that stop the robot. When an accident is expected, the most important thing is to stop the robot.

*	When performing trial opreation of the robot, first set it to manual mode, input a job program with which you can test all axes, and then check the operation by repeating more than 1 cycle for each step While the robot is moving, open the safety guard or remove the enabling switch (enabling swith on the teaching pendant) to see whether the robot stop. If a problem is found, press the emergency stop button to check whether the robot stops. If the emergency stop device does not perform its function well, immediately shut off the main power. After that, you should call the responsible aftersales person. If there is no problem, increase the speed in sequence (50% → 75% → 100%), and check the operation by repeating more than 1 cycle each. Operating at high speed from the beginning may lead to a major accident.

*	It is not possible to predict what kind of problem will occur during trial-operation. Never enter inside the safety fence during trial-operation. As the reliability is low, it is very likely that unexpected accidents could occur

# 1.11.3. Safety Measures for Auto Operation

Observe the following measures considering that safety is very important when operating the robot in auto mode.

* 	Put up a sign [No entry during operation] on the safety fence entrance and ask the worker to refrain from entering during operation. If the robot is stopped, you may enter inside the safety fence after judging the situation. 

*	When starting the auto operation, you must check whether there is a worker inside the safety fence. If you work without checking whether there is a worker inside, it may cause an accident involving people. 

*	When starting the auto operation, check first that that the program number, step number, mode, start selection, etc. are in proper state for auto operation. If you start the robot while an irrelevant program or step is selected, the robot may behave unexpectedly causing an accident. 

*	When starting the auto operation, check in advance that the robot is in the position where the robot can start the auto operation. Check also whether the program number or step number matches with the robot position. Even when the program or step is correct, if the robot is in a different position, an accident may occur due to an operation different from a normal operation 

*	Be prepared to press the emergency stop button immediately at the start of auto operation. If an unexpected robot operation or unexpecred situation occurs, immediately press the emergency stop button. 

*	Check the operation path, operation status, and operation sound, etc. of the robot to judge whether there is any abnormal state. The robot may suddenly cause an abnormality such as a failure, but it may give some symptoms before the failure occurs. In order to predict this in advance, it is required to well understand the normal operation status of the robot. 

*	If any abnormality is found, immediately make an emergency stop and take proper measure for it. Using the robot without proper measures could lead to a severe failure that may lead to production interruption and significant accidents involving people. 

*	While completing measures and checking the operation after an abnormality occurred, do not operate the robot while the worker is still inside the safety fence. Unexpected accidents such as other abnormalities may occur as the reliability is low. 

*	Before selecting the auto mode, if there is a safety device function that has been stopped, you should progress works after recovering the function back to completely normal state.
# 1.12. Safety Measures When Entering Inside the Safety Fence

When required to enter the safety door in the robot operation area, a worker and a super visor who have received certain trainings should perform works in a group of two. Also, they must wear a safety helmet, protective glasses and safety shoes. The supervisor should be prepared to press the emergency stop switch at any time, and the worker must bring in the teach pendant when going inside, making impossible for other people to operate the robot. Must put up a sign on the control panel to indicate that the robot is being operated.

When you enter the robot operation area, you must full understand the following items. 

*	No one except for the teaching person should enter the robot operation area.
*	The operation setting mode of the controller should be manual mode on the control panel.
*	Always wear certified work clothes.
*	Do not wear gloves when operating the controller.
*	Don't let underwear, shirt, tie etc. come out of the work clothes.
*	Do not wear large jewelry such as earrings, rings or necklaces.
*	Must wear safety shoes, safety helmet and protective glasses, and, when necessary, should wear safety gear such as safety gloves.
*	Before operating the robot, check if the emergency stop circuit is functioning well to turn off the motor when the emergency stop button on the control panel or the teach pendant is pressed
*	Work in a position facing the manipulator.
*	Follow predetermined work procedures.
*	Thinking that the robot may rush towards you unexpectedly, you should prepare a method or place for evacuation. 


{% hint style="info" %}
You should not be negligent in paying attention to sudden movements even when entry is made possible. Must avoid approaching without preparing for possible emergency situation under any circumstances.
{% endhint %}

# 1.13. Safety Measures When Maintaining and Inspecting# 1.13.1. Safety Measures When Maintaining and Inspecting the Controller

Observe the following safety measures when maintaining and inspecting the robot controller.

* 	Maintenance and inspection works should be performed only by those who have received special maintenance trainings and fully understand the related contents.

*	Progress the work according to the controller maintenance and inspection procedures.

*	For the maintenance and inspection works, you must check the surroundings for safety and secure a passage or a place to avoid danger before progressing the work safely.

*	Must turn off the power before performing daily inspection or maintenance of the robot or replacement of parts. In addition, in order to prevent other workers from inadvertently turning on the power, put a warning marking such as [Power-On Prohibited] on the primary power supply. 

*	Always use the designated replacement parts. 

*	When required to open the controller door, you must turn off the power first and then wait for about 3 minutes before starting the work.

*	Use external lighting when sufficient illumination is not secured when performing maintenance and inspection works inside the controller.

*	Do not touch the heat sink and regenerative resistor of the servo amplifier because they generate excessive heat. After maintenance, check whether tools, foreign substances, etc. are left behind inside the controller, and then close the door securely.
# 1.13.2. Safety Measures When Maintaining and Inspecting the Robot System and Manipulator

Observe the following safety measures when maintaining and inspecting the robot system and manipulator.

* 	Refer to safety measures for the maintenance and inspection of the controller.

*	When maintaining and inspecting the robot system and manipulator, proceed with the work according to the instructed procedures.

*	Must cut off the main power of the controller. In order to prevent other workers from powering it up again, put a warning marking such as [Power-On Prohibited] on the primary power supply.
 

{% hint style="info" %}
During maintenance and inspection of the manipulator, the robot arm may fall, or there could be a different type of danger. So, you must proceed with the work according to the instructed procedures. 
{% endhint %}


{% hint style="info" %}
When moving the axis of the robot without driving force applied, there is a risk of the axis dropping due to gravity and also an additional risk due to the release of the brake system. So, you must proceed with the work according to the instructed procedures.
{% endhint %}
# 1.13.3. Actions to Take after Maintenance and Inspection

Observe the following actions after maintenance and inspection.

*	Check if the wires or parts inside the controller are connected normally.

*	After maintenance, check whether any tool is left behind inside and around the controller, manipulator or the robot system, and keep them surely arranged and organized. Must close every door.

*	If any problem or fatal defect is found, do not turn on the power of the robot.

*	Turn on the main breaker in the control panel.

*	Check the current position and status of the robot. 

*	Operate the robot at a low speed.


{% hint style="info" %}
Before turning on the power, check that there is no worker inside the robot operation area and you are in a safe place
{% endhint %}

{% hint style="warning" %}
When it comes to the change of components or additoin of optional equipment (both hardware and software) to the robot both of which may affect safety-related functions, you must check whether the functions are in normal conditions, by paying attention to the items described in “1.11 Safety Works When Operating the Robot”. 
{% endhint %}

# 1.14. Safety Related to End Effctors

{% hint style="warning" %}
When installing and operating end effectors, you must comply with ISO 10218-1:2018 in applying, maintaining and operating them.
{% endhint %}


Refer to the maintenance manual of each robot for detailed specifications regarding the installation of end effectors.# 1.14.1. Gripper

* 	When a gripper is used to hold a workpiece, there should be a measure to take against abrupt dropping of the workpiece.

*	When installing the device onto an end effector or arm, you should use the bolts of specified sizes and the specified number of bolts, and tighten them completely according to regulated torques by using torque wrenches. You should use bolts that are not rusted or stained.

*	When manufacturing an end effector, you should take into account that it can be used within the allowable load value of the wrist of the robot. An end effector should hava a structure that will not allow a gripped material to be released or dropped even when the power supply or air supply is interrupted, and the corners and protrusions should be surely treated in order to prevent people or objects from suffering any damage.

# 1.14.2. Tools/Workpieces

* 	It should be possible to safely change tools such as a milling cutter. Until the cutter stops rotating, the safety devices should surely perform proper functions.

*	The tool should be designed in a way that the workpiece will not have any abnormality even when a sudden power failure or control failure occurs. In manual operation, it should be possible to separate the workpiece.

# 1.14.3. Pneumatic / Hydraulic Systems

* 	Special safety laws will be applied to the pneumatic and hydraulic systems. 

*	In this type of systems, as residual energy may remain even after the system is shut down, you should pay attention in particular. Before repairing the pneumatic or hydraulic systems, you must remove the pressure inside the devices.
# 2. Details of Specifications
# 2.1. Details of Specifications of Each Controller Model

Table 2‑1 Details of Specifications of Each Controller Model

<table>
<thead>
  <tr>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>Model&nbsp;&nbsp;&nbsp;</th>
    <th><br>Hi6-N00-A0<br>Hi6-N30-A0<br>Hi6-N80-A0</th>
    <th><br>Hi6-N00U-A0<br>Hi6-N30U-A0<br>Hi6-N80U-A0</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>CPU&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>2.7GHz Dual core&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Program execution method&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Teaching &amp; playback&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Opertion method&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Menu-based&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Interpolation type&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>PTP, linear and circular&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Memory backup method&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Battery backup IC memory&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Encoder type&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Absolute encoder&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Servo drive unit&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>6 axes integrated, digital servo&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Maximum number of units&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Maximum 32 axes simultaneously&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Step&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>10,000,000 steps&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Program selection&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>255 (binary)/8 (discret)&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Display on the teach pendant&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>7-inch colorful TFT-LCD (800x480)&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Fieldbus interface&nbsp;&nbsp;&nbsp;(optional)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>DeviceNet,&nbsp;&nbsp;&nbsp;ProfiNET, Modbus TCP/UDP, EtherCAT &nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Digital I/O<br>&nbsp;&nbsp;&nbsp;(optional)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Input: 8 points (maximum 496 points) / Output: 8 points (maximum 496 points)&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Analogue I/O<br>&nbsp;&nbsp;&nbsp;(optional)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Input: 4 points / Output: 4 points&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Conveyor pulse counter&nbsp;&nbsp;&nbsp;(optional)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Line driver / Open collector&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Communication interface&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>3Ethernet port/ 2 USB 2.0 ports/ 2 RS232 ports&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td rowspan="4">&nbsp;&nbsp;&nbsp;<br>Circuit board&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Main module&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H6COM-T&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Servo board&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>BD640&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Safety module&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>BD632&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Power supply module&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H6PSM(BD6C2)&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td rowspan="2">&nbsp;&nbsp;&nbsp;<br>Drive&nbsp;&nbsp;&nbsp;module&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>For medium-sized 6 axes</td>
    <td colspan="2"><br>N00(U)-A0 : H6D6X<br>N80(U)-A0 : H6D6X<br>N30(U)-A0 : H6D6A</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>For one additional axis&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>H6D1X, H6D1Z&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Wire harness&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>CMC1, CMC2, CEC1&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Teach pendant&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>TP630&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Rated supply voltage&nbsp;&nbsp;&nbsp;</td>
    <td><br>3-phase 220V(50/60 Hz)±10%±10%<br>Option: 3-phase 380V, 400V, 415V and 440V</td>
    <td><br>3-phase 220V(50/60 Hz)±10%<br>Option: 3-phase 460V and 480V</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Maximum power consumption&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2"><br>Hi6-N80(U)-A0:10.5KVA<br>Hi6-N00(U)-A0: 7.8KVA<br>Hi6-N30(U)-A0: 4.4KVA&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Operation temperature&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>0 ~ 45 ℃&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Operation humidity&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>75%&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Protection grade&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>IP54&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Noise level&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Maximum 68 dB&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Exterior diemsion*1 (WxHxD)<br>&nbsp;&nbsp;&nbsp;(WxHxD)&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>W650xD560xH580 (mm)<br>Caster 100mm Exclude&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Weight&nbsp;&nbsp;&nbsp;</td>
    <td colspan="2">&nbsp;&nbsp;&nbsp;<br>Standard Voltage Specification(Exclude TR)<br>Hi6-N30(U): 120kg<br>Hi6-N00(U): 120kg<br>Hi6-N80(U): 125kg<br><br>Optional Voltage Specification(Include TR)<br>Hi6-N30(U): 165kg<br>Hi6-N00(U): 185kg<br>Hi6-N80(U): 195kg</td>
  </tr>
</tbody>
</table>

<br>

Table 2‑2 Power Requirements
<table>
<thead>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>Controller type&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Capacity *1) [KVA]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Input voltage *2) [V]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Frequency[Hz]&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>Peak current [A]&nbsp;&nbsp;&nbsp;</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N30&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 4.4 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>15 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N00&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 7.8 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>30 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N80&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 10.5 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>220/380/400/415/440V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N30U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 4.4 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>15 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N00U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 7.8 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>30 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
  <tr>
    <td>&nbsp;&nbsp;&nbsp;<br>Hi6-N80U&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>Max. 10.5 KVA&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>460/480V&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50/60&nbsp;&nbsp;&nbsp;</td>
    <td>&nbsp;&nbsp;&nbsp;<br>50 A&nbsp;&nbsp;&nbsp;</td>
  </tr>
</tbody>
</table>


Note 1) Power capacity: Refers to the power supply capacity of the controller. For the power capacity of each robot, refer to the manipulator maintenance manual.

Note 2) Voltage range: ±10% (at the power terminal of the controller)
# 2.2. Exterior of the Controller

![](../_assets/2.2._제어기_외관(Hi6).png )

Figure 2.1 Front Exterior of the Controller

# 3. Installation of the Controller

If you properly install, transport, and store the product in consideration of the position and direction of the installation and the size of the surrounding space, you can secure the service life of the product and prevent the degradation of its performance.

*	Checking of the installation and use environments

*	Transport of the controller

*	Storage of the controller

*	Discarding of the controller


{% hint style="info" %}
Before installing the product, you must perform a risk assessment sufficiently and then set the safety function based on the assement results. For details on safety functions, refer to “1. Safety”.
{% endhint %}

# 3.1. Configuration
# 3.1.1. Basic Configuration

![](../../_assets/그림_3.1_산업용_로봇_설치의_기본_구성.png)

Figure 3.1 Basic Installation Configuration of the Industrial Robot

* 	Hi6 controller

*	Teaching pendant

*	Wire harness (Hi6 controller ↔ robot)

*	Robot

# 3.1.2. Checking of Various Name Plates

![](../../_assets/그림_1.1_안전라벨.png  )

Figure 3.2 Controller’s Labels <br/><br/>

Table 3-1 Label Type

![](../../_assets/표3-1_라벨_종류-1.png  )

![](../../_assets/표3-1_라벨_종류-2.png  )

![](../../_assets/표3-1_라벨_종류-3.png  )


{% hint style="warning" %}
Any act of damaging the safety labels, such as relocating the name plates, warning markings, safety symbols, name markings and wire markings or painting over them or blocking them with a cover is prohibited. 
{% endhint %}


{% hint style="info" %}
Mark the installation and dangerous areas of the robot in a way that they can be differentiated from other facilities and devices in terms of type, color and style.
{% endhint %}
# 3.2. Installation and Use Environmets 

Install the product in an appropriate place in consideration of the installation and use environments and conditions.

*	The proper use temperature of the product is 0℃ - 45℃, and the proper storage humidity is 20 to 85%RH.

*	Do not drop the product or apply a strong impact to it while moving or using it.

*	Transport and install the product in a correct way based on the weight of the product while paying attention to the safety.

*	Install and use the product in a solid, flat and vibration-free area where the product will not turn over easily.

*	Do not install and use the product in an area with a lot of foreign substances such as water, moisture, gas, dust, or in a dirty place.

*	Do not install or use the product in an area with flammable and corrosive substances or gases, or in an area wherer heat is generated, or near heat of fire.

*	Do not install or use the product in an area that has a source of strong electrical noise or is affected by it.

*	Install the controller in a safe area by referring to “1.10 Safety Measures When Installing”.

*	Carry out the controller maintenance work by referring to “1.13. Safety Measures When Maintaining and Inspecting”.

*	When installing the product in an area where welding work is performed, install the product in a location where there will be no effect from welding spatter and cooling water.

*	When installing the controller, keep a distance of at least 500mm if there is a wall or obstacle nearby.

*	For the matters related to the installation of the robot, refer to each robot maintenance manual.


{% hint style="info" %}
If the product is not installed in the recommended locations, the performance and service life of the product may be reduced. Install and use the product according to the recommendations.
{% endhint %}

{% hint style="warning" %}
The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. 
Our company (or the manufacturer) will not be responsible for any accidents that occur due to not complying with the relevant requirements of international standards and national laws or due to not reviewing the “risk assessment”.
{% endhint %}

# 3.3. Transport of the Controller

The following items describle the precautions to take in packing, transporting, and unpacking the Hi6 controller. Rrefer to the robot maintenance manual for the matters related to the packing and transport of the robot.# 3.3.1. Packing

* 	Attach the model name plate to the box.

*	Protect all exposed connectors with a dust cap or polyvinyl.

*	When the teach pendant is packaged in a box, use an air-filled cushioning to prevent the LCD from getting damaged due to external impact.

*	Attach the waterproofed packing list to the outside of the box.

# 3.3.2. Transport (Modifying the Weight)

* 	Check whether the front door of the controller is completely locked.

*	Remove anything that is not fixed onto the controller.

*	Check if the eye bolts on the controller are surely fastened.

*	As the controller is a precision device, pay attention to the transport of it to prevent any strong impact from being applied to it.

*	The weight of the controller is maximum 200kg. When using a crane, take precautions to prevent an object on the controller from being damaged by the wire. 

※ For the weight of the controller, refer to “2. Details of Specifications’.

*	 When using a forklift, fix the controller in a way to prevent the controller from shaking.

*	When moving the product by vehicle, fix the manipulator and controller by using squids.

*	When transporting the product, fully understand the contents related to the packing and transport, and follow the instructions. Our company will not be responsible for any damage to or breaking of the product due to customer’s carelessness, inexperience in operation, or negligence.

*	Check the following items when transporting the controller by using a crane.


    - 	In general, the controller should be transported by using crane wires for which eye bolts are used.
    -	Check whether the wires have sufficient strength to withstand the weight of the controller.
    -	Check whether the eye bolts are fastened tightly.


![](../../_assets/그림_3.3_제어기_와이어_연결_위치.png  )

Figure 3.3 Controller Wire Connection Position

*	Check the following items when transporting the controller by using a forklift,
    -	When transporting the product by using wire ropes, use a wire that can withstand the weight of the controller.
    -	Check whether the eyebolts are firmly fixed.
    -	Transport the controller while keeping it as low as possible.<br/><br/>


![](../../_assets/그림_3.4_지게차를_이용한_제어기_운반.png  )

Figure 3.4 Transport of the Controller by Using a Forklift


{% hint style="warning" %}
If you transport the product by uisng lifting equpment, you should comply with the relevant national and local safety regulations and equipment usage guidelines. When moving the product by using a crane, you must make sure that that no workers are under the product. Also, never work or walk under the crane or the product.
{% endhint %}


# 3.3.3. Unpacking 

* 	Fully understand the safety regulations and other guidelines carefully before unpacking and installing the robot.

*	Unpack the product according to the unpacking instructions.

*	Check whether the location is an area where the robot and controller can be safely installed.

*	Check if a path that allows the robot and controller to move safely is secured.

*	Transport of the robot should be performed by a qualified person.

*	When unpacking the product, check that whether there is any damage that might have occurred during transport or unpcking.

# 3.4. Storage of the Controller

When storing the controller, instead of installing it, refer to the following items.
*	Store the controller while keeping it in the packaged state and seal the power and communication connection parts tightly.

*	When storing the controller for a long time, you must take safety measures against the risk of it falling over.

*	When storing the controller wrapped in packing material, pack it with a desiccant or store it in a dry place. If it is stored in a highly humid place, moisture may form inside the packing material, damaging the product.

*	Avoid places where temperature and humidity may change easily (where condensation occurs) and store the controller in a cool, dry place where the ambient temperature ranges from -15 ℃ to 40 ℃.

*	Do not store the controller in locations where there are chemical products, acid and alkali products, batteries, circuit breakers, etc.

# 3.5. Discarding of the Controller

In order to ensure user safety and protect the environment, certain parts should be managed and discarded according to specified methods, and if they contain industrial waste materials, they must never be discarded together with general industrial or household waste. When discarding all or part of the robot system, you must comply with the relevant national or local regulations and laws. For details on the discarding and disposal of the product, please contact our customer support team.# 3.6. Connection

{% hint style="info" %}
1. Before connecting the cables, turn “off” the controller's main power switch and lock it by using use a padlock. 
2. The controller has DC400V charged energy. Be careful. 
Turn “off” the power switch and then wait 5 minutes at least to discharge the charged energy.
3. When handling the PCB, take precautions not to allow static electricity to damage it.
4. Wiring and connection of wires must be performed by qualified personnel.
{% endhint %}
# 3.6.1. Connection of the Teaching Pendant 

Connect the cable connector of the teaching pendant to the CNRTP receptacle of the controller.

![](../../_assets/그림_3.5_Hi6-N_(U)_티칭펜던트의_접속.png  )

Figure 3.5 Connection of Hi6-N**(U) Teaching Pendant  
# 3.6.2. Connection of the Manipulator and Controller

Connect between the manipulator and controller by using a wire harness. Check the names of individual receptacles while connecting them.

![](../../_assets/3.6.2._로봇_본체와_제어기의_접속-1.png)<br/><br/>

Wire Harness connection diagram

<table>
<thead>
  <tr>
    <th>&nbsp;&nbsp;&nbsp;<br>Hi6-N Controller&nbsp;&nbsp;&nbsp;</th>
    <th>&nbsp;&nbsp;&nbsp;<br>ROBOT&nbsp;&nbsp;&nbsp;</th>
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
Since the contact part of the connector for each robot may be different from the figure above, you must read the relevant robot maintenance manual carefully before connecting the wire harness.
{% endhint %}


Figure 3.6 Connection of the Manipulator and Controller (Hi6-N**(U))
# 3.6.3. Connectin of the Controller and Primary Power

Check whether the power has been removed from the primary power and breaker (NFB).
In the case of a Hi6-N** controller, insert the power cable through the power inlet and then connect it to the breaker (NFB).

At this time, use a terminal receptable of an appropriate size for the end side of the primary power supply cable.


![](../../../_assets/그림_3.8_Hi6-N__U__제어기에_1차_전원_접속부.png  )

![](../../../_assets/그림_3.8_Hi6-N__U__제어기에_1차_전원_접속부_2.png  )

Figure 3.7 Primary Power Connection Part of Hi6-N**(U) Controller
# 3.6.3.1. Power Requirements 

Table 3-2 Power Requirements 

<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>Controller type</strong></p></td>
<td><p><strong>Capacity*1)<sup>*1)</sup>[KVA]</strong></p></td>
<td><p><strong>Input voltage<sup>*2)</sup>[V]</strong></p></td>
<td><p><strong>Frequency[Hz]</strong></p></td>
<td><p><strong>Peak current[A]</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>Hi6-N00</p></td>
<td><p>Max. 7.8KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>30A</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>Hi6-N30</p></td>
<td><p>Max. 4.4KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>15A</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>Hi6-N80</p></td>
<td><p>Max. 10.5KVA</p></td>
<td><p>220V/380V/400V/440V</p></td>
<td><p>50/60</p></td>
<td><p>50A</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>Hi6-N00U</p></td>
<td><p>Max. 7.8KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>30A</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>Hi6-N30U</p></td>
<td><p>Max. 4.4KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>15A</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>Hi6-N80U</p></td>
<td><p>Max. 10.5KVA</p></td>
<td><p>460V/480V</p></td>
<td><p>50/60</p></td>
<td><p>50A</p></td>
</tr>
</tbody>
</table>


Note 1) Power capacity

Refers to the power supply capacity of the controller. For the power capacity of each robot, refer to the “Manipulator Maintenance Manual”.

Note 2) Voltage range: ±10% (at the power terminal of the controller)

# 3.6.3.2. Power Cable Thickness 


Table 3-3 Recommended Minimum Cable Thickness 

<table>
<thead>
  <tr>
    <th rowspan="2">&nbsp;&nbsp;&nbsp;<br>No.&nbsp;&nbsp;&nbsp;</th>
    <th rowspan="2">&nbsp;&nbsp;&nbsp;<br>Cable length m(feet)&nbsp;&nbsp;&nbsp;</th>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>Cable thickness<br>&nbsp;&nbsp;&nbsp;<br>(Hi6-N00(U),Hi6-N80(U))&nbsp;&nbsp;&nbsp;</th>
    <th colspan="2">&nbsp;&nbsp;&nbsp;<br>Cable thickness<br>&nbsp;&nbsp;&nbsp;<br>(Hi6-N30(U))&nbsp;&nbsp;&nbsp;</th>
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
# 3.6.4. The Controller and Grounding

For using the controller safely, connect the grounding wire to the controller. Use a grounding wire of 5.5㎟ or more. (Grounding of Category 3).
# 3.6.5. Other Cautions 

{% hint style="info" %}
1. When wiring the controller and manipulator, separate the signal line and the power line.
In addition, use separate ducts respectively for high power lines and signal lines.
2. Use a protective cover for the wires, as a measure to prevent the wires from getting damaged when people are passing.
3. Before supplying the primary power, you must check again the relationship in terms of connection, the power specification and the power supply specification of the controller.
{% endhint %}
# 3.6.6. Connection of the Ethernet Port for the User

The Ethernet port for the user is located on the front door of the controller. The pin descriptin and connection with a Pc are as follows.</br></br>

Table 3-4 Pin Description (RJ45 Connector Specification; RJ 45P Shield)

<table>
<tbody>
<tr class="odd">
<td><p><strong>RJ45 Pin No.</strong></p></td>
<td><p><strong>Name</strong></p></td>
<td><p><strong>Abbreviation</strong></p></td>
<td><p><strong>Direction</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>Transmit Data +</p></td>
<td><p>TX +</p></td>
<td><p>Out</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>Transmit Data -</p></td>
<td><p>TX -</p></td>
<td><p>Out</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>Receive Data +</p></td>
<td><p>RX +</p></td>
<td><p>In</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>Receive Data -</p></td>
<td><p>RX -</p></td>
<td><p>In</p></td>
</tr>
</tbody>
</table>
# 4. Basic Configuration of the Controller

{% hint style="info" %}
The person in charge of maintenance should work after understanding the placement of various devices and parts and their functions inside the controller.
{% endhint %}

# 4.1. Configuration 

The controller consists of the main body and teaching pendant.

![](../_assets/그림_4.1_Hi6-N_(U)_제어기.png  )

Figure 4.1 Hi6-N**(U) Controller

![](../_assets/그림_4.2_티칭펜던트_TP630.png  )

Figure 4.2 Teaching Pendant TP630
# 4.2. Placement of Parts

The main components of the Hi6-N00/N30/N80 controller and their individual names are shown below in Table 4-1 and are arranged as shown in Figure 4.3 to Figure 4.5.</br></br>

Table 4-1 Names of Individual Parts of the Hi6-N00/N30/N80 Controller

<table>
<tbody>
<tr class="odd">
<td><p><strong>No</strong></p></td>
<td><p><strong>Type</strong></p></td>
<td><p><strong>Part name</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>H6COM-T</p></td>
<td><p>Main control module</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>BD640</p></td>
<td><p>Servo board</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>BD632</p></td>
<td><p>Safety board</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>H6PSM</p></td>
<td><p>Power supply module</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>H6D6X(Large/Medium-sized)</p>
<p>/H6D6A(Small-sized)</p></td>
<td><p>Drive module for Large/Medium/Small-sized 6 axes</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>H6D1X(Optional)</p></td>
<td><p>Drive module for 1 axis of 100A</p></td>
</tr>
<tr class="even">
<td><p><strong>6-1</strong></p></td>
<td><p>H6D1Z(Optional)</p></td>
<td><p>Drive module for 1 axis of 50A</p></td>
</tr>
<tr class="odd">
<td><p><strong>7</strong></p></td>
<td><p>OP EM. SW.</p></td>
<td><p>Emergency switch on the controller panel</p></td>
</tr>
<tr class="even">
<td><p><strong>8</strong></p></td>
<td><p>NFB</p></td>
<td><p>No fuse breaker</p></td>
</tr>
<tr class="odd">
<td><p><strong>9</strong></p></td>
<td><p>FAN2</p></td>
<td><p>Drive module internal cooling fan</p></td>
</tr>
<tr class="even">
<td><p><strong>10~12</strong></p></td>
<td><p>FAN3~5</p></td>
<td><p>Drive module external cooling fan</p></td>
</tr>
<tr class="odd">
<td><p><strong>13</strong></p></td>
<td><p>NFT1</p></td>
<td><p>Line noise filter</p></td>
</tr>
<tr class="even">
<td><p><strong>14</strong></p></td>
<td><p>RDR1</p></td>
<td><p>Small/Medium/Large-sized regenerative discharge resistor</br>(CE/UL certified article)</p></td>
</tr>
<tr class="odd">
<td><p><strong>15</strong></p></td>
<td><p>TR</p></td>
<td><p>Transformer for the input power for options</p></td>
</tr>
<tr class="even">
<td><p><strong>16</strong></p></td>
<td><p>CMC1</p></td>
<td><p>Motor drive power cable inlet connection</p></td>
</tr>
<tr class="odd">
<td><p><strong>17</strong></p></td>
<td><p>CMC2</p></td>
<td><p>Motor drive power cable inlet connection</p>
<p>(Small controllers without a CMC2 mounted)</p></td>
</tr>
<tr class="even">
<td><p><strong>18</strong></p></td>
<td><p>AMC1(Option)</p></td>
<td><p>Inlet connector for the motor-driving power cable
for options 1
</p></td>
</tr>
<tr class="odd">
<td><p><strong>19</strong></p></td>
<td><p>AMC2(Option)</p></td>
<td><p>Inlet connector for the motor-driving power cable
for options 2
</p></td>
</tr>
<tr class="even">
<td><p><strong>20</strong></p></td>
<td><p>CEC1</p></td>
<td><p>Encoder communication cable inlet connection</p></td>
</tr>
<tr class="odd">
<td><p><strong>21</strong></p></td>
<td><p>AEC1</p></td>
<td><p>Inlet connector for the motor encoder cable for options 1</p></td>
</tr>
<tr class="even">
<td><p><strong>22</strong></p></td>
<td><p>AEC2</p></td>
<td><p>Inlet connector for the motor encoder cable for options 2</p></td>
</tr>
<tr class="odd">
<td><p><strong>23</strong></p></td>
<td><p>CNRTP</p></td>
<td><p>Teaching pendant cable inlet connector </p></td>
</tr>
</tbody>
</table>

![](../_assets/그림_4.3_Hi6-N00(U),N30(U),N80(U)_제어기_전면_외부의_부품배치.png  )

Figure 4.3 Placement of Parts on the Front Exterior of the Hi6-N00(U)/N30(U)/N80(U) Controller

![](../_assets/그림_4.4_Hi6-N00(U),N30(U),N80(U)_제어기_전면_내부의_부품배치.png  )

Figure 4.4 Placement of Parts on the Front Interior of the Hi6-N00(U)/N30(U)/N80(U) Controller

![](../_assets/그림_4.5_Hi6-N00(U),N30(U),N80(U)_제어기_후면_부품배치-1.png  )

![](../_assets/그림_4.5_Hi6-N00(U),N30(U),N80(U)_제어기_후면_부품배치.png  )

![](../_assets/그림_4.5_Hi6-N00(U),N30(U),N80(U)_제어기_후면_부품배치-3.png  )

Figure 4.5 Placement of Parts on the Back of the Hi6-N00(U)/N30(U)/N80(U) Controller
# 4.3. Functions of the Individual Components 

Table 4-2 Summary of Functions of the Individual Components

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">Control module</td>
    <td>Main control module (H6COM-T)</td>
    <td>- Recording the record points and calculating the operation paths<br>- 	Preservation of the programs and robot integers<br>- Teach pendant (T/P) communication<br>- Connection of the LAN, USB, and the serial (RS232) communication</td>
  </tr>
  <tr>
    <td>Servo board (BD640)</td>
    <td>-	DSP for servo control<br>- Encoder connection (Serial I/F)<br>- Open/close outputs for the servo motor<br>- Sequence control</td>
  </tr>
  <tr>
    <td>Safety module (BD632)</td>
    <td>- I/O in the controller (I/O for the system)<br>- Processing of various input signals from the manipulator<br>- Safety chain circuit</td>
  </tr>
  <tr>
    <td>Drive module</td>
    <td>Large/Medium-sized 6 axes: H6D6X<br>Small-sized 6 axes: H6D6A<br>Additional axis: H6D1X, H6D1Z</td>
    <td>- Generation of the motor drive power<br>- Regenerative discharge<br>- Servo motor power amplification circuit<br>- Various error outputs</td>
  </tr>
  <tr>
    <td>T/P<br>(Teach Pendant)</td>
    <td>TP630</td>
    <td>- Display of various information (LCD)<br>- Button inputs and switch inputs (function/jog, etc.)<br>- Emergency stop, enable, and T/P On/Off inputs</td>
  </tr>
  <tr>
    <td>Cooling device</td>
    <td>Fan</td>
    <td>- Air circulation inside the panel<br>- Cooling of the drive module</td>
  </tr>
  <tr>
    <td>Power supply module</td>
    <td>H6PSM</td>
    <td>- Opening/closing of the motor drive power<br>- Distribution of various power</td>
  </tr>
</tbody>
</table>


※ For the types of components of each controller, refer to “2.1 Details of Specifications of Each Controller Model.”# 4.3.1. Main Module (H6COM-T)
# 4.3.1.1. Overview

H6COM-T is structure as shown in Figure 4.3, in which the main CPU board and the carrier board are combined. The main CPU board consists of an SSD slot, a CPU slot, a memory card slot, a USB port, a COM port, and a bus connector that is to be connected to the carrier board. The carrier board contains three LAN ports for external systems, two LAN ports for internal systems, two USB ports, one GPIO port, two PCI connectors, one PCI-e connector and one DC 24V power connector. The LAN ports for internal systems are used for EtherCAT communication, as well as for interface with the teach pendant, and the GPIO port is used to detect a power failure signal from the power system. The SB is used for debugging. One PCI expansion slot and three spare LAN ports for external systems are provided to support other universal bus interfaces. The connection to other communication interfaces than EtherCAT can be made via the relevant slots.

![](../../../_assets/그림_4.23_H6COM-T.png  )

Figure 4.6 H6COM-T
# 4.3.1.2. Connectors

Table 4-3 describes the usage of the connector and the connection of external devices.

Table 4-3 Types and Usage of the Connectors of Hi6COM-T

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>DC IN 24V</strong></p></td>
<td><p>DC24V main power supply</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>COM 1,2</strong></p></td>
<td><p>Serial port (RS232/RS422/RS485)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>GIO</strong></p></td>
<td><p>Application of the power failure of the power unit</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 4</strong></p></td>
<td><p>EtherCAT master connector port</p></td>
<td><p>EtherCAT connector</p></td>
</tr>
<tr class="even">
<td><p><strong>LAN 5</strong></p></td>
<td><p>Ethernet port: For communication between teach pendants</p></td>
<td><p>TP connector</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 1</strong></p></td>
<td><p>Ethernet port: For the user (PC I/F)</p></td>
<td><p>Optional EtherCAT connector</p></td>
</tr>
<tr class="even">
<td><p><strong>LAN 2</strong></p></td>
<td><p>Ethernet port: For the user (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>LAN 3</strong></p></td>
<td><p>Ethernet port: For the user (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>PCI, PCIe</strong></p></td>
<td><p>Optional expansion board slot</p></td>
<td><p>-</p></td>
</tr>
<tr class="odd">
<td><p><strong>USB1,2</strong></p></td>
<td><p>USB port: For the user (PC I/F)</p></td>
<td><p>-</p></td>
</tr>
</tbody>
</table>
# 4.3.2. Safety Module (BD632)
# 4.3.2.1. Overview

For meeting the requirement of PLr=d cat3 (SIL2) in compliance with IOS 13849-1, the safety module (BD632) is designed in a dualized safety electric circuit and continuously monitors the status of safety-related inputs. If a system error or safety-related input is detected, this safety module renders the robot into a safe state by cutting off the motor power and brake power according to the classification of the stop types determined through risk assessment.
# 4.3.2.2. Connectors

The following figure shows the positions and usage of various connectors installed on BD632 (Safety IO Module).

![](../../../_assets/그림_4.24_BD632(Safety_IO_Board)의_커넥터_및_스위치_배치.png  )

Figure 4.7 Placement of the Connectors and Switches of the BD632 (Safety IO Board)</br></br>

Table 4-4 Types and Usage of the Connectors of the BD632 (Safety IO Board)

<table>
<tbody>
<tr class="odd">
<td><p><strong></strong></p></td>
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS1</strong></p></td>
<td><p>SMPS DC24V power supply</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="odd">
<td><p><strong>A</strong></p></td>
<td><p><strong>CNSMPS2</strong></p></td>
<td><p>SMPS DC24V power supply</p></td>
<td><p>DC24V SMPS</p></td>
</tr>
<tr class="even">
<td><p><strong>B</strong></p></td>
<td><p><strong>CNTP</strong></p></td>
<td><p>Inputs of the emergency stop switch, mode switch, and enable switch of the teaching pendant</p></td>
<td><p>Teaching Pendant</p></td>
</tr>
<tr class="odd">
<td><p><strong>C</strong></p></td>
<td><p><strong>CNMC</strong></p></td>
<td><p>Connection of the Magnet Contact (MC) input and output signals</p></td>
<td><p>MC(Magnet Contact)</p></td>
</tr>
<tr class="even">
<td><p><strong>D</strong></p></td>
<td><p><strong>CNLS</strong></p></td>
<td><p>Limit switch input for the detection of arm interference and over-travel</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>E</strong></p></td>
<td><p><strong>CNLS7</strong></p></td>
<td><p>Limit switch input for the detection of the over-travel of the additional axis 7</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>F</strong></p></td>
<td><p><strong>CNLS8</strong></p></td>
<td><p>Limit switch input for the detection of the over-travel of the additional axis 8</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>G</strong></p></td>
<td><p><strong>CNSV</strong></p></td>
<td><p>Servo sequence board (BD640) I/F</p>
<p>(Status related to motor on/off, feedback, the servo sequence board, and the safety board)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>H</strong></p></td>
<td><p><strong>CNEMSW</strong></p></td>
<td><p>Emergency stop input of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>I</strong></p></td>
<td><p><strong>CNOPSW</strong></p></td>
<td><p>Inputs of the mode switch and keys of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="even">
<td><p><strong>J</strong></p></td>
<td><p><strong>CNOPLP</strong></p></td>
<td><p>Lamp output of the Operational Panel (OP)</p></td>
<td><p>OP(Operational Panel)</p></td>
</tr>
<tr class="odd">
<td><p><strong>K</strong></p></td>
<td><p><strong>TBEM</strong></p></td>
<td><p>External safety inputs</p>
<p>(Emergency stop, auto mode safety guard 1, auto mode safety guard 2, and general safety guard input)</p></td>
<td><p>User IO</p></td>
</tr>
<tr class="even">
<td><p><strong>L</strong></p></td>
<td><p><strong>EXMON</strong></p></td>
<td><p>External motor on signal input</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>M</strong></p></td>
<td><p><strong>TBPLC</strong></p></td>
<td><p>Connection of the safety PLC safety signals</p></td>
<td><p>Safety PLC</p></td>
</tr>
<tr class="even">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ1</strong></p></td>
<td><p>EtherCat communication connection (INPUT)</p></td>
<td><p>BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>N</strong></p></td>
<td><p><strong>MJ2</strong></p></td>
<td><p>EtherCat communication connection (OUTPUT)</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>O</strong></p></td>
<td><p><strong>SW3,SW4</strong></p></td>
<td><p>limit&OVT On/OFF SW</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>P</strong></p></td>
<td><p><strong>SW1,SW2</strong></p></td>
<td><p>OP INSTALL input (enable, disable)</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Q</strong></p></td>
<td><p><strong>A_JTAG1,B_JTAG1</strong></p></td>
<td><p>J-TAG connector (Program download)</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>R</strong></p></td>
<td><p><strong>SW7</strong></p></td>
<td><p>ES, SG input (enable, disable)</p></td>
<td></td>
</tr>
</tbody>
</table>

\(1\) External Safety Signal Terminal Block of the BD632: TBEM

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.8 BD632(Safety IO Board) TBEM

{% hint style="info" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}

Table 4-5 Description of TBEM of the BD632 (Safety IO Board) 

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>16</td>
    <td>SGG1+</td>
    <td rowspan="2">General safety guard chain 1 input</td>
    <td rowspan="2">If the general safety guard chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>8</td>
    <td>SGG1-</td>
  </tr>
  <tr>
    <td>15</td>
    <td>SGG2+</td>
    <td rowspan="2">General safety guard chain 2 input</td>
    <td rowspan="2">If the general safety guard chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>7</td>
    <td>SGG2-</td>
  </tr>
  <tr>
    <td>14</td>
    <td>SGA11+</td>
    <td rowspan="2">Automatic safety guard 1 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>6</td>
    <td>SGA11-</td>
  </tr>
  <tr>
    <td>13</td>
    <td>SGA21+</td>
    <td rowspan="2">Automatic safety guard 1 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 1 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>5</td>
    <td>SGA21-</td>
  </tr>
  <tr>
    <td>12</td>
    <td>SGA12+</td>
    <td rowspan="2">Automatic safety guard 2 chain 1 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 1 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SGA12-</td>
  </tr>
  <tr>
    <td>11</td>
    <td>SGA22+</td>
    <td rowspan="2">Automatic safety guard 2 chain 2 input</td>
    <td rowspan="2">If the automatic safety guard 2 chain 2 input is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>SGA22-</td>
  </tr>
  <tr>
    <td>10</td>
    <td>EMEX1+</td>
    <td rowspan="2">External emergency stop chain 1 input</td>
    <td rowspan="2">If the external emergency stop chain 1 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMEX1-</td>
  </tr>
  <tr>
    <td>9</td>
    <td>EMEX2+</td>
    <td rowspan="2">External emergency stop chain 2 input</td>
    <td rowspan="2">If the external emergency stop chain 2 is not to be used, it should be short-circuited.</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMEX2-</td>
  </tr>
</tbody>
</table>


\(2\) Safety PLC Connection Terminal Block of the BD632: TBPLC

![](../../../_assets/그림_4.26_BD632(Safety_IO_Board)_TBPLC.png  )

Figure 4.9 BD632(Safety IO Board) TBPLC

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}


Table 4-6 Description of TBPLC of BD632 (Safety IO Board)

<table>
<thead>
  <tr>
    <th>Terminal no.</th>
    <th>Terminal name</th>
    <th>Usage</th>
    <th>Others</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>12</td>
    <td>PLC_P</td>
    <td>Safety PLC 24V</td>
    <td></td>
  </tr>
  <tr>
    <td>6</td>
    <td>PLC_G</td>
    <td>Safety PLC GND</td>
    <td>To function as Common for the SG/ES signal </td>
  </tr>
  <tr>
    <td>11</td>
    <td>PLC_TO1</td>
    <td>Input terminal for the monitoring output of the safety IO</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>5</td>
    <td>PLC_FDBK1</td>
    <td>Feedback signal output for T0 of the safety IO</td>
  </tr>
  <tr>
    <td>10</td>
    <td>SG1</td>
    <td>Chain 1 for the safety guard input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>4</td>
    <td>SG2</td>
    <td>Chain 2 for the safety guard input from the safety PLC</td>
  </tr>
  <tr>
    <td>9</td>
    <td>ES1</td>
    <td>Chain 1 for the emergency stop input from the safety PLC</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>3</td>
    <td>ES2</td>
    <td>Chain 2 for the emergency stop input from the safety PLC</td>
  </tr>
  <tr>
    <td>8</td>
    <td>EMOUT11+</td>
    <td rowspan="2">Internal emergency stop output chain 1</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>2</td>
    <td>EMOUT11-</td>
  </tr>
  <tr>
    <td>7</td>
    <td>EMOUT21+</td>
    <td rowspan="2">Internal emergency stop output chain 2</td>
    <td rowspan="2">PNP output type applicable only</td>
  </tr>
  <tr>
    <td>1</td>
    <td>EMOUT21-</td>
  </tr>
</tbody>
</table>

\(3\)  External Motor On connecter

![](../../../_assets/외부_모터온_커넥터.png  )

Table 4-7 BD632 external motor on switch 

<table>
<tbody>
<tr class="odd">
<td><p><strong>Terminal no. </strong></p></td>
<td><p><strong>Terminal name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Others</strong></p></td>
</tr>
<tr class="even">
<td><p>5</p></td>
<td><p>EXMON_C1+</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C1+ should be short-circuited with EXMON_C1-.</p></td>
</tr>
<tr class="odd">
<td><p>1</p></td>
<td><p>EXMON_C1-</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C1+ should be short-circuited with EXMON_C1-.</p></td>
</tr>
<tr class="even">
<td><p>8</p></td>
<td><p>EXMON_C2+</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C2+ should be short-circuited with EXMON_C2-.</p></td>
</tr>
<tr class="odd">
<td><p>4</p></td>
<td><p>EXMON_C2-</p></td>
<td><p>External motor on (Contact type)</p></td>
<td><p>When not to be used, EXMON_C2+ should be short-circuited with EXMON_C2-.</p></td>
</tr>
</tbody>
</table>
# 4.3.2.3. Display Devices

![](../../../_assets/그림_4.27_BD632(Safety_IO_Board)의_표시장치.png  )

Figure 4.10 Display Devices of BD632 (Safety IO Board)</br></br>

Table 4-8 Description of the Display Devices of the BD632 (Safety IO Module)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Contents of display</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>When normal</strong></p></td>
<td><p><strong>Actions to take when an abnormality occurs</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>LED1</strong></p></td>
<td><p>24 V power (Chain 1)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon Red LED turned on or off </p>
<p>Action 1: Check the inpput voltage (24 V).</p>
<p>Action 2: If the LED is turned off, check the fuse (F1).</p>
<p>Action 3: Replace the BD632 board.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LED2</strong></p></td>
<td><p>24 V power (Chain 2)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon Red LED turned on or off</p>
<p>Action 1: Check the inpput voltage (24 V).</p>
<p>Action 2: If the LED is turned off, check the fuse (F2).</p>
<p>Action 3: Replace the BD632 board.</p></td>
</tr>
<tr class="even">
<td><p><strong>LED3</strong></p></td>
<td><p>24 V power (Chain 1)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon Red LED turned on or off</p>
<p>Action 1: Check the inpput voltage (24 V).</p>
<p>Action 2: If the LED is turned off, check the fuse (F3).</p>
<p>Action 3: Replace the BD632 board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LED4</strong></p></td>
<td><p>24 V power (Chain 2)</p></td>
<td><p>Green</p>
<p>Red</p></td>
<td><p>Green LED turned on</p></td>
<td><p>Phenomenon Red Turned on or Turned off</p>
<p>Action 1: Check the inpput voltage (24 V).</p>
<p>Action 2: If the LED is turned off, check the fuse (F5).</p>
<p>Action 3: Replace the BD632 board.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDR1</strong></p></td>
<td><p>Reset</p></td>
<td><p>Red</p></td>
<td><p>Turned off</p></td>
<td><p>Phenomenon Red Turned on</p>
<p>Action 1: Replace the BD632 board.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDR2</strong></p></td>
<td><p>EtherCAT communication error LED</p></td>
<td><p>Red</p></td>
<td><p>Turned off</p></td>
<td><p>Phenomenon Red Turned on</p>
<p>Action 1: Check the EtherCAT cable connection status.</p>
<p>Action 2: Replace the BD632 board.</p>
<p>Action 3: Check H6COM-T or BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG3</strong></p></td>
<td><p>OP installation LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>Switch On (When the OP is installed) green LED turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG4</strong></p></td>
<td><p>OP installation LED (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>Switch On (When the OP is installed) green LED turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG5</strong></p></td>
<td><p>STO output LED (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>STO On: Turned on</p>
<p>STO OFF: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board</p>
<p>Action 2: Replace the magnet contact.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG6</strong></p></td>
<td><p>STO output LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>STO On: Turned on</p>
<p>STO OFF: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board.</p>
<p>Action 2: Replace the magnet contact</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG7</strong></p></td>
<td><p>MC status check LED (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>MC Close: Turned on</p>
<p>MC Open: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board</p>
<p>Action 2: Replace the magnet contact</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG8</strong></p></td>
<td><p>MC status check LED (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>MC Close: Turned on</p>
<p>MC Open: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the BD632 board</p>
<p>Action 2: Replace the magnet contact</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG9</strong></p></td>
<td><p>Teach pendant manual mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG10</strong></p></td>
<td><p>Teach pendant manual mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG11</strong></p></td>
<td><p>Teach pendant auto mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG12</strong></p></td>
<td><p>Teach pendant auto mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG13</strong></p></td>
<td><p>Teach pendant remote mode input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG14</strong></p></td>
<td><p>Teach pendant remote mode input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG15</strong></p></td>
<td><p>Teach pendant enable input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG16</strong></p></td>
<td><p>Teach pendant enable input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG17</strong></p></td>
<td><p>Teach pendant emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG18</strong></p></td>
<td><p>Teach pendant emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace the teach pendant</p>
<p>Action 2: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG19</strong></p></td>
<td><p>OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the OVT switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG20</strong></p></td>
<td><p>OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the OVT switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG21</strong></p></td>
<td><p>Hard limit input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the hard limit switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG22</strong></p></td>
<td><p>Hard limit input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the hard limit switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG23</strong></p></td>
<td><p>Additional axis OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the additional axis OVT switch.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG24</strong></p></td>
<td><p>Additional axis OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the additional axis OVT switch.</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG25</strong></p></td>
<td><p>Extended OVT input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the extended OVT switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG26</strong></p></td>
<td><p>Extended OVT input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the extended OVT switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG27</strong></p></td>
<td><p>Safety guard input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the safety guard</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG28</strong></p></td>
<td><p>Safety guard input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the safety guard</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG29</strong></p></td>
<td><p>Auto mode safety guard 1 input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the auto mode 1 safety guard</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG30</strong></p></td>
<td><p>Auto mode safety guard 1 input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the auto mode 1 safety guard</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG31</strong></p></td>
<td><p>Auto mode safety guard 2 input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the auto mode 2 safety guard</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG32</strong></p></td>
<td><p>Auto mode safety guard 2 input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the auto mode 2 safety guard</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG33</strong></p></td>
<td><p>External motor on input (Contact type)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the external motor on contact switch.</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG34</strong></p></td>
<td><p>External emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Replace the external emergency stop switch</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG35</strong></p></td>
<td><p>External emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Replace the external emergency stop switch</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG36</strong></p></td>
<td><p>Servo state input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG37</strong></p></td>
<td><p>Safety module state output (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG38</strong></p></td>
<td><p>Servo state input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace BD640</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG39</strong></p></td>
<td><p>Safety module state output (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG40</strong></p></td>
<td><p>OP emergency stop input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>: Replace the OP emergency stop switch. </p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG41</strong></p></td>
<td><p>OP emergency stop input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the cable</p>
<p>Action 2: Replace BD632</p>
<p>: Replace the OP emergency stop switch. </p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG52</strong></p></td>
<td><p>PLC power</p></td>
<td><p>Green</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the fuse (F6)</p>
<p>Action 2: Inspect the cable</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG53</strong></p></td>
<td><p>Emergency stop (npn type) input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect LEDG52 (when abnormal, take action for LEDG52)</p>
<p>Action 2: Inspect the cable</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG54</strong></p></td>
<td><p>Emergency stop (npn type) input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect LEDG52 (when abnormal, take action for LEDG52)</p>
<p>Action 2: Inspect the cable</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG55</strong></p></td>
<td><p>Safety guard (npn type) input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect LEDG52 (when abnormal, take action for LEDG52)</p>
<p>Action 2: Inspect the cable</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG56</strong></p></td>
<td><p>Safety guard (npn type) input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When not inputted: Turned on</p>
<p>When not inputted: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect LEDG52 (when abnormal, take action for LEDG52)</p>
<p>Action 2: Inspect the cable</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG57</strong></p></td>
<td><p>24 V power input</p></td>
<td><p>Green</p></td>
<td><p>Green Turned on</p></td>
<td><p>Phenomenon Turned off</p>
<p>Action 1: Inspect the 24 V power cable and voltage (power for connecting the CNSMPS1 connector)</p>
<p>Action 2: Inspect the fuse (F1)</p>
<p>Action 3: Replace BD632</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG58</strong></p></td>
<td><p>EtherCAT MJ1 connector ACT LED</p></td>
<td><p>Green</p></td>
<td><p>When EterCAT cable connected: Turned on</p>
<p>When EterCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG59</strong></p></td>
<td><p>EtherCAT MJ2 connector ACT LED</p></td>
<td><p>Green</p></td>
<td><p>When EterCAT cable connected: Turned on</p>
<p>When EterCAT cable not connected: Turned off</p>
<p>During EtherCAT communication: Blinking</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG60</strong></p></td>
<td><p>EtherCAT state LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: Blinking</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG61</strong></p></td>
<td><p>EtherCAT RUN LED</p></td>
<td><p>Green</p></td>
<td><p>When communication connected: Blinking</p>
<p>When communication not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG62</strong></p></td>
<td><p>Safety chain input (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG63</strong></p></td>
<td><p>Safety chain input (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG64</strong></p></td>
<td><p>EtherCAT MJ2 connector speed LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG65</strong></p></td>
<td><p>EtherCAT MJ1 connector speed LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG68</strong></p></td>
<td><p>Safety chain output (Chain 1)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG69</strong></p></td>
<td><p>Safety chain output (Chain 2)</p></td>
<td><p>Green</p></td>
<td><p>When inputted: Turned off</p>
<p>When not inputted: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG70</strong></p></td>
<td><p>ACFLT</p></td>
<td><p>Green</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board or electrical equipment</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG71</strong></p></td>
<td><p>EXMON_C2</p></td>
<td><p>Green</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Replace the connected board or electrical equipment</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG72</strong></p></td>
<td><p>Magnet contact ON/OFF signal (Channel 1)
</p></td>
<td><p>Green</p></td>
<td><p>When ON signal: Turned off</p>
<p>When OFF signal: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable(BD632-BD640)</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Check the firmware</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG73</strong></p></td>
<td><p>Magnet status Feedback(Channel 1)</p></td>
<td><p>Green</p></td>
<td><p>MC CLOSE: Turned off</p>
<p>MC OPEN: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable(BD632-H6PSM-MC)</p>
<p>Action 2: Replace MC</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Check the firmware</p></td>
</tr>
<tr class="odd">
<td><p><strong>LEDG74</strong></p></td>
<td><p>Magnet contact ON/OFF signal (Channel 2)
</p></td>
<td><p>Green</p></td>
<td><p>When ON signal: Turned off</p>
<p>When OFF signal: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable(BD632-BD640)</p>
<p>Action 2: Replace BD632</p>
<p>Action 3: Check the firmware</p></td>
</tr>
<tr class="even">
<td><p><strong>LEDG75</strong></p></td>
<td><p>Magnet status Feedback(Channel 2)</p></td>
<td><p>Green</p></td>
<td><p>MC CLOSE: Turned off</p>
<p>MC OPEN: Turned on</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the connected cable(BD632-H6PSM-MC)</p>
<p>Action 2: Replace MC</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Check the firmware</p></td>
</tr>
<tr class="odd">
<td><p><strong>MJ1 G</strong></p></td>
<td><p>EtherCAT MJ1 connector link LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Blinking</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>MJ1 Y</strong></p></td>
<td><p>EtherCAT MJ1 connector ACT LED</p></td>
<td><p>Yellow</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>MJ2 G</strong></p></td>
<td><p>EtherCAT MJ2 connector link LED</p></td>
<td><p>Green</p></td>
<td><p>When connected: Blinking</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="even">
<td><p><strong>MJ2 Y</strong></p></td>
<td><p>EtherCAT MJ2 connector ACT LED</p></td>
<td><p>Yellow</p></td>
<td><p>When connected: Turned on</p>
<p>When not connected: Turned off</p></td>
<td><p>Phenomenon States other than normal state</p>
<p>Action 1: Inspect the EtherCAT cable</p>
<p>Action 2: Check the firmware</p>
<p>Action 3: Replace BD632</p>
<p>Action 4: Replace BD640 or H6COM-T</p></td>
</tr>
<tr class="odd">
<td><p><strong>SEG1</strong></p></td>
<td><p>Safety module state LED (Chain 1)</p></td>
<td><p>7-seg</p></td>
<td><p>When normal: A number will be displayed, and the dot will blink.</p></td>
<td><p>Phenomenon Turned off, or the dot stops blinking</p>
<p>Action 1: Replace BD632</p></td>
</tr>
<tr class="even">
<td><p><strong>SEG2</strong></p></td>
<td><p>Safety module state LED (Chain 2)</p></td>
<td><p>7-seg</p></td>
<td><p>When normal: A number will be displayed, and the dot will blink.</p></td>
<td><p>Phenomenon Turned off, or the dot stops blinking</p>
<p>Action 1: Replace BD632</p></td>
</tr>
</tbody>
</table>
# 4.3.2.4. Setting Devices

![](../../../_assets/그림_4.31_BD632(Safety_IO_Board)의_설정장치_설명.png  )

Figure 4.11 Description of the Setting Devices of the BD632 (Safety IO Board)

{% hint style="warning" %}
When a safety-related input is connected and activated, you must check whether the function is operating normally by referring to “1.11 Safety Measures When Operating the Robot.”
{% endhint %}


Table 4-9 Description of the SW1, SW2, SW3, SW4 and SW7 setting devices of BD632 (Safety IO Module)


<table>
<thead>
  <tr>
    <th colspan="2">Switch</th>
    <th rowspan="2">SW1</th>
    <th rowspan="2">SW2</th>
    <th rowspan="2">SW3</th>
    <th rowspan="2">SW4</th>
    <th rowspan="2">SW7</th>
  </tr>
  <tr>
    <th colspan="2">number</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td colspan="2">Usage</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 1)</td>
    <td>Sets whether to install the Operation Panel (OP) (Chain 2)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 1)</td>
    <td>Sets whether to install OVT6, LS, OVT7 (additional axis), and OVT8 (extended axis) (Chain 2)</td>
    <td>Sets whether to install the PLC ES, SG(Chain 1, Chain 2)
</td>
  </tr>
  <tr>
    <td rowspan="2">Contents of setting</td>
    <td>OFF</td>
    <td>Non-installation</td>
    <td>Non-installation</td>
    <td>1: Installation of OVT6</br>2: Installation of LS<br>3: Installation of OVT7</br>4: Installation of OVT8
</td>
    <td>1: Installation of OVT6</br>2: Installation of LS</br>3: Installation of OVT7</br>4: Installation of OVT8</br>
</td>
    <td>1: Installation of ES(Chain 1)</br>2: Installation of SG(Chain 1)</br>3: Installation of ES(Chain 2)</br>4: Installation of SG(Chain 2)</br>
</td>
  </tr>
  <tr>
    <td>ON</td>
    <td>Installation</td>
    <td>Installation</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation of OVT6</br>2: No installation of LS</br>3: No installation of OVT7</br>4: No installation of OVT8</br>
</td>
    <td>1: No installation of ES(Chain 1)</br>2: No installation of SG(Chain 1)</br>3: No installation of ES(Chain 2)</br>4: No installation of SG(Chain 2)</br>
</td>
  </tr>
  <tr>
    <td colspan="2">Setting when shipped from the factory</td>
    <td>Non-installation (OFF)</td>
    <td>Non-installation (OFF)</td>
    <td>1: OFF</br>2: OFF</br>3: On (OFF when an additional axis OVT is connected)</br>4: On (OFF when an extended axis OVT is connected)</br>
</td>
    <td>1: OFF</br>2: OFF</br>3: On (OFF when an additional axis OVT is connected)</br>4: On (OFF when an extended axis OVT is connected)</br>
</td>
    <td>1: No installation of ES(Chain 1)</br>2: No installation of SG(Chain 1)</br>3: No installation of ES(Chain 2)</br>4: No installation of SG(Chain 2)</br>
</td>
  </tr>
</tbody>
</table>
# 4.3.2.5. Connections of the Emergency Stop

(1\)  External Emergency Stop of Contact Input Type 

The external emergency stop (EMEX) is designed in a way that it can be operated regardless of the controller mode (automatic or manual) and is continuously monitored by the BD632 (Safety IO Board). When a safety input is coming in, the motor power will be shut off to put the robot in a safe state. The external emergency stop switch should be connected and used in the form of contact output, as shown in the figure below.

![](../../../_assets/그림_4.32_터미널블록_TBEM에_외부비상정지_스위치를_연결하는_방법.png  )

Figure 4.12 Method to Connect the External Emergency Stop Switch to the Terminal Block TBEM

If the external emergency stop is not to be used, connect the terminals of the terminal block TBEM (connect the pins 9-1 and 10-2 of the TBEM connector), as shown below, to disable the input.

![](../../../_assets/그림_4.25_BD632(Safety_IO_Board)_TBEM.png  )

Figure 4.13 Method to Perform When Not Using the External Emergency Stop of Contact Input Type

{% hint style="warning" %}
If an external emergency stop is to be installed and used, the robot should be operated after confirming that the emergency stop operates normally. In addition, check if the emergency stop input is disabled. This is an essential measure that must be taken in advance for the safety of workers.
{% endhint %}
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

# 4.3.2.8. Connection of the External Motor On Signal

![](../../../_assets/그림_4.39_외부_모터온_신호의_연결방법.png  )

Figure 4.19 Method for Connection of the External Motor On Signal

When using a motor on signal input from the outside of the controller, the relevant connection should be configured in the form of a contact as above. If you don't connect, please connect it with a jumper wire. (N.C Contact type)
# 4.3.3. Servo Board (BD640)
# 4.3.3.1. Overview

The servo board controls the operation of six axes (maximum eight axes) according to the position command received from the main board through EtherCAT communication, and processes the encoder signal, checks the error status, and creates the PWM signal of the drive unit.

![](../../../_assets/4.3.3.1._개요(Hi6).png  )
# 4.3.3.2. Connectors

Table 4-10 Types and Usage of the Connectors of the Servo Board (BD640)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNEC1,4</strong></p></td>
<td><p>Connection of the encoder signal</p></td>
<td><p>CNR4</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNEC7,8</strong></p></td>
<td><p>Connection of encoder signal of the additional axis</p></td>
<td><p>CNR7,CNR8</p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1,2,3</strong></p></td>
<td><p>Connection of the drive unit signal</p></td>
<td><p>CNBS1, CNBS2, and CNBS 3 of the drive unit</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNJTAG1</strong></p></td>
<td><p>FPGA JTAG emulator port</p></td>
<td><p>JTAG emulator</p></td>
</tr>
<tr class="even">
<td><p><strong>JP1</strong></p></td>
<td><p>FPGA BOOT MODE</p></td>
<td><p>FPGA flash and JTAG boot mode</p></td>
</tr>
<tr class="odd">
<td><p><strong>VR1</strong></p></td>
<td><p>Encoder input power regulator</p></td>
<td><p>-</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPNB1</strong></p></td>
<td><p>Brake power input</p></td>
<td><p>Brake cable</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNB1</strong></p></td>
<td><p>Brake power of the main axis</p></td>
<td><p>Brake cables for axis 1 to axis 6</p></td>
</tr>
<tr class="even">
<td><p><strong>CNB7,8</strong></p></td>
<td><p>Brake power of the additional axis</p></td>
<td><p>Brake cables for axis 7 and axis 8</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPRC1</strong></p></td>
<td><p>MC relay contact</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>CN24VB1</strong></p></td>
<td><p>BD640 main power</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>CNSV1</strong></p></td>
<td><p>BD630 DIO contact interface</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>DS1</strong></p></td>
<td><p>DSP boot mode</p></td>
<td><p>-</p></td>
</tr>
</tbody>
</table>
# 4.3.3.3. Display Devices

 Table 4-11 LEDs of the Servo Board (BD640)

<table>
<tbody>
<tr class="odd">
<td><p><strong>Status</strong></p>
<p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>When normal</strong></p></td>
<td><p><strong>When abnormal</strong></p></td>
<td><p><strong>Remarks</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>AL1</strong></p></td>
<td><p>Red</p></td>
<td><p>Turned off</p></td>
<td><p>Turned on</p></td>
<td><p>The PWM control signals for all axes will be turned off.</p></td>
</tr>
<tr class="odd">
<td><p><strong>SON1~8</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the motor is on</p></td>
<td><p>Will be turned off when the motor is off</p></td>
<td><p>-</p></td>
</tr>
</tbody>
</table>
# 4.3.3.4. Setting Devices 

{% hint style="info" %}
The DIP switch is set to OFF mode when shipped from the factory, and the setting should not be changed arbitrarily by the user.
{% endhint %}


Table 4-12 Method to Set the DIP Switch (DS1) of the Servo Board (BD640) 

<table>
<thead>
  <tr>
    <th>Switch number</th>
    <th>1</th>
    <th>2</th>
    <th>Mode</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Setting when shipped from the factory</td>
    <td>OFF</td>
    <td>OFF</td>
    <td>GET MODE</td>
  </tr>
  <tr>
    <td>When testing</td>
    <td>ON</td>
    <td>OFF</td>
    <td>WAIT MODE</td>
  </tr>
  <tr>
    <td>Switch exterior</td>
    <td colspan="3"></td>
  </tr>
</tbody>
</table>

![](../../../_assets/표4-11_스위치외형.png)</br></br>

{% hint style="info" %}
The user cannot change the following items arbitrarily and needs to refer to them only when required to reprogram through FPGA JTAG.
{% endhint %}


Table 4-13 Description of the Jumper (JP1) of the Servo Board (BD640) 

<table>
<thead>
  <tr>
    <th colspan="2" rowspan="2">Name<br>Contents of the setting</th>
    <th colspan="4">JP1</th>
  </tr>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">Setting of the jumper</td>
    <td>QSPI (flash) boot mode</td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>JTAG programming mode</td>
    <td></td>
    <td>⊙</td>
    <td>⊙</td>
    <td></td>
  </tr>
  <tr>
    <td>Setting when shipped from the factory</td>
    <td colspan="5">1, 2 : short / 3 : open</td>
  </tr>
</tbody>
</table>
# 4.3.4. Drive Module
# 4.3.4.1. H6D6X (Medium-Sized 6 Axes Integrated Drive Module)

The drive module performs a power amplification function that allows the current to flow to the individual phases of the motor according to the current command from the servo board. The six axes integrated drive module can drive six motors at the same time and is configured as follows.

The three-phase current entered from the power supply module is rectified through a diode module and then converted into direct current and stored in a smoothing capacitor. When the motor speed of the robot is decelerated, the electric power generated from the motor will be consumed through IGBT and resistors. The relevant configuration is as follows. 

Table 4-14 Configuration of H6D6X (Medium-Sized 6 Axes Integrated Drive Module)


<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD651<br>(Power Board)</td>
    <td>Gate drive circuit</td>
    <td>Generates the IPM gate signal</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Transmit the gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td>Regenerative control</td>
    <td>Drives the IGBT when the PN voltage rises</td>
  </tr>
  <tr>
    <td>Error detection part</td>
    <td>Detects the PN overvoltage, regenerative discharge resistor overheating, and PN undervoltage errors</td>
  </tr>
  <tr>
    <td>High voltage capacitor</td>
    <td>Smooths the direct current</td>
  </tr>
  <tr>
    <td rowspan="2">BD652<br>(Iterface Board)</td>
    <td>Sequence interlocking part</td>
    <td>Interlocks between the sequence status and the servo on signal</td>
  </tr>
  <tr>
    <td>Dedicated IO Terminal Blocks</td>
    <td>Reserved IO port inside the controller</td>
  </tr>
  <tr>
    <td rowspan="4">Other parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated from power elements to the outside</td>
  </tr>
  <tr>
    <td>Rectification part</td>
    <td>Rectify the AC input power to generate DC power for driving the motor</td>
  </tr>
  <tr>
    <td>Regenerative IGBT</td>
    <td>Performs regenerative discharge</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>Convert the power for driving a three-phase motor</td>
  </tr>
</tbody>
</table>

■  **Configuration of the Type Number of the Medium-Sized 6 Axes Integrated Drive Module**

![](../../../_assets/중형_6축_일체형_드라이브모듈_형번_구성.png  )

Table 4-15 Type Symbol of the Medium-Sized 6 Axes Integrated Drive Module 

<table>
<tbody>
<tr class="odd">
<td><p><strong>Category</strong></p></td>
<td><p><strong>Type symbol</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 Medium-Sized 6 Axes drive module</strong></p></td>
<td><p>H6D6X</p></td>
</tr>
</tbody>
</table>

Table 4-16 Specification of the Medium-Sized 6 Axes Integrated Drive Module

<table>
<thead>
  <tr>
    <th>Configuration</th>
    <th colspan="2">Classification</th>
    <th colspan="2">Application </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">IPM capacity</td>
    <td>3X</td>
    <td>3Y</td>
    <td>HS180, HS220, HH300, HH050</td>
    <td rowspan="2">6 axes integrated </td>
  </tr>
  <tr>
    <td>4X</td>
    <td>2Y</td>
    <td>HC2502B2D, HC2503B2D</td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000~2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January~December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~999</td>
  </tr>
</tbody>
</table>

Table 4-17 Symbols of the IPM of the medium-sized 6 axes drive module 

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>IPM symbol</th>
    <th>IPM Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the medium-sized 6 axes</td>
    <td>X</td>
    <td>(IPM current rating) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM current rating) 75A</td>
  </tr>
   <tr>
    <td>Z</td>
    <td>(IPM current rating) 50A</td>
  </tr>
</tbody>
</table>

Table 4-18 Symbols of the Hall Sensors of the medium-sized 6 axes drive module 

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall sensor symbol (Specification)</th>
    <th>Full-scalecurrent (Im)</th>
    <th>IPM specification<br>(Rated current)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the medium-sized 6 axes</td>
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
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}


![](../../../_assets/그림_4.39_BD651_부품_배치도.png  )

Figure 4.20 Parts Placement Diagram of BD651</br></br>

Table 4-19 Description of the Connectors of BD651

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals</p></td>
<td><p>Board-to-board connectors of the BD652</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>3-phase power input</p></td>
<td><p>CNRST for the electronic module</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of the BD652</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>Regenerative discharge power output</p></td>
<td><p>Regenerative discharge resistor</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>Regenerative discharge resistor overheating detection</p></td>
<td><p>Regenerative discharge resistor temperature sensor</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~3</strong></p></td>
<td><p>Motor drive output for axis 1 to axis 3</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~6</strong></p></td>
<td><p>Motor drive output for axis 4 to axis 6</p></td>
<td><p>CMC2</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>Direct current power for the drive module of the additional axis</p></td>
<td><p>CNPN for the drive module for an optional additional axis.</p></td>
</tr>
<tr class="even">
<td><p><strong>CNFG1</strong></p></td>
<td><p>Frame ground for axis 1 to axis 3</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG2</strong></p></td>
<td><p>Frame ground for axis 4 to axis 6</p></td>
<td><p>CMC2</p></td>
</tr>
</tbody>
</table>

Table 4-20 Description of LEDs of BD651

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status Display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control voltage of the converter part is normal</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on the regenerative discharge is operating</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on when the PN voltage is higher than 42V</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned off when the PN discharge is operating</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4.40_BD652_부품_배치도.png  )

Figure 4.21 Parts Placement Diagram of BD652

Table 4-21 Description of the Connectors of BD652

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>PWM signals and IPM error signals for 8 axes<br>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals for individual axes</p></td>
<td><p>Board-to-board connectors of BD651</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>PWM signal and IPM error signal for the additional axis</p></td>
<td><p>CNPWM of the drive module (BD658 or BD659) of the additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD651</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>Reserved only for the IO terminal block</p></td>
<td><p>Reserved</p></td>
</tr>
</tbody>
</table>

Table 4-22 Description of the LEDs of BD652

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status Display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control power is normal</p></td>
</tr>
</tbody>
</table>
# 4.3.4.2. H6D6A (Small-Sized 6 Axes Integrated Drive Module)

The drive module performs a power amplification function that allows the current to flow to individual phases of the motor according to the current command from the servo board. The six axes integrated drive module can drive six motors at the same time and is configured as follows.

The three-phase current entered from the power supply module is rectified through a diode module and then converted into direct current and stored in a smoothing capacitor. When the motor speed of the robot is decelerated, the electric power generated from the motor will be consumed through IGBT and resistors. The relevant configuration is as follows.


Table 4-23 Configuration of H6D6A (Small-Sized 6 Axes Integrated Drive Module)

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Components</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">BD653<br>(Power Board)</td>
    <td>Gate drive circuit</td>
    <td>Generates the IPM gate signal</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Generates the gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td>Regenerative control</td>
    <td>Turn on the IGBT when the PN voltage rises</td>
  </tr>
  <tr>
    <td>Error detection part</td>
    <td>Detects the overvoltage, regenerative resistor overheating, and undervoltage errors</td>
  </tr>
  <tr>
    <td>High voltage capacitor</td>
    <td>Smooths the direct current</td>
  </tr>
  <tr>
    <td rowspan="2">BD654<br>(Iterface Board)</td>
    <td>Sequence interlocking part</td>
    <td>Interlocks between the sequence status and the servo on signal</td>
  </tr>
  <tr>
    <td>Dedicated IO Terminal Blocks</td>
    <td>Reserved IO port inside the controller</td>
  </tr>
  <tr>
    <td rowspan="4">Other Parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated in power elements to the outside</td>
  </tr>
  <tr>
    <td>Rectification part</td>
    <td>Rectify the AC input power to generate DC power for driving the motor</td>
  </tr>
  <tr>
    <td>Regenerative IGBT</td>
    <td>Performs regenerative discharge</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>Convert the power for driving a three-phase motor</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}

■  **Configuration of the Type Number of the Small-Sized 6 Axes Integrated Drive Module**


![](../../../_assets/소형_6축_일체형_드라이브모듈_형번_구성.png  )

Table 4-24 Type Symbol of the Small-Sized 6 Axes Integrated Drive Module

<table>
<tbody>
<tr class="odd">
<td><p><strong>Category </strong></p></td>
<td><p><strong>Type symbol</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 Small-Sized 6 Axes drive module</strong></p></td>
<td><p>H6D6A</p></td>
</tr>
</tbody>
</table>

Table 4-25 Specification of the Small-Sized 6 Axes Integrated Drive Module

<table>
<thead>
  <tr>
    <th>Configuration</th>
    <th colspan="2">Classification</th>
    <th colspan="2">Application</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>IPM capacity</td>
    <td>3A</td>
    <td>3D</td>
    <td>HA006B, HH020</td>
    <td>6 axes integrated </td>
  </tr>
  <tr>
    <td>Year</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">Production year: 2000-2099</td>
  </tr>
  <tr>
    <td>Month</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">Production month: January-December</td>
  </tr>
  <tr>
    <td>Serial No.</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">Number of units produced monthly: 1~999</td>
  </tr>
</tbody>
</table>

Table 4-26 Capacity of the Small-Sized IPM

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>IPM symbol</th>
    <th>IPM Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">Drive module of the small-sized 6 axes</td>
    <td>A</td>
    <td>(IPM allowable current rating) 30A</td>
  </tr>
  <tr>
    <td>D</td>
    <td>(IPM allowable current rating) 10A</td>
  </tr>
</tbody>
</table>

Table 4-27 Symbols of the Hall Sensors of the Small-Sized IPM

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall sensor symbol (Specification)</th>
    <th>Full-scale current (Im)</th>
    <th>IPM specification (Allowable current rating)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">Drive module of the small-sized 6 axes</td>
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
The drive module differs depending on the type of the robot, so you must check the type when replacing it.
{% endhint %}

![](../../../_assets/그림_4.41_BD653_부품_배치도.png  )

Figure 4.22 Parts Placement Diagram of BD653 

Table 4-28 Description of the Connectors of BD653

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals</p></td>
<td><p>Board-to-board connectors of BD654</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>3-phase power input</p></td>
<td><p>CNRST for the electronic module</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD654</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>Regenerative discharge power output </p></td>
<td><p>Regenerative discharge resistor</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>Regenerative discharge resistor overheating detection</p></td>
<td><p>Regenerative discharge resistor temperature sensor</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~6</strong></p></td>
<td><p>Motor drive output</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>Direct current for the drive module of the additional axis</p></td>
<td><p>CNPN for the drive module for an optional additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG1, CNFG4</strong></p></td>
<td><p>Frame ground for motors</p></td>
<td><p>CMC1</p></td>
</tr>
</tbody>
</table>

Table 4-29 Description of the LEDs of BD653

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC ON</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control voltage of the converter part is normal</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on the regenerative discharge is operating</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned on when the PN voltage is higher than 42V</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>Red</p></td>
<td><p>Will be turned off when the PN discharge operation starts</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4.42_BD654_부품_배치도.png  )

Figure 4.23 Parts Placement Diagram of BD654</br></br>

Table 4-30 Description of the Connectors of BD654

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Usage</strong></p></td>
<td><p><strong>Connection of external devices</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>PWM signals and IPM error signals for 8 axes<br>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD640</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>PWM signals and IPM error signals for individual axes</p></td>
<td><p>Board-to-board connectors of BD653</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>PWM signal and IPM error signal for the additional axis</p></td>
<td><p>CNPWM of the drive module (BD 658 or BD 659) of the additional axis</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>Converter part error signal</p></td>
<td><p>Board-to-board connectors of BD653</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>Reserved only IO terminal block</p></td>
<td><p>Reserved</p></td>
</tr>
</tbody>
</table>

Table 4-31 Description of the LEDs of BD654

<table>
<tbody>
<tr class="odd">
<td><p><strong>Name</strong></p></td>
<td><p><strong>Color</strong></p></td>
<td><p><strong>Status Display</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>MC</strong></p></td>
<td><p>Yellow</p></td>
<td><p>Will be turned on when the magnet contact is driving</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>Green</p></td>
<td><p>Will be turned on when the control power is normal</p></td>
</tr>
</tbody>
</table>
# 4.3.4.3. Specification of the Optional Drive Module

■  **Configuration of the Type Number of the Optional Drive Module**

![](../../../_assets/선택사양_드라이브모듈의_형번_구성.png  )

Table 4-32 Type Symbol of the Optional Drive Module

<table>
<thead>
  <tr>
    <th>Category</th>
    <th>Type symbol</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Hi6 1 Axes drive module</td>
    <td>H6D1</td>
  </tr>
</tbody>
</table>

Table 4-33 Capacity of the IPM of the Optional Drive Module

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>IPM symbol</th>
    <th>IPM Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the additional axis</td>
    <td>X</td>
    <td>(IPM current rating) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM current rating) 75A</td>
  </tr>
  <tr>
    <td>Z</td>
    <td>(IPM current rating) 50A</td>
  </tr>
</tbody>
</table>

Table 4-34 Symbols of the Hall Sensors of the Optional Drive Module

<table>
<thead>
  <tr>
    <th>Drive Model</th>
    <th>Hall sensor symbol(Specification)</br>Full-scale current (Im)</th>
    <th>Full-scale current(Im)</th>
    <th>IPM specification</br>(Rated current</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">Drive module of the additional axis</td>
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
# 4.3.4.4. H6D1X (Carriage Drive Module; Optional)

The drive module performs a power amplification function that allows the current to flow to the individual phases of the motor according to the current command from the servo board. The carriage drive module can drive one motor of 100A or below and is configured as follows.

![](../../../_assets/그림_4.43_H6D1X용BD658_부품_배치도.png  )

Figure 4.24 Parts Placement Diagram of BD658 for H6D1X</br></br>

Table 4-35 Configuration of H6D1X

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD658</br>(IPM board)
</td>
    <td>Logic part</td>
    <td>Converts the PWM signals received from the drive module for the 6 axes into the upper and lower sides drive signals of the IPM, and processes errors</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Generates the IPM gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td rowspan="2">Other parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated in IPM to the outside</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>Convert the power for driving a three-phase motor</td>
  </tr>
</tbody>
</table>

Table 4-36 Description of the Connectors of H6D1X

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Connection of external devices</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM signal and error signal</td>
    <td>CNPWM7 or CNPWM8 of the drive module (BD652 or BD654) for the 6 axes</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>Motor drive output</td>
    <td>AMC1 or AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>Frame ground for the motor</td>
    <td>AMC1 or AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>Drive direct current power input</td>
    <td>CNPN7 or CNPN8 of the drive module (BD651 or BD653) for the 6 axes</td>
  </tr>
</tbody>
</table>
# 4.3.4.5. H6D1Z (Servo Gun Drive Module; Optional)

The drive module performs a power amplification function that allows the current to flow to the individual phases of the motor according to the current command from the servo board. The servo gun drive module can drive one motor of 50A or below and is configured as follows.

![](../../../_assets/그림_4.44_H6D1Z용_BD659_부품_배치도.png  )

Figure 4.25 Parts Placement Diagram of BD659 for H6D1Z</br></br>

Table 4-37 Configuration of H6D1Z

<table>
<thead>
  <tr>
    <th colspan="2">Components</th>
    <th>Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD659<br>(IPM board)</td>
    <td>Logic part</td>
    <td>Converts the PWM signals received from the drive module for the 6 axes into the upper and lower sides drive signals of the IPM, and processes errors</td>
  </tr>
  <tr>
    <td>Gate power module</td>
    <td>Generates the IPM gate power</td>
  </tr>
  <tr>
    <td>Current detection part</td>
    <td>Detects the current that flows through the motor</td>
  </tr>
  <tr>
    <td rowspan="2">Other parts</td>
    <td>Heat sink</td>
    <td>Releases the heat generated in IPM to the outside</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>Convert the power for driving a three-phase motor</td>
  </tr>
</tbody>
</table>

Table 4-38 Description of the Connectors of H6D1Z

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Connection of external devices</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM signal and error signal</td>
    <td>CNPWM7 or CNPWM8 of the drive module (BD652 or BD654) for the 6 axes</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>Motor drive output</td>
    <td>AMC1 or AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>Frame ground for the motor</td>
    <td>AMC1 or AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>Drive direct current power input</td>
    <td>CNPN7 or CNPN8 of the drive module (BD651 or BD653) for the 6 axes</td>
  </tr>
</tbody>
</table>
# 4.3.5. Power Supply Module (H6PSM)
# 4.3.5.1. H6PSM and Power Distribution Board (BD6C2) 

The H6PSM (Hi6-N controller power supply module) module is responsible for the opening and closing and distribution of various power supplied to the controller. The following figures show the interior and exterior of the electrical module with diverse connectors and fuses.

![](../../../_assets/그림_4.45_H6PSM(Hi6-N_제어기_전원공급모듈)_외부.png  )

Figure 4.26 Exterior of H6PSM (Hi6-N Controller Power Supply Module)

The following figure shows the power system diagram for the AC control power related to the opening and closing of the 3-phase AC power for the motor power, the generation of the brake power, and the driving of the fan. The diagram in the figure also shows the power distribution, such as the SMPS power for the DC power supply to the control module. A circuit breaker (CP) or fuse is connected to each power to protect individual circuits against overcurrent.

![](../../../_assets/그림_4.47_Hi6-N_제어기의_전원계통.png  )

Figure 4.27 Power System of the Hi6-N Controller</br></br>

Table 4-39 Types and Usage of the Fuses of the Electronic Module 

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>F1, F2</td>
    <td>Overcurrent protection fuse for the cooling fan power (AC220V)</td>
    <td>AC220V 5A</td>
  </tr>
  <tr>
    <td>F3, F4</td>
    <td>Overcurrent protection fuse for the CMSMPS power (AC220V) </td>
    <td>AC220V 5A</td>
  </tr>
  <tr>
    <td>F5, F6</td>
    <td>Overcurrent protection fuse for the BKSMPS power (AC220V) </td>
    <td>AC220V 5A</td>
  </tr>
</tbody>
</table>
# 4.3.5.2. Connectors of BD6C2

The placement of the connectors of the electronic board (BD6C2) is shown in the following figure, and the usage and connection devices for each are as shown in Table 4-39.

![](../../../_assets/그림_4.48_전장보드(BD6C2)의_커넥터.png  )

Figure 4.28 Connectors of the Electronic Board (BD6C2)</br></br>

Table 4-40 Types and Usage of the Connectors of BD6C2

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Specification</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNAC</td>
    <td>3-phase power input for control</td>
    <td>3-phase 220V</td>
  </tr>
  <tr>
    <td>CN220</td>
    <td>CMSMPS power output</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNFN1~4</td>
    <td>AC fan power output</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNPR1</td>
    <td>Inrush current limiting circuit input</td>
    <td>3-phase 220V, MC1 input side</td>
  </tr>
  <tr>
    <td>CNPR2</td>
    <td>Inrush current limiting circuit output</td>
    <td>3-phase 220V, MC2 output side </td>
  </tr>
  <tr>
    <td>CNBKAC</td>
    <td>Brake SMPS input</td>
    <td>Single-phase 220V</td>
  </tr>
  <tr>
    <td>CNBKDC</td>
    <td>Brake SMPS output</td>
    <td>24VDC</td>
  </tr>
  <tr>
    <td>CNPB1</td>
    <td>Brake control power</td>
    <td>24VDC, PB, BD640</td>
  </tr>
  <tr>
    <td>CNPB2</td>
    <td>Brake control power</td>
    <td>24VDC, PB, Reserved</td>
  </tr>
  <tr>
    <td>CNPRC</td>
    <td>Inrush current limiting circuit control and monitoring</td>
    <td>BD640 CNPRC</td>
  </tr>
  <tr>
    <td>CNFPS1</td>
    <td>CMSMPS power failure detection signal output 1</td>
    <td>H6COM DIO</td>
  </tr>
  <tr>
    <td>CNFPS2</td>
    <td>CMSMPS power failure detection signal output 2</td>
    <td>Reserved</td>
  </tr>
  <tr>
    <td>CNMC1</td>
    <td>Electronic contact MC1 control and monitoring</td>
    <td>MC1</td>
  </tr>
  <tr>
    <td>CNMC2</td>
    <td>Electronic contact MC2 control and monitoring</td>
    <td>MC2</td>
  </tr>
  <tr>
    <td>CNMC</td>
    <td>Electronic contact control and monitoring</td>
    <td>BD632 CNMC</td>
  </tr>
  <tr>
    <td>CN24VB</td>
    <td>Control power input for each module</td>
    <td>24VDC, CMBUFFER output</td>
  </tr>
  <tr>
    <td>CN24VB1~8</td>
    <td>Control power output for each module</td>
    <td>24VDC, CN24VB for each module</td>
  </tr>
  <tr>
    <td>CNBM</td>
    <td>CMSMPS power failure detection signal input</td>
    <td>CMSMPS 13-14</td>
  </tr>
</tbody>
</table>
# 4.3.6. Teach Pendant (TP630)
# 4.3.6.1. Overview

The teach pendant (TP630) communicates with the main module (H6COM-T) of the controller through Ethernet and allows the user to directly operate the following functions.

*	Monitoring	: Job program / Data of each axis / Input and output signals / Status of the robot, etc.

*	Log management 	: System version, operation time, error log, stop log, etc.

*	File management 	: Version and teach program up/down

*	Setting of various variables : User environment / control / robot / application / automatic integer, etc.

*	Robot teaching 	: Jog and teach program registration

*	Robot operation 	: Motor on / start / stop / mode settings

The teach pendant is also equipped with a three-stage enable switch and emergency stop switch to ensure user safety.
In addition, a USB A type connector is mounted under the rubber cover at the bottom of the teach pendant, allowing the user to upload/download necessary files, such as data and teaching programs, as well as versions of diverse types of boards using a USB memory stick.


![](../../../_assets/그림_4.49_티치펜던트_TP630의_외관.png  )

Figure 4.29 Exterior of the Teach Pendant TP630
# 4.3.6.2. USB Cover

There is a USB A type connector mounted under the rubber cover at the bottom of the teach pendant, allowing the user to upload/download necessary files, such as versions of diverse types of boards, as well as data and teaching programs, using a USB memory stick.
 
# 5. Optional Components of the Controller
# 5.1. PCI Communication Card
# 5.1.1. Overview

To use industrial communication in the Hi6 controller, you can use a PCI communication card. Descriptions below are provided based on a PCI communication card for Ethernet, which is a general model. For details, please refer to the contents for the PC Cards CIFX 50 model in the document “PC Cards CIFX 50 50E 70E 100EH UM 51 EN.”

Table 5-1 Part Names of PCI Communication Cards

<table>
<thead>
  <tr>
    <th>No.</th>
    <th>Model Name</th>
    <th>Communication type</th>
    <th>Interface Connector</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>CIFX 50-RE/ML-HRC</td>
    <td>HRC Real-Time Ethernet Master PCI</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>2</td>
    <td>CIFX 50-RE-HRC</td>
    <td>HRC Real-Time Ethernet Slave PCI</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>3</td>
    <td>CIFX 50E-RE/ML-HRC</td>
    <td>HRC Real-Time Ethernet Master PCIe</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>4</td>
    <td>CIFX 50E-RE-HRC</td>
    <td>HRC Real-Time Ethernet Slave PCIe</td>
    <td>RJ45</td>
  </tr>
  <tr>
    <td>5</td>
    <td>CIFX 50-CC-HRC</td>
    <td>CC-Link Slave PCI</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>6</td>
    <td>CIFX 50E-CC-HRC</td>
    <td>CC-Link Slave PCIe</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>7</td>
    <td>CIFX 50-DN/ML-HRC</td>
    <td>DeviceNet Maser PCI</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>8</td>
    <td>CIFX 50-DN-HRC</td>
    <td>DeviceNet Slave PCI</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>9</td>
    <td>CIFX 50E-DN/ML-HRC</td>
    <td>DeviceNet Maser PCIe</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>10</td>
    <td>CIFX 50E-DN-HRC</td>
    <td>DeviceNet Slave PCIe</td>
    <td>CombiCon Male, 5 pin</td>
  </tr>
  <tr>
    <td>11</td>
    <td>CIFX 50-DP/ML-HRC</td>
    <td>PROFIBUS Master PCI</td>
    <td>Dsub Female, 9 pin</td>
  </tr>
  <tr>
    <td>12</td>
    <td>CIFX 50-DP-HRC</td>
    <td>PROFIBUS Slave PCI</td>
    <td>Dsub Female, 9 pin</td>
  </tr>
  <tr>
    <td>13</td>
    <td>CIFX 50E-DP/ML-HRC</td>
    <td>PROFIBUS Master PCIe</td>
    <td>Dsub Female, 9 pin</td>
  </tr>
  <tr>
    <td>14</td>
    <td>CIFX 50E-DP-HRC</td>
    <td>PROFIBUS Slave PCIe</td>
    <td>Dsub Female, 9 pin</td>
  </tr>
  <tr>
    <td>15</td>
    <td>CIFX 50E-CCIES-HRC</td>
    <td>CC-Link IE Fileld PCIe</td>
    <td>RJ45</td>
  </tr>
</tbody>
</table>
# 5.1.2. Configuration of the PCI Communication Card

A PCI communication card is basically configured, as shown below (when Ethernet-based communication is used), and varies in the number of connectors and LEDs depending on the type of industrial communication.

![](../../_assets/그림_5.1_PCI통신_카드_외관.png  )

Figure 5.1 Exterior of the PCI Communication Card</br></br>

Table 5-2 Description of the Exterior of the PCI Communication Card

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Rotary Switch</td>
    <td>Sets the communication according to the slot ID</td>
  </tr>
  <tr>
    <td>LED</td>
    <td>Displays the system and communication status</td>
  </tr>
  <tr>
    <td>Communication Port</td>
    <td>Communication connection port</td>
  </tr>
  <tr>
    <td>PCI Bus</td>
    <td>PC connection bus</td>
  </tr>
</tbody>
</table>
# 5.1.3. Front Part of the PCI Communication Card

You can check the communication setting, communication cable connection, and communication status through the front part of the PCI communication card. Basically, you can use the card by setting the rotary switch to 1-4 in order according to the location of the H6COM-T PCI slot.

![](../../_assets/그림_5.2_PCI통신_카드_전면부.png  )

Figure 5.2 Front Part of the PCI Communication Card</br></br>

Table 5-3 Configuration of the Front Part of the PCI Communication Card, and the Description of the Functions

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Description of Functions</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Rotary Switch</td>
    <td>Sets the communication for each slot number</td>
    <td>H6COM-T PCI slots are fixed as #1~#4 sequentially starting from the one at the top (Communication to be set from TP).</td>
  </tr>
  <tr>
    <td>System LED</td>
    <td>System status checking LED</td>
    <td>Green: System in operation</br>Yellow: Boot loader waiting
</td>
  </tr>
  <tr>
    <td>Communication Status LED</td>
    <td>Communication status checking LED</td>
    <td>Green: Communication in operation</br>Red: Communication error
</td>
  </tr>
  <tr>
    <td>Communication Interface</td>
    <td>Communication cable connection port</td>
    <td>Use of connectors suitable for communication</td>
  </tr>
</tbody>
</table>
# 5.2. Brake Release Unit 
# 5.2.1. Overview

The brake release unit can be used when it is necessary to release the motor brake for each axis of the robot. It can help to set the robot posture mainly during the initial installation of the robot. When releasing the brake, you must fully understand the safety information of “Release of the manual brake” in “1.8.2 Other Related Functions” before using the robot.

{% hint style="info" %}
1. Do not release more than two axes at the same time.
2. Keep a safe distance from the robot first before using the brake release unit.
3. Use the brake release unit after preparing for the dropping of the robot’s axis using equipment such as a crane.
4. Check the safety matters while working in a group of at least two people.
{% endhint %}

{% hint style="warning" %}
The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, it is required to comply with the relevant requirements of international standards and national laws. 
Our company (or the manufacturer) will not be responsible for any accidents that occur because of not complying with the relevant requirements of international standards and national laws or not following the above “caution.”
{% endhint %}

# 5.2.2. Brake Release Switch

The placement of the switches of the brake release unit is as shown in Figure 5.3, and their individual usage and operation are described in Table 5-4. To release the brake of the targeted axis, first press the Enable button, and then, while pressing the Enable button, press one of the buttons B1–B8 at the same time. Then, the relevant axis will be released.


![](../../_assets/그림_5.3_브레이크_해제유닛_스위치_및_상태확인_LED.png  )

Figure 5.3 Switches and Status Checking LEDs of the Brake Release Unit</br></br>

Table 5-4 Usage of the Switches of the Brake Release Unit 

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>During operation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>E</td>
    <td>Brake Release Enable</td>
    <td>Yellow Enable LED ON</td>
  </tr>
  <tr>
    <td>B1</td>
    <td>Axis 1 Brake Release</td>
    <td>Green D1 LED ON</td>
  </tr>
  <tr>
    <td>B2</td>
    <td>Axis 2 Brake Release</td>
    <td>Green D2 LED ON</td>
  </tr>
  <tr>
    <td>B3</td>
    <td>Axis 3 Brake Release</td>
    <td>Green D3 LED ON</td>
  </tr>
  <tr>
    <td>B4</td>
    <td>Axis 4 Brake Release</td>
    <td>Green D4 LED ON</td>
  </tr>
  <tr>
    <td>B5</td>
    <td>Axis 5 Brake Release</td>
    <td>Green D5 LED ON</td>
  </tr>
  <tr>
    <td>B6</td>
    <td>Axis 6 Brake Release</td>
    <td>Green D6 LED ON</td>
  </tr>
  <tr>
    <td>B7</td>
    <td>Axis 7 Brake Release</td>
    <td>Green D7 LED ON</td>
  </tr>
  <tr>
    <td>B8</td>
    <td>Axis 8 Brake Release</td>
    <td>Green D8 LED ON</td>
  </tr>
</tbody>
</table>
# 5.2.3. Power and Connectors 

The placement of the power and connectors of the brake release unit is as shown in Figure 5.4 below, and their individual usage and connection devices are as shown in Table 5-5 below.

{% hint style="info" %}
- When using the brake release unit, follow the procedures below.
1. Turn off the AC220V power switch and check that the DC24V power switch is turned off.
2. Connect the AC power cable to the AC power connector.
3. Turn on the AC220V power switch.
4. Turn on the DC24V power switch.

- When the use of the brake release unit is finished, follow the procedures below.
1. Turn off the DC24V power switch.
2. Turn off the AC220V power switch.
4. Disconnect the AC power cable.

- Do not use AC220V power and DC24V battery power at the same time.
{% endhint %}

{% hint style="warning" %}
Our company (or the manufacturer) will not be responsible for any accidents that occur because of not complying with the above “caution.”
{% endhint %}


![](../../_assets/그림_5.4_브레이크_해제_유닛_스위치_및_커넥터.png  )

Figure 5.4 Switches and Connectors of the Brake Release Unit</br></br>

Table 5-5 Types and Usage of the Connectors of the Brake Release Unit

<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>Connection of external devices</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>AC 220V power connector and switch</td>
    <td>Application of the AC power</td>
    <td>100V AC~240V AC Single phase</td>
  </tr>
  <tr>
    <td>Brake release cable connection connector</td>
    <td>Connection of the brake release unit and controller</td>
    <td>CNB1, CNB7, and CNB8 of BD640</td>
  </tr>
  <tr>
    <td>DC24V battery power connector</td>
    <td>Connection of the power of a portable 24V battery</td>
    <td>Portable 24V battery</td>
  </tr>
  <tr>
    <td>DC24V power switch</td>
    <td>Brake release unit drive on/off</td>
    <td>None</td>
  </tr>
</tbody>
</table>
# 5.2.4. Brake Release Unit Status Display LEDs
The LEDs for displaying the status of the brake release unit are as shown in Figure 5.3, and their individual usage and operation status are as shown in Table 5-6 below.

Table 5--6 Usage and Operation of the LEDs for the Status of the Brake Release Unit


<table>
<thead>
  <tr>
    <th>Name</th>
    <th>Usage</th>
    <th>LED On operation</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Enable</td>
    <td>Checking by pressing the Enable switch</td>
    <td>When the Enable switch is pressed,</br>the yellow Enable LED will be turned on.</td>
  </tr>
  <tr>
    <td>D1</td>
    <td>Checking by pressing the switch for axis 1</td>
    <td>When the switch for axis 1 is pressed, the green D1 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D2</td>
    <td>Checking by pressing the switch for axis 2</td>
    <td>When the switch for axis 2 is pressed, the green D2 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D3</td>
    <td>Checking by pressing the switch for axis 3</td>
    <td>When the switch for axis 3 is pressed, the green D3 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D4</td>
    <td>Checking by pressing the switch for axis 4</td>
    <td>When the switch for axis 4 is pressed, the green D4 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D5</td>
    <td>Checking by pressing the switch for axis 5</td>
    <td>When the switch for axis 5 is pressed, the green D5 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D6</td>
    <td>Checking by pressing the switch for axis 6</td>
    <td>When the switch for axis 6 is pressed, the green D6 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D7</td>
    <td>Checking by pressing the switch for axis 7</td>
    <td>When the switch for axis 7 is pressed, the green D7 LED will be turned on.</td>
  </tr>
  <tr>
    <td>D8</td>
    <td>Checking by pressing the switch for axis 8</td>
    <td>When the switch for axis 8 is pressed, the green D8 LED will be turned on.</td>
  </tr>
</tbody>
</table>
# 5.3. Remote IO
# 5.3.1. Overview

To use general IO signals in the Hi6 controller, you need the commercial remote IO. Basically, the commercial remote IO can be used by connecting an “IO module” (selected by the user) to one “communication module.” The module introduced below is a commercial remote IO module of Crevis, and you may purchase and use a commercial remote of other companies. For details on how to use each module, you are required to ask the company about the IO module you purchased.

{% hint style="info" %}
Fieldbus communication must be available to use the commercial remote IO. Therefore, you should configure the PCI communication card together by referring to “5.1 PCI Communication Card” mentioned above.
{% endhint %}


![](../../_assets/그림_5.5상용_리모트_IO_구성_예시.png  )

Figure 5.5 Example of Configuration of Commercial Remote IO
# 5.3.2. Communication Module (of Crevis)

The types of communication modules are as shown below and can be used according to the desired communication.

Table 5-7 Communication Module (of Crevis)


<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M9212</p></td>
<td><p>DeviceNet Network Adapter</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M9287</p></td>
<td><p>ProfiNet Network Adapter</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>M9289</p></td>
<td><p>ModbusTCP/UDP, EthernetIP Network Adapter</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>M9386</p></td>
<td><p>EtherCAT ID Network Adapter, 1452 bytes</p></td>
</tr>
</tbody>
</table>
# 5.3.3. IO and Other Modules (of Crevis)

The types of IO and other modules are as shown below and can be configured and used according to the desired operation.

Table 5-8 IO Module (of Crevis)


<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M12DF</p></td>
<td><p>Digital Input 16Points, Universal (Sink or</p>
<p>Source), 24Vdc, 18RTB</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M12FA</p></td>
<td><p>Digital Input 32Points, Universal (Sink or</p>
<p>Source), 24Vdc, Hirose 40P</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>M225F</p></td>
<td><p>Digital Output 16 Points, Sink, 24Vdc/0.3A,</p>
<p>18RTB</p></td>
</tr>
<tr class="odd">
<td><p><strong>4</strong></p></td>
<td><p>M226F</p></td>
<td><p>Digital Output 16 Points, Source, 24Vdc/0.3A,</p>
<p>18RTB</p></td>
</tr>
<tr class="even">
<td><p><strong>5</strong></p></td>
<td><p>M22BA</p></td>
<td><p>Digital Output 32Points, Sink, 24Vdc/0.3A,</p>
<p>Hirose 40P</p></td>
</tr>
<tr class="odd">
<td><p><strong>6</strong></p></td>
<td><p>M2618</p></td>
<td><p>Digital Output 8 Points, Sink, 24Vdc/1A, Max</p>
<p>8A, 18RTB</p></td>
</tr>
<tr class="even">
<td><p><strong>7</strong></p></td>
<td><p>M2628</p></td>
<td><p>Digital Output 8 Points, Source, 24Vdc/1A, Max</p>
<p>8A, 18RTB</p></td>
</tr>
</tbody>
</table>

Table 5-9 Relay Module (of Crevis)

<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model Name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M2788</p></td>
<td><p>MOS Relay, 8 Points, 110Vdc/ac, 1A, 18RTB</p></td>
</tr>
</tbody>
</table>

Table 5-10 Analogue IO Module (of Crevis)

<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model Name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M3534</p></td>
<td><p>Analog Input 4ch Volatage, -10~10Vdc, 14bits</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M4534</p></td>
<td><p>Analog Output 4ch Volatage, -10~10Vdc,</p>
<p>14bits</p></td>
</tr>
</tbody>
</table>

Table 5-11 Pulse Measuring Module (of Crevis)

<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model Name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M5112</p></td>
<td><p>High speed counter, 2Channels, 24Vdc,</p>
<p>18RTB(Open Collector)</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M5102</p></td>
<td><p>High speed counter, 2Channels, 5Vdc,</p>
<p>18RTB(RS422 Differential)</p></td>
</tr>
</tbody>
</table>

Table 5-12 Serial Communication Module (of Crevis)

<table>
<tbody>
<tr class="odd">
<td><p><strong>NO</strong></p></td>
<td><p><strong>Model Name</strong></p></td>
<td><p><strong>Specification</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>M5212</p></td>
<td><p>RS232 Serial Interface, 2channels Full Duplex</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>M5232</p></td>
<td><p>RS485 Serial Interface, 2channels Full Duplex</p></td>
</tr>
</tbody>
</table>
# 6. Periodic Inspections

The periodic inspection of the controller is designed to minimize the occurrence of failures and to maintain the performance continuously. This section describes the cautions and contents of works during the periodic inspection. # 6.1. Inspection Schedule 

Inspections should be carried out according to the schedule shown in the figure below. Periodic inspections are designed to prevent failures in advance and to secure safety and maintain accuracy even when the controller and manipulator are used for a long time. Periodic inspections are absolutely necessary and must be conducted even during normal operation.

![](../_assets/그림_6.1_점검_일정.png  )

Figure 6.1 Inspection Schedule
# 6.2. General Cautions for Periodic Inspections

* 	The inspection work should be conducted by a person who has completed the courses implemented at the robot training center by our company.

*	Before carrying out inspection works, check the parts, tools, drawings, etc. necessary for the work.

*	Use the specialized replacement parts designated by our company.

*	Turn off the power when inspecting the manipulator.

*	When conducting works while keeping the door open, turn off the primary power and take precautions to prohibit dust, etc. to fly into the surrounding area.

*	When required to touch the parts of the controller, you should take special care not to allow the IC to be destroyed by static electricity (Be careful also when contacting the connector).

*	When performing periodic inspections while operating the manipulator, take precautions to prohibit anyone from entering inside the operation range.

*	You should measure the voltage at a designated place and take precautions for electric shock and short-circuiting.

*	Do not inspect the robot and the controller at the same time. 

*	After inspection, you must perform a trial-operation to check the operation of the robot before performing the normal operation.

# 6.3. General Inspections 

Table 6-1 Daily Inspection 

<table>
<thead>
  <tr>
    <th>No.</th>
    <th>Elements to inspect</th>
    <th>Items to inspect</th>
    <th>Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">1</td>
    <td rowspan="3">Controller</td>
    <td>Are the display lamps normal?</td>
    <td>Check with your own eyes.</td>
  </tr>
  <tr>
    <td>Is the door closed properly?</td>
    <td>Check with your own eyes.</td>
  </tr>
  <tr>
    <td>Is there any problem with the screen of the teach pendant?</td>
    <td>Check with your own eyes.</td>
  </tr>
  <tr>
    <td rowspan="4">2</td>
    <td rowspan="4">Manipulator</td>
    <td>Is there any noise during the operation?</td>
    <td>Listen with your own ears.</td>
  </tr>
  <tr>
    <td>Is there any loosening of the screw at the front-end connection part?</td>
    <td>Fasten.</td>
  </tr>
  <tr>
    <td>Is there any scratch, contamination, or damage to the wiring and wire harness of the manipulator?</td>
    <td>Check with your own eyes.</td>
  </tr>
  <tr>
    <td>Is there any dirt or obstacle that causes damage to the manipulator?</td>
    <td>Check with your own eyes, then clean.</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Others</td>
    <td>Is there any interference with the surrounding area of the controller and manipulator?</td>
    <td>Check with your own eyes.</td>
  </tr>
</tbody>
</table>
# 6.4. First Inspection (Inspection When Reaching 750 Hours) 

Table 6-2 First Inspection 

<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>Elements to Inspect</strong></p></td>
<td><p><strong>Items to Inspect</strong></p></td>
<td><p><strong>Remarks</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>External and main screws</p></td>
<td><p>Loosening of screws </p></td>
<td><p>Fasten.</p></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>Electric wiring connectors and wire harnesses of the manipulator</p></td>
<td><p>Loosening of connectors</p></td>
<td><p>Fasten.</p></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>Screws for fastening the dogs and limit switches</p></td>
<td><p>Loosening of screws</p></td>
<td><p>Fasten.</p></td>
</tr>
</tbody>
</table>
# 6.5. Cyclic Inspections

Table 6-3 Cyclic Inspections 

<table>
<thead>
  <tr>
    <th rowspan="2">No.</th>
    <th colspan="3">Cycle</br>(Months)</th>
    <th rowspan="2">Elements to Inspect </th>
    <th rowspan="2">Items to Inspect</th>
    <th rowspan="2">Remarks</th>
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
    <td>Packing of the door</td>
    <td>‧Checking for deformation and detachment</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4">2</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">Back</td>
    <td>‧Checking dust on and rotation of the cooling fan blade part</td>
    <td></td>
  </tr>
  <tr>
    <td>‧Checking the regenerative discharge resistor for damage and dust</td>
    <td></td>
  </tr>
  <tr>
    <td>‧Checking the transformer room for any heat using the sense of touch, and then cleaning the room</td>
    <td></td>
  </tr>
  <tr>
    <td>‧Checking the transformer terminal block for any loosening and damage</td>
    <td></td>
  </tr>
  <tr>
    <td>3</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>Wire harness</td>
    <td>‧Checking the connectors for any loosening and damage</td>
    <td></td>
  </tr>
  <tr>
    <td>4</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>Motor drive</td>
    <td>‧Checking the connectors and terminals for any loosening and damage </td>
    <td></td>
  </tr>
  <tr>
    <td>5</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>Connectors of each board</td>
    <td>‧Checking for any loosening using the sense of touch</td>
    <td></td>
  </tr>
  <tr>
    <td>6</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>Operation panel</td>
    <td>‧Checking the status of buttons and switches</td>
    <td></td>
  </tr>
  <tr>
    <td>7</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>The whole controller</td>
    <td>‧Cleaning dust</td>
    <td></td>
  </tr>
  <tr>
    <td>8</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>Nameplate</td>
    <td>‧Inspecting various nameplates</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4">9</td>
    <td rowspan="4"></td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">Voltage measurement</td>
    <td>‧Voltage of the primary power</td>
    <td rowspan="4"></td>
  </tr>
  <tr>
    <td>‧CNFN1 B2-C2</td>
  </tr>
  <tr>
    <td>‧CNPB1 PB-MB</td>
  </tr>
  <tr>
    <td>‧CN24VB1 P24B-24GND</td>
  </tr>
  <tr>
    <td>10</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>Grounding</td>
    <td>‧Checking the terminals for any loosening and detachment</td>
    <td></td>
  </tr>
  <tr>
    <td>11</td>
    <td></td>
    <td>◎</td>
    <td>◎</td>
    <td>Battery</td>
    <td>‧Checking the voltage and replacing the battery Periodically</td>
    <td>Main board LEDs</td>
  </tr>
  <tr>
    <td rowspan="4">12</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">◎</td>
    <td rowspan="4">Teach pendant</td>
    <td>‧Inspecting the exterior and checking the connector connection part</td>
    <td></td>
  </tr>
  <tr>
    <td>‧LCD Display</br>Checking the status of the LCD display
</td>
    <td></td>
  </tr>
  <tr>
    <td>‧Checking the display of LEDs</td>
    <td></td>
  </tr>
  <tr>
    <td>‧Checking the status of the buttons, switches, and LEDs</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="5">13</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td rowspan="5">Safety-related parts</td>
    <td>‧Checking the emergency stop switch (on the controller and teach pendant)</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>‧Checking the main power circuit breaker switch (NFB1)</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>‧Checking the Enable device of the teach pendant</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>‧Checking the circuit protector (CP1)</td>
    <td></td>
  </tr>
  <tr>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>‧Checking the magnetic contacts (MC1, MC2)
</td>
    <td></td>
  </tr>
  <tr>
    <td>14</td>
    <td>◎</td>
    <td>◎</td>
    <td>◎</td>
    <td>Safety-related board</td>
    <td>‧Checking the BD630 (Connectors, LEDs)</td>
    <td></td>
  </tr>
</tbody>
</table>
# 6.6. Inspection When Going on a Long Vacation

When going on a long vacation, you should check the following items first before turning off the controller of the robot.

(1)	Check whether the yellow LED (BATLOW) for battery discharge detection on the main board is turned on. The yellow LED will be turned on if there is a problem with the battery. In this case, replace the battery with a battery of rated capacity. If the controller input power is turned off while there is a problem with the battery, various programs and integer data in the board will be removed after about seven days. Therefore, you must back them up using HRView or a USB memory.

(2)	Check if the door of the controller is secured.

# 6.7. Maintenance Parts 

The characteristics of individual parts are described below. 

**Maintenance Parts of the Category A**

{% hint style="info" %}
These are the important parts to be prepared for daily maintenance and inspection.
{% endhint %}


To maintain normal operation, the parts of the category A-2 and parts of the category A-3 are the minimum necessary parts, and at least one set of each group should be prepared.


Table 6-4 Inspection of Maintenance Parts of the Category A 


<table>
<thead>
  <tr>
    <th>Type</th>
    <th>Contents</th>
    <th>Remarks (Reference)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Maintenance parts of the category A-1</td>
    <td>Spare parts for standard parts</td>
    <td></td>
  </tr>
  <tr>
    <td>Maintenance parts of the category A-2</td>
    <td>Important backup parts</td>
    <td></td>
  </tr>
  <tr>
    <td>Maintenance parts of the category A-3</td>
    <td>Periodic replacement parts</td>
    <td></td>
  </tr>
</tbody>
</table>

Table 6-5 Maintenance Parts of the Category A-1 (Spare Parts for Standard Parts) 

<table>
<thead>
  <tr>
    <th>No.</th>
    <th>Part name</th>
    <th>Type</th>
    <th>Maker</th>
    <th>Quantity(EA)</th>
    <th>Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>Fuse (F1,F2)</td>
    <td>0218005</td>
    <td>Littlefuse</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Fuse (F3,F4)</td>
    <td>0218005</td>
    <td>Littlefuse</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
  <tr>
    <td>3</td>
    <td>Fuse (F5,F6)</td>
    <td>0218005</td>
    <td>Littlefuse</td>
    <td>2</td>
    <td>BD6C2</td>
  </tr>
</tbody>
</table>

Table 6-6 Maintenance Parts of the Category A-2 (Important Backup Parts) 

<table>
<thead>
  <tr>
    <th>No.</th>
    <th>Part name</th>
    <th>Type</th>
    <th>Maker</th>
    <th>Quantity(EA)</th>
    <th>Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>1</td>
    <td>Motor drive</td>
    <td>H6D6X<br>H6D6A</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Large-sized robot</br>Medium-sized<br>Small-sized robot</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Main control module</td>
    <td>H6COM</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td>3</td>
    <td>Teach pendant</td>
    <td>TP600</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td></td>
  </tr>
  <tr>
    <td>4</td>
    <td>Power supply module</td>
    <td>H6PSM30<br>H6PSM15</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Large-sized robot</br>Medium-sized robot<br>Small-sized robot</td>
  </tr>
  <tr>
    <td rowspan="3">5</td>
    <td rowspan="3">Boards</td>
    <td>BD640</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Servo board</td>
  </tr>
  <tr>
    <td>BD632</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Safety IO board</td>
  </tr>
  
</tbody>
</table>

Table 6-7 Maintenance Parts of the Category A-3 (Periodic Replacement Parts) 

<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>Part name</strong></p></td>
<td><p><strong>Type</strong></p></td>
<td><p><strong>Maker</strong></p></td>
<td><p><strong>Quantity(EA)</strong></p></td>
<td><p><strong>Remarks</strong></p></td>
</tr>
<tr class="even">
<td><p>1</p></td>
<td><p>Battery(3.6V AA Size)</p></td>
<td><p>ER6V-T1</p></td>
<td><p>TOSHIBA (JAPAN)</p></td>
<td><p>1</p></td>
<td><p>Replace it every two years</p></td>
</tr>
</tbody>
</table>

**Maintenance Parts of the Category B**

{% hint style="info" %}
These are the maintenance parts to be prepared when multiple units are purchased.
{% endhint %}


Table 6-8 Maintenance Parts of the Category B 

<table>
<tbody>
<tr class="odd">
<td><p><strong>Type</strong></p></td>
<td><p><strong>Contents</strong></p></td>
<td><p><strong>Remarks (Reference)</strong></p></td>
</tr>
<tr class="even">
<td><p>Maintenance parts of the category B-1</p></td>
<td><p>Parts that should be purchased from Hyundai Robotics</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Maintenance parts of the category B-2</p></td>
<td><p>Parts that can be purchased directly from the parts maker</p></td>
<td></td>
</tr>
</tbody>
</table>

Table 6-9 Maintenance Parts of the Category B-1 (Parts that should be purchased from Hyundai Robotics)

<table>
<thead>
  <tr>
    <th>No.</th>
    <th>Part Name</th>
    <th>Type</th>
    <th>Maker</th>
    <th>Quantity(EA)</th>
    <th>Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">1</td>
    <td rowspan="3">Wire harness</td>
    <td>CMC1</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Large-sized/Medium-sized/Small-sized</td>
  </tr>
  <tr>
    <td>CMC2</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Large-sized/Medium-sized</td>
  </tr>
  <tr>
    <td>CEC1</td>
    <td>Hyundai Robotics</td>
    <td>1</td>
    <td>Large-sized/Medium-sized/Small-sized</td>
  </tr>
</tbody>
</table>

Table 6-10 Maintenance Parts of the Category B-2 (Parts that can be purchased directly from the parts maker)

<table>
<tbody>
<tr class="odd">
<td><p><strong>No.</strong></p></td>
<td><p><strong>Part Name</strong></p></td>
<td><p><strong>Type</strong></p></td>
<td><p><strong>Maker</strong></p></td>
<td><p><strong>Quantity(EA)</strong></p></td>
<td><p><strong>Remarks</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>1</strong></p></td>
<td><p>No fuse breaker (NFB)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>1</p></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>2</strong></p></td>
<td><p>Magnetic contact (MC1, MC2)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>2</p></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>3</strong></p></td>
<td><p>Circuit protector (CP1)</p></td>
<td><p>-</p></td>
<td><p>-</p></td>
<td><p>1</p></td>
<td></td>
</tr>
</tbody>
</table>

![](../_assets/6.7._보수_부품_항목-보존온도.png  )
# Appendices
# Rules on Occupational Safety and Health Standards, and Notice for Safety Inspection

The industrial robot should be installed in consideration of the inspection standards, both of the Rules on Occupational Safety and Health Standards and of the Notice for Safety Inspection (if subject to inspection).

"[Rules on Occupational Safety and Health Standards](https://hrbook-hrc.web.app/#/view/rules-on-occupational-safety-and-health-standards/korean/README)"
# Quality Assurance

"[Quality Assurance](https://hrbook-hrc.web.app/#/view/quality-assurance/korean/README)"
