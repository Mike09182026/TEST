# ZeroTrace Branding Guide

## 1. 名稱與標語
- **產品名稱**：ZeroTrace
- **標語**：極致隱私·零痕跡

## 2. 色彩方案
| 角色 | HEX | 用途 |
|------|------|------|
| 主色 | `#00f0ff` | 主要按鈕、徽章、即時訊息點綴 |
| 次色 | `#00ff88` | 次要按鈕、強調文字 |
| 暗背景 | `#070b12` | 頁面背景、底層容器 |
| 卡片背景 | `#0d1522` | 卡片、彈窗底色 |
| 警示色 | `#f59e0b` (Amber) | 警示、提醒、捐贈按鈕 |
| 文本主色 | `#f0f4f8` | 主要文字 |
| 文本次色 | `#8a99ad` | 次要文字、描述 |

## 3. 字體與排版
- **字體**：-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans TC", "Microsoft JhengHei", sans-serif
- **字重**：
  - 標題：900 (超粗) 
  - 小標題：800 
  - 正文：600‑700 
- **行高**：1.6（正文）
- **字距**：標題使用 `letter-spacing: 1px`，提升科技感

## 4. 標誌與圖示
- **Logo**：文字 `ZeroTrace`，`Zero` 使用主色 (`#00f0ff`)，`Trace` 使用次色 (`#00ff88`)。可搭配簡潔的弧形圖形象徵「零痕跡」。
- **圖示**：使用線性圖示（line‑icon），顏色遵循主/次色調。圖示尺寸建議 24‑32px。

## 5. UI 元件樣式
| 元件 | CSS 範例 |
|------|----------|
| 按鈕 | `background: linear-gradient(135deg, var(--primary), #0077ff); color: #000; border-radius: 30px;` |
| 標籤 (chip) | `background: rgba(0,240,255,0.12); border: 1px solid var(--primary); color: var(--primary); border-radius: 40px;` |
| 卡片 | `background: var(--card-bg); border: 1px solid var(--card-border); border-radius: 16px;` |
| 滑動條 | 使用 `.paradigm-pill` 互動樣式（參見 `index.html`） |

## 6. 多語系支援
- 所有 UI 文案均以 `data-i18n="key"` 方式標記。
- 每個 `key` 必須在 `zh`, `en`, `ja` 三語的翻譯物件中都有條目。
- 新增的文字鍵如下（已在 `index.html` 中加入）：
  - `backer_title`, `backer_desc`, `investor_title`, `investor_desc`
  - `labs_title`, `labs_desc`, `lab_zero_trace_ram`, `lab_airdrop_x`, `lab_steganovault`, `lab_hardware_key`

## 7. 使用建議
- **保持極簡**：避免長段文字，使用卡片、標籤、圖示快速傳遞資訊。
- **漸層交互**：在滑動切換、時間軸等互動中使用主/次色的漸層過渡，提高視覺層次感。
- **可存取性**：確保文字與背景對比度符合 WCAG AA（最小 4.5:1），尤其在暗背景上使用亮色文字。

---
*此指南僅作為 ZeroTrace 專案的 UI/UX 基礎，未來若有新功能請持續擴充相應的色彩與字體規範。*
