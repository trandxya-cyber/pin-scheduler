# v1lads Pin Scheduler — простой информационный сайт для Pinterest Developers

Готовый статический шаблон для GitHub Pages. НЕ публикуйте его без корректировки политики конфиденциальности.

## Что обязательно заменить

1. `privacy.html`: `[REPLACE WITH REAL OWNER OR BUSINESS NAME]` — фактическое имя владельца или название существующей компании/проекта.
2. `privacy.html`: `REPLACE_WITH_REAL_EMAIL@example.com` и `[REPLACE WITH REAL CONTACT EMAIL]` — реальный контактный email.
3. `privacy.html`: уточните, будет ли приложение использовать Make, n8n, локальные токены, OAuth, какие данные реально хранятся, сроки хранения и удаление. Текст написан для проекта в разработке, а не уже существующего продукта.
4. При необходимости отредактируйте `index.html`: название и точное назначение приложения. Не обещайте функций, которых не будет.

## Бесплатное размещение

1. Войдите на https://github.com/ и создайте **Public**-репозиторий, например `pin-scheduler`.
2. Загрузите в корень репозитория `index.html`, `privacy.html`, `styles.css`.
3. Откройте **Settings → Pages → Build and deployment**.
4. **Source: Deploy from a branch**; **Branch: main**; **Folder: /(root)**; **Save**.
5. Сайт будет опубликован по адресу `https://ВАШ-ЛОГИН.github.io/pin-scheduler/` (для соответствующего логина/репозитория).
6. Проверьте обе страницы из режима инкогнито, без авторизации GitHub.
7. Ссылку на главную страницу впишите в поле Website Pinterest; ссылку `.../privacy.html` в поле Privacy Policy.

## GitHub Actions

Для этих трёх статических файлов собственный workflow создавать НЕ нужно. GitHub Pages автоматически публикует их при изменении основной ветки. GitHub Actions годится для деплоя или запланированных временных задач, но НЕ превращает GitHub Pages в сервер для OAuth и НЕ предоставляет доступа к изображениям на вашем ПК.

## Pinterest API

Сайт не выдаёт App ID/Secret автоматически: подайте заявку на Trial Access на https://developers.pinterest.com/apps/. После одобрения начните тестирование, затем подготовьте OAuth-демонстрацию для Standard Access. Trial Pins видны только владельцу. Одобрение Pinterest не гарантировано.

## Конфиденциальность

Не добавляйте в этот публичный репозиторий пароли, OAuth-токены, App Secret, личные изображения, Make webhook URL и файлы с персональными данными. Разместите только информационные страницы.

Официальные источники:
- https://developers.pinterest.com/docs/getting-started/connect-app/
- https://developers.pinterest.com/docs/key-concepts/access-tiers/
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
