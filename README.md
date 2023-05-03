# PHP_SEKAINOTODO

## 使うもの 
　PHP,DB（MySQLかfirestore）,firebase


## 機能
〇TODOアプリ<br>
・世界中の人が投稿できるTODO。<br>
・カード形式で表示。<br>
・タグ機能を使い、みんながどのようなタスクをためこんでいるかを表示。<br>
・国籍をtodoカードに追加。

## 手順
〇その他
　・.gitignoreにファイル名指定したら、addcompushされないかも。

〇Node.js?npm?らへんインストールする。<br>　
　変なエラー出たらまずバージョン確認。<br>

〇reactの環境構築<br>

　[npx create-react-app .]<br>
　フォルダ名大文字使えない。<br>

〇firebase環境構築<br>
・サイトでfirebaseの登録やプロジェクト作成を行う。<br>
　そしたらhostingってとこ押して、画面に表示されるコマンドを打つ。<br>

　[npm install firebase]<br>　
　[npm install -g firebase-tools]<br>
　[firebase login]<br>

　・ログイン出来たら、firebaseのサイトに行き、firestore（DB）の設定を行う。<br>
　　場所とか決めるやつ。<br>
  [firebase init]

  ・ここたくさんエラー出る。firebaseのアカウント系とか、バージョン系が多い。<br>
  ・今回は、[firebase login --reauth]で解決した。<br>
  　ログインはできていたが、数か月ぶりに使うなら再ログインして的な？？<br>
  ・firebase initの後に、hostingとかfirestore指定することもできる。<br>

　[firebase deploy]
　
　・これで変更がweb上に反映される。

〇
