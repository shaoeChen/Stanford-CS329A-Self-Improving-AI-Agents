# Stanford CS329A：Self-Improving AI Agents 互動教學網頁

把 Stanford CS329A〈Self-Improving AI Agents〉的課堂內容，整理成可離線開啟的繁體中文互動教材。

> **本專案的教學網頁由 Claude Opus 5.5 建立。**
> 網頁的內容編排、文字撰寫、圖表與互動元件，皆由 Claude Opus 5.5 依據課程字幕與投影片截圖產生。內容可能有疏漏或錯誤，請以原始課程影片為準。

## 線上瀏覽

<https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/>

## 課程連結

- 課程影片（第 1 講）：<https://www.youtube.com/watch?v=6YnLB0XbTnI>
- 課程網站：<https://cs329a.stanford.edu>

## 課程說明

CS329A 是 Stanford 於 2025 年秋季開設的課程，由 Aakanksha Chowdhery 與 Azalia Mirhoseini 授課，主題是能夠自我改進的 AI Agent。課程涵蓋 test-time scaling、self-improvement 技術（verifier、feedback、RL、search）、tool use、retrieval 與 memory、planning 與 multi-step reasoning、Agent 評估，以及 multimodal agent 與機器人。

第 1 講是課程總覽，用約 70 分鐘走過 LLM 近五年的發展主線：

1. **把模型做大**：算力、資料量、參數量三軸放大，loss 可預測地下降（scaling law）
2. **讓模型好用**：instruction tuning 與 RLHF 造就 ChatGPT
3. **推論時多想**：不改參數，靠 repeated sampling 與 reasoning model 換取更好的答案
4. **真正完成任務**：能自己規劃、行動、驗證並修正錯誤的 Agent

## 教學網頁

| 講次 | 線上瀏覽 | 原始檔 |
|---|---|---|
| 第 1 講：課程總覽 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/part-1-course-overview.html) | [part-1-course-overview.html](part-1-course-overview.html) |

### 使用方式

點選上表的「開啟網頁」即可在瀏覽器中閱讀。也可以下載 HTML 檔後直接開啟，不需要安裝任何東西，也不需要啟動伺服器。網頁為單一檔案，樣式與程式全部內嵌，離線可用；只有各章節的時間戳連結需要網路，點擊後會跳到 YouTube 影片的對應位置。

### 網頁內容

- 依概念重組的 10 個章節，每章附「一句話重點」與原始影片的時間戳連結
- 互動示範：prompt 類型切換、訓練管線逐步檢視、repeated sampling 模擬器、workflow 組件流程圖
- 課堂問答精選、一頁總結、8 題自我檢測、可搜尋的術語表
- 支援深色模式與手機寬度

### 閱讀時請留意

- 內容整理自課程字幕；字幕中辨識有誤的專有名詞已依課堂投影片校正。
- 部分圖表數值是依論文圖表整理的近似值。
- 標示為「示意」的圖表與模擬用於說明概念，不代表實驗數據。

## 聲明

本專案為個人學習用途的非官方整理，與 Stanford University 及授課講者無關。課程內容的著作權屬於原作者。
