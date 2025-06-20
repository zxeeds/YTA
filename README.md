youtube-automation/
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
├── config/
│   ├── __init__.py
│   ├── settings.py
│   └── credentials.json
├── src/
│   ├── __init__.py
│   ├── auth/
│   │   ├── __init__.py
│   │   └── youtube_auth.py
│   ├── upload/
│   │   ├── __init__.py
│   │   ├── video_uploader.py
│   │   └── scheduler.py
│   ├── analytics/
│   │   ├── __init__.py
│   │   ├── data_collector.py
│   │   └── report_generator.py
│   ├── comments/
│   │   ├── __init__.py
│   │   ├── comment_manager.py
│   │   └── auto_reply.py
│   ├── seo/
│   │   ├── __init__.py
│   │   ├── keyword_research.py
│   │   └── content_optimizer.py
│   ├── social/
│   │   ├── __init__.py
│   │   ├── facebook_integration.py
│   │   ├── twitter_integration.py
│   │   └── instagram_integration.py
│   └── utils/
│       ├── __init__.py
│       ├── database.py
│       ├── email_sender.py
│       └── logger.py
├── data/
│   ├── videos/
│   ├── thumbnails/
│   ├── templates/
│   └── exports/
├── logs/
├── tests/
│   ├── __init__.py
│   ├── test_upload.py
│   ├── test_analytics.py
│   └── test_comments.py
├── scripts/
│   ├── setup.py
│   ├── daily_tasks.py
│   └── backup.py
├── web_dashboard/
│   ├── app.py
│   ├── templates/
│   │   ├── index.html
│   │   ├── analytics.html
│   │   └── upload.html
│   └── static/
│       ├── css/
│       ├── js/
│       └── images/
└── main.py
