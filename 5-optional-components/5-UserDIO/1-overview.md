# 5.5.1 Overview 

In Hi7, the 'user DIO board (BD681)' and 'extended DIO board (BD682)' can be used to handle general-purpose I/O signals and synchronize conveyor encoders. 

{% hint style="info" %}
In this manual, DIO refers to Digital Input and Output. 
{% endhint %}

The 'extended DIO board (BD682)' cannot be used independently and should be used together with the 'user DIO board (BD681)'. 

Table 5-18 Board Specifications 
<table>
<thead>
    <tr>
        <th style="width: 50px; text-align: center;">
            No.
        </th>
        <th style="width: 110px; text-align: center;">
             Board Name<br>
            (Board Identifier)
        </th>
        <th style="width: 300px; text-align: center;">
            Board Function
        </th>
    </tr>
</thead>
<tbody>
    <tr>
        <td style="text-align: center;">
            <strong>1</strong>
        </td>
        <td style="text-align: center;">
            User DIO board<br>
            (BD681)
        </td>
        <td> 
             - 16-channel general-purpose input<br>
             - 16-channel general-purpose output
        </td>
    </tr>
    <tr>
        <td style="text-align: center;">
            <strong>2</strong>
        </td>
        <td style="text-align: center;">
            User DIO board<br>
            (BD682)
        </td>
        <td> 
             - 16-channel general-purpose input<br>
             - 16-channel general-purpose output<br> 
             - 2-channel conveyor encoder<br> 
             - Cannot be used independently(should be used  with 
BD681)
        </td>
    </tr>
</tbody>
</table>

<br>
By using two BD681 and one BD682, up to 48 channels of input/output can be controlled. 
<br><br>
