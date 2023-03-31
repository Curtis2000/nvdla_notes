# hardware workflow

[reference1](https://vvviy.github.io/2018/09/12/nv_small-FPGA-Mapping-Workflow-I/)  
[reference2](https://zhuanlan.zhihu.com/p/378202360)  
[reference3](https://github.com/SCLUO/ITRI-OpenDLA)  
  
These are excellent references. Here, I will provide just a few details:  
1: When encapsulating the nvdla ip core, pay attention to the allocation of address blocks.  
2: Remember to turn off the gated clock during block design as well.  
3: Combine all the references to correct problems in the mapping process.   