# GT06 客户端功能

## 修订历史

| Version |   Date     |   Author   |   Change expression   |
| :------ | ---------- | ---------- | --------------------- |
| 1.0.0   | 2022-07-12 | 孙健       | 初始版本               |

## GT06 介绍

### 功能概述

该项目实现了GT06协议**客户端**功能, 用户可直接使用该功能与对应服务端进行标准内的数据交互。

### 主要功能

- 服务器连接
- 终端登录
- 终端GPS&LBS定位信息上报
- 终端设备状态信息上报
- 服务端指令下发与应答


### English Readme

**GT06 Client Functionality**
Revision History
Version   Date         Author      Change Expression
1.0.0     2022-07-12   Sun Jian    Initial Version

**Introduction to GT06**

**Function Overview**

This project implements GT06 protocol client functionality, allowing users to directly engage in standard data interaction with the corresponding server.

**Key Features**

- Server Connection
- Terminal Login
- Reporting of Terminal GPS & LBS Location Information
- Reporting of Terminal Device Status Information
- Server Command Issuance and Responses

**Notes**

The GT06 protocol specifies a limited number of messages. This project focuses on basic message functionality. Custom messages for different service platforms require secondary development, and interface adjustments are necessary for extending messages.

QuecPython does not support Unicode name escaping, while GT06 server messages contain Unicode-encoded data. Consequently, escaping is not feasible in this context, and this should be noted.

### 备注

- GT06协议规定的消息较少, 该项目只实现了基础的消息功能, 不同的服务平台自定义的消息需要进行二次开发, 扩展的消息也需要进行接口调整。
- QuecPython未实现Unicode名称转义, 而GT06服务端下发消息中有unicode编码数据, 因此进行无法转移, 此处需要注意。
