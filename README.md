# 🍖 电商详情页策划 Skill

> 不是 AI 自动出图工具。是一个帮设计师"想清楚再动手"的前期策划引擎。

[![Skill Type](https://img.shields.io/badge/type-WorkBuddy%20Skill-1A6B8A)](https://github.com/497832698/ecommerce-detail-page-skill)
[![Version](https://img.shields.io/badge/version-v1.2.0-27AE60)](https://github.com/497832698/ecommerce-detail-page-skill/releases)
[![Platform](https://img.shields.io/badge/platform-淘宝%20|%20天猫%20|%20京东%20|%20拼多多-e03e2d)](https://github.com/497832698/ecommerce-detail-page-skill)
[![Phase](https://img.shields.io/badge/品类-零食🍒🍬🧀🥩%20|%20洗护🧴%20|%20日用品🪣%20|%20小家电📷-orange)](https://github.com/497832698/ecommerce-detail-page-skill)

---

## 它解决什么问题？

设计师做详情页时最难的其实不是"画图"——是**"想清楚"**：

- 竞品在讲什么？他们的文案和画面策略是什么？
- 这一屏到底应该传达什么信息？文案怎么写？配什么画面？
- 为什么这样做？——不只是拍脑袋，要有商业理由。

这个 Skill 把 8 年零食电商设计经验沉淀为自动化工作流，输入一个产品和卖点，输出一份可以直接拿去执行的策划文档。

---

## 当前版本 v1.2.0

相较 v1.0（仅零食通用框架），本版本完成多品类扩展，当前共支持以下品类策划：

| 品类 | 状态 | 画像 / 说明 |
|------|------|------------|
| 零食（通用框架） | ✅ 通用覆盖 | 共享"妈妈买给孩子 + 年轻自用"画像，覆盖儿童零食/肉脯/果干/糖果/坚果 |
| 🧴 洗护用品 | ✅ 专属画像 | `references/categories/wash-care.md`（含广告法合规规则） |
| 🪣 日用品 | ✅ 专属画像 | `references/categories/daily-use.md`（母婴/居家/个护小物/配饰） |
| 🧻 纸品 / 快消 | ✅ 框架覆盖 | 面巾纸、抽纸等，归 `daily-use.md`；案例见 `docs/example-tissue.html` |
| 📷 小家电 | ✅ 专属画像 | `references/categories/small-appliance.md`（风扇/行车记录仪/监控摄像头，弹性逐屏） |

每个品类内置：消费者画像、视觉规则、竞品特征、FBE 示例、逐屏策略差异、广告法合规红线。

## 主要功能

- **品类自动识别**：按产品名+卖点路由到对应画像（零食 / 洗护 / 日用品 / 小家电 / 纸巾等）。
- **竞品真实抓取**：联网搜 3-5 个真实竞品（京东/天猫直链 + 销量数据），沉淀差异化机会（全品类通用 SOP）。
- **FBE 卖点转换**：把「功能参数」翻成「用户好处 + 情绪 + 画面」的人话。
- **逐屏策划**：弹性框架输出 N 屏，每屏主文案≤10字、副文案≤12字，含画面描述与设计理由。
- **视觉方向**：给出配色、摄影、字体、调性建议。
- **广告法合规**：每品类内置红线（食品级≠可食用、防晒 UPF 须真实、风扇禁"制冷/冰感"等）。
- **可编辑品类画像**：`references/categories/*.md` 可本地改真实参数。

## 能做什么（真实案例）

| 产品 | 核心策略 | 输出 |
|------|---------|------|
| 🍒 冻干山楂条 | "全场唯一把真实食材作为视觉主线" | [查看案例](docs/preview-hawthorn.png) |
| 🧀 四重芝士鳕鱼肠 | "全场唯一把芝士从配角升级为主角" | [查看案例](docs/preview-cod.png) |
| 🥩 猪肉脯 | "好肉，不需要甜来撑场面" | [查看案例](docs/preview-pork.png) |
| 🧴 可蒂家婴童泡泡沐浴露 | "全场唯一把初生肌+专利胎脂做成主题" | [案例截图](docs/preview-coddy.png) · [完整文档](docs/example-coddy-bath.html) |
| 📷 手持小风扇 | "全场唯一把双DC无刷电机+五档精细风控做成技术突破口" | [案例截图](docs/preview-fan.png) · [完整文档](docs/example-handheld-fan.html) |
| 🧻 云柔感纸面巾 | "平价带里唯一把食品级保湿因子做成主题" | [完整文档](docs/example-tissue.html) |
| 🥣 吸盘式PPSU吸汤碗 | "唯一把吸得牢+不洒不翻的防翻防洒逻辑讲透" | [完整文档](docs/example-suction-bowl.html) |
| 🍼 飞鹤婴幼儿奶粉 | "唯一把100种多维营养+吸收逻辑做成科研主题" | [完整文档](docs/example-feihe-milk.html) |

每个案例都包含：竞品数据分析（附真实链接）→ FBE卖点转换 → 逐屏策划（小家电等卖点密集品类可 10+ 屏，文案 ≤ 10字 + 画面描述 + AI Prompt + 设计理由）→ 整体视觉方向。

---

## 使用方法与示例

### 输入格式
对话中提供「产品名称 + 卖点清单」（可选：目标平台、品牌调性）。
输入示例：

> 吸盘式PPSU吸汤碗，卖点：优选硅胶、超大吸盘、分隔不串味、14度内扣盘口设计、加厚餐盘壁单手端也不变形

### 输出格式
单文件 HTML 策划文档，含「消费者洞察 + 竞品分析（真实链接）+ FBE + N 屏逐屏策划 + 视觉方向 + 广告法合规」。
完整输出示例见上方「能做什么（真实案例）」表中的文档链接。

### 自动执行流程
① 识别品类 → ② 联网搜 3-5 个真实竞品（带销量+链接）→ ③ FBE 卖点转换 → ④ 逐屏策划（主≤10字/副≤12字）→ ⑤ 视觉方向 → ⑥ 输出 HTML。

### 补真实参数
本地（VS Code）编辑 `references/categories/*.md`，把占位替换为真实数据。

## 工作流

```
输入产品 + 卖点
    ↓
① 消费者分析        → 谁买？为什么买？担心什么？
    ↓
② 竞品分析          → 自动抓取 3-5 个真实竞品（有销量数据 + 商品直链，WebSearch 优先，故障时子代理兜底）
    ↓
③ FBE 卖点转换      → Feature → Benefit → Emotion → 画面方向
    ↓
④ 逐屏策划（核心）   → 每屏：文案（≤10字） + 画面 + AI Prompt + 设计理由
    ↓
⑤ 视觉方向          → 配色、摄影、字体、调性
    ↓
⑥ 输出策划文档 HTML  → 可直接拿去执行的完整方案
```

---

## 和其他 AI 设计工具有什么不同？

| 普通 AI 对话 | 这个 Skill |
|-------------|-----------|
| "这个详情页应该做得高级大气" | "首屏主文案：好肉，不需要甜来撑场面。（设计理由：暗合消费者对猪肉脯糖太多的不满）" |
| 没有竞品数据支撑 | 每个竞品都附月销量、好评率、真实商品链接 |
| 给你一堆文案随便选 | 每屏主文案严格 ≤ 10 字，副文案 ≤ 12 字 |
| 输出零散想法 | 输出结构化策划文档 HTML，可直接分享给团队 |

---

## 文件结构

```
snack-ecommerce-detail-page/
├── SKILL.md                          # 核心工作流：6 阶段完整指引
├── references/                       # 6 份知识库文档
│   ├── consumer-psychology.md        # 消费者心理分析框架
│   ├── fbe-sellpoint-model.md        # FBE 卖点转换模型 + 案例
│   ├── competitor-research.md        # 竞品真实链接自动抓取 SOP（全品类通用，含子代理兜底）
│   ├── detail-page-structure.md      # 6 屏结构规范 + 竞品分析框架 + 输出模板
│   ├── visual-design-rules.md        # 色彩/字体/摄影/版式/竞品参考
│   ├── review-standards.md           # 5 维度设计评审标准
│   ├── ai-design-rules.md            # AI 行为准则（三大禁忌 + 五项铁律）
│   └── categories/                   # 品类专属画像（跨品类逐步扩展）
│       ├── _index.md                 # 品类路由索引表 + 新增品类模板
│       ├── wash-care.md              # 洗护用品品类画像（含广告法合规规则）
│       ├── daily-use.md              # 日用品品类画像（母婴/居家/个护小物/配饰，含广告法合规）
│       └── small-appliance.md        # 小家电品类画像（风扇/行车记录仪/监控摄像头，含广告法合规）
└── assets/
    └── html-templates/
        └── template-general.html     # 通用详情页 HTML 模板（750px，CSS 变量可定制）
```

---

## 安装方式

**方式一：ClawHub 一键安装（推荐）**
在 WorkBuddy 技能市场搜索「电商详情页策划」或 `snack-ecommerce-detail-page`，点击安装即可。

**方式二：手动安装（GitHub 源码）**

```bash
# 仓库默认分支为 main
git clone -b main https://github.com/497832698/ecommerce-detail-page-skill.git
# 确保技能目录存在，并软链到 WorkBuddy 技能目录（已存在则覆盖）
mkdir -p ~/.workbuddy/skills
ln -sf "$(pwd)/ecommerce-detail-page-skill/.workbuddy/skills/snack-ecommerce-detail-page" \
       ~/.workbuddy/skills/snack-ecommerce-detail-page
# 重启 WorkBuddy，对话中输入产品名+卖点即可触发
```

> 依赖：仅需 WorkBuddy 客户端，无需额外运行环境。

---

## 关于设计师

这个 Skill 的知识体系来自 **般叶**，8 年电商设计师：

- 专注零食、母婴品类
- 覆盖平台：淘宝、天猫、京东、拼多多、孩子王
- 服务品牌：良品铺子、三只松鼠、英式、贝亲等
- 核心理念：**"不分析产品有什么，而分析消费者为什么买"**

---

## License

MIT
