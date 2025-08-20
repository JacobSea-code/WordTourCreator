# WordTourCreator

基于AI的文字冒险创作与体验平台

## 项目简介

WordTourCreator是一个支持AI原创文字冒险体验和创作者入驻的互动平台。用户可以体验丰富的文字冒险故事，创作者则可以使用AI辅助创作功能来创建独特的故事内容。

## 技术栈

- 前端：React + TypeScript
- 后端：Node.js + Express + TypeScript
- 数据库：MongoDB
- AI集成：OpenAI GPT & DALL-E API

## 目录结构

```
WordTourCreator/
├── frontend/     # React前端应用
├── backend/      # Node.js后端服务
├── shared/       # 共享类型和工具
└── docker/       # Docker配置文件
```

## 开发指南

### 环境要求

- Node.js 18+
- pnpm 8+
- Docker (可选，用于容器化部署)
- MongoDB 6+

### 本地开发

1. 克隆仓库
```bash
git clone https://github.com/JacobSea-code/WordTourCreator.git
cd WordTourCreator
```

2. 安装依赖
```bash
pnpm install
```

3. 启动开发服务
```bash
pnpm dev
```

## 贡献指南

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'feat: Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 许可证

本项目采用 MIT 许可证
