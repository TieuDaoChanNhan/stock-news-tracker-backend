# Installation and Running Instructions

## 1. Install dependencies

```

pip install -r requirements.txt

```

## 2. Restart API server

```

rm local_news_tracker.db
python -m uvicorn main:app --reload --port 8000

```

## 5. Run project

```

python app/scheduler_script.py

```

**Demo Link**: https://soft-cassata-869f95.netlify.app/
