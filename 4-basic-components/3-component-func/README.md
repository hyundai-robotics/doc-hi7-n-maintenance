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