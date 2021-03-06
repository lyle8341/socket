## IPV4/IPV6

| ip | Format | 描述 | 例子 |
|:---:|:---:|:---:|:---:|
| ipv4 | xxx.xxx.xxx.xxx | 共四部分，每部分一个字节，十进制显示，共32位 | 192.16.1.1 | 
| ipv6 | xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx | 共八部分，每部分两个字节，十六进制显示，共128位 | 2000:fdb8:0000:0000:0001:00ab:853c:39a1 |
### port
端口是一组16位的无符号二进制数。范围[1,65535],0被保留了。
### TCP
序号 :Seq(Sequence number顺序号码)  
确认序号:Ack(Acknowledge number确认序号)  
标志位:URG,ACK,PSH,RST,SYN,FIN  
URG:紧急位(urgent pointer)  
ACK:确认位  
PSH:(push传送)急迫位  
RST:重置位  
SYN:同步位
FIN:(finish结束)终止位  
![三次握手](/images/three.jpg "三次握手")
* * *
![四次挥手](/images/four.jpg "四次挥手")