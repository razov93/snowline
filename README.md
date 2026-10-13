# SNOWLINE v1.0

SNOWLINE: Snowboard Resort Tycoon — браузерная экономическая стратегия об управлении горнолыжным курортом. Игра работает без установки библиотек и сохраняет прогресс в браузере.

## Запуск

Откройте `index.html` двойным щелчком. Если браузер ограничивает локальные файлы, запустите в папке проекта `python3 -m http.server 8000` и откройте `http://localhost:8000`.

## Публикация на GitHub Pages

1. Создайте репозиторий на GitHub и загрузите в его корень `index.html`, `snowboard-tycoon-map.png`, `.nojekyll` и этот `README.md`.
2. Откройте **Settings → Pages**.
3. В разделе **Build and deployment** выберите **Deploy from a branch**, ветку `main` и папку `/ (root)`, затем нажмите **Save**.
4. После публикации GitHub покажет адрес игры в этом же разделе.

## Откат

Предыдущая рабочая версия сохранена в `index.html.before-v1.0-release.bak`. Для отката замените текущий `index.html` содержимым этой копии.
