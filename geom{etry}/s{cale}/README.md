# s{cale}
pcdc geom{etry} <span style='color: red;'>s{cale}</span>
> **描述：**按比例缩放几何体

> 
> **值：**
> 
> v（[vector](数据类型/vector/)，沿X，Y方向缩放的比例）

**子关键词：**[l{ayer}](geom{etry}/s{cale}/l{ayer}/)，


**举例：**
```
#下列命令在X方向缩放比例为2.0，Y方向缩放比例为1.0对创建的圆进行缩放
pcdc geometry create circle c (0,0) rad 5.0 seg-l 1.0 as-layer 'circle'
pcdc geometry scale (2,1) layer 'circle'

```
