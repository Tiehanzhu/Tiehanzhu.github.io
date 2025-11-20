# 文章写作指南

## 文章命名规则

文件名格式：`YYYY-MM-DD-标题.md`

例如：`2025-11-20-my-first-post.md`

## 文章模板

### 学术研读模板

```markdown
---
layout: post
title: "论文标题或笔记主题"
date: 2025-11-20
category: academic
tags: [密码学, 论文阅读]
---

## 论文信息
- 标题：
- 作者：
- 发表年份：
- 会议/期刊：

## 研究背景

## 主要贡献

## 技术方法

## 实验结果

## 个人思考
```

### 生活随笔模板

```markdown
---
layout: post
title: "随笔标题"
date: 2025-11-20
category: life
tags: [生活, 感悟]
---

## 开始

## 正文内容

## 结语
```

### 目标规划模板

```markdown
---
layout: post
title: "目标标题"
date: 2025-11-20
category: goals
tags: [目标, 规划]
---

## 目标概述

## 具体计划

### 短期目标（本周/本月）

### 中期目标（本学期）

### 长期目标（本学年）

## 行动步骤

## 评估标准
```

### 思绪漫谈模板

```markdown
---
layout: post
title: "漫谈主题"
date: 2025-11-20
category: thoughts
tags: [思考, 随笔]
---

## 引子

## 观点展开

## 总结
```

## 分类说明

- `academic` - 学术研读
- `life` - 生活随笔
- `goals` - 目标与规划
- `thoughts` - 思绪漫谈

## Markdown 语法提示

### 标题
```markdown
# 一级标题
## 二级标题
### 三级标题
```

### 列表
```markdown
- 无序列表项
- 无序列表项

1. 有序列表项
2. 有序列表项
```

### 链接和图片
```markdown
[链接文字](https://example.com)
![图片描述](图片URL)
```

### 代码
```markdown
行内代码：`code`

代码块：
\`\`\`python
def hello():
    print("Hello World")
\`\`\`
```

### 引用
```markdown
> 这是一段引用文字
```

### 加粗和斜体
```markdown
**加粗文字**
*斜体文字*
```

## 快速创建新文章

在 `_posts` 文件夹中创建新文件，文件名格式为 `YYYY-MM-DD-标题.md`，然后按照上面的模板填写内容即可。

