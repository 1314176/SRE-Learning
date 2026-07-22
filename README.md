# SRE-Learning

> 一名 IT 运维工程师向 SRE / DevOps 工程师转型的学习与实战记录。

![方向](https://img.shields.io/badge/方向-SRE%20%2F%20DevOps-blue)
![Linux](https://img.shields.io/badge/Linux-学习中-orange)
![Python](https://img.shields.io/badge/Python-自动化-yellow)
![Docker](https://img.shields.io/badge/Docker-计划中-2496ED)
![Kubernetes](https://img.shields.io/badge/Kubernetes-计划中-326CE5)

---

## 关于本仓库

本仓库用于记录我从传统 IT 运维岗位向 SRE / DevOps 工程师转型的全过程。

这里不仅会保存课程笔记，还会持续记录：

- Linux 学习笔记
- Linux 动手实验
- Shell 自动化脚本
- Python 自动化工具
- Git 使用记录
- Docker 实验
- Kubernetes 实验
- CI/CD 流水线实践
- Prometheus 与 Grafana 监控实践
- 故障排查与复盘
- AI 辅助运维项目

本仓库的目标不是单纯记录“学过什么”，而是通过持续学习、动手实验、项目实战和问题复盘，逐步建立真实的 SRE / DevOps 工程能力。

---

## 关于我

### 当前岗位

**IT 运维工程师**

我拥有 8 年企业 IT 运维相关工作经验。

目前具备的工作经验包括：

- 桌面与终端运维
- Windows 系统管理
- 软件与硬件故障排查
- 企业 IT 服务支持
- 基础网络故障排查
- 日常基础设施维护
- 运维事件处理

### 转型目标

目标岗位：

- SRE 工程师
- DevOps 工程师
- Linux 运维工程师（过渡方向）

目标城市：

- 上海
- 西安

我的目标是把已有的传统 IT 运维经验，与现代基础设施工程能力结合起来，重点补强：

- Linux 系统管理
- Shell 脚本
- Python 自动化
- Git 工程协作
- Docker
- Kubernetes
- CI/CD
- 监控与可观测性
- SRE 可靠性工程

---

## 职业发展路径

```text
IT 运维工程师
       |
       v
Linux / 系统运维工程师
       |
       v
SRE / DevOps 工程师
```

---

## 为什么选择 SRE / DevOps

传统 IT 运维更多关注：

- 系统能否正常运行
- 用户问题处理
- 日常维护
- 故障恢复

现代基础设施还要求：

- 使用自动化替代重复操作
- 使用监控和数据提升可观测性
- 使用工程化方法解决长期问题
- 建设稳定、可扩展、可恢复的系统
- 对故障进行复盘和持续改进

我的目标，是从：

> 维护系统正常运行

逐步成长为：

> 设计、建设并保障可靠系统

---

## 学习路线

### 2026 年：工程基础建设

重点学习内容：

- Linux
- Shell
- Python
- Git
- 计算机网络
- Docker
- Kubernetes
- CI/CD
- Prometheus
- Grafana
- 日志分析
- 可观测性
- 故障排查

主要目标：

- 掌握 Linux 系统管理基础
- 建立 Shell 与 Python 自动化能力
- 熟悉 Git 日常工作流
- 掌握 Docker 基础
- 掌握 Kubernetes 核心概念和常用操作
- 完成 CI/CD 流水线实践
- 完成监控与告警平台实践
- 建立规范的实验与故障记录习惯

### 2027 年：求职与岗位转型

目标方向：

- SRE 工程师
- DevOps 工程师
- Linux 运维工程师

计划完成：

- 简历优化
- GitHub 项目整理
- 面试题复盘
- 项目讲解准备
- 上海与西安岗位投递
- 完成岗位转型

---

## 当前能力评估

### Linux

- 当前水平：3 / 10
- 目标水平：8 / 10

### Shell

- 当前水平：0 / 10
- 目标水平：7 / 10

### Python

- 当前水平：3 / 10
- 目标水平：7 / 10

### Git

- 当前水平：1 / 10
- 目标水平：7 / 10

### 计算机网络

- 当前水平：3 / 10
- 目标水平：8 / 10

### Docker

- 当前水平：0 / 10
- 目标水平：7 / 10

### Kubernetes

- 当前水平：0 / 10
- 目标水平：6 / 10

### CI/CD

- 当前水平：0 / 10
- 目标水平：7 / 10

### 监控与可观测性

- 当前水平：0 / 10
- 目标水平：7 / 10

---

## 学习环境

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

### Linux 虚拟机规划

- Rocky Linux
- Ubuntu Server
- 其他课程所需兼容发行版

---

## 实验室架构

```text
                  Windows 宿主机
                        |
                     VMware
                        |
          +-------------+-------------+
          |             |             |
      sre-node01    sre-node02    sre-node03
          |             |             |
      Linux 基础     自动化练习      服务实验
```

实验环境主要用于：

- Linux 系统管理
- 用户与权限实验
- 文件系统实验
- 网络故障排查
- Shell 自动化
- Python 自动化
- Web 服务部署
- Docker 实验
- Kubernetes 实验
- Prometheus 与 Grafana 监控实验

---

## 项目规划

### 项目一：Linux SRE 实验室

**状态：进行中**

主要内容：

- Linux 系统安装
- 用户与权限管理
- 服务管理
- 日志管理
- 磁盘与存储管理
- 网络配置
- 性能分析
- 故障排查

### 项目二：自动化工具箱

**状态：计划中**

主要内容：

- Shell 系统巡检脚本
- Shell 自动备份脚本
- Python 主机巡检工具
- Python 日志分析工具
- 自动报告生成工具

### 项目三：Docker 实战

**状态：计划中**

主要内容：

- Docker 镜像
- Dockerfile
- 容器网络
- 数据卷
- Docker Compose
- 应用容器化
- 容器故障排查

### 项目四：Kubernetes 实验室

**状态：计划中**

主要内容：

- Kubernetes 集群
- Pod
- Deployment
- Service
- ConfigMap
- Secret
- 存储
- 调度
- 健康检查
- 滚动更新与回滚
- Kubernetes 故障排查

### 项目五：CI/CD 流水线

**状态：计划中**

主要内容：

- 自动构建
- 自动测试
- 自动部署
- 版本管理
- 回滚机制
- 流水线故障排查

### 项目六：监控与告警平台

**状态：计划中**

主要内容：

- Prometheus
- Grafana
- Exporter
- 告警规则
- 指标采集
- 仪表盘
- 故障告警
- 监控复盘

### 项目七：AI-SRE 助手

**状态：计划中**

主要内容：

- AI 辅助日志分析
- AI 辅助故障排查
- AI 辅助文档生成
- AI 辅助自动化脚本
- AI 辅助运维知识库

---

## 学习资源

### 主课程

- 老男孩 SRE 课程

### 补充课程

- Linux 云计算线上深度实战技能课

### 学习方法

```text
课程学习
    |
    v
动手实验
    |
    v
整理笔记
    |
    v
提交 GitHub
    |
    v
复盘与改进
    |
    v
形成工程能力
```

---

## 仓库目录规划

```text
SRE-Learning
├── README.md
├── 00-学习路线
├── 01-Linux基础
├── 02-Shell脚本
├── 03-Python自动化
├── 04-计算机网络
├── 05-Git
├── 06-Docker
├── 07-Kubernetes
├── 08-CI-CD
├── 09-监控与可观测性
└── 10-AI-SRE
```

---

## 文档记录规范

每个重要实验应尽量包含：

1. 实验目标
2. 实验环境
3. 操作步骤
4. 使用命令
5. 预期结果
6. 实际结果
7. 遇到的问题
8. 排查过程
9. 根本原因
10. 解决方案
11. 验证结果
12. 后续改进

---

## Git 提交规范

推荐使用以下提交前缀：

```text
docs: 更新学习文档
lab: 新增实验记录
feat: 新增脚本或功能
fix: 修复问题
refactor: 优化目录或代码结构
chore: 仓库维护
```

示例：

```text
docs: 更新Linux基础学习笔记
lab: 新增Linux实验环境搭建记录
feat: 新增Shell系统巡检脚本
fix: 修复脚本磁盘使用率判断问题
```

---

## 安全规则

禁止上传：

- 账号密码
- API Token
- SSH 私钥
- 公司内部文件
- 真实生产环境信息
- 敏感 IP 地址
- 付费课程文件
- 个人隐私资料

统一使用占位符：

```text
<SERVER_IP>
<USERNAME>
<PASSWORD>
<API_TOKEN>
```

---

## 当前学习重点

当前阶段重点完成：

1. 整理 GitHub 仓库结构
2. 建立 Linux 学习目录
3. 搭建 Linux 虚拟机实验环境
4. 开始 Linux 基础课程
5. 记录第一份 Linux 实验文档
6. 熟悉 Git 提交与推送流程

---

## 学习原则

- 坚持动手，不只看视频
- 每个重要知识点都做实验
- 每次实验都记录结果
- 记录失败和排查过程
- 不盲目追求学习速度
- 优先保证身体和长期坚持
- 用项目证明能力
- 用持续提交记录成长

---

## 最终目标

通过持续学习和项目实战，逐步具备以下能力：

- 独立管理 Linux 系统
- 编写 Shell 自动化脚本
- 编写 Python 运维工具
- 熟练使用 Git
- 部署和维护 Docker 应用
- 运维基础 Kubernetes 环境
- 建设 CI/CD 流水线
- 建设监控与告警系统
- 排查生产环境故障
- 编写规范的实验与复盘文档
- 使用真实项目成果申请 SRE / DevOps 岗位

本仓库将持续记录我的学习、实验、项目和成长过程。
