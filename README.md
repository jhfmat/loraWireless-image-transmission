#loraWireless image transmission
lora 图像传输具备下面几个优点：
功耗低，体积小，传输距离远，能够在复杂的环境中穿透障碍物（采用的低频433m频段）
缺点：
传输速度慢，速度有限只能传输小图（目前可以通过一些深度学习方法如超分辨等来提升分辨率图像大小和画质等）

#0 pcb.rar 硬件主板设计(Altium Designer)
发送端主板
接受端主板

#1 ov2640sx1276发送.rar 微型设备传输端 (keil)
控制器:stm32
图像传感器：ov2640
无线发送模块：sx12768

#2 STM32_SX1278接收-串口发送(keil)
控制器:stm32 
无线接受模块：sx12768
链接端：串口

#3 UartDisplay_2.2_SRC (vs)
链接端：串口
显示界面：mfc(c++) 

![pic1](./pics/test0.jpg)
![pic1](./pics/test1.jpg)
![pic1](./pics/界面.jpg)