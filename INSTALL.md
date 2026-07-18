# Как установить профильный README

## 1. Создай специальный репозиторий

Название репозитория должно полностью совпадать с твоим GitHub-логином.

Пример:

```text
Логин: vladdev
Репозиторий: vladdev
```

Репозиторий должен быть публичным.

## 2. Загрузи файлы

Структура:

```text
YOUR_USERNAME/
├── README.md
└── assets/
    ├── banner.png
    ├── about.png
    ├── projects.png
    └── resume.pdf
```

`resume.pdf` необязателен. Если резюме нет, удали кнопку Resume из README.

## 3. Замени значения

В README.md найди и замени:

- `YOUR_USERNAME` — логин GitHub;
- `YOUR_TELEGRAM` — имя в Telegram без символа @;
- `YOUR_EMAIL` — адрес электронной почты;
- `EXILLIUM_REPOSITORY` — название репозитория Exillium;
- `TELEGRAM_BOT_PLATFORM` — название репозитория платформы ботов;
- `FASTAPI_REPOSITORY` — название репозитория FastAPI-проекта.

## 4. Размеры изображений

Рекомендуемые размеры:

- `banner.png`: 1280 × 350 px;
- `about.png`: примерно 500 × 500 px с прозрачным фоном;
- `projects.png`: примерно 500 × 500 px с прозрачным фоном.

GitHub не поддерживает полноценный пользовательский CSS. Поэтому расположение сделано через HTML-таблицы внутри Markdown.
