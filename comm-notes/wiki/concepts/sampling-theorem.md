---
title: 取樣定理
type: concept
sources: [2026-11-16-course-outline]
related: [signals-and-spectrum, bandwidth]
updated: 2026-11-16
---

# 取樣定理

> 📝 資料不足：目前只有課程大綱的簡短重點，尚未上課。需補充課本例題與抗混疊濾波器的資料後，才適合做成第 4 回講義。

## 一句話定義
把連續訊號變成離散樣本時，取樣率必須大於訊號最高頻率的 2 倍，才能完整還原。

## 直覺說明
取樣太慢，快速變化的部分會被「看錯」成慢的訊號，這就是混疊（aliasing）。

## 公式
- `fs > 2fmax`：fs 為取樣率（Hz），fmax 為訊號最高頻率（Hz）；2fmax 稱為奈奎斯特率（Nyquist rate）

## 常見誤解
- （待補充資料後整理）

## 相關概念
- [訊號與頻譜](signals-and-spectrum.md)、[頻寬](bandwidth.md)

## 出處
- [課程大綱 第 4 單元](../sources/2026-11-16-course-outline.md)
