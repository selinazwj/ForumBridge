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
## 🎯 Forum Sections
- 📝 问卷互助 — 学术问卷、科研互助
- 💼 Intern专区 — 实习、内推、招聘经验
- 🎉 校内活动 — 讲座、社团、展览、比赛
- 🧠 专业答疑 — 课程学习与学术讨论
