# 広島映写 ホームページ

広島映写（代表 本田雅也）の公式サイト。HTMLだけで作った静的サイト。

## ファイル
- `index.html` … トップページ（全セクションがこの1ファイル。CSS・JSも中に入っている）
- `privacy.html` … プライバシーポリシー・利用規約・特定商取引法・免責事項
- `robots.txt` / `sitemap.xml` … 検索エンジン用（公開URLは https://hiroshimaeisya.github.io/ （GitHub Pages、mainブランチの直下を公開））

## よくある更新
- 料金：`index.html` の `id="price"` セクション
- 実績カード追加：`id="cards"` の中の `<article class="card" data-c="video|photo|sns">` をコピーして書き換え
- 実績動画追加：`class="videos"` の中の `<figure>` をコピー
- ギャラリー写真：ページ下部 `<script>` の `row1` / `row2` 配列
- Googleアナリティクス：`<head>` のコメント内 `G-XXXXXXXXXX` を測定IDに変えてコメントを外す

## 注意
- 写真・動画は今はSTUDIO（storage.googleapis.com）とGenspark（genspark.ai）に置いてあるものを読み込んでいる。STUDIOのプロジェクト「広島映写」や Genspark のファイルを消すと表示されなくなるので、元データを `assets/` に入れて差し替えるのが望ましい。
- 文章は本人の確認なしに事実（経歴・実績・料金）を足さない。
- 問い合わせフォームはサーバーなしで動くよう、メールアプリを開く方式（mailto）。
