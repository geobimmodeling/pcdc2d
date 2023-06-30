# dens{ify}  < [range](range/) >
pcdc e{lement} <span style='color: red;'>dens{ify}</span>
> **描述：**四叉树方法加密四边形单元模型。仅适用于模型的四边形单元，某四边形单元加密到给定大小，与之相邻的其他四边形单元按四叉树方法自动加密。

**子关键词：**[p{attern}](e{lement}/dens{ify}/p{attern}/)，[m{aximum}-l{ength}](e{lement}/dens{ify}/m{aximum}-l{ength}/)，


**举例：**
```
#下列命令生成一个四边形单元模型，并加密给定范围的单元
pcdc model new
#create a quad model
pcdc element create brick p0 (0,0) p1 (100,0) p2 (0,100) n 10 10 tri false
#create a circle 
pcdc geometry create circle c 50,50 rad 20 as-layer 'c'
#densify
pcdc element densify pattern 1 1 max-length 1.0 1.0 range geom-dis 'c' within 10.0
#define group of element
pcdc element group 'tunnel' range geom-loc 'c' r-dir 0,1 count 1

```
