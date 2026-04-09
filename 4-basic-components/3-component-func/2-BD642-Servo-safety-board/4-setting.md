# 4.3.2.4. 配置设备

下图显示了 Servo/Safety Module(BD642) 上配置(开关)设备的位置。
下表描述了每个配置设置的功能。

![](../../../_assets/BD642_PCB_설정_r1.png)   
图 4.3.2.4-1 Servo/Safety Module(BD642) 的配置设备布局

{% hint style="info" %}
以下设置不得被用户更改。
仅在通过 JTAG 接口进行 FPGA 重新编程时参考此部分。
{% endhint %}

表 4.3.2.4-1 SW1 配置设置的描述(BD642)
<table>
<thead>
  <tr>
    <th><strong>编号</strong></th>
    <th><strong>名称</strong></th>
    <th><strong>设置状态</strong></th>
    <th><strong>描述</strong></th>
    <th><strong>备注</strong></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="2">①</td>
    <td rowspan="2">SW1</td>
    <td><img src="../../../_assets/BD642_플래쉬메모리_부팅모드.png" width="100"></td>
    <td>闪存启动模式</td>
    <td>出厂默认设置</td>
  </tr>
  <tr>
    <td><img src="../../../_assets/BD642_JTAG프로그램_다운로드모드.png" width="100"></td>
    <td>JTAG 程序下载模式</td>
    <td>-</td>
  </tr>
</table>
</tbody>