# NaviLas — instalacja dla testerów

Oficjalne, publiczne wydania aplikacji **NaviLas** (Android).

**Adres tego repozytorium (do przekazania testerom):**  
https://github.com/Woszik/NaviLas-releases

Kod źródłowy pozostaje w prywatnym repozytorium. Tutaj są tylko opis, pliki APK i manifest aktualizacji.

---

## Co robi NaviLas

NaviLas pomaga znaleźć **miejsca odpoczynku w lasach** (dane BDL / „Czas w Lesie”):

- wyszukiwanie wokół GPS, punktu na mapie lub miejscowości,
- mapa wyników i stref „Zanocuj w lesie”,
- dojazd samochodem lub motocyklem,
- dane BDL offline,
- zapisywanie ulubionych miejsc z kategoriami.

---

## Wymagania

- telefon z **Android 8.0** lub nowszym,
- dostęp do internetu (pierwsza instalacja i aktualizacje; wyszukiwanie może działać też na danych offline),
- uprawnienie **lokalizacji** (gdy szukasz od GPS).

---

## Instalacja (pierwszy raz)

1. Otwórz na telefonie: https://github.com/Woszik/NaviLas-releases  
2. Wejdź w **[Releases](https://github.com/Woszik/NaviLas-releases/releases)** i pobierz najnowszy plik `navilas-*.apk`.  
3. Otwórz pobrany plik i zezwól na instalację z tego źródła (przeglądarka / pliki), jeśli system o to poprosi.  
4. Zainstaluj aplikację.

### Ostrzeżenie Google Play Protect („aplikacja niebezpieczna”)

To **częste i oczekiwane** przy instalacji spoza Google Play.

NaviLas **nie pochodzi ze sklepu Play**, tylko z oficjalnego release na GitHubie (to repozytorium). Play Protect bywa ostrożny wobec takich APK — **nie oznacza to automatycznie wirusa**.

Jeśli pobrałeś APK z powyższego linku / z zakładki Releases:

- możesz wybrać opcję w stylu **„Mimo to zainstaluj”** / **„Zainstaluj mimo to”**,
- albo w Play Protect tymczasowo zezwolić na tę instalację.

Nie instaluj NaviLas z innych, nieoficjalnych stron.

---

## Aktualizacje

Po pierwszej instalacji z tego repozytorium:

- przy **starcie aplikacji** NaviLas sprawdza, czy jest nowsza wersja,
- jeśli tak — pojawia się okno z opisem zmian i przyciskami **Aktualizuj** / **Później**,
- możesz też sprawdzić ręcznie: ekran **Wyszukiwanie** → **Sprawdź aktualizacje**.

Aktualizacja pobiera APK z GitHub i uruchamia instalator systemowy. Ponownie może pojawić się Play Protect — zachowanie jak przy pierwszej instalacji.

---

## Pliki w tym repo

| Element | Opis |
|---------|------|
| [Releases](https://github.com/Woszik/NaviLas-releases/releases) | Historia wersji i pliki `navilas-*.apk` |
| [`latest.json`](https://github.com/Woszik/NaviLas-releases/blob/main/latest.json) | Manifest używany przez aplikację do auto-update |

---

## Krótka wiadomość do skopiowania dla testerów

```
NaviLas (Android) — testowa instalacja:

https://github.com/Woszik/NaviLas-releases

1) Wejdź w Releases i pobierz najnowszy navilas-*.apk
2) Zainstaluj (zezwól na instalację z tego źródła)
3) Jeśli Play Protect ostrzeże, że aplikacja jest „niebezpieczna” — to normalne przy instalacji spoza Google Play. APK bierz tylko z powyższego linku, potem „zainstaluj mimo to”.

Aktualizacje: przy starcie aplikacji albo Wyszukiwanie → Sprawdź aktualizacje.
```
