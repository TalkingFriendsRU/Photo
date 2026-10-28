# TalkingFriendsRU | Альбом

Скринкапсы эпизодов «Говорящий Том» — кадр каждые 0,5 секунды.

## Структура
- `index.html` — сайт (без зависимостей, чистый HTML/CSS/JS)
- `data/episodes.js` — список эпизодов и ссылки на кадры
- `.nojekyll` — отключает обработку Jekyll на GitHub Pages

## Добавить эпизод
1. Загрузить кадры на imgbb: `python3 imgbb_upload.py --dir <папка> --prefix <код>`
2. Перегенерировать `data/episodes.js`
3. Закоммитить — Pages обновится сам
