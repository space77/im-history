HistoryToDBSync
---------------

Синхронизатор истории для серии плагинов *HistoryToDB (RnQHistoryToDB, QIPHistoryToDB, MirandaHistoryToDB)

Автор:		Михаил Григорьев
E-Mail: 	sleuthhound@gmail.com
ICQ: 		161867489
WWW:		http://www.im-history.ru
Лицензия:	GNU GPLv3

Системные требования:
---------------------
ОС:		Win2000/XP/2003/Vista/7
IM-клиент:	Любой
БД:		MySQL 4.0, 4.1, 5.0, 5.1
		PostgreSQL 7.1 - 8.3
		Oracle 8i - 11i
		SQLite 3
		Firebird 2.x

Необходимые компоненты для сборки плагина:
------------------------------------------

1. Embarcadero RAD Studio XE3

2. ZeosLib 7.0.0-alpha
   http://www.sourceforge.net/projects/zeoslib

3. JEDI Core + JEDI VCL
   http://www.delphi-jedi.org

4. DCPcrypt Cryptographic Component Library v2
   http://www.cityinthesky.co.uk/

5. CoolTrayIcon
   http://www.songbeamer.com/delphi/

Описание параметров запуска:
----------------------------

HistoryToDBSync.exe <1> <2>

<1> - (Обязательный параметр) - Путь до файла плагина *HistoryToDB.dll (Например: "C:\Program Files\QIP Infium\Plugins\QIPHistoryToDB\")

<2> - (Обязательный параметр) - Путь до файла настроек *HistoryToDB.dll (Например: "C:\Program Files\QIP Infium\Profiles\sleuthhound@qip.ru\Plugins\QIPHistoryToDB\")
