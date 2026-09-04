<div align="center">

<img src="assets/logo.png" alt="FateMaster" width="120">

# FateMaster

**규칙 엔진이 명식을 계산하고, AI가 쉬운 말로 풀어줍니다.**

사주명리 · 자미두수 · 육효 · 매화역수 · 기문둔갑 · 타로 카드 · AI 황력

### [→ www.fatemaster.ai](https://www.fatemaster.ai/ko)

[English](README.md) ·
[简体中文](README.zh-CN.md) ·
[繁體中文](README.zh-TW.md) ·
[日本語](README.ja.md) ·
**한국어**

</div>

---

## 무엇을 하는 서비스인가

대부분의 AI 점술 도구는 모든 작업을 언어 모델에 통째로 맡기고, 모델이 사주 명식이 어떻게 생겼는지 알고 있기를 기대합니다. FateMaster는 이 과정을 나눴습니다. **명식은 규칙 엔진이 결정론적으로 계산하고**, AI는 그 결과를 해석할 뿐입니다.

그래서 명식은 재현됩니다. 같은 생년월일로 두 번 물어도 같은 사주가 나옵니다. 달라지는 것은 해석이지, 천문 계산이 아닙니다.

기본 풀이는 무료이며 가입도 필요 없습니다.

## 일곱 가지 체계

| 체계 | 워크스페이스 | 무엇을 답하는가 |
| --- | --- | --- |
| 사주명리 | [/workspace/bazi-calculate](https://www.fatemaster.ai/ko/workspace/bazi-calculate) | 타고난 명식과 대운에 따른 변화 |
| 자미두수 | [/workspace/ziwei-doushu](https://www.fatemaster.ai/ko/workspace/ziwei-doushu) | 십이궁과 성좌 배치 |
| 육효 | [/workspace/liuyao](https://www.fatemaster.ai/ko/workspace/liuyao) | 구체적인 질문을 괘로 뽑아 봅니다 |
| 매화역수 | [/workspace/meihua/daily-decision](https://www.fatemaster.ai/ko/workspace/meihua/daily-decision) | 오늘 내려야 할 결정 |
| 기문둔갑 | [/workspace/qimen](https://www.fatemaster.ai/ko/workspace/qimen) | 일의 시기와 방위 |
| 타로 카드 | [/workspace/tarot](https://www.fatemaster.ai/ko/workspace/tarot) | 열린 질문을 그림과 상징으로 |
| 황력 | [/workspace/huangli](https://www.fatemaster.ai/ko/workspace/huangli) | 오늘의 길흉과 날짜 잡기 |

이 밖에 [일일운세](https://www.fatemaster.ai/ko/workspace/bazi-daily) —— 자신의 명식을 오늘에 겹쳐 읽습니다.

## 궁합과 관계 분석

'궁합'이라고 하면 보통 연애 하나만 떠올리지만, 실제 관계는 훨씬 다양하고 사주에서는 조합마다 읽는 법이 다릅니다.

| | |
| --- | --- |
| [결혼 호환성](https://www.fatemaster.ai/ko/workspace/bazi-marriage) | [연인 궁합](https://www.fatemaster.ai/ko/workspace/bazi-lover) |
| [비즈니스 파트너십](https://www.fatemaster.ai/ko/workspace/bazi-business) | [리더-하급 관계](https://www.fatemaster.ai/ko/workspace/bazi-leader) |
| [부모-자식 관계](https://www.fatemaster.ai/ko/workspace/bazi-parent-child) | [모자관계](https://www.fatemaster.ai/ko/workspace/bazi-mother-child) |
| [시어머니 관계](https://www.fatemaster.ai/ko/workspace/bazi-mother-in-law) | [절친 궁합](https://www.fatemaster.ai/ko/workspace/bazi-best-friends) |
| [친구 관계](https://www.fatemaster.ai/ko/workspace/bazi-friends) | [사주 관계 네트워크](https://www.fatemaster.ai/ko/workspace/relationship-network) |

## 기능

- **진태양시 보정** —— 벽시계 시각 그대로가 아니라 경도에 맞춰 출생 시각을 보정합니다. [왜 중요한지](https://www.fatemaster.ai/ko/guides/true-solar-time)
- **양력·음력 생일 모두 입력 가능**. 이미 사주를 알고 있다면 간지를 직접 넣어도 됩니다
- **이어서 질문하기** —— 명식이 문맥에 남아 있어 계속 파고들 수 있습니다
- **기록** —— 뽑은 명식은 저장됩니다. 탭을 닫아도 사라지지 않습니다
- **타로 해석 스타일 선택** —— 같은 배열을 네 가지 방식으로
- **다섯 개 언어** —— 영어·간체중문·번체중문·일본어·한국어

## 작동 방식

명식을 뽑는 것은 순수한 계산입니다. 절기, 육십갑자, 진태양시 보정, 궁과 성좌 배치 —— 이 과정이 먼저 코드 안에서 끝나며 모델은 전혀 관여하지 않습니다. 같은 생년월일에서 항상 같은 명식이 나오는 이유입니다.

AI는 그 위에 얹힙니다. 계산된 명식을 구조화된 데이터로 받아, 격국이 무엇을 뜻하는지, 오행이 어떻게 맞물리는지, 지금의 대운이 무엇을 바꾸는지 설명합니다. 명식을 읽을 뿐, 만들지는 않습니다.

## 명리 해설

명식 뒤에 있는 개념 자료입니다. 풀이를 하지 않더라도 참고 자료로 쓸 수 있습니다.

**기초** —
[오행](https://www.fatemaster.ai/ko/guides/wuxing) ·
[천간](https://www.fatemaster.ai/ko/guides/tiangan) ·
[지지](https://www.fatemaster.ai/ko/guides/dizhi) ·
[육십갑자](https://www.fatemaster.ai/ko/guides/liushijiazi) ·
[납음](https://www.fatemaster.ai/ko/guides/nayin)

**명식 읽기** —
[십신](https://www.fatemaster.ai/ko/guides/shishen) ·
[격국](https://www.fatemaster.ai/ko/guides/geju) ·
[신살](https://www.fatemaster.ai/ko/guides/shensha) ·
[형충회합](https://www.fatemaster.ai/ko/guides/xing-chong-hui-he) ·
[대운](https://www.fatemaster.ai/ko/guides/dayun) ·
[기운 시점](https://www.fatemaster.ai/ko/guides/qiyun-starting-time)

**시간과 역법** —
[진태양시](https://www.fatemaster.ai/ko/guides/true-solar-time) ·
[자시 이론](https://www.fatemaster.ai/ko/guides/zi-time-theory)

**다른 체계** —
[육십사괘](https://www.fatemaster.ai/ko/guides/64-hexagrams) ·
[기문둔갑](https://www.fatemaster.ai/ko/guides/qimen-dunjia) ·
[풍수](https://www.fatemaster.ai/ko/guides/fengshui) ·
[타로 카드 의미](https://www.fatemaster.ai/ko/tarot-cards)

실제 사례: [명리 사례 연구](https://www.fatemaster.ai/ko/mingli-cases) ·
[블로그](https://www.fatemaster.ai/ko/blog)

## 요금

기본 풀이는 무료입니다. 유료 플랜은 모든 체계에서 분석 깊이를 열어줍니다.

| | |
| --- | --- |
| 데이 패스 | $15 / 일 |
| 연간 플랜 | $59 / 년 —— 얼리버드 가격. 정가 $299, 갱신 가격 고정 |

플랜별 포함 내역은 [요금 페이지](https://www.fatemaster.ai/ko/pricing)를 참고하세요.

## 기술 스택

Next.js 15 · React · TypeScript · Tailwind CSS ·
역법과 간지 계산에 [lunar-typescript](https://github.com/6tail/lunar-typescript),
[lunar-javascript](https://github.com/6tail/lunar-javascript) ·
해석은 AI SDK를 통해 OpenAI · Better Auth · Stripe

## 이 저장소에 대하여

여기는 FateMaster의 공개 홈입니다. 이슈, 피드백, 해설 자료의 오류 지적을 환영합니다. **애플리케이션 소스 코드는 공개하지 않습니다.**

**명식 오류를 발견하셨다면** —— 생년월일과 예상한 결과를 함께 적어 [이슈를 남겨주세요](https://github.com/pomodiary/fatemaster.ai/issues). 명식 정확도에 관한 제보는 정말 큰 도움이 되며 우선적으로 고칩니다.

## 링크

- 웹사이트 —— [www.fatemaster.ai](https://www.fatemaster.ai/ko)
- X —— [@Fatemaster38208](https://x.com/Fatemaster38208)
- 문의 —— hi@fatemaster.ai

---

<div align="center">
<sub>八字 · 紫微斗數 · 四柱推命 · 사주 · Four Pillars of Destiny</sub>
</div>
