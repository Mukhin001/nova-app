# 🚀 Nova App — Full Stack Application

**Nova App** — это учебный full-stack проект, построенный на **Next.js (App Router)**, **Node.js**, и **MongoDB (Atlas)**.  
Он демонстрирует современный стек и архитектуру клиент–серверного приложения с аутентификацией, хранением данных и управлением состоянием через **Redux Toolkit**.

---

## 🧩 Технологический стек

### **Frontend**

- ⚛️ [Next.js 14 (App Router)](https://nextjs.org/docs/app)
- 🎨 TypeScript, Tailwind CSS
- 🧠 Redux Toolkit + RTK Query
- 🔐 JWT авторизация
- ⚙️ Axios для запросов к API

### **Backend**

- 🧱 Node.js + Express (или чистый HTTP)
- 🗄️ MongoDB (Atlas) + Mongoose
- 🔑 Авторизация (JWT, bcrypt)
- 🌐 REST API с CRUD-операциями

---

## 🧠 Архитектура проекта

nova-app/
│
├── backend/ # Серверная часть (Node.js + MongoDB)
│ ├── app.ts # Точка входа сервера
│ ├── lib/mongodb.ts # Подключение к базе данных
│ ├── models/ # Mongoose-схемы
│ ├── routes/ # Маршруты API
│ └── ...
│
├── frontend/ # Клиентская часть (Next.js)
│ ├── app/ # App Router
│ ├── components/ # Компоненты UI
│ ├── store/ # Redux Toolkit
│ ├── api/ # RTK Query endpoints
│ └── ...
│
├── .gitignore
├── README.md
└── package.json

---

## ⚙️ Запуск проекта локально

### 1️⃣ Клонирование репозитория

```bash
git clone https://github.com/Mukhin001/nova-app.git
cd nova-app

Установка зависимостей
cd frontend && npm install
cd ../backend && npm install

```

Запуск

# Терминал 1

cd backend && npm run dev

# Терминал 2

cd frontend && npm run dev

Функциональность пользователей
Возможность Анонимный пользователь Авторизованный пользователь
Просмотр контента ✅ ✅
Комментирование ❌ ✅
Публикация постов ❌ ✅
Лайки / Избранное ❌ ✅
Редактирование профиля ❌ ✅

📦 В планах
🔥 Добавить систему уведомлений
📱 Адаптировать под мобильные устройства
🧩 Ввести SSR-кеширование и оптимизацию SEO
🌙 Тёмная тема

Автор
Игорь Мухин
📧 Mukhin001@github.io
🗓️ Проект создан для практики и демонстрации Full Stack навыков.
