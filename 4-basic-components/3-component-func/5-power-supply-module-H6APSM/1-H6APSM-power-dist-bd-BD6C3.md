# 4.3.5.1. H7PSM 和电源分配板(BD6C3)

H7PSM (Hi7-N 控制器电源模块) 模块负责控制器供电的开闭和分配。以下图展示了电气模块的内部和外部，其配有各种连接器和保险丝。

![](../../../_assets/그림_4.26_H6APSM(Hi6a-N_제어기_전원공급모듈)_외부_en.png  )<br>
图 4.34 H7PSM (Hi7-N 控制器电源模块) 外部<br>

以下图展示了与电机电源的三相交流电开闭、制动电源的生成及风扇驱动相关的交流控制电源的电源系统图。图中的电路图还展示了电源分配，例如供给控制模块的直流电源的 SMPS 电源。每个电源都连接了断路器 (CP) 或保险丝，以保护单独电路免受过流的影响。

![](../../../_assets/그림_4.27_Hi6a-N_제어기의_전원계통_en.png)<br>
图 4.35 Hi7-N 控制器的电源系统

表 4-35 电子模块保险丝的类型和使用
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
    <td>F1, F2, F3</td>
    <td>控制电源过流保护的保险丝(AC 220V)</td>
    <td>AC220V 8A</td>
  </tr>
  <tr>
    <td>FS17</td>
    <td>CMDCFAN 和 DCFAN2-5 GND 过流保护的保险丝</td>
    <td>7VAC/60VDC 7A</td>
  </tr>
  <tr>
    <td>FS18</td>
    <td>DCFAN2-5 过流保护的保险丝</td>
    <td>125VAC/125VDC 6.3A</td>
  </tr>
  <tr>
    <td>FS19</td>
    <td>控制模块冷却的直流风扇过流保护的保险丝</td>
    <td>125VAC/125VDC 0.315A</td>
  </tr>
</tbody>
</table>