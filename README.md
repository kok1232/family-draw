# 分派典禮｜家族抽籤儀式

[繁體中文](#繁體中文) | [English](#english)

---

## 繁體中文

### 簡介

專為 EMBA 家族活動設計的抽籤儀式系統。有別於傳統「一次公布全部名單」的做法，本系統採用類似分類儀式的**逐人揭曉**流程：每位學員被單獨唱名、羅盤指針轉動後停在所屬家族，讓抽籤本身成為一場有儀式感的活動橋段。同時，公平分配的核心邏輯完全保留——每一屆的人數都會盡量平均分配到每個家族。

### 線上使用

👉 <https://kok1232.github.io/family-draw/>

### 主要功能

- **逐人唱名分類**：不是一次公布結果，而是一位一位揭曉，羅盤指針動畫決定所屬家族
- **家族與屆別皆可自由設定**：家族數量、名稱、顏色不限制數量；屆別可新增多筆，各自貼上名單（一行一位）
- **同屆內公平分配**：每一屆的人數會自動平均分給每個家族，多出的名額隨機分配給不同家族，不會每次都是同一家族多一位
- **多屆連續進行**：一屆分類完會直接接續下一屆，不需中途返回設定、名單也不會重置
- **家族即時名單看板**：右側即時顯示各家族目前收到的成員，格狀排列一次看到全部家族，姓名前的色點依「第幾屆」上色，方便一眼確認各家族是否平均
- **簡易音效**：唱名分類時有滴答音效與確認音（可一鍵靜音）
- **匯出 Excel（.xlsx）**：內含「總覽」分頁（各家族在各屆的人數統計）與每個家族各自一個分頁
- **重新分配防呆**：已有結果時，設定頁按鈕會變成警示色的「重新分配」並跳出確認視窗，避免手滑清空
- **返回名單畫面**：分派完成後回設定頁修改家族名稱／顏色，可透過「返回名單畫面」查看套用新名稱的結果，不會重新抽籤
- 桌面／投影優先版面設計，支援空白鍵操作（適合搭配簡報遙控器）

### 使用方式

1. 在「家族設定」新增家族、命名並選擇顏色（至少需要 2 個家族）
2. 在「屆別名單」貼上每一屆的學員名單（一行一位），可新增多個屆別
3. 按下「開始分派」，依屆別順序逐一進行唱名分類儀式
4. 全部屆別完成後，可在畫面上直接匯出 Excel，或回設定頁調整家族名稱後用「返回名單畫面」查看最終結果

### 隱私說明

本應用程式不收集任何個人資料，所有名單資料僅在您的裝置（瀏覽器）上處理，不會上傳至任何伺服器。完全免費，無廣告。

---

## English

### Introduction

An interactive sorting-ceremony system designed for EMBA Family events. Instead of revealing the entire assignment list at once, this tool calls each member one by one — a compass needle spins and settles on their assigned family, turning the draw itself into a ceremonial moment. The fair-distribution logic is fully preserved: within each cohort, members are distributed as evenly as possible across families.

### Live Demo

👉 <https://kok1232.github.io/family-draw/>

### Features

- **One-by-one reveal ceremony**: members are called individually; a spinning compass needle decides their family in real time
- **Fully configurable families and cohorts**: no fixed number of families — add, rename, and recolor freely; add as many cohorts as needed, each with its own pasted name list
- **Fair distribution within each cohort**: members are split as evenly as possible across families each round; any remainder is randomly assigned so the same family doesn't always get the extra seat
- **Continuous multi-cohort flow**: finishing one cohort seamlessly continues into the next — no need to return to setup, and the roster never resets mid-activity
- **Live family roster board**: a grid of cards on the right shows every family's current members at a glance, with small colored dots marking which cohort each name belongs to
- **Lightweight sound effects**: ticking sounds during the spin and a confirmation chime on reveal, with a one-tap mute toggle
- **Excel (.xlsx) export**: includes an overview sheet (headcount per family per cohort) plus one sheet per family
- **Safeguard against accidental resets**: once results exist, the setup button turns into a warning-colored "Reassign" action with a confirmation prompt
- **View results without redrawing**: after finishing, you can tweak family names/colors in setup and use "View Results" to see the updated names applied to the existing results — no re-shuffling involved
- Desktop/projector-first layout, with spacebar support for remote clickers

### How to Use

1. In **Family Settings**, add families, name them, and pick colors (at least 2 required)
2. In **Cohort Lists**, paste each cohort's member list (one name per line); add as many cohorts as needed
3. Click **Start Assignment** to run the ceremony cohort by cohort, in order
4. Once all cohorts are done, export to Excel directly from the same screen, or return to setup to rename families and use **View Results** to see the final list with the updated names

### Privacy

This application does not collect any personal data. All list data is processed on your device only and is never uploaded to any server. Completely free, no ads.

### Tech Stack

- Pure HTML / CSS / JavaScript (single-file, no backend)
- Web Audio API for real-time synthesized sound effects
- SheetJS (client-side) for multi-sheet Excel export
- GitHub Pages hosting
