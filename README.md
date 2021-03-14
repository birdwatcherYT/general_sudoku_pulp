# 一般化した数独の問題作成&ソルバー by pulp
- 数独はニコリの登録商標です
- ナンプレとも呼ばれます
- pulpを使って整数計画問題を解く練習のために作ったnotebookです
- [Qiita](https://qiita.com/birdwatcher/items/d5c2a88c733ca71ae91e)で解説してます

## ソルバー
- 与えられた問題の解を全て出力する

## 問題作成
- 方法1: 空の盤面にランダムに数字を入れていき, ソルバーで解が一意かどうか判定しながらやる
- 方法2: 埋まった盤面からランダムに数字を抜いていき, ソルバーで解が一意かどうか判定しながらやる
    - 埋まった盤面を作る必要がある

## 一般化
- 普通の数独(9x9盤面)の正方形ブロック(3x3)をm x nにした
- 盤面のサイズは mn x mn

Prologバージョン
- https://github.com/birdwatcherYT/SudokuProlog/blob/master/sudoku.pro
