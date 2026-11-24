# Tile Commands / マスに、命令がある。

ゲーム考古学研究室 #02 から生まれた、4×4のソロパズル。1930年代のオランダのボードゲーム Schada（シャダ）の「現在いるマスが駒の移動方法を決める」という発想を取り出した独立作品です。原作の復刻ではありません。

## 遊び方

- 駒を1個動かして星のゴールを目指します。
- 現在のマスの記号が移動方法を決めます。横1マス、縦1マス、斜め1マス、縦横2マス跳びの4種類です。
- 全30問。最短手数への挑戦、ヒント、やり直し、自己ベストの保存に対応しています。

## 実行・公開

`index.html` をブラウザで開くだけで遊べます。外部ライブラリやビルド工程は不要です。進行記録はブラウザの localStorage に保存します。

Cloudflare Pages: GitHubリポジトリを接続し、production branch を `main`、framework preset を None、build command を空欄、build output directory を `.` に設定します。

## Reference

- [Schada — Abstract Games](https://www.abstractgames.org/schada.html)
- [Schada Online](https://schada.org/)

Created by madowaku with AI assistance.
