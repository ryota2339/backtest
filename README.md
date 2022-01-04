# 株式トレードのバックテスト

株式トレードのバックテストができるアプリケーションです。
テクニカル指標を設定し、そのテクニカル指標を用いて、買う条件と売る条件の二つを入力します。
その条件で売買を行った時のトレード結果を出力します。

# 使いかた
１．左のサイドバーから証券コードを入力し、データを取得する
ex) 「7203.T」
<br><br>
２．売買ルールに用いるテクニカル指標を選択し、パラメータを設定し、候補に追加する。
選択されたインジケータは表に追加される

３. 複数のテクニカル指標を選択し終えたら、ルール設定へ。

４．ルール設定ページで売買ルールを設定する。
・数値入力のチェックボックスをクリックすると、一つのテクニカル指標と数値に対して、条件を設定できる。
ex) RSIが60以上のとき
・数値入力のチェックなしのとき、二つのテクニカル指標に対して条件を設定できる。
ex) 陽線のとき ⇒ close > open, S_m

