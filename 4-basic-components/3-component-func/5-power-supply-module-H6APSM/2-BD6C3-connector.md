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