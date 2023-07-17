# leak-off
pcdc f{ace}-j{oint} c{onstitutive}-m{odel} hydr{aulic}-p{orous}-p{roppant}-m{edium} prop{erty} <span style='color: red;'>leak-off</span>
> **描述：**流体损失（泄露）开关。该开关表明是否流道（Flow channel）中的流体向周围基质渗流。如果Leak-off取值为true (或者on)，则会模拟计算节理在流体压力作用破裂后向基质渗流导致流体损失，同时需要输入与之相关的参数，比如基质渗透系数、基质孔隙压缩系数和基质孔隙率等，否则不需输入这些参数。省缺值：off，指流道（Flow channel）中的流体不向周围基质渗流
。可选

> 
> **值：**
> 
> b（[bool](数据类型/bool/)，渗流开关值）

