# Samsung Reminders Clone - Full Stack CRUD App

Task management application with category filtering, complete/incomplete marking, and importance starring.

## 🚀 Features
- ✅ Add, edit, delete tasks
- ✅ Mark tasks complete (with strikethrough)
- ✅ Star tasks as important
- ✅ Filter by 6 categories (Today, Scheduled, Important, Place, No Alert, Completed)
- ✅ Real-time category counts
- ✅ Clean dark UI

## 🛠️ Tech Stack
**Frontend:** HTML5, CSS3, Vanilla JavaScript  
**Backend:** Node.js, Express.js  
**Storage:** In-memory REST API

## 📦 Installation

### Backend
```bash
cd backend
npm install
node server.js
```

### Frontend
Open `frontend/index.html` in browser

## 📡 API Endpoints
- `GET /api/tasks` - Get all tasks
- `POST /api/tasks` - Create task
- `PUT /api/tasks/:id` - Update task
- `DELETE /api/tasks/:id` - Delete task
