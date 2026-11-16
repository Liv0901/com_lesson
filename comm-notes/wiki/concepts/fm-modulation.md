---
title: FM 調變
type: concept
sources: [2026-11-16-course-outline]
related: [modulation, modulation-index, carsons-rule, am-modulation]
updated: 2026-11-16
lesson: 03-fm-modulation
---

# FM 調變

## 一句話定義
頻率調變（frequency modulation, FM）讓訊息改變載波的頻率，振幅保持不變。

## 直覺說明
訊息高時載波振盪得快，訊息低時振盪得慢，波形忽密忽疏。雜訊多半疊加在振幅上，接收機可以直接把振幅削平（限幅），所以 FM 比 AM 抗雜訊。

## 公式
- `s(t) = Ac cos[2πfc t + β sin(2πfm t)]`
- 調變指數 `β = Δf / fm`，Δf 為最大頻率偏移（Hz），見 [調變指數](modulation-index.md)
- 頻寬用 [卡森法則](carsons-rule.md) 估算：`B ≈ 2(Δf + fm)`

## 常見誤解
- 「訊息越大，FM 波形越高」：錯，振幅固定，訊息大小只影響 Δf。
- 「FM 頻寬就是 2Δf」：不完整，還要加 2fm。

## 實例
- FM 廣播：Δf = 75 kHz、fm = 15 kHz → β = 5，頻寬約 180 kHz。

## 相關概念
- [AM 調變](am-modulation.md)：比較見 [AM 與 FM 比較](../answers/am-vs-fm.md)

## 出處
- [課程大綱 第 3 單元](../sources/2026-11-16-course-outline.md)
