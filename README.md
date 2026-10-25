# chetvertak.site

Резюме и портфолио. Статический сайт, хостинг GitHub Pages.

## Как обновляется

- Любое изменение файлов в ветке `main` автоматически публикуется на сайте (1–2 минуты).
- Домен: `chetvertak.site`, DNS в Cloudflare (A-записи на GitHub Pages, прокси выключен).
- HTTPS включается автоматически: workflow `.github/workflows/pages-https.yml` проверяет каждые 15 минут и ставит галочку «Enforce HTTPS», как только GitHub выпустит сертификат.

## Структура

- `index.html` — резюме
- `хардфит.html`, `бот-канал.html`, `деталь.html` — кейсы
- `portfolio.html` — общая страница портфолио
- `case.css`, `case-gold.css`, `case-auto.css`, `cases-readable.css` — стили
- `img/` — скриншоты и фото
