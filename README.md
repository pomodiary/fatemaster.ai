<div align="center">

<img src="assets/logo.png" alt="FateMaster" width="120">

# FateMaster

**A deterministic engine draws the chart. AI reads it back in plain language.**

BaZi · Zi Wei Dou Shu · Liu Yao · Mei Hua Yi Shu · Qi Men Dun Jia · Tarot · Chinese Almanac

### [→ www.fatemaster.ai](https://www.fatemaster.ai)

**English** ·
[简体中文](README.zh-CN.md) ·
[繁體中文](README.zh-TW.md) ·
[日本語](README.ja.md) ·
[한국어](README.ko.md)

<sub>Open the site in your language:
<a href="https://www.fatemaster.ai/en">EN</a> ·
<a href="https://www.fatemaster.ai/zh">简体</a> ·
<a href="https://www.fatemaster.ai/zh-TW">繁體</a> ·
<a href="https://www.fatemaster.ai/ja">日本語</a> ·
<a href="https://www.fatemaster.ai/ko">한국어</a></sub>

</div>

---

## What it does

Most AI fortune-telling tools hand the whole job to a language model and hope it knows
what a Four Pillars chart looks like. FateMaster splits the work: a **rule engine
computes the chart deterministically**, then the AI interprets what the engine produced.

The chart is reproducible. Ask twice, get the same pillars. What changes between readings
is the reading, not the astronomy.

Core readings are free and need no signup.

## The seven systems

| System | Workspace | What it answers |
| --- | --- | --- |
| BaZi (Four Pillars) | [/workspace/bazi-calculate](https://www.fatemaster.ai/en/workspace/bazi-calculate) | The natal pattern and its changes through Luck Cycles |
| Zi Wei Dou Shu | [/workspace/ziwei-doushu](https://www.fatemaster.ai/en/workspace/ziwei-doushu) | The twelve palaces and star placements |
| Liu Yao | [/workspace/liuyao](https://www.fatemaster.ai/en/workspace/liuyao) | A specific question, cast as a hexagram |
| Mei Hua Yi Shu | [/workspace/meihua/daily-decision](https://www.fatemaster.ai/en/workspace/meihua/daily-decision) | A decision you need to make today |
| Qi Men Dun Jia | [/workspace/qimen](https://www.fatemaster.ai/en/workspace/qimen) | Timing and direction for a plan |
| Tarot | [/workspace/tarot](https://www.fatemaster.ai/en/workspace/tarot) | An open question, through image and symbol |
| Chinese Almanac | [/workspace/huangli](https://www.fatemaster.ai/en/workspace/huangli) | What today is suited to, and picking a date |

Plus [Daily Fortune](https://www.fatemaster.ai/en/workspace/bazi-daily) — your own chart
read against today.

## Relationship analysis

Compatibility usually means one thing: romance. Real relationships are more varied than
that, and each pairing reads differently in BaZi.

| | |
| --- | --- |
| [Marriage](https://www.fatemaster.ai/en/workspace/bazi-marriage) | [Dating compatibility](https://www.fatemaster.ai/en/workspace/bazi-lover) |
| [Business partnership](https://www.fatemaster.ai/en/workspace/bazi-business) | [Leader and subordinate](https://www.fatemaster.ai/en/workspace/bazi-leader) |
| [Parent and child](https://www.fatemaster.ai/en/workspace/bazi-parent-child) | [Mother and child](https://www.fatemaster.ai/en/workspace/bazi-mother-child) |
| [Mother-in-law](https://www.fatemaster.ai/en/workspace/bazi-mother-in-law) | [Close friends](https://www.fatemaster.ai/en/workspace/bazi-best-friends) |
| [Friends](https://www.fatemaster.ai/en/workspace/bazi-friends) | [Relationship network](https://www.fatemaster.ai/en/workspace/relationship-network) |

## Features

- **True solar time correction** — birth time adjusted for longitude, not just the clock
  on the wall. See [why it matters](https://www.fatemaster.ai/en/guides/true-solar-time)
- **Solar or lunar birth date**, or enter the four pillars directly if you already know them
- **Follow-up questions** — the chart stays in context, so you can keep asking
- **History** — readings are saved, not thrown away when you close the tab
- **Reading styles** for Tarot — the same spread, read four different ways
- **Five languages** — English, Simplified and Traditional Chinese, Japanese, Korean

## How it works

Charting is pure computation: solar terms, the sexagenary cycle, true solar time
correction, palace and star placement. That runs first, in code, with no model involved —
which is why the same birth data always produces the same chart.

The AI layer sits on top. It receives the computed chart as structured data and explains
it: what the pattern means, how the elements interact, what the current Luck Cycle
changes. It reads the chart; it does not invent it.

## Guides

Reference material on the concepts behind the charts — useful whether or not you ever
run a reading.

**Foundations** —
[Wu Xing (Five Elements)](https://www.fatemaster.ai/en/guides/wuxing) ·
[Tian Gan (Heavenly Stems)](https://www.fatemaster.ai/en/guides/tiangan) ·
[Di Zhi (Earthly Branches)](https://www.fatemaster.ai/en/guides/dizhi) ·
[Liu Shi Jia Zi (Sexagenary Cycle)](https://www.fatemaster.ai/en/guides/liushijiazi) ·
[Na Yin](https://www.fatemaster.ai/en/guides/nayin)

**Reading a chart** —
[Shi Shen (Ten Gods)](https://www.fatemaster.ai/en/guides/shishen) ·
[Ge Ju (Structure)](https://www.fatemaster.ai/en/guides/geju) ·
[Shen Sha](https://www.fatemaster.ai/en/guides/shensha) ·
[Xing Chong Hui He (Interactions)](https://www.fatemaster.ai/en/guides/xing-chong-hui-he) ·
[Da Yun (Luck Cycles)](https://www.fatemaster.ai/en/guides/dayun) ·
[Qi Yun (Starting Time)](https://www.fatemaster.ai/en/guides/qiyun-starting-time)

**Time and calendar** —
[True Solar Time](https://www.fatemaster.ai/en/guides/true-solar-time) ·
[Zi Hour Theory](https://www.fatemaster.ai/en/guides/zi-time-theory)

**Other systems** —
[64 Hexagrams](https://www.fatemaster.ai/en/guides/64-hexagrams) ·
[Qi Men Dun Jia](https://www.fatemaster.ai/en/guides/qimen-dunjia) ·
[Feng Shui](https://www.fatemaster.ai/en/guides/fengshui) ·
[Tarot cards](https://www.fatemaster.ai/en/tarot-cards)

Worked examples: [Mingli case studies](https://www.fatemaster.ai/en/mingli-cases) ·
[Blog](https://www.fatemaster.ai/en/blog)

## Pricing

Core readings are free. Paid plans unlock the full analysis depth across every system.

| | |
| --- | --- |
| Day Pass | $15 / day |
| Yearly | $59 / year — early bird, list price $299, renewal price locked |

See [pricing](https://www.fatemaster.ai/en/pricing) for what each plan includes.

## Built with

Next.js 15 · React · TypeScript · Tailwind CSS ·
[lunar-typescript](https://github.com/6tail/lunar-typescript) and
[lunar-javascript](https://github.com/6tail/lunar-javascript) for the calendar and
sexagenary math · OpenAI via the AI SDK for interpretation · Better Auth · Stripe

## About this repository

This is the public home for FateMaster — issues, feedback, and corrections to the
reference material are welcome here. **The application source is not open source.**

**Found a charting error?** [Open an issue](https://github.com/pomodiary/fatemaster.ai/issues)
with the birth data and what you expected. Chart accuracy reports are genuinely useful and
get fixed fast.

## Links

- Website — [www.fatemaster.ai](https://www.fatemaster.ai)
- X — [@Fatemaster38208](https://x.com/Fatemaster38208)
- Contact — hi@pomodiary.com

---

<div align="center">
<sub>八字 · 紫微斗數 · 四柱推命 · 사주 · Four Pillars of Destiny</sub>
</div>
