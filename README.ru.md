# Ulvis URL Shortener для Telegram

Интеграция [Ulvis API](https://ulvis.net/) в Telegram-бота на Python. Позволяет сокращать ссылки, задавать пользовательские имена и передавать пароль.

<p align="left">
  <img src="https://skillicons.dev/icons?i=python" height="42" alt="Python" />
  <img src="https://cdn.simpleicons.org/telegram/26A5E4" height="42" alt="Telegram" />
</p>

## Использование

```text
/shorten <url> [custom_name] [password]
```

Примеры:

```text
/shorten https://example.com
/shorten https://example.com mylink
/shorten https://example.com mylink mypassword
```

## Реализация

- `UlvisUrlShortener` — взаимодействие с API, обработка ответов и ошибок.
- `UlvisShortenerBotFunction` — обработка команды Telegram и отправка результата пользователю.

Предусмотрена обработка сетевых ошибок, некорректных ответов API и ошибок пользовательского ввода.

## Технологии

Python · pyTelegramBotAPI · Requests · Ulvis API

## Ссылки

- [Оригинальный репозиторий](https://github.com/IHVH/system-integration-bot-2)
- [Pull Request #99](https://github.com/IHVH/system-integration-bot-2/pull/99)
