<div align="center">

# Domain Relay

**带星空动效的前端域名跳转页**<br>
*A cinematic frontend landing page for domain redirects*

[![Status](https://img.shields.io/badge/Status-Prototype-f0ad4e?style=for-the-badge)](https://github.com/kerntau/relay)
[![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://github.com/kerntau/relay)
[![Vite](https://img.shields.io/badge/Vite-6-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://github.com/kerntau/relay)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/kerntau/relay)

</div>

---

## 01. 项目定位 // POSITIONING

Domain Relay 是一个纯前端域名入口页面，用星空背景、状态反馈和动效展示跳转体验。仓库不提供后端跳转服务、短链数据库或固定线上域名。

## 02. 功能与边界 // SCOPE

- React 单页界面与响应式布局。
- 星空背景、状态动画和图标反馈。
- 可按部署环境修改域名与跳转目标。
- 不处理账号、链接持久化或服务端重定向。

## 03. 技术矩阵 // TECHNICAL MATRIX

| 模块 | 技术 | 说明 |
| --- | --- | --- |
| UI | React 19、TypeScript | 组件与页面 |
| 构建 | Vite 6 | 开发服务器和生产打包 |
| 样式 | Tailwind CSS 4 | 设计系统 |
| 动效 | Motion | 过渡与状态动画 |
| 图标 | Lucide React | UI 图标 |
| 可选服务 | Express、dotenv、@google/genai | 以源码配置为准，默认前端不提供后端 |

## 04. 目录拓扑 // REPOSITORY TOPOLOGY

~~~text
.
├── src/
│   ├── components/          # 页面和交互组件
│   ├── assets/              # 静态资源
│   ├── App.tsx              # 应用入口
│   └── main.tsx             # React 挂载
├── public/                  # 公共静态文件
├── index.html
├── package.json
└── vite.config.*
~~~

## 05. 快速开始 // QUICK START

环境要求：Node.js 18+、pnpm。

~~~bash
pnpm install
pnpm dev
# 默认监听 http://localhost:3000
~~~

## 06. 部署与验证 // DEPLOYMENT & VALIDATION

~~~bash
pnpm lint
pnpm build
pnpm preview
~~~

将 dist/ 发布到静态托管服务。部署前在源码中确认域名、跳转目标和环境变量；仓库没有固定线上演示地址。



## 09. 许可证 // LICENSE

仓库当前未附带 LICENSE 文件。使用或再分发前，请先补充许可证并同步更新本节。
