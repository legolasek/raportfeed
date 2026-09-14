# 📦 RaportFeed - Synchronizator Dostępności i Cen Allegro
<img width="1376" height="768" alt="Gemini_Generated_Image_1z41di1z41di1z41" src="https://github.com/user-attachments/assets/cb0318c2-a5e0-499a-95af-ef605f43cceb" />


> **Profesjonalne narzędzie desktopowe do automatycznego monitorowania hurtowni, feedów XML oraz bezpiecznej synchronizacji ofert na Allegro.**

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

* Pobierz najnowszy plik `RaportFeed_PawelSteczka.exe`.
* Program jest w wersji przenośnej (standalone) – nie wymaga instalacji ani zewnętrznych bibliotek.

---

## 🚀 Pierwsze Uruchomienie (Krok po kroku)

### 1. Uruchomienie programu
1. Umieść plik `RaportFeed_PawelSteczka.exe` w dowolnym wygodnym folderze (np. na Pulpicie lub w `C:\RaportFeed`).
2. Uruchom program dwuklikiem.
> **Uwaga (Windows SmartScreen):** Przy pierwszym uruchomieniu system Windows może wyświetlić niebieski komunikat *„System Windows ochronił ten komputer”* (standard dla nowych plików bez komercyjnego certyfikatu EV). Kliknij **„Więcej informacji”**, a następnie **„Uruchom mimo to”**.

### 2. Aktywacja licencji
* Przy pierwszym starcie program poprosi o podanie **Klucza Licencyjnego**.
* Wklej otrzymany od autora ciąg znaków licencji i kliknij **Aktywuj**.
* Program zapisze licencję lokalnie w pliku `license.key` – kolejne uruchomienia nie będą już wymagały wpisywania klucza.

### 3. Połączenie z Allegro
1. Przejdź do zakładki **Allegro** i kliknij **Zaloguj do Allegro**.
2. Wpisz swoje dane aplikacji partnerskiej (`Client ID` oraz `Client Secret`) – zostaną bezpiecznie zapisane na Twoim komputerze.
3. Kliknij **Zaloguj przez przeglądarkę** – program wygeneruje kod jednorazowy i otworzy oficjalną stronę Allegro, gdzie zatwierdzisz dostęp jednym kliknięciem.

---

## 🛡️ Bezpieczeństwo Twojej Sprzedaży

Program został zaprojektowany ze szczególnym naciskiem na eliminację kosztownych pomyłek:

* 📦 **Price Drop Guard (Ochrona Zestawów):**
  Program automatycznie wykrywa oferty będące wielopakami (np. *„2 sztuki”*, *„zestaw”*, *„dwupak”*, *„x2”*). Jeśli feed dostawcy podaje cenę pojedynczego produktu, automat **nie nadpisze zestawu zaniżoną ceną**, dopóki tego wyraźnie nie potwierdzisz lub nie ustawisz odpowiedniego mnożnika (pod prawym przyciskiem myszy).
* 📉 **Wykrywanie dużych obniżek cen:**
  Każda zmiana obniżająca cenę o więcej niż **40%** zostaje oznaczona wyraźnym ostrzeżeniem i wymaga potwierdzenia użytkownika.
* ↩️ **Safety Snapshot & Rollback (Błyskawiczne cofnięcie zmian):**
  Przed każdą wysyłką do Allegro program tworzy automatyczną migawkę stanu. W razie jakiejkolwiek pomyłki po stronie dostawcy możesz **jednym kliknięciem przywrócić poprzednie ceny i stany na Allegro**.
* 🔄 **Automatyczne Aktualizacje:**
  Aplikacja automatycznie informuje o dostępności nowej wersji i umożliwia aktualizację jednym kliknięciem wewnątrz programu.

---

## 📊 Eksport Raportów

* **Eksport do Excela (.xlsx):** Przejrzyste, kolorowane zestawienie produktów (dostępne na zielono, braki magazynowe na czerwono, informacje o przedsprzedaży).
* **Raporty tekstowe (.txt):** Szybkie podsumowanie dla magazynu z podziałem na marki.

---

## 💻 Wymagania Systemowe

* **System operacyjny:** Windows 10 lub Windows 11 (64-bit)
* **Połączenie internetowe:** Wymagane do pobierania feedów XML oraz komunikacji z Allegro API
* **Brak dodatkowych wymagań:** Nie musisz instalować Pythona ani żadnych środowisk programistycznych.

---

## 📬 Kontakt i Wsparcie

W sprawach przedłużenia licencji, zgłaszania uwag lub zamówienia dedykowanych integracji:

* **Autor:** Paweł Steczka
* **Strona:** [pesteczka.com](https://pesteczka.com)
* **E-mail:** [kontakt@pesteczka.com](mailto:kontakt@pesteczka.com)
