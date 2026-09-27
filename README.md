# site

わくてかスタディ研究所（[wakutekastudy.com](https://wakutekastudy.com/)）のサイトです。ゲームのように夢中になれる学び方を探求し、長く遊ばれてきた定番ゲームの楽しさの仕組みを研究しています。GitHub Pages で公開しています。

## 構成

| 場所 | 内容 |
| --- | --- |
| `index.html` | ホーム(案内ページ) |
| `classic-games/index.html` | 定番ゲームの一覧(案内ページ) |
| `classic-games/<スラッグ>.html` | 定番ゲーム。1ゲーム＝1ファイルで、CSS・JavaScriptも同じファイルに入っています |
| `learning-games/index.html` | 学習ゲーム(準備中) |
| `assets/` | マスコット画像・ファビコン |
| `_dev/` | 開発用の資料(公開ページには含まれません) |

## ゲームを作る・改造する

`_dev/game-page-guide.md`(ルール)と `_dev/game-template.html`(ひな型)を参照してください。

## 手元での確認

ゲームのファイルは、ダブルクリックでブラウザに開くだけで遊べます(外部通信なし)。サイト全体を確認するときは、リポジトリのフォルダで簡単なWebサーバーを起動します(例:`python -m http.server`)。

## ライセンス

`classic-games/` と `learning-games/`(`learning-games/packs/` を除く)のファイルは MIT-0 です。それ以外(ホーム、画像など)は対象外です。詳しくは `LICENSE` を参照してください。
