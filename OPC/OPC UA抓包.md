

# OPC UA抓包

## 配置OPC服务器

这里用研华网关ECU1251作为OPC服务器

### 用户点，配置了一个点位MyPoint

![image-20210903155032172](../Kepserver/Imag/image-20210903155032172.png)

### OPC协议转发配置

![image-20210903155129396](../Kepserver/Imag/image-20210903155129396.png)

![image-20210903155142968](../Kepserver/Imag/image-20210903155142968.png)

## UaExpert配置与OPC UA服务器的连接

![image-20210903173048500](Imag/image-20210903173048500.png)

## Wireshark抓包

![image-20210903172837333](Imag/image-20210903172837333.png)

可以发现，UaExpert与OPC UA的服务器通信数据，都被加密了

