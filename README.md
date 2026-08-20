# koyomi-calendarV2-LP

日本の吉日・凶日カレンダー「暦しるべ」のランディングページ（LP）です。

- 本体サービス: https://koyomi-calendar.ohtaka-84d.workers.dev/

## 構成

静的サイト（ビルド不要）です。

- `index.html` — LP本体（CSS/JSはインライン）
- `assets/logo-mark.png` — ブランドロゴ
- `assets/icon.svg` — ファビコン

## プレビュー

```bash
npx serve .
# または index.html をブラウザで直接開く
```

## デプロイ

静的ホスティング（Cloudflare Pages / Workers Assets、GitHub Pages など）にそのまま配置できます。
