AUTOCAT JP v25 - 公開用パッケージ

このZIPは元ファイルをWebホスティング向けに調整したものです。

変更点:
- PORT 環境変数に対応
- gunicorn を requirements.txt に追加
- Render 用 render.yaml を追加
- Procfile を追加

注意:
- 実運用には .env.example にある各種秘密情報の設定が必要です。
- Discord OAuth を使う場合、公開後のURLに合わせて DISCORD_REDIRECT_URI を設定してください。
- DBを永続化したい場合は、利用するホスティング側で永続ディスク/DB設定が必要です。
