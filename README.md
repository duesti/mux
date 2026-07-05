![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Ubuntu&pause=1000&color=4E94F7&width=435&lines=%F0%9F%9A%80+Mux+%E2%80%94+Minimalist+AI+Chat+Interface)

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) 
## 📸 Скриншоты:
<img width="1440" height="1024" alt="mux" src="https://github.com/user-attachments/assets/3f1bf798-79de-4379-b2f4-f3f1a693259b" />
<img width="1440" height="1024" alt="mux-dialogue" src="https://github.com/user-attachments/assets/e3136bb7-eccd-4213-8cc6-8628ef684ca4" />


Mux — это быстрый, легковесный и минималистичный веб-интерфейс (чат-клиент) для локальных и облачных языковых моделей, спроектированный с упором на приватность, UX и фокусную работу. Приложение вдохновлено интерфейсами передовых ИИ-ассистентов для разработчиков и поддерживает бесшовное переключение контекстов, управление историей чатов и гибкую настройку генерации (Effort Level).

## ✨ Ключевые фичи

* 🤖 Мультимодельность: Нативная поддержка интеграции через API с новейшими моделями (включая Laguna XS 2.1 от Poolside, OpenAI, Anthropic). [1] 
* 🧠 Управление усилиями (Effort level): Тонкая настройка глубины рассуждения (Reasoning Tokens) модели прямо из панели ввода (low / medium / high). [2] 
* 📂 Контекстные сессии и история: Удобный боковой сайдбар с возможностью ведения параллельных цепочек диалогов (например, разработка аудиоплееров, брейншторм стартапов).
* ⌨️ Быстрые подсказки (Quick Actions): Готовые пресеты под полем ввода для мгновенного старта популярных задач (архитектура, генерация кода, вопросы).
* 🎛️ Минималистичный UI/UX: Темная тема без отвлекающих факторов, адаптивная верстка и плавные переходы.

## 🛠️ Технологический стек

* Frontend: React (rsbuild), TailwindCSS, TypeScript, Lucide Icons.
* Backend / API Wrapper: Rust (Axum)
* State Management: Zustand.

## 🚀 Быстрый старт## 1. Клонирование репозитория

```
git clone https://github.com/duesti/mux.git
cd mux
```

## 2. Настройка окружения

Создайте файл .env в корне проекта и добавьте ваши API-ключи:

```
NEXT_PUBLIC_DEFAULT_MODEL=laguna-xs-2.1
POOLSIDE_API_KEY=your_key_here
OPENROUTER_API_KEY=your_key_here
```

## 3. Установка зависимостей и запуск

```
bun install
bun dev или с помощью yarn/bun/pnpm
```

Откройте http://localhost:3000 в браузере.

