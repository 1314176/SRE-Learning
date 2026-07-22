# Experiment 001: Linux Lab Environment Setup

## 1. Objective

Build the initial Linux laboratory environment for SRE / DevOps learning.

The environment will be used for:

- Linux administration
- Network experiments
- Shell automation
- Service deployment
- Docker learning
- Kubernetes preparation
- Monitoring experiments

---

## 2. Host Environments

### Work Computer

- CPU: Intel Core i7-10700
- Memory: 64 GB RAM
- Storage: 500 GB SSD
- Host operating system: Windows
- Virtualization software: VMware

### Home Computer

- CPU: Intel Core Ultra 7 265K
- Memory: 64 GB RAM
- Virtual machine storage: 500 GB SSD
- Host operating system: Windows
- Virtualization software: VMware

---

## 3. Initial Node Plan

### sre-node01

- Operating system: Rocky Linux or another course-compatible Linux distribution
- CPU: 2 vCPU
- Memory: 4 GB
- Disk: 40 GB
- Purpose: Linux foundation and system administration

### sre-node02

- Operating system: Rocky Linux or another course-compatible Linux distribution
- CPU: 2 vCPU
- Memory: 4 GB
- Disk: 40 GB
- Purpose: Service deployment and automation practice

### sre-node03

- Operating system: Ubuntu Server or another course-compatible Linux distribution
- CPU: 2 vCPU
- Memory: 4 GB
- Disk: 40 GB
- Purpose: Cross-distribution practice and future container experiments

---

## 4. Naming Standard

Hostnames:

```text
sre-node01
sre-node02
sre-node03
```

User account:

```text
sreuser
```

Do not publish real passwords, private keys, or sensitive network information.

---

## 5. Network Plan

Recommended mode during the foundation phase:

```text
NAT
```

Reasons:

- Simple internet access
- Lower risk of affecting the company or home network
- Suitable for package installation and basic experiments

Record only non-sensitive lab information in the public repository.

Example:

```text
sre-node01: <LAB_IP_01>
sre-node02: <LAB_IP_02>
sre-node03: <LAB_IP_03>
```

---

## 6. Installation Checklist

- [ ] Create virtual machine for sre-node01
- [ ] Install Linux
- [ ] Configure hostname
- [ ] Create learning user
- [ ] Configure network
- [ ] Update system packages
- [ ] Install basic tools
- [ ] Verify SSH service
- [ ] Record system information
- [ ] Create a virtual machine snapshot

---

## 7. Verification Commands

Run the following commands after installation:

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

Package update commands depend on the Linux distribution.

For an RPM-based distribution:

```bash
sudo dnf update -y
```

For an Ubuntu-based distribution:

```bash
sudo apt update
sudo apt upgrade -y
```

---

## 8. Expected Result

The first Linux virtual machine should:

- Start normally
- Have the correct hostname
- Access the network
- Resolve domain names
- Update packages
- Allow local login
- Have SSH service available
- Display normal CPU, memory, disk, and network information

---

## 9. Actual Result

Complete this section after the experiment.

```text
Installation status:
Hostname:
Operating system:
IP configuration:
Internet connectivity:
SSH status:
Problems encountered:
```

---

## 10. Problems and Troubleshooting

Record every problem using this format:

```text
Problem:

Symptom:

Diagnostic commands:

Root cause:

Solution:

Verification:
```

---

## 11. Conclusion

Complete this section after the environment has been verified.

Example:

> The first Linux virtual machine was installed successfully. Network access, package management, and SSH service were verified. The environment is ready for Linux foundation experiments.

---

## 12. Next Experiment

After completing this experiment:

```text
002-linux-basic-information-and-help-system.md
```
