# プロジェクトのルール

## Pythonパッケージ

- Pythonパッケージはuvで管理する
- pythonパッケージのコマンドの実行は uv run で実施する
- 必要なパッケージはpyproject.tomlに追加する

## Sphinx

- ドキュメントのテーマには`furo`を使用する
- ドキュメントのビルドは `uv run sphinx-build` で実行する

## Git

- add, commit, pushは一括で行う

## GitHub

- issueを立てたり、確認する場合は git remote -v コマンドを使う
- issueの内容は変更せず、コメントを追加する
- チェックボックスはGFM記法を使う