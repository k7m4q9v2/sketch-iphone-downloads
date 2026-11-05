# Sketch for iPhone

既存のSketch Retroid 0.2.16を土台にした、iPhone縦画面の音楽制作アプリです。既存のGUI・配色・フォント・音声処理を引き継いでいます。

## 入れる

1. 初回のみ、[SideStore公式手順](https://docs.sidestore.io/docs/installation/prerequisites)に沿ってPCとUSBでSideStoreを入れます。各自のApple Accountを使います。
2. SideStoreのSources（ソース）→「＋」に、下の配信URLを貼り付けます。
3. Sketchを選んでインストールします。追加した配信元から今後のアプリ更新も受け取れます。

配信URL（コピー用）:

https://github.com/k7m4q9v2/sketch-iphone-downloads/releases/latest/download/source.json

[IPAを直接ダウンロード](https://github.com/k7m4q9v2/sketch-iphone-downloads/releases/latest/download/Sketch-iPhone.ipa) → iPhoneのファイルに保存 → SideStoreのMy Apps「＋」から選ぶ方法も使えます。

## 署名を更新する

Sketchの「iPhone設定」に手順があります。ショートカットアプリでSideStoreの「Refresh All Apps / Refresh Apps」を追加し、「Sketchの署名更新」という名前で保存してください。ホーム画面にも追加します。LocalDevVPNなど公式手順の接続を有効にして実行し、SideStoreの残日数で成功を確認します。

毎日1回の時刻オートメーションで、このショートカットを実行すると更新を忘れにくくなります。最初に手動実行してください。iOSによる制限や接続切れで失敗する場合もあります。SideStoreのショートカット利用はiOS 17以降を推奨します。

無料Apple Accountでは通常7日ごとの再署名が必要で、初回セットアップを省くことはできません。期限切れ後はホーム画面の更新ショートカットかSideStoreを使います。AltStore Classicでも導入可能ですが、更新時にはAltServerを起動したPCへの接続が必要です。

## 曲を作る

「＋」でプロジェクト → チャンネル追加 → チャンネルのノート欄をタップしてピアノロールで入力。Playlist／Mixerは既存の切り替えボタンを使います。曲は自動保存。ソングのWAVはExportから「ファイルに保存」や共有できます。音楽制作はオフラインで動きます。

配布版にはGeneralUser GSを同梱。追加SF2や音声はアプリ内で取り込めます。フォルダはアプリ内コピーで、元フォルダとは自動同期しません。

## 音源とライセンス

[GeneralUser GSライセンス](https://github.com/k7m4q9v2/sketch-iphone-downloads/releases/latest/download/GeneralUser-LICENSE.txt) / [エンジンのライセンス](https://github.com/k7m4q9v2/sketch-iphone-downloads/releases/latest/download/THIRD_PARTY_NOTICES.txt)

この配布版には元Retroid個人版の追加ゲーム音源15バンクを含めません。画面や編集機能は同じです。

対応: iPhone / iOS 16以降。App Store版ではありません。バックグラウンドや通話で再生が止まった場合は、戻って再生してください。