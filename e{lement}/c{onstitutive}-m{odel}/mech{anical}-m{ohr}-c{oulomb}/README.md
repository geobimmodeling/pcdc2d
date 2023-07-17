# mech{anical}-m{ohr}-c{oulomb}
pcdc e{lement} c{onstitutive}-m{odel} <span style='color: red;'>mech{anical}-m{ohr}-c{oulomb}</span>
> **描述：**摩尔-库伦弹塑性本构模型

**子关键词：**[prop{erty}](e{lement}/c{onstitutive}-m{odel}/mech{anical}-m{ohr}-c{oulomb}/prop{erty}/)，


**举例：**
```
pcdc element c-model mech-m-c prop den 2700 y 10e9 p-r 0.3 coh 10e6 fri 30 dil 5 ten 1e6 range x 0 1000.0
#该命令定义在X从0到1000.0范围内的单元的本构模型为摩尔-库伦弹塑性本构模型，其参数值分别为：
#密度=2700
#杨氏模量=10e9
#泊松系数=0.3
#粘结力=10e6
#摩擦角=30度
#剪胀角=5度
#抗拉强度=1e6

```
