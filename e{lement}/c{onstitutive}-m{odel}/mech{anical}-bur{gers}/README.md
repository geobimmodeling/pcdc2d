# mech{anical}-bur{gers}
pcdc e{lement} c{onstitutive}-m{odel} <span style='color: red;'>mech{anical}-bur{gers}</span>
> **描述：**Burgers蠕变本构模型

**子关键词：**[prop{erty}](e{lement}/c{onstitutive}-m{odel}/mech{anical}-bur{gers}/prop{erty}/)，


**举例：**
```
pcdc element c-model mech-burgers prop density 1.0 kelvin-shear 1.0 kelvin-viscosity 2.0 bulk 1.0 maxwell-shear 2.0 maxwell-viscosity 3.0  range x 0 1000.0
#该命令定义在X从0到1000.0范围内的单元的本构模型为Burgers蠕变本构模型，其参数值分别为：
#密度=1.0
#Kelvin剪切模量=1.0
#Kelvin粘度=2.0
#体积模量=1.0
#Maxwell剪切模量=2.0
#Maxwell粘度=3.0

```
