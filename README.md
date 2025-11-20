
# 🤖 AI Scheduler System

**Automated Content Generation System with Django, Celery & Redis**

## 🚀 Overview
A professional scheduling system that automatically generates content at predefined times using background workers. Built for the Python Developer role technical assessment.

## ✨ Features
- ✅ **Automated Scheduling** - Content generation at scheduled times
- ✅ **Background Processing** - Celery workers with Redis broker
- ✅ **RESTful APIs** - Complete CRUD operations for schedules
- ✅ **Database Logging** - Track all executions with status
- ✅ **Production Ready** - Scalable and reliable architecture

## 🛠 Tech Stack
- **Backend:** Django, Django REST Framework
- **Task Queue:** Celery, Redis
- **Database:** SQLite (can be upgraded to PostgreSQL)
- **Architecture:** Microservices-ready

## 📋 Requirements Met
✔ Background scheduler independent of server state  
✔ Celery + Redis as required by company  
✔ Automatic content generation at scheduled times  
✔ REST APIs for schedule management  
✔ Database storage for schedules and execution logs  
✔ Error handling and status tracking  

## 🎯 Company Requirements Fulfilled
*"Even server is not running it should generate content on the pre scheduled time"* - ✅ Achieved with Celery background workers

*"You can use celery or redis services for this task"* - ✅ Both technologies implemented

## 🏗 Project Structure
