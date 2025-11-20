# AI Scheduler System
Django + Celery + Redis Background Scheduler

## 🎯 Company Requirements Met
- ✅ Background scheduler (works even when server not running)
- ✅ Uses Celery + Redis as specified
- ✅ Automatic content generation at scheduled times
- ✅ REST APIs for schedule management
- ✅ Database logging for executions

## 🚀 Quick Setup

1. Install dependencies:**
```bash
pip install -r requirements.txt
2. Start services (4 terminals):

# Terminal 1 - Redis
cd Redis-x64-3.2.100
redis-server.exe

# Terminal 2 - Celery Worker  
cd ai_scheduler
venv\Scripts\activate
celery -A ai_scheduler worker --pool=solo

# Terminal 3 - Celery Beat
celery -A ai_scheduler beat

# Terminal 4 - Django Server
python manage.py runserver
3. Test API:

Open: http://127.0.0.1:8000/api/schedules/

Create schedule with future time

System automatically executes at scheduled time

Project Structure:
ai_scheduler/
├── schedules/          # Main app (models, views, tasks)
├── ai_scheduler/      # Project config (settings, celery)
└── requirements.txt   # Dependencies
