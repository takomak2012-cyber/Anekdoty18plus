# Анекдоты 18+

Сайт мобильного приложения «Анекдоты 18+» (Android).

- Приложение: `com.windak.schooljokes18plus`
- Версия на сайте: 1.10 (APK в `download/`)
- Публикация: GitHub Pages, ветка `main`
- Адрес: https://takomak2012-cyber.github.io/Anekdoty18plus/

## Содержимое

| Файл | Назначение |
| --- | --- |
| `index.html` | Главная страница: описание, экраны, скачивание APK |
| `privacy.html` | Политика конфиденциальности (обязательна для RuStore) |
| `ads.txt` | Список рекламных систем (требование РСЯ) |
| `app-ads.txt` | Авторизованные продавцы рекламы для приложения (требование РСЯ) |
| `assets/style.css` | Оформление сайта |
| `assets/icon-512.png` | Иконка приложения |
| `assets/screen-*.png` | Скриншоты приложения |
| `download/*.apk` | Подписанный universal APK |

## Обновление версии

1. Собрать подписанный universal APK и положить его в `download/`.
2. Обновить версию в `index.html`: кнопка скачивания (`href` и `download`), список фактов.
3. Сделать коммит и запушить в `main` — GitHub Pages обновится автоматически.

## Требования РСЯ

`app-ads.txt` и `ads.txt` должны оставаться в корне сайта и открываться по прямым ссылкам:

- https://takomak2012-cyber.github.io/Anekdoty18plus/app-ads.txt
- https://takomak2012-cyber.github.io/Anekdoty18plus/ads.txt

Один `app-ads.txt` покрывает все приложения разработчика `takomak2012-cyber`.
