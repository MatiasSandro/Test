# TestMariedtest
ИНСТРУКЦИЯ ПО РАЗВЁРТЫВАНИЮ
Так как данное андроид приложение имеет архитектуру клиент-сервер, нужно развернуть сервер и клиент.
Для запуска приложения потребуется:
1)	Microsoft SQL Server Management Studio;
2)	Microsoft Visual Studio;
3)	AndroidStudio;
4)	Мобильный телефон на ОС Android с версией Android не ниже 4.0.3.
Развёртывание сервера
Алгоритм развёртывания приложения:
1.	Перейти по ссылке: 
2.	Скачать архив с названием Married001.rar;
3.	Открыть Microsoft SQL Server Management Studio;
4.	Создать пустую БД с именем MarriedTest;
5.	Открываем MicrosoftVisualStudio;
6.	Запускаем проект из скачанного архива;
7.	Открыть Console Packages в MVC ипрописать Add-migration Init;
8.	Прописать в консоли Update-database;
9.	Исправить зависимость ключа на NoAction он отобразится в ошибке при Update;
10.	Скопировать скрипты из файла Married_Init.sql, выполнить заполнение БД;
11.	Запускаем командную строку, прописываем команду ipconfig;
12.	Копируем IP адрес и вставляем его в файл LaunchSettings.json.
5.2 Развёртывание клиент
1.	Открыть AndroidStudio;
2.	Открыть приложение из архива;
3.	Подключить телефон через провод к компьютеру;
4.	Все устройства должны находиться в одной сети;
