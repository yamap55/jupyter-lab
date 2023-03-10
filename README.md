# jupyter-lab

本リポジトリはTypeScriptの実行環境を加えたJupyter Notebookを起動するためのDockerImageを管理します。

## 使用方法

```
docker build -t ghcr.io/yamap55/jupyter-lab:v0.0.0 .
docker run --rm -it -p 8888:8888 ghcr.io/yamap55/jupyter-lab:v0.0.0
```
