# study-network
学习计算机网络的仓库

## 网络通信协议

### 数据链路层
- 以太网协议
- MAC 地址 【物理地址】
    - 定位网卡

- 广播
    - 定义：以太网数据包必须知道接收方的 MAC 地址才能发送。即使知道了 MAC 地址，也并没有单一的发送数据给单一接收方。在以太网中采用了一种很原始的方法，而是向本网络内的所有计算机发送，让每一台计算机自己判断是否是自己需要的数据。