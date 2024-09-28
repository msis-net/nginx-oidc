# nginx-oidc

[https://qiita.com/ydclab_P002/items/b49ed23ca7b2532fcce2](https://qiita.com/ydclab_P002/items/b49ed23ca7b2532fcce2)

```bash
.
├── backend/ # WEB サーバ
│ └── nginx.conf
├── docker-compose.yml
├── keycloak/ # 認可サーバ
│ └── import/
│ └── realm-develop.json # Keycloak の Realm エクスポートファイル
└── proxy/ # リバースプロキシ
├── conf.d/
│ └── app.conf
├── nginx.conf
└── njs/ # njs の JavaScript コード
├── jwt.js
└── oidc.js
```

### GettingStart

1. docker エンジンを起動
2. docker-compose up --build -d
