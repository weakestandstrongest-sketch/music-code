# コードホイール

五度圏のコードホイール。タップでコードを鳴らし、構成音（例：C → C・E・G / ド・ミ・ソ）を表示します。
`index.html` と `samples/piano/` だけで動くので、ブラウザで開くだけで使えます（iPhone / Android / Windows / Mac）。

## 機能
- 音色はグランドピアノ（実録サンプル＋ホール残響）。音源が読み込めない環境では簡易シンセで鳴ります
- 五度圏ホイール（メジャー / マイナー / ディミニッシュ）。キー内のコードは色付き、キー外はグレーでも鳴らせます
- キー変更（長調・短調）、セブンス切替、ダイアトニックコードの一覧
- すべてのコード：12 ルート × 19 種類（m, 7, M7, m7♭5, dim7, sus4, add9, 9 …）と構成音
- 構成音は音楽理論どおりの綴り＋ドレミ＋度数（R, 3, 5…）、鍵盤表示
- コード進行の作成・再生（BPM、ループ、王道進行などの定番進行）

## URL で公開する（GitHub Pages）
1. リポジトリの **Settings → Pages** を開く
2. **Source: Deploy from a branch**、ブランチとフォルダ `/ (root)` を選んで Save
3. 数分後に `https://<ユーザー名>.github.io/music-code/` で開けます

## クレジット
ピアノ音源：Salamander Grand Piano V2（Alexander Holm, CC BY 3.0）。詳細は `samples/piano/LICENSE.txt`。
