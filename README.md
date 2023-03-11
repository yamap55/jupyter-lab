# ts-jupyter

[![hadolint](https://github.com/yamap55/ts-jupyter/actions/workflows/hadolint.yml/badge.svg?branch=main)](https://github.com/yamap55/ts-jupyter/actions/workflows/hadolint.yml)

本リポジトリはTypeScriptの実行環境を加えたJupyter Notebookを起動するためのDockerImageを管理します。

## 使用方法

1. 起動
  - `docker run -p 8888:8888 ghcr.io/yamap55/ts-jupyter:latest`
2. ブラウザでアクセス
  - `http://localhost:8888`
