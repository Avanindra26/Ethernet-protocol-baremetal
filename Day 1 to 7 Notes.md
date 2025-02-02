# Ethernet Configuration
There are many types of configurations available with different MCUs. Some MCUs let you configure the memory in the CubeMX, while others don’t. Some of the Boards have the MII Hardware, while other have RMII.  

![image](https://github.com/user-attachments/assets/ea3af6ef-a912-4d3c-8edb-f6e21e9681ab)  


### Before proceeding further Things to learn
1- QSPI  
2- MPU Configuration  
3- Special memory configuration  
4- Flash script

## QSPI  
## MPU (Memory Protection Unit)  
-Memory Protection Unit is a piece of hardware in modern MCUs  
-Prevents a process from accessing an unallocated region  
-Allows privileged access to defined regions  
-Can be controlled with attributes  
-Monitors every transaction (including instruction fetch)  
-Violation triggers fault exception  

# Uses of MPU
 Speculative Access
 DMA Issues
 Task Management



  





















Resources used:-
- STM32 ETHERNET by ControllersTech https://www.youtube.com/watch?v=8r8w6mgSn1A&list=PLfIJKC1ud8ggZKVtytWAlOS63vifF5iJC
- MPU - https://core.slscorp.com/resources/blogs/160-fpga/281-memory-protection-unit.html
