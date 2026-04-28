# Trạm Phin — Demo Specialty Coffee Roastery Website

> **AI HP営業販売プロジェクト**のデモサイト（第2号）。
> ベトナム現地企業向け営業時に「こういうサイトを作れます」と提示するための架空店舗。

ホーチミン市3区の路地裏にあるという設定の、Lâm Đồng直送のスペシャルティコーヒー焙煎所「Trạm Phin」のバイリンガル（VN/EN）対応サイト。

## Live

- **本番**: https://tram-phin-demo.vercel.app
- GitHub: https://github.com/poposuke18/tram-phin-demo

## ベトナム現地のデザイン文化への配慮

- **Zalo フローティングボタン**（ベトナム独自のメッセンジャー文化）
- **電話番号をヘッダーで常時表示**（call-firstな顧客行動）
- **Today's batch 表示**（specialty coffee文化の信頼シグナル）
- **顧客テストモニアル**（ベトナム式トラスト構築）
- **価格を全アイテムに明示**（曖昧さを避ける文化）
- **写真密度高め**（情報密度のVN好み）
- **Vietnamese diacritics タイポを最優先**（Lora + Be Vietnam Pro）

## Stack

- **Astro 6** (静的サイトジェネレーター)
- **Tailwind CSS v4** (スタイリング)
- **TypeScript strict**
- **Vercel** デプロイ

## Pages (7)

| Path | Locale | Page |
|---|---|---|
| `/` | vi | Home |
| `/menu` | vi | Coffees + Drinks + Workshops |
| `/visit` | vi | Address, Hours, Map |
| `/en/`, `/en/menu`, `/en/visit` | en | All |
| `/404` | — | Not found |

## Design System

- **Paper** `#f8f4ed` / **Bean** `#2a1810` / **Jade** `#4f6f52` / **Phin** `#b89968` / **Lacquer** `#a23b2c`
- **Lora** (serif headlines, VN diacritic-safe)
- **Be Vietnam Pro** (body, native VN font)
- **JetBrains Mono** (tabular numerals, dates, prices)

## Local Development

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static output to dist/
npm run preview
```

## Sister project

姉妹デモ: [Sakura Phở](https://sakura-pho-demo.vercel.app/) — 日系ベトナム料理レストラン、JP/VI/ENトライリンガル
