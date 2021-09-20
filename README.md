Привет! Для себя написал расширение, чтобы просматривать выполненные задания.
Что не нравилось:
[list]бесконечная загрузка заданий[/list]
[list]переход на новую страницу[/list]
[list]нет возможности увидеть "всё и сразу"[/list]
Что сделал:
[list]все задания в одной таблице[/list]
[list]первые 10 пулов загружаются автоматом[/list]
[list]можно увидеть все свои свои задания в одной таблице[/list]
[list]дополнительные метрики, как-то:
[list]процент ошибок[/list]
[list]скорость выполнения[/list]
[list]кол-во(ошибки/принято/на проверке)[/list]
[/list]
Чтобы это всё увидеть, надо скачать архив , распаковать, затем 
[b]chrome://extensions/[/b]
-->[b]Загрузить распакованное расширение[/b]
-->[b]Выбрать ту папку, которую распаковали[/b]
-->[b]Клик по Иконке расширения (Бабочка)-->Параметры[/b]
(можно сохранить в закладки)
 [b]QA:[/b]
[spoil]
[*]Зачем расширение?
Из-за CORS посылать запрос с других доменов [b]нельзя[/b], можно сделать userScript, но слишком много мороки
[*]Какие преимущества?
Скорость загрузки, можно увидеть всё и сразу, всё как мы любим.
[*]Конфиденциальность?
Всё выполняется на клиенте, никаких метрик не собирается, код открытый - можно посмотреть его даже не имея навыков в программировании
[*]Что ещё?
Я перечеслил основные плюшки: 
[list]процент ошибок[/list]
[list]скорость выполнения[/list]
[list]кол-во(ошибки/принято/на проверке)[/list]
но в зависимости от фидбека добавлю новые
[/spoil]
Так как расширение писалось изначально "под себя", есть ряд неочевидных моментов
[list]загружаются полные данные [b]по первым 10 пулам[/b][/list]
[list]чтобы загрузить статистику по какой-то строке -- просто двойной клик по этой строке[/list]
[list]можно сортировать таблицу по колонкам -- клик по названию колонки, и таблица отсортируется по убыванию этой колонки[/list]

Любой фидбек приветствуется. Если вам что-то не хватает --пишите об этом, или не нравится цветовая схема, UX/UI, не тот шрифт -- буду учитывать (если сообществу интересно).
[b]Ограничения[/b]: предполагается, что вы пользуетесь доменом [b]toloka.yandex.ru[/b] (бывает ещё toloka.yandex.com и, наверное, другие), или авторизованы в нём. Если у вас другой рабочий домен для толоки, сообщите об этом
[b]Restrictions:[/b] It is assumed that you use the Toloka.yandex.ru domain (there is still toloka.yandex.com and, probably, others), or authorized in it. If you have another working domain for push, report it
