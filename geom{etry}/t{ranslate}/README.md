# t{ranslate}
pcdc geom{etry} <span style='color: red;'>t{ranslate}</span>
> **描述：**平移几何体

> 
> **值：**
> 
> v（[vector](数据类型/vector/)，沿X，Y方向的平移量）

**子关键词：**[l{ayer}](geom{etry}/t{ranslate}/l{ayer}/)，


**举例：**
```
#下列命令平移创建的圆
pcdc geometry create circle c (0,0) rad 5.0 seg-l 1.0 as-layer 'circle'
pcdc geometry translate (10,0) layer 'circle'

```
