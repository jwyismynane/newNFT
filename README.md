# NFT 收藏品项目

这是一个基于Scaffold ETH 2框架构建的NFT项目。该项目允许用户铸造、转移和查看独特的NFT收藏品。

## 项目概述

本项目是一个完整的NFT应用程序，包含以下功能：

* 铸造新的NFT收藏品
* 查看已拥有的NFT
* 向其他地址转移NFT
* 查看交易历史

项目使用了以下技术栈：

* Solidity（智能合约开发）
* Hardhat（智能合约测试和部署框架）
* Next.js（前端框架）
* ethers.js / wagmi（与区块链交互）
* TypeScript

## 安装和运行

### 环境要求

* Node.js (>= v18.17)
* Yarn (v1 或 v2+)
* Git

### 安装步骤

1. 克隆仓库
```
git clone https://github.com/jwyismynane/newNFT.git
cd newNFT
```

2. 安装依赖
```
yarn install
```

3. 启动本地区块链
```
yarn chain
```

4. 部署合约（在新的终端窗口中）
```
yarn deploy
```

5. 启动前端（在另一个新的终端窗口中）
```
yarn start
```

6. 访问 http://localhost:3000 查看应用程序

## 使用指南

### 铸造NFT

1. 访问"我的NFT"选项卡
2. 点击"铸造NFT"按钮
3. 等待交易确认
4. 新的NFT将显示在您的收藏中

### 转移NFT

1. 在"我的NFT"选项卡找到您想要转移的NFT
2. 点击"转移"按钮
3. 输入接收者的地址
4. 确认交易

### 查看交易历史

1. 访问"转移"选项卡
2. 查看所有NFT转移交易的历史记录
