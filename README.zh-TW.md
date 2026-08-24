<div align="center">

<img src="assets/logo.png" alt="FateMaster" width="120">

# FateMaster

**規則引擎先排盤，AI 再用白話講給你聽。**

八字算命 · 紫微斗數 · 六爻 · 梅花易數 · 奇門遁甲 · 塔羅牌 · AI 老黃曆

### [→ www.fatemaster.ai](https://www.fatemaster.ai/zh-Hant)

[English](README.md) ·
[简体中文](README.zh-CN.md) ·
**繁體中文** ·
[日本語](README.ja.md) ·
[한국어](README.ko.md)

</div>

---

## 它是做什麼的

多數 AI 算命工具把整件事丟給大模型，指望它自己知道一副八字盤長什麼樣。FateMaster 把這兩步拆開：**排盤由規則引擎確定性計算**，AI 只負責解讀引擎算出來的結果。

所以盤是可重現的 —— 同一組生辰問兩次，得到的是同一副盤。變的是解讀，不是天文計算。

核心排盤免費，無需註冊。

## 七套術數

| 術數 | 工作台 | 回答什麼 |
| --- | --- | --- |
| 八字（四柱） | [/workspace/bazi-calculate](https://www.fatemaster.ai/zh-Hant/workspace/bazi-calculate) | 本命格局，以及大運帶來的變化 |
| 紫微斗數 | [/workspace/ziwei-doushu](https://www.fatemaster.ai/zh-Hant/workspace/ziwei-doushu) | 十二宮與星曜落位 |
| 六爻 | [/workspace/liuyao](https://www.fatemaster.ai/zh-Hant/workspace/liuyao) | 一個具體問題，起卦來答 |
| 梅花易數 | [/workspace/meihua/daily-decision](https://www.fatemaster.ai/zh-Hant/workspace/meihua/daily-decision) | 今天要做的一個決定 |
| 奇門遁甲 | [/workspace/qimen](https://www.fatemaster.ai/zh-Hant/workspace/qimen) | 一件事的時機與方位 |
| 塔羅牌 | [/workspace/tarot](https://www.fatemaster.ai/zh-Hant/workspace/tarot) | 開放性問題，藉圖像與象徵來看 |
| 老黃曆 | [/workspace/huangli](https://www.fatemaster.ai/zh-Hant/workspace/huangli) | 今日宜忌，以及擇日 |

另有[每日運勢](https://www.fatemaster.ai/zh-Hant/workspace/bazi-daily) —— 用你自己的盤去看今天。

## 合盤與關係分析

說到「合盤」，多數產品只做姻緣一種。真實的關係遠不止這一類，而每一種在八字裡的讀法都不一樣。

| | |
| --- | --- |
| [八字合婚](https://www.fatemaster.ai/zh-Hant/workspace/bazi-marriage) | [戀人合盤](https://www.fatemaster.ai/zh-Hant/workspace/bazi-lover) |
| [事業合盤](https://www.fatemaster.ai/zh-Hant/workspace/bazi-business) | [領導下屬](https://www.fatemaster.ai/zh-Hant/workspace/bazi-leader) |
| [父子關係](https://www.fatemaster.ai/zh-Hant/workspace/bazi-parent-child) | [母子關係](https://www.fatemaster.ai/zh-Hant/workspace/bazi-mother-child) |
| [婆媳合盤](https://www.fatemaster.ai/zh-Hant/workspace/bazi-mother-in-law) | [閨蜜合盤](https://www.fatemaster.ai/zh-Hant/workspace/bazi-best-friends) |
| [朋友關係](https://www.fatemaster.ai/zh-Hant/workspace/bazi-friends) | [八字關係圖譜](https://www.fatemaster.ai/zh-Hant/workspace/relationship-network) |

## 功能

- **真太陽時校正** —— 按經度校正出生時間，而不是直接用鐘錶時間。[為什麼這件事要緊](https://www.fatemaster.ai/zh-Hant/guides/true-solar-time)
- **國曆或農曆生日**，已經知道四柱的話也可以直接輸入干支
- **追問** —— 盤一直在上下文裡，可以接著問下去
- **歷史紀錄** —— 排過的盤會存下來，不是關掉分頁就沒了
- **塔羅的多種解讀風格** —— 同一個牌陣，四種不同的讀法
- **五種語言** —— 英文、簡體中文、繁體中文、日文、韓文

## 運作方式

排盤是純計算：節氣、干支紀年、真太陽時校正、宮位與星曜落位。這一步先在程式碼裡跑完，全程沒有模型參與 —— 這就是為什麼同一組生辰永遠得到同一副盤。

AI 在這之上。它拿到的是排好的盤（結構化資料），負責解釋：格局說明什麼、五行如何生剋、當前大運改變了什麼。它讀盤，但不造盤。

## 命理知識庫

盤背後的概念，即使你不排盤也能當資料看。

**基礎** —
[五行](https://www.fatemaster.ai/zh-Hant/guides/wuxing) ·
[天干](https://www.fatemaster.ai/zh-Hant/guides/tiangan) ·
[地支](https://www.fatemaster.ai/zh-Hant/guides/dizhi) ·
[六十甲子](https://www.fatemaster.ai/zh-Hant/guides/liushijiazi) ·
[納音](https://www.fatemaster.ai/zh-Hant/guides/nayin)

**看盤** —
[十神](https://www.fatemaster.ai/zh-Hant/guides/shishen) ·
[格局](https://www.fatemaster.ai/zh-Hant/guides/geju) ·
[神煞](https://www.fatemaster.ai/zh-Hant/guides/shensha) ·
[刑沖會合](https://www.fatemaster.ai/zh-Hant/guides/xing-chong-hui-he) ·
[大運](https://www.fatemaster.ai/zh-Hant/guides/dayun) ·
[起運時間](https://www.fatemaster.ai/zh-Hant/guides/qiyun-starting-time)

**時間與曆法** —
[真太陽時](https://www.fatemaster.ai/zh-Hant/guides/true-solar-time) ·
[子時理論](https://www.fatemaster.ai/zh-Hant/guides/zi-time-theory)

**其他術數** —
[六十四卦](https://www.fatemaster.ai/zh-Hant/guides/64-hexagrams) ·
[奇門遁甲](https://www.fatemaster.ai/zh-Hant/guides/qimen-dunjia) ·
[風水](https://www.fatemaster.ai/zh-Hant/guides/fengshui) ·
[塔羅牌義](https://www.fatemaster.ai/zh-Hant/tarot-cards)

實例：[命理案例](https://www.fatemaster.ai/zh-Hant/mingli-cases) ·
[部落格](https://www.fatemaster.ai/zh-Hant/blog)

## 定價

核心排盤免費。付費檔解鎖全部術數的完整分析深度。

| | |
| --- | --- |
| 日卡 | $15 / 天 |
| 年卡 | $59 / 年 —— 早鳥價，原價 $299，續費價永久鎖定 |

各檔包含什麼見[定價頁](https://www.fatemaster.ai/zh-Hant/pricing)。

## 技術棧

Next.js 15 · React · TypeScript · Tailwind CSS ·
曆法與干支計算用 [lunar-typescript](https://github.com/6tail/lunar-typescript) 和
[lunar-javascript](https://github.com/6tail/lunar-javascript) ·
解讀透過 AI SDK 呼叫 OpenAI · Better Auth · Stripe

## 關於本倉庫

這裡是 FateMaster 的公開主頁 —— 歡迎在這裡提 issue、回饋，或指出知識庫裡的錯誤。**應用原始碼不開源。**

**發現排盤錯誤？**[提個 issue](https://github.com/pomodiary/fatemaster.ai/issues)，附上生辰資料和你預期的結果。排盤準確性的回饋非常有用，我們會盡快修。

## 連結

- 網站 —— [www.fatemaster.ai](https://www.fatemaster.ai/zh-Hant)
- X —— [@Fatemaster73685](https://x.com/Fatemaster73685)
- 聯絡 —— hi@pomodiary.com

---

<div align="center">
<sub>八字 · 紫微斗數 · 四柱推命 · 사주 · Four Pillars of Destiny</sub>
</div>
