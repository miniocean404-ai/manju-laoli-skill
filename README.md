# 漫剧老李 AIGC 全流程 Skill · V6.5 Multi-Agent（Short-Drama Director Suite）

> 面向抖音 & 红果爆款短剧/漫剧的**工业化编剧与视听导演超级系统**
> 技术标识：`short-drama-director` ｜ 版本：V6.5 Multi-Agent（2026-09-02） ｜ 曾用名：Manju Laoli Skill v5.0.2

---

## 🇨🇳 这是什么

一条龙贯穿「立项锁定 → 门控编剧 → 台词诊断 → 资产与空间锁定 → 文武双模分镜动力学 → 视频模型精准提示词渲染 → 独立质检审查」的短剧/漫剧工业化生产管线，供 AI 助手 / LLM 直接调用。

> 🔑 **核心理念：资产图先于分镜。** 角色/场景/道具在 P2 数字资产包阶段完成**出图并锁定**（非文字描述），成为《资产图册》唯一权威事实来源，分镜/投喂一律引用已锁定 @资产图。

- **管线**：Asset-First 六阶段（P0~P5 唯一生产顺序）+ 画幅自适应路由（横/竖屏全流程裁决）
- **平台**：多 Agent 平台适配（OpenClaw / WorkBuddy / 豆包Coze / Dify）+ 豆包 JSON 分块
- **剧本**：五阶门控引擎（Premise→Structure→Beat→Entity→Page），拒绝无大纲直奔台词
- **台词**：七维全量诊断，杜绝播音腔与反向灌输设定；**强制语速自检**（三档语速/五步流程/拆镜）
- **资产**：A/B/C 分级资产锁 + **分批出图执行规范（角色/场景/道具）** + 3D 空间快照与 180° 轴线锁；《剧组资产图册》CHR/AUD/PRP/SCN/Uxx 工业化台账；T1→T2→T3 亲缘遗传推导直接出图
- **情绪**：12 节拍全片情绪张力量化 + 可视化曲线（`generate_emotion_curve.py` 绘图）
- **空间**：2x2 顶视图机位调度（CAM1~4）+ 文戏机位调度图 / 战斗角色站位图双模板
- **分镜**：文武双模——文戏微表情生理递进 + 武戏 15 秒打戏完播率评分（R1/R2/R3 三档）+ 11 环动力链
- **武打**：23 门武学 + 9 套剑法 + 兵器 + 轻功 + 11 环杀招；武打导演引擎（快准狠 + 独立攻击逻辑）；机枪节奏防守三态；镜头规格 15 铁律
- **玄幻**：法术战斗 R3 专用（法宝/五行术法/术法攻防/能量具象/对军清场）
- **渲染**：Seedance 2.5 三层解耦提示词（16:9 / 9:16），15s / 首尾帧双图 / Hit-Stop / [SFX:] 原生音效 / 三层解耦
- **质检**：P0/P1/P2 三级独立门禁 + 投喂前必查清单（P4 六步执行序列）
- **合规**：平台安全合规转译词典（降低风险，不承诺 100% 通过）
- **工程**：时长前置预算 + 模型适配层 + Canvas/API 工作流对接 + 内置 `check_package.py` 校验脚本

**快速开始**：`openclaw skills install ./short-drama-director --as short-drama-director`，完整规则与指令见 [`short-drama-director/SKILL.md`](short-drama-director/SKILL.md)。

旧版 V5.0.2 与空间导演 V3 已归档至独立仓库：[**manju-laoli-skill-legacy**](https://github.com/lixiaoxiao9888-create/manju-laoli-skill-legacy)。

---

## 🇬🇧 What This Is

**Manju Laoli AIGC Full-Pipeline Skill (V6.5 Multi-Agent)** — an industrial-grade screenwriting & audiovisual-directing system for viral short dramas / animated short dramas (Douyin & Hongguo), built for AI agents/LLMs to call directly.

The pipeline: *project lock-in → gated screenwriting → dialogue diagnosis → asset & spatial locking → dual-mode storyboard dynamics (dialogue/action) → precise video-model prompt rendering → independent QC review*.

- **Pipeline**: Asset-First 6-stage (P0–P5, single authoritative production order) + aspect-ratio routing (horizontal/vertical)
- **Platforms**: multi-agent adapters (OpenClaw / WorkBuddy / Doubao Coze / Dify) + Doubao JSON chunking
- **Script**: 5-stage gated engine (Premise→Structure→Beat→Entity→Page); no jumping into dialogue without structure
- **Dialogue**: 7-dimension full diagnosis; **mandatory speech-speed self-check** (3 tiers / 5 steps / shot splitting)
- **Assets**: A/B/C graded asset locking + batched image-generation specs (characters/scenes/props) + 3D spatial snapshot with 180° axis lock; production ledger (CHR/AUD/PRP/SCN/Uxx) + lineage derivation (T1→T2→T3) with direct image generation
- **Emotion**: 12-beat full-episode emotional intensity + visual curve (via `generate_emotion_curve.py`)
- **Space**: 2×2 top-view camera scheduling (CAM1–4) + dual storyboard-map templates (dialogue camera map / combat character-stance map)
- **Storyboard**: dual-mode — micro-expression physiological progression (drama) + 15-second action completion-rate scoring (R1/R2/R3 tiers) + 11-link kinetic chain
- **Action**: 23 martial-arts schools + 9 sword forms + weapons + lightness skills + 11 finisher links; combat direction engine; machine-gun rhythm defense 3-state; 15 camera-spec iron rules
- **Fantasy combat**: R3-dedicated (artifacts / five-element spells / spell attack-defense / energy materialization / army-clearing)
- **Rendering**: Seedance 2.5 3-layer decoupled prompts (16:9 / 9:16), 15s / first-last frame dual-image / Hit-Stop / native [SFX:] audio / 3-layer decoupling
- **QC**: P0/P1/P2 independent gates + pre-feed mandatory checklist (P4 6-step execution sequence)
- **Compliance**: platform safety translation dictionary (risk reduction; no 100% pass guarantee)
- **Engineering**: pre-set runtime budget + model adapter layer + Canvas/API workflow + built-in `check_package.py` lint script

**Quick start**: `openclaw skills install ./short-drama-director --as short-drama-director`. Full rules & commands live in [`short-drama-director/SKILL.md`](short-drama-director/SKILL.md).

Previous V5.0.2 and Space Director V3 are archived in the separate repo: [**manju-laoli-skill-legacy**](https://github.com/lixiaoxiao9888-create/manju-laoli-skill-legacy).

---

## 📦 Structure

```
lixiaoxiao9888-create/manju-laoli-skill/
└── short-drama-director/          # V6.5 Multi-Agent main package (39 files)
    ├── SKILL.md                   # Router + working method + module index
    ├── references/                # 33 professional rulebooks
    ├── scripts/check_package.py   # static lint
    ├── scripts/generate_emotion_curve.py  # emotion-beat-curve visualizer
    └── README.md  /  LICENSE  /  CHANGELOG.md
```

## 📄 License

See [LICENSE](short-drama-director/LICENSE). For creative/learning use; comply with platform content policies.
