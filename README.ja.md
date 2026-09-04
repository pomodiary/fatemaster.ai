<div align="center">

<img src="assets/logo.png" alt="FateMaster" width="120">

# FateMaster

**命式はルールエンジンが計算し、AI がそれを平易な言葉で読み解く。**

四柱推命 · 紫微斗数 · 六爻 · 梅花易数 · 奇門遁甲 · タロットカード · AI 旧暦カレンダー

### [→ www.fatemaster.ai](https://www.fatemaster.ai/ja)

[English](README.md) ·
[简体中文](README.zh-CN.md) ·
[繁體中文](README.zh-TW.md) ·
**日本語** ·
[한국어](README.ko.md)

</div>

---

## これは何をするもの

多くの AI 占いツールは、命式のことを大規模言語モデルが分かっている前提で、すべてを丸投げしています。FateMaster は工程を分けました。**命式はルールエンジンが確定的に計算し**、AI はその結果を解釈するだけです。

だから命式は再現します。同じ生年月日で二度尋ねても、同じ四柱が出ます。変わるのは読み解きであって、天文計算のほうではありません。

基本の鑑定は無料、登録も不要です。

## 七つの体系

| 体系 | ワークスペース | 何が分かるか |
| --- | --- | --- |
| 四柱推命 | [/workspace/bazi-calculate](https://www.fatemaster.ai/ja/workspace/bazi-calculate) | 生まれ持った命式と、大運による移り変わり |
| 紫微斗数 | [/workspace/ziwei-doushu](https://www.fatemaster.ai/ja/workspace/ziwei-doushu) | 十二宮と星の配置 |
| 六爻 | [/workspace/liuyao](https://www.fatemaster.ai/ja/workspace/liuyao) | 具体的な問いを、卦を立てて占う |
| 梅花易数 | [/workspace/meihua/daily-decision](https://www.fatemaster.ai/ja/workspace/meihua/daily-decision) | 今日下すべき判断 |
| 奇門遁甲 | [/workspace/qimen](https://www.fatemaster.ai/ja/workspace/qimen) | 物事のタイミングと方位 |
| タロットカード | [/workspace/tarot](https://www.fatemaster.ai/ja/workspace/tarot) | 開かれた問いを、図像と象徴から読む |
| 旧暦カレンダー | [/workspace/huangli](https://www.fatemaster.ai/ja/workspace/huangli) | 今日の吉凶と、日取り |

ほかに[毎日の運勢](https://www.fatemaster.ai/ja/workspace/bazi-daily) —— 自分の命式を今日に重ねて読みます。

## 相性・関係の分析

「相性」というと恋愛だけを指しがちですが、現実の関係はもっと多様で、四柱推命では組み合わせごとに読み方が変わります。

| | |
| --- | --- |
| [四柱推命結婚相性](https://www.fatemaster.ai/ja/workspace/bazi-marriage) | [恋人相性](https://www.fatemaster.ai/ja/workspace/bazi-lover) |
| [事業連携分析](https://www.fatemaster.ai/ja/workspace/bazi-business) | [上司部下関係](https://www.fatemaster.ai/ja/workspace/bazi-leader) |
| [親子関係](https://www.fatemaster.ai/ja/workspace/bazi-parent-child) | [母子関係](https://www.fatemaster.ai/ja/workspace/bazi-mother-child) |
| [姑嫁関係分析](https://www.fatemaster.ai/ja/workspace/bazi-mother-in-law) | [親友相性分析](https://www.fatemaster.ai/ja/workspace/bazi-best-friends) |
| [友人関係](https://www.fatemaster.ai/ja/workspace/bazi-friends) | [四柱推命 関係ネットワーク](https://www.fatemaster.ai/ja/workspace/relationship-network) |

## 機能

- **真太陽時の補正** —— 時計の時刻そのままではなく、経度で出生時刻を補正します。[なぜ重要か](https://www.fatemaster.ai/ja/guides/true-solar-time)
- **新暦・旧暦のどちらでも入力可**。四柱がすでに分かっていれば干支を直接入力もできます
- **続けて質問できる** —— 命式が文脈に残るので、そのまま掘り下げられます
- **履歴** —— 出した命式は保存されます。タブを閉じても消えません
- **タロットの読み口を選べる** —— 同じスプレッドを四通りの読み方で
- **五言語対応** —— 英語・簡体中文・繁体中文・日本語・韓国語

## しくみ

命式を出すのは純粋な計算です。節気、干支、真太陽時の補正、宮と星の配置 —— これがまずコードの中で完結し、モデルは一切関与しません。同じ生年月日から常に同じ命式が出るのはこのためです。

AI はその上に乗ります。計算済みの命式を構造化データとして受け取り、格局が何を意味するか、五行がどう働き合うか、今の大運が何を変えるかを説明します。命式を読むのであって、作るのではありません。

## 命理の解説

命式の背後にある概念の資料です。鑑定をしなくても読み物として使えます。

**基礎** —
[五行](https://www.fatemaster.ai/ja/guides/wuxing) ·
[天干](https://www.fatemaster.ai/ja/guides/tiangan) ·
[地支](https://www.fatemaster.ai/ja/guides/dizhi) ·
[六十干支](https://www.fatemaster.ai/ja/guides/liushijiazi) ·
[納音](https://www.fatemaster.ai/ja/guides/nayin)

**命式を読む** —
[十神](https://www.fatemaster.ai/ja/guides/shishen) ·
[格局](https://www.fatemaster.ai/ja/guides/geju) ·
[神殺](https://www.fatemaster.ai/ja/guides/shensha) ·
[刑冲会合](https://www.fatemaster.ai/ja/guides/xing-chong-hui-he) ·
[大運](https://www.fatemaster.ai/ja/guides/dayun) ·
[立運の起算](https://www.fatemaster.ai/ja/guides/qiyun-starting-time)

**時刻と暦** —
[真太陽時](https://www.fatemaster.ai/ja/guides/true-solar-time) ·
[子刻の考え方](https://www.fatemaster.ai/ja/guides/zi-time-theory)

**ほかの体系** —
[六十四卦](https://www.fatemaster.ai/ja/guides/64-hexagrams) ·
[奇門遁甲](https://www.fatemaster.ai/ja/guides/qimen-dunjia) ·
[風水](https://www.fatemaster.ai/ja/guides/fengshui) ·
[タロットカードの意味](https://www.fatemaster.ai/ja/tarot-cards)

実例：[命理ケーススタディ](https://www.fatemaster.ai/ja/mingli-cases) ·
[ブログ](https://www.fatemaster.ai/ja/blog)

## 料金

基本の鑑定は無料です。有料プランでは、すべての体系で分析の深さが解放されます。

| | |
| --- | --- |
| デイパス | $15 / 日 |
| 年間プラン | $59 / 年 —— 早期価格。通常 $299、更新価格は据え置き |

各プランの内容は[料金ページ](https://www.fatemaster.ai/ja/pricing)をご覧ください。

## 技術構成

Next.js 15 · React · TypeScript · Tailwind CSS ·
暦と干支の計算に [lunar-typescript](https://github.com/6tail/lunar-typescript) と
[lunar-javascript](https://github.com/6tail/lunar-javascript) ·
解釈は AI SDK 経由で OpenAI · Better Auth · Stripe

## このリポジトリについて

ここは FateMaster の公開ページです。issue・ご意見・解説の誤りのご指摘を歓迎します。**アプリケーションのソースコードは公開していません。**

**命式の誤りを見つけたら** —— 生年月日と期待した結果を添えて[issue を立ててください](https://github.com/pomodiary/fatemaster.ai/issues)。命式の正確さに関する報告は本当に助かりますし、優先して直します。

## リンク

- ウェブサイト —— [www.fatemaster.ai](https://www.fatemaster.ai/ja)
- X —— [@Fatemaster95726](https://x.com/Fatemaster95726)
- お問い合わせ —— hi@fatemaster.ai

---

<div align="center">
<sub>八字 · 紫微斗數 · 四柱推命 · 사주 · Four Pillars of Destiny</sub>
</div>
