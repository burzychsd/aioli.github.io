# Instrukcja obsługi systemu zarządzania treścią

**Wersja:** 1.0
**Data utworzenia:** 06.11.2025
**System:** WordPress z motywem Sage

---

## Spis treści

1. [Wprowadzenie](#1-wprowadzenie)
2. [Zarządzanie stronami](#2-zarządzanie-stronami)
3. [Bloki treści (Gutenberg)](#3-bloki-treści-gutenberg)
4. [Wpisy (Blog/Aktualności)](#4-wpisy-blogaktualności)
5. [Menu restauracyjne](#5-menu-restauracyjne)
6. [Oferty pracy (Kariera)](#6-oferty-pracy-kariera)
7. [Biblioteka mediów](#7-biblioteka-mediów)
8. [Zarządzanie formularzami (Fluent Forms)](#8-zarządzanie-formularzami-fluent-forms)
9. [Menu nawigacyjne](#9-menu-nawigacyjne)
10. [Ustawienia motywu](#10-ustawienia-motywu)
11. [Wielokrotne bloki](#11-wielokrotne-bloki-reusable-blocks)
12. [Najczęstsze problemy i rozwiązania](#12-najczęstsze-problemy-i-rozwiązania)
13. [Załączniki](#13-załączniki)

---

## 1. Wprowadzenie

### 1.1. O systemie WordPress

WordPress to system zarządzania treścią (CMS - Content Management System), który umożliwia tworzenie, edycję i publikowanie treści na stronie internetowej bez konieczności posiadania wiedzy technicznej z zakresu programowania. System wykorzystuje intuicyjny interfejs administracyjny dostępny przez przeglądarkę internetową.

### 1.2. Logowanie do panelu administracyjnego

Aby uzyskać dostęp do panelu administracyjnego, należy:

1. Otworzyć przeglądarkę internetową (zalecane: Google Chrome, Firefox, Safari, Edge)
2. Wpisać w pasku adresu: `https://domena-strony.pl/wp-admin/`
3. Wprowadzić dane logowania:
   - **Nazwa użytkownika** lub **Adres e-mail**
   - **Hasło**
4. Kliknąć przycisk **„Zaloguj się"**

**Uwaga:** W przypadku zapomnienia hasła należy skorzystać z opcji **„Nie pamiętasz hasła?"** dostępnej na stronie logowania.

### 1.3. Przegląd panelu administracyjnego

Po zalogowaniu wyświetla się **Panel administracyjny** (Dashboard), który składa się z następujących elementów:

- **Górny pasek** – zawiera szybki dostęp do najważniejszych funkcji oraz link do podglądu strony
- **Menu boczne** (lewe) – główna nawigacja systemu z dostępem do wszystkich funkcji
- **Obszar roboczy** – centralna część ekranu, w której wykonuje się operacje edycyjne
- **Moduły informacyjne** – wyświetlają statystyki, aktualności i skróty

---

## 2. Zarządzanie stronami

Strony stanowią główny typ treści służący do prezentacji statycznych informacji (np. O nas, Kontakt, Oferta).

### 2.1. Tworzenie nowej strony

Aby utworzyć nową stronę, należy:

1. W menu bocznym wybrać **Strony → Dodaj nową**
2. W polu **„Dodaj tytuł"** wprowadzić nazwę strony
3. Dodać treść przy użyciu bloków Gutenberg (szczegóły w rozdziale 3)
4. Skonfigurować ustawienia strony w panelu prawym
5. Zapisać zmiany lub opublikować stronę

### 2.2. Edycja istniejącej strony

W celu edycji strony należy:

1. Wybrać **Strony → Wszystkie strony** z menu bocznego
2. Odnaleźć stronę do edycji (możliwe użycie wyszukiwarki)
3. Kliknąć w tytuł strony lub przycisk **„Edytuj"**
4. Wprowadzić wymagane zmiany
5. Kliknąć **„Aktualizuj"** w celu zapisania zmian

### 2.3. Dodawanie bloków treści na stronie

Edytor Gutenberg umożliwia dodawanie treści za pomocą bloków:

1. Kliknąć ikonę **„+"** w lewym górnym rogu lub w miejscu, gdzie ma zostać dodany blok
2. Wybrać blok z listy dostępnych bloków
3. Skonfigurować ustawienia bloku w panelu prawym
4. Wprowadzić treść do bloku

**Dodawanie bloków za pomocą skrótów:**
- Wpisać **/** w edytorze, aby otworzyć szybkie wyszukiwanie bloków
- Wpisać nazwę bloku i nacisnąć Enter

### 2.4. Ustawienia strony (klasa body)

W prawym panelu, w sekcji **„Strona"**, dostępne są następujące ustawienia:

- **Dodatkowa klasa `<body>`** – pole tekstowe umożliwiające dodanie niestandardowej klasy CSS do strony, co pozwala na indywidualne stylowanie

**Zastosowanie:**
Wprowadzenie wartości np. `dark-theme` lub `custom-layout` spowoduje zastosowanie specjalnych styli do danej strony.

### 2.5. Publikowanie i aktualizacja stron

#### Publikowanie nowej strony:
1. Po zakończeniu edycji kliknąć **„Publikuj"** w prawym górnym rogu
2. Potwierdzić publikację przyciskiem **„Publikuj"** w wyświetlonym oknie

#### Aktualizacja istniejącej strony:
1. Po wprowadzeniu zmian kliknąć **„Aktualizuj"**
2. Zmiany zostaną natychmiast widoczne na stronie

#### Zapisywanie wersji roboczej:
- Kliknąć **„Zapisz wersję roboczą"**, aby zachować zmiany bez publikowania

#### Planowanie publikacji:
1. Kliknąć **„Publikuj"**
2. Wybrać **„Harmonogram"**
3. Ustawić datę i godzinę publikacji
4. Potwierdzić przyciskiem **„Zaplanuj"**

---

## 3. Bloki treści (Gutenberg)

System wykorzystuje edytor blokowy Gutenberg, który oferuje szeroki zestaw dedykowanych bloków do budowy stron.

### 3.1. Bloki tekstowe

#### Text (Tekst prosty)
**Zastosowanie:** Wyświetlanie prostych sekcji tekstowych.

**Ustawienia:**
- Pole tekstowe do wprowadzenia treści
- Możliwość formatowania tekstu

#### Content (Treść rozbudowana)
**Zastosowanie:** Sekcje z rozbudowaną treścią.

**Ustawienia:**
- Nagłówek
- Treść z edytorem WYSIWYG
- Opcje wyrównania

#### Quote (Cytat)
**Zastosowanie:** Wyróżnianie cytatów.

**Ustawienia:**
- Tekst cytatu
- Autor (opcjonalnie)
- Styl wyświetlania

### 3.2. Bloki nagłówkowe i Hero

#### Hero Home (Strona główna)
**Zastosowanie:** Główny nagłówek na stronie startowej.

**Ustawienia:**
- Tytuł główny
- Podtytuł
- Obraz lub wideo tła
- Przyciski CTA (Call to Action)
- Ustawienia koloru i tła

#### Hero Menu (Strona menu)
**Zastosowanie:** Nagłówek dedykowany dla stron menu restauracyjnych.

**Ustawienia:**
- Tytuł
- Grafika tła
- Linki do kategorii menu

#### Hero Simple (Prosty nagłówek)
**Zastosowanie:** Uproszczony nagłówek dla standardowych podstron.

**Ustawienia:**
- Tytuł
- Opis krótki
- Opcjonalne tło

### 3.3. Bloki medialne

#### Image (Obrazek)
**Zastosowanie:** Wyświetlanie pojedynczego obrazu.

**Ustawienia:**
- Wybór obrazu z biblioteki mediów
- Tekst alternatywny (ALT)
- Wyrównanie i rozmiar
- Link (opcjonalnie)

#### ImageSeparator (Separator z obrazem)
**Zastosowanie:** Separator wizualny z grafiką.

**Dostępne warianty:** 3 warianty stylizacji

**Ustawienia:**
- Obraz tła
- Wysokość sekcji
- Wariant wyświetlania

#### Slider (Slider)
**Zastosowanie:** Karuzela obrazów lub treści.

**Dostępne warianty:** 2 warianty

**Ustawienia:**
- Dodawanie slajdów (powtarzalne pole)
- Dla każdego slajdu:
  - Obraz
  - Tytuł (opcjonalnie)
  - Opis (opcjonalnie)
  - Link (opcjonalnie)
- Ustawienia autoplay
- Prędkość przejścia

#### TextAndGallery (Tekst z galerią)
**Zastosowanie:** Połączenie treści tekstowej z galerią zdjęć.

**Dostępne warianty:** 4 warianty układu

**Ustawienia:**
- Nagłówek
- Treść tekstowa
- Galeria obrazów
- Układ (tekst po lewej/prawej)
- Wariant wyświetlania

### 3.4. Bloki Call-to-Action

#### CTA (Wezwanie do działania)
**Zastosowanie:** Sekcje zachęcające użytkownika do wykonania akcji.

**Dostępne warianty:** 3 warianty stylizacji

**Ustawienia:**
- Nagłówek
- Treść
- Przycisk(i):
  - Tekst przycisku
  - URL
  - Styl przycisku
- Tło (kolor lub obraz)
- Wariant wizualny

#### Promo (Promocja)
**Zastosowanie:** Wyróżnienie oferty promocyjnej.

**Dostępne warianty:** 2 warianty

**Ustawienia:**
- Tytuł promocji
- Opis
- Obraz
- Przycisk CTA
- Termin ważności (opcjonalnie)

#### InfoBar (Pasek informacyjny)
**Zastosowanie:** Wyświetlanie istotnych informacji w formie paska.

**Ustawienia:**
- Treść informacji
- Ikona (opcjonalnie)
- Kolor tła
- Link (opcjonalnie)

### 3.5. Bloki restauracyjne

#### Menu (Wyświetlanie menu)
**Zastosowanie:** Prezentacja pełnego menu restauracji z kategoriami.

**Ustawienia:**
- Wybór kategorii menu do wyświetlenia
- Układ (lista/siatka)
- Wyświetlanie cen
- Filtrowanie po kategoriach

#### MenuListing (Lista menu)
**Zastosowanie:** Lista dostępnych menu (np. obiadowe, kolacja, śniadanie).

**Ustawienia:**
- Nagłówek sekcji
- Automatyczne pobieranie menu z CPT
- Limit wyświetlanych elementów
- Układ wyświetlania

#### MenuSingle (Pojedyncze menu)
**Zastosowanie:** Szczegółowa prezentacja wybranego menu.

**Dostępne warianty:** 3 warianty układu

**Ustawienia:**
- Wybór konkretnego menu (CPT: Menu)
- Wariant wyświetlania
- Wyświetlanie linku do pełnego menu

#### Restaurants (Restauracje)
**Zastosowanie:** Prezentacja listy lokali restauracyjnych.

**Ustawienia:**
- Powtarzalne pole restauracji:
  - Nazwa
  - Adres
  - Zdjęcie
  - Link do lokalizacji (mapa)
  - Godziny otwarcia
- Układ wyświetlania

### 3.6. Bloki kontaktowe

#### ContactUs (Kontakt)
**Zastosowanie:** Sekcja kontaktowa z informacjami.

**Dostępne warianty:** 2 warianty układu

**Ustawienia:**
- Nagłówek
- Dane kontaktowe:
  - Adres
  - Telefon
  - E-mail
- Mapa (opcjonalnie)
- Wariant wyświetlania

#### ContactForm (Formularz kontaktowy)
**Zastosowanie:** Sekcja z formularzem kontaktowym.

**Ustawienia:**
- Nagłówek (opcjonalnie)
- **Shortcode formularza** – pole do wklejenia kodu formularza Fluent Forms (np. `[fluentform id="1"]`)
- Wariant tła:
  - **Wideo** – upload pliku wideo (format MP4)
  - **Obraz** – upload grafiki tła
- Identyfikator sekcji

**Jak pobrać shortcode formularza:**
1. Przejść do **Fluent Forms → Wszystkie formularze**
2. Skopiować kod z kolumny **„Shortcode"**
3. Wkleić w pole **„Shortcode formularza"** w bloku

### 3.7. Bloki treści dynamicznych

#### FeaturedNews (Wyróżnione aktualności)
**Zastosowanie:** Automatyczne wyświetlanie najnowszych wpisów z bloga.

**Ustawienia:**
- Nagłówek sekcji
- Liczba wyświetlanych wpisów
- Kategoria (filtrowanie)
- Układ (siatka/lista)

#### PostListing (Lista wpisów)
**Zastosowanie:** Archiwum lub lista wpisów blogowych.

**Ustawienia:**
- Liczba wpisów na stronie
- Sortowanie (data, tytuł)
- Filtrowanie po kategoriach
- Paginacja

#### JobOffers (Oferty pracy)
**Zastosowanie:** Lista aktywnych ofert pracy.

**Ustawienia:**
- Nagłówek sekcji
- Liczba wyświetlanych ofert
- Sortowanie
- Link do pełnego archiwum

#### JobOfferAnnotation (Adnotacja oferty)
**Zastosowanie:** Krótka informacja lub wyróżnienie oferty pracy.

**Ustawienia:**
- Tytuł
- Krótki opis
- Link do oferty

#### Article (Artykuł)
**Zastosowanie:** Rozbudowana sekcja artykułu z dodatkową treścią.

**Ustawienia:**
- Nagłówek
- Treść artykułu (WYSIWYG)
- Obraz wyróżniający
- Metadata

### 3.8. Bloki opinii i list

#### Testimonials (Opinie)
**Zastosowanie:** Wyświetlanie opinii klientów lub referencji.

**Dostępne warianty:** 3 warianty układu

**Ustawienia:**
- Powtarzalne pole opinii:
  - Treść opinii
  - Imię i nazwisko autora
  - Stanowisko/firma
  - Zdjęcie (opcjonalnie)
  - Ocena gwiazdkowa (opcjonalnie)
- Wariant wyświetlania
- Autoplay slider (jeśli dotyczy)

#### ListBlock (Lista)
**Zastosowanie:** Wyświetlanie list punktowanych lub numerowanych.

**Ustawienia:**
- Nagłówek listy
- Powtarzalne elementy listy:
  - Tytuł elementu
  - Opis
  - Ikona (opcjonalnie)
- Typ listy (punktowana/numerowana)
- Układ kolumn

#### TextAndList (Tekst z listą)
**Zastosowanie:** Połączenie treści tekstowej z listą punktów.

**Dostępne warianty:** 2 warianty układu

**Ustawienia:**
- Nagłówek
- Treść tekstowa
- Lista elementów
- Układ (tekst po lewej/prawej)

### 3.9. Separatory

#### TextSeparator (Separator tekstowy)
**Zastosowanie:** Wizualne oddzielenie sekcji z opcjonalnym tekstem.

**Ustawienia:**
- Tekst separatora (opcjonalnie)
- Styl linii
- Odstępy (padding/margin)
- Kolor

---

## 4. Wpisy (Blog/Aktualności)

Wpisy służą do publikacji aktualności, artykułów blogowych oraz wiadomości. W przeciwieństwie do stron, wpisy są wyświetlane chronologicznie i mogą być organizowane w kategorie oraz oznaczane tagami.

### 4.1. Dodawanie nowego wpisu

Procedura tworzenia wpisu:

1. W menu bocznym wybrać **Wpisy → Dodaj nowy**
2. Wprowadzić tytuł wpisu w polu **„Dodaj tytuł"**
3. Dodać treść przy użyciu edytora Gutenberg
4. W prawym panelu ustawić:
   - **Kategorie** – przypisanie do jednej lub kilku kategorii
   - **Tagi** – dodanie słów kluczowych
   - **Zdjęcie wyróżniające** – obraz reprezentujący wpis
5. Kliknąć **„Publikuj"** lub **„Zapisz wersję roboczą"**

### 4.2. Edycja wpisu

Aby edytować istniejący wpis:

1. Przejść do **Wpisy → Wszystkie wpisy**
2. Odnaleźć wpis na liście
3. Kliknąć w tytuł lub przycisk **„Edytuj"**
4. Wprowadzić zmiany
5. Kliknąć **„Aktualizuj"**

### 4.3. Kategorie i tagi

#### Kategorie
Kategorie służą do organizacji wpisów w główne grupy tematyczne.

**Zarządzanie kategoriami:**
1. Wybrać **Wpisy → Kategorie**
2. Wprowadzić:
   - **Nazwę** kategorii
   - **Slug** (nazwa w adresie URL)
   - **Opis** (opcjonalnie)
   - **Kategorię nadrzędną** (dla hierarchii)
3. Kliknąć **„Dodaj nową kategorię"**

#### Tagi
Tagi stanowią bardziej szczegółowe słowa kluczowe opisujące treść wpisu.

**Dodawanie tagów:**
- Podczas edycji wpisu w prawym panelu wprowadzić tagi w polu **„Tagi"**
- Można dodać wiele tagów oddzielając je przecinkami

### 4.4. Zdjęcie wyróżniające

Zdjęcie wyróżniające to główny obraz reprezentujący wpis, wyświetlany na listach i w archiwach.

**Ustawianie zdjęcia wyróżniającego:**
1. W prawym panelu edycji wpisu znaleźć sekcję **„Zdjęcie wyróżniające"**
2. Kliknąć **„Ustaw zdjęcie wyróżniające"**
3. Wybrać obraz z biblioteki mediów lub przesłać nowy
4. Kliknąć **„Ustaw zdjęcie wyróżniające"**

**Zalecane wymiary:** Zgodnie z wytycznymi w załączniku 13.3

---

## 5. Menu restauracyjne

System umożliwia zarządzanie menu restauracyjnymi poprzez dedykowane typy wpisów (Custom Post Types).

### 5.1. Zarządzanie kategoriami menu

Kategorie menu służą do grupowania pozycji (np. Przystawki, Dania główne, Desery, Napoje).

#### Tworzenie kategorii menu:

1. W menu bocznym wybrać **Menu → Kategorie**
2. Wypełnić formularz:
   - **Nazwa** – nazwa kategorii (np. „Przystawki")
   - **Slug** – wersja URL (generowana automatycznie)
   - **Opis** – opcjonalny opis kategorii
3. Kliknąć **„Dodaj nową Kategoria"**

#### Dodawanie zdjęcia do kategorii:

1. Po utworzeniu kategorii przejść do listy kategorii
2. Kliknąć **„Edytuj"** przy wybranej kategorii
3. Przewinąć do sekcji **„Zdjęcie"**
4. Kliknąć **„Dodaj zdjęcie"** i wybrać obraz z biblioteki
5. Kliknąć **„Aktualizuj"**

### 5.2. Dodawanie całych menu

Menu reprezentuje kompletny zestaw pozycji (np. „Menu letnie", „Menu świąteczne").

#### Tworzenie nowego menu:

1. Wybrać **Menu → Dodaj nowe menu**
2. Wprowadzić tytuł menu (np. „Menu obiadowe")
3. Ustawić **Zdjęcie wyróżniające** – obraz reprezentujący menu
4. Wypełnić pola dodatkowe:
   - **Zewnętrzny odnośnik do menu** – URL do pliku PDF z menu (wymagane)
   - **Nowe** – zaznaczyć, jeśli menu ma być oznaczone jako nowość
5. Przypisać do **Kategorii menu**
6. Kliknąć **„Publikuj"**

**Uwaga:** Pole „Zewnętrzny odnośnik do menu" jest wymagane. W przypadku braku zewnętrznego pliku należy pozostawić pusty URL lub skontaktować się z administratorem.

### 5.3. Pozycje menu (Menu Item)

Pozycje menu to pojedyncze dania dostępne w ofercie restauracyjnej.

#### Dodawanie pozycji menu:

1. Wybrać **Pozycje Menu → Dodaj nową pozycję menu**
2. Wprowadzić tytuł dania (nazwa pozycji)
3. Ustawić **Zdjęcie wyróżniające** – fotografia dania
4. Wypełnić pola dodatkowe:
   - **Tytuł - Label** – alternatywna nazwa lub etykieta (opcjonalnie)
   - **Krótki opis** – opis składników lub sposobu przygotowania
   - **Cena** – cena dania (np. „45 zł")
5. W sekcji **„Porządek"** ustawić kolejność wyświetlania (niższe numery = wyższa pozycja)
6. Kliknąć **„Publikuj"**

**Zarządzanie kolejnością:**
- Możliwe użycie wtyczki **Post Types Order** do zmiany kolejności poprzez przeciąganie elementów

---

## 6. Oferty pracy (Kariera)

System umożliwia zarządzanie ofertami pracy jako osobny typ wpisów.

### 6.1. Dodawanie oferty pracy

Procedura tworzenia nowej oferty:

1. W menu bocznym wybrać **Oferty pracy → Dodaj Oferta pracy**
2. Wprowadzić tytuł stanowiska (np. „Kelner/Kelnerka")
3. Ustawić **Zdjęcie wyróżniające** – grafika związana z ofertą
4. W edytorze dodać szczegółowy opis oferty (zakres obowiązków, wymagania, benefity)
5. Wypełnić pola dodatkowe (szczegóły w sekcji 6.3)
6. Kliknąć **„Publikuj"**

### 6.2. Edycja treści oferty (Gutenberg)

Treść oferty pracy tworzy się przy użyciu edytora Gutenberg. Zalecana struktura:

1. **Nagłówek sekcji** (blok Heading) – np. „Zakres obowiązków"
2. **Lista** (blok List) – punktowane obowiązki
3. **Nagłówek sekcji** – np. „Wymagania"
4. **Lista** – wymagania wobec kandydata
5. **Nagłówek sekcji** – np. „Oferujemy"
6. **Lista** – benefity i warunki pracy

### 6.3. Ustawienia oferty

W prawym panelu dostępne są następujące pola dedykowane:

- **Lokalizacja** – miejsce pracy (np. „Warszawa, ul. Przykładowa 1")
- **Typ zatrudnienia** – forma zatrudnienia (np. „Umowa o pracę", „Pełny etat")
- **Wynagrodzenie** – widełki płacowe (np. „4500 - 6000 zł brutto")
- **Wynagrodzenie - label** – dodatkowa etykieta (np. „+ premie")
- **Odnośnik do oferty pracy** – link do zewnętrznego systemu aplikacyjnego lub formularza

**Ustawienia linku:**
1. Kliknąć **„Dodaj link"**
2. Wypełnić:
   - **URL** – adres docelowy
   - **Tekst linku** – np. „Aplikuj teraz"
   - **Otwieraj w nowej karcie** – zaznaczyć, jeśli dotyczy

### 6.4. Publikowanie oferty

Po uzupełnieniu wszystkich danych:

1. Sprawdzić poprawność wprowadzonych informacji
2. Kliknąć **„Publikuj"**

**Wycofanie oferty:**
- Nie należy usuwać oferty
- Zmienić status na **„Wersja robocza"** lub **„Prywatne"**

---

## 7. Biblioteka mediów

Biblioteka mediów stanowi centralne repozytorium wszystkich plików graficznych i multimedialnych używanych na stronie.

### 7.1. Dodawanie plików (obrazy, wideo)

#### Przesyłanie nowych plików:

1. W menu bocznym wybrać **Media → Biblioteka**
2. Kliknąć **„Dodaj nowy plik"**
3. Wybrać jedną z metod:
   - **Przeciągnij i upuść** – przeciągnąć pliki do okna przeglądarki
   - **Wybierz pliki** – kliknąć przycisk i wybrać z dysku
4. Poczekać na zakończenie przesyłania
5. Uzupełnić metadane (szczegóły w sekcji 7.3)

**Obsługiwane formaty:**
- Obrazy: JPG, PNG, GIF, WebP, SVG
- Wideo: MP4
- Dokumenty: PDF

**Ograniczenia:**
- Maksymalny rozmiar pliku zależy od konfiguracji serwera (zazwyczaj 64 MB)

### 7.2. Organizacja mediów

Biblioteka umożliwia filtrowanie i wyszukiwanie plików:

- **Widok siatki/lista** – przełączanie widoku w prawym górnym rogu
- **Filtry** – filtrowanie po typie pliku (obrazy, audio, wideo, dokumenty)
- **Wyszukiwanie** – pole wyszukiwania w prawym górnym rogu
- **Sortowanie** – po dacie przesłania

**Uwaga:** WordPress nie posiada natywnego systemu folderów. Organizacja odbywa się poprzez odpowiednie nazewnictwo plików.

### 7.3. Edycja informacji o plikach

#### Uzupełnianie metadanych obrazu:

1. Kliknąć na wybrany plik w bibliotece
2. W prawym panelu uzupełnić:
   - **Tekst alternatywny (Alt Text)** – opis obrazu dla czytników ekranu (ważne dla SEO i dostępności)
   - **Tytuł** – nazwa pliku
   - **Podpis** – opcjonalny podpis wyświetlany pod obrazem
   - **Opis** – szczegółowy opis (użycie wewnętrzne)
3. Kliknąć **„Aktualizuj"**

**Zalecenia:**
- Zawsze uzupełniać pole **„Tekst alternatywny"**
- Używać opisowych nazw plików przed przesłaniem (np. `menu-letnie-2025.jpg` zamiast `IMG_1234.jpg`)

### 7.4. Optymalizacja obrazów

Przed przesłaniem obrazów zaleca się:

1. **Kompresję** – zmniejszenie rozmiaru pliku bez utraty jakości (narzędzia: TinyPNG, ImageOptim)
2. **Odpowiednie wymiary** – przesyłanie obrazów w rozmiarze zbliżonym do docelowego (patrz załącznik 13.3)
3. **Format WebP** – nowoczesny format oferujący lepszą kompresję (jeśli obsługiwany)

**Uwaga:** WordPress automatycznie generuje wiele wersji przesłanego obrazu w różnych rozmiarach.

---

## 8. Zarządzanie formularzami (Fluent Forms)

System wykorzystuje wtyczkę **Fluent Forms** do tworzenia i zarządzania formularzami kontaktowymi, aplikacyjnymi i innymi.

### 8.1. Przegląd formularzy

#### Dostęp do listy formularzy:

1. W menu bocznym wybrać **Fluent Forms → Wszystkie formularze**
2. Wyświetla się lista wszystkich formularzy z następującymi informacjami:
   - Nazwa formularza
   - Shortcode (kod do wstawienia)
   - Liczba zgłoszeń
   - Data utworzenia
   - Status

#### Status i statystyki:

Dla każdego formularza dostępne są:
- **Całkowita liczba zgłoszeń**
- **Nieprzeczytane wpisy**
- **Współczynnik konwersji** (jeśli włączona analityka)

### 8.2. Tworzenie nowego formularza

#### Rozpoczęcie tworzenia formularza:

1. Wybrać **Fluent Forms → Dodaj nowy formularz**
2. Wybrać metodę tworzenia:
   - **Od podstaw** – pusty formularz
   - **Użycie szablonu** – gotowe wzory (kontakt, rejestracja, ankieta, aplikacja o pracę, itp.)
3. Wprowadzić nazwę formularza
4. Kliknąć **„Utwórz formularz"**

#### Kreator formularzy:

Po utworzeniu otwiera się edytor formularza składający się z:
- **Panel pól** (lewy) – dostępne typy pól
- **Obszar roboczy** (środek) – budowa formularza
- **Panel ustawień** (prawy) – konfiguracja wybranego pola

### 8.3. Edytor formularza

#### Interfejs edytora:

Edytor formularza składa się z zakładek:
1. **Edytor** – budowa struktury formularza
2. **Ustawienia i integracje** – konfiguracja formularza
3. **Email Notifications** – powiadomienia e-mail
4. **Wpisy** – lista zgłoszeń

#### Panel pól (lewy):

Dostępne kategorie pól:
- **Podstawowe pola** – najczęściej używane
- **Zaawansowane pola** – pola specjalistyczne
- **Kontenery** – sekcje i kolumny

#### Podgląd na żywo:

Zmiany w formularzu są natychmiast widoczne w obszarze roboczym. W prawym górnym rogu dostępny jest przycisk **„Podgląd"** otwierający formularz w nowym oknie.

### 8.4. Pola formularza

#### Pola tekstowe

**Input (Pole tekstowe)**
- Zastosowanie: krótkie odpowiedzi (imię, nazwisko, miasto)
- Ustawienia:
  - Etykieta pola
  - Placeholder (tekst podpowiedzi)
  - Wartość domyślna
  - Wymagane (tak/nie)
  - Typ walidacji (email, liczba, URL)

**Textarea (Pole tekstowe wieloliniowe)**
- Zastosowanie: dłuższe wiadomości
- Ustawienia:
  - Etykieta
  - Liczba wierszy
  - Maksymalna liczba znaków
  - Wymagane

**Email**
- Zastosowanie: adresy e-mail (automatyczna walidacja)
- Ustawienia:
  - Etykieta
  - Placeholder
  - Wymagane
  - Potwierdzenie adresu (drugie pole weryfikacyjne)

#### Pola wyboru

**Select (Lista rozwijana)**
- Zastosowanie: wybór jednej opcji z listy
- Ustawienia:
  - Etykieta
  - Lista opcji (każda w nowej linii)
  - Wartość domyślna
  - Wymagane
  - Możliwość wyszukiwania (searchable)

**Radio Buttons (Przyciski opcji)**
- Zastosowanie: wybór jednej opcji (widoczne wszystkie)
- Ustawienia:
  - Etykieta
  - Lista opcji
  - Domyślnie zaznaczona opcja
  - Układ (pionowy/poziomy)

**Checkbox (Pola wyboru)**
- Zastosowanie: wybór wielu opcji lub zgody
- Ustawienia:
  - Etykieta
  - Lista opcji
  - Domyślnie zaznaczone
  - Układ

#### Pola zaawansowane

**Upload (Przesyłanie plików)**
- Zastosowanie: CV, portofolio, dokumenty
- Ustawienia:
  - Etykieta
  - Dozwolone formaty plików
  - Maksymalny rozmiar pliku
  - Maksymalna liczba plików
  - Wymagane

**Date Picker (Wybór daty)**
- Zastosowanie: rezerwacje, terminy
- Ustawienia:
  - Etykieta
  - Format daty
  - Zakres dat (min/max)
  - Dni wyłączone (np. weekendy)

**Rating (Ocena gwiazdkowa)**
- Zastosowanie: ankiety, opinie
- Ustawienia:
  - Etykieta
  - Liczba gwiazdek (1-10)
  - Ikona (gwiazdki, serca, itp.)

**Number (Pole numeryczne)**
- Zastosowanie: liczby (wiek, ilość, kod pocztowy)
- Ustawienia:
  - Etykieta
  - Minimalna wartość
  - Maksymalna wartość
  - Krok (dla przycisków +/-)

**Phone (Numer telefonu)**
- Zastosowanie: numery telefonów (z walidacją międzynarodową)
- Ustawienia:
  - Etykieta
  - Format (krajowy/międzynarodowy)
  - Domyślny kraj
  - Wymagane

#### Walidacja pól

Dla każdego pola można ustawić:
- **Wymagane** – pole musi być wypełnione
- **Komunikat błędu** – własna treść przy nieprawidłowym wypełnieniu
- **Wzorzec walidacji** – wyrażenie regularne (zaawansowane)

**Dostępne walidacje:**
- Email
- URL
- Liczba
- Kod pocztowy
- Nr telefonu
- Własny wzorzec

#### Logika warunkowa

Logika warunkowa pozwala pokazywać/ukrywać pola w zależności od odpowiedzi.

**Konfiguracja logiki warunkowej:**
1. Wybrać pole, które ma być warunkowe
2. W prawym panelu aktywować **„Enable Conditional Logic"**
3. Ustawić reguły:
   - **Pokaż to pole jeśli** / **Ukryj to pole jeśli**
   - Wybrać pole źródłowe
   - Wybrać operator (równe, różne, zawiera, itp.)
   - Wprowadzić wartość
4. Dodać kolejne warunki (AND/OR)

**Przykład:**
Pole „Numer ewidencyjny" pokaże się tylko gdy w polu „Posiadasz doświadczenie?" wybrano „Tak".

### 8.5. Ustawienia formularza

Po zbudowaniu struktury należy skonfigurować ustawienia ogólne.

#### Dostęp do ustawień:

1. W edytorze formularza kliknąć zakładkę **„Ustawienia i integracje"**
2. Dostępne sekcje:
   - General Settings
   - Form Settings
   - Confirmation Settings

#### Ustawienia ogólne (General Settings):

- **Nazwa formularza** – nazwa wewnętrzna
- **Opis** – notatka dla administratorów

#### Form Settings:

- **Tekst przycisku wysyłki** – np. „Wyślij wiadomość", „Aplikuj", „Zapisz się"
- **Label Placement** – położenie etykiet pól (górne/lewe)
- **Pomocy Help Message** – dodatkowe instrukcje nad formularzem
- **Ograniczenia wysyłki:**
  - Limit zgłoszeń (max liczba)
  - Zakres dat (tylko w określonym okresie)
  - Wymóg zalogowania

#### Tekst przycisku wysyłki:

Dostosowanie tekstu przycisku:
1. Rozwinąć sekcję **„Submit Button Settings"**
2. Zmienić wartość w polu **„Button Text"**
3. Opcjonalnie: zmienić **„Processing Text"** (tekst podczas wysyłania)

#### Ochrona antyspamowa:

Dostępne metody zabezpieczenia:
- **reCAPTCHA v2** – wymaga konfiguracji kluczy API
- **reCAPTCHA v3** – niewidoczne dla użytkownika
- **hCaptcha** – alternatywa dla reCAPTCHA
- **Honeypot** – ukryte pole wykrywające boty (zalecane, bez konfiguracji)

**Aktywacja Honeypot:**
1. Przejść do **Settings → General Settings**
2. Włączyć **„Enable Honeypot Protection"**

### 8.6. Powiadomienia email

System umożliwia automatyczne wysyłanie powiadomień po złożeniu formularza.

#### Konfiguracja powiadomień administratora:

1. Przejść do zakładki **„Email Notifications"**
2. Kliknąć **„Add Notification"** lub edytować istniejące
3. Wypełnić formularz powiadomienia:
   - **Notification Name** – nazwa wewnętrzna
   - **Send To Email Address** – adres(y) odbiorcy (można użyć zmiennych)
   - **Email Subject** – tytuł wiadomości
   - **Email Body** – treść powiadomienia

#### Personalizacja treści email:

W polach treści można używać **zmiennych dynamicznych** (Smart Codes):

**Najczęściej używane zmienne:**
- `{inputs.nazwa_pola}` – wartość konkretnego pola
- `{all_data}` – wszystkie dane z formularza w formacie tabeli
- `{submission.id}` – numer zgłoszenia
- `{date}` – data wysłania
- `{submission.admin_url}` – link do zgłoszenia w panelu

**Przykład treści email:**
```
Nowe zgłoszenie z formularza kontaktowego:

Imię i nazwisko: {inputs.full_name}
Email: {inputs.email}
Telefon: {inputs.phone}

Wiadomość:
{inputs.message}

---
Data zgłoszenia: {date}
Numer zgłoszenia: {submission.id}
```

#### Ustawienia zaawansowane powiadomień:

- **From Name** – nazwa nadawcy
- **From Email** – adres nadawcy
- **Reply To** – adres odpowiedzi (można ustawić email użytkownika: `{inputs.email}`)
- **CC** – dodatkowi odbiorcy (kopia)
- **BCC** – ukryci odbiorcy (ukryta kopia)

#### Załączniki:

Możliwe dołączanie:
- Plików przesłanych przez użytkownika (z pola Upload)
- Plików z serwera (ścieżka bezwzględna)

**Załączanie przesłanych plików:**
1. W sekcji **„Attachments"** kliknąć **„Add Attachment"**
2. Wybrać **„File Upload Field"**
3. Wybrać pole typu Upload z formularza

### 8.7. Potwierdzenia

Potwierdzenia definiują, co widzi użytkownik po wysłaniu formularza.

#### Typy potwierdzeń:

1. **Wiadomość tekstowa** (Message) – wyświetlenie komunikatu
2. **Przekierowanie** (Redirect) – przeniesienie na inną stronę
3. **Strona** (Page) – przekierowanie na konkretną stronę WordPress

#### Konfiguracja potwierdzenia:

1. W zakładce **„Ustawienia i integracje"** rozwinąć **„Confirmation Settings"**
2. Wybrać typ potwierdzenia
3. Skonfigurować szczegóły

#### Wiadomość potwierdzająca (Message):

- Wprowadzić treść komunikatu (obsługa HTML)
- Przykład: „Dziękujemy za wysłanie wiadomości. Odpowiemy w ciągu 24 godzin."
- Można użyć zmiennych dynamicznych

#### Przekierowanie po wysłaniu (Redirect):

- Wprowadzić pełny URL strony docelowej
- Przykład: `https://domena.pl/dziekujemy`
- Można przekazać dane w URL (query string)

#### Przekierowanie na stronę WordPress (Page):

- Wybrać stronę z listy rozwijanej
- System automatycznie przekieruje na wybraną stronę

#### Autoresponder dla użytkownika:

Automatyczna wiadomość wysyłana do użytkownika po złożeniu formularza.

**Konfiguracja autoresponderu:**
1. W zakładce **„Email Notifications"** kliknąć **„Add Notification"**
2. W polu **„Send To Email Address"** wpisać: `{inputs.email}`
3. Uzupełnić:
   - **Email Subject** – np. „Potwierdzenie otrzymania wiadomości"
   - **Email Body** – treść potwierdzenia dla użytkownika
4. Zapisać powiadomienie

**Przykładowa treść autoresponderu:**
```
Dzień dobry {inputs.first_name},

Dziękujemy za skontaktowanie się z nami. Twoja wiadomość została odebrana.

Postaramy się odpowiedzieć w ciągu 24 godzin.

Twoja wiadomość:
{inputs.message}

---
Ten email został wygenerowany automatycznie. Prosimy nie odpowiadać.
```

### 8.8. Integracje

Fluent Forms obsługuje integracje z zewnętrznymi serwisami.

#### Dostępne integracje:

- **Newsletter** – MailChimp, Mailster, GetResponse, itp.
- **CRM** – Salesforce, HubSpot, Zoho
- **Webhooks** – własne integracje
- **Google Sheets** – zapis danych do arkusza
- **Slack** – powiadomienia na kanale
- **ActiveCampaign**
- **ConvertKit**

#### Konfiguracja integracji newsletter:

Przykład dla MailChimp:

1. W zakładce **„Ustawienia i integracje"** kliknąć **„Marketing & CRM Integrations"**
2. Wybrać **MailChimp** i kliknąć **„Add Integration"**
3. Wprowadzić klucz API (pobrany z konta MailChimp)
4. Wybrać listę subskrybentów
5. Zmapować pola formularza z polami MailChimp:
   - Email → Email
   - First Name → Imię
   - Last Name → Nazwisko
6. Opcjonalnie: włączyć **„Double Opt-in"** (podwójne potwierdzenie)
7. Zapisać integrację

#### Webhooks:

Webhooks pozwalają wysyłać dane formularza do zewnętrznych systemów.

**Konfiguracja webhooka:**
1. W sekcji integracji wybrać **„WebHooks"**
2. Kliknąć **„Add Webhook"**
3. Wprowadzić:
   - **Webhook URL** – adres endpointa API
   - **Request Method** – GET/POST/PUT
   - **Request Format** – JSON/Form Data
4. Zmapować pola
5. Zapisać

### 8.9. Zarządzanie wpisami

Wszystkie zgłoszenia z formularzy są zapisywane w bazie danych.

#### Przeglądanie zgłoszeń:

1. Wybrać **Fluent Forms → Wszystkie formularze**
2. Kliknąć **„Wpisy"** przy wybranym formularzu
3. Wyświetla się lista wszystkich zgłoszeń

#### Szczegóły zgłoszenia:

Po kliknięciu w zgłoszenie wyświetlane są:
- Wszystkie wprowadzone dane
- Data i godzina wysłania
- IP użytkownika (jeśli włączone)
- User Agent (przeglądarka)
- Notatki (możliwość dodania komentarza przez administratora)

#### Eksport danych:

Możliwy eksport zgłoszeń do:
- **CSV** – arkusz kalkulacyjny
- **Excel** – format XLSX
- **JSON** – format developerski

**Procedura eksportu:**
1. Na liście wpisów kliknąć **„Export"** (u góry)
2. Wybrać format
3. Wybrać zakres dat (opcjonalnie)
4. Wybrać pola do eksportu
5. Kliknąć **„Eksportuj"**

#### Filtrowanie i wyszukiwanie:

Dostępne opcje:
- **Wyszukiwanie** – pole w prawym górnym rogu
- **Filtr po dacie** – zakres czasowy
- **Filtr po statusie** – przeczytane/nieprzeczytane
- **Zaawansowane filtry** – według wartości konkretnych pól

#### Oznaczanie i zarządzanie:

Możliwe akcje:
- Oznacz jako przeczytane/nieprzeczytane
- Dodaj notatkę
- Oznacz gwiazdką (ważne)
- Usuń zgłoszenie

**Masowe operacje:**
1. Zaznaczyć checkboxy przy zgłoszeniach
2. Wybrać akcję z menu rozwijanego **„Bulk Actions"**
3. Kliknąć **„Zastosuj"**

### 8.10. Kopiowanie shortcode

Każdy formularz posiada unikalny shortcode umożliwiający wstawienie go na stronie.

#### Pobieranie kodu formularza:

1. Przejść do **Fluent Forms → Wszystkie formularze**
2. W kolumnie **„Shortcode"** znajdować się będzie kod formularza w formacie:
   ```
   [fluentform id="1"]
   ```
3. Kliknąć w kod, aby go skopiować

#### Wstawianie na stronie:

**Metoda 1: Blok ContactForm**
1. Edytować stronę
2. Dodać blok **„Contact Form"**
3. W polu **„Shortcode formularza"** wkleić skopiowany kod
4. Zaktualizować stronę

**Metoda 2: Blok Shortcode WordPress**
1. Edytować stronę
2. Dodać blok **„Shortcode"**
3. Wkleić kod formularza
4. Zaktualizować stronę

**Metoda 3: Widget**
- Możliwe dodanie formularza do stopki lub sidebaru poprzez widget **„Fluent Forms Widget"**

---

## 9. Menu nawigacyjne

Menu nawigacyjne to struktury linków wykorzystywane w nagłówku, stopce i innych miejscach strony.

### 9.1. Tworzenie menu nawigacyjnego

Procedura tworzenia nowego menu:

1. W menu bocznym wybrać **Wygląd → Menu**
2. W górnej części strony kliknąć **„utwórz nowe menu"**
3. Wprowadzić nazwę menu (np. „Menu główne", „Menu stopki")
4. Kliknąć **„Utwórz menu"**

### 9.2. Dodawanie elementów do menu

#### Typy elementów menu:

W lewym panelu dostępne są:
- **Strony** – linki do stron WordPress
- **Wpisy** – linki do wpisów
- **Własne odnośniki** – dowolne URL
- **Kategorie** – linki do archiwów kategorii
- **Tagi** – linki do archiwów tagów
- **Typy niestandardowe** – Menu, Oferty pracy, itp.

#### Dodawanie strony do menu:

1. Rozwinąć sekcję **„Strony"**
2. Zaznaczyć checkboxy przy stronach do dodania
3. Kliknąć **„Dodaj do menu"**
4. Strony pojawią się w strukturze menu

#### Dodawanie własnego odnośnika:

1. Rozwinąć sekcję **„Własne odnośniki"**
2. Wypełnić:
   - **URL** – adres docelowy (np. `https://facebook.com/strona`)
   - **Tekst odnośnika** – nazwa wyświetlana w menu
3. Kliknąć **„Dodaj do menu"**

### 9.3. Struktura hierarchiczna

Menu może posiadać strukturę wielopoziomową (menu rozwijane).

#### Tworzenie podmenu:

1. Przeciągnąć element menu lekko w prawo pod element nadrzędny
2. Element stanie się podmenu (wcięcie wskazuje hierarchię)
3. Możliwe tworzenie wielu poziomów zagnieżdżenia

**Uwaga:** Niektóre motywy obsługują tylko 1-2 poziomy podmenu.

#### Zmiana kolejności:

- Przeciągać elementy w górę/dół, aby zmienić kolejność
- Przeciągać w lewo/prawo, aby zmienić poziom hierarchii

#### Edycja elementu menu:

1. Kliknąć strzałkę w prawym górnym rogu elementu
2. Edytować:
   - **Etykieta nawigacji** – tekst wyświetlany w menu
   - **Atrybut tytułu** – tooltip (opcjonalnie)
   - **Klasy CSS** – własne klasy (zaawansowane)
   - **Relacja linku (XFN)** – relacje semantyczne (rzadko używane)
   - **Otwieraj w nowej karcie** – checkbox
3. Kliknąć **„Zapisz menu"**

### 9.4. Przypisywanie menu do lokalizacji

Motyw definiuje lokalizacje, w których mogą być wyświetlane menu.

#### Dostępne lokalizacje:

Zazwyczaj dostępne:
- **Primary Navigation** – menu główne (nagłówek)
- **Footer Navigation** – menu w stopce

#### Przypisanie menu:

1. Po utworzeniu menu rozwinąć sekcję **„Ustawienia menu"** (u dołu)
2. Zaznaczyć checkboxy przy lokalizacjach (można wybrać wiele)
3. Kliknąć **„Zapisz menu"**

**Alternatywna metoda:**
1. Wybrać **Wygląd → Menu**
2. Przejść do zakładki **„Zarządzaj lokalizacjami"**
3. Dla każdej lokalizacji wybrać menu z listy rozwijanej
4. Kliknąć **„Zapisz zmiany"**

---

## 10. Ustawienia motywu

Ustawienia motywu to dedykowana strona opcji umożliwiająca konfigurację elementów globalnych witryny.

**Dostęp:** W menu bocznym wybrać **Ustawienia motywu**

Ustawienia podzielone są na zakładki tematyczne.

### 10.1. Nagłówek

Zakładka **„Nagłówek"** zawiera ustawienia górnej części strony.

#### Dostępne opcje:

**Logo w nagłówku:**
1. Kliknąć **„Dodaj zdjęcie"** w polu **„Logo"**
2. Wybrać obraz z biblioteki mediów lub przesłać nowy
3. Zalecany format: PNG z przezroczystym tłem
4. Zalecane wymiary: zgodnie z załącznikiem 13.3

**Przycisk rezerwacji:**
1. Kliknąć **„Dodaj link"** w polu **„Przycisk rezerwacji"**
2. Wypełnić:
   - **URL** – adres strony rezerwacji
   - **Tekst linku** – np. „Zarezerwuj stolik"
   - **Otwieraj w nowej karcie** – zaznaczyć, jeśli dotyczy
3. Kliknąć **„Aktualizuj link"**

Po uzupełnieniu kliknąć **„Zapisz zmiany"** (u góry strony).

### 10.2. Stopka

Zakładka **„Stopka"** zawiera ustawienia dolnej części strony.

#### Dostępne opcje:

**Logo w stopce:**
- Procedura analogiczna jak dla logo w nagłówku
- Może być to ten sam lub inny obraz (np. wersja jasna/ciemna)

**Logotypy partnerów:**
1. Kliknąć **„Dodaj do galerii"** w polu **„Logotypy"**
2. Wybrać maksymalnie 4 obrazy
3. Ustawić kolejność przeciągając miniatury
4. Kliknąć **„Dodaj do galerii"**

**Adresy lokali:**
1. Kliknąć **„Dodaj wiersz"** w sekcji **„Adresy"**
2. W edytorze WYSIWYG wprowadzić:
   - Nazwę lokalu
   - Adres
   - Godziny otwarcia
   - Telefon kontaktowy
3. Możliwe formatowanie tekstu (pogrubienie, kolory)
4. Dodać maksymalnie 4 adresy
5. Zmienić kolejność przeciągając wiersze

**Formularz newslettera:**
1. Utworzyć formularz newslettera w Fluent Forms (rozdział 8)
2. Skopiować shortcode formularza
3. Wkleić w polu **„Formularz newslettera"**
4. Przykład: `[fluentform id="2"]`

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.3. Media społecznościowe

Zakładka **„Media społecznościowe"** służy do zarządzania linkami do profili społecznościowych.

#### Dodawanie profilu społecznościowego:

1. Kliknąć **„Dodaj wiersz"** w sekcji **„Media społecznościowe"**
2. Wypełnić:
   - **Etykieta** – nazwa serwisu (np. „Facebook", „Instagram")
   - **Link** – pełny URL do profilu
   - **Ikona** – przesłać ikonę serwisu (format SVG lub PNG, wymiary: 24×24px lub 32×32px)
3. Dodać kolejne profile
4. Zmienić kolejność przeciągając wiersze

**Zalecane serwisy:**
- Facebook
- Instagram
- Twitter / X
- LinkedIn
- YouTube
- TikTok

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.4. Strona 404

Zakładka **„Strona 404"** pozwala dostosować wygląd strony błędu (gdy adres nie zostanie znaleziony).

#### Dostępne opcje:

**Wideo lub grafika:**

**Opcja 1: Wideo**
1. W polu **„Wideo"** kliknąć **„Dodaj plik"**
2. Przesłać plik wideo w formacie MP4
3. Zalecany rozmiar: do 5 MB (ze względu na szybkość ładowania)

**Opcja 2: Grafika**
1. W polu **„Grafika"** kliknąć **„Dodaj zdjęcie"**
2. Wybrać obraz z biblioteki
3. Zalecany format: PNG lub JPG

**Nagłówek:**
- Wprowadzić tekst wyświetlany na stronie błędu
- Przykład: „Ups! Nie ma takiej strony"

**Przycisk:**
1. Kliknąć **„Dodaj link"** w polu **„Przycisk"**
2. Wypełnić:
   - **URL** – zazwyczaj link do strony głównej (`/`)
   - **Tekst linku** – np. „Wróć do strony głównej"
3. Kliknąć **„Aktualizuj link"**

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.5. Rezerwacje

Zakładka **„Rezerwacja"** umożliwia zarządzanie linkami do systemów rezerwacyjnych.

#### Dodawanie linku rezerwacji:

1. Kliknąć **„Dodaj link"** w sekcji **„Linki rezerwacji"**
2. Wypełnić:
   - **Etykieta** – nazwa restauracji lub typu rezerwacji (np. „Aioli Centrum", „Rezerwuj catering")
   - **Link** – pełny URL do systemu rezerwacji (np. BookIt, TheFork, własna strona)
3. Dodać kolejne linki (jeśli więcej niż jeden lokal)
4. Zmienić kolejność przeciągając wiersze

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.6. Archiwum

Zakładka **„Archiwum"** pozwala wybrać strony pełniące funkcję archiwów.

#### Dostępne opcje:

**Archiwum wpisów:**
1. Kliknąć w polu **„Archiwum wpisów"**
2. Wybrać stronę z listy rozwijanej
3. Wybrana strona będzie pełnić rolę archiwum bloga/aktualności

**Archiwum ofert pracy:**
1. Kliknąć w polu **„Archiwum ofert pracy"**
2. Wybrać stronę z listy rozwijanej
3. Wybrana strona będzie wyświetlać wszystkie oferty pracy

**Uwaga:** Wybrane strony powinny być pustymi stronami utworzonymi specjalnie w tym celu. System automatycznie wygeneruje na nich listę wpisów/ofert.

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.7. Listy

Zakładki **„Lista wpisów"** i **„Lista ofert pracy"** umożliwiają wybór bloków wielokrotnego użytku wyświetlanych w archiwach.

#### Lista wpisów:

1. Przejść do zakładki **„Lista wpisów"**
2. W polu **„Listing wpisów"** wybrać blok wielokrotnego użytku (Reusable Block)
3. Wybrany blok będzie wyświetlany na stronie archiwum wpisów

#### Lista ofert pracy:

1. Przejść do zakładki **„Lista ofert pracy"**
2. W polu **„Listing ofert pracy"** wybrać blok wielokrotnego użytku
3. Wybrany blok będzie wyświetlany na stronie archiwum ofert

**Uwaga:** Bloki wielokrotnego użytku należy najpierw utworzyć (szczegóły w rozdziale 11).

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.8. Pojedyncza oferta pracy

Zakładka **„Pojedyncza oferta pracy"** pozwala wybrać bloki wyświetlane na stronie szczegółów oferty.

#### Dostępne opcje:

**Blok CTA:**
1. W polu **„Blok CTA"** wybrać blok wielokrotnego użytku
2. Blok będzie wyświetlany na dole każdej oferty pracy
3. Zazwyczaj zawiera wezwanie do aplikowania

**Blok referencji:**
1. W polu **„Blok referencji"** wybrać blok wielokrotnego użytku
2. Blok może zawierać opinie pracowników lub informacje o firmie
3. Wyświetlany na dole oferty

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

### 10.9. Kody niestandardowe

Zakładka **„Kody niestandardowe"** umożliwia wstawienie własnych skryptów (np. Google Analytics, Facebook Pixel, chat).

**Dostępne lokalizacje:**

#### Kod przed zamknięciem `</head>`:
1. Rozwinąć sekcję **„Kod przed zamknięciem </head>"**
2. Włączyć przełącznik **„Włącz kod"**
3. W polu tekstowym wkleić kod HTML/JavaScript
4. Kod zostanie wstawiony przed tagiem `</head>` (zalecane dla meta tagów, CSS, analityki)

**Przykład użycia:** Google Analytics, Google Tag Manager, Facebook Pixel

#### Kod po otwarciu `<body>`:
1. Rozwinąć sekcję **„Kod po otwarciu <body>"**
2. Włączyć przełącznik **„Włącz kod"**
3. Wkleić kod
4. Kod zostanie wstawiony zaraz po tagu `<body>` (zalecane dla Google Tag Manager noscript)

#### Kod przed zamknięciem `</body>`:
1. Rozwinąć sekcję **„Kod przed zamknięciem </body>"**
2. Włączyć przełącznik **„Włącz kod"**
3. Wkleić kod
4. Kod zostanie wstawiony przed tagiem `</body>` (zalecane dla skryptów JavaScript, chatbotów)

**Przykład użycia:** LiveChat, Intercom, własne skrypty JS

**UWAGA BEZPIECZEŃSTWA:**
- Wstawiać tylko zaufane kody
- Niepoprawny kod może zepsuć działanie strony
- W razie wątpliwości skonsultować się z administratorem

Po uzupełnieniu kliknąć **„Zapisz zmiany"**.

---

## 11. Wielokrotne bloki (Reusable Blocks)

Wielokrotne bloki (Reusable Blocks) to bloki treści, które można wykorzystać w wielu miejscach na stronie.

### 11.1. Tworzenie bloku wielokrotnego użytku

#### Metoda 1: Podczas edycji strony

1. Edytować stronę i zbudować blok treści
2. Kliknąć w blok, aby go zaznaczyć
3. Kliknąć ikonę trzech kropek (⋮) w prawym górnym rogu bloku
4. Wybrać **„Utwórz wzorzec"** (lub **„Add to Reusable blocks"**)
5. Wprowadzić nazwę bloku (np. „CTA - Dołącz do zespołu")
6. Kliknąć **„Zapisz"**

#### Metoda 2: Zarządzanie blokami

1. W menu bocznym wybrać **Wygląd → Edytor** (lub bezpośredni dostęp przez starszy interfejs)
2. Alternatywnie: podczas edycji strony kliknąć ikonę WordPressa (W) → **„Wzorce"** → **„Zarządzaj wzorcami"**
3. Kliknąć **„Utwórz wzorzec"**
4. Zbudować blok przy użyciu edytora Gutenberg
5. Wprowadzić tytuł wzorca
6. Kliknąć **„Publikuj"**

### 11.2. Wykorzystanie bloków w Ustawieniach motywu

Utworzone bloki wielokrotnego użytku można przypisać w Ustawieniach motywu:

**Przykłady zastosowania:**

**Listing wpisów:**
1. Utworzyć blok wielokrotnego użytku zawierający blok **PostListing**
2. Przejść do **Ustawienia motywu → Lista wpisów**
3. W polu **„Listing wpisów"** wybrać utworzony blok
4. Blok będzie automatycznie wyświetlany na stronie archiwum wpisów

**Blok CTA dla ofert pracy:**
1. Utworzyć blok wielokrotnego użytku zawierający blok **CTA** z treścią zachęcającą do aplikowania
2. Przejść do **Ustawienia motywu → Pojedyncza oferta pracy**
3. W polu **„Blok CTA"** wybrać utworzony blok
4. Blok będzie wyświetlany na dole każdej oferty pracy

**Zalety:**
- Zmiana treści w jednym miejscu aktualizuje wszystkie wystąpienia
- Spójność wizualna i treściowa
- Oszczędność czasu

### 11.3. Edycja wielokrotnych bloków

#### Edycja treści bloku:

**Metoda 1: Bezpośrednia edycja**
1. Na stronie, gdzie blok jest używany, kliknąć w blok
2. Wprowadzić zmiany
3. Kliknąć **„Aktualizuj"** – zmiany zostaną zastosowane wszędzie

**Metoda 2: Zarządzanie wzorcami**
1. W edytorze kliknąć ikonę WordPressa (W) → **„Wzorce"** → **„Zarządzaj wzorcami"**
2. Znaleźć blok na liście
3. Kliknąć w nazwę bloku
4. Edytować treść
5. Kliknąć **„Zapisz"**

#### Konwersja na zwykły blok:

Jeśli trzeba zmodyfikować blok tylko w jednym miejscu:

1. Kliknąć w blok wielokrotnego użytku
2. Kliknąć ikonę trzech kropek (⋮)
3. Wybrać **„Odłącz"** (lub **„Convert to regular blocks"**)
4. Blok stanie się zwykłym blokiem i można go edytować niezależnie

#### Usuwanie wielokrotnego bloku:

1. Przejść do **Wzorce → Zarządzaj wzorcami**
2. Najechać na blok do usunięcia
3. Kliknąć **„Usuń"**
4. Potwierdzić usunięcie

**Uwaga:** Usunięcie bloku wielokrotnego użytku nie usunie jego treści z już istniejących stron – treść pozostanie, ale przestanie być synchronizowana.

---

## 12. Najczęstsze problemy i rozwiązania

### 12.1. Problemy z publikowaniem

#### Problem: Nie można opublikować strony – przycisk „Publikuj" jest nieaktywny

**Możliwe przyczyny i rozwiązania:**

1. **Brak tytułu strony**
   - Upewnić się, że pole tytułu jest wypełnione

2. **Błędy walidacji w blokach**
   - Sprawdzić, czy wszystkie wymagane pola w blokach są uzupełnione
   - Zwrócić uwagę na czerwone obramowania bloków wskazujące błędy

3. **Problemy z uprawnieniami**
   - Skontaktować się z administratorem w celu weryfikacji uprawnień użytkownika

4. **Błąd połączenia z serwerem**
   - Odświeżyć stronę (Ctrl+R / Cmd+R)
   - Sprawdzić połączenie internetowe
   - Spróbować ponownie za kilka minut

#### Problem: Strona nie aktualizuje się po zapisaniu

**Rozwiązanie:**

1. Wyczyścić cache przeglądarki:
   - **Chrome:** Ctrl+Shift+Delete (Windows) / Cmd+Shift+Delete (Mac)
   - **Firefox:** Ctrl+Shift+Delete
   - **Safari:** Cmd+Option+E

2. Wymusić odświeżenie strony:
   - Ctrl+F5 (Windows)
   - Cmd+Shift+R (Mac)

3. Sprawdzić w trybie incognito/prywatnym

4. Wyczyścić cache WordPress (jeśli włączona wtyczka cachująca):
   - Skontaktować się z administratorem

### 12.2. Problemy z obrazami

#### Problem: Obraz nie przesyła się do biblioteki mediów

**Możliwe przyczyny i rozwiązania:**

1. **Zbyt duży rozmiar pliku**
   - Sprawdzić limit rozmiaru (zazwyczaj 64 MB)
   - Skompresować obraz przed przesłaniem (TinyPNG.com, Squoosh.app)

2. **Nieobsługiwany format**
   - Upewnić się, że plik jest w formacie: JPG, PNG, GIF, WebP, SVG
   - Konwertować plik do obsługiwanego formatu

3. **Uprawnienia folderów na serwerze**
   - Skontaktować się z administratorem

4. **Problem z połączeniem**
   - Sprawdzić stabilność połączenia internetowego
   - Spróbować ponownie za chwilę

#### Problem: Obraz wyświetla się źle (rozciągnięty, zniekształcony)

**Rozwiązanie:**

1. Sprawdzić proporcje obrazu
2. Przesłać obraz w zalecanych wymiarach (załącznik 13.3)
3. Użyć narzędzi do edycji obrazów (Photoshop, GIMP, Canva) do przycięcia w odpowiednich proporcjach

#### Problem: Brak możliwości edycji obrazu (kadrowanie)

**Rozwiązanie:**

1. W bibliotece mediów kliknąć na obraz
2. Kliknąć przycisk **„Edytuj obraz"**
3. Użyć narzędzia kadrowania
4. Zapisać zmiany

**Uwaga:** Edycja obrazu w WordPress jest ograniczona. Zaleca się edycję w zewnętrznych programach przed przesłaniem.

### 12.3. Problemy z formularzami

#### Problem: Formularz nie wysyła zgłoszeń

**Możliwe przyczyny i rozwiązania:**

1. **Nieprawidłowy shortcode**
   - Sprawdzić, czy shortcode formularza jest poprawnie skopiowany
   - Format: `[fluentform id="X"]` gdzie X to numer formularza
   - Upewnić się, że brak dodatkowych spacji lub znaków

2. **Formularz dezaktywowany**
   - Przejść do **Fluent Forms → Wszystkie formularze**
   - Sprawdzić, czy formularz jest aktywny

3. **Problemy z walidacją pól**
   - Sprawdzić, czy wszystkie wymagane pola są wypełnione
   - Wyłączyć tymczasowo walidację w ustawieniach formularza

4. **Konflikt z ochroną antyspamową**
   - Tymczasowo wyłączyć reCAPTCHA
   - Sprawdzić, czy Honeypot nie blokuje zgłoszeń

#### Problem: Nie przychodzą powiadomienia email

**Rozwiązanie:**

1. Sprawdzić folder SPAM
2. Zweryfikować ustawienia powiadomień w **Email Notifications**
3. Upewnić się, że adres email odbiorcy jest poprawny
4. Sprawdzić, czy powiadomienie jest włączone (przełącznik aktywności)
5. Skontaktować się z administratorem w celu weryfikacji konfiguracji serwera email

#### Problem: Nie można przesłać pliku w formularzu

**Rozwiązanie:**

1. Sprawdzić rozmiar pliku (limit ustawiony w polu Upload)
2. Zweryfikować format pliku (czy jest dozwolony)
3. Zmniejszyć rozmiar pliku
4. Spróbować inny plik testowy

### 12.4. Kontakt z administratorem

W przypadku problemów, których nie można rozwiązać samodzielnie, należy skontaktować się z administratorem systemu.

**Informacje do przekazania:**

1. Dokładny opis problemu
2. Kiedy problem wystąpił (data, godzina)
3. Co było robione przed wystąpieniem problemu
4. Zrzuty ekranu obrazujące problem
5. Przeglądarka i system operacyjny
6. Ewentualny komunikat błędu (pełna treść)

---

## 13. Załączniki

### 13.1. Słowniczek pojęć

**ACF (Advanced Custom Fields)** – wtyczka umożliwiająca tworzenie niestandardowych pól

**Blok** – element treści w edytorze Gutenberg (np. paragraf, obraz, nagłówek)

**CMS (Content Management System)** – system zarządzania treścią

**CPT (Custom Post Type)** – niestandardowy typ wpisu (np. Menu, Oferty pracy)

**CTA (Call to Action)** – wezwanie do działania (przycisk, link zachęcający do akcji)

**Fluent Forms** – wtyczka do tworzenia formularzy kontaktowych

**Gutenberg** – nazwa edytora blokowego w WordPress

**Reusable Block** – blok wielokrotnego użytku (wzorzec)

**Shortcode** – kod w formacie `[nazwa]` umożliwiający wstawienie dynamicznej treści

**Slug** – wersja nazwy przystosowana do użycia w adresie URL (np. „o-nas")

**Taxonomy** – sposób klasyfikacji treści (kategorie, tagi)

**WYSIWYG** – edytor „What You See Is What You Get" (co widzisz, to otrzymasz)

### 13.2. Skróty klawiszowe

#### Windows / Linux:

| Skrót | Akcja |
|-------|-------|
| `Ctrl + S` | Zapisz wersję roboczą |
| `Ctrl + Z` | Cofnij |
| `Ctrl + Shift + Z` | Ponów |
| `Ctrl + C` | Kopiuj |
| `Ctrl + V` | Wklej |
| `Ctrl + B` | Pogrubienie |
| `Ctrl + I` | Kursywa |
| `Ctrl + K` | Wstaw/edytuj link |
| `Ctrl + Shift + K` | Usuń link |
| `/` | Otwórz szybkie wyszukiwanie bloków |

#### macOS:

| Skrót | Akcja |
|-------|-------|
| `Cmd + S` | Zapisz wersję roboczą |
| `Cmd + Z` | Cofnij |
| `Cmd + Shift + Z` | Ponów |
| `Cmd + C` | Kopiuj |
| `Cmd + V` | Wklej |
| `Cmd + B` | Pogrubienie |
| `Cmd + I` | Kursywa |
| `Cmd + K` | Wstaw/edytuj link |
| `Cmd + Shift + K` | Usuń link |
| `/` | Otwórz szybkie wyszukiwanie bloków |

### 13.3. Zalecane rozmiary obrazów

| Element | Wymiary (px) | Proporcje | Format | Uwagi |
|---------|--------------|-----------|--------|-------|
| **Logo nagłówek** | 200×80 | dowolne | PNG | Przezroczyste tło |
| **Logo stopka** | 200×80 | dowolne | PNG | Przezroczyste tło |
| **Hero (tło)** | 1920×1080 | 16:9 | JPG | Kompresja do 200 KB |
| **Zdjęcie wyróżniające (wpis)** | 1200×630 | ~19:10 | JPG | Dla social media |
| **Obrazy w galerii** | 1200×800 | 3:2 | JPG | Kompresja do 150 KB |
| **Menu (zdjęcie dania)** | 800×600 | 4:3 | JPG | Atrakcyjne zdjęcie |
| **Menu (kategoria)** | 600×600 | 1:1 | JPG | Kwadratowy |
| **Slider** | 1600×900 | 16:9 | JPG | Kompresja do 200 KB |
| **Ikony social media** | 32×32 | 1:1 | PNG/SVG | Przezroczyste tło |
| **Logotypy partnerów** | 300×150 | 2:1 | PNG | Przezroczyste tło |
| **Separator z obrazem** | 1920×600 | ~3:1 | JPG | Szeroki format |
| **Grafika 404** | 800×600 | 4:3 | PNG/JPG | Zgodna z identyfikacją |
| **Wideo tło** | 1920×1080 | 16:9 | MP4 | Max 5 MB, H.264 |

**Ogólne wytyczne:**

- **Kompresja:** Używać narzędzi online (TinyPNG, ImageOptim) przed przesłaniem
- **Nazewnictwo:** Stosować opisowe nazwy plików (np. `hero-strona-glowna.jpg` zamiast `IMG_1234.jpg`)
- **Tekst alternatywny:** Zawsze wypełniać pole ALT opisem obrazu
- **Format WebP:** Zalecany dla lepszej kompresji (jeśli obsługiwany)
- **Retina:** Możliwe przesłanie obrazów 2× większych dla ekranów wysokiej rozdzielczości

---

**Koniec instrukcji obsługi**

*Dokument został utworzony w celu ułatwienia pracy z systemem zarządzania treścią. W przypadku wątpliwości lub problemów technicznych należy skontaktować się z administratorem.*