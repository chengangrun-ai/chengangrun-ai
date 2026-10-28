<div align="center">

<h1>嗨，我是 Cami 👋</h1>

<p><strong>不会写代码，但我让 AI 把想法跑成了能用的产品。</strong></p>

<p>重本音乐院校毕业 · 全职交易员 · 营养师</p>

<p>
<a href="https://opensourceoss.pages.dev/">🌍 开源官网</a> ｜
<a href="https://github.com/chengangrun-ai?tab=repositories">🧩 全部仓库</a> ｜
<a href="https://opensourceoss.pages.dev/download">📱 下载 App</a>
</p>

</div>

---

重本音乐院校毕业，却是一名全职交易员和营养师，完完全全不会写代码。

但我用 AI Agent 把「要是有人能替我干活就好了」变成了一个个真实跑起来的产品：交易平台、输入法、简历工具、拼豆图纸、相册清理、垃圾清理，都是这么来的。

**11 个项目 · 16 个公开仓库 · 代码全在里面。** 接下来还会继续捣鼓，希望你也一起参与。

---

## 🆕 刚刚开源

### [公子简历作坊 · CV Studio](https://github.com/chengangrun-ai/cv-studio)

**一份数据，四套版式，六道体检。** 左边填资料，中间实时变，右边告诉你这份简历机器到底读不读得懂。

不是拍脑袋定的：先把五个开源简历工具拆开量了一遍——51 份语料、3 个解析器、98 条测量，量出六种死法。最狠的是双栏版式，文字还原率 100%，字段顺序 **0%**。

```
单栏纯文本  →  还原 100% · 顺序 100%
双栏侧边栏  →  还原 100% · 顺序   0%
图片型 PDF  →  还原   0% · 顺序   0%
```

所以版式天生安全：单栏、姓名在首块、有文字层，三条由渲染器保证；剩下三条内容项你自己决定。四套皮肤换着看——衬线学术 / 工程等宽 / 极简无衬线 / 中文国企。微信或邮箱登录，手机电脑打开是同一份。

<sub>HTML · 零依赖 · MCP 服务器 · [线上直接用](https://gongzi-cv.app.workbuddy.host/?sharecode=AHSMNLSLAM)</sub>

---

## 📦 全部项目

六类，按用途排。点名字进仓库。

### 💹 交易与金融

[**开源 · Open Source**](https://github.com/chengangrun-ai/opensourceoss) — 交易领域的极致开源网站

免费 TradingView 指标 · 量化信号 · 软件工具 · 一周集训课 · 合作券商，安卓 App 直接装，一个入口全给。

<sub>HTML · Cloudflare Pages · [线上已跑起来](https://opensourceoss.pages.dev/)</sub>

### 📖 语言与学习

[**公子输入法 · WordBridge**](https://github.com/chengangrun-ai/wordbridge) — 边打字边学英语

你打拼音出中文，候选词旁边挂着**英文释义 + 音标 + 考试等级**，上屏永远是中文——不弹窗、不改字、不打断节奏。

```
输入 diannao   →  电脑   computer /kəmˈpjuːtə/ 〔高考〕
输入 xuexi     →  学习   to learn; to study 〔高考〕
输入 pingguo   →  苹果   apple /ˈæpl/ 〔高考〕
```

10.9 万条中文词的英文释义 · 2.5 万词 IPA 音标 · 1.07 万词等级标签，5.97 MB 纯文本，全程离线。装在 Windows 的清风输入法上，双击一个 bat 就装好，改配置前自动备份。

<sub>Python · GPL-3.0 · Windows</sub>

### 📱 手机 App

[**删了么**](https://github.com/chengangrun-ai/shanleme) — 滑卡整理相册：左滑删 · 右滑留 · 上滑精选

把「判断」和「操作」拆开，手只负责判断，一秒一张；删除的动作攒到最后统一做一次。

<sub>TypeScript · Expo / React Native · MIT · ⚠️ 真删功能还在做</sub>

### 🎨 图像与创意

[**拼豆公子**](https://github.com/chengangrun-ai/pindou-gongzi) — 把任何图片变成拼豆图纸

四张成品图 + 带色号图纸 + 可直接发布的文案台账，一条命令跑完；附 12 条真实踩坑记录。

<sub>Python · MIT · 命令行</sub>

[**公子图纸原创**](https://github.com/chengangrun-ai/gongzi-original) — 参考图 → 一整套能卖、能举证原创的图纸

参考图只用来「量」风格（配色、线宽、纹理、构图），画面全部由代码从零画；15 个风格包 / 85 个造型 / 168 款全量质量 0.922。

<sub>Python · MIT · 命令行</sub>

### 🏗️ AI 编程工作流

[**camiAI 编程全流程**](https://github.com/chengangrun-ai/camiai-programming-workflow) — 五步从需求到验收

环境搭建 → 产品设计（可跳）→ 技术设计（可跳）→ 实现 → 人工验证。拿到的是跑得起来、能回退的产品，不是一堆没验证的代码。

<sub>Agent Skill · MIT</sub>

[**公子教代码做事**](https://github.com/chengangrun-ai/gongzi-teaches-code) — 写之前先问「这段代码真的需要写吗」

一个主技能 + 五个配套，从动手前拦一下，到事后查账。六步走完，常常是零行代码或者一行。

<details>
<summary>五个配套仓库</summary>

- [改动审查](https://github.com/chengangrun-ai/gongzi-teaches-code-review) — 只看这次 diff，一行一条，结尾给 `net: -N lines`
- [整仓审计](https://github.com/chengangrun-ai/gongzi-teaches-code-audit) — 扫整个仓库，按能砍多少从大到小排名
- [欠账本](https://github.com/chengangrun-ai/gongzi-teaches-code-debt) — 把所有「以后再说」的注释收成一张表
- [效果看板](https://github.com/chengangrun-ai/gongzi-teaches-code-gain) — 基准测试中位数：代码量、成本、速度
- [速查卡](https://github.com/chengangrun-ai/gongzi-teaches-code-help) — 忘了怎么用就说一句

</details>

<sub>Agent Skill · 基于 Ponytail (MIT) 改写</sub>

### 🔧 效率工具

[**公子简历作坊**](https://github.com/chengangrun-ai/cv-studio) — 写简历，顺手做六道机器可读性体检

一份数据四套版式：衬线学术 / 工程等宽 / 极简无衬线 / 中文国企。登录后存云端，手机电脑打开是同一份。

<sub>HTML · 零依赖 · MCP 服务器 · [线上直接用](https://gongzi-cv.app.workbuddy.host/?sharecode=AHSMNLSLAM)</sub>

[**Windows 垃圾清理**](https://github.com/chengangrun-ai/cleanup-junk) — 先扫描出报告，确认后才动手

删除一律进回收站，绝不碰桌面、文档、下载等个人目录。仅支持 Windows。

<sub>PowerShell · Agent Skill</sub>

[**MT5 编译兜底**](https://github.com/chengangrun-ai/mt5-ex5-fallback) — 沙箱编不出 .ex5 时的替代路径

MetaEditor 报 0xC0000139、安装包被拦、需要认证时，一键本地编译脚本直接放到桌面。

<sub>Agent Skill · MetaTrader 5</sub>

[**跨平台调研**](https://github.com/chengangrun-ai/agent-reach) — 一次查清一个话题

零配置起步，多通道并行检索，把散在各处的说法收成一份能看的结论。

<sub>Agent Skill</sub>

---

## 🚀 怎么用

工具类仓库全部是 [Agent Skills](https://agentskills.io/specification) 开放格式，支持 WorkBuddy、Claude Code、Cursor、Codex 等。

```bash
npx skills add chengangrun-ai/pindou-gongzi
```

或者把仓库链接直接丢给你的 Agent，它会读 `SKILL.md` 自己上手。

软件类（输入法、删了么、开源 Open Source）按各仓库 README 里的步骤装。

---

## English

A music-school graduate. Full-time trader and nutritionist. **I don't write code.**

I use AI agents to turn "this should be automatic" into products that actually run:

- **[CV Studio](https://github.com/chengangrun-ai/cv-studio)** — a résumé builder with one dataset and four layouts, plus six machine-readability checks derived from measuring 51 résumés across 3 parsers.
- **[WordBridge](https://github.com/chengangrun-ai/wordbridge)** — a Chinese IME candidate layer showing English gloss, IPA and exam-level tags while you type. Offline, 109k entries, GPL-3.0.
- **[Open Source](https://opensourceoss.pages.dev/)** — a trading-education platform: free TradingView indicators, quant signals, courses, Android app.
- **[删了么](https://github.com/chengangrun-ai/shanleme)** — an open-source app that cleans your camera roll by swiping (Expo / React Native).
- **[Pindou Gongzi](https://github.com/chengangrun-ai/pindou-gongzi)** — turn any image into a perler-bead pattern, with color codes and a caption ledger.

Everything under `Agent Skill` is in the open [Agent Skills](https://agentskills.io/specification) format. Install with `npx skills add chengangrun-ai/<repo>`.

---

<sub>Follow builders, not influencers.</sub>
