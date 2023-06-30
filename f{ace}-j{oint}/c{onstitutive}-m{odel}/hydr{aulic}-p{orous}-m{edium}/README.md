# hydr{aulic}-p{orous}-m{edium}
pcdc f{ace}-j{oint} c{onstitutive}-m{odel} <span style='color: red;'>hydr{aulic}-p{orous}-m{edium}</span>
> **描述：**水力多孔介质本构模型。该本构模型实际赋给和该单元相连的面-节理，使得面-节理成为流体通道(Flow channel)

**子关键词：**[prop{erty}](f{ace}-j{oint}/c{onstitutive}-m{odel}/hydr{aulic}-p{orous}-m{edium}/prop{erty}/)，[range](range/)，


**举例：**
```
pcdc element c-model hydr-p-m f-den 1000 f-b 10e9 visc 1.0 leak-off false range group 't' set 'sample'
#该命令定义在命名"sample"类组名为"t"的单元的本构模型为水力多孔介质本构模型，其参数值分别为：
流体密度=1000
流体体积模量=10e9
运动粘度=1.0
渗流开关=false

```
