# LIFE＋MONEY PWA v0.1

## iPhoneだけで公開する手順
1. GitHubアカウントを無料作成。
2. 新しいPublicリポジトリ `life-money` を作成。
3. ZIPを解凍し、フォルダ内の **5ファイル**（index.html、manifest.webmanifest、sw.js、icon-192.png、icon-512.png）をリポジトリ直下にアップロード。README.mdは任意。
4. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。
5. 数分後に表示される `https://ユーザー名.github.io/life-money/` にSafariでアクセス。
6. Safariの共有ボタン →「ホーム画面に追加」→「追加」。

GitHubの無料Pages公開は**インターネット上に公開**されます。個人の家計データはGitHubにアップロードせず、iPhone側のlocalStorageに保存されます。金融情報のバックアップJSONやCSVはリポジトリにアップロードしないでください。

## 機能
- 収入・支出の登録
- 当月の収支、月間予算
- 月別履歴と削除
- 支出カテゴリ分析・貯蓄率
- JSONバックアップ/復元、CSV書き出し
- PWAホーム画面追加、初回読み込み後オフライン利用

## 制約
- 自動銀行連携、クラウド同期、ログイン機能は未実装。
- データは各ブラウザ/端末ごとに保存されます。Safariデータの消去、プライベートブラウズ等で失われる可能性があります。
- 本バージョンは一般向けの試作です。公開前にiPhone実機で動作、バックアップ/復元、アクセスビリティ等を確認してください。
- GitHub Pagesでのホストは無料枠の規約・制限に従います。
