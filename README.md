# Paper Reading Skills

这是一组辅助论文阅读的 Codex skills。核心目标不是“把每篇论文都读完”，而是在阅读开始前先识别当前阅读动机，再根据动机选择合适的阅读策略、关注点和产出格式。

很多低效阅读来自一个隐蔽问题：开始读之前并没有说清楚自己要从论文里拿到什么。这个项目把论文阅读拆成一组常见动机，让每次阅读都能先回答：

- 我现在为什么读这篇论文？
- 我应该重点看哪些部分？
- 我这次阅读应该产出什么？
- 读到什么程度就可以停？

## 项目结构

```text
.
├── paper-reading-motivation-router/
│   └── SKILL.md
├── 01-field-map/
│   └── SKILL.md
├── 02-research-question/
│   └── SKILL.md
├── 03-problem-reality-check/
│   └── SKILL.md
├── 04-theoretical-grounding/
│   └── SKILL.md
├── 05-method-inspiration/
│   └── SKILL.md
├── 06-experiment-design/
│   └── SKILL.md
├── 07-baseline-search/
│   └── SKILL.md
├── 08-metric-search/
│   └── SKILL.md
├── 09-citation-support/
│   └── SKILL.md
├── 10-positioning-differentiation/
│   └── SKILL.md
├── 11-writing-patterns/
│   └── SKILL.md
└── 12-risk-objection/
    └── SKILL.md
```

## 使用方式

阅读开始前，优先触发 `paper-reading-motivation-router`。它负责通过简短提问判断当前阅读动机，并把阅读任务路由到对应的动机 skill。

后续每个动机 skill 会逐步补充：

- 适用场景
- 阅读前提问
- 阅读顺序
- 重点关注章节
- 信息抽取模板
- 产出格式
- 停止条件

## 阅读动机

| 编号 | 动机 | 典型产出 | 适用阶段 |
| --- | --- | --- | --- |
| 01 | 了解领域全貌 | 领域研究地图 | 刚进入方向，问题还没定 |
| 02 | 寻找研究问题 | 候选研究问题列表 | 已知道领域大概情况，但不知道切哪里 |
| 03 | 验证问题是否真实 | 问题依据 / problem justification | 有初步 idea，但担心是伪问题 |
| 04 | 寻找理论依据 | 理论支柱 | 问题已有，但需要理论地基 |
| 05 | 寻找方法启发 | 方法候选库 | 问题初步确定，正在设计方法 |
| 06 | 寻找实验设计 | 实验方案草图 | 方法有雏形，但不知道怎么验证 |
| 07 | 寻找 baseline | baseline list | 方法基本确定，准备实验或 proposal |
| 08 | 寻找评价指标 | metric bank | 不知道如何证明 claim |
| 09 | 寻找论文依据 / 引用支撑 | citation bank | 写 introduction、related work 或 proposal |
| 10 | 寻找定位和差异化 | positioning matrix | 方法和问题稳定，准备写 related work |
| 11 | 学习写作套路 | 写作模板 / 表达素材 | 准备写 proposal、paper 或 related work |
| 12 | 排雷和反驳自己 | risk list / objection list | idea 成型前后，尤其是过于兴奋时 |

## 初始化原则

这个仓库目前只做骨架初始化。每个动机目录先保留一个简洁的 `SKILL.md` 占位文件，后续可以逐个扩写，不急着一次性把所有流程写死。

每个 skill 应尽量保持短小，只保存真正会改变阅读行为的指令；详细模板、示例和表格可以在需要时再加入 `references/`。
