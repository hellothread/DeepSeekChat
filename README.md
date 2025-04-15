## 主要功能

### 对话功能
- 支持多轮对话
- 支持代码高亮显示
- 支持 Markdown 渲染
- 支持数学公式渲染
- 支持多会话管理
- 支持对话历史导出/导入

### 模型控制
- 支持采样策略选择（top_p, top_k）
- 支持最大输出长度控制
- 支持系统提示词（System Prompt）自定义
- 支持多个模型切换（Chat, Coder）


### 高级功能
- 提示词（Prompt）模板库
- API 密钥管理
- 函数配置管理
- 对话历史管理

## 技术栈

- Next.js 14 (App Router)
- TypeScript
- Tailwind CSS
- Zustand (状态管理)
- Ant Design (UI 组件)
- localStorage (本地数据存储)

## 快速开始

### 本地开发

1. 克隆项目
```
bash
git clone https://github.com/hellothread/DeepSeekChat.git
cd deepseek-webui
```
2. 安装依赖
```
bash
npm install
```
3. 启动开发环境
```
bash
npm run dev
```
4. 访问项目
```
http://localhost:3000
```
### 生产构建
```
bash
npm run build
```

## Vercel 一键部署

1. Fork 本项目到你的 GitHub 账号

2. 在 [Vercel](https://vercel.com) 注册账号并连接你的 GitHub

3. 点击 "New Project" 导入本项目

4. 点击 "Deploy" 开始部署

5. 部署完成后，Vercel 会自动生成一个域名供访问

## 使用说明

1. 首次使用需要在设置页面配置 API Key
2. 可以在函数配置页面添加或修改可调用的外部函数
3. 在对话页面可以直接与 AI 进行对话，AI 会根据需要调用配置的函数


