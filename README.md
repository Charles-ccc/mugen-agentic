# mugen-agentic

这是一个面向固定少数伙伴的 Agent 共学工作台。

当前阶段，这个仓库只优先做两件事：

1. 沉淀高质量问题与答案
2. 记录实验、踩坑和复盘

完整边界见 [CHARTER.md](CHARTER.md)，结构验证方法见 [STRUCTURE_EVALUATION.md](STRUCTURE_EVALUATION.md)，外部资料索引见 [REFERENCES.md](REFERENCES.md)。

## 从哪里开始

第一次进入仓库，按下面顺序看：

1. [CHARTER.md](CHARTER.md)：先理解仓库服务谁、做什么、不做什么。
2. [TOPIC_MAP.md](TOPIC_MAP.md)：了解当前的主题地图和优先探索方向。
3. [drafts/INBOX.md](drafts/INBOX.md)：查看待整理的问题、观察和实验线索。
4. [questions/README.md](questions/README.md)：进入问题卡片主线。
5. [experiments/README.md](experiments/README.md)：进入实验记录主线。

## 内容流转

这个仓库默认按下面的路径工作：

1. 有问题、想法、线索时，先进入 [drafts](drafts/README.md)
2. 整理为结构化内容后，进入 [questions](questions/README.md) 或 [experiments](experiments/README.md)
3. 每周至少做一次整理，沉淀到 [weekly](weekly/README.md)
4. 某个主题积累足够多后，再做专题归档到 [topics](topics/README.md)

## 目录说明

| 路径                                 | 作用                           | 内容粒度                     |
| ------------------------------------ | ------------------------------ | ---------------------------- |
| [drafts](drafts/README.md)           | 轻量草稿层，承接待整理内容     | 一个线索、一个问题、一个想法 |
| [questions](questions/README.md)     | 问题卡片区，沉淀高质量问答     | 一个问题                     |
| [experiments](experiments/README.md) | 实验记录区，保存真实尝试       | 一次实验                     |
| [weekly](weekly/README.md)           | 每周整理区，连接碎片与稳定内容 | 一周一篇                     |
| [topics](topics/README.md)           | 专题归档区，做阶段性总结       | 一个专题                     |
| [REFERENCES.md](REFERENCES.md)       | 外部资料索引，集中管理参考链接 | 一条资料                     |

## 新增内容时怎么选位置

如果你还没想清楚，只记录到能推动下一步的程度，先放草稿层。

1. 这是一个待回答的问题：先放 [drafts/INBOX.md](drafts/INBOX.md) 或新建草稿。
2. 这已经能回答一个具体问题：进入 [questions](questions/README.md)。
3. 这是一次真实尝试，不论成功失败：进入 [experiments](experiments/README.md)。
4. 这是本周的整理和取舍：进入 [weekly](weekly/README.md)。
5. 这个主题已经积累了足够的问答和实验：进入 [topics](topics/README.md)。

## 当前最小骨架

```text
.
├── CHARTER.md
├── README.md
├── REFERENCES.md
├── STRUCTURE_EVALUATION.md
├── TOPIC_MAP.md
├── drafts/
├── experiments/
├── questions/
├── topics/
└── weekly/
```

这是一套最小可运行结构。先让它服务真实记录，再根据使用摩擦做下一轮调整。
