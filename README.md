# ⏱ Time Planner for You

> 一款帮助你掌控每一天的 AI 时间管理工具

🌐 **在线体验：** https://time-planner-sepia.vercel.app

---

## ✨ 产品特色

### 📋 今日计划
- 添加任务并设置预计用时
- 任务属性标签系统（重要/紧急/容易拖延等）
- 随机抽取任务（老虎机动画 + 确认机制）
- 基于心理学「5分钟启动效应」设计任务启动流程
- 5分钟倒计时 → 自动切换正计时，可拖拽浮窗/最小化/全屏三种模式
- 今日时间概览饼图

### ⏰ 专注计时
- 翻转时钟样式大号数字显示
- 三种模式：当前时间 / 倒计时 / 正计时
- 快速预设时长（15/30/45/60分钟）或自定义

### 🕰 感知时间
- 今年进度、本月进度、今日进度、本小时进度实时点阵可视化
- 人生进度（自定义出生年份和预期寿命）
- 让你直观感受时间的流逝

### 📖 复盘
- 历史日历视图，点击查看任意一天的数据
- 任务完成情况 + 时间差分析（超出/节省了多少分钟）
- 时间差归因标签（刷手机/任务比预计难/状态不好等）
- 今日随想（支持语音输入）
- **AI个性化复盘**：支持通义千问 / OpenAI / DeepSeek 多AI提供商，三种AI人设（理性型/热情型/严厉型）自由切换
- 数据导出 XLSX

### ⚙️ 设置
- 用户名 + 头像自定义
- 深色 / 浅色主题切换
- 主题色自定义（紫/蓝/绿/橙）
- AI提供商配置（用户自配API Key，仅保存在本地）
- 累计专注时长 + 时间准确率统计

---

## 🤖 AI 复盘功能配置

本产品支持接入主流 AI 提供商，用户自行配置 API Key：

| 提供商 | 模型 | 获取 API Key |
|--------|------|-------------|
| 通义千问 | qwen-turbo | [阿里云百炼](https://bailian.aliyun.com) |
| OpenAI | gpt-4o-mini | [OpenAI Platform](https://platform.openai.com) |
| DeepSeek | deepseek-chat | [DeepSeek](https://platform.deepseek.com) |

> ⚠️ 您的 API Key 仅保存在本地浏览器中，不会上传到任何服务器

---

## 🛠 技术栈

- 纯原生 HTML / CSS / JavaScript，无需任何框架
- Chart.js 数据可视化
- SheetJS 数据导出
- Lucide Icons 图标
- Google Fonts（Inter + Instrument Serif + LXGW WenKai）
- 本地数据存储（localStorage）

---

## 🚀 本地运行

直接下载或克隆仓库，双击打开 `index.html` 即可使用。
```bash
git clone https://github.com/tansy9725-collab/Time-Planner.git
cd Time-Planner
# 直接用浏览器打开 index.html
```

> 注意：AI 复盘功能需要通过服务器访问（或使用线上版本），本地直接打开 HTML 文件会有跨域限制。

---

## 📸 界面预览

![今日计划](screenshots/today.png)
![感知时间](screenshots/time.png)
![AI复盘](screenshots/review.png)

---

## 👩‍💻 开发方式

本项目由 [Tansy](https://github.com/tansy9725-collab) 独立设计并开发，运用 **Claude Code** 进行 AI 辅助开发，通过迭代式提示词工程驱动功能实现。

---

## 📄 License

MIT License
