# Polityka prywatności

*Aplikacja „Piłkarzyki na kartce” · wersja 1.0 · obowiązuje od [DATA WEJŚCIA W ŻYCIE]*

> **W skrócie.** Gra z komputerem działa na twoim telefonie, także offline. Do chmury (Google Firebase) trafiają tylko: twój profil, pseudonim, punkty, statystyki, historia meczów i przerwany mecz – żeby działał ranking i synchronizacja. Pseudonim i punkty są publiczne w rankingu. Reklamy dopasowane do ciebie, statystyki użycia i raporty awarii włączamy tylko za twoją zgodą. Konto i wszystkie dane usuniesz jednym przyciskiem w Ustawieniach.

## 1. Administrator i kontakt

Administratorem twoich danych osobowych jest [IMIĘ I NAZWISKO / NAZWA FIRMY], [ADRES] (dalej: „my”). W sprawach danych osobowych pisz na [ADRES E-MAIL]. Nie wyznaczyliśmy inspektora ochrony danych.

Polityka dotyczy aplikacji mobilnej „Piłkarzyki na kartce” na Android i iOS. Słowa pisane wielką literą mają znaczenie nadane w [Regulaminie](terms.md).

## 2. Jakie dane przetwarzamy, w jakim celu i na jakiej podstawie

Podstawy prawne to przepisy RODO: art. 6 ust. 1 lit. a (zgoda), lit. b (wykonanie umowy – Regulaminu), lit. c (obowiązek prawny) i lit. f (nasz prawnie uzasadniony interes).

### 2.1. Konto i logowanie (Firebase Authentication)

- **Dane:** identyfikator Konta (UID); przy koncie gościa – nic więcej. Przy logowaniu przez Apple lub Google dodatkowo identyfikator konta w tej usłudze i adres e-mail przekazany przez Apple lub Google (Apple pozwala ukryć prawdziwy adres) – oraz informacja, którą metodą się logujesz. Nie pobieramy haseł.
- **Cel:** założenie i prowadzenie Konta, przypisanie do niego wyników, połączenie konta gościa z Apple lub Google, przywrócenie Konta na nowym urządzeniu.
- **Podstawa:** wykonanie umowy (lit. b).

### 2.2. Profil, statystyki, historia i synchronizacja (Cloud Firestore)

- **Dane profilu:** pseudonim, kolor długopisu, metody logowania, daty założenia i aktualizacji, punkty (łącznie i w bieżącym tygodniu), statystyki (rozegrane, wygrane, przegrane, sposób wygranej, samobóje, poddania, serie, liczba odcinków i odbić, łączny czas gry, wyniki na poszczególnych poziomach), osiągnięcia z datami ich zdobycia.
- **Historia meczów:** dla każdego meczu – daty i czas trwania, wersja Aplikacji i silnika, ustawienia (poziom, boisko, kto zaczyna, zegar, podgląd ruchów, cofanie), ziarno losowe komputera, zapis ruchów, wynik i jego powód, punkty, liczba podpowiedzi i cofnięć.
- **Przerwany mecz:** stan meczu w toku (ustawienia, ruchy, pozycja piłki, czas, pozostałe podpowiedzi i cofnięcia) – zapisywany przy pauzie, wyjściu z meczu lub przejściu Aplikacji w tło.
- **Cel:** profil, statystyki, osiągnięcia, powtórki meczów, wznowienie meczu i synchronizacja między urządzeniami.
- **Podstawa:** wykonanie umowy (lit. b).

### 2.3. Pseudonim i publiczny ranking

- **Dane:** pseudonim, kolor długopisu, punkty i miejsce w rankingu światowym i tygodniowym. Te dane **widzą inni Użytkownicy**. Rezerwacja pseudonimu (pseudonim → UID) jest publiczna, aby nikt inny nie mógł użyć tego samego pseudonimu.
- **Moderacja:** pseudonimy sprawdza automatyczny filtr słów; w razie zgłoszenia możemy je też sprawdzić ręcznie.
- **Cel i podstawa:** prowadzenie rankingu – wykonanie umowy (lit. b); moderacja pseudonimów i ochrona innych Użytkowników – nasz prawnie uzasadniony interes (lit. f).

### 2.4. Game Center i Google Play Games

- **Dane:** wynik punktowy i zdobyte osiągnięcia przesyłane do Game Center (iOS) lub Google Play Games (Android), jeśli jesteś w nich zalogowany.
- **Cel i podstawa:** tablica znajomych i osiągnięcia na platformie – wykonanie umowy (lit. b).
- Apple i Google przetwarzają te dane jako odrębni administratorzy, na zasadach własnych polityk prywatności. Widoczność twojego profilu dla znajomych ustawiasz w Game Center lub Play Games.

### 2.5. Ochrona przed oszustwami i bezpieczeństwo (Firebase App Check, reguły bezpieczeństwa)

- **Dane:** tokeny potwierdzające, że żądanie pochodzi z oryginalnej Aplikacji na prawdziwym urządzeniu (Google Play Integrity na Androidzie, App Attest / DeviceCheck na iOS), adres IP i podstawowe informacje techniczne o żądaniu.
- **Cel:** ochrona rankingu przed sfałszowanymi wynikami (m.in. limit przyrostu punktów), ochrona danych i infrastruktury przed nadużyciami.
- **Podstawa:** nasz prawnie uzasadniony interes (lit. f) – uczciwy ranking i bezpieczeństwo usługi.

### 2.6. Zdalna konfiguracja (Firebase Remote Config)

- **Dane:** identyfikator instalacji Firebase, wersja Aplikacji i systemu, język i kraj urządzenia.
- **Cel:** dostarczanie ustawień bez aktualizacji Aplikacji, np. częstotliwości reklam pełnoekranowych i balansu poziomów komputera.
- **Podstawa:** wykonanie umowy (lit. b) i nasz prawnie uzasadniony interes (lit. f).

### 2.7. Statystyki użycia (Google Analytics for Firebase) – tylko za zgodą

- **Dane:** identyfikator instancji Aplikacji, zdarzenia w Aplikacji (np. otwarte ekrany, rozpoczęcie i wynik meczu, poziom komputera, użycie podpowiedzi), model urządzenia, wersja systemu i Aplikacji, język, przybliżony kraj lub region ustalony na podstawie adresu IP. Nie łączymy tych danych z pseudonimem ani adresem e-mail.
- **Cel:** zrozumienie, jak gra jest używana, i dostrajanie poziomów komputera.
- **Podstawa:** zgoda (lit. a), wyrażona przełącznikiem „Statystyki użycia”.

### 2.8. Raporty awarii (Firebase Crashlytics) – tylko za zgodą

- **Dane:** przebieg błędu (stack trace), czas awarii, model urządzenia, wersja systemu i Aplikacji, ilość wolnej pamięci, identyfikator instalacji Crashlytics.
- **Cel:** wykrywanie i naprawianie błędów.
- **Podstawa:** zgoda (lit. a), wyrażona przełącznikiem „Raporty awarii”.

### 2.9. Reklamy (Google AdMob)

Opisane w [punkcie 4](#4-reklamy-i-twoje-zgody).

### 2.10. Kontakt, zgłoszenia błędów i reklamacje

- **Dane:** adres e-mail, treść wiadomości i dane, które sam podasz (np. pseudonim, model urządzenia, wersja Aplikacji).
- **Cel i podstawa:** odpowiedź i rozpatrzenie zgłoszenia – nasz prawnie uzasadniony interes (lit. f); rozpatrzenie reklamacji i obsługa wniosków dotyczących danych – obowiązek prawny (lit. c).

## 3. Dane przechowywane tylko na telefonie

W pamięci Aplikacji na twoim urządzeniu zapisujemy: ustawienia (gra, dźwięk i wibracje, motyw, tryb dla daltonistów, język), twoje wybory dotyczące zgód, potwierdzenie wieku, autozapis bieżącego meczu (po każdym ruchu), lokalną historię do powtórek, licznik meczów potrzebny do rzadszego wyświetlania reklam pełnoekranowych oraz informację, które karty z naszymi innymi grami ukryłeś. Te dane nie opuszczają telefonu, z wyjątkiem zapisów opisanych w punkcie 2.2. Usuniesz je, odinstalowując Aplikację lub czyszcząc jej dane w ustawieniach systemu.

Aplikacja nie prosi o dostęp do lokalizacji GPS, kontaktów, zdjęć, aparatu ani mikrofonu. Wibracje i dźwięki działają lokalnie.

## 4. Reklamy i twoje zgody

Aplikacja jest darmowa dzięki reklamom Google AdMob: banerom w menu, rankingu i profilu (nigdy na planszy), reklamom pełnoekranowym po meczu (najwyżej co drugi mecz, nie w pierwszych meczach i nie po samouczku) i dobrowolnym reklamom nagradzanym (podpowiedź lub 3 cofnięcia).

W menu i w Ustawieniach polecamy też nasze inne gry. To zwykły link do sklepu z aplikacjami – przy tym nie przekazujemy nikomu żadnych danych, a kartę w menu możesz ukryć.

- **Dane przetwarzane przez Google i partnerów reklamowych:** identyfikator reklamowy urządzenia (Android Advertising ID / IDFA na iOS – tylko jeśli na to pozwolisz), adres IP, przybliżona lokalizacja ustalona na jego podstawie, informacje o urządzeniu, systemie i Aplikacji, informacje o wyświetleniach reklam i interakcjach z nimi.
- **Reklamy dopasowane (spersonalizowane)** – wyświetlamy tylko wtedy, gdy włączysz przełącznik „Reklamy dopasowane do mnie”, wyrazisz zgodę w formularzu zgód Google (UMP), a na iPhonie także pozwolisz na śledzenie w systemowym zapytaniu (App Tracking Transparency). Podstawa: zgoda (art. 6 ust. 1 lit. a RODO i art. 399 ustawy – Prawo komunikacji elektronicznej).
- **Reklamy ogólne (niespersonalizowane)** – wyświetlamy, jeśli nie zgodzisz się na reklamy dopasowane albo nie potwierdzisz, że masz co najmniej 16 lat. Nie są oparte na twojej historii, ale Google może używać identyfikatorów i adresu IP do ograniczania liczby wyświetleń, wykrywania oszustw i pomiaru reklam – w zakresie twoich wyborów w formularzu zgód. Podstawa: nasz prawnie uzasadniony interes w finansowaniu darmowej Aplikacji (lit. f) oraz zgoda, gdy jest wymagana do zapisu lub odczytu informacji na urządzeniu.
- **Lista partnerów reklamowych** jest dostępna w formularzu zgód Google, otwieranym z ekranu „Zgody i prywatność” (link „Partnerzy reklamowi”). Jak Google wykorzystuje dane: [policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites?hl=pl).

### Jak zmienić lub wycofać zgody

- W Aplikacji: **Ustawienia → Prywatność i reklamy → Zgody na reklamy i analitykę**. Wycofanie zgody nie wpływa na zgodność z prawem przetwarzania przed jej wycofaniem.
- iPhone: Ustawienia systemu → Prywatność i ochrona → Śledzenie.
- Android: Ustawienia systemu → Google → Reklamy (zresetowanie lub usunięcie identyfikatora reklamowego).

## 5. Odbiorcy danych

Nie sprzedajemy twoich danych. Przekazujemy je tylko:

- **Google Ireland Limited** (Irlandia) i **Google LLC** (USA) – Firebase (Authentication, Cloud Firestore, App Check, Remote Config, Analytics, Crashlytics), logowanie przez Google, Google Play Games, AdMob i formularz zgód UMP. W zakresie Firebase Google działa jako nasz podmiot przetwarzający; w zakresie reklam, logowania i Play Games – także jako odrębny administrator. [Polityka prywatności Google](https://policies.google.com/privacy?hl=pl).
- **Apple Distribution International Ltd.** (Irlandia) i **Apple Inc.** (USA) – Zaloguj się przez Apple, Game Center, App Attest – jako odrębny administrator. [Polityka prywatności Apple](https://www.apple.com/pl/legal/privacy/).
- **Partnerom reklamowym Google** – w zakresie twoich zgód (punkt 4).
- **Innym Użytkownikom** – pseudonim, kolor i punkty w rankingu.
- **Organom publicznym** – gdy wymaga tego prawo.

## 6. Przekazywanie danych poza EOG

Google LLC i Apple Inc. mogą przetwarzać dane w USA i innych państwach poza Europejskim Obszarem Gospodarczym. Podstawą jest decyzja Komisji Europejskiej z 10 lipca 2023 r. stwierdzająca odpowiedni stopień ochrony (EU-US Data Privacy Framework – obie firmy są w nim certyfikowane), a uzupełniająco standardowe klauzule umowne zatwierdzone przez Komisję. Kopię zabezpieczeń możesz otrzymać, pisząc do nas.

## 7. Jak długo przechowujemy dane

| Dane | Okres |
|---|---|
| Konto, profil, pseudonim, punkty, statystyki, osiągnięcia | Do usunięcia Konta. Konta gościa nieużywane przez [24 MIESIĄCE] usuwamy automatycznie. |
| Historia meczów w chmurze | 12 miesięcy od zakończenia meczu (automatyczne usuwanie), wcześniej – przy usunięciu Konta. |
| Przerwany mecz w chmurze | Do zakończenia lub porzucenia meczu albo usunięcia Konta. |
| Statystyki użycia (Analytics) | Dane na poziomie użytkownika – 2 miesiące; potem tylko zbiorcze raporty bez identyfikatorów. |
| Raporty awarii (Crashlytics) | 90 dni. |
| Dane reklamowe | Według zasad Google i partnerów reklamowych (lista w formularzu zgód). |
| Korespondencja i reklamacje | Do zakończenia sprawy, a następnie do upływu terminu przedawnienia ewentualnych roszczeń. |
| Dane na telefonie | Do odinstalowania Aplikacji lub wyczyszczenia jej danych. |

## 8. Usunięcie konta i danych {#usuniecie-konta}

**W Aplikacji:** Ustawienia → **Usuń konto i wszystkie dane** → potwierdź. Aplikacja od razu usuwa historię meczów, przerwany mecz, profil ze statystykami i punktami, rezerwację pseudonimu, a na końcu samo Konto w Firebase Authentication. Twój pseudonim znika z rankingu.

**Bez Aplikacji:** napisz na [ADRES E-MAIL] z tematem „Usunięcie konta” i podaj pseudonim oraz sposób logowania (gość, Apple, Google). Możemy poprosić o informacje potwierdzające, że Konto należy do ciebie. Usuniemy dane w ciągu 30 dni i potwierdzimy to e-mailem.

Usunięcie Konta nie usuwa danych w Game Center i Google Play Games (usuwasz je w ustawieniach tych usług) ani danych na telefonie (odinstaluj Aplikację). Kopie zapasowe usług Google są nadpisywane w ciągu ich standardowych cykli. Dane, które musimy zachować z mocy prawa (np. korespondencję reklamacyjną), przechowujemy tylko przez wymagany okres.

## 9. Twoje prawa

Masz prawo do:

- dostępu do swoich danych i otrzymania ich kopii,
- sprostowania danych (pseudonim zmienisz w Ustawieniach),
- usunięcia danych (punkt 8),
- ograniczenia przetwarzania,
- przenoszenia danych przetwarzanych na podstawie umowy lub zgody,
- sprzeciwu wobec przetwarzania opartego na naszym prawnie uzasadnionym interesie,
- wycofania zgody w dowolnym momencie (punkt 4),
- wniesienia skargi do Prezesa Urzędu Ochrony Danych Osobowych (ul. Stawki 2, 00-193 Warszawa, [uodo.gov.pl](https://uodo.gov.pl)) lub organu nadzorczego w państwie twojego zamieszkania.

Aby skorzystać z praw, napisz na adres z punktu 1. Odpowiemy w ciągu miesiąca. Podanie danych jest dobrowolne, ale bez UID i danych profilu nie możemy prowadzić Konta ani rankingu – możesz wtedy grać z komputerem offline.

## 10. Dzieci i młodzież

Na ekranie „Zgody i prywatność” pytamy, czy masz co najmniej 16 lat. Jeśli tego nie potwierdzisz, wyświetlamy wyłącznie reklamy niespersonalizowane i nie włączamy statystyk użycia ani raportów awarii, ponieważ osoby poniżej 16 lat nie mogą same wyrazić zgody na takie przetwarzanie (art. 8 RODO). Aplikacja nie jest skierowana do dzieci poniżej 13 lat. Rodzic lub opiekun, który uważa, że dziecko przekazało nam dane, może napisać do nas, a my je usuniemy.

## 11. Bezpieczeństwo i profilowanie

- Połączenia z serwerami są szyfrowane (TLS). Reguły bezpieczeństwa bazy danych pozwalają każdemu Użytkownikowi czytać i zmieniać wyłącznie własne dane (poza publicznym rankingiem i rezerwacją pseudonimu), a App Check blokuje żądania spoza oryginalnej Aplikacji.
- Nie podejmujemy wobec ciebie decyzji opartych wyłącznie na zautomatyzowanym przetwarzaniu, które wywołują skutki prawne lub w podobny sposób istotnie na ciebie wpływają. Automatyczne limity punktów i filtr pseudonimów służą uczciwości rankingu – jeśli nie zgadzasz się z ich efektem, napisz do nas, a sprawę rozpatrzy człowiek.
- Reklamy dopasowane wiążą się z profilowaniem przez Google i partnerów reklamowych – tylko za twoją zgodą.
- Komputer, z którym grasz, to algorytm działający na telefonie; nie analizuje on twoich danych osobowych.

## 12. Zmiany polityki

Politykę aktualizujemy, gdy zmieniają się funkcje Aplikacji, usługi, z których korzystamy, lub przepisy. O istotnych zmianach poinformujemy cię w Aplikacji, a jeśli zmiana wymaga nowej zgody – poprosimy o nią ponownie.
