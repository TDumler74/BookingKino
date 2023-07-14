# BookingKino

**_Final project for base Java course an AIT-School._**

EN - "Cinema or theatre ticket booking system, with the ability to add events, select seats, 
view available seats for a particular session"

DE - "Buchungssystem für Kino- oder Theaterkarten, mit der Möglichkeit, Veranstaltungen hinzuzufügen, 
Sitzplätze auszuwählen und verfügbare Plätze für eine bestimmte Sitzung anzuzeigen.

RU - "Система бронирования билетов в кинотеатре или театре, с возможностью добавления событий, 
выбора места, просмотра свободных мест на конкретный сеанс"

______________________________________
 В данном проекте я реализовал рабочее место кассира оператора небольшого кинотеатра. Кассир может 
 работать со списком фильмов, сеансов, бронировать билеты, просматривать карту мест сеанса 
 (свободные и занятые места на конкретный сеанс), добавить филь или сеанс для фильма.
 
Для запуска необходима версия Java openjdk-20.0.1.
Стартовый файл классически Main.

При старте выводится собственно меню пользователя с доступными командами.
Стартовый класс Main.java содержит стартовую инициализацию и вызов меню. Дальнейшая работа 
происходит из класса Menu, где собственно описано само меню и действия для каждой из команд.
Вспомогательные классы:
* Cinema (собственно и есть класс кинотеатра)
* Hall (класс для залов кинотеатра)
* Film (класс для фильмов)
* Session (класс для сеансов)
* Constants (отдельный класс для использования одних и тех же констант из разных классов)
* Files (отдельный класс в котором организована работа с файлами чтение и запись).


Для хранения информации используются файлы
* FilmList.csv (хранение списка фильмов доступных в программе)
* HallList.csv (хранение списка залов кинотеатра)
* SessionList.csv (хранение списка сеансов кинотеатра)

Privet, kak dela 
