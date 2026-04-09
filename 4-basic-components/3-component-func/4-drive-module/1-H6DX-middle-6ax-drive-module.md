# 4.3.4.1. H6D6X (中型 6 轴集成驱动模块)

驱动模块执行功率放大功能，使电流根据伺服板的电流命令流向电动机的各个相。六轴集成驱动模块可以同时驱动六个电动机，其配置如下。

从电源模块进入的三相电流通过二极管模块整流，然后转化为直流电并储存在平滑电容中。当机器人的电动机速度减速时，电动机产生的电能将通过IGBT和电阻消耗。相关配置如下。

表 4-14 H6D6X 的配置（中型 6 轴集成驱动模块）

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
    <td>生成 IPM 栅极信号</td>
  </tr>
  <tr>
    <td>栅极电源模块</td>
    <td>传递栅极电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流经电动机的电流</td>
  </tr>
  <tr>
    <td>再生控制</td>
    <td>当 PN 电压升高时驱动 IGBT</td>
  </tr>
  <tr>
    <td>错误检测部分</td>
    <td>检测 PN 过电压、再生放电电阻过热和 PN 欠电压错误</td>
  </tr>
  <tr>
    <td>高压电容器</td>
    <td>平滑直流电</td>
  </tr>
  <tr>
    <td rowspan="2">BD652<br>(接口板)</td>
    <td>序列联锁部分</td>
    <td>序列状态与伺服开信号之间的联锁</td>
  </tr>
  <tr>
    <td>专用 IO 端子块</td>
    <td>控制器内部的保留 IO 端口</td>
  </tr>
  <tr>
    <td rowspan="4">其他部分</td>
    <td>散热器</td>
    <td>将功率元件产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>整流部分</td>
    <td>将交流输入电源整流以生成驱动电动机的直流电</td>
  </tr>
  <tr>
    <td>再生 IGBT</td>
    <td>执行再生放电</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换用于驱动三相电动机的电源</td>
  </tr>
</tbody>
</table>

■ **中型 6 轴集成驱动模块的型号配置**

![](../../../_assets/중형_6축_일체형_드라이브모듈_형번_구성_en.png)

表 4-15 中型 6 轴集成驱动模块的类型符号 

<table>
<tbody>
<tr class="odd">
<td><p><strong>类别</strong></p></td>
<td><p><strong>类型符号</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Hi6 中型 6 轴驱动模块</strong></p></td>
<td><p>H6D6X</p></td>
</tr>
</tbody>
</table>

表 4-16 中型 6 轴集成驱动模块的规格

<table>
<thead>
  <tr>
    <th>配置</th>
    <th colspan="2">分类</th>
    <th colspan="2">应用 </th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">IPM 容量</td>
    <td>3X</td>
    <td>3Y</td>
    <td>HS180, HS220, HH300, HH050</td>
    <td rowspan="2">6 轴集成 </td>
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
    <td colspan="2">每月生产单位数量：1~999</td>
  </tr>
</tbody>
</table>

表 4-17 中型 6 轴驱动模块的 IPM 符号 

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
    <td rowspan="6">中型 6 轴的驱动模块</td>
    <td>X</td>
    <td>(IPM 电流额定值) 100A</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>(IPM 电流额定值) 75A</td>
  </tr>
   <tr>
    <td>Z</td>
    <td>(IPM 电流额定值) 50A</td>
  </tr>
</tbody>
</table>

表 4-18 中型 6 轴驱动模块的霍尔传感器符号 

<table>
<thead>
  <tr>
    <th>驱动模型</th>
    <th>霍尔传感器符号（规格）</th>
    <th>满刻度电流（Im）</th>
    <th>IPM 规格<br>(额定电流)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">中型 6 轴的驱动模块</td>
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
驱动模块根据机器人的类型有所不同，因此更换时必须检查类型。
{% endhint %}


![](../../../_assets/그림_4_20_BD651V60_부품_배치도.PNG)</br></br>
![](../../../_assets/그림_4_21_BD651V70_부품_배치도.PNG)</br></br>

图 4.20 BD651V60、BD651V70 的部件布置图</br></br>

表 4-19 BD651 连接器的描述

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
<td><p>BD652 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNRST</strong></p></td>
<td><p>三相电源输入</p></td>
<td><p>电子模块的 CNRST</p></td>
</tr>
<tr class="even">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换器部分错误信号</p></td>
<td><p>BD652 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNDR</strong></p></td>
<td><p>再生放电电源输出</p></td>
<td><p>再生放电电阻</p></td>
</tr>
<tr class="even">
<td><p><strong>CNTR</strong></p></td>
<td><p>再生放电电阻过热检测</p></td>
<td><p>再生放电电阻温度传感器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNM1~3</strong></p></td>
<td><p>轴 1 到轴 3 的电动机驱动输出</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="even">
<td><p><strong>CNM4~6</strong></p></td>
<td><p>轴 4 到轴 6 的电动机驱动输出</p></td>
<td><p>CMC2</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPN7~8</strong></p></td>
<td><p>用于额外轴的驱动模块的直流电源</p></td>
<td><p>用于可选额外轴的驱动模块的 CNPN。</p></td>
</tr>
<tr class="even">
<td><p><strong>CNFG1</strong></p></td>
<td><p>轴 1 到轴 3 的框架接地</p></td>
<td><p>CMC1</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNFG2</strong></p></td>
<td><p>轴 4 到轴 6 的框架接地</p></td>
<td><p>CMC2</p></td>
</tr>
</tbody>
</table>

表 4-20 BD651 的 LED 描述

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
<td><p>当磁接触驱动时将打开</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当转换器部分的控制电压正常时将打开</p></td>
</tr>
<tr class="even">
<td><p><strong>DR</strong></p></td>
<td><p>红色</p></td>
<td><p>当再生放电运行时将打开</p></td>
</tr>
<tr class="odd">
<td><p><strong>PN</strong></p></td>
<td><p>红色</p></td>
<td><p>当 PN 电压高于 42V 时将打开</p></td>
</tr>
<tr class="even">
<td><p><strong>RYON</strong></p></td>
<td><p>红色</p></td>
<td><p>当 PN 放电运行时将关闭</p></td>
</tr>
</tbody>
</table>

![](../../../_assets/그림_4_22_BD652V60_부품_배치도.PNG)</br></br>

![](../../../_assets/그림_4_23_BD652V70_부품_배치도.PNG)</br></br>

图 4.21 BD652V60、BD652V70 的部件布置图

表 4-21 BD652 连接器的描述

<table>
<tbody>
<tr class="odd">
<td><p><strong>名称</strong></p></td>
<td><p><strong>用途</strong></p></td>
<td><p><strong>外部设备连接</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>CNBS1~3</strong></p></td>
<td><p>用于 8 轴的 PWM 信号和 IPM 错误信号<br>转换器部分错误信号</p></td>
<td><p>BD640 的板对板连接器</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNPWM1~6</strong></p></td>
<td><p>用于各个轴的 PWM 信号和 IPM 错误信号</p></td>
<td><p>BD651 的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>CNPWM7~8</strong></p></td>
<td><p>用于额外轴的 PWM 信号和 IPM 错误信号</p></td>
<td><p>用于额外轴驱动模块 (BD658 或 BD659) 的 CNPWM</p></td>
</tr>
<tr class="odd">
<td><p><strong>CNCVT</strong></p></td>
<td><p>转换器部分错误信号</p></td>
<td><p>BD651 的板对板连接器</p></td>
</tr>
<tr class="even">
<td><p><strong>TBIO</strong></p></td>
<td><p>仅保留用于 IO 端子块</p></td>
<td><p>保留</p></td>
</tr>
</tbody>
</table>

表 4-22 BD652 的 LED 描述

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
<td><p>当磁接触驱动时将打开</p></td>
</tr>
<tr class="odd">
<td><p><strong>POW</strong></p></td>
<td><p>绿色</p></td>
<td><p>当控制电源正常时将打开</p></td>
</tr>
</tbody>
</table>