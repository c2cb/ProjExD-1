# 第1回
## 消えたアルファベットを探すゲーム(ex01/alphabet.py)
### 遊び方
* コマンドラインでquiz.pyを実行すると,標準出力に問題が表示される
* 標準入力から答えを入れる（全三問）
* 正解なら正解と答える
* 不正解ならやり直し
### プログラム内解説
* list_difference関数:表示文字と対象文字の差分を求める関数
* lfa関数:問題文の出題と回答の正解をチェックし結果を出力する
### やり残し
* 繰り返しの最大回数が設定されていない