# therm{al}-c{onst}-h{eat}
pcdc e{lement}-f{ace} b{oundary} a{pply} <span style='color: red;'>therm{al}-c{onst}-h{eat}</span>
> **描述：**热力学边界条件。如果设置了与环境之间的传热系数，则模拟会根据单元温度和环境温度传热，否则，单元边界面是绝热的

**子关键词：**[h{eat}-f{lux}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/h{eat}-f{lux}/)，[t{ransfer}-c{oefficent}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/t{ransfer}-c{oefficent}/)，[e{nvironment}-t{emperature}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/e{nvironment}-t{emperature}/)，


**举例：**
```
pcdc element-face apply m-s-b-c stress-y 2e6 range x 0 1000.0
#该命令定义在X从0到1000.0和Y从-5到0范围内的单元-面上施加y方向应力2e6

```
