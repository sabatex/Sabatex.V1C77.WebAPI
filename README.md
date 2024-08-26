# Sabatex.V1C77.WebAPI
[![MIT License](https://img.shields.io/badge/license-MIT-red.svg)](https://github.com/sabatex/Sabatex.V1C77.WebAPI/blob/master/LICENSE.TXT)


# Web API для 1С7.7
 Данное API можно запустить для любой конфигурации 1С7.7.
 Что может API ?
   1. Читать Метаданные, Константы, Справочники, Документы ...
   2. API использует проверенную временем библиотеку для доступа по OLE (COM) к 1С7.7
			https://github.com/sabatex/Sabatex.V1C77

Что нужно для запуска API?
   1. Windows 7 и выше;
   2. 1С7.7
   3. И всё ...

Как запустить ?

	1. Распаковать в любую папку.
	2. Отредактировать файл appsettings.json заменив строчки -- **** -- на реальные не забывая
	что обратный слеш пишем два раза, например C:\\Users\\admin\\.1C\\MyCompany\\1C7.7
	3. Запускаем WebApi1C.Server.exe
	4. Разрешаем доступ к порту 5000
	5. Запускаем браузер http://localhost:5000 или http://you ip:5000
