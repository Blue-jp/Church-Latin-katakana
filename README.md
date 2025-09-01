# Latin → Church Latin Katakana Converter (single HTML)
教会ラテン語を日本語のカタカナで**ライブ変換**するHTMLツールです。
- 出力はカタカナのみ
- オフライン動作（外部依存なし）
- 6000字超は自動停止、約140msデバウンス
- iOSはQuick Lookでは動かないため**Safariで開く**を推奨

## 使い方
`index.html` をブラウザで開くか、公開URL（GitHub Pages等）にアクセスしてください。
[公開URLをここに記載]

## ライセンス
**Prosperity Public License 3.0.0**  
- 非商用：無料（使用・改変・共有可）  
- 商用：**30日間のトライアル**のみ可。継続は**有償ライセンスが必要**  
- 連絡先：このリポジトリの **Issues** からご連絡ください  
詳細は `LICENSE` を参照。SPDX: `Prosperity-3.0.0`

## 開発メモ
- 変換ロジックは**アクセント除去→合字分解→音価規則→カタカナ合成**の順で適用。例外表を先にマッチ。:contentReference[oaicite:6]{index=6}
