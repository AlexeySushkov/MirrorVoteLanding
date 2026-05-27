# MirrorVote — лендинг

Статичный лендинг для сервиса **MirrorVote** — AI-помощника выбора образа.

🌐 Сайт: [mirror-vote.ru](https://mirror-vote.ru)

---

## Состав

- `index.html` — основной файл лендинга
- `images/` — все изображения, используемые на странице
- `.github/workflows/deploy.yml` — автодеплой на сервер при пуше в `main`

## Запуск локально

Откройте `index.html` в браузере.

## Деплой

При каждом `git push` в ветку `main` GitHub Actions автоматически синхронизирует файлы на сервер через rsync:

```
index.html + images/ → /var/www/landing/ (mirror-vote.ru)
```

## Контакты

| Канал | Адрес |
|-------|-------|
| Telegram | [@mirrorvote](https://t.me/MirrorVote_bot) |
| Email | [mirror-vote@yandex.ru](mailto:mirror-vote@yandex.ru) |

## Лицензия

См. файл `LICENSE` в этом каталоге.
