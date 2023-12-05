# nix-python-template

## 主要パッケージバージョン

| package | ver  |
| ------- | ---- |
| python  | 3.10 |
| CUDA    | 11.8 |
| cuDNN   | 8.9  |

## その他

- 外部プロジェクトを管理する場合は、`pyproject.toml`が無い場合は`venv`を使う
- 新しくプロジェクトを作成する場合は、`poetry`で管理した方が良い
- 外部プロジェクトはこのプロジェクトにサブモジュールで追加する

## 参考

- [Git submodule の基礎](https://qiita.com/sotarok/items/0d525e568a6088f6f6bb)
