# У Вас должны быть установлены:
- Composer
- Git
- OpenServer

# Инструкция

Один из возможных вариантов установки

- Создать в папке с доменом новую папку
- Склонируем репозиторий
< git clone https://github.com//zour228/task.task .> 
- После клонирования необходимо создать базу данных :
> По умолчанию, установлены следующих параметры:
>> DB_HOST=127.0.0.1
>> DB_PORT=3306
>> DB_DATABASE=task
>> DB_USERNAME=root
>> DB_PASSWORD=
> При необходимости, вы можете изменить данные значения в скрытом файле .env 
- После настройки БД необходимо открыть консоль в корневой папке с проектом и ввести следующие команды
< php artisan migrate >
< php artisan serve >
- После данных действий в консоли появится сообщение о том, что сервер запущен под определенным Ip-адресом (По умолчанию "127.0.0.1:8000")
Готово