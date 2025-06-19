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
* These are maintenance parts to be prepared when multiple units are purchased.