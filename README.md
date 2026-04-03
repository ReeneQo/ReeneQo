# Привет, я Дмитрий 👋

Fullstack-разработчик с коммерческим опытом создания полноценных клиент-серверных приложений.
Работаю с React и Next.js, активно двигаюсь в сторону углубления в backend разработку с Nest.js.

---

### 🛠 Стек

**Frontend:**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=for-the-badge&logo=react&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)

**Backend:**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Инструменты:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

### 💼 Коммерческий опыт

**Bambi Best** — коммерческий сайт центра семейного образования | bambibest.moscow
Fullstack-разработчик | Команда 5 человек

Полноценное клиент-серверное приложение с серверным рендерингом и админ-панелью. Единолично реализовал 100% фронтенда, админ-панель и большую часть серверной логики. Самостоятельный деплой на VPS.

Frontend (Next.js, TypeScript, SCSS):
— Спроектировал FSD подобную архитектуру
— Реализовал маршрутизацию на 4 страницы, с отдельным защищенным роутом для админ-панели
— Полностью адаптивная вёрстка, семантическая разметка, доступность (a11y)
— Полная SEO-оптимизация: meta-теги (title, description, Open Graph), structured data (JSON-LD), оптимизация изображений (next/image, автоконвертация WebP, lazy loading, responsive sizes), SSR для индексации
— Результат: после рефакторинга посещаемость и отклик клиентов выросли на 35%

Backend (NestJS, TypeScript, PostgreSQL, Redis, Docker):
— Реализовал REST API для управления контентом: CRUD-эндпоинты для текстовых блоков и изображений каждого раздела
— Настроил загрузку и хранение файлов на стороне сервера с валидацией формата и размера
— Реализовал авторизацию для админ-панели: регистрация, вход, защита роутов через Guards
— Сессии через Redis: сохранение состояния авторизации, TTL, устойчивость к перезагрузке сервера
— Контейнеризация: PostgreSQL и Redis в docker-compose

Админ-панель:
— Защищённый роут с авторизацией
— Полный CRUD контента: создание, редактирование, удаление текстовых блоков и изображений для всех разделов
— Загрузка изображений с превью и валидацией на клиенте и сервере

Деплой:
— Самостоятельный деплой на VPS: настройка сервера, Nginx (reverse proxy, SSL), Docker Compose

`Next.js` `TypeScript` `SCSS` `NestJS` `PostgreSQL` `Redis` `Docker` `Nginx` `Git` `Figma`

---

**Spectre Boost** — коммерческий сервис интернет-услуг | Fullstack-разработчик | Команда 2 человека

Полноценное клиент-серверное приложение с каталогом услуг, оформлением заказов, онлайн-оплатой через YooKassa, личным кабинетом и взаимодействием через Telegram.

**Frontend** (основной фокус) — React, TypeScript, Tailwind CSS, Zustand:
- Спроектировал клиентскую архитектуру: API-клиент (native fetch) с обработкой ошибок и retry-логикой, сторы на Zustand, маршрутизация
- Реализовал полный пользовательский флоу: каталог услуг → выбор → применение промокода → оформление заказа → оплата через YooKassa → отслеживание статуса в личном кабинете
- Реализовал авторизацию через Telegram: интеграция Login Widget + fallback на code-based авторизацию (6-значный код с polling)
- Обработка платёжных статусов на клиенте: редиректы, отображение результата, обработка edge-кейсов (таймаут, отмена, ошибка)
- Адаптивная вёрстка, анимации (Framer Motion), полная оптимизация, семантика и доступность (a11y)

**Backend** (участие в разработке) — NestJS, TypeScript, Prisma, PostgreSQL, Docker:
- Участвовал в проектировании REST API: структура эндпоинтов, формат ответов, обработка ошибок
- Доработка эндпоинтов под нужды фронтенда, работа с Prisma-моделями
- Участвовал в интеграции YooKassa: тестирование webhook, валидация платёжных статусов
- Понимание полной серверной архитектуры: RBAC (3 роли), статусная машина заказов, event-driven распределение

**Деплой:** Vercel (фронтенд)

`React` `TypeScript` `Tailwind CSS` `Zustand` `Framer Motion` `NestJS` `Prisma` `PostgreSQL` `Docker` `Telegram Bot API` `Git` `Figma`

---

### 📚 Сейчас
- Углубляюсь в Nest.js и серверную разработку
- Двигаюсь к фуллстек-специализации
- Пишу pet-проекты для портфолио

---

### 📬 Контакты

Почта: `wind.autumn@mail.ru`
Telegram: `@ReneeQ_o`
