# Rss-Backend

NestJS service for RSS Foods. The first version exposes a health endpoint for deployment checks.

```sh
npm ci
npm run build
npm start
```

Set `PORT` to override the default port `3000`. `GET /health` returns `{"status":"ok"}`.
