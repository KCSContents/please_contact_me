# これはWordPress用のプラグインです。

これはcsvファイルに登録した部署・所在地・連絡先等の情報が、投稿の末尾に自動的に追加されるシンプルなプラグインです。

## 「write.csv」の登録

まずcsvファイル「write.csv」に、投稿の末尾に掲載したい情報を登録します。
「write.csv」ファイルの１行目にサンプルデータが入っていますので、同様に１行目から入力してください。

* １列目はキーとなりますので重複しない英数字データを登録してください。  
* １列目のキーに日本語は使えません。  
* ２列目は部署名です。
* ３列目は部署名に設定するリンク先のURLです。部署のページがある場合に設定してください。
* ４列目は施設名です。本庁・支所等名称を設定してください。  
* ５列目は郵便番号・住所です。部署のある階数等もあるとわかりやすいかと思います。郵便番号の先頭に〒マークを表示したい場合はその位置に「〒」を入力してください。  
* ６列目は電話番号です。電話番号の先頭に「TEL」と表示したい場合はその位置にTEL」を入力してください。  
* ７列目はファックス番号です。ファックス番号の先頭に「FAX」と表示したい場合はその位置に「FAX」を入力してください。  

更新しましたら上書き保存してください。

## WordPressの投稿「タグ」の設定

WordPressの投稿では「タグ」を使います。
その投稿の末尾に掲載したい部署のキーを、タグに入力し保存します。
それで投稿での設定は完了です。

※最後に「更新」ボタンをクリックしてください。  
タグの「追加」だけでは更新されません。

## 内容の表示

「write.csv」ファイルに設定した情報は、WordPressダッシュボードの「設定」の「問い合わせ先一覧」から確認することができます。

## 注意

※固定ページには対応しておりません。
