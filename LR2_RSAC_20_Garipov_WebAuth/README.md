# Лабораторная работа №2

## Вариант 2
Реализовать аутентификацию по паролю с подтверждением по email. В таблице идентификаторов должны храниться: логин, email, пароль, временный код подтверждения. Таблица идентификаторов должна представлять собой таблицу в реляционной БД, данные должны передаваться через SQL-запросы. При аутентификации на сервере сравниваются пароли и на email пользователя отправляется сгенерированный на сервере временный код подтверждения. На клиенте после отправки данных с паролем должен произойти редирект на форму для ввода временного кода подтверждения. После отправки кода на сервере сравниваются пришедший код и код из БД. При совпадении кодов аутентификация считается успешной и происходит редирект на страницу-заглушку.

### Инструкция по работе
1. Скопировать репозиторий.
2. Установить зависимости с файла ```requirements.txt``` 
3. Запустить файл main.py

### Демонстрация работы программы

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4BHT_IEKq0o/0.jpg)](https://www.youtube.com/watch?v=4BHT_IEKq0o)

_нажмите на картинку, чтобы посмотреть демонстрацию_

Программа реализована с использованием пакета Flask. Программа реализует метод аутентификации по паролю и временному коду.

Работу выполнил:
Ильнур Гарипов, студент группы №42514c, Университет ИТМО, ФБИТ

Контакты для связи:
- Почта - i_garipov@mail.ru
- telegram - @Better_than_Leonid
