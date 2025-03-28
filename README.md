# NFT Collectible Project

这是我在大三时开发的第一个NFT项目，基于Scaffold ETH 2框架构建。该项目允许用户铸造、转移和查看独特的NFT收藏品。

## 项目概述

本项目是一个完整的NFT应用程序，包含以下功能：
- 铸造新的NFT收藏品
- 查看已拥有的NFT
- 向其他地址转移NFT
- 查看交易历史

项目使用了以下技术栈：
- Solidity（智能合约开发）
- Hardhat（智能合约测试和部署框架）
- Next.js（前端框架）
- ethers.js / wagmi（与区块链交互）
- TypeScript

## 安装和运行

### 环境要求
- Node.js (>= v18.17)
- Yarn (v1 或 v2+)
- Git

### 安装步骤

1. 克隆仓库
```sh
git clone https://github.com/jwyismynane/NFT-first-project_study.git
cd NFT-first-project_study
```

2. 安装依赖
```sh
yarn install
```

3. 启动本地区块链
```sh
yarn chain
```

4. 部署合约（在新的终端窗口中）
```sh
yarn deploy
```

5. 启动前端（在另一个新的终端窗口中）
```sh
yarn start
```

6. 访问 [http://localhost:3000](http://localhost:3000) 查看应用程序

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

## 部署到测试网络

若要部署到公共测试网络（例如Sepolia），请按照以下步骤操作：

1. 修改 `packages/hardhat/hardhat.config.ts` 中的 `defaultNetwork` 为 `sepolia`
2. 生成部署地址：`yarn generate`
3. 向生成的地址发送一些测试网ETH
4. 部署合约：`yarn deploy`
5. 修改 `packages/nextjs/scaffold.config.ts` 中的 `targetNetwork` 为 `chains.sepolia`

## 学习收获

通过开发这个项目，我学习了：
- 区块链基础知识和智能合约开发
- NFT标准（ERC-721）的实现
- 前端与区块链的交互
- Web3应用程序的部署流程

## 后续改进

这个项目还有许多可以改进的地方：
- 添加更多的NFT元数据和自定义图像
- 实现NFT市场功能
- 改进UI/UX设计
- 添加更多的用户交互功能

## 致谢

感谢Scaffold ETH 2框架提供的模板和指导，帮助我完成了这个项目。
