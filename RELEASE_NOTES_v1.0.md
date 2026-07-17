# MythicRPG-TW v1.0 Release Notes

發行日期：2026-07-18

## 完成狀態

- 完成模組／語言命名空間：63
- 已驗證 JAR：62
- 官方英文總 key：18,081
- 完成率：100.00%
- 最終驗證：PASS

## 修正內容

- 所有實際 JAR 的 `en_us.json` 均有對應 `zh_tw.json`。
- Key 數量完全一致，缺少與多餘 key 均為 0。
- 修正 Placeholder、JSON、Duplicate Key 與英文殘留。
- 統一 Minecraft 官方術語與專案 Glossary。
- 完成 Tooltip、Advancement、Death Message、Config GUI、Curios、Patchouli、JEI、Lore、首領、武器與建築名稱 QA。

## 特殊修正

- JourneyMap：同步目前 JAR 的新版語言 key，統一「Waypoint → 路徑點」。
- ProjectE／Project Expansion：保留並明確標示 MK 升級階級。
- Spartan Weaponry：修正格式佔位符與箭袋階級名稱。
- Twilight Forest：統一首領、生怪磚與相關 GUI／字幕名稱。
- Waystones：重寫新增設定文字，修正跨維度傳送、清單識別字與路徑點術語。
- Structure Gel：修正建築工具、資料處理器與動態生怪磚 GUI 的錯譯。

## 已知限制

- 41 個玩家可見英文候選位於 3 個 JAR 的非語言檔 JSON；本專案不修改 JAR 或功能資料，詳見 `LOCALIZATION_REMAINING.md`。
- 模組名稱、作者與歌曲名稱、網址、指令、搜尋別名、技術縮寫及 Resource Location 依規範保留原文。

## 封版驗證

- 無語言檔範圍內英文殘留。
- 無 Placeholder 問題。
- 無 JSON 問題。
- 無 Duplicate Key。
- 無 Prompt 污染。
- 封版 Commit 完成後確認 Git Working Tree Clean。
