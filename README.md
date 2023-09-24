# ロボホンが「ボクと歌お」の曲をおすすめしてくれるアプリ

ロボホンのアプリ「[ボクと歌お](https://robohon.com/apps/app33.php)」の有償オプションで歌える曲は 2023 年 9 月 27 日現在で 291 曲もあります。何が歌えるのか覚えてないですし，背中の画面で一覧を見るものつらいですし，[ボクと歌お](https://robohon.com/apps/app33.php)のページにある[『ボクと歌お』楽曲一覧](https://robohon.com/apps/app33.php#main-box)を毎回見るのも大変ですよね。

そこで，[ロブリック](https://robohon.com/apps/robrick.php)を使ってロボホンがおすすめの曲を教えてくれるアプリを作りました。

## 特徴

[![「ボクと歌お」おすすめアプリ実行動画](https://img.youtube.com/vi/YV8MQU0aMfk/0.jpg)](https://youtu.be/YV8MQU0aMfk)

「カラオケを教えて」と言うと，「ボクと歌お」で歌える曲の中からランダムに 1 曲おすすめしてくれます。一度おすすめした曲は全部おすすめするまで再度おすすめすることはありません。

このアプリでおすすめの曲を聞いた後，「カラオケして」もしくは「カラオケを起動して」と言うと「ボクと歌お」アプリを起動できます。ロボホンが教えてくれた歌手名や曲名を言うと，その歌を歌ってくれます。

## インストール方法

- [ZIPファイル](https://github.com/3110/robrick-karaoke-curator/archive/v1.0.1.zip)をダウンロードします。
- ダウンロードした ZIP ファイルを適当なフォルダに展開します。
- ロボホンでロブリックアプリを起動します。  
  <a href="https://gyazo.com/4c6059c6ee7deace2185d194e2587e22"><img src="https://i.gyazo.com/4c6059c6ee7deace2185d194e2587e22.png" alt="ロブリックアプリアイコン" width="180"/></a>
- ロボホンの画面に表示されている文字列を Web ブラウザのアドレスバーに入力してください（詳細は[ロブリック利用マニュアルの10ページ](https://robohon.com/apps/robrick/robrick-manual_v1-3-0.pdf#page=10)を参照）  
  <a href="https://gyazo.com/03ab2d8be37ce7ec4e92773205f10020"><img src="https://i.gyazo.com/03ab2d8be37ce7ec4e92773205f10020.png" alt="ロブリック起動画面" width="180"/></a>  
  <a href="https://gyazo.com/2c4fa167263e0cc0f90c2911ffe87f22"><img src="https://i.gyazo.com/2c4fa167263e0cc0f90c2911ffe87f22.png" alt="Google Chromeでの例" width="800"/></a>
- Web ブラウザにロブリックの画面が表示されます。  
  <a href="https://gyazo.com/826959a2535c9b253b6dd647bc01217a"><img src="https://i.gyazo.com/826959a2535c9b253b6dd647bc01217a.png" alt="ロブリック画面" width="800"/></a>
- 画面左下にある「設定」ボタンを押し，「保存先」が「デバイス」になっていることを確認します。「保存先」はプログラムを読み込むときの読み込み先としても使われます。設定画面を閉じるときは右上の「×」を押します。  
  <a href="https://gyazo.com/0f9dbbe00a22f19ba0c1bcd32933efa0"><img src="https://i.gyazo.com/0f9dbbe00a22f19ba0c1bcd32933efa0.png" alt="設定画面" width="800"/></a>
- 画面下にある「読み込み」ボタンを押して，ZIP ファイルを展開したフォルダにある `karaoke-curator.xml` を選択し，「開く」ボタンを押します。  
  <a href="https://gyazo.com/4b870265c8c1ef874a5b56a1e80393f7"><img src="https://i.gyazo.com/4b870265c8c1ef874a5b56a1e80393f7.png" alt="ファイルの選択" width="800"/></a>
- アプリが読み込まれます。  
  <a href="https://gyazo.com/9a894c21f89b8138ea920a558810d8f5"><img src="https://i.gyazo.com/9a894c21f89b8138ea920a558810d8f5.png" alt="アプリ読み込み完了" width="800"/></a>
- 「ロボホンに送信」ボタンを押してロボホンに送信します。「ロボホンに保存する時のファイル名をいれてください」というダイアログが表示され，読み込んだXMLファイル名の`karaoke-curator`が入っています。特に変更する必要がなければそのままで「OK」ボタンを押します。  
  <a href="https://gyazo.com/7e7bb5d9f58b4c292d1d2359a59ae3be"><img src="https://i.gyazo.com/7e7bb5d9f58b4c292d1d2359a59ae3be.png" alt="ロボホンに送信" width="800"/></a>
- 「待ち受けで、『カラオケヲオシエテ』と呼びけた時に起動するプログラムを追加します。」というダイアログが表示されるので「OK」ボタンを押します。  
  <a href="https://gyazo.com/ff33f6fb4eb57a761899886f3797d606"><img src="https://i.gyazo.com/ff33f6fb4eb57a761899886f3797d606.png" alt="Image from Gyazo" width="2048"/></a>
- 「保存しました。待ち受け起動を登録しました。」と表示されたら「OK」ボタンを押します。  
  <a href="https://gyazo.com/154eb0c6e447c4ac58d9eedaefc02382"><img src="https://i.gyazo.com/154eb0c6e447c4ac58d9eedaefc02382.png" alt="保存完了" width="800"/></a>

## 実行方法

- ロボホンが待ち受け状態（ロブリックやロブリック実行を含め，他のアプリが起動していない状態）なのを確認し，ロボホンに向かって「カラオケを教えて」と話しかけます。
- ロブリック実行アプリが起動し，「ボクと歌お」おすすめアプリが自動的に実行します。

待ち受け起動（指定したキーワードをロボホンが聞いたら，その言葉に紐付いたロブリックのアプリを起動する）については，[ロブリック利用マニュアルの 45 ページ](https://robohon.com/apps/robrick/robrick-manual_v1-3-0.pdf#page=45)を参照してください。

## 曲の追加方法

「ボクと歌お」の曲は奇数月に10曲ずつ追加されていきます（[「ボクと歌お」曲名一覧](https://docs.google.com/spreadsheets/d/1EWo2EAvWR-jEza-YIrW-5ecb81rpQwllYQypLS6Kngs/edit?usp=sharing)（Google Spreadsheet）を参照）。

以下は私が曲を追加するときの作業メモです。ロブリックで`karaoke-curator.xml`を開いて以下のように修正します。

- 変数「バージョン」のパッチバージョンを1上げます。
- 変数「曲一覧対象」にバージョンアップする日付を「YYYYMMDD」（年月日）の形式でリストの一番最後に追加します。
- 関数「曲一覧-雛形」をコピーして関数「曲一覧-YYYYMMDD」を作成し，曲データを埋めます。
- 関数「曲一覧の初期化」で「他にもしも「日付」＝"YYYYMMDD"」を追加し，関数「曲一覧に追加」の引数に関数呼び出し「曲一覧-YYYYMMDD」ブロックを入れます。

これで曲の追加が完了するので，変数「デバッグ」を`true`に変更して実行し，追加分の発話を確認します。

発話がおかしい場合，アーティスト名の場合は関数「アーティスト発話辞書の初期化」で連想配列「アーティスト発話辞書」にキー「アーティスト名」，値「正しい発話文字列」を，曲名の場合は関数「曲名発話辞書の初期化」で連想配列「曲名発話辞書」にキー「曲名」，値「正しい発話文字列」を追加します。

発話の確認が終了したら変数「デバッグ」を`false`に変更するのを忘れないようにしてください。
