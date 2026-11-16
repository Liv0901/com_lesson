# 通訊原理講義站 + 知識庫

給通訊電子工程系學生的通訊原理預習與複習講義。參考 Andrej Karpathy 的 LLM Wiki 做法：先由 AI 把原始資料整理成知識庫，再從知識庫產生講義網頁。純 HTML + CSS，部署在 GitHub Pages。

- 線上瀏覽：`https://<你的帳號>.github.io/comm-notes/`
- 知識庫規則：[`AGENTS.md`](./AGENTS.md)
- 網站規則：[`CLAUDE.md`](./CLAUDE.md)
- 知識庫入口：[`wiki/index.md`](./wiki/index.md)

## 運作方式

```
raw/（老師放資料） → wiki/（AI 整理成知識庫） → lessons/（AI 產生講義網頁）
```

## 常用指令（對 AI 說）

| 想做的事 | 指令範例 |
|---|---|
| 匯入新資料 | 依照 AGENTS.md 匯入 raw/2026-11-20-sampling-notes.md |
| 對知識庫提問 | 依照 AGENTS.md 回答：AM 和 FM 哪個比較省電？值得保留就存成問答頁 |
| 健檢知識庫 | 依照 AGENTS.md 健檢知識庫 |
| 產生講義 | 依照 AGENTS.md 與 CLAUDE.md，把取樣定理做成第 4 回講義 |

## 目前講義

1. 訊號與頻譜
2. AM 調變
3. FM 調變（依 CLAUDE.md 流程由 AI 新增）
4. 取樣定理（規劃中，知識庫資料待補）
