### 简介

这是一个参考的AutopilotPI载板，包括：
- ov2640摄像头接口
- ESP32及其下载电路
  - 其中esp32的sdio接口与AutopilotPI相连，v3s可以通过sdio接口控制esp32作为sdio网卡，实测延迟比较高（80ms+），后放弃
  - ov2640摄像头接口与esp32 I2S相连，未测试
- E32-900M20S（SX1280模块）（可用于制作900M ELRS）
  - 未测试
- ea3036三路dcdc电路
- 1S锂电池充电/升压电路
- 4路空心杯驱动电路
  
### Images

![image1](https://github.com/Ncerzzk/V3s_Quadrotor/blob/master/images/top.jpg?raw=true)
![image2](https://github.com/Ncerzzk/V3s_Quadrotor/blob/master/images/bottom.jpg?raw=true)

![image3](https://github.com/Ncerzzk/V3s_Quadrotor/blob/master/images/quadrotors.jpg?raw=true)