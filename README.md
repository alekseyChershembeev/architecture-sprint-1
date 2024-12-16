# Задание 1
Вам нужно разделить проект Mesto на несколько микрофронтендов.
Самостоятельно решите, какой фреймворк будете использовать, — Module Federation или Single SPA.

## Уровень 1. Проектирование

### Выбор фреймворка:

- Определить, на какие микрофронты разделить монолит нам поможет подход:  Анализ домена бизнеса, Domain-Driven Design.Сервисы будем делать по бизнес-доменам.
- Для разделения этого монолита достаточно использовать создание микрофронтендов с помощью паттерна Module Federation.
- Где каждый компонент будет написан на react, так как в проекте нет сложных форм и таблиц. 
- Так же у команды уже есть опыт работы на данном фреймворке.

## Уровень 2. Планирование изменений

Структура проекта для каждого микрофронтенда:

1. host
   - blocks
   - components
      - App.jsx
      - Footer.js
      - Header.js
      - ProtectedRoute.js
   - utils
     - api.js
   - images
   - webpack.config.js
   - package.json

2. auth
    - blocks
    - components
      - Login.js
      - Register.js
      - InfoTooltip.js
    - utils
        - api.js
        - auth.js
    - webpack.config.js
    - package.json

3. profile
    - blocks
    - components
        - EditAvatarPopup.js
        - EditProfilePopup.js
        - Main.js
        - Register.js
    - utils
      - api.js
    - webpack.config.js
    - package.json

4. crud_photos
    - blocks
    - components
      - AddPlacePopup.js
      - Card.js
      - ImagePopup.js
      - PopupWithForm.js
    - utils
      - api.js
    - webpack.config.js
    - package.json






## Уровень 3. Запуск готового кода
- Не сделано

# Задание 2

Вам нужно разбить её на сервисы, используя подход Domain-Driven Design.





