# RAG 评估与防幻觉验证
[![Trust Score](https://img.shields.io/badge/Trust%20Score-91%2F100%20A+-2ea44f.svg)](https://github.com/zhaoxinghua09-cell/skillgate)
## 许可说明 · License Notice

- **权利状态**：本仓库以 **MIT 许可** 许可发布，可依该许可证条款自由使用、修改与再分发。
- **引用建议**：引用时请标注仓库名与原文链接 `https://github.com/zhaoxinghua09-cell/rag-eval-harness`
  与权利人「赵兴华 / Steven Zhao·China」。
- **品牌状态限定**：MedXpert、SynomosAI、LGD 等为相关项目标识，
  **均未申请实体注册、未申请商标注册**；出现仅作来源标识，
  不构成对法人实体或商标权的任何主张。
- **完整条款**：见仓库根目录 [LICENSE](LICENSE)。
- **联系**：zhaoxinghua06@126.com ｜ ORCID 0009-0001-0512-1237

---


> RAG 问答系统的质量评估与防幻觉验证方法论，用于回答「知识库答得准不准」「它会不会胡编」「换了模型还稳不稳」这类问题

SynomosAI 四支柱体系：**身份（Identity）· 溯源（Traceability）· 治理（Governance）· 共生（Symbiosis）**——当 AI 进入商业，可信是唯一的硬通货。

## 仓库内容

本仓库为 `rag-eval-harness` 技能的发布包：核心文件 `SKILL.md` 遵循 Agent Skills 规范（YAML frontmatter），可直接放入主流 AI Agent 的技能目录使用。

- **分类**：开发工具
- **版本**：1.1.0
- **署名**：诺衡(Krites)@SynomosAI
- **许可**：MIT（详见仓库 LICENSE）

## 使用方式

1. 克隆本仓库，或将技能目录放入 Agent 技能目录（如 `~/.workbuddy/skills/`）；
2. 按 `SKILL.md` 的描述与触发词调用对应能力；
3. 详细方法与模板见 `SKILL.md` 正文。

---

## 免责声明

本仓库内容为**理论站位与工具化探索**，不代表任何已获认证、已商业化交付或已服务特定客户的声明；文中涉及的外部标准、认证与条款信息为公开资料转述，正式引用前请**独立核实**。API、授权码与形象大使等为路线图（roadmap）事项，尚未上线。

## Ecosystem / 生态闭环

- [awesome-trusted-agents](https://github.com/zhaoxinghua09-cell/awesome-trusted-agents) — 四角度评分精选清单（生态榜单入口）
- [skill-scorecard](https://github.com/zhaoxinghua09-cell/skill-scorecard) — 四角度评分引擎
- [lgd-hub](https://github.com/zhaoxinghua09-cell/lgd-hub) — LGD 理论资产统一入口
- [lgd-skill-marketplace](https://github.com/zhaoxinghua09-cell/lgd-skill-marketplace) — LGD 技能超市总目录
- [governanceos](https://github.com/zhaoxinghua09-cell/governanceos) — 治理编排枢纽（SPEC→PLAN→GATE→AUDIT→EVO）
- [skillgate](https://github.com/zhaoxinghua09-cell/skillgate) — 技能信任评分引擎
