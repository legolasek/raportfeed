# 📦 RaportFeed PRO - Synchronizator Dostępności i Cen Allegro
<img width="1376" height="768" alt="Gemini_Generated_Image_1z41di1z41di1z41" src="https://github.com/user-attachments/assets/cb0318c2-a5e0-499a-95af-ef605f43cceb" />

> **Nowoczesne narzędzie desktopowe PRO do automatycznego monitorowania hurtowni, feedów XML oraz bezpiecznej synchronizacji ofert i cen na Allegro.**

<img width="1918" height="1007" alt="image" src="https://github.com/user-attachments/assets/25a74d03-4a5d-430d-8da2-ed5dfa26cbea" />

---

<img width="1918" height="1008" alt="image" src="https://github.com/user-attachments/assets/8cc99921-1fc8-469c-99a3-e77f34ce362e" />

---

<img width="1919" height="1008" alt="image" src="https://github.com/user-attachments/assets/1c6e0e22-1c15-4993-be3b-4f3c06d7f69f" />

---

<img width="1918" height="1004" alt="image" src="https://github.com/user-attachments/assets/61f75205-f8be-40fe-a80c-992c9623f100" />

---

<img width="1919" height="1002" alt="image" src="https://github.com/user-attachments/assets/97522f2e-77b3-436a-8003-540070333e64" />

---

## 📥 Pobieranie programu

Najnowszą wersję programu pobierzesz w zakładce:
👉 **[Wydania / Releases](../../releases/latest)**

* Pobierz plik `RaportFeed_PawelSteczka.exe`.
* Program jest w wersji przenośnej (**portable**) – nie wymaga instalacji ani zewnętrznych plików.

---

## 🚀 Pierwsze Uruchomienie (Krok po kroku)

### 1. Uruchomienie programu
1. Umieść plik `RaportFeed_PawelSteczka.exe` w dowolnym wygodnym folderze (np. na Pulpicie lub w `C:\RaportFeed`).
2. Uruchom program dwuklikiem.
3. Program wyświetli dynamiczny ekran startowy (Splash Screen), który w czasie rzeczywistym weryfikuje licencję, pobiera pliki XML hurtowni oraz łączy się z Allegro.

> **Uwaga (Windows SmartScreen):** Przy pierwszym uruchomieniu system Windows może wyświetlić niebieski komunikat *„System Windows ochronił ten komputer”* (standard dla nowych plików bez komercyjnego certyfikatu EV). Kliknij **„Więcej informacji”**, a następnie **„Uruchom mimo to”**.

### 2. Aktywacja licencji
* Przy pierwszym starcie program wyświetli okno aktywacji licencji.
* Wklej otrzymany od autora klucz licencyjny (lub wskaż plik `.key` / `.lic`) i kliknij **Aktywuj licencję**.
* Program utworzy plik `license.key` obok aplikacji – kolejne uruchomienia nie będą już wymagały podawania klucza.

### 3. Połączenie z Allegro REST API
1. W menu bocznym przejdź do sekcji **Ustawienia & API** (lub kliknij status Allegro na górnym pasku).
2. Wprowadź dane swojej aplikacji partnerskiej Allegro (`Client ID` oraz `Client Secret`) i kliknij **Zapisz ustawienia**.
3. Kliknij **Zaloguj do Allegro przez przeglądarkę** – program otworzy oficjalną stronę logowania Allegro, gdzie potwierdzisz dostęp jednym kliknięciem.

---

## 🛡️ Bezpieczeństwo i Kluczowe Funkcje

Program został zaprojektowany ze szczególnym naciskiem na eliminację kosztownych pomyłek magazynowych i cenowych:

* ⚡ **Pasek postępu synchronizacji na żywo:**
  Podczas wysyłki zmian do Allegro okno wyświetla dynamiczny pasek postępu (0% – 100%), licznik przetworzonych pozycji oraz kartę z podglądem oferty, która w danej sekundzie jest aktualizowana w Allegro API. Proces odbywa się w tle bez zawieszania interfejsu.
* 📦 **Price Drop Guard (Ochrona Zestawów i Wielopaków):**
  Program automatycznie wykrywa oferty będące zestawami (np. *„2 sztuki”*, *„zestaw”*, *„dwupak”*, *„x2”*). Jeśli w feedzie hurtowni cena dotyczy pojedynczej sztuki, program **nie zaniży ceny zestawu**, dopóki nie zatwierdzisz tego ręcznie lub nie nadasz mnożnika.
* 🖱️ **Menu kontekstowe (PPM):**
  Klikając prawym przyciskiem myszy na dowolną ofertę w tabeli, możesz błyskawicznie ustawić mnożnik (x2, x3, x4) lub całkowicie zablokować zmianę ceny (pozostawiając aktualizację samego stanu magazynowego).
* 📉 **Ochrona przed drastycznymi spadkami cen:**
  Każda zmiana obniżająca cenę o więcej niż **40%** jest oznaczana alertem ostrzegawczym wymagającym weryfikacji.
* ↩️ **Safety Snapshot & Rollback (Cofnięcie zmian):**
  Przed każdą wysyłką tworzona jest kopia bezpieczeństwa. W razie jakiejkolwiek pomyłki po stronie hurtowni możesz **jednym kliknięciem przywrócić poprzednie stany i ceny na Allegro**.
* 🔍 **Wyszukiwarka na żywo (`Ctrl+F`):**
  Błyskawiczne filtrowanie tysięcy pozycji po tytule aukcji, kodzie EAN lub SKU hurtowni.
* 🔄 **Automatyczne Aktualizacje:**
  Aplikacja automatycznie sprawdza dostępność nowej wersji i umożliwia aktualizację jednym kliknięciem.

---

## 📊 Eksport Danych

* **Eksport do Excela (.xlsx):** Przejrzyste, kolorowane zestawienie produktów (dostępne na zielono, braki na czerwono, informacje o przedsprzedaży i datach dostaw).
* **Raporty tekstowe (.txt):** Szybkie zestawienie magazynowe z podziałem na marki (Jan Nowak, Diablo Chairs).

---

## 💻 Wymagania Systemowe

* **System operacyjny:** Windows 10 lub Windows 11 (64-bit)
* **Połączenie internetowe:** Wymagane do pobierania feedów XML oraz komunikacji z Allegro API
* **Brak konieczności instalacji:** Program posiada wbudowane wszystkie niezbędne biblioteki (Edge WebView2 jest standardowo obecny w systemach Windows 10/11).

---

## 📬 Kontakt i Wsparcie

W sprawach przedłużenia licencji, zgłaszania uwag lub zamówienia dedykowanych integracji:

* **Autor:** Paweł Steczka
* **Strona:** [pesteczka.com](https://pesteczka.com)
* **E-mail:** [kontakt@pesteczka.com](mailto:kontakt@pesteczka.com)
