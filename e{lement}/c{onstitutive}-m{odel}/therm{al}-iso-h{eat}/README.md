# therm{al}-iso-h{eat}
pcdc e{lement} c{onstitutive}-m{odel} <span style='color: red;'>therm{al}-iso-h{eat}</span>
> **描述：**各向同性热力学本构模型。赋予该模型的单元成为热力学单元，相关的节点成为热力学节点

**子关键词：**[prop{erty}](e{lement}/c{onstitutive}-m{odel}/therm{al}-iso-h{eat}/prop{erty}/)，


**举例：**
```
pcdc element c-model therm-iso-h cond 100.0 cap 0.0 e-c 80.0 range group 't' set 'sample'
#该命令定义在命名"sample"类组名为"t"的单元的本构模型为各向同性热力学本构模型，其参数值分别为：
热导率=100.0
热容=0.0
热膨胀系数=80.0

```
