# Yorimatch Form

`Yorimatch` 向けのシンプルな問い合わせフォームです。静的ホスティング前提で、送信ボタンを押すと `yorimatch.support@gmail.com` 宛てのメール作成画面を開きます。

## 構成

- `index.html`: 画面・スタイル・送信スクリプトを含む単一ファイル
- `docs/contact-form-spec.md`: 現行フォーム仕様

## ローカル確認

```bash
python3 -m http.server 8000
```

その後、`http://localhost:8000` を開いてください。
