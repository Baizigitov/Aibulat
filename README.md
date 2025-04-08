# Telegram GPT Chat Bot 🤖

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-blue)](https://core.telegram.org/bots)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT_3.5-green)](https://openai.com)

Телеграм-бот, использующий OpenAI GPT-3.5 Turbo для генерации ответов на вопросы пользователей.

## 🚀 Особенности
- Ответы на текстовые вопросы
- Обработка ошибок API
- Логирование запросов
- Простая интеграция с Telegram

## ⚙️ Требования
- Python 3.8+
- Аккаунт OpenAI с API-ключом
- Telegram Bot Token от [@BotFather](https://t.me/BotFather)

## 📦 Установка
1. Клонируйте репозиторий:
```bash
git clone https://github.com/Baizigitov/Chatbot.git
cd Chatbot
```
2. Установите зависимости:

```bash
pip install -r requirements.txt
```
## 🔧 Настройка
1. Создайте файл .env в корне проекта:

```env
TELEGRAM_BOT_TOKEN=ваш_telegram_токен
OPENAI_API_KEY=ваш_openai_ключ
```
2. Получите токены:

Telegram Bot Token: через [@BotFather](https://t.me/BotFather)

OpenAI API Key: Получить API-ключ можно в личном кабинете [OpenAI](https://platform.openai.com/api-keys)

## 🖥️ Запуск
```bash
python Chatbot.py
```
## 🎮 Использование
Начните диалог командой `/start`
parse_mode="MarkdownV2"

Задавайте любые вопросы текстом

Бот ответит используя GPT-3.5 Turbo

Пример диалога:
```
Пользователь: Напиши рецепт борща
Бот: 1. Приготовьте бульон из говядины...
```
## 📝 Структура проекта
```
Chatbot/
├── Chatbot.py        # Основной код бота
├── requirements.txt  # Зависимости
└── .env.example      # Шаблон файла конфигурации
```
## 🔄 Команды
/start - начать диалог

Любой текст - получить ответ от ИИ

## ⚠️ Ограничения
Максимальная длина ответа: 4096 символов (ограничение Telegram)

Скорость ответа зависит от OpenAI API

Требуется стабильное интернет-соединение

## 🌟 Возможные улучшения
Добавить обработку изображений

Реализовать ответы голосовыми сообщениями

## 📄 Лицензия
MIT License. Подробнее в файле [License](LICENSE).
