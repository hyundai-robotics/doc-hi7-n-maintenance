# 5.4.3. 指示设备

(1) 板上顶部指示灯   

下图显示了选项安全IO模块(BD680)上指示LED的位置。下表描述了每个指示灯的含义。

![](../../_assets/BD680_PCB_상태.png)   
图 5.4.3-1 选项安全IO模块(BD680)上指示LED的布局

表 5.4.3-1 选项安全IO模块(BD680)的指示说明
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
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
      <br>操作 1: 检查A通道输入电源(24V)
      <br>操作 2: 检查保险丝(FS1)
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
      <br>操作 1: 检查B通道输入电源(24V)
      <br>操作 2: 检查保险丝(FS2)
    </td>
</table>
</tbody>

(2) 前面板指示灯   

下图显示了选项安全I/O模块(BD680)的前面板指示灯。下表描述了每个指示灯的功能和含义。

![](../../_assets/BD680_전면표시장치.png)   
图 5.4.3-2 前面板指示灯布局–选项安全I/O模块(BD680)   

表 5.4.3-2 前面板指示灯说明–选项安全I/O模块(BD680) 
<table>
<thead>
  <tr>
    <th><strong>No.</strong></th>
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
    <td>已保留</td>
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