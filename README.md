# MiniApp Todo

[English](#english) | [Русский](#русский)

---

## English

### 📌 Overview
MiniApp Todo is a small **pet project** for practicing full-stack development.  
It includes a Python backend (FastAPI/Flask) and a React + Vite frontend deployed with Firebase.

### ✨ Features
- Create and delete tasks  
- View task list in a clean UI  
- Data persistence via Firebase  
- Test integration with Instagram Reels Parser bot  

### 🛠 Tech Stack
- **Backend:** Python 3.11+, FastAPI / Flask  
- **Frontend:** React + Vite  
- **Database / Hosting:** Firebase, NocoDB (for experiments)  

### 🚀 Installation & Run

#### Backend

cd todoapp
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
python main.py

Backend runs at: http://127.0.0.1:8000

#### Frontend
cd todofront
npm install
npm run dev

Frontend runs at: http://localhost:5173

#### 🌍 Deployment
Frontend: Firebase Hosting →
npm run build
firebase deploy
Backend: Render, Railway, Heroku, or any Python-compatible hosting.

This project was built as a personal pet project for learning and experimentation.

---

## Русский

### 📌 Обзор
MiniApp Todo — небольшой pet-проект для практики full-stack разработки.
Состоит из Python-бэкенда (FastAPI/Flask) и фронтенда на Vite/React с хостингом на Firebase.

### ✨ Функционал
Добавление и удаление задач
Просмотр списка задач
Сохранение данных через Firebase
Тестовый бот-интерфейс для Instagram Reels Parser

### 🛠 Технологии
Бэкенд: Python 3.11+, FastAPI / Flask
Фронтенд: React + Vite
База данных / Хостинг: Firebase, NocoDB (для экспериментов)

### 🚀 Установка и запуск

#### Бэкенд
cd todoapp
python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows
pip install -r requirements.txt
python main.py
Бэкенд поднимается на: http://127.0.0.1:8000

#### Фронтенд
cd todofront
npm install
npm run dev
Фронтенд доступен на: http://localhost:5173

#### 🌍 Деплой
Фронтенд: Firebase Hosting →
npm run build
firebase deploy
Бэкенд: Render, Railway, Heroku или любой Python-хостинг.

Проект написан как учебный pet-project для практики.
