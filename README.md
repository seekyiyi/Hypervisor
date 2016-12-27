## Hypervisor
是用來建立與執行虛擬機器的部份電腦軟體，韌體或是硬體。
被Hypervisor用來執行一個或多個虛擬機器的電腦被稱為主體機器（host machine），這些虛擬機器，則稱為客體機器（guest machine）。

# Host Machine
運行Hypervisor的實體主機，但有時運行在Hypervisor之上

# Guest Machine
運行在Hypervisor之上的虛擬主機



## Hypervisor類型

# Type-1: native or bare-metal hypervisors
Hypervisor直接運行在host的硬體上，並直接控制硬體及管理Guest作業系統，此時host把Guest作業系統當成一個process。
# Type-2: hosted hypervisors
Hypervisor運行在host的作業系統上，再去提供虛擬化服務。

![Hypervisor](https://upload.wikimedia.org/wikipedia/commons/e/e1/Hyperviseur.png)
