# hydr{aulic}-p{orous}-p{roppant}-m{edium}
pcdc e{lement} c{onstitutive}-m{odel} <span style='color: red;'>hydr{aulic}-p{orous}-p{roppant}-m{edium}</span>
> **描述：**含支撑剂的水力多孔介质本构模型。该本构模型实际赋给和该单元相连的面-节理，使得面-节理成为流体通道(Flow channel)

**子关键词：**[prop{erty}](e{lement}/c{onstitutive}-m{odel}/hydr{aulic}-p{orous}-p{roppant}-m{edium}/prop{erty}/)，


**举例：**
```
pcdc element c-model hydr-p-m f-den 1000 f-b 10e9 visc 1.0 leak-off false p-den 2000 p-size 1e-4 p-s-f 1.0 p-c-l 1.0 p-m 1e7 range group 't' set 'sample'
#该命令定义在命名"sample"类组名为"t"的单元的本构模型为含支撑剂的水力多孔介质本构模型，其参数值分别为：
流体密度=1000
流体体积模量=10e9
运动粘度=1.0
渗流开关=false
支撑剂密度=2000
支撑剂尺寸=1e-4
支撑剂尺寸因子=1.0
支撑剂弹性模量=1e7

```
