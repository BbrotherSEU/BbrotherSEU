<div align="center">

# 范彬 · Fan.Bin

**架构师 @ HSBC · 上海**

大数据 · 高性能 · AI

把复杂度收进架构，把想法做成能跑的东西。

`中文` · [`English`](README_en.md)

[![GitHub](https://img.shields.io/badge/GitHub-BbrotherSEU-181717?style=flat-square&logo=github)](https://github.com/BbrotherSEU)
[![Since](https://img.shields.io/badge/since-2015-6e5494?style=flat-square)](#)
[![Location](https://img.shields.io/badge/📍_Shanghai-0aa1dd?style=flat-square)](#)

</div>

---

## 关于我

我是范彬（Fan.Bin），目前在 **HSBC** 担任架构师。长期关注三个方向：**大数据** —— 海量数据的采集、建模与治理；**高性能** —— 把延迟和吞吐当成设计约束，而不是上线后再优化；**AI** —— 让大模型真正嵌进业务流程，而不是停在 Demo。

工作之外有两条主线：**把 AI 用进真实场景**，以及**把想法做成能点开就看到效果的成品** —— 从浏览器里的 3D 小店，到能装进手机的卡牌游戏。

---

## 🚧 正在做

### ⚽ AI 足球

> 用 AI 理解足球。

把比赛与训练过程变成可计算的数据：事件结构化、战术识别、球员与阵容表现评估。
目标是把「看比赛」变成「读数据」，让分析结论能直接指导训练和选人。

`状态：进行中` · 方案与代码陆续整理公开

### 📊 AI 大数据

> 让大模型长在数据栈上。

自然语言查询、指标异常归因、自动生成分析结论 —— 把「取数 → 分析 → 出报告」这条链路交给 Agent，
把人从写 SQL 和手工做表里解放出来。

`状态：进行中`

---

## 01 · AI 项目与想法

| 项目 | 说明 | 技术 |
| :-- | :-- | :-- |
| **[llm_ai_resume_jd_matching](https://github.com/BbrotherSEU/llm_ai_resume_jd_matching)** | 多 Agent 的 HR 简历筛选：Orchestrator 编排 JD 分析、简历解析、匹配打分、欺诈检测四个子 Agent，输出人可读的评估结论。支持 PDF/TXT 拖拽，带 Web UI 与 REST API | `Python` `LLM` `Multi-Agent` |
| **[build-local-ai](https://github.com/BbrotherSEU/build-local-ai)** | 本地大模型环境搭建的全流程手册：NVIDIA 驱动 → CUDA → Ollama → 模型选型与显存估算，附常见坑的排查 | `Python` `Ollama` `CUDA` |
| **[Ad-Service-System](https://github.com/BbrotherSEU/Ad-Service-System)** | 广告系统的想法原型：Node.js 业务层负责请求与回调，机器学习层负责提升下载率与体验。只留研究与思路，不提供完整系统 | `Node.js` `Machine Learning` |
| **[mobikeCup](https://github.com/BbrotherSEU/mobikeCup)** | 2017 年摩拜杯数据竞赛（BIENdata）的参赛记录与建模思路 | `Python` `数据建模` |

---

## 02 · 游戏项目

| 项目 | 说明 | 技术 |
| :-- | :-- | :-- |
| **[sanguo-luanxing](https://github.com/BbrotherSEU/sanguo-luanxing)** | 三国背景的单机叙事 + 战斗 Unity 游戏。玩家从桃林结义一路走到渭水定天下：9 个可探索区域、7 张回合制副本关卡、仕途官阶成长、旗号选择的多分支结局、昼夜流转。内置渲染管线，纯 C# 无第三方依赖，自定义 Toon / 描边 Shader | `Unity` `C#` `ShaderLab` `Built-in RP` |
| **[sanguo-cards](https://github.com/BbrotherSEU/sanguo-cards)** | 粉丝向自制的三国卡牌 Web 游戏。程序化 SVG 武将立绘、回合回放战斗演出、突破 / 觉醒、装备强化与掉落、竞技场；横屏专属布局，可添加到手机主屏以全屏 PWA 运行，局域网内手机与电脑共用一份存档 | `TypeScript` `Vite` `Canvas/SVG` `Node` |
| **[forest-shop](https://github.com/BbrotherSEU/forest-shop)** | 浏览器 3D 文具店。Three.js 建模的店铺场景、固定跟随相机、虚拟现金交互与结算流程；状态用 Zustand 管理 | `TypeScript` `React 19` `React Three Fiber` |
| **[kid-shop-3d](https://github.com/BbrotherSEU/kid-shop-3d)** | 课堂版 3D 商店，界面为低年级学生设计，专注练习「元 / 角」换算 | `TypeScript` `Three.js` |

> 前两个是「游戏」，后两个是「游戏化的教学工具」 —— 见下一节。

---

## 03 · 教学项目

| 项目 | 说明 | 技术 |
| :-- | :-- | :-- |
| **[kid-shop-3d](https://github.com/BbrotherSEU/kid-shop-3d)** · 课堂场景 | 一节课就能跑起来，老师不用装软件，打开浏览器就能带着学生练元角换算 | `TypeScript` `Three.js` |
| **[forest-shop](https://github.com/BbrotherSEU/forest-shop)** · 教师端 | 学生每笔交易都被记录：买了什么、算错几次、错在哪一步。老师据此复盘，而不是靠一张卷子判断掌握程度 | `TypeScript` `React` |

**设计思路**：知识点要藏在操作里。孩子不是在做练习题，是在真的买一次东西 —— 算错了就付不出钱。

---

## 04 · 大数据 / Java / 高性能

| 项目 | 说明 | 技术 |
| :-- | :-- | :-- |
| **[mySpringBootRedis](https://github.com/BbrotherSEU/mySpringBootRedis)** | Spring Boot 与 Redis 集成的实践工程：缓存配置、序列化方案、Swagger UI，作为团队新人的后端脚手架参考 | `Java` `Spring Boot` `Redis` |
| **[Tailer](https://github.com/BbrotherSEU/Tailer)** | 通用文件读取程序。重写了 tailer 类，解决文件轮转 / 重命名后导致的重复读取问题 | `Java` |
| **[KnowledgeEveryDay](https://github.com/BbrotherSEU/KnowledgeEveryDay)** | Java 方向的日常技术积累与验证代码 | `Java` |

---

## 🧰 技术栈

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

---

## 📊 GitHub

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=BbrotherSEU&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BbrotherSEU&layout=compact&hide_border=true&langs_count=8" />

</div>

---

## 📮 联系

<div align="center">

GitHub 是最快的联系方式 → **[@BbrotherSEU](https://github.com/BbrotherSEU)**

项目有用就 Star ⭐，有想法就开 Issue —— AI 足球、AI 大数据和卡牌游戏这三个方向尤其欢迎聊。

</div>

<div align="center">
<sub>Made with ☕ in Shanghai</sub>
</div>
