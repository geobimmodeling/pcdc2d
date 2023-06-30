# exp{ort}
pcdc geom{etry} <span style='color: red;'>exp{ort}</span>
> **描述：**导出选定的一个或多个几何到文件

> 
> **值：**
> 
> s1（[string](数据类型/string/)，第一个几何的层位名称）
> 
> s2（[string](数据类型/string/)，第二个几何的层位名称）
> 
> ...（[string](数据类型/string/)，多个几何的层位名称）

**子关键词：**[f{ile}](geom{etry}/exp{ort}/f{ile}/)，


**举例：**
```
#下列命令将几何"a1","a2","a3"导出到AutoCAD文件"a.dxf"
pcdc geometry export 'a1' 'a2' 'a3' file 'a.dxf'

```
