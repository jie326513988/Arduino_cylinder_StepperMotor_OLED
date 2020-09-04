# Arduino_cylinder_StepperMotor_OLED
![](https://github.com/jie326513988/Arduino_cylinder_StepperMotor_OLED/blob/master/QQ%E6%88%AA%E5%9B%BE20200904155513.png)
观看视频https://www.bilibili.com/video/BV1Tf4y197VP  <br>
6个气缸联动，1个步进运动，OLED菜单交互，1个旋转编码器，1个复位按钮，1个启停按钮，2个传感器<br>
OLED配合旋转编码器用来调节参数<br>
主界面显示步进状态，缺料、满料、磁铁没吸起会有提示<br>
外接了一个3位按钮盒，急停、复位、启停<br>
可调节参数有步进电机的一些基本参数速度、加速度等，气缸流程的各步之间延时参数<br>
设有手动操作界面，可单独操作步进电机和每一个气缸的启停<br>
步进电机的运动和气缸的延时不会影响系统的运行和屏幕的刷新人机交互，利用定时器写了伪多线程操作<br>
