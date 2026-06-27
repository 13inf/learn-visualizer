<div align="center">

# Learn Visualizer

**Turn any knowledge point into an interactive HTML explanation and animation.**

[中文](#中文) | [English](#english)

</div>

---

## 中文

**Learn Visualizer** 是一个通用学习可视化 Skill。

它可以帮助 AI Agent 把抽象、复杂、零散的知识点，自动拆解成清晰的学习结构，并生成一个可交互的单文件 HTML 动画页面。

它不只适用于某一个学科，而是可以用于食品化学、食品免疫学、工程制图、机械原理、数学公式、历史时间线、计算机流程、法律流程等各种知识点。

---

### 核心功能

Learn Visualizer 可以帮助 Agent 自动完成：

1. 判断知识点类型
2. 拆解关键概念
3. 选择合适的可视化模型
4. 生成交互式 HTML 学习页面
5. 加入动画、解释、总结、易错点和小测验

---

### 支持的知识类型

它可以处理多种类型的知识点：

| 类型    | 示例                   |
| ----- | -------------------- |
| 流程型知识 | 补体激活流程、实验步骤、工艺流程     |
| 结构型知识 | 抗体结构、机械零件、细胞结构       |
| 对比型知识 | 固有免疫 vs 适应性免疫、孔和轴的配合 |
| 公式型知识 | 齿轮参数、物理公式、数学推导       |
| 分类型知识 | 蛋白质类型、食品色素分类、酶的分类    |
| 时间轴知识 | 历史事件、项目阶段、技术发展过程     |
| 因果型知识 | 蛋白质变性、食品腐败、反馈调节      |
| 决策型知识 | 判断题流程、诊断流程、分类判断      |

---

### 生成效果

使用 Learn Visualizer 后，Agent 应该生成一个完整的单文件 HTML 页面，通常包括：

* 知识点标题
* 核心概念解释
* 动画示意图
* 步骤拆解
* SVG 连线或结构图
* 可点击节点
* 悬停提示
* 易错点提醒
* 考场版总结
* 小测验

生成的 HTML 文件应该：

* 可以直接用浏览器打开
* CSS 和 JavaScript 内联在同一个文件中
* 不依赖外部库
* 适合学习、复习、讲课和展示
* 页面清晰，适合手机和电脑查看

---

### 使用示例

你可以这样对 AI Agent 说：

```text
Use learn-visualizer.skill to turn the following knowledge point into an interactive HTML learning page.

Knowledge point:
[Paste your knowledge point here]

Requirements:
1. First identify the knowledge type.
2. Break it down into clear learning modules.
3. Choose the most suitable animation or visualization model.
4. Generate a single-file HTML page.
5. Include explanations, animations, common mistakes, summaries, and quiz questions.
```

中文也可以这样说：

```text
请使用 learn-visualizer.skill，把下面这个知识点自动拆解，并生成一个可交互的 HTML 动画学习页面。

知识点：
[在这里粘贴你的知识点]

要求：
1. 先判断知识点类型。
2. 拆解成清晰的学习模块。
3. 选择最适合的动画或可视化模型。
4. 生成单文件 HTML 页面。
5. 加入解释、动画、易错点、总结和小测验。
```

---

### 适合场景

Learn Visualizer 适合用于：

* 复习考试知识点
* 理解抽象概念
* 制作教学演示
* 生成 HTML 学习页面
* 把课堂笔记变成交互动画
* 制作知识点讲解素材
* 辅助学生、教师和知识博主创作学习内容

---

### 文件

主要 Skill 文件：

```text
learn-visualizer.skill
```

---

### License

MIT License

---

## English

**Learn Visualizer** is a universal learning visualization skill.

It helps AI agents turn abstract, complex, and fragmented knowledge points into clear learning structures and interactive single-file HTML animations.

It is not limited to one subject. It can be used for biology, chemistry, engineering drawing, mechanical principles, mathematics, history, computer science, legal processes, and other knowledge-heavy topics.

---

### Core Features

Learn Visualizer helps an agent automatically:

1. Identify the type of knowledge point
2. Break down complex concepts
3. Choose a suitable visualization model
4. Generate an interactive HTML learning page
5. Add animations, explanations, summaries, common mistakes, and quiz questions

---

### Supported Knowledge Types

It can handle many kinds of learning content:

| Type                           | Examples                                                    |
| ------------------------------ | ----------------------------------------------------------- |
| Process-based knowledge        | Immune pathways, experiment steps, manufacturing workflows  |
| Structure-based knowledge      | Antibody structure, machine parts, cell components          |
| Comparison-based knowledge     | Innate immunity vs adaptive immunity, hole fit vs shaft fit |
| Formula-based knowledge        | Gear parameters, physics formulas, mathematical derivations |
| Classification-based knowledge | Protein types, food pigments, enzyme categories             |
| Timeline-based knowledge       | Historical events, project stages, technology development   |
| Cause-and-effect knowledge     | Protein denaturation, food spoilage, feedback regulation    |
| Decision-based knowledge       | Judgment flows, diagnosis flows, classification logic       |

---

### Output

With Learn Visualizer, the agent should generate a complete single-file HTML learning page, usually including:

* Knowledge point title
* Core concept explanation
* Animated diagram
* Step-by-step breakdown
* SVG lines or structural diagrams
* Clickable nodes
* Hover tooltips
* Common mistake reminders
* Exam-style summary
* Mini quiz

The generated HTML file should be:

* Openable directly in a browser
* Self-contained with inline CSS and JavaScript
* Free from external dependencies
* Suitable for learning, review, teaching, and presentation
* Clear on both desktop and mobile screens

---

### Example Prompt

You can use this skill with an AI agent like this:

```text
Use learn-visualizer.skill to turn the following knowledge point into an interactive HTML learning page.

Knowledge point:
[Paste your knowledge point here]

Requirements:
1. First identify the knowledge type.
2. Break it down into clear learning modules.
3. Choose the most suitable animation or visualization model.
4. Generate a single-file HTML page.
5. Include explanations, animations, common mistakes, summaries, and quiz questions.
```

---

### Use Cases

Learn Visualizer is useful for:

* Reviewing exam knowledge points
* Explaining abstract concepts
* Creating teaching materials
* Making interactive study pages
* Turning notes into visual learning tools
* Building HTML-based educational demos
* Helping students, teachers, and knowledge creators

---

### File

Main skill file:

```text
learn-visualizer.skill
```

---

### License

MIT License
