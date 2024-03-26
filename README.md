### 概要
- PostgresSQL実行用Dockerコンテナ
- version 15.1-alpine

### 利用手順
```
# ディレクトリ移動
cd docker-postgres

# 起動
docker-compose up -d

# 停止、削除
docker-compose down --rmi all --volumes --remove-orphans
```