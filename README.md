# 環境構築

- 以下の.envファイルを作成

```
DATABASE_URL="postgresql://nestjsuser:nestjspass@localhost:5432/todoapp?schema=public"

JWT_SECRET="7d62037d4e74a30a61a9c470ab8ed6afcc4149b24c44e5bf8856409b99e0135d"
```

- docker compose upで起動

- 以下のコマンドで起動

```
export $(grep -v '^#' .env | xargs)
npm start
```
