如何应对不断提高的封锁技术？


1. kcp-go 协议字段长度变化， 添加无效字段，便于数据包与标准kcp数据包有差异，难以进行负载的识别。
其中的类型字段可以自定义。

2.sctp  (Stream Control Transmission Protocol) ,暂时无相关实现 .与tcp udp 平齐的协议

3.SRT 用于tunnel   utp  srtp

4.dtls .  gost v3

5.udp speeder.   配合vpn使用 

6.xray   对握手字段进行去特征


