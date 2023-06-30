# init{ialize}  < [range](range/) >
pcdc e{lement} <span style='color: red;'>init{ialize}</span>
> **描述：**初始化单元如果给定了初始值s0和梯度系数(比如g)，那么单元在某方向的初始值由下列公式计算得到(三维)\ns0+g.X*cx+g.Y*cy+g.Z*cz\n其中cx，cy，cz为单元中心坐标值

**子关键词：**[s{stress}-xx](e{lement}/init{ialize}/s{stress}-xx/)，[s{stress}-yy](e{lement}/init{ialize}/s{stress}-yy/)，[s{stress}-xy](e{lement}/init{ialize}/s{stress}-xy/)，


**举例：**
```
pcdc element init s-xx 0.0 s-yy 1e6 range y 0 100.0
#该命令把Y从0到100.0范围内的单元X方向应力初始化为0.0，Y方向应力初始化为1e6

```
