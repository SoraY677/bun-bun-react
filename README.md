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
# パッケージインストール(初回のみ)
bun install
# 実行
bun run dev
```

### 停止・再起動

```bash
# コンテナ停止
docker-compose down
# コンテナ再起動
docker-compose restart
```