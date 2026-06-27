# 5.5.1 概述 

在 Hi7 中，'用户 DIO 板 (BD681)' 和 '扩展 DIO 板 (BD682)' 可以用于处理通用 I/O 信号并同步传送带编码器。

{% hint style="info" %}
在本手册中，DIO 指数字输入和输出。
{% endhint %}

'扩展 DIO 板 (BD682)' 不能单独使用，必须与 '用户 DIO 板 (BD681)' 一起使用。

表 5-18 板规范 
<table>
<thead>
    <tr>
        <th style="width: 50px; text-align: center;">
            No.
        </th>
        <th style="width: 110px; text-align: center;">
             板名称<br>
            (板标识符)
        </th>
        <th style="width: 300px; text-align: center;">
            板功能
        </th>
    </tr>
</thead>
<tbody>
    <tr>
        <td style="text-align: center;">
            <strong>1</strong>
        </td>
        <td style="text-align: center;">
            用户 DIO 板<br>
            (BD681)
        </td>
        <td> 
             - 16 通道通用输入<br>
             - 16 通道通用输出
        </td>
    </tr>
    <tr>
        <td style="text-align: center;">
            <strong>2</strong>
        </td>
        <td style="text-align: center;">
            用户 DIO 板<br>
            (BD682)
        </td>
        <td> 
             - 16 通道通用输入<br>
             - 16 通道通用输出<br> 
             - 2 通道传送带编码器<br> 
             - 不能独立使用（必须与 BD681 一起使用）
        </td>
    </tr>
</tbody>
</table>

<br>
通过使用两个 BD681 和一个 BD682，最多可以控制 48 个输入/输出通道。
<br><br>