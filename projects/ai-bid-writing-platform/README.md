# AI Bid Writing Platform

中文名称：AI 标书写作平台

面向招投标场景的 AI 辅助标书写作 SaaS。用户上传招标文件后，系统解析评分点、资质要求、废标条款，辅助生成标书目录和章节内容，并导出 Word 文档。

## 相关站点

- 筱楠 API：https://api.ipsunion.com/
- 筱楠官网：https://www.lianqiai.cn/

## 目录结构

```text
.
├── README.md
├── docs/
│   ├── 00-raw/
│   ├── 01-prd/
│   ├── 02-estimates/
│   └── 03-incoming-requirements/
├── src/
├── assets/
└── scripts/
```

## 文档索引

| 文件 | 内容 | 备注 |
| --- | --- | --- |
| [docs/00-raw/AI标书写作平台-完整功能清单.docx](docs/00-raw/AI标书写作平台-完整功能清单.docx) | 完整功能清单与技术方案 | 原始资料，V2.0，2026-06-15 |
| [docs/01-prd/MVP-PRD.md](docs/01-prd/MVP-PRD.md) | MVP 产品需求文档 | 主链路 MVP 范围 |
| [docs/02-estimates/开发周期与报价.md](docs/02-estimates/开发周期与报价.md) | 开发周期与报价估算 | 推荐按 MVP 可用版推进 |
| [docs/03-incoming-requirements/README.md](docs/03-incoming-requirements/README.md) | 后续需求入口 | 新需求先放这里，再评估并入 PRD |

## 文档内容概览

原始 Word 文档主要包含：

- 项目概述：产品定位、商业模式、技术约束。
- 用户端架构：Web 形态、技术架构、前期准备事项。
- 功能清单：基础架构、模板系统、智能图表、知识库、团队协作、运营后台等。
- 收费体系：会员费、Token 消耗费、支付接入。
- 范围边界：明确不做标讯商机搜索等功能。
- 技术方案：技术栈总览、Token 强制走自有中转的实现方案。
