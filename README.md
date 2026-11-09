# Design and Development (P4)

Адаптивная вёрстка макета 2Р4 «Design and Development Process».

## Структура проекта

```text
design-development-p4/
├── index.html
├── styles.css
└── README.md
```

## Запуск локально

Откройте `index.html` в браузере. Для этого проекта не нужны сборщик, npm или дополнительные зависимости.

## Использовано

- HTML5, семантическая разметка
- CSS Flexbox для сетки карточек и расположения элементов
- Относительные единицы (`vh`, `vw`, `%`, `rem`)
- Медиазапросы для планшетов и телефонов
- Адаптивная типографика через `clamp()`

## Публикация на GitHub Pages

1. Создайте на GitHub новый публичный репозиторий, например `design-development-p4`.
2. Загрузите в корень репозитория файлы `index.html`, `styles.css` и `README.md`.
3. Откройте репозиторий → **Settings** → **Pages**.
4. В блоке **Build and deployment** выберите:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Нажмите **Save**.
6. Подождите, пока GitHub соберёт сайт. Адрес появится в разделе **Settings → Pages**. Обычно он выглядит так:
   `https://ВАШ-ЛОГИН.github.io/ИМЯ-РЕПОЗИТОРИЯ/`

Если сайт не появился сразу, обновите страницу Pages через минуту или проверьте вкладку **Actions**.
