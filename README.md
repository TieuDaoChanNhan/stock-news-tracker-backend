# Hướng dẫn cài đặt và chạy dự án

## 1. Cài đặt dependencies

```

pip install -r requirements.txt

```

## 2. Restart API server

```

rm local_news_tracker.db
python -m uvicorn main:app --reload --port 8000

```

## 5. Chạy project

```

python app/scheduler_script.py

```
