---
title: 頻寬
type: concept
sources: [2026-11-16-course-outline]
related: [signals-and-spectrum, am-modulation, fm-modulation, carsons-rule]
updated: 2026-11-16
---

# 頻寬

## 一句話定義
頻寬（bandwidth）是訊號頻譜所佔的頻率範圍，決定傳輸時需要多寬的通道。

## 直覺說明
頻寬像道路的寬度：訊號越「寬」，就要分配越寬的頻道給它。比較各種調變方式時，頻寬是最重要的指標之一。

## 公式
- `B = fmax − fmin`：fmax、fmin 為頻譜中有明顯能量的最高與最低頻率（Hz）

## 常見誤解
- 「頻寬就是最高頻率」只對從 0 Hz 開始的基頻訊號成立。電話語音 300 Hz 到 3400 Hz，頻寬是 3.1 kHz。

## 各調變方式頻寬比較
| 方式 | 頻寬 | 出處 |
|---|---|---|
| AM | `2W` | [AM 調變](am-modulation.md) |
| FM | `2(Δf + fm)` | [卡森法則](carsons-rule.md) |

## 相關概念
- [訊號與頻譜](signals-and-spectrum.md)
- [AM 調變](am-modulation.md)、[FM 調變](fm-modulation.md)

## 出處
- [課程大綱 第 1～3 單元](../sources/2026-11-16-course-outline.md)
