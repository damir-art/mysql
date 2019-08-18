# MySQL
Руководство по MySQL
http://mysql.itgid.info/

## Импорт каталога в PHPMyAdmin
* Заходим в PHPMyAdmin
* Вкладка "Базы данных" > Вводим имя > Сравнение: utf8_general_ci > Создать
* Вкладка "Импорт" > Обзор... > Загружаем файл .sql > Вперёд > Зеленые записи (всё в порядке)
* Слева кликаем по загруженной таблице

### Содержание
* [Подключение к базе данных PHP](https://damir-art.github.io/mysql/mysqli_connect/)

## Добавление пользователя в БД (логин, пароль)
* Создаём таблицу `users`
* В PHPMyAdmin слева кликаем по БД
* Под именем БД кликаем по ссылке "Новая"
* Имя таблицы `users`
    * id (автоинкремент, primary)
    * login (varchar, 50)
    * email (varchar, 50)
    * pass (varchar, 50)
    * сохранить

### Как удалить таблицу
* В PHPMyAdmin слева выбираем таблицу
* Жмём по вкладке "Операции"
* Снизу жмем по "Удалить таблицу"
