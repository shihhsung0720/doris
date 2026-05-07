# 01-data-brain — 品牌知識層

Doris 個人 IP 的「品牌靈魂」+「彈藥庫」、給 AI 寫腳本前讀。

## 設計理念

1. **知識層 vs 狀態層分開**：這個資料夾是知識層（人寫 markdown）。未來如有狀態層（機器寫 JSON）會放別處
2. **brand.md 是靈魂、慢變、人填**：AI 唯讀、不准生成
3. **cases.md 是彈藥庫**：寫腳本舉例時來這找
4. **brand-summary.md 是速查版**：由 brand.md 提煉、SessionStart hook 自動注入
5. **index.md 是地圖**：SSoT、決定誰讀什麼、新增資料層只改這

## 檔案

| 檔案 | 角色 |
|---|---|
| `index.md` | 資料地圖 SSoT |
| `brand.md` | 品牌大腦本體（精簡 8 節） |
| `brand-summary.md` | 速查精簡版（待 brand.md 填到一定程度後生成） |
| `cases.md` | 爆款案例庫 |
