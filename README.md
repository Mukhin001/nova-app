🚀 Nova App — Full Stack Application

Nova App — это персонализированная платформа новостей и погоды, позволяющая пользователю получать контент по выбранным городам и категориям.

🧩 Основной функционал
Регистрация и авторизация пользователей (JWT + bcrypt)
Выбор городов и категорий новостей
Персонализированная новостная лента
Погода по выбранным городам
Аналитика популярных городов и категорий
Профиль пользователя с настройками

🧠 Архитектура проекта
Клиент взаимодействует только с собственным backend API
Backend агрегирует данные из:
NewsData API (новости)
OpenWeatherMap API (погода)
MongoDB используется для хранения:
пользователей
подписок
аналитики

⚙️ Технологический стек
Frontend
Next.js (App Router)
React
TypeScript
Redux Toolkit
RTK Query
CSS

Backend
Node.js
MongoDB Atlas
JWT + bcrypt
REST API

⚡ Архитектурные особенности
SSR (Server-Side Rendering) для улучшения SEO и скорости загрузки
Server Components и Client Components (Next.js)
Централизованный backend для работы с внешними API
Определение устройства пользователя (Client Hints + User-Agent)
Определение геолокации пользователя по IP
Система аналитики пользовательских подписок

📦 Установка и запуск
Клонирование проекта
git clone https://github.com/Mukhin001/nova-app.git
cd nova-app

Backend
cd backend
npm install
npm run dev

Frontend
cd frontend
npm install
npm run dev

📊 Функциональность
Возможность Доступ
Просмотр ленты новостей ✅
Погода по городам ✅
Авторизация ✅
Подписки на города ✅
Аналитика ✅
Редактирование профиля ✅

👤 Автор
Игорь Мухин
GitHub: https://github.com/Mukhin001
