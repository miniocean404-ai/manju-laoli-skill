# 漫剧老李 AIGC 全流程 Skill · V6.0（Short-Drama Director Suite）

> 面向抖音 & 红果爆款短剧/漫剧的**工业化编剧与视听导演超级系统**
> 技术标识：`short-drama-director` ｜ 版本：V6.0（2026-08-28） ｜ 曾用名：Manju Laoli Skill v5.0.2

---

## 🇨🇳 这是什么

一条龙贯穿「小说分析 → 门控编剧 → 台词诊断 → 资产与空间锁定 → 文武双模分镜动力学 → 视频模型精准提示词渲染 → 独立质检审查」的短剧/漫剧工业化生产管线，供 AI 助手 / LLM 直接调用。

- **剧本**：五阶门控引擎（Premise→Structure→Beat→Entity→Page），拒绝无大纲直奔台词
- **台词**：七维全量诊断，杜绝播音腔与反向灌输设定；强制语速自检（3.5~5 字/秒）
- **资产**：16 项资产锁定（A/B/C 分级）+ 三栏无头三视图参考图 + 3D 空间快照与 180° 轴线锁
- **分镜**：文武双模——文戏微表情生理递进 + 武戏 15 秒 PREVIS 动力学（R1/R2/R3 三档）
- **武打**：11 环动力链 + 3 轻 1 重机枪对招 + 防守三态 + 终结技三幕 + 大招运镜 11 模式 + 全门派武学库
- **渲染**：Seedance 2.0 / 即梦 / 可灵 三层解耦提示词，单组 ≤15s 独立投喂
- **质检**：P0/P1/P2 三级独立门禁 + 声音三层相对电平
- **合规**：平台安全合规转译词典（安全默认 / 强动作非血腥 / 成人级草案）
- **工程**：时长前置预算 + 模型适配层 + 场景资产参考图规则 + 内置 `check_package.py` 校验脚本

**快速开始**：`openclaw skills install ./short-drama-director --as short-drama-director`，完整规则与指令见 [`short-drama-director/SKILL.md`](short-drama-director/SKILL.md)。

旧版 V5.0.2 与空间导演 V3 保留在 [`legacy/`](legacy/) 供回溯。

---

## 🇬🇧 What This Is

**Manju Laoli AIGC Full-Pipeline Skill (V6.0)** — an industrial-grade screenwriting & audiovisual-directing system for viral short dramas / animated short dramas (Douyin & Hongguo), built for AI agents/LLMs to call directly.

The pipeline: *novel analysis → gated screenwriting → dialogue diagnosis → asset & spatial locking → dual-mode storyboard dynamics (dialogue/action) → precise video-model prompt rendering → independent QC review*.

- **Script**: 5-stage gated engine (Premise→Structure→Beat→Entity→Page); no jumping into dialogue without structure
- **Dialogue**: 7-dimension full diagnosis; mandatory speech-speed self-check (3.5–5 chars/sec)
- **Assets**: 16-item asset locking (A/B/C grading) + headless three-view reference sheets + 3D spatial snapshot with 180° axis lock
- **Storyboard**: dual-mode — micro-expression physiological progression (drama) + 15-second action PREVIS dynamics (R1/R2/R3 tiers)
- **Action**: 11-link kinetic chain + machine-gun combo + 3-state defense breakdown + 3-act finisher + 11 ultimate camera patterns + full martial-arts library
- **Rendering**: 3-layer decoupled prompts for Seedance 2.0 / Jimeng / Kling; ≤15s per unit, independently feedable
- **QC**: P0/P1/P2 independent gates + 3-layer relative audio levels
- **Compliance**: platform safety translation dictionary (safe-default / strong-action non-gore / adult-draft)
- **Engineering**: pre-set runtime budget + model adapter layer + scene-reference usage rules + built-in `check_package.py` lint script

**Quick start**: `openclaw skills install ./short-drama-director --as short-drama-director`. Full rules & commands live in [`short-drama-director/SKILL.md`](short-drama-director/SKILL.md).

Previous V5.0.2 and Space Director V3 are kept under [`legacy/`](legacy/) for reference.

---

## 📦 Structure

```
lixiaoxiao9888-create/manju-laoli-skill/
├── short-drama-director/          # V6.0 main package (23 files)
│   ├── SKILL.md                   # Router + working method + module index
│   ├── references/                # 18 professional rulebooks
│   ├── scripts/check_package.py   # static lint
│   ├── README.md  /  LICENSE  /  CHANGELOG.md
└── legacy/                        # archived previous versions
    ├── manju-laoli-v5.0/          # V5.0.2
    └── space-director-v3/         # Space Director V3
```

## 📄 License

See [LICENSE](short-drama-director/LICENSE). For creative/learning use; comply with platform content policies.
