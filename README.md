# まちだ桜花火 2027 特設サイト

公式サイトとは別の、花火イベント専用のスタティックサイトです（HTML / CSS / JS のみ、ビルド不要）。

## 構成
- index.html … ページ本体（CSS・JSも同梱）
- assets/img/ … WebP画像（ヒーロー、PC背景、各セクション、ギャラリー）と OGP画像（og-image.jpg, 1200×630）

## 公開前に編集する箇所（すべて index.html 内）
1. `<head>` 冒頭のコメント：公開URLが決まったら canonical / og:url / og:image を追加
2. `<script>` 内の `EVENT` オブジェクト：日時・会場・主催などの開催情報
3. `EVENT.officialUrl`：WARMBLUE公式サイトのURL。入れると「WARMBLUEとは」に公式サイトへのリンクが表示されます（空のままなら非表示）

## 未掲載（情報未提供のため創作していません）
入場料、打ち上げ数、雨天対応、駐車場、出店店舗、協賛企業、問い合わせ先、SNS
