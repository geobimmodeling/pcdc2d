# mech{anical}-{e}lastic-plastic
pcdc b{olt}-e{lement} c{onstitutive}-m{odel} <span style='color: red;'>mech{anical}-{e}lastic-plastic</span>
> **描述：**支护锚杆的弹塑性本构模型

**子关键词：**[prop{erty}](b{olt}-e{lement}/c{onstitutive}-m{odel}/mech{anical}-{e}lastic-plastic/prop{erty}/)，[range](range/)，


**举例：**
```
pcdc element c-model mech-iso-e den 2700 y 10e9 p-r 0.3 range x 0 1000.0
#该命令定义在X从0到1000.0范围内的单元的本构模型为各向同性线性弹性本构模型，其参数值分别为：
密度=2700
杨氏模量=10e9
泊松系数=0.3

```
