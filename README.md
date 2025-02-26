## FastAPI Todo App

### フォルダ構成
```
.
├── README.md
├── app
│   ├── __init__.py
│   ├── models
│   ├── routers
│   └── tests
├── requirements.txt
├── venv
├── Dockerfile
└── docker-compose.yml
```

### ブランチ戦略
git flow の簡略版を採用
- main（開発環境）
- release（本番環境）
- feature/fix（mainから派生）
- hotfix（releaseから派生、releaseとmainにマージ）
