# 示例项目  
在使用板子之前，请注意核心板插在底板上的方向，如下图所示：

1. RGB三色灯例子  
用跳帽短接三色灯和模块GPIO：BLED连GPIO13，RlED连GPIO14，GLED连GPIO15,如下图：
![RGB三色灯连接示意图](image/example-rgb.png)  
在user_main的函数中添加“led_object_init()”；
2. 电机的例子
用跳帽短接电机驱动和模块GPIO：IA连GPIO13，IB连GPIO12，如下图：
![电机连接示意图](image/example-rgb.png) 
在user_main的函数中添加“motor_object_init()”
3. 温度的例子
用跳帽短接DHT11和模块GPIO：DHT连GPIO12,如下图：
![温度连接示意图](image/example-dht.png) 
在user_main的函数中添加“temperature_object_init()”
4. 湿度的例子
用跳帽短接DHT11和模块GOIO：DHT连GPIO12，同温度的例子
在user_mian的函数中添加“humiture_object_init()”  
5.继电器的例子
用跳帽短接继电器和模块GPIO：JDQ连GPIO12，如下图：
![继电器连接示意图](image/example-jdq.png) 
在user_main的函数中添加“plug_object_init”




