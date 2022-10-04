# Ruz_search for windows in timetable

Авторы: Кармадонова О., Межакова П.

Программа автоматически сопоставляет расписание нескольких людей из базы РУЗ ВШЭ (раписание учебных занятий для студентов и сотрудников НИУ ВШЭ) и указывает промежутки, в которые все перечисленные люди свободны от учебных занятий. Программа поможет вам и вашим коллегам из Вышки найти свободное окошко в рабочем графике по любому поводу - будь то мероприятие студенческой организации или встреча с научным руководителем!

Ссылка на сайт РУЗа: https://ruz.hse.ru/

Для работы программы Вам необходимы следующие пакеты для Python: Selenium, Beautiful Soup и Pandas, модуль time.

Помимо установки пакета Selenium, Вам также понадобится предустановленный Google Chrome версии .95 и выше, а также скачанный на компьютер WebDriver и сохранённый к нему путь: скачать WebDriver можно по [ссылке](https://chromedriver.chromium.org/downloads), путь к файлу можно посмотреть и скопировать в Вашем файловом менеджере.

Программа берет на вход дату планируемой встречи, ФИО студента_тки и/или сотрудника_цы НИУ ВШЭ, их статус (студент_ка/преподаватель_ница). На выходе выдает пары, в течение которых в данную дату свободны все введенные студенты_тки и/или преподаватели_ницы. Вывод программы осуществляется в виде таблицы. Использованеи программы для поиска окон в расписании возможно как для одного дня, так и для периода времени. Учтен вывод случая, когда все студенты_тки/преподаватели_ницы заняты в рассматриваемый день/период. 
