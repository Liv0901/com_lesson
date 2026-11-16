---
title: AM 與 FM 比較
type: answer
sources: [2026-11-16-course-outline]
related: [am-modulation, fm-modulation, modulation-index, carsons-rule]
updated: 2026-11-16
---

# AM 與 FM 比較

> 提問：「同樣傳送音樂，AM 和 FM 各有什麼優缺點？」（2026-11-16）

| 項目 | AM | FM |
|---|---|---|
| 訊息改變什麼 | 載波振幅 | 載波頻率 |
| 調變指數 | `μ = Am / Ac`，需 ≤ 1 | `β = Δf / fm`，可 > 1 |
| 頻寬 | `2W` | `≈ 2(Δf + fm)` |
| 廣播實例頻寬 | 10 kHz（音訊 5 kHz） | 約 180 kHz（音訊 15 kHz） |
| 抗雜訊 | 差，雜訊直接疊在資訊上 | 好，接收機可限幅 |
| 接收機 | 簡單（包絡檢波） | 較複雜 |

## 結論
FM 用約 18 倍的頻寬，換來更高音質（音訊上限 15 kHz vs 5 kHz）與抗雜訊能力。頻道擁擠、只需傳語音時，AM 或窄頻 FM 較省頻寬。

## 引用頁面
- [AM 調變](../concepts/am-modulation.md)
- [FM 調變](../concepts/fm-modulation.md)
- [調變指數](../concepts/modulation-index.md)
- [卡森法則](../concepts/carsons-rule.md)
