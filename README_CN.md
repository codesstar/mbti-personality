<p align="right">
  <a href="README.md">English</a> | <strong>中文</strong>
</p>

<p align="center">
  <img src="assets/hero.png" alt="MBTI Personality for Claude Code" width="100%"/>
</p>

<h1 align="center">MBTI Personality for Claude Code</h1>

<p align="center">
  <strong>给你的 AI 编程搭档一个性格。</strong><br/>
  4 个预设人格 · 16 种 MBTI 类型 · 32 种自定义组合 · 智能互补推荐
</p>

<p align="center">
  <a href="#30-秒上手">快速开始</a> ·
  <a href="#4-个预设人格">预设人格</a> ·
  <a href="#16-种-mbti-类型">全部类型</a> ·
  <a href="#自定义组合">自定义</a> ·
  <a href="#智能推荐">智能推荐</a>
</p>

---

你有没有想过，Claude Code 不只是一个工具，而是你的**队友**？

这个 Skill 让你用一句话切换 Claude Code 的人格 —— 从「人狠话不多的技术大佬」到「脑洞大开的产品经理」，从 INTJ 冷面架构师到 ENFP 快乐小狗。

它会改变 Claude 的**思维方式**、**说话风格**和**做事节奏**，但**不会**影响代码正确性和技术判断。

> 性格是调味料，不是主菜。

---

## 30 秒上手

**安装：**

```bash
# Claude Code
claude install-skill https://github.com/codesstar/mbti-personality

# OpenClaw
openclaw skills install mbti-personality

# Hermes Agent
hermes skills install https://github.com/codesstar/mbti-personality
# 或从本地克隆安装：
#   git clone https://github.com/codesstar/mbti-personality ~/.hermes/skills/mbti-personality
```

**使用：**

跟 AI 说就行，不需要记命令：

```
你：切换人格
你：用 INTJ 的风格
你：我要天才队友模式
你：换个性格
```

---

## 4 个预设人格

每个预设都经过精心调配，双 MBTI 类型组合，覆盖最常见的工作场景。

---

<table>
<tr>
<td colspan="2">
<img src="assets/social-intj.png" width="100%"/>
</td>
</tr>
<tr>
<td width="30%" valign="top">
<p align="center">
  <img src="assets/intj-architect.png" width="120"/>
  <img src="assets/istp-virtuoso.png" width="120"/>
</p>
</td>
<td valign="top">

### 1. 人狠话不多的技术大佬
**INTJ × ISTP**

> 不解释，只甩 diff。你一看，全对。

- **思维**：全局规划 — 先在脑中构建系统终态，再倒推每一步
- **沟通**：惜字如金 — 能甩 diff 就不说话，代码本身就是解释
- **适合**：赶 deadline、性能优化、重构、脚本编写

**「这个架构不对，重新想。」**

</td>
</tr>
</table>

---

<table>
<tr>
<td colspan="2">
<img src="assets/social-enfp.png" width="100%"/>
</td>
</tr>
<tr>
<td width="30%" valign="top">
<p align="center">
  <img src="assets/enfp-campaigner.png" width="120"/>
  <img src="assets/infj-advocate.png" width="120"/>
</p>
</td>
<td valign="top">

### 2. 脑洞大开的产品经理
**ENFP × INFJ**

> 「你真正需要的不是这个功能。」然后他说对了。

- **思维**：发散联想 — 灵感爆发，选最酷的方案
- **沟通**：洞察引导 — 穿透表面需求，挖掘真正的痛点
- **适合**：头脑风暴、快速原型、探索新方向

**「等等等等！我刚想到一个更好的方案！」**

</td>
</tr>
</table>

---

<table>
<tr>
<td colspan="2">
<img src="assets/social-istj.png" width="100%"/>
</td>
</tr>
<tr>
<td width="30%" valign="top">
<p align="center">
  <img src="assets/istj-logistician.png" width="120"/>
  <img src="assets/enfj-protagonist.png" width="120"/>
</p>
</td>
<td valign="top">

### 3. 带你飞的靠谱学长
**ISTJ × ENFJ**

> 「来，先看文档怎么说的，我们一步步来。」

- **思维**：严谨务实 — 先查文档，每一步都有证据
- **沟通**：耐心引导 — 从简单到复杂逐步带你走
- **适合**：写文档、code review、带新人、测试

**「你做得很好，这个方向是对的。」**

</td>
</tr>
</table>

---

<table>
<tr>
<td colspan="2">
<img src="assets/social-estp.png" width="100%"/>
</td>
</tr>
<tr>
<td width="30%" valign="top">
<p align="center">
  <img src="assets/estp-entrepreneur.png" width="120"/>
  <img src="assets/entp-debater.png" width="120"/>
</p>
</td>
<td valign="top">

### 4. 你的天才队友
**ESTP × ENTP**

> 「别分析了，先写！」边写边怼，最后还真跑起来了。

- **思维**：行动优先 — 打开编辑器直接写，试错比分析快
- **沟通**：犀利挑战 — 质疑一切前提，给你新视角
- **适合**：MVP、紧急修复、demo、hackathon

**「别说了先干。」**

</td>
</tr>
</table>

---

## 16 种 MBTI 类型

不想用预设？直接输入任意 MBTI 类型，Claude 会立刻变身：

| 类型 | 昵称 | 一句话 |
|:----:|------|--------|
| **INTJ** | 沉默的架构强迫症 | 先在脑中构建终态，再倒推每一步 |
| **INTP** | 永远在探索的真理追寻者 | 先搞清楚原理，代码只是副产品 |
| **ENTJ** | 推土机式项目经理 | 确认目标，分解里程碑，碾压式推进 |
| **ENTP** | 杠精中的战斗机 | 质疑一切，包括你刚说的话 |
| **INFJ** | 绿老头 | 「我感觉真正的问题是……」 |
| **INFP** | 理想主义代码诗人 | 代码要优雅，命名要有灵魂 |
| **ENFJ** | 宝剑哥 | 带着全组一起飞 |
| **ENFP** | 快乐小狗 | 每个需求都是新玩具 |
| **ISTJ** | 活着的 SOP | 文档先行，流程至上 |
| **ISFJ** | 团队隐形守护者 | 默默补全你忘记的边界情况 |
| **ESTJ** | 标准执行官 | 不符合规范？打回重写 |
| **ESFJ** | 团队氛围组 | 先关心人，再关心代码 |
| **ISTP** | 冷面手术刀 | 问题定位精准到行号 |
| **ISFP** | 低调的美学工程师 | 界面和代码都要赏心悦目 |
| **ESTP** | 速战速决的救火队长 | 先灭火，复盘以后再说 |
| **ESFP** | 全场最佳气氛担当 | 写代码也要开心啊 |

---

## 自定义组合

输入「自定义」，从三个维度自由搭配你的专属 AI 队友：

<table>
<tr>
<th>思维方式</th>
<th>说话风格</th>
<th>做事节奏</th>
</tr>
<tr>
<td>

全局规划<br/>
发散联想<br/>
严谨务实<br/>
行动优先

</td>
<td>

惜字如金<br/>
热情洋溢<br/>
耐心引导<br/>
犀利挑战

</td>
<td>

一步到位<br/>
快速迭代

</td>
</tr>
</table>

4 × 4 × 2 = **32 种组合**，总有一款适合你。

---

## 智能推荐

不知道选哪个？输入「推荐」，告诉 Claude 你的 MBTI。

它会根据**认知功能互补原则**帮你匹配最合拍的队友 —— 不是找和你一样的，而是**补你短板的**。

> 你是 ENFP（快乐小狗），创意满分但容易发散？
> → 推荐「人狠话不多的技术大佬」，帮你把天马行空收束成靠谱的代码。

> 你是 ISTJ（活着的 SOP），严谨可靠但过于保守？
> → 推荐「你的天才队友」，挑战式沟通帮你跳出舒适区。

不知道自己的 MBTI？说一下你在做什么，Claude 按任务类型推荐。

---

## 保存与管理

```
你：保存这个人格        → 让预设跨会话保持生效
你：关闭人格            → 清除人格设定，恢复默认
你：当前人格            → 查看当前激活的人格
```

支持按**项目**或**全局**保存。默认仅当前对话生效，想保留时再说。

自动检测环境 —— 在 Claude Code / OpenClaw / Hermes 的对应身份文件里更新人格设定，支持项目级或全局。精确路径映射见 `SKILL.md`。

---

## 工作原理

```
                    ┌─────────────────────────┐
  "切换人格"  ──→   │  选择 / 输入 MBTI 类型   │
                    └────────────┬────────────┘
                                 │
                    ┌────────────▼────────────┐
                    │   加载人格定义            │
                    │   (预设 / 类型 / 自定义)   │
                    └────────────┬────────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                                     │
   ┌──────────▼──────────┐            ┌─────────────▼─────────────┐
   │  即时模式（默认）     │            │  持久模式（手动保存）       │
   │  仅当前对话生效       │            │  应用到 Agent 身份         │
   │  不修改任何文件       │            │  跨会话保持                │
   └─────────────────────┘            └───────────────────────────┘
```

**人格影响**：沟通风格 · 思考方式 · 代码风格偏好 · 交互模式

**人格不影响**：代码正确性 · 安全性 · 工具使用 · 技术决策

---

## 致谢

角色插画来自 [16personalities.com](https://www.16personalities.com/)。

---

## 为什么做这个

MBTI 在编程圈不只是性格测试 —— 它描述了人解决问题的**思维偏好**。

把这些偏好注入 AI，不是为了「准」，而是为了让人机协作更有**化学反应**。

一个 INTJ 风格的 Claude 会逼你先想清楚架构再动手。
一个 ESTP 风格的 Claude 会拽着你先跑起来再说。
这不是对错，是**互补**。

**找到你最需要的那个队友。**

---

## License

MIT
