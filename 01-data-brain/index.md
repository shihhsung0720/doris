# index.md — 資料地圖（SSoT）

新增 / 改動資料層、只改這個檔。

---

## 載入清單（什麼任務讀什麼）

| 任務類型 | 必讀 | 選讀 |
|---|---|---|
| 寫短影音腳本 | `brand-summary.md`、`brand.md` [3][4][5][7] | `cases.md` |
| 想選題 / 找角度 | `brand.md` [3][4]、`cases.md` | `brand-summary.md` |
| 改品牌定位 / 調性 | `brand.md` 全部 | `cases.md` |
| 一般對話 | `brand-summary.md` | — |

---

## 寫入分工矩陣

| 檔案 | 誰可以寫 | 誰只能讀 |
|---|---|---|
| `brand.md` | Doris 本人 | AI |
| `cases.md` | Doris + AI 協助整理 | — |
| `brand-summary.md` | 由 `brand.md` 提煉（衍生、不可手改） | 所有人 |
| `index.md` | Doris（決定資料架構時） | AI |

---

## 進化觸發規則

- `brand.md` 任一節 `last_updated` > 90 天 → 對話開頭提醒
- `cases.md` 案例數 < 5 → 寫腳本前提醒「彈藥不足」
- 新增資料層（例如未來加 `competitors.md`、`products.md`）→ 必須回來改 `index.md`
