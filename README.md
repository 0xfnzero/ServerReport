# Bare Metal Server Report / Solana RPC 服务器避坑指南

收集社区在搭建低成本 Solana RPC 节点时遇到的 Bare Metal 服务器、服务商、机型、内存、区域和稳定性反馈。把你稳定运行或不稳定运行的配置提交到 Issue，我会持续整理，帮助大家减少踩坑。

## 这个项目提供什么

| 方向 | 内容 |
| --- | --- |
| 覆盖范围 | Bare Metal 服务商、CPU 机型、内存规格、机房区域、运行稳定性 |
| 主要场景 | 低成本 Solana RPC 节点选型和服务器避坑 |
| 数据来源 | 社区 Issue、公开反馈和实际运行经验整理 |
| 注意事项 | 样本有限，结果不代表 100% 稳定或不稳定 |
| 提交方式 | 在 Issues 中提交服务商、机型、内存、地区和运行结果 |

## 当前样本

以下都以最低成本搭建 Solana RPC 节点为例，下面的情况只是社区用户遇到的情况，并不一定代表 100%。

### 可以稳定运行的机器

1. tsw 9950X, RAM: 128G, region: ny
2. allnodes 9950X, RAM: 256G, region: fra

### 不稳定运行的机器

1. interserver 9950X, RAM: 192G, region: ny
2. allnodes 9950X, RAM: 128G, region: fra
3. latitude 9254, RAM: 768G, region: ny
