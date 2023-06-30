# p{olyline}-c{lose}
pcdc geom{etry} c{reate} <span style='color: red;'>p{olyline}-c{lose}</span>
> **描述：**根据多个节点坐标生成封闭折线。最少需要三个节点。

> 
> **值：**
> 
> v1（[vector](数据类型/vector/)，第一个节点坐标）
> 
> v1（[vector](数据类型/vector/)，第二个节点坐标）
> 
> ...（[vector](数据类型/vector/)，多个节点坐标）

**子关键词：**[as-l{ayer}](geom{etry}/c{reate}/p{olyline}-c{lose}/as-l{ayer}/)，


**举例：**
```
#下列命令生成5节点封闭折线
p0=(0,0)
p1=(2,0)
p2=(3,1)
p3=(9,5)
p4=(5,9)
pcdc geometry create polyline-close [p0] [p1] [p2] ...  #continuing
[p3] [p4] as-layer 'close-polyline'

```
