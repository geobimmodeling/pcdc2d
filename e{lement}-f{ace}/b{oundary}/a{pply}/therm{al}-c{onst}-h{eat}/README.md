# therm{al}-c{onst}-h{eat}
pcdc e{lement}-f{ace} b{oundary} a{pply} <span style='color: red;'>therm{al}-c{onst}-h{eat}</span>
> **描述：**热力学边界条件。如果设置了与环境之间的传热系数，则模拟会根据单元温度和环境温度传热，否则，单元边界面是绝热的

**子关键词：**[h{eat}-f{lux}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/h{eat}-f{lux}/)，[t{ransfer}-c{oefficent}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/t{ransfer}-c{oefficent}/)，[e{nvironment}-t{emperature}](e{lement}-f{ace}/b{oundary}/a{pply}/therm{al}-c{onst}-h{eat}/e{nvironment}-t{emperature}/)，


**举例：**
```
pcdc element-face apply therm-c-heat heat-flux 1.0 t-c 2.0 e-t 30 range x 0 1000.0
#该命令定义在X从0到1000.0范围内单元-面上施加热力学边界条件：
#热通量为1.0
#与环境之间的传热系为2.0
#环境温度值为30摄氏度

```
