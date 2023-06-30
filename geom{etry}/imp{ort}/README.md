# imp{ort}
pcdc geom{etry} <span style='color: red;'>imp{ort}</span>
> **描述：**从外部文件导入几何。自动根据文件后缀判断文件类型，目前支持导入AutoCAD的.dxf文件和.stl文件

> 
> **值：**
> 
> s（[string](数据类型/string/)，文件名）

**子关键词：**[as-l{ayer}](geom{etry}/imp{ort}/as-l{ayer}/)，


**举例：**
```
#下列命令从文件"test.dxf"导入几何并命名为"test"
pcdc geometry import 'test.dxf' as-layer 'test'

```
