## CYPRESS

### Notes
- https://docs.cypress.io/guides/getting-started/installing-cypress#Switching-browsers
- https://docs.cypress.io/guides/getting-started/writing-your-first-test#Add-a-test-file

### Stories

1. Użytkownik chce się zarejestrować.
- musi podać swój email, dwukrotnie hasło, imię oraz nazwisko
- hasło jest walidowane i musi spełniać następujące założenia:
    - posiada minimum 8 znaków
    - duże oraz małe litery
    - cyfry
    - znaki specjalne
- imię i naziwsko musi być stringiem
- jeżeli konto już istnieje, użytkownik zostanie o tym powiadomiony
- email jest walidowany, string musi posiadać @ oraz .com w odpowiednich miejscach

2. Użytkownik chce się zalogować.
- loguje się za pomocą emaila i hasła, lub korzysta z OAuth
- w pierwszym przypadku - email jest walidowany jak wyżej
- błąd logowania sygnalizowany jest wiadomością pod formularzem logowania



3. Sprzedawca chce dodać nowy produkt na sprzedaż.
- Formularz pozwala na podanie podstawowych informacji o produkcie 
    - nazwa
    - cena
    - kategoria
    - zdjęcia produktu
    - dokładny opis, wielkość, waga itd (opcjonalnie)

4. Użytkownik chce wyszukać interesujące go produkty.
- search bar zaczyna szukać dopiero po podaniu 3 znaków
- wyniki wyświetlane są na głównej stronie z produktami
- wyniki podlegają paginacji

5. Użytkownik chce zobaczyć swoją historię zakupów i dodać ocenę zakupionego produktu
- ocenę można dokonać poprzez
    - historię zakupów 
    - na stronie produktu o ile wcześniej został zakupiony
