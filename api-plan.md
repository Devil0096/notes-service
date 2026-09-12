# План API

## Endpoints
- GET /notes — список заметок
- POST /notes — создать заметку
- GET /notes/{id} — получить заметку
- PUT /notes/{id} — обновить
- DELETE /notes/{id} — удалить

## Модель заметки
- id
- title
- content
- tags[]
- created_at

## Теги
- GET /tags — список всех тегов
- POST /notes/{id}/tags — добавить тег