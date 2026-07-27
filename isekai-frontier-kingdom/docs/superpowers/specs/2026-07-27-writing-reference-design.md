# 執筆用設定資料の分割設計

## 目的

『異世界工場長、荒野に国を造る』の総合執筆指示書を、執筆・校正時に必要な資料だけ参照できるMarkdownファイル群へ分割する。

## 構成

- `docs/setting/world.md`：世界、地域、資源、技術、魔法
- `docs/setting/structure.md`：テーマ、文体、制作規則、禁止事項
- `docs/setting/plot.md`：全10話の目的、問題、生産成果、伏線
- `docs/setting/characters.md`：人物の特徴、技能、目標、関係性
- `docs/setting/continuity.md`：話数ごとの時系列、人口、設備、技術、伏線
- `docs/episodes/NN/outline.md`：各話の場面構成用
- `docs/episodes/NN/draft.md`：各話本文用
- `docs/episodes/NN/review.md`：校正記録用

## 運用

各話は一話ずつ、`plot.md` と `continuity.md` を確認して設計する。本文完成後に `continuity.md` を更新し、次話の執筆へ進む。設定にない新要素は本文から分離して候補として記録する。

## 完了条件

共通資料5ファイルと、全10話分の作業雛形が存在し、各ファイルの責務が重複しないこと。
