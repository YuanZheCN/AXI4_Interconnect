# AXI4_Interconnect

#### 项目介绍
AXI4总线连接器，将最多4个AXI4总线主设备连接到最多8个AXI4总线从设备。

#### 日志

* 首次更新 2020.3.15
    * 4个AXI4总线主设备接口；
    * 8个AXI4总线从设备接口；
    * 从设备地址隐藏与读写地址的高三位；
    * 主设备仲裁优先级随上一次总线所有者向后顺延。


* 0号主设备读写0号从设备仿真：
    * ![m0_wr](https://raw.githubusercontent.com/Verdvana/AXI4_Interconnect/master/Simulation/AXI4_Interconnect_TB/m0_wr.jpg)
    * ![s0_wr](https://raw.githubusercontent.com/Verdvana/AXI4_Interconnect/master/Simulation/AXI4_Interconnect_TB/s0_wr.jpg)
* 0号主设备和1号主设备同时请求总线：
    * ![handshake](https://raw.githubusercontent.com/Verdvana/AXI4_Interconnect/master/Simulation/AXI4_Interconnect_TB/handshake.jpg)