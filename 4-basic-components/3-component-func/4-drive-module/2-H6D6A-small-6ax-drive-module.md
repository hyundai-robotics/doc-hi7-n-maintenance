# 4.3.4.2. H6D6A (小型6轴集成驱动模块)

驱动模块执行一种功率放大功能，允许电流根据伺服板的电流命令流向电机的各个相。六轴集成驱动模块可以同时驱动六个电机，配置如下。

从电源模块输入的三相电流通过二极管模块整流，然后转换为直流并存储在平滑电容中。当机器人的电机速度减速时，电机产生的电能将通过IGBT和电阻被消耗。相关配置如下。

表 4-23 H6D6A (小型6轴集成驱动模块) 的配置

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
    <td>生成IPM门信号</td>
  </tr>
  <tr>
    <td>门电源模块</td>
    <td>生成门电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测通过电机的电流</td>
  </tr>
  <tr>
    <td>再生控制</td>
    <td>当PN电压上升时打开IGBT</td>
  </tr>
  <tr>
    <td>错误检测部分</td>
    <td>检测过电压、再生电阻过热和欠电压错误</td>
  </tr>
  <tr>
    <td>高压电容</td>
    <td>平滑直流</td>
  </tr>
  <tr>
    <td rowspan="2">BD654<br>(接口板)</td>
    <td>顺序联锁部分</td>
    <td>在顺序状态和伺服启动信号之间联锁</td>
  </tr>
  <tr>
    <td>专用IO端子块</td>
    <td>控制器内部保留IO端口</td>
  </tr>
  <tr>
    <td rowspan="4">其他部件</td>
    <td>散热器</td>
    <td>将电力元件产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>整流部分</td>
    <td>将AC输入电源整流为DC电源以驱动电机</td>
  </tr>
  <tr>
    <td>再生IGBT</td>
    <td>执行再生放电</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换用于驱动三相电机的电源</td>
  </tr>
</tbody>
</table>

{% hint style="info" %}
驱动模块的类型因机器人而异，因此更换时必须检查类型。
{% endhint %}

■  **小型6轴集成驱动模块的型号配置**

![](../../../_assets/소형_6축_일체형_드라이브모듈_형번_구성_en.png)

表 4-24 小型6轴集成驱动模块的型号符号

<table>
<tbody>
<tr class="odd">
<td><p><strong>类别 </strong></p></td>
<td><p><strong>型号符号</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 小型6轴驱动模块</strong></p></td>
<td><p>H6D6A</p></td>
</tr>
</tbody>
</table>

表 4-25 小型6轴集成驱动模块的规格

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
    <td>IPM容量</td>
    <td>3A</td>
    <td>3D</td>
    <td>HA006B, HH020</td>
    <td>6轴集成 </td>
  </tr>
  <tr>
    <td>年份</td>
    <td colspan="2">00 ~ 99</td>
    <td colspan="2">生产年份：2000-2099</td>
  </tr>
  <tr>
    <td>月份</td>
    <td colspan="2">01 ~ 12</td>
    <td colspan="2">生产月份：一月-十二月</td>
  </tr>
  <tr>
    <td>序列号</td>
    <td colspan="2">001 ~ 999</td>
    <td colspan="2">每月生产单位数量：1~999</td>
  </tr>
</tbody>
</table>

表 4-26 小型IPM的容量

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
    <td rowspan="7">小型6轴的驱动模块</td>
    <td>A</td>
    <td>(IPM允许电流额定值) 30A</td>
  </tr>
  <tr>
    <td>D</td>
    <td>(IPM允许电流额定值) 10A</td>
  </tr>
</tbody>
</table>

表 4-27 小型IPM的霍尔传感器符号

<table>
<thead>
  <tr>
    <th>驱动型号</th>
    <th>霍尔传感器符号 (规格)</th>
    <th>满量程电流 (Im)</th>
    <th>IPM规格 (允许电流额定值)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="7">小型6轴的驱动模块</td>
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
驱动模块的类型因机器人而异，因此更换时必须检查类型。
{% endhint %}

![](../../../_assets/그림_4_24_BD653V60_부품_배치도.PNG  )

图 4.22 BD653V60 的部件布置图

表 4-28 BD653连接器的描述

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
<td><p>BD654的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>三相电源输入</p></td>
<td><p>电子模块的CNRST</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换器部分错误信号</p></td>
<td><p>BD654的板对板连接器</p></td>
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
<td><p>额外轴的驱动模块的直流电源</p></td>
<td><p>用于额外轴的驱动模块的CNPN</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG1, CNFG4</strong></p></td>
<td><p>电机的框架接地</p></td>
<td><p>CMC1</p></td>
</tr>
</tbody>
</table>

表 4-29 BD653的LED描述

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
<td><p>当磁铁接触驱动时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当转换器部分的控制电压正常时将被点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>红色</p></td>
<td><p>当再生放电正在操作时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>红色</p></td>
<td><p>当PN电压高于42V时将被点亮</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>红色</p></td>
<td><p>当PN放电操作开始时将熄灭</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4_25_BD654V60_부품_배치도.PNG  )

图 4.23 BD654的部件布置图</br></br>

表 4-30 BD654连接器的描述

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>8轴的PWM信号和IPM错误信号<br>转换器部分错误信号</p></td>
<td><p>BD640的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>各个轴的PWM信号和IPM错误信号</p></td>
<td><p>BD653的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>额外轴的PWM信号和IPM错误信号</p></td>
<td><p>额外轴的驱动模块 (BD 658或BD 659) 的CNPWM</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换器部分错误信号</p></td>
<td><p>BD653的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>仅保留IO端子块</p></td>
<td><p>保留</p></td>
</tr>
</tbody>
</table>

表 4-31 BD654 LED的描述

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
<td><p>当磁铁接触驱动时将被点亮</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当控制电源正常时将被点亮</p></td>
</tr>
</tbody>
</table>