# NEO·DEV 个人技术工作室
> 项目官网：[dcode.org.cn](https://dcode.org.cn)

个人技术展示站点，基于 uni‑app + Vue3 构建，侧重交互细节、页面动效与工程化实践。
站点以可运行实验室Demo的形式展示技术能力，包含交互粒子、AI流式对话、工程化配置、开发规范、个人成长时间线与技术服务介绍，所有演示页面均可直接运行观测。

## ✨ 功能特性
- 📄 个人主页与关于我：个人技术栈、技能熟练度、学习理念展示
- 🧪 **粒子实验室**：requestAnimationFrame + 离屏Canvas预渲染实现粒子动效；内置FPS性能监控；支持鼠标拖尾粒子、点击粒子爆炸、十秒点击挑战小游戏，可直观观测动画性能表现
- 🤖 **AI对话实验室**：对接大模型实现SSE流式逐字输出；包含超时指数退避重试、断连续写、错误分级处理、接口耗时统计，支持多会话管理
- ☁️ uniCloud实践演示：集合结构、索引设计、权限规则示例，统一 errCode 错误返回格式参考
- ⚙️ 工程化实践示例：ESLint + Prettier + commitlint + husky + Vitest 完整前端工程化落地配置参考，CI思路展示
- 📜 协作与规范：Git分支策略、Conventional Commits提交规范、PR模板、Code Review检查清单
- 📈 成长轨迹时间线：2019至今学习路径，记录各阶段技术栈、产出与关键收获
- 🛠️ 技术服务介绍：软件开发定制、网站开发、小程序开发、App上架协助、软著申请指导等服务说明
- ❓ 常见问题折叠面板：技术经验自问自答，适合开发者参考
- 📱 响应式布局：PC、移动端适配，打磨交互动效体验

> 说明：个人备案站点无法展示真实商业项目界面与业务数据，全部能力以可运行Demo、配置样例形式呈现，仅供学习参考，不用于商业生产。

## 📦 技术栈
- 前端框架：Vue3 / uni‑app
- 动效渲染：Canvas（离屏）、requestAnimationFrame
- AI能力：SSE 流式接口
- 工程化：ESLint、Prettier、husky、commitlint、Vitest
- 云开发：uniCloud
- 部署：H5静态站点

## 🚀 本地运行
1. 克隆仓库
```bash
git clone 你的仓库地址
cd neo‑dev‑studio
