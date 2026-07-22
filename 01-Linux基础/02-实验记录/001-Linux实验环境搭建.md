# 实验 001：Linux 实验环境搭建

## 一、实验目标

搭建 SRE / DevOps 学习所需的 Linux 实验环境。

该环境将用于：

- Linux 系统管理
- 网络实验
- Shell 自动化
- 服务部署
- Docker 学习
- Kubernetes 准备
- 监控实验

---

## 二、宿主机环境

### 公司电脑

- CPU：Intel Core i7-10700
- 内存：64 GB
- 存储：500 GB SSD
- 宿主系统：Windows
- 虚拟化软件：VMware

### 家用电脑

- CPU：Intel Core Ultra 7 265K
- 内存：64 GB
- 虚拟机存储：500 GB SSD
- 宿主系统：Windows
- 虚拟化软件：VMware

---

## 三、初始节点规划

### sre-node01

- 操作系统：Rocky Linux 或课程所使用的兼容发行版
- CPU：2 vCPU
- 内存：4 GB
- 磁盘：40 GB
- 用途：Linux 基础与系统管理

### sre-node02

- 操作系统：Rocky Linux 或课程所使用的兼容发行版
- CPU：2 vCPU
- 内存：4 GB
- 磁盘：40 GB
- 用途：服务部署与自动化练习

### sre-node03

- 操作系统：Ubuntu Server 或课程所使用的兼容发行版
- CPU：2 vCPU
- 内存：4 GB
- 磁盘：40 GB
- 用途：跨发行版练习和后续容器实验

---

## 四、命名规范

主机名：

```text
sre-node01
sre-node02
sre-node03
```

学习账户：

```text
sreuser
```

禁止在公开仓库中记录真实密码、私钥或敏感网络信息。

---

## 五、网络规划

Linux 基础学习阶段建议使用：

```text
NAT
```

原因：

- 上网配置简单
- 不容易影响公司或家庭网络
- 适合安装软件包和进行基础实验

公开仓库只记录非敏感实验信息。

示例：

```text
sre-node01：<LAB_IP_01>
sre-node02：<LAB_IP_02>
sre-node03：<LAB_IP_03>
```

---

## 六、安装检查清单

- [ ] 创建 sre-node01 虚拟机
- [ ] 安装 Linux 系统
- [ ] 设置主机名
- [ ] 创建学习账户
- [ ] 配置网络
- [ ] 更新系统软件包
- [ ] 安装基础工具
- [ ] 验证 SSH 服务
- [ ] 记录系统信息
- [ ] 创建虚拟机快照

---

## 七、验证命令

安装完成后执行：

```bash
hostnamectl
cat /etc/os-release
uname -a
ip address
ip route
cat /etc/resolv.conf
free -h
df -h
lsblk
systemctl status sshd
```

RPM 系发行版更新命令：

```bash
sudo dnf update -y
```

Ubuntu 系发行版更新命令：

```bash
sudo apt update
sudo apt upgrade -y
```

---

## 八、预期结果

第一台 Linux 虚拟机应满足：

- 系统可以正常启动
- 主机名设置正确
- 网络可以正常访问
- DNS 可以正常解析
- 软件包可以正常更新
- 学习账户可以正常登录
- SSH 服务正常
- CPU、内存、磁盘和网络信息正常

---

## 九、实际结果

完成实验后填写：

```text
安装状态：
主机名：
操作系统：
IP 配置：
互联网连接：
SSH 状态：
遇到的问题：
```

---

## 十、问题与排查

每个问题按照以下格式记录：

```text
问题：

故障现象：

排查命令：

根本原因：

解决方案：

验证结果：
```

---

## 十一、实验结论

完成验证后填写。

示例：

> 第一台 Linux 虚拟机已经成功安装，网络、软件包管理和 SSH 服务均验证正常，可以开始 Linux 基础实验。

---

## 十二、下一项实验

```text
002-Linux系统信息与帮助系统.md
```
