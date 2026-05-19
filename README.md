# Requirements Analysis

这个项目用于沉淀各类需求分析工作，从原始需求线索、调研材料、分析报告到最终决策都放在同一个工作区内。

## 目录结构

```text
requirements-analysis/
├── 00_inbox/       # 原始输入：会议纪要、用户反馈、临时想法、未整理资料
├── 01_research/    # 调研材料：用户访谈、竞品分析、数据观察、业务背景
├── 02_analysis/    # 分析文档：正式需求分析、范围拆解、方案比较
├── 03_decisions/   # 决策记录：已确认结论、取舍原因、后续影响
├── 04_templates/   # 文档模板：新需求分析时复制使用
└── 05_archive/     # 归档内容：已完成、暂停或废弃的需求
```

## 命名规范

- 项目目录使用英文小写连字符：`requirements-analysis`。
- 需求分析文档使用日期加主题：`YYYY-MM-DD-topic.md`。
- 调研材料使用日期、来源和主题：`YYYY-MM-DD-source-topic.md`。
- 决策记录使用编号和主题：`ADR-0001-topic.md`。
- 文件名优先使用英文小写、数字和连字符，避免空格；文档标题和正文可以使用中文。

## 推荐流程

1. 把未整理的输入先放入 `00_inbox/`。
2. 将背景资料、访谈、竞品和数据观察整理到 `01_research/`。
3. 复制 `04_templates/analysis-report.md` 到 `02_analysis/`，按命名规范创建分析报告。
4. 对已确认的重要取舍，复制 `04_templates/decision-record.md` 到 `03_decisions/`。
5. 需求完成、暂停或废弃后，将相关材料整理到 `05_archive/`。

## 状态建议

- `draft`：草稿，仍在收集信息。
- `reviewing`：待评审或正在讨论。
- `approved`：已确认，可以进入设计或开发。
- `paused`：暂缓。
- `archived`：已归档。
