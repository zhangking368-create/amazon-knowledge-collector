# Amazon Knowledge Collector

> 抖音 / YouTube / Amazon 内容 → AI 知识提炼 → 思维导图 → 个人 Amazon 知识作品集

## 项目定位

Amazon Knowledge Collector 是一个面向 Amazon 电商从业者的知识采集与知识资产管理 Skill。

第一阶段聚焦 AI 知识引擎，将非结构化内容转化为：

- 结构化 Knowledge Card
- Amazon Taxonomy 分类
- Claim / Fact / Opinion 区分
- Confidence 可信度评估
- Duplicate / Conflict 检测
- Mind Map 思维导图
- Personal Knowledge Portfolio 作品集

## 核心流程

```text
Source
  ↓
Content Extraction
  ↓
Amazon Taxonomy Classification
  ↓
Claim & Knowledge Extraction
  ↓
Confidence Assessment
  ↓
Fact Verification
  ↓
Duplicate / Conflict Detection
  ↓
Knowledge Card
  ↓
Mind Map
  ↓
Knowledge Graph
  ↓
Personal Portfolio
```

## 版本路线

### V1.0 — AI Knowledge Engine
- 内容提取
- Amazon 知识分类
- 知识卡片
- 思维导图
- 可信度分级
- 事实验证接口
- 重复与冲突检测
- 批量知识聚类

### V1.1 — Douyin Adapter
- 抖音分享链接标准化
- 视频元数据获取
- 字幕 / ASR
- OCR
- 内容归一化

### V2.0 — Knowledge Base
- 持久化知识库
- 语义搜索
- 关联知识
- 重复检测
- 冲突知识图谱

### V3.0 — Portfolio
- Amazon Knowledge Map
- 专题研究报告
- 个人方法论库
- 可视化 Dashboard

## 知识可信度

| Level | Type | Meaning |
|---|---|---|
| A | Official Fact | Amazon 官方资料支持 |
| B | Verified Information | 多个可靠来源支持 |
| C | Industry Practice | 行业普遍实践 |
| D | Seller Experience | 卖家个人经验 |
| E | Personal Opinion | 个人解释、推测或预测 |
| U | Unverified | 证据不足 |

## 核心原则

> 别人分享的是信息，AI整理的是知识，你最终沉淀的是自己的方法论。

## 当前状态

V1.0 Foundation — AI 知识引擎规格已完成，下一阶段接入实际运行时与外部内容 Adapter。
