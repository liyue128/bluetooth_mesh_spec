# PB-ADV

**PB-ADV是在广播层上面使用**[**Generic Provisioning PDU**](../generic-provisioning-ceng/)**对目标设备进行入网操作的一种provisiong bearer**。该入网机制是基于会话的。未入网的目标设备在特定时间段内只能支持一个会话。但provisioner不受该限制。会话通过[连接建立过程](../generic-provisioning-ceng/lian-jie-jian-li-guo-cheng.md)来建立的。

PB-ADV用于Generic Provision PDU的传输。PB-ADV bearer的最大传输单元(MTU)大小是24个oct。

使用PB-ADV时，通过《PB-ADV》认证的PB-ADV AD类型来发送Generic Provision PDU。

为防止丢失任何接收到的Generic Provision PDU，支持PB-ADV的目标设备应当大量执行占空比接近100%的信号扫描。

PB-ADV AD类型包含一个PB-ADV PDU
