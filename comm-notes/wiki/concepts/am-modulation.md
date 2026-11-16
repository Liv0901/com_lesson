---
title: AM 調變
type: concept
sources: [2026-11-16-course-outline]
related: [modulation, modulation-index, bandwidth, fm-modulation]
updated: 2026-11-16
lesson: 02-am-modulation
---

# AM 調變

## 一句話定義
振幅調變（amplitude modulation, AM）讓訊息改變載波的振幅，載波的包絡（envelope）就是訊息的形狀。

## 直覺說明
載波的高度跟著訊息起伏。接收端只要沿著外框描出包絡，就能還原訊息，所以接收機很簡單。

## 公式
- `s(t) = Ac[1 + μ cos(2πfm t)] cos(2πfc t)`
- 調變指數 `μ = Am / Ac`，見 [調變指數](modulation-index.md)
- 頻寬 `B = 2W`，W 為訊息最高頻率（Hz）
- 功率效率 `η = μ² / (2 + μ²)`，μ = 1 時約 33%

## 常見誤解
- μ 設大於 1 會過度調變，包絡檢波失真。
- 功率大部分花在不帶資訊的載波上。

## 實例
- AM 廣播音訊上限 5 kHz，每臺頻寬 10 kHz。

## 相關概念
- [FM 調變](fm-modulation.md)：比較見 [AM 與 FM 比較](../answers/am-vs-fm.md)
- [頻寬](bandwidth.md)

## 出處
- [課程大綱 第 2 單元](../sources/2026-11-16-course-outline.md)
