# p{olyline}
pcdc geom{etry} c{reate} <span style='color: red;'>p{olyline}</span>
> **描述：**根据多个节点坐标生成非封闭折线。最少需要二个节点。

> 
> **值：**
> 
> v1（[vector](数据类型/vector/)，第一个节点坐标）
> 
> v1（[vector](数据类型/vector/)，第二个节点坐标）
> 
> ...（[vector](数据类型/vector/)，多个节点坐标）

**子关键词：**[as-l{ayer}](geom{etry}/c{reate}/p{olyline}/as-l{ayer}/)，


**举例：**
```
#下列命令生成5节点非封闭折线
p0=(0,0,0)
p1=(2,0,0)
p2=(3,1,0)
p3=(9,5,0)
p4=(5,9,0)
pcdc geometry create polyline [p0] [p1] [p2] ...  #continuing
[p3] [p4] as-layer 'close-polyline'

```
