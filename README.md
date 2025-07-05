# Open WebUI テスト環境

## 概要
Open WebUIのローカルテスト環境です。

## セットアップ
```bash
# リポジトリをクローン
git clone <your-repo-url>
cd openwebui-test

# ブランチを作成
git checkout -b feature/openwebui-setup

# Docker Composeで起動
docker-compose up -d
```

## ブランチ戦略
- `main`: 安定版
- `develop`: 開発版
- `feature/*`: 機能開発用
- `test/*`: テスト用
