# Sklep internetowy
> Chciałabym stworzyć prosty sklep internetowy do sprzedaży suplementów i kosmetyków oraz działający przy nim blog. W miarę rozwoju projektu chciałabym go poszerzać o użyteczne i ciekawe funkcje.

## Spis treści
* [Raport III](#raport_III)
* [Raport II](#raport_II)
* [Technologie](#technologie)
* [Status](#status)
* [Inspiracje](#inspiracje)

## Raport_III
Zrobiłam:
- zintegrowanie całego sklepu z Django ORM (opierającego się na sqlite3) 
- dodałam nową funkcjonalność do panelu administratora, która pozwala na dodawanie/usuwanie/edycję produktów na stronie przez włąściciela za pomocą intuicyjnego interfejsu stworzonego z wykorzystaniem modeli
- umożliwiłam dodawania produktów do koszyka ze strony głównej sklepu poprzez naciśnięcie przycisku, ikonka koszyka na stronie głównej wyświetla ilość rzeczy tam się znajdujących, stan koszyka danego użytkownika/gościa jest zapisywany za pomocą ciasteczek w przeglądarce, także zamykając przeglądarkę produkty stale są zapamiętane w koszyku
- podgląd koszyka wraz z całą jego funkcjonalnością, dodałam użyteczną funkcję regulacji liczby produktów w koszyku poprzez intuicyjne strzałki, liczba produktów oraz ich koszt aktualizują się w zależności od stanu koszyka, wyświetlają sie tam również wszystkie informacje o produktach wraz ze zdjęciem, następnie przechodzi się do finalizacji zamowienia
- podsumowanie zamówienia, które wyświetla listę i liczbę produktów, które chce się zamówić oraz łączny koszt zamówienia, obok wyświetlany jest formularz do wypełnienia z danymi użytkownika do wysyłki oraz przygotowane miejsce na płatność
- deployment na heroku, dzięki czemu na każdym urządzeniu nie będącym w sieci lokalnej można podglądać stan projektu oraz korzystać ze sklepu. Jednocześnie skonfigurowałam konto na heroku z kontem na githubie, w taki sposób, że każda wprowadzona zmiana do mojego projektu i zacommitowana na githuba jest wyświetlana od razu na stronie, przez co zaautomatyzowałam proces deploymentu

Aktualnie zajmuję się:
- dopracowaniem UI designu aby sklep wyglądał bardziej nowocześnie, dopasowaniem rozdzielczości zdjęć do formatu na stronie
- umożliwieniem płatności na stronie poprzez Paypala
- dopracowaniem stworzonych już funkcji, które działąją w niezadawalający mnie sposób
- możliwością wyświetlania szczegółowej informacji o danym produkcie po kliknięciu przycisku 

## Raport_II
Zrobiłam:
- research na temat frameworków webowych, zastanawiałam się nad wyborem pomiędzy Django, Flask oraz nowym fastAPI, jednak z powodu braku wystarczających materiałów dla fastAPI oraz przeczytanych opinii wybór padł na Django 
- wykorzystywałam do pracy środowisko wirtualne venv do zarządzania moimi modułami pip
- stworzyłam repozytorium na githubie, jednak po wielu commitach i pracy na kilku branchach coś tknęło mnie do założenia nowego repozytorium ;) przez co zakładanie nowych repozytoriów opanowałam do perfekcji 
- skorzystałam z wyszukanego boilerplata dla Django, żeby ułatwić sobie pracę nad backendem mojego sklepu

Aktualnie zajmuję się:
- przystosowywaniem mojej strony do zaczęcia pracy nad frontendem
- deploymentem na heroku, co ułatwiłoby podgląd aplikacji webowiej na innych komputerach, jednak cały czas wyrzuca mi bład, który jest prawdopodobnie związany ze źle skonfigurowanym procfilem

W najbliżych planach:
- zajęcie się UI/UX design 
- umożliwienie dodawania produktów do koszyka oraz funkcjonalości podglądu zamówienia 
- stworzenie frontendu korzystając z elementów bootstrapa 
- umożliwienie płatności na stronie

Przemyślenia:
wszystko zajmuję mi bardzo dużo czasu i nerwów, ponieważ pierwszy raz robię stronę, która nie jest zwykłym HTML z CSS, jednak bardzo dużo w ten sposób się uczę.

## Technologie
* Python - version 3.8.2
* Django- version 2.2.8
* Bootstap 4 
* Sqlite3
* Heroku 
* płatności API Paypal

## Status
Projekt w przygotowaniu.

## Inspiracje
> Tutaj będę dodawała źródła, inspiracje, poradniki, z których korzystałam i inspirowałam się nimi.
