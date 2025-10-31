# 水质自动采样器监控系统

## 项目简介

本项目是一个基于 Vue 3 + TypeScript 开发的智能水质自动采样器监控系统，主要用于实时监测水质状况并控制取水器的启停操作。系统提供全面的远程监控和设备管理功能，确保水质安全和设备稳定运行。

## 技术栈

- **前端框架**: Vue 3.5+ (Composition API)
- **开发语言**: TypeScript
- **构建工具**: Vite 7+
- **UI 组件库**: Element Plus
- **状态管理**: Pinia
- **路由管理**: Vue Router
- **CSS 预处理器**: Scss
- **代码规范**: ESLint
- **包管理器**: pnpm
- **网络请求**: Axios

## 核心功能

- 🔍 **实时监测** - 水质数据实时采集与展示
- ⚙️ **设备控制** - 远程控制取水器启停
- 📊 **数据分析** - 历史数据统计与可视化
- 🚨 **智能报警** - 异常状态自动告警
- 📹 **视频监控** - 设备现场实时监控
- 🛠️ **参数配置** - 设备参数远程配置

## 快速开始

### 环境要求

- Node.js >= 18.0.0
- pnpm >= 8.0.0

### 安装依赖

```bash
pnpm install
```

### 开发环境

```bash
pnpm run dev
```

### 构建生产版本

```bash
pnpm run build
```

### 代码检查

```bash
pnpm run lint
```

## 项目结构

```
src/
├── common/          # 通用模块
├── pages/           # 页面组件
├── layouts/         # 布局组件
├── router/          # 路由配置
├── pinia/           # 状态管理
├── http/            # 网络请求
└── plugins/         # 插件配置
```

## 浏览器支持

- Chrome >= 90
- Firefox >= 88
- Safari >= 14
- Edge >= 90

## 许可证

[MIT License](LICENSE)

## 联系方式

如有问题或建议，请通过 Issues 反馈。