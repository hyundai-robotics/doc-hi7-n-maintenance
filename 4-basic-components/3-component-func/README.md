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
    <td>- 记录记录点并计算操作路径<br>- 程序和机器人整数的保存<br>- 教学挂件(T/P)通信<br>- LAN、USB 和串行 (RS232) 通信的连接</td>
  </tr>
  <tr>
    <td>伺服板(BD642)</td>
    <td>- 用于伺服控制的DSP<br>- 编码器连接（串行 I/F）<br>- 伺服电机的开/关输出<br>- 功能安全功能<br>- 顺序控制<br>- 系统 I/O<br>- 安全链路电路</td>    
  </tr>
  <tr>
    <td>背板(BD604)</td>
    <td>- 每块板的控制电源<br>- 与伺服安全板(BD642)的AMP信号连接<br>- 预充电/风扇继电器操作信号传输</td></td>
  </tr>
  <tr>
    <td>驱动模块<br>(驱动模块)</td>
    <td>大型/中型 6轴: H6D6X<br>小型 6轴: H6D6A<br>附加轴: H6D1X, H6D1Z</td>
    <td>- 生成电机驱动电源<br>- 再生放电<br>- 伺服电机功率放大电路<br>- 各种错误输出</td>
  </tr>
  <tr>
    <td>T/P<br>(教学挂件)</td>
    <td>TP630</td>
    <td>- 各种信息的显示 (LCD)<br>- 按钮输入和开关输入 (功能/慢走等)<br>- 紧急停止、启用和 T/P 开/关输入</td>
  </tr>
  <tr>
    <td>冷却设备</td>
    <td>风扇</td>
    <td>- 面板内部的空气循环<br>- 驱动模块的冷却</td>
  </tr>
  <tr>
    <td>电源模块</td>
    <td>H6PSM</td>
    <td>- 电机驱动电源的开/关<br>- 各种电源的分配</td>
  </tr>
</tbody>
</table>

※ 关于各控制器组件的类型，请参见“2.1 各控制器型号的详细配置。” 

![](../../_assets/그림_4_3_구성품%20위치.png)<br>
Figure 4.7 控制模块的组件<br>