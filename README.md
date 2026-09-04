# AI Agent 教師研習｜3 小時速成版簡報

給高中非資訊科教師的 AI Agent 入門研習簡報。單一 HTML 檔，用瀏覽器打開即可播放。

**主軸：把生成教材做成技能。** 三小時只有一條線 —— 先講清楚 → 做一次 → 把它變成永久的。
散場時每位老師手上有一份考卷、一整包教材，以及一個能重複觸發、可以複製給同事的技能。

## 播放

打開簡報網址，按 `F` 全螢幕即可上台。

| 按鍵 | 動作 |
|---|---|
| `→` `↓` `空白` | 下一頁 |
| `←` `↑` | 上一頁 |
| `Home` / `End` | 第一頁 / 最後一頁 |
| `F` | 全螢幕 |
| `E` | 匯出當前頁 2× PNG |

也可以點畫面右側 30% 下一頁、左側 30% 上一頁（觸控與簡報筆友善）。

## 內容（22 頁）

| 段落 | 頁 | 內容 |
|---|---|---|
| 引起動機 | 1–4 | 痛點 → 代理 vs 生成 → 今天的路線 |
| S1 先講清楚，再讓它做 | 5–11 | 四大能力、專案與路徑、三條安全底線、**需求探索四象限**、實作①出一份考卷 |
| S2 做過一次，就讓它變成你的 | 12–18 | 一份教材長出一整包、Bloom 分層、技能是說明書、**對話型 vs 檔案型**、實作②包成技能 |
| 喚起行動 | 19–22 | 評分看什麼、回校後會撞到的三件事、下一步 |

### 三個互動元件

- **P10 需求探索四象限**：點卡片展開。建議現場一格一格點開，第三、四象限留到最後
- **P14 Bloom 分層對比表**：點欄位標題可排序，含一欄「假分層的樣子」
- **P19 評分雷達圖**：對比「只顧做出來」與「做出來且檢查過」

## 設計

- 林長揚 30 原則：字級階層、標題 ≤10 字、一頁一重點、強調色僅 2 種
- SOIL 三段式脈絡，左上角即時顯示當前段落
- 8px 基線網格
- 版面驗收：1600×900 與 1366×768 兩種解析度，22 頁零溢出
- 全向量 SVG，無外嵌點陣圖，檔案 45 KB

## 需要網路

`E` 鍵匯出 PNG（html-to-image）、P19 雷達圖（Chart.js）與字體（Google Fonts）走 CDN。
場地無網路時仍可正常播放與翻頁，但上述三項會失效。

## 教材來源與致謝

本研習的觀念與方法，整理自 **[三師爸 Sense Bar](https://www.youtube.com/@sensebar)** 的教學影片。

| 系列 | 連結 |
|---|---|
| AI Agent 基本功 EP01–EP07 | [播放清單](https://www.youtube.com/playlist?list=PLkNQUBglz8EyGuOIKfrKX9V7ot5VbZKha) |
| Claude Code 基本功 | [播放清單](https://www.youtube.com/playlist?list=PLkNQUBglz8EwHJQu6ijh5ra41RTfaaZT8) |
| ChatGPT Codex 基本功 | [播放清單](https://www.youtube.com/playlist?list=PLkNQUBglz8EyvaS1lFWnFeLR4JvlSzB48) |
| AntiGravity 基本功 | [播放清單](https://www.youtube.com/playlist?list=PLkNQUBglz8Eyh1xcFYFBOcOEBu1WGoB0p) |
| OpenCode 基本功 | [播放清單](https://www.youtube.com/playlist?list=PLkNQUBglz8EzKWIuDCtS5AmfSFzuwFv-H) |
| 全部播放清單 | [頻道](https://www.youtube.com/@sensebar/playlists) |

**本簡報的單元架構、實作題情境與評分規準，是為高中教師研習所做的教學設計**；
其中的觀念與方法來自上述影片，強烈建議搭配原片學習，本簡報無法取代原始教學內容。

## 使用與授權

本簡報為**校內教師研習之教學設計**，公開分享供教育工作者參考。

⚠️ **本專案目前未附加任何開放授權（如 CC）。** 原因是：簡報所整理的觀念來自第三方 YouTube 影片，
該影片並非以開放授權釋出，因此本專案無權代為授權他人改作或再散布。

- ✅ 歡迎教育工作者**觀看、於自身教學現場參考使用**
- ✅ 歡迎分享本頁網址
- ❌ 請勿逕行改作後再散布，或用於商業用途

若你想在自己的研習中使用或改編，請先與 [三師爸 Sense Bar](https://www.youtube.com/@sensebar) 聯繫確認，
並可另行與本專案作者討論。
