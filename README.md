[Русский](README.ru.md) | [English](README.md)

# Ulvis URL Shortener for Telegram

Integration of the [Ulvis API](https://ulvis.net/) into a Python Telegram bot. Allows users to shorten URLs, specify custom aliases, and set a password.

<p align="left">
  <img src="https://skillicons.dev/icons?i=python" height="42" alt="Python" />
  <img src="https://cdn.simpleicons.org/telegram/26A5E4" height="42" alt="Telegram" />
</p>

## Usage

```text
/shorten <url> [custom_name] [password]
```

Examples:

```text
/shorten https://example.com
/shorten https://example.com mylink
/shorten https://example.com mylink mypassword
```

## Implementation

- `UlvisUrlShortener` — handles API requests, responses, and errors.
- `UlvisShortenerBotFunction` — processes Telegram commands and sends results to users.

Includes handling of network errors, invalid API responses, and invalid user input.

## Technologies

Python · pyTelegramBotAPI · Requests · Ulvis API

## Links

- [Original repository](https://github.com/IHVH/system-integration-bot-2)
- [Pull Request #99](https://github.com/IHVH/system-integration-bot-2/pull/99)
