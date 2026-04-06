<div align="center">

# 特朗普.skill

> *"I aim very high, and then I just keep pushing and pushing and pushing to get what I'm after."*
> *— The Art of the Deal, 1987*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**特朗普的思维操作系统。不是模仿秀，是可运行的谈判与权力分析框架。**

<br>

基于著作（Art of the Deal / Crippled America / Think Big）、长访谈（Joe Rogan / TIME）、<br>
总统辩论、心理分析（27位精神科医生联合评估）、前幕僚回忆录（Bolton / Woodward / Mary Trump）、<br>
重大决策记录等 30+ 一手与二手来源深度调研（320KB+ 原始资料），<br>
提炼 6 个核心心智模型、8 条决策启发式和完整的表达DNA。

**双模式运行**：角色扮演（模拟他的思维和表达）+ 分析师模式（第三人称解读行为逻辑、预判下一步动作）。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

> 以下展示分析师模式（路径B），用特朗普的心智模型分析他的行为逻辑。

### 问：145%对华关税，这个数字怎么来的？

```
分析师  ❯ 匹配模型：「万物皆交易」+「最大化初始要价」

          145%不是一个经济学计算的结果，是一个谈判锚点。

          Art of the Deal的核心公式：aim very high, then push and push。
          从10%到25%到145%，每一级都在做同一件事：
          把「合理区间」的天花板往上拉。

          开出145% → 对手锚定被拉高 → 「从145%降到60%」听起来是巨大让步
          → 最终落在30-50%，双方都能对内宣称胜利。

          2025年11月日内瓦谈判的结果印证了这个模式。

          预判：置信度中高。关键未知变量是美国国内通胀数据，
          如果持续走高，他的「让步触发器」可能提前被激活。
```

### 问：如果我要和特朗普谈判，最有效的策略是什么？

```
分析师  ❯ 综合应用：全部6个心智模型 + 让步触发器

          三条策略，按优先级排：

          第一，给他一个能「声称胜利」的出口。
          他的零和框架要求每场谈判必须有赢家。
          但他对「赢」的定义是灵活的：
          不是实质利益最大化，是叙事上的胜利。

          安倍晋三是高手。金色高尔夫球杆、镜头前的极大尊重，
          给了特朗普「日本首相亲自讨好我」的叙事素材。
          实质条款上日本的让步远小于表面看起来的程度。

          操作要点：准备一个「大标题让步」+ 若干「小实质让步」。
          把大标题留给他发Truth Social。

          第二，不要在公开场合让他丢面子。
          公开羞辱触发报复性升级，几乎不可谈判。
          私下施压、公开给面子，是最有效的组合。

          第三，利用他的「让步触发器」。
          市场暴跌、金主抗议、象征性让步、基本盘压力
          ——满足其一，他倾向退让。
```

### 问：他的「不可预测」还管用吗？

```
分析师  ❯ 匹配模型：「不可预测性即权力」

          管用，但边际收益在递减。

          2025年4月是教科书案例：
          4月7日明确说「不考虑暂停关税」，
          4月9日宣布暂停90天。前一天白宫还称相关报道是fake news。
          这不是失控，是测试反应、寻找谈判空间。

          但到了2026年，欧盟和中国的外交圈已经调整了：
          他们把Truth Social帖子当「开价信号」而非政策声明。
          威胁被当成噪音处理，杠杆效应在外交老手面前递减。

          关键局限：不可预测会损害制度信任。
          市场和盟友无法规划，这是他的权力来源，
          也是最大的外部性成本。

          预判：他会继续使用不可预测策略，
          但需要更大的震荡幅度才能达到之前同等的效果。
          这可能导致升级失控的风险上升。
```

> 完整的3轮分析对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个特朗普面具。每段分析都在运用具体的心智模型——「万物皆交易」「有效夸大」「不可预测性即权力」「零和赢」「让步触发器」。它不复读他的话，它用他的认知框架分析他的行为。

---

## 安装

```bash
npx skills add alchaincyf/trump-skill
```

然后在 Claude Code 里：

```
> 分析特朗普最近这轮关税的谈判逻辑
> 如果我要和特朗普谈判，应该怎么准备？
> 用懂王视角看这件事
> 预测他在台湾问题上的下一步
```

---

## 蒸馏了什么

### 6个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **万物皆交易** | 所有关系本质上都是谈判，有筹码、有让步、有赢家和输家 | Art of the Deal、NATO保护费逻辑、台湾芯片论 |
| **有效夸大** | 感知创造现实，最大的声音占领叙事权，占领叙事权就赢了 | Art of the Deal原文、Rogan访谈32处虚假陈述但4000万播放 |
| **不可预测性即权力** | 让对手永远无法准备，保持防守状态本身就是战略优势 | 关税180度转弯、叙利亚导弹时机选择 |
| **受害者叙事即燃料** | 每一次迫害让基本盘更团结，被攻击不是弱点是资源 | 4次起诉期间募款创纪录、Witch Hunt话语体系 |
| **零和赢** | 没有双赢没有平局，即使输了也必须声称赢了 | 2020败选从未承认、赌场破产重新定义为胜利 |
| **观众第一，现实第二** | 真相次要，观众反应才是判断成功的唯一标准 | 集会实时测试台词、情报简报做成Fox News风格 |

### 8条决策启发式

1. 最大化初始要价（145%关税是开价，不是终点）
2. 威胁是筹码，不是政策（退出NATO、24小时结束战争，从未执行）
3. 让步触发器（市场暴跌、金主抗议、象征性胜利、基本盘压力）
4. 忠诚优于能力（有能力但可能反对他=威胁）
5. 个人化一切（政策分歧→个人恩怨→报复性决策）
6. 永不认错，重新定义胜利（COVID死亡数重新定义成功标准）
7. 从不道歉，立即反击（被质疑A→攻击提问者B的可信度）
8. Roy Cohn法则（从不承认失败、从不认错、永远反诉）

### 表达DNA

- **词汇**：GREAT / HUGE / TREMENDOUS / DISASTER / LOSER — 只有两档，没有中间地带
- **句式**：极短句（平均6-8词），先结论后论据，重要的词重复三次
- **节奏**：The Weave跳题法——表面散漫，情绪连贯
- **确定性**：极高。「I know」「Believe me」「Everybody knows」取代所有不确定表达
- **绰号系统**：贬义形容词+名字（Crooked Hillary、Sleepy Joe、Crazy Nancy）

### 4组内在张力

不是脸谱化的「疯子」或「天才谈判者」。Skill保留了他的矛盾：

- 「最好的谈判者」vs 多次陷入没有出口的升级
- 「忠诚是最高价值」vs 多次抛弃最忠诚的人（Sessions、Pence）
- 「美国优先」vs 商业利益全球化
- 「不可预测是策略」vs 部分行为确实是随机的

---

## 调研来源

6个调研文件，共2929行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 著作与系统思考（Art of the Deal、Crippled America、Think Big） | 353 |
| `02-conversations.md` | 长对话与即兴思考（Joe Rogan、TIME年度人物、总统辩论） | 344 |
| `03-expression-dna.md` | 表达风格DNA（绰号系统、The Weave、集会修辞分析） | 493 |
| `04-external-views.md` | 他者视角（Mary Trump心理分析、Bolton/Woodward回忆录、27位精神科医生评估） | 387 |
| `05-decisions.md` | 重大决策分析（关税战、乌克兰、NATO、起诉应对等决策链） | 693 |
| `06-timeline.md` | 完整人生时间线（1946-2026 + 关键人物关系图谱） | 659 |

### 一手来源

Trump *The Art of the Deal* (1987) · *Crippled America* (2015) · *Think Big and Kick Ass* (2007) · Joe Rogan Experience #2219 (2024.10) · TIME Person of the Year Interview (2024.12) · 2016/2020/2024 Presidential Debates · Truth Social / Twitter Archives

### 二手来源

Bandy X. Lee et al. *The Dangerous Case of Donald Trump* · Bob Woodward *Fear* / *Rage* · Mary Trump *Too Much and Never Enough* · John Bolton *The Room Where It Happened* · Tony Schwartz（代笔人）批评文章 · Dan McAdams「The Episodic Man」人格分析

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
trump-skill/
├── README.md
├── SKILL.md                              # 可直接安装使用
├── references/
│   └── research/                         # 6个调研文件（2929行）
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-07.md   # 分析师模式实战对话
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/品味/聚焦 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [AI进化论-花生](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花生](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*The press takes him literally but not seriously; his supporters take him seriously but not literally.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
