# g{roup}  < [range](range/) >
pcdc e{lement} <span style='color: red;'>g{roup}</span>
> **描述：**定义单元组，如果没有定义所属的类(set)，则所属的类的省缺名称是"default"

> 
> **值：**
> 
> s（[string](数据类型/string/)，字符串定义组的名称）

**子关键词：**[s{et}](e{lement}/g{roup}/s{et}/)，


**举例：**
```
pcdc element group 'tunnel' set 'excavation' range x 0 1000.0
#该命令定义在X从0到1000.0范围内的单元的组是"tunnel",其所在的类是"excavation"

```
