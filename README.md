# bunをブンブンしてみようのコーナー

## 開発方法

### 必須環境

- Docker (docker-compose)

### コマンド

#### 起動

```bash
# コンテナ起動
docker-compose up -d
# コンテナログイン
docker-compose exec bun bash
# 実行
bun run index.ts
```

### 停止・再起動

```bash
# コンテナ再起動
docker-compose restart
# コンテナ停止
docker-compose down
```