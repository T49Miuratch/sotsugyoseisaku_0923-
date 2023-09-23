# sotsugyoseisaku_0923-

GitHub Codespacesで環境構築してLaravelベースで開発を行う

# ターミナルコマンド一覧

ls  #カレントディレクトリにあるファイルやディレクトリを表示する
ls -l  #ファイルやディレクトリの詳細も同時に表示する
ls -a  #隠しファイルも含めファイルやディレクトリを全て表示する
ls −la  #隠しファイルを含む全てのファイルやディレクトリの詳細を表示する

cd test.html  # testテストというファイルに移動する
cd ~/  #ホームディレクトリに移動する
cd ..  #一つ上の階層のファイルに移動する

pwd  #カレントディレクトリのパスを表示する

touch test.html  #test.htmlという中身が空のファイルを作る

mkdir test #testというファイルを作る

mv test.html tmp/  #test.htmlというファイルを相対パスでtmp/に移動する
mv test.html test2.html  #test.htmlというファイルをtest2.htmlに名前変更する

cp test.html tmp/  #test.htmlを相対パスでtmp/というディレクトリの中にコピーする
cp test.html test2.html  #test.htmlをtest2.htmlという名前でコピーする
cp −r dir /tmp/  #dirというディレクトリとその中身を絶対パスで/tmp/にそっくりコピーする

rm test.html  #test.htmlを削除する
rm -r test  #testというディレクトリとその中身を削除する
rm -f test  #testというファイルを警告なしで削除する
rm -rf test  #testというディレクトリとその中身を警告なしで削除する

open .  #現在のターミナルのディレクトリFinderで開く
open ~/  #ホームディレトリをFinderで開く

source ~/.bash_profile  #ホームディレクトリにある.bash_profileに書き込んだ設定を読み込み有効にする
source .bash_profile  #カレントディレクトリにある.bash_profile設定を読み込み有効にする

history  #これまで実行してきたコマンドの履歴を表示する
history -c  #これまで実行してきたコマンドの履歴を消去する

# Laravel関連参考URL

CodespaceでLaravelの参考URL

GitHub Codespaces で Laravel を使った開発
https://pages.michinobu.jp/t/20221203codespaceslaravel.html

開発環境を持たないという選択。GitHub CodespacesとLaravelとVSCodeと。
https://qiita.com/miracle-FJSW/items/e2dbe53b7a59101b23fe

エラー対応
laravel起動時に「failed to open stream: No such file or directory in ***/artisan on line 18」エラー
https://www.thirtyfive.info/entry/2018/06/06/rarabel%E8%B5%B7%E5%8B%95%E6%99%82%E3%81%AB%E3%80%8Cfailed_to_open_stream%3A_No_such_file_or_directory_in_%2A%2A%2A/artisan_on_line_18%E3%80%8D%E3%82%A8%E3%83%A9%E3%83%BC

Github はユーザーにデータベースを提供しません
https://laracasts.com/discuss/channels/laravel/how-to-access-phpmyadmin-in-live-github-codespace

【拡張機能メモ】

【2023年最新版】VSCodeをLaravel超特化型にする 最高の拡張機能10選まとめ。
https://yurupro.cloud/2132/

Laravel開発で導入してほしいVSCode拡張機能 (WSLリモート接続)
https://zenn.dev/na9/articles/23c18a0d2d8ee2

Laravel開発でおすすめのVSCode拡張機能5選
https://feeld-uni.com/?p=1926

【Laravel】開発に便利なVSCodeの設定や拡張機能
https://yutaro-blog.net/2021/08/11/laravel-vscode/