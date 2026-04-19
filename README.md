# 🚀 飞飞学伴 FeiFei Companion v4.0

<p align="center">
  <img src="https://img.shields.io/badge/Version-4.0.0-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-Apache%202.0-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/OpenClaw-Skill-brightgreen?style=for-the-badge" alt="OpenClaw">
  <img src="https://img.shields.io/badge/K12-AI%20Education-orange?style=for-the-badge" alt="K12">
</p>

<p align="center">
  <strong>AI陪你飞，学习不费力！</strong><br>
  <strong>AI-powered learning companion — let your potential take flight!</strong>
</p>

<p align="center">
  <a href="https://github.com/SimonsTang/feifei-companion">GitHub</a> •
  <a href="https://clawhub.ai/skill/feifei-companion">ClawHub</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#使用示例">使用示例</a> •
  <a href="#功能详解">功能详解</a>
</p>

---

## 📖 目录 Table of Contents

- [🌟 项目简介](#-项目简介)
- [🎯 核心特性](#-核心特性)
- [🚀 快速开始](#-快速开始)
- [💡 使用示例](#-使用示例)
- [📚 功能详解](#-功能详解)
- [👥 关于学来学去学习社](#-关于学来学去学习社)
- [📄 版权与许可](#-版权与许可)
- [🔗 相关链接](#-相关链接)

---

## 🌟 项目简介

**飞飞学伴（FeiFei Companion）**是由[学来学去学习社](#关于学来学去学习社)开发的AI智能教育陪伴系统，采用**三位一体**架构设计，为中国K12家庭提供全方位的学习支持。

### 三位一体架构 Trinity Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                   🚀 飞飞学伴 FeiFei Companion               │
│                                                             │
│  ┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│  │  🎖️ 菲菲老师     │  │  📚 小菲学姐     │  │  🔬 浩云学长     │
│  │  (刘一菲)        │  │  (刘小菲)        │  │  (唐浩云)        │
│  │  总管调度        │  │  文科辅导        │  │  理科辅导        │
│  │  知识网络总控    │  │  诗词作文英语    │  │  数理化编程      │
│  │  亲子沟通        │  │  雅思8分才女     │  │  UCL理科学霸     │
│  └─────────────────┘  └─────────────────┘  └─────────────────┘
└─────────────────────────────────────────────────────────────┘
```

### 设计理念 Design Philosophy

> "每个孩子都值得被看见，每个梦想都值得被托举！"
> 
> "Every child deserves to be seen, every dream deserves to be supported!"

我们坚信：**AI不是替代老师，而是成为每个孩子的专属学习伙伴。**

---

## 🎯 核心特性

| 特性 Feature | 说明 Description | 示例 Example |
|-------------|-----------------|-------------|
| 🌸 **三位一体** | 一个入口集成总管+文科+理科+亲子 | 数学问浩云，诗词问小菲，规划找菲菲 |
| 🧠 **知识网络** | 全科知识图谱，薄弱点智能定位 | "第三单元不会"→自动定位人教版八年级第14章一次函数 |
| 📚 **教材同步** | 紧扣人教版/统编版等主流教材 | 支持语文1-12年级、数学7-12年级全版本 |
| 🎯 **考点精讲** | 知识点/考点/难点三维讲解 | 中考必考：二次函数与圆的综合应用 |
| 💬 **亲子翻译** | 化解家长与孩子的沟通障碍 | "你怎么这么慢！"→"宝贝，妈妈看到你遇到难题了" |
| 📊 **学习报告** | 每日简报+每周周报+家长沟通报告 | 掌握度追踪、遗忘曲线复习提醒 |
| 🔄 **心跳任务** | 主动AI：唤醒→发任务→校验→循环 | 到点自动提醒学习，无需家长催促 |
| 🎓 **MIT 48h学习法** | 三阶段提问法快速掌握陌生领域 | 领域共识→争议焦点→鉴别性考题 |
| 🇬🇧 **双语支持** | 中英文无缝切换 | 作文批改同时提供中英文反馈 |

---

## 🚀 快速开始

### 安装方式 Installation

#### 方式一：OpenClaw 本地安装
```bash
# 克隆到 OpenClaw skills 目录
git clone https://github.com/SimonsTang/feifei-companion.git ~/.openclaw/skills/feifei-companion

# 安装完成，立即使用
# 在 OpenClaw 中输入：飞飞学伴 或 FeiFei Companion
```

#### 方式二：ClawHub 一键安装
```bash
# 通过 ClawHub CLI 安装
npx clawhub@latest install feifei-companion
```

#### 方式三：GitHub Codespaces（免配置）
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/SimonsTang/feifei-companion/codespaces)

### 环境要求 Requirements

- Python 3.10+
- OpenClaw >= 2.0 或 Claude Code / Cursor / Codex
- 可选：腾讯云API密钥（用于AI对话功能）

---

## 💡 使用示例

### 示例 1：数学辅导（浩云学长）

**用户输入：**
```
我数学八年级下册的一次函数不太懂，可以帮我讲讲吗？
```

**飞飞学伴响应：**
```
🎯 菲菲老师分析中...

📍 知识定位：人教版八年级下册 → 第19章 一次函数
📊 前置检查：
   ✅ 平面直角坐标系（掌握度 85%）
   ✅ 变量与常量（掌握度 90%）
   ⚠️  函数概念（掌握度 60%，建议先复习）

👨‍🏫 正在为你分派：浩云学长（UCL理科学霸）

---
🔬 浩云学长讲解：
"这个简单。来，我给你推一遍..."

【第一性原理拆解】
一次函数 y = kx + b 的本质是：
- k：斜率（变化率）
- b：截距（起始点）

【已知→未知推导】
你已经学过：一元一次方程 ax + b = 0
→ 类比：一次函数 y = kx + b 是方程的"可视化"

【例题】...
```

### 示例 2：诗词赏析（小菲学姐）

**用户输入：**
```
帮我赏析一下李白的《静夜思》，还想知道怎么用这首诗写作文
```

**飞飞学伴响应：**
```
📚 小菲学姐来啦！

【诗词深度赏析】
《静夜思》李白
"举头望明月，低头思故乡"

🌙 意象解读：
"明月"在中国文化中 = 思乡、团圆、孤独
这种意象从《诗经》延续至今...

【作文素材迁移】
💡 适用主题：
1. 乡愁/思念 → 直接用"明月"意象
2. 传统文化 → 引用诗句增加文采
3. 对比手法 → 举头↔低头的动作对比

【写作示例】
写"我的故乡"：
"正如李白'举头望明月，低头思故乡'，每当夜深人静..."

【英语作文迁移】
用"moon"意象写 "My Hometown":
"The moon shines the same over my hometown..."
```

### 示例 3：亲子沟通（菲菲老师）

**家长输入：**
```
孩子最近总是玩手机，作业拖到晚上11点，我怎么说他都不听，怎么办？
```

**飞飞学伴响应：**
```
💞 菲菲老师理解您的焦虑

【亲子翻译官】
👨‍👩‍👧 您的焦虑 → 孩子的感受：
"你又玩手机！作业做完了吗？" 
→ 孩子听到的："妈妈只关心作业，不关心我"

💡 建议表达方式：
"妈妈注意到你最近用手机时间比较久，是有什么有趣的内容吗？
我们可以一起制定一个时间表，既不影响学习，也能有放松时间。"

【深层分析】
根据知识网络理论，作业拖拉往往不是因为"懒"，而是因为：
1. 任务太大 → 拆解为25分钟番茄钟
2. 缺乏兴趣 → 关联孩子喜欢的内容
3. 情绪问题 → 需要心理陪伴

【21天习惯养成计划】
Day 1-7：共同制定手机使用时间表
Day 8-14：每日打卡，完成奖励
Day 15-21：巩固习惯，复盘调整

需要我生成详细的《家庭手机使用公约》吗？
```

### 示例 4：学习规划（菲菲老师）

**用户输入：**
```
我初三了，离中考还有3个月，怎么规划复习？
```

**飞飞学伴响应：**
```
🎖️ 菲菲老师为您制定中考冲刺计划

【知识网络诊断】
📊 当前掌握度评估（模拟）：
数学：75% | 语文：80% | 英语：70% | 物理：65% | 化学：72%

🔴 薄弱点TOP3：
1. 物理：电学综合（掌握度 55%）→ 浩云学长专项突破
2. 数学：二次函数与圆（掌握度 60%）→ 浩云学长专题讲解
3. 英语：完形填空（掌握度 62%）→ 小菲学姐技巧训练

【3个月冲刺规划】
Month 1（基础巩固）：
- 每天1个薄弱知识点（番茄工作法25min×4）
- 周末知识网络复盘

Month 2（专题突破）：
- 中考真题分类训练
- 错题溯源，前置知识补救

Month 3（模拟冲刺）：
- 全真模拟考试
- 心态调整+应试技巧

【每日学习节奏】
06:30 心跳唤醒 → 07:00 早读（小菲：古诗词/英语）
19:00 理科突破 → 21:00 文科积累 → 21:30 复盘打卡

需要详细的每日任务表吗？
```

### 示例 5：MIT 48小时学习法

**用户输入：**
```
我想快速学会Python编程，有什么高效方法？
```

**飞飞学伴响应：**
```
🧠 菲菲老师推荐：MIT 48小时学习法

【三阶段提问法】

Phase 1：领域共识挖掘（20分钟）
提问："Python编程领域专家公认的5个核心思维模式是什么？"

🔍 核心思维模式：
1. 代码即逻辑可视化
2. 模块化编程思维
3. 数据结构与算法结合
4. 调试即学习过程
5. 开源生态利用

Phase 2：争议焦点定位（20分钟）
提问："Python专家争论最激烈的3个问题及各方的核心论据？"

💬 争议点：
- Python 2 vs Python 3（已解决，选Python 3）
- 动态类型 vs 静态类型（类型提示PEP 484）
- 性能优化：CPython vs PyPy vs Cython

Phase 3：深度理解测试（6小时+）
要求AI生成10个鉴别性考题，区分真实理解与死记硬背：

【考题示例】
1. 为什么Python的GIL会影响多线程性能？
2. 列表推导式 [x for x in range(10)] 的底层实现是什么？
3. 装饰器@staticmethod和@classmethod的本质区别？
...

【48小时执行计划】
Hour 0-2: 建立知识框架（Phase 1+2）
Hour 2-8: 高强度答题+纠错（Phase 3）
Hour 8-48: 项目实战：用Python做一个简单的...（根据兴趣选择）

每道错题追问："为什么错？遗漏了什么核心概念？"

需要我为你生成Python入门10道鉴别性考题吗？
```

---

## 📚 功能详解

### 功能模块总览

| 模块 | 角色 | 核心能力 | 触发方式 |
|------|------|---------|----------|
| 总管调度 | 菲菲老师 | 知识网络总控、学习规划、Agent协调 | "规划""报告""协调" |
| 文科辅导 | 小菲学姐 | 诗词、作文、英语、文科知识 | "诗词""作文""英语" |
| 理科辅导 | 浩云学长 | 数学、物理、化学、编程 | "数学""物理""编程" |
| 亲子沟通 | 菲菲老师 | 翻译官、心理陪伴、家庭教育 | "亲子""沟通""情绪" |

### 详细功能列表

#### 1. 知识网络总控 Knowledge Network Command
- **教材索引导航**：年级+版本+单元 → 精准定位知识点
- **前置知识检测**：自动检查学习新内容前的前置掌握情况
- **薄弱点定位**：根据历史数据精准识别薄弱环节
- **跨学科关联**：数学函数 ↔ 物理运动 ↔ 化学速率

#### 2. 心跳任务 Heartbeat Tasks
主动AI的四大核心动作：
1. **主动唤醒**：到点提醒学习（可设置早晨/放学后/睡前）
2. **主动发任务**：根据知识网络自动生成今日学习任务
3. **主动校验**：确认任务完成，标记掌握度
4. **主动循环**：完成后自动进入下一轮学习

#### 3. 五大学习法 The Five Learning Methods
| 序号 | 方法 | 核心要点 |
|-----|------|---------|
| 1 | 西蒙学习法 | 目标锁定：一次只攻克一个知识点 |
| 2 | 番茄工作法 | 25分钟专注+5分钟休息 |
| 3 | 康奈尔笔记法 | 极简记录：知识点+重点+总结 |
| 4 | 第一性原理 | 根源理解：不背答案、只抓本质 |
| 5 | 费曼学习法 | 输出检验：能讲出来才算真懂 |
| 6 | 闭环复盘 | 自动复盘：总结→巩固→循环 |

#### 4. 文科核心能力 Liberal Arts (小菲学姐)
- 📚 诗词赏析创作（唐诗宋词深度解读）
- ✍️ 作文辅导（三明治反馈法：肯定+建议+鼓励）
- 🔤 英语学习（单词、语法、阅读全方位）
- 📖 文科知识趣讲（历史、文化趣味讲解）
- 🧠 记忆方法训练（记忆宫殿等）
- 🎯 教材同步（统编版语文1-12年级、人教版英语3-12年级）

#### 5. 理科核心能力 STEM (浩云学长)
- 🔢 数学辅导（函数、几何、概率统计）
- ⚡ 物理辅导（力学、电磁学、光学）
- 🧪 化学辅导（反应原理、元素周期）
- 💻 编程启蒙（Python、AI思维、算法基础）
- 🔬 科学思维（第一性原理、实验精神）
- 🎯 教材同步（人教版/北师大版7-12年级）

#### 6. 亲子沟通 Parent-Child Communication
- **双向翻译**：把家长焦虑翻译成孩子理解，把孩子心声翻译给家长
- **情绪疏导**：识别情绪信号，提供调节方法
- **升学指导**：小升初+中考规划，学校选择建议
- **习惯养成**：21天习惯养成计划+每日打卡
- **成长陪伴**：发现天赋、制定目标、持续跟进

#### 7. 学习报告 Report Templates
- **每日简报**：今日完成、专注时长、掌握度更新
- **每周周报**：完成情况、知识网络变化、薄弱点趋势
- **家长沟通报告**：整体掌握度、需关注点、本周亮点、下周计划

---

## 👥 关于学来学去学习社

### 我们的使命

**学来学去学习社（Xue Lai Xue Qu Learning Society）**致力于用AI技术革新K12教育，让每个孩子都能享受到个性化的学习陪伴。

> "给不一样的孩子，拥有不一样的人生！"

### 团队背景

| 角色 | 背景 | 专业领域 |
|------|------|---------|
| 🎖️ 菲菲老师 (刘一菲) | 美国索菲亚大学心理学博士<br>伦敦大学学院教育学讲师 | 全科辅导、知识网络、亲子沟通、青少年心理 |
| 📚 小菲学姐 (刘小菲) | UCL教育系学生 | 文学、诗词、英语、心理辅导<br>隐藏技能：雅思8分、琴棋书画 |
| 🔬 浩云学长 (唐浩云) | UCL物理系学生 | 数学、物理、化学、编程、AI<br>隐藏技能：编程大牛、游戏高手、效率至上 |

### 核心优势

- 🎓 **学术背景**：UCL等顶尖学府背景，专业可靠
- 🧠 **科学方法**：融合心理学、教育学、认知科学的先进学习法
- 🤖 **AI驱动**：结合大语言模型，提供7×24小时智能陪伴
- 📊 **数据驱动**：知识网络追踪，精准定位薄弱点
- 💞 **人文关怀**：不仅关注学习，更关注成长与心理健康

### 联系我们

- 📧 邮箱：待补充
- 🌐 网站：待补充
- 💬 微信/飞书群：详见GitHub主页

---

## 📄 版权与许可

### 版权声明

**飞飞学伴 FeiFei Companion** 版权所有 © 2026 学来学去学习社

### 开源协议

本项目采用 [Apache License 2.0](LICENSE) 开源协议。

```
Copyright 2026 Xue Lai Xue Qu Learning Society

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### 使用条款

1. **个人使用**：欢迎个人用户免费使用飞飞学伴进行学习
2. **教育机构**：如需在教育机构中使用，请联系获取授权
3. **二次开发**：遵循Apache 2.0协议，允许 fork 和修改，但需保留版权声明
4. **商业用途**：商业使用需获得书面授权

### 免责声明

飞飞学伴是AI辅助学习工具，旨在提供学习支持，不能替代：
- 专业教师的面对面教学
- 心理医生/心理咨询师的专业诊断
- 家长/监护人的陪伴与引导

使用本产品即表示您理解并同意以上条款。

---

## 🔗 相关链接

| 平台 | 链接 | 说明 |
|------|------|------|
| GitHub | [github.com/SimonsTang/feifei-companion](https://github.com/SimonsTang/feifei-companion) | 源码仓库 |
| ClawHub | [clawhub.ai/skill/feifei-companion](https://clawhub.ai/skill/feifei-companion) | OpenClaw技能市场 |
| 历史版本 | [feifei-learning-commander](https://github.com/SimonsTang/feifei-learning-commander) | 原菲菲老师v3.5.1 |
| 历史版本 | [xiaofei-liberal-arts](https://github.com/SimonsTang/xiaofei-liberal-arts) | 原小菲学姐v3.5.0 |
| 历史版本 | [haoyun-stem-tutor](https://github.com/SimonsTang/haoyun-stem-tutor) | 原浩云学长v3.5.0 |

### 推荐相关项目

- [CLI-Anything](https://github.com/HKUDS/CLI-Anything) - 让AI接管任何软件
- [GSD](https://github.com/gsd-build/get-shit-done) - Spec-Driven Development框架

---

## 🙏 致谢

感谢以下个人和机构对飞飞学伴的支持：

- **学来学去学习社**全体成员
- **香港大学数据科学实验室（HKUDS）** - CLI-Anything项目启发
- **所有用户**的反馈和建议

---

<p align="center">
  <strong>学来学去学习社 | Xue Lai Xue Qu Learning Society</strong><br>
  <em>AI陪你飞，学习不费力！</em><br>
  <em>AI-powered learning companion — let your potential take flight!</em>
</p>

<p align="center">
  <a href="https://github.com/SimonsTang/feifei-companion/stargazers">⭐ Star 我们</a> •
  <a href="https://github.com/SimonsTang/feifei-companion/issues">🐛 提交问题</a> •
  <a href="https://github.com/SimonsTang/feifei-companion/pulls">🤝 贡献代码</a>
</p>
