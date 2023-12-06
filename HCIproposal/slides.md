---
theme: seriph
background: https://source.unsplash.com/collection/94734566/1920x1080
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Welcome to Slidev
---

# HCI Final Project Proposal
我們都是資科三 蔡至倫 梁栯睿


---
transition: fade-out
---

# The problem to be solved

## 手勢辨識螢幕滾動裝置
#

#### 提案想法
- 🛠 **操作效率及直覺性** - 操作方法符合人類習慣與直覺
- 🛠 **簡單的手勢推移及拖曳功能** - 功能簡單好上手 適合各年齡層使用
- 🛠 **實現無接觸控制裝置** - 減少病菌傳播及維護成本

#

#### 應用面
- 🛠 **個人用途** - 觀看電子書時不須接觸實體裝置即可控制
- 🛠 **商業用途** - 速食店點餐機 觀光景點電子看板
- 🛠 **降低成本** - 減少人力及維護成本
- 🛠 **增加人工作業安全性** - 高危險設備可由非接觸控制


<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: default
---

# Device to be utilized

- 🛠 **測試裝置** - 電腦或手機前鏡頭
- 🛠 **未來應用裝置** - 在各種設備上安裝鏡頭或影像辨識裝置

---
transition: slide-up

level: 2
---

# Methodology Techniques used to tackle the problem

### 主要以Python套件與模型為主

|     |     |
| --- | --- |
| <kbd>OpenCV 鏡頭模組</kbd> | 將數據結果進行分析處理，不同手部動作與擺動幅度可得到不同程度的控制回饋 |
| <kbd>測試並調整參數</kbd> | 將功能做到最滑順、最人性化 |
| <kbd>CNN卷積神經網路模型</kbd> | 使用機器學習分析並記錄每一位使用者的手勢使用習慣，給予最適合的控制回饋 |
| <kbd>網頁版的測試UI</kbd> | 提供展示用，讓使用者得知測得知手勢習慣 |


---
layout: image-right
---

# AIP/Libraries

|     |     |
| --- | --- |
| <kbd>PyAutoGUI</kbd> | 自動化工具，協助模擬使用者的鍵盤和滑鼠操作，實現手勢引導的螢幕滾動 |
| <kbd>mediapipe</kbd> | 機器學習套件，以收集和分析使用者手勢的關鍵特徵，提高辨識的精準度 |
| <kbd>OpenCV</kbd> | 進行數據處理、轉換和影像處理 |

---

# Expected outcome

- 🛠 **完整的UI介面** - 供使用者直覺性的控制
- 🛠 **符合所有使用者習慣** - 運用機器學習訓練及分析 為所有使用者客製化參數
- 🛠 **精準及多功能的偵測邏輯** - 精準辨識手勢的意義及尺度 給用戶最好的使用者體驗

---
layout: image-right
---

# 感謝聆聽