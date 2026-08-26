# China Growth Transition Lab

Публичный сайт исследовательского проекта об экономической трансформации Китая.

## Публикация через GitHub Pages

1. Создайте новый репозиторий на GitHub.
2. Загрузите в него **всё содержимое этой папки**.
3. В репозитории откройте **Settings → Pages**.
4. В разделе Build and deployment выберите **GitHub Actions**.
5. Сделайте push в ветку `main`.
6. GitHub Actions автоматически опубликует сайт.

Workflow находится в `.github/workflows/pages.yml`.

## Обновление сайта

Главная страница: `index.html`  
Стили: `assets/style.css`

Для следующих этапов можно добавить:
- `research/` — отдельные главы исследования;
- `data/` — codebook и описания наборов данных;
- `results/` — таблицы регрессий;
- `maps/` — GIS-карты;
- `papers/` — PDF;
- `replication/` — код и replication package;
- `updates/` — подробный research log.

## Важно

Не публикуйте секретные ключи, персональные данные или закрытые datasets в публичном репозитории.
