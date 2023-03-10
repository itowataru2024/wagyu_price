# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリ
  - ネット上に配置して複数人で共有するリポジトリ。
- ローカルリポジトリ
  - 個人が使用するために、PC上に配置するリポジトリ
## プッシュとマージの違いは何でしょうか？
- プッシュ
  - ローカルの変更内容をリモートにアップする。
- マージ
  - 別のブランチの作業内容をブランチに取り込む。
## コミットとプッシュの違い
- コミット
  - 変更した内容をローカルに保存する
- プッシュ
  - 変更した内容をリモートにアップする
## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 変更内容と変更した理由を分かりやすくシンプルに記述する
## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージするフロー
  - masterブランチから作業用のブランチを切り、変更内容をmasterブランチにマージし、リモートのmasterブランチにプッシュする。
- プルリクエストでマージするフロー
  - 行うことはローカルでマージするフローと変わりないが、ローカルではなくリモートリポジトリ上でマージする。リモート上でマージした内容を、ローカルのmasterブランチは知らないので反映させるにはpullというコマンドを使用する。
## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 先にマージされた変更内容を取り込む、後にマージしようとしている変更内容を取り込む、どちらの変更内容も取り込む。

