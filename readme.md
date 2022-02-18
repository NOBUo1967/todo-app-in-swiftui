## 大まかな機能
+ Todo作成機能 
+ Todo一覧機能
+ Todo詳細表示
+ Todo詳細から編集機能
+ Todo更新・削除機能 -> 一覧からも削除する？

自分しか使わない前提のためログイン・ログアウトは現時点では必要なし。</br>
一覧から削除するのであればSwiftUIのListのスワイプ機能の実装の方法を調べる必要あり。</br>
一覧画面からは各Todoの詳細画面に遷移できる。</br>
一覧画面からTodoを追加できる。</br>
一覧画面では完了したTodoと未完了のTodoを別で確認できるようにする。

## データ構造
Todoは一覧で表示する = Listで表示
+ ID
+ title(String)
+ detail(Stging)
+ isDone(Bool)
+ createAt(Date)
+ updateAT(Date)

createAtとupdateAtはDate型でいいか考える必要がある。

## 画面設計
レイアウトは下記記事を参考にさせていただいた。</br>
https://zenn.dev/t0_inoue/books/fe8902398314fa7f2545/viewer/c9f5e4
