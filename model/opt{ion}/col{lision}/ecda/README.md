# ecda
pcdc model opt{ion} col{lision} <span style='color: red;'>ecda</span>
> **描述：**启用或禁用有效接触判断算法（Efficient Contact Detect Activation)。如果启用该算法，则接触计算只发生在真实破裂面之间，这可以缩短计算时间，但由于节理在压缩状态下在未破裂前就有重叠而不计算由于重叠产生的额外的接触力，破裂后计算的接触力可能会有较大的“跳跃”而影响非连续计算结果；
						 否则，需要禁用该算法使接触计算也发生在未破裂之前的节理面之间，这会一定程度提高计算准确性，但会延长计算时间。 省缺情况下启用该算法

> 
> **值：**
> 
> b（[bool](数据类型/bool/)，是否启用?）



**举例：**
```
pcdc model collision ecda off
#该命令禁用有效接触判断算法

```
