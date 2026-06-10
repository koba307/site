# Мой сайт (static)

Папка для статического сайта. Все .html и .htm файлы в этой папке доступны по прямым ссылкам.

## Как работает локально

### Удобный способ

```bash
./serve.sh
```

Или классика:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Открой в браузере http://localhost:8000/

**Внимание:** В этой среде локальный сервер в фоновом режиме живёт максимум 10 часов. Для долгой работы запускай команду сам в своём терминале.

## Постоянный хостинг (GitHub Pages)

1. Открой https://github.com/koba307/site/settings/pages
2. Source → Deploy from a branch → `main` / (root)
3. Save.

Сайт будет жить по адресу:
https://koba307.github.io/site/

## Бесплатный домен

- **DigitalPlat** (dpdns.org, qzz.io и др.): https://dash.domain.digitalplat.org/
- **is-a.dev**: https://github.com/is-a-dev/register

## Советы

- Добавляй новые .html/.htm файлы — они автоматически будут доступны по /filename.html
- Для чистых URL без .html используй подпапки с index.html
- `.nojekyll` уже есть (нужен для GitHub Pages)

Удачи с сайтом!