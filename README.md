# STACK
Класс Movie:

Этот класс представляет собой модель фильма. Он содержит атрибуты title, genre и release_year, которые описывают соответственно название фильма, его жанр и год выпуска.
Метод __str__ определен для удобного представления объекта класса Movie в виде строки.
Класс MovieDatabase:

Этот класс представляет базу данных фильмов. Внутри него используется стек для хранения объектов класса Movie.
Метод add_movie добавляет новый фильм в базу данных.
Метод remove_movie удаляет последний добавленный фильм из базы данных.
Метод print_all_movies выводит все фильмы из базы данных.
Метод search_movie_by_title ищет фильм по его названию.
Метод list_movies_by_genre выводит все фильмы по указанному жанру.
Метод list_movies_by_release_year выводит все фильмы по указанному году выпуска.
Цикл в __main__:

В этом цикле предоставляется интерактивное меню для взаимодействия с базой данных фильмов.
Каждый пункт меню соответствует одной из операций: добавление фильма, удаление фильма, вывод всех фильмов, поиск фильма по названию, вывод фильмов по жанру, вывод фильмов по году выпуска.
Интеграция с Git:

Для использования этого кода с Git, вы можете создать новый репозиторий с помощью команды git init, а затем добавить этот файл в репозиторий с помощью git add <имя файла> и зафиксировать изменения с помощью git commit -m "Добавлен базовый функционал базы данных фильмов".
При работе с Git вы также можете создавать ветки для разработки новых функций, комбинировать изменения из разных веток и работать над различными версиями кода с помощью функциональности ветвления и слияния Git.
Команды Git позволяют отслеживать изменения в коде, возвращаться к предыдущим версиям, сравнивать изменения между версиями и сотрудничать с другими разработчиками, работающими над тем же проектом.
