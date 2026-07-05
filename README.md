# 🧭 英語學習入口（英語一點通）

整個英語 App 家族的**總入口頁 + 跨 App 學習儀表板**。一頁看到所有 App、一鍵開啟，並彙整各 App 的學習進度。

> App 顯示名稱：**英語一點通**（manifest `name`）。純單一 HTML 檔、離線可用、免安裝。

> **狀態**：✅ 使用中（hub-v4）　｜　🔵 主題 `#4f6ef7`　｜　📊 跨 App 儀表板　｜　📱 響應式

---

## ✨ 功能
- **總入口**：列出並連到全部英語 App（單字／題庫／會話／拼句等）
- **跨 App 學習儀表板（hub-v4）**：彙整各 App 進度，已補上**多益／托福**進度彙整
- **共用進度 key**：先前「共用 key 撞資料」bug 已修，各 App 的 `localStorage` key 皆有專屬後綴，互不覆蓋

## 🔗 收錄的 App（上線連結）
| App | 網址 |
|---|---|
| 國小 1200 | <https://fullmodel-star.github.io/english1200/> |
| 國中 2000 | <https://fullmodel-star.github.io/english2000/> |
| 高中 6000 | <https://fullmodel-star.github.io/english6000/> |
| 多益單字 | <https://fullmodel-star.github.io/toeic-vocab/> |
| 托福單字 | <https://fullmodel-star.github.io/toefl-vocab/> |
| 會考複習 | <https://fullmodel-star.github.io/cap-english/> |
| 學測複習 | <https://fullmodel-star.github.io/gsat-english/> |
| 會考題庫 | <https://fullmodel-star.github.io/cap-qbank/> |
| 學測題庫 | <https://fullmodel-star.github.io/gsat-qbank/> |
| 閱讀 | <https://fullmodel-star.github.io/englishreading/> |
| 拼句 | <https://fullmodel-star.github.io/englishS/> |
| 旅遊英文 | <https://fullmodel-star.github.io/travel-english/> |
| 家庭生活 | <https://fullmodel-star.github.io/family-english/> |
| 校園生活 | <https://fullmodel-star.github.io/campus-english/> |
| 生活辦事 | <https://fullmodel-star.github.io/errand-english/> |
| 社交英文 | <https://fullmodel-star.github.io/social-english/> |

## 📁 檔案結構
| 檔案 | 說明 |
|---|---|
| `index.html` | 入口頁 + 儀表板（單檔） |
| `manifest.json` / `sw.js` | PWA 設定與離線快取 |
| `icon-*.png` / `apple-touch-icon.png` / `icon.svg` | 圖示 |

## 🔒 隱私
完全離線、不連外部伺服器；進度資料只存裝置 `localStorage`；無帳號、無追蹤、無廣告。

## 📝 變更記錄
- 2026-07-05：建立本 README。
- hub-v4：補上多益／托福進度彙整；修正共用 key bug（各 App key 皆加後綴）。
