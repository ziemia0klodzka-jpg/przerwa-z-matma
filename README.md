# Przerwa z Matmą

Aplikacja na tablety z Androidem (7.0+), która co ustalony czas korzystania wymusza przerwę:
dziecko rozwiązuje zadania z matematyki (klasy 1–3, także działania pisemne „pod kreską”),
ze słówek włoskich (obrazek + 4 odpowiedzi z wymową) i — od wersji 3.3 — z czytania ze zrozumieniem
po polsku i po włosku. Ustawienia chroni PIN rodzica.

## Nowości w 3.3

- **📊 Statystyki nauki** na telefonie rodzica („Więcej…” → Statystyki nauki): zadania i poprawność z 14 dni,
  „Czy się uczy?”, powtórki, rodzaje zadań z matematyki, najtrudniejsze słówka. Tablet wysyła je tylko na prośbę.
- **Czytanie po polsku i po włosku** (bez lektora): słowo → obrazek, zdanie z pytaniem, krótki tekst z pytaniem.
- **Przedmioty do zaznaczenia**: matematyka, włoski, czytanie po polsku, czytanie po włosku — w dowolnym zestawie.
- **Więcej włoskiego**: ok. 800 słówek (było 500) i ok. 500 zdań (było 300).
- **Głośność** po przerwie, blokadzie lub komunikacie wraca do poziomu sprzed przerwy, jeśli w tym czasie wzrosła.

## Pobierz

**[PrzerwaZMatma.apk — najnowsza wersja](https://github.com/ziemia0klodzka-jpg/przerwa-z-matma/releases/latest/download/PrzerwaZMatma.apk)**

Otwórz link na tablecie, pobierz plik i zainstaluj (Android zapyta o zgodę na instalację z nieznanego źródła).

## Aktualizacje

Od wersji 2.1 aplikacja sama sprawdza to repozytorium (mniej więcej co 3 godziny, przez Wi-Fi;
do wersji 3.0 — co 12 godzin) i instaluje nowe wersje. W panelu rodzica: **Uprawnienia → Instalowanie
aktualizacji** oraz **Aktualizacje → Sprawdź teraz**. Wersję 2.0 trzeba raz zaktualizować ręcznie.

Od wersji 3.1 aktualizację można zlecić z telefonu rodzica („Więcej…” → **Zaktualizuj teraz**) — tablet
instaluje ją od razu, także przez dane komórkowe. Na karcie tabletu widać jego wersję i stan aktualizacji.

Od wersji 3.2 aplikacja na telefonie rodzica sama pokazuje **„Jest nowa wersja aplikacji”** z przyciskiem
„Zaktualizuj aplikację”, a potem **„Zaktualizuj wszystkie tablety”**. Telefon z wersją 3.1 lub starszą
trzeba raz zaktualizować ręcznie — linkiem wyżej.

## Limit serwera wiadomości

Telefon rodzica i tablety rozmawiają przez darmowy przekaźnik ntfy.sh. Przyjmuje on najwyżej **250 wiadomości
na dobę z jednej sieci** (telefon i tablety w tym samym Wi-Fi dzielą jeden limit). Od wersji 3.2.1 aplikacja
wysyła ich kilka razy mniej, a po wyczerpaniu limitu pokazuje prawdziwy powód i godzinę odnowienia
(zamiast „brak internetu”). Szczegóły: panel rodzica → menu → **🩺 Diagnostyka**. Do czasu odnowienia
polecenia wyślesz z telefonu przez dane komórkowe. Pobranie statystyk nauki (od 3.3) to 2 wiadomości.

Każde wydanie zawiera `PrzerwaZMatma.apk` i `version.properties` (numer wersji i suma SHA-256).
Aplikacja instaluje tylko plik podpisany tym samym kluczem co zainstalowana wersja.
