# mech{anical}-s{tress}-b{oundary}-c{ondition}
pcdc e{lement}-f{ace} b{oundary} a{pply} <span style='color: red;'>mech{anical}-s{tress}-b{oundary}-c{ondition}</span>
> **描述：**应力边界条件

**子关键词：**[s{tress}-x{x}](e{lement}-f{ace}/b{oundary}/a{pply}/mech{anical}-s{tress}-b{oundary}-c{ondition}/s{tress}-x{x}/)，[s{tress}-y{y}](e{lement}-f{ace}/b{oundary}/a{pply}/mech{anical}-s{tress}-b{oundary}-c{ondition}/s{tress}-y{y}/)，[s{tress}-n{ormal}](e{lement}-f{ace}/b{oundary}/a{pply}/mech{anical}-s{tress}-b{oundary}-c{ondition}/s{tress}-n{ormal}/)，


**举例：**
```
pcdc element-face apply mech-s-b-c stress-y 2e6 range x 0 1000.0
#该命令定义在X从0到1000.0和Y从-5到0范围内的单元-面上施加y方向应力2e6
pcdc table 'tbl1' data 0.0 0.0, 0.1 2e6,1e20 2e6
#该命令创建一个名称是“tbl1"的二维数据表，数据表的二维数据对（x,y)依次为（0.0,0.0), (0.1 2e6), (1e20 2e6). 表示x(计算时间）从0到0.1时，y从0线性增加到2e6,然后x(计算时间）从0.1到1e20时，y保持为常量2e6
pcdc element-face apply mech-s-b-c stress-x table 'tbl1' range x -5 0
#该命令定义在X从-5到0范围内的单元-面上施加x方向应力，应力根据二维数据表"tbl1"随时间变化
pcdc element-face apply mech-s-b-c stress-n 3e6 range y 100 105
#该命令定义在Y从100到105范围内的单元-面上施加法向方向的压应力，应力值为3e6

```
