# MKDocs サンプルリポジトリ

MkDocs でドキュメントを作成する時のサンプルリポジトリ

## ローカル実行環境構築

以下のコマンドで仮想環境を作成してください

```bash
uv sync
```

## ローカルで動かしたい

以下のコマンドでローカルサーバを起動した後、ブラウザで [http://127.0.0.1:8000](http://127.0.0.1:8000)にアクセスしてください

```bash
uv run mkdocs serve
```

ブラウザでアクセスしたイメージ
![screenshot 7.png](images/launch.png)

## HTMLをビルドしたい

以下のコマンドでビルドできます。
ビルド成果物はプロジェクト直下に `site/` として生成されます

```bash
uv run mkdocs build
```

## 参考リンク
- [MKDocs](https://www.mkdocs.org/)
- [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/reference/)
