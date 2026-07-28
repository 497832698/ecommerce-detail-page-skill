# 🍖 电商详情页策划 Skill

> 不是 AI 自动出图工具。是一个帮设计师"想清楚再动手"的前期策划引擎。

[![Skill Type](https://img.shields.io/badge/type-WorkBuddy%20Skill-1A6B8A)](https://github.com/497832698/ecommerce-detail-page-skill)
[![Version](https://img.shields.io/badge/version-v1.0-27AE60)](https://github.com/497832698/ecommerce-detail-page-skill/releases)
[![Platform](https://img.shields.io/badge/platform-淘宝%20|%20天猫%20|%20京东%20|%20拼多多-e03e2d)](https://github.com/497832698/ecommerce-detail-page-skill)
[![Phase](https://img.shields.io/badge/品类-零食🍒🍬🧀🥩%20|%20洗护🧴-orange)](https://github.com/497832698/ecommerce-detail-page-skill)

---

## 它解决什么问题？

设计师做详情页时最难的其实不是"画图"——是**"想清楚"**：

- 竞品在讲什么？他们的文案和画面策略是什么？
- 这一屏到底应该传达什么信息？文案怎么写？配什么画面？
- 为什么这样做？——不只是拍脑袋，要有商业理由。

这个 Skill 把 8 年零食电商设计经验沉淀为自动化工作流，输入一个产品和卖点，输出一份可以直接拿去执行的策划文档。

---

## 能做什么（真实案例）

| 产品 | 核心策略 | 输出 |
|------|---------|------|
| 🍒 冻干山楂条 | "全场唯一把真实食材作为视觉主线" | [查看案例](docs/preview-hawthorn.png) |
| 🧀 四重芝士鳕鱼肠 | "全场唯一把芝士从配角升级为主角" | [查看案例](docs/preview-cod.png) |
| 🥩 猪肉脯 | "好肉，不需要甜来撑场面" | [查看案例](docs/preview-pork.png) |

每个案例都包含：竞品数据分析（附真实链接）→ FBE卖点转换 → 6屏逐屏策划（文案 ≤ 10字 + 画面描述 + AI Prompt + 设计理由）→ 整体视觉方向。

---

## 工作流

```
输入产品 + 卖点
    ↓
① 消费者分析        → 谁买？为什么买？担心什么？
    ↓
② 竞品分析          → 搜 3-5 个真实竞品（有销量数据 + 商品链接）
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
│   ├── detail-page-structure.md      # 6 屏结构规范 + 竞品分析框架 + 输出模板
│   ├── visual-design-rules.md        # 色彩/字体/摄影/版式/竞品参考
│   ├── review-standards.md           # 5 维度设计评审标准
│   └── ai-design-rules.md            # AI 行为准则（三大禁忌 + 五项铁律）
└── assets/
    └── html-templates/
        └── template-general.html     # 通用详情页 HTML 模板（750px，CSS 变量可定制）
```

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
