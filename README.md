# ForumBridge MVP
Forum version of Survey Bridge

A minimal campus forum built with Flask + SQLite.

## Features
- User register / login
- Create and view posts
- Simple HTML frontend (Tailwind CSS)
- Lightweight database (SQLite)

## Our Structure
```
campus-forum/
├── app.py                 # Flask 主程序
├── templates/             # 前端页面（HTML模板）
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── post.html
│   └── create_post.html
├── static/                # CSS / JS 文件
│   ├── style.css
├── forum.db               # SQLite 数据库
└── requirements.txt       # Python依赖
```
