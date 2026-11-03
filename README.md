# 行動記録アプリ（本物のPWA版）

1日のすべての行動時間をカテゴリ別に記録するPWAです。
データは端末の localStorage に自動保存され、オフラインでも動作します。

## 使い方
1. 下の「公開方法」で作ったURLを iPhone の Safari で開く
2. 共有ボタン →「ホーム画面に追加」
3. ホーム画面のアイコンから全画面アプリとして起動

## 公開方法（どれか1つ、全部無料）

### A. GitHub Pages（一番おすすめ：URLがずっと使える）
1. GitHubで新しいリポジトリを作る（例：koudou-app、Public）
2. このフォルダのファイルを全部アップロードする
3. リポジトリの Settings → Pages → Branch を main / (root) にして Save
4. 数分後に https://ユーザー名.github.io/koudou-app/ が公開される

### B. Netlify
1. app.netlify.com にログイン
2. Sites の画面にこのフォルダをドラッグ＆ドロップするだけ
3. 表示されたURLを使う

### C. Cloudflare Pages
1. Cloudflareにログイン → Workers & Pages → Create → Pages → Upload assets
2. このフォルダをアップロードするとURLが発行される

## 注意
- データは「そのブラウザ／ホーム画面アプリの中」に保存されます。Safariタブで記録したデータと、ホーム画面アプリのデータは別扱いになることがあるので、最初からホーム画面アプリで使うのがおすすめ。
- 機種変更や初期化に備えて、ときどきアプリ内の「JSON書き出し」でバックアップを取ってください。
