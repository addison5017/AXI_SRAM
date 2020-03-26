# AXI_SRAM

#### 项目介绍
&#160; &#160; &#160; &#160; AXI4总线协议的SRAM。

#### 文件结构

##### 工程结构

- AXI_Sram.sv   
    - axi_slave_if.sv    
        - axi_w_channel.sv
        - axi_r_channel.sv
    - sram_core.sv

##### 仿真结构

- AXI_Sram_TB.sv
    - AXI_Master.sv
    - AXI_Sram.sv   
        - axi_slave_if.sv    
            - axi_w_channel.sv
            - axi_r_channel.sv
        - sram_core.sv

#### 日志

* 首次更新 `2020.3.26`
    * AXI总线协议；
    * SRAM大小为8k×8；
    * 数据位宽为32bit；
    * 地址位宽为16bit。



* 读写仿真：
    * ![m0_wr](https://raw.githubusercontent.com/Verdvana/AXI4_Interconnect/master/Simulation/AXI4_Interconnect_TB/m0_wr.jpg)

