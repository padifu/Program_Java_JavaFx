**Temat:** Wykrywanie stanu zapalnego: temperatura ciała (liczba rzeczywista), tętno i liczba
leukocytów (liczby całkowite).


**Biblioteki:** JDK-11.0.2,JavaFX

**Instrukcja:** 1. Po włączeniu aplikacji użytkownik może uruchomić formularz pacjenta poprzez naciśnięcie przycisku „Dodaj” lub wyłączyć aplikację rozwijając menu „Aplikacja – Zamknij ALT+F4”. Wszystkie pozostałe pola są zablokowane.
2. Formularz pacjenta zawiera kilka ograniczeń, by dane wprowadzone przez użytkownika nie były absurdalne: -w polach „Imię”, ”Nazwisko” użytkownik nie ma możliwości wprowadzania cyfr, -pole „PESEL” ograniczone jest do 11 znaków tylko w formie cyfr, -nie ma możliwości zaznaczenia obu płci równocześnie, -jeśli któreś z pól nie zostało wypełnione lub PESEL został wprowadzony błędnie, po naciśnięciu na przycisk „Zapisz” w danym polu pojawi się czerwony kolor, a pacjent nie zostanie dodany na listę, -nie ma możliwości dodania do tabeli dwóch pacjentów o tym samym numerze PESEL – duplikat powoduje zmiany koloru pola PESEL na czerwony. 
 
3. Przycisk „Zapisz” przy odpowiednim wypełnieniu wyświetla pacjenta w tabeli i odblokowuje dla niego formularz badania – po zaznaczeniu go w tabeli. Domyślnie Blokuje formularz pacjenta i umożliwia dodanie nowej osoby.
4. Przycisk „Anuluj” oczyszcza formularz.
5. W przypadku formularza badania również wprowadzone są pewne bardzo ogólne ograniczenia co do wprowadzanych wartości.  Nie można wprowadzać innych znaków niż cyfry. Zakres temperatur: 36-42 Puls: 30-200 Leukocyty:2000-40000.
6. Przycisk „Zapisz” w formularzu badania przy prawidłowym jego wypełnieniu powoduje zaznaczenia pola „Badanie” w tabeli oraz przypisuje pacjentowi odpowiednie parametry badania. Jest to ostateczny zapis, więc powoduje on zablokowanie obu formularzy i umożliwia dodanie nowego pacjenta. Przycisk „Anuluj” czyści formularz.
7. Nie ma możliwości „usunięcia” badania – jeśli dane pacjenta zostały raz uzupełnione o formularz badania, można dane tego formularza jedynie edytować.

8.Przycisk „Usuń” czyści formularze i usuwa pacjenta z tabeli, odblokowuje możliwość dodania nowego pacjenta. 
