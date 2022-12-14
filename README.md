# Weeaboo Store

Weeaboo Store - интернет-магазин манги, написанный на __React + Redux__.

В качестве бэкенда использует __[json-server](https://www.npmjs.com/package/json-server)__ с __[json-server-auth](https://www.npmjs.com/package/json-server-auth)__. Для запросов на сервер - библиотеку __[axios](https://www.npmjs.com/package/axios)__.

Функционал, уже реализованный в приложении:
* Авторизация с помощью AccessToken
* Каталог
* Корзина с добавлением и удалением содержимого
* Избранное с добавлением и удалением содержимого
* Поиск по каталогу
* Меню бургер с навигацией
* Возможность сделать заказ
* Страница аккаунта с возможностью сменить пароль в профиле или глянуть историю заказов
* Адаптивный дизайн

## Дополнительно
* Так как __json-server-auth__ поддерживает только access token - при завершении действия работы access token'а и каких-либо действиях, затрагивающих операции с сервером - приложение выкинет пользователя из аккаунта.
* Еще не реализована валидация формы регистрации и логина.
* Приложение будет дорабатываться.

## Что нужно добавить
* Фильтры для товаров
* Валидацию форм
* Темизацию
* Работу с нелокальным сервером
