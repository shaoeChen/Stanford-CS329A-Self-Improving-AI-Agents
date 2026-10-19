# Stanford CS329A：Self-Improving AI Agents 互動教學網頁

把 Stanford CS329A〈Self-Improving AI Agents〉的課堂內容，整理成可離線開啟的繁體中文互動教材。

> **本專案的教學網頁由 Claude Opus 5.5 建立。**
> 網頁的內容編排、文字撰寫、圖表與互動元件，皆由 Claude Opus 5.5 依據課程字幕與投影片截圖產生。內容可能有疏漏或錯誤，請以原始課程影片為準。

## 線上瀏覽

<https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/>

## 課程連結

- 課程影片（第 1 講）：<https://www.youtube.com/watch?v=6YnLB0XbTnI>
- 課程影片（第 2 講）：<https://www.youtube.com/watch?v=-Ggc37xLj_Y>
- 課程影片（第 3 講）：<https://www.youtube.com/watch?v=p7TdPUcPoik>
- 課程影片（第 4 講）：<https://www.youtube.com/watch?v=Lxh9RF5S-K0>
- 課程影片（第 5 講）：<https://www.youtube.com/watch?v=Ml_fp9XkB8Y>
- 課程影片（第 6 講）：<https://www.youtube.com/watch?v=yVnmHSAy3ck>
- 課程影片（第 7 講）：<https://www.youtube.com/watch?v=Uni9dqyuuDM>
- 課程影片（第 8 講）：<https://www.youtube.com/watch?v=8JAqLnTaZu4>
- 課程影片（第 9 講）：<https://www.youtube.com/watch?v=AyO6wyu4DEg>
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
| 第 2 講：Test-Time Compute Scaling | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%202%20-%20Test-Time%20Compute%20Scaling.html) | [Part 2 - Test-Time Compute Scaling.html](Part%202%20-%20Test-Time%20Compute%20Scaling.html) |
| 第 3 講：穩健的驗證（Robust Verification） | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%203%20-%20Robust%20Verification.html) | [Part 3 - Robust Verification.html](Part%203%20-%20Robust%20Verification.html) |
| 第 4 講：從回饋中學習：工具、程式碼與 AI 回饋 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%204%20-%20Learning%20from%20Feedback%20with%20Tools-Code.html) | [Part 4 - Learning from Feedback with Tools-Code.html](Part%204%20-%20Learning%20from%20Feedback%20with%20Tools-Code.html) |
| 第 5 講：Planning 與多步推理 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%205%20-%20Planning%20and%20Multi-Step%20Reasoning.html) | [Part 5 - Planning and Multi-Step Reasoning.html](Part%205%20-%20Planning%20and%20Multi-Step%20Reasoning.html) |
| 第 6 講：Train-time Scaling：把 RL 放大 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%206%20-%20Train%20Time%20Scaling-Scaling%20RL.html) | [Part 6 - Train Time Scaling-Scaling RL.html](Part%206%20-%20Train%20Time%20Scaling-Scaling%20RL.html) |
| 第 7 講：用搜尋改進模型：AlphaCode 與 Deep Research Agent | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%207%20-%20Self-Improvement%20and%20Deep%20Research%20Agents.html) | [Part 7 - Self-Improvement and Deep Research Agents.html](Part%207%20-%20Self-Improvement%20and%20Deep%20Research%20Agents.html) |
| 第 8 講：Agentic Evaluation 與長時程任務 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%208%20-%20Agentic%20Evaluations%20and%20Long%20Horizon%20Tasks.html) | [Part 8 - Agentic Evaluations and Long Horizon Tasks.html](Part%208%20-%20Agentic%20Evaluations%20and%20Long%20Horizon%20Tasks.html) |
| 第 9 講：自我改進 Agent 的未來研究方向 | [開啟網頁](https://shaoechen.github.io/Stanford-CS329A-Self-Improving-AI-Agents/Part%209%20-%20Future%20Research%20Areas.html) | [Part 9 - Future Research Areas.html](Part%209%20-%20Future%20Research%20Areas.html) |

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
