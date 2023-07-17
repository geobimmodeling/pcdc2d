# null
pcdc e{lement} c{onstitutive}-m{odel} <span style='color: red;'>null</span>
> **描述：**空的本构模型。该模型表示单元为空单元，空单元不再参与计算，也不在视图空间显示，当空单元赋予非空的特定力学本构模型后，则重新参与计算并显示。在岩土工程中通常用来模拟开挖过程。



**举例：**
```
pcdc element c-model null range group 't' set 'sample'
#该命令定义在命名"sample"类中组名为"t"的单元的是空单元（不参与计算

```
