# ポケチャン対戦ノート

ポケモンチャンピオンズ用の対戦記録＆AIフィードバックアプリです。

---

## セットアップ手順（コピペだけでOK）

### ステップ1：GitHubアカウントを作る
1. https://github.com を開く
2. 「Sign up」からアカウントを作成（無料）

---

### ステップ2：リポジトリを作る
1. GitHubにログインして右上の「+」→「New repository」
2. Repository name に `pokemon-battle` と入力
3. 「Public」を選択
4. 「Create repository」をクリック

---

### ステップ3：ファイルをアップロード
1. 「uploading an existing file」をクリック
2. `index.html` と `manifest.json` の2ファイルをドラッグ＆ドロップ
3. 下の「Commit changes」をクリック

---

### ステップ4：GitHub Pagesで公開
1. リポジトリの「Settings」タブをクリック
2. 左メニューの「Pages」をクリック
3. Source を「Deploy from a branch」に設定
4. Branch を「main」、フォルダを「/(root)」にして「Save」
5. 数分待つと `https://あなたのユーザー名.github.io/pokemon-battle/` でアクセスできる

---

### ステップ5：Androidのホーム画面に追加
1. AndroidのChromeでそのURLを開く
2. 右上の「︙（メニュー）」→「ホーム画面に追加」
3. 「追加」をタップ
4. ホーム画面にアイコンが追加されてアプリっぽく使える！

---

### ステップ6：APIキーを設定
1. アプリを開いて上部の入力欄にAnthropicのAPIキーを入力
2. 「保存」をタップ
3. APIキーはこちらで取得：https://console.anthropic.com

---

## 使い方
1. **パーティタブ**：最初に6匹を持ち物・性格・技まで登録
2. **対戦中タブ**：選出3匹をタップで選んで、ターンごとに技・相手を記録
3. **フィードバックタブ**：「AIにフィードバックしてもらう」でコメントが届く

データはスマホ内に保存されるので、オフラインでも記録できます（フィードバックはネット必要）。
