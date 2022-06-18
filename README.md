# YOLOv4

## 動作環境
MacOS Big Sur Version 11.6

## 仮想環境構築
パッケージのインストール
```
poetry install
```
.envファイルの作成
```
cp .env.sample .env
```

## 実行(楽天レシピからデータ取得)
- 初回実行
```
make rakuten_recipe
```
