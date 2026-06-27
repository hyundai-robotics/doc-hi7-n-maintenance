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