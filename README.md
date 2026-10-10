# バズれ45

45秒で何いいね稼げるか競う、片手タップのスマホ向けゲーム。ビルド不要の静的サイト(HTML 1ファイル)です。

## 遊び方
- 💗 タップでいいね(コンボで倍率アップ) / ⭐ 高得点
- 🔥 さわると炎上(時間が減る) / 🚀 取るとバズタイム(得点2倍)
- ランクは C → B → A → S。プレイするとXPが貯まり、Lv1〜10で難易度が上がります
- 中断しても、レベル・XP・ベスト・プレイ途中の状態はブラウザに保存され「つづきから」で再開できます

## ローカルで動かす
`index.html` をブラウザで開くだけで動きます。

## デプロイ(Vercel)
1. このリポジトリを Vercel の "Add New → Project" から Import
2. Framework Preset は `Other`、Build Command と Output Directory は空のまま Deploy

## 構成
| ファイル | 役割 |
|---|---|
| `index.html` | ゲーム本体(HTML/CSS/JS) |
| `manifest.webmanifest` | ホーム画面に追加するための設定 |
| `icons/` | アプリアイコン |
| `og-image.png` | SNSでシェアしたときのプレビュー画像 |
| `vercel.json` | Vercel の設定 |
