**********************ST-Link/V2 JTAG/SWD**********************
ST-Link/V2 JTAG/SWD接口定义： \
( \
实际有效引脚为RST、SWD、SWC、3.3V、GND \
1号引脚是TVCC，是接收电压的引脚，对外不输出电压，主要功能就是接受目标电压以平衡电压。需要将这个1号引脚再连接到板子的3.3V上才可以 \
) \
![jointMap](https://github.com/Freecss123456/STM32/blob/master/picture_source/ST-LinkV2JTAG_SWD_List.jpg) \

ST-Link/V2 JTAG/SWD标准的接口排列： \
![jointMap](https://github.com/Freecss123456/STM32/blob/master/picture_source/ST-LinkV2JTAG_SWD.jpg) \

**********************ST-Link/V2 SWIM********************** 
ST-Link/V2 SWIM接口定义： \
![jointMap](https://github.com/Freecss123456/STM32/blob/master/picture_source/ST-LinkV2SWIM_List.jpg) \

ST-Link/V2 SWIM标准的接口排列： \
![jointMap](https://github.com/Freecss123456/STM32/blob/master/picture_source/ST-LinkV2SWIM%E6%A0%87%E5%87%86%E6%8E%A5%E5%8F%A3.jpg) 
