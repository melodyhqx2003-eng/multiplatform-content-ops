# 多平台内容运营与复盘系统

面向小红书、闲鱼及后续新增平台的长期内容增长与交易转化知识库。

## 核心闭环

> 发布 → 获取真实反馈 → 分析 → 总结规律 → 优化下一篇 → 再验证

目标不是一次性写文案，而是逐渐形成一套基于真实数据、可持续修正的个人多平台增长系统。

## 核心原则

1. 平台不同，用户场景和转化机制不同，禁止直接复制同一套文案。
2. 优先使用本人真实发布、咨询和成交数据。
3. 不把相关性直接当因果关系。
4. 不因单个爆款或单次失败过度总结。
5. 所有结论区分“已验证规律”和“待验证假设”。
6. 跨平台只沉淀真正通用的规律；标题长度、标签、价格、交易表达等按平台独立管理。
7. 不为了点击使用虚假、误导或无法兑现的表达。

## 项目结构

```text
.
├── AGENTS.md
├── platforms/
│   ├── xiaohongshu.md
│   └── xianyu.md
├── rules/
│   ├── cross-platform.md
│   ├── validated-rules.md
│   └── hypotheses.md
├── data/
│   ├── published-content.csv
│   ├── benchmark-samples.csv
│   └── conversion-events.csv
├── templates/
│   ├── content-generation.md
│   ├── post-review.md
│   ├── sample-analysis.md
│   └── new-platform.md
└── experiments/
    └── testing-plan.md
```

## 数据优先级

1. 本人真实发布与成交数据
2. 同平台、同赛道、同目标样本
3. 平台官方规则与可靠一手信息
4. 通用内容运营经验
5. 未验证推测

## 平台扩展

新增平台时，先基于 `templates/new-platform.md` 建立独立平台规则文件，再开始采集样本和发布测试。不得默认沿用小红书或闲鱼规则。
