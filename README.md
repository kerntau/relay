# Domain Relay

Domain Relay 是一个纯前端域名跳转页面，用星空动画展示跳转状态。它适合放在域名入口、短链落地页或项目导航页中；仓库本身不提供后端跳转服务。

## 技术栈

- React 19 + TypeScript
- Vite 6
- Tailwind CSS 4
- Motion（动效）
- Lucide React（图标）

## 本地开发

需要 Node.js 18+ 与 pnpm。

    pnpm install
    pnpm dev
    # 默认监听 http://localhost:3000

## 构建与预览

    pnpm build
    pnpm preview

生成的静态文件位于 dist/，可部署到任意静态托管服务。部署时请根据自己的域名和跳转目标修改源码中的配置；仓库未提供固定的线上演示地址。

## 质量检查

    pnpm lint       # TypeScript 类型检查
    pnpm clean      # 删除 dist/
