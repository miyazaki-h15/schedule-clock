24時間スケジュール時計（PWA）

【公開手順：GitHub Pages】
1. github.com で新しいリポジトリを作成（Public）
2. 「Add file → Upload files」でこのフォルダの中身5ファイルをアップロード
   （index.html / manifest.webmanifest / sw.js / icon-192.png / icon-512.png）
3. Settings → Pages → Branch を「main」「/(root)」にして Save
4. 数分後に表示されるURL（https://ユーザー名.github.io/リポジトリ名/）を開く

【インストール】
- PCのChrome：アドレスバー右端のインストールアイコン、またはメニュー →「キャスト、保存、共有」→「ページをアプリとしてインストール」
- Android：Chromeメニュー →「ホーム画面に追加」
- iPhone：Safariの共有ボタン →「ホーム画面に追加」

【更新するとき】
ファイルを差し替え、sw.js の CACHE の番号（v1 → v2）を上げる

【データ】
予定は端末ごとのブラウザ内に保存される（PCとスマホの間では同期されない）
