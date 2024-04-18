# auth_app

Harmonogram:
https://docs.google.com/spreadsheets/d/1eXGbNb3vDarOcoMxmDGrlQjJqaRxWPMlAvNsCGpKq3s/edit#gid=1386834576

Do 18.04: 
Stworzenie drzewa (struktury) plików w folderze głównym (auth_app):

Foldery: 
instance (bazy danych)
static (style css)
templates (pliki html)
Do auth_app dać app.py i authenticator.py, 
do instance dać jakąś bazę danych użytkowników (puki co mydatabase.db (testowa baza) i users.db)
w static wrzucić jakiś index.css albo main.css, 
w templates dać register, login, authenticate i dashboard (html)


Do 19.04:
Zrobić podstawowe formsy dla plików html i jakiś znośny css

Do 20.04:

Rozpocząć pisanie app - 
1. Zaimportować wszystkie potrzebne rzeczy: Flask, SQL-Alchemy, Flask-login, werkzeug.security(dla bezpieczeństwa haseł w razie wycieku), pyotp (generowanie kodów)
2. Napisać wszystkie routy (render_template)

Do 21.04:

Napisanie bazy danych i klasy User by można było jej używać w przyszłości

Do 25.04:

Napisanie (najlepiej) działającego registeru i loginu (przekierowywuje na authenticator) w appie

Do 27.04:

Naprawianie wszystkich bugów, jeżeli jakieś się pojawią, a jak nie to zwiększyć bezpieczeństwo strony (wykorzystanie hashowania haseł jeżeli nie zostało użyte) : Jak nic z tego to przejście do następnego punktu

Do 01.05:

Napisanie authenticatora w appie

Do 03.05:

Zrobienie lepszych stylów css

Do 12.05 (23:59)

Doszlifowywanie aplikacji w razie potrzeby
