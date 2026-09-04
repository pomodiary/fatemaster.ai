<div align="center">

<img src="assets/logo.png" alt="FateMaster" width="120">

# FateMaster

**规则引擎先排盘，AI 再用大白话讲给你听。**

八字算命 · 紫微斗数 · 六爻 · 梅花易数 · 奇门遁甲 · 塔罗牌 · AI 老黄历

### [→ www.fatemaster.ai](https://www.fatemaster.ai/zh)

[English](README.md) ·
**简体中文** ·
[繁體中文](README.zh-TW.md) ·
[日本語](README.ja.md) ·
[한국어](README.ko.md)

</div>

---

## 它是做什么的

多数 AI 算命工具把整件事丢给大模型，指望它自己知道一副八字盘长什么样。FateMaster 把这两步拆开：**排盘由规则引擎确定性计算**，AI 只负责解读引擎算出来的结果。

所以盘是可复现的 —— 同一组生辰问两次，得到的是同一副盘。变的是解读，不是天文计算。

核心排盘免费，无需注册。

## 七套术数

| 术数 | 工作台 | 回答什么 |
| --- | --- | --- |
| 八字（四柱） | [/workspace/bazi-calculate](https://www.fatemaster.ai/zh/workspace/bazi-calculate) | 本命格局，以及大运带来的变化 |
| 紫微斗数 | [/workspace/ziwei-doushu](https://www.fatemaster.ai/zh/workspace/ziwei-doushu) | 十二宫与星曜落位 |
| 六爻 | [/workspace/liuyao](https://www.fatemaster.ai/zh/workspace/liuyao) | 一个具体问题，起卦来答 |
| 梅花易数 | [/workspace/meihua/daily-decision](https://www.fatemaster.ai/zh/workspace/meihua/daily-decision) | 今天要做的一个决定 |
| 奇门遁甲 | [/workspace/qimen](https://www.fatemaster.ai/zh/workspace/qimen) | 一件事的时机与方位 |
| 塔罗牌 | [/workspace/tarot](https://www.fatemaster.ai/zh/workspace/tarot) | 开放性问题，借图像与象征来看 |
| 老黄历 | [/workspace/huangli](https://www.fatemaster.ai/zh/workspace/huangli) | 今天宜忌，以及择日 |

另有[每日运势](https://www.fatemaster.ai/zh/workspace/bazi-daily) —— 用你自己的盘去看今天。

## 合盘与关系分析

说到"合盘"，多数产品只做姻缘一种。真实的关系远不止这一类，而每一种在八字里的读法都不一样。

| | |
| --- | --- |
| [八字合婚](https://www.fatemaster.ai/zh/workspace/bazi-marriage) | [恋人合盘](https://www.fatemaster.ai/zh/workspace/bazi-lover) |
| [事业合盘](https://www.fatemaster.ai/zh/workspace/bazi-business) | [领导下属](https://www.fatemaster.ai/zh/workspace/bazi-leader) |
| [父子关系](https://www.fatemaster.ai/zh/workspace/bazi-parent-child) | [母子关系](https://www.fatemaster.ai/zh/workspace/bazi-mother-child) |
| [婆媳合盘](https://www.fatemaster.ai/zh/workspace/bazi-mother-in-law) | [闺蜜合盘](https://www.fatemaster.ai/zh/workspace/bazi-best-friends) |
| [朋友关系](https://www.fatemaster.ai/zh/workspace/bazi-friends) | [八字关系图谱](https://www.fatemaster.ai/zh/workspace/relationship-network) |

## 功能

- **真太阳时校正** —— 按经度校正出生时间，而不是直接用钟表时间。[为什么这件事要紧](https://www.fatemaster.ai/zh/guides/true-solar-time)
- **公历或农历生日**，已经知道四柱的话也可以直接输入干支
- **追问** —— 盘一直在上下文里，可以接着问下去
- **历史记录** —— 排过的盘会存下来，不是关掉标签页就没了
- **塔罗的多种解读风格** —— 同一个牌阵，四种不同的读法
- **五种语言** —— 英文、简体中文、繁体中文、日文、韩文

## 工作原理

排盘是纯计算：节气、干支纪年、真太阳时校正、宫位与星曜落位。这一步先在代码里跑完，全程没有模型参与 —— 这就是为什么同一组生辰永远得到同一副盘。

AI 在这之上。它拿到的是排好的盘（结构化数据），负责解释：格局说明什么、五行如何生克、当前大运改变了什么。它读盘，但不造盘。

## 命理知识库

盘背后的概念，即使你不排盘也能当资料看。

**基础** —
[五行](https://www.fatemaster.ai/zh/guides/wuxing) ·
[天干](https://www.fatemaster.ai/zh/guides/tiangan) ·
[地支](https://www.fatemaster.ai/zh/guides/dizhi) ·
[六十甲子](https://www.fatemaster.ai/zh/guides/liushijiazi) ·
[纳音](https://www.fatemaster.ai/zh/guides/nayin)

**看盘** —
[十神](https://www.fatemaster.ai/zh/guides/shishen) ·
[格局](https://www.fatemaster.ai/zh/guides/geju) ·
[神煞](https://www.fatemaster.ai/zh/guides/shensha) ·
[刑冲会合](https://www.fatemaster.ai/zh/guides/xing-chong-hui-he) ·
[大运](https://www.fatemaster.ai/zh/guides/dayun) ·
[起运时间](https://www.fatemaster.ai/zh/guides/qiyun-starting-time)

**时间与历法** —
[真太阳时](https://www.fatemaster.ai/zh/guides/true-solar-time) ·
[子时理论](https://www.fatemaster.ai/zh/guides/zi-time-theory)

**其他术数** —
[六十四卦](https://www.fatemaster.ai/zh/guides/64-hexagrams) ·
[奇门遁甲](https://www.fatemaster.ai/zh/guides/qimen-dunjia) ·
[风水](https://www.fatemaster.ai/zh/guides/fengshui) ·
[塔罗牌义](https://www.fatemaster.ai/zh/tarot-cards)

实例：[命理案例](https://www.fatemaster.ai/zh/mingli-cases) ·
[博客](https://www.fatemaster.ai/zh/blog)

## 定价

核心排盘免费。付费档解锁全部术数的完整分析深度。

| | |
| --- | --- |
| 日卡 | $15 / 天 |
| 年卡 | $59 / 年 —— 早鸟价，原价 $299，续费价永久锁定 |

各档包含什么见[定价页](https://www.fatemaster.ai/zh/pricing)。

## 技术栈

Next.js 15 · React · TypeScript · Tailwind CSS ·
历法与干支计算用 [lunar-typescript](https://github.com/6tail/lunar-typescript) 和
[lunar-javascript](https://github.com/6tail/lunar-javascript) ·
解读通过 AI SDK 调用 OpenAI · Better Auth · Stripe

## 关于本仓库

这里是 FateMaster 的公开主页 —— 欢迎在这里提 issue、反馈，或指出知识库里的错误。**应用源代码不开源。**

**发现排盘错误？**[提个 issue](https://github.com/pomodiary/fatemaster.ai/issues)，附上生辰数据和你预期的结果。排盘准确性的反馈非常有用，我们会尽快修。

## 链接

- 网站 —— [www.fatemaster.ai](https://www.fatemaster.ai/zh)
- X —— [@Fatemaster73685](https://x.com/Fatemaster73685)
- 联系 —— hi@fatemaster.ai

---

<div align="center">
<sub>八字 · 紫微斗數 · 四柱推命 · 사주 · Four Pillars of Destiny</sub>
</div>
