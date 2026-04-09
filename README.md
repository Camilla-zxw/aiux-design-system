# AIUX Design System

本仓库包含 AIUX 官方的统一视觉与排版规范库。本规范的核心目标是**“让复杂的 AI 逻辑消失于无形”**，告别传统 AI 生成物千篇一律的廉价科技感，构建具有专业克制与人文温度的数字体验。

## 文件结构 (Files)

| 文件名 | 描述 |
|------|-------------|
| `DESIGN.md` | 核心视觉架构文档（包含色彩、排版、组件及去 AI 化护栏等 9 大模块的完整 Token 表）。 |
| `preview.html` | 交互式设计 Token 预览页（明亮模式）。 |
| `preview-dark.html` | 交互式设计 Token 预览页（暗黑模式）。 |

**🚀 核心调用方式：** 请将 `DESIGN.md` 作为顶级系统提示词（System Prompt）或上下文文件，投喂给 AI 代理（如 OpenClaw, Cursor, Claude, 或是生成式 UI 引擎）。Agent 将精准读取我们的字号律动、8px 栅格以及护栏规则，生成符合 AIUX 调性的网页、演示文稿或调研报告。

## 视觉预览 (Preview)

基于 `DESIGN.md` 构建的示例组件库。你将在此页面直观感受到：

* **克制的底色**：告别纯白，使用带有微弱人文暖灰的珍珠白 (`#FAFAFA`) 作为呼吸画布。
* **严谨的排版**：Roboto 搭配思源黑体 (Source Han Sans SC)，呈现 1.6 行高的最佳阅读律动。
* **点睛的锋芒**：极简界面中，精准克制地使用 AIUX Red (`#FF0217`) 作为交互锚点。
* **无痕的层级**：全局 0 阴影，深度全部交由背景色阶与毛玻璃材质 (Frosted Glass) 传递。

### 亮色模式 (Light Mode)
![AIUX Design System — Light Mode](preview-light.png)

### 暗黑模式 (Dark Mode)
![AIUX Design System — Dark Mode](preview-dark.png)