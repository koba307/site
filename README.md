# Мой сайт (static)

Папка для статического сайта. Все .html и .htm файлы в этой папке доступны по прямым ссылкам.

## Как работает локально
Уже запущен сервер:
```
http://localhost:8000/
```

Просто добавляй файлы:
- `index.html` — главная
- `about.html` — любая страница
- `мои-проекты.html` — будет по адресу `/мои-проекты.html`

## Развёртывание (бесплатно)

### Вариант 1: GitHub Pages (рекомендую)
1. Репозиторий уже создан.
2. Открой https://github.com/koba307/site/settings/pages
3. Source → **Deploy from a branch** → Branch: `main`, Folder: `/ (root)`
4. Save. Подожди 30–60 секунд.

Сайт появится по адресу:
`https://koba307.github.io/site/`

### Вариант 2: Бесплатный домен (регистрация)
**DigitalPlat** (лучший вариант в 2026):
→ https://dash.domain.digitalplat.org/

Зарегистрируй например:
- `koba.dpdns.org`
- `мойсайт.qzz.io`
- `project.us.kg`

Потом добавь DNS запись **CNAME**:
```
@  или имя  →  koba307.github.io
```

**is-a.dev** (очень красивый dev-домен):
→ https://github.com/is-a-dev/register

Получишь `твоёимя.is-a.dev` через простой PR.

### Самый быстрый способ (без Git)
Зайди → https://app.netlify.com/drop
Перетащи всю папку `sites` — получишь мгновенный URL вида `random-name.netlify.app`

## Советы
- Чтобы не было .html в URL — используй папки с `index.html` внутри (например `/about/index.html`).
- `.nojekyll` уже добавлен (нужен для GitHub Pages).
- Можно подключить любой домен (бесплатный или купленный).

Когда добавишь свои реальные файлы — просто закоммить/запушь или перетащи на Netlify.

Удачи!