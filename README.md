# 项目集合

本仓库包含三个独立的项目，每个项目都有其特定的用途和功能。

## 项目列表

### 1. [express-ejs-demo-final](./express-ejs-demo-final/)
Express.js + EJS 演示项目，展示如何使用 Express.js 框架和 EJS 模板引擎构建 Web 应用。

**主要功能：**
- Express.js Web 应用
- EJS 模板引擎
- 员工管理系统
- RESTful API 端点

### 2. [md](./md/)
Markdown 文档项目，包含文档和相关的附件文件。

**内容：**
- Markdown 文档
- 附件文件
- 图片资源

### 3. [StudyProject](./StudyProject/)
完整的 Node.js 学习项目，实现了 REST API 服务、JWT 认证和代码质量控制。

**核心功能：**
- Express.js + MongoDB REST API
- JWT 用户认证和授权
- 完整的 CRUD 操作
- Docker 容器化部署
- ESLint 代码质量控制
- VS Code 开发环境配置

## 快速开始

### StudyProject 启动指南

```bash
# 进入项目目录
cd StudyProject

# 安装依赖
npm install

# 配置环境变量
cp .env.example .env

# 启动开发服务器
npm run dev

# 访问应用
# API: http://localhost:8000/api
# 文档: http://localhost:8000
```

### Docker 部署

```bash
# 使用 Docker Compose
docker-compose up -d

# 查看服务状态
docker-compose ps
```

## 项目结构

```
├── express-ejs-demo-final/     # Express.js 演示项目
├── md/                         # Markdown 文档项目
├── StudyProject/               # Node.js 学习项目
│   ├── src/                    # 源代码
│   ├── 1/                      # API 测试文件
│   ├── .vscode/                # VS Code 配置
│   ├── package.json           # 项目配置
│   ├── docker-compose.yml     # Docker 部署
│   └── README.md              # 项目文档
└── README.md                  # 本文件
```

## 技术栈

- **后端框架:** Express.js
- **模板引擎:** EJS
- **数据库:** MongoDB
- **认证:** JWT + bcryptjs
- **代码质量:** ESLint
- **容器化:** Docker + Docker Compose
- **开发工具:** VS Code

## 许可证

每个项目可能使用不同的许可证。请查看各个项目的具体许可证信息。

## 贡献

欢迎提交 Issue 和 Pull Request 来改进这些项目。