MedService Web PWA v57

Что добавлено:
1. Новый логотип для web:
   - favicon.png
   - icons/icon-192.png
   - icons/icon-512.png
   - apple-touch-icon.png

2. Manifest для установки сайта как приложения:
   - manifest.webmanifest

3. Service Worker:
   - sw.js

Как загрузить на GitHub Pages:
1. В репозитории сайта замените текущий index.html на файл index.html из этой папки.
2. Загрузите рядом с index.html:
   - manifest.webmanifest
   - sw.js
   - favicon.png
   - папку icons целиком

Структура должна быть такая:
/
  index.html
  manifest.webmanifest
  sw.js
  favicon.png
  /icons
    icon-192.png
    icon-512.png
    apple-touch-icon.png
    ...

После загрузки:
- откройте сайт;
- обновите Ctrl+F5;
- на Android/Chrome можно будет выбрать "Установить приложение" или "Добавить на главный экран".

Важно:
Если сайт уже был установлен раньше, удалите старый ярлык/приложение и установите заново, чтобы подтянулась новая иконка.
