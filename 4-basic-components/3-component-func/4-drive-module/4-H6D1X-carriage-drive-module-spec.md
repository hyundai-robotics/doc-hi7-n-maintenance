# 4.3.4.4. H7D1X (载体驱动模块；可选)

驱动模块执行功率放大功能，允许电流根据伺服板的电流命令流向电机的各个相。载体驱动模块可以驱动100A或以下的一台电机，配置如下。

![](../../../_assets/그림_4_26_BD658V60_부품_배치도.PNG  )

图 4.24 H7D1X 的 BD658V60 部件布置图</br></br>

表 4-35 H7D1X 的配置

<table>
<thead>
  <tr>
    <th colspan="2">组件</th>
    <th>功能</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="3">BD658</br>(IPM 板)
</td>
    <td>逻辑部分</td>
    <td>将从驱动模块接收的六轴 PWM 信号转换为 IPM 的上下侧驱动信号，并处理错误</td>
  </tr>
  <tr>
    <td>栅极电源模块</td>
    <td>生成 IPM 栅极电源</td>
  </tr>
  <tr>
    <td>电流检测部分</td>
    <td>检测流经电机的电流</td>
  </tr>
  <tr>
    <td rowspan="2">其他部件</td>
    <td>散热器</td>
    <td>将 IPM 产生的热量释放到外部</td>
  </tr>
  <tr>
    <td>IPM</td>
    <td>转换用于驱动三相电机的电源</td>
  </tr>
</tbody>
</table>

表 4-36 H7D1X 的连接器描述

<table>
<thead>
  <tr>
    <th>名称</th>
    <th>用法</th>
    <th>外部设备连接</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>CNPWM</td>
    <td>PWM 信号和错误信号</td>
    <td>驱动模块 (BD652 或 BD654) 的 CNPWM7 或 CNPWM8，用于六轴</td>
  </tr>
  <tr>
    <td>CNM</td>
    <td>电机驱动输出</td>
    <td>AMC1 或 AMC2</td>
  </tr>
  <tr>
    <td>CNFG</td>
    <td>电机的框架接地</td>
    <td>AMC1 或 AMC2</td>
  </tr>
  <tr>
    <td>CNPN</td>
    <td>驱动直流电源输入</td>
    <td>驱动模块 (BD651 或 BD653) 的 CNPN7 或 CNPN8，用于六轴</td>
  </tr>
</tbody>
</table>