# 4.3.2.1. Overview

The Servo/Safety Module(BD642) performs both servo control and safety functions within the robot controller. The servo control function supports simultaneous control of up to eight axes, consisting of six primary robot axes and two auxiliary axes.

The servo control system is composed of several functional blocks. These include an input stage that receives feedback signals required for motor control(such as current sensor signals and position feedback signals), a processing unit consisting of an MCU and FPGA that executes the motor control algorithms(including position, velocity, torque, and current control) and a power control stage that controls and monitors the power devices used for servo operation, such as the IPM, rectifier diodes, DC link, and brake circuits.

In addition to motion control, the module provides the safety functions required by the robot controller. For safety implementation, the MCU is configured in a dual-channel architecture to ensure reliable processing of safety functions. This architecture supports Safe Torque Off (STO) handling as well as the processing of safety-related input and output signals.

The module also provides communication and signal interfaces required for integration with other components of the robot controller system. These include interfaces for the T/P(Teach Pendant), BD671(PROFIsafe) board, Main COM, BD604(Backplane) board, BD680(Optional Safety I/O) board and BD6C3 (Power Distribution) board.