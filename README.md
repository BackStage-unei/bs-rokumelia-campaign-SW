# bs-rokumelia-campaign

鹿鳴りあ（RokumeLia）の企画のユーザー向け紹介ページ。GitHub Pages で配信する。

回ごとにサブフォルダを分ける。ルートは最新の回へ転送するだけ。

- `silverweek/` … 通話キャンペーン（2026年シルバーウィーク）
- 次の回は `newyear/` のように足す。同じ季節を翌年もやる場合は `silverweek-2027/`

**公開 URL**: https://backstage-unei.github.io/bs-rokumelia-campaign/silverweek/

- **直接編集しない。** 源泉は Obsidian 側の `10_イベント/2026-09/鹿鳴りあSW通話CP/鹿鳴りあ通話キャンペーン_LP.html`
- 更新手順: 源泉を直す → `ソース/test_lp.py` を通す → このリポジトリの `silverweek/index.html` に上書きコピー → commit & push
- 自己完結1ファイル。外部リソース・JavaScript なし

## 公開前に外すもの

- `<meta name="robots" content="noindex,nofollow">`（日付が未確定の間の保険）
- 日付のプレースホルダ 4 か所（応募開始・応募締切・結果連絡日・通話期間）
