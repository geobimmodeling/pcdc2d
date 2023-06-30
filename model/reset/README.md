# reset
pcdc model <span style='color: red;'>reset</span>
> **描述：**重置模型求解时的计算开始时间、目前时间、以及计算时间步长

**子关键词：**[m{echanical}](model/reset/m{echanical}/)，[t{hermal}](model/reset/t{hermal}/)，[h{ydraulic}](model/reset/h{ydraulic}/)，[p{roppant}-t{ransport}](model/reset/p{roppant}-t{ransport}/)，


**举例：**
```
pcdc model reset mech s-time 0 c-time 10.0 t-s 1e-5 therm s-time 1.0 c-time 10.0 t-s 1.0
#该命令设置模型求解时，纯力学计算的开始时间为0，当前时间为10.0，时间步长为1e-5。热力学开始时间为1.0， 当前时间为10.0， 计算时间步长为1.0

```
