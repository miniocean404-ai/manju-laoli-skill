<div align="center">

# 🎬 漫剧老李 AIGC 全流程 Skill

## **V6.5 Multi-Agent** · Short-Drama Director Suite

> ⚡ 抖音 & 红果爆款短剧/漫剧的 **工业化编剧与视听导演超级系统**
> 供 AI 助手 / LLM 直接调用的完整生产管线

![Version](https://img.shields.io/badge/版本-V6.5--Multi--Agent-6a5acd)
![Modules](https://img.shields.io/badge/规则库-33%20模块-00b4d8)
![Files](https://img.shields.io/badge/文件-39-2ec4b6)
![Platform](https://img.shields.io/badge/平台-OpenClaw%20%7C%20Coze%20%7C%20Dify%20%7C%20WorkBuddy-ff6b6b)
![License](https://img.shields.io/badge/License-MIT-ffca3a)
![Stars](https://img.shields.io/github/stars/lixiaoxiao9888-create/manju-laoli-skill?style=social)

---

### 🎥 生产管线

```
📋 立项锁定 → ✍️ 门控编剧 → 🎙️ 台词诊断 → 🖼️ 资产锁定 → 🎬 文武分镜 → 🚀 提示词渲染 → ✅ 独立质检
```

</div>

---

## 🔥 核心亮点

| 领域 | 能力 | 说明 |
|:---:|:---|:---|
| 🏗️ **管线** | Asset-First 六阶段 | P0~P5 唯一生产顺序，**资产图先于分镜** |
| 🖥️ **平台** | 多 Agent 适配 | OpenClaw / WorkBuddy / 豆包Coze / Dify + 豆包 JSON 分块 |
| 📐 **画幅** | 自适应路由 | 横/竖屏全流程裁决，用户指令优先 |
| ✍️ **编剧** | 五阶门控引擎 | Premise→Structure→Beat→Entity→Page，拒绝无大纲直奔台词 |
| 🎙️ **台词** | 七维诊断 + 语速自检 | 杜绝播音腔；三档语速/五步流程/拆镜 |
| 🖼️ **资产** | 工业化台账 | A/B/C 分级锁 + CHR/AUD/PRP/SCN/Uxx 台账 + T1→T2 亲缘遗传推导 |
| 📈 **情绪** | 12 节拍曲线 | 全片情绪张力量化 + 可视化绘图 |
| 🎬 **分镜** | 文武双模 | 文戏微表情递进 + 武戏 15s 完播率评分（R1/R2/R3 三档） |
| ⚔️ **武打** | 全流派武学库 | 23 门武学 + 9 套剑法 + 兵器 + 轻功 + 11 环杀招 |
| 🔮 **玄幻** | 法术战斗 R3 | 法宝/五行术法/术法攻防/能量具象/对军清场 |
| 🚀 **渲染** | Seedance 2.5 深度适配 | 15s / 首尾帧双图 / Hit-Stop / [SFX:] 原生音效 / 三层解耦 |
| 🎥 **空间** | 2x2 顶视图机位 | CAM1~4 + 文戏机位调度图 / 战斗角色站位图双模板 |
| ✅ **质检** | 三级门禁 + 必查清单 | P0/P1/P2 独立门禁 + P4 投喂前六步执行序列 |
| 🛡️ **合规** | 安全转译词典 | 降低平台风险，不承诺 100% 通过 |

---

## ⚙️ 快速开始

```bash
# 安装到 OpenClaw
openclaw skills install ./short-drama-director --as short-drama-director

# 自检包完整性（33 模块静态检查）
python3 short-drama-director/scripts/check_package.py
```

完整规则与指令见 [`short-drama-director/SKILL.md`](short-drama-director/SKILL.md)

---

## 📦 项目结构

```
lixiaoxiao9888-create/manju-laoli-skill/
└── short-drama-director/              # V6.5 Multi-Agent 主包（39 文件）
    ├── SKILL.md                       # 路由 + 工作方法 + 模块索引
    ├── references/                    # 33 部专业规则库
    │   ├── asset-first-pipeline.md    #   Asset-First 六阶段（权威）
    │   ├── seedance-render-engine.md  #   Seedance 2.5 三层解耦
    │   ├── combat-direction-engine.md #   武打导演引擎
    │   ├── ★ prompt-feeding-checklist.md  # P4 投喂必查清单
    │   └── ... 共 33 模块
    ├── scripts/
    │   ├── check_package.py           # 静态自检
    │   └── generate_emotion_curve.py  # 情绪曲线绘图
    └── README.md / LICENSE / CHANGELOG.md
```

---

## 📜 更新历史

- **V6.5 Multi-Agent**（2026-09-02）— Asset-First 六阶段 + 多 Agent 平台适配 + Seedance 2.5 深度适配 + 静止段禁用铁律（AI 视频无静止表演能力，情绪蓄力必须在运动中完成）
- **V6.0**（2026-08-28）— 23 references 模块重组 + 瘦身 + 审计修复
- **V5.0.2**（2026-08-27）— 武学招式库补全 + 打斗专项优先声明
- 旧版归档：[**manju-laoli-skill-legacy**](https://github.com/lixiaoxiao9888-create/manju-laoli-skill-legacy)

---

<div align="center">

### 📄 License

MIT · 仅供创作与学习使用，请遵守各平台内容规范

**Made with ❤️ for AI Content Creators**

</div>
