---
title: 卡森法則
type: concept
sources: [2026-11-16-course-outline]
related: [fm-modulation, bandwidth, modulation-index]
updated: 2026-11-16
---

# 卡森法則

## 一句話定義
卡森法則（Carson's rule）用來估算 FM 訊號的頻寬，約包含 98% 的功率。

## 直覺說明
FM 理論上有無限多根旁帶，但離載波越遠越小。實務上只要算到夠用的範圍：載波被推開的距離 Δf，再加上訊息本身的頻率 fm，兩邊各一份。

## 公式
- `B ≈ 2(Δf + fm) = 2(β + 1)fm`
- B：近似頻寬（Hz）；Δf：最大頻率偏移（Hz）；fm：訊息最高頻率（Hz）

## 常見誤解
- 漏掉 fm，只算 2Δf。
- β 很小（窄頻 FM）時，頻寬約為 2fm，和 AM 差不多。

## 實例
- FM 廣播：2 × (75 + 15) kHz = 180 kHz

## 相關概念
- [FM 調變](fm-modulation.md)、[頻寬](bandwidth.md)、[調變指數](modulation-index.md)

## 出處
- [課程大綱 第 3 單元](../sources/2026-11-16-course-outline.md)
