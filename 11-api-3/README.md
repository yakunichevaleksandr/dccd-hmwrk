# Домашнее задание к уроку 10 – API #2

Разработать JSON API-приложение «Холодильник»:

1. Приложение должно быть работать на порту `3000`.

### 🍰 Piece of cake (+3 exp)
Приложение должно отдавать при `GET` запросе на `http://localhost:3000/items` данные, хранящиеся в файле `index.json`.

### 🎸 Let's rock (+5 exp)
При `POST` запросе на `http://localhost:3000/items` приложение должно добавлять в массив элементов в файле `index.json`
данные, переданные в теле запроса.

### ✊ Come get some (+5 exp)
При `PUT` запросе на `https://localhost:3000/items/:id` (где `id` – идентификатор элемента в `index.json`) приложение
должно заменять этот элемент на данные, переданные в теле запроса.

При `DELETE` запросе на `https://localhost:3000/items/:id` приложение должно удалять элемент с соответствующим
идентификатором из файла `index.json`.

---

Шаблон для старта разработки [здесь](./index.js).
Пример index.json [здесь](./index.json).
