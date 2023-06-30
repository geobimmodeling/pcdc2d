# c{ycle}-o{ption}
pcdc model <span style='color: red;'>c{ycle}-o{ption}</span>
> **描述：**设置模型求解时每一循环计算步各计算模块的时间步长和迭代步， 通常在耦合计算时设置

**子关键词：**[m{echanical}](model/c{ycle}-o{ption}/m{echanical}/)，[t{hermal}](model/c{ycle}-o{ption}/t{hermal}/)，[ h{ydraulic}](model/c{ycle}-o{ption}/ h{ydraulic}/)，[p{roppant}-t{ransport}](model/c{ycle}-o{ption}/p{roppant}-t{ransport}/)，


**举例：**
```
pcdc model cycle-option mech t-s 1e-5 c-n 1000 therm t-s 1.0 c-n 500
#该命令设置模型每一循环计算步求解时，纯力学计算时间步长为1e-5,迭代1000，热力学计算时间步长为1.0,迭代500步

```
