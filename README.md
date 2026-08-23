# NaviLas — instalacja dla testerów

Oficjalne, publiczne wydania aplikacji **NaviLas** (Android).

**Adres tego repozytorium (do przekazania testerom):**  
https://github.com/Woszik/NaviLas-releases

**Kod źródłowy (GPL-3.0):** https://github.com/Woszik/NaviLas

Tutaj są opis, pliki APK z kanału **GitHub** i manifest auto-update. Równolegle przygotowywany jest kanał **F-Droid** (osobna instalacja, inny podpis).

---

## GitHub vs F-Droid

| Kanał | Skąd instalować | Aktualizacje |
|-------|-----------------|--------------|
| **GitHub** (ten repo) | [Releases](https://github.com/Woszik/NaviLas-releases/releases) | In-app przy starcie lub „Sprawdź aktualizacje” |
| **F-Droid** | Klient F-Droid (po wejściu do katalogu) | Tylko F-Droid |

**Nie przełączaj kanałów na jednym telefonie bez kopii zapasowej** — APK mają różne podpisy. Przed zmianą: **Lista → Zapisane → Kopia → Eksportuj**.

---

## Co robi NaviLas

NaviLas pomaga znaleźć **miejsca odpoczynku w lasach** (dane BDL / „Czas w Lesie”):

- wyszukiwanie wokół GPS, punktu na mapie lub miejscowości,
- mapa wyników i stref „Zanocuj w lesie”,
- dojazd samochodem lub motocyklem,
- dane BDL offline,
- zapisywanie ulubionych miejsc z kategoriami,
- **eksport i import zapisanych miejsc** (kopia zapasowa w pliku JSON).

---

## Wymagania

- telefon z **Android 8.0** lub nowszym,
- dostęp do internetu (pierwsza instalacja i aktualizacje; wyszukiwanie może działać też na danych offline),
- uprawnienie **lokalizacji** (gdy szukasz od GPS).

---

## Instalacja z GitHub (pierwszy raz)

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

## Aktualizacje (kanał GitHub)

Po pierwszej instalacji z tego repozytorium:

- przy **starcie aplikacji** NaviLas sprawdza, czy jest nowsza wersja,
- jeśli tak — pojawia się okno z opisem zmian i przyciskami **Aktualizuj** / **Później**,
- możesz też sprawdzić ręcznie: ekran **Wyszukiwanie** → **Sprawdź aktualizacje**.

Aktualizacja pobiera APK z GitHub i uruchamia instalator systemowy. Ponownie może pojawić się Play Protect — zachowanie jak przy pierwszej instalacji.

---

## Kopia zapisanych miejsc (eksport / import)

Jeśli masz zapisane ulubione miejsca, możesz je **zabezpieczyć przed utratą** (np. przed odinstalowaniem aplikacji):

1. Ekran **Lista** → **Zapisane** → **Kopia** → **Eksportuj zapisane…**
2. Zapisz plik JSON (np. w folderze **Pobrane**)

Po ponownej instalacji lub na innym telefonie:

1. **Lista** → **Zapisane** → **Kopia** → **Importuj zapisane…**
2. Wybierz plik kopii
3. **Scal** (dodaje brakujące) lub **Zastąp wszystko** (przywraca kopię na czysto)

Plik kopii **nie jest wysyłany automatycznie** nigdzie poza Twoim urządzeniem. Szczegóły: ikona **ⓘ** → **O aplikacji**.

---

## Licencja

NaviLas — Copyright (C) 2026 Woszik.  
Program na licencji **GNU GPL v3**. Pełny tekst: https://github.com/Woszik/NaviLas/blob/main/LICENSE

---

## Pliki w tym repo

| Element | Opis |
|---------|------|
| [Releases](https://github.com/Woszik/NaviLas-releases/releases) | Historia wersji i pliki `navilas-*.apk` (kanał GitHub) |
| [`latest.json`](https://github.com/Woszik/NaviLas-releases/blob/main/latest.json) | Manifest auto-update (tylko build `github`) |

---

## Krótka wiadomość do skopiowania dla testerów

```
NaviLas (Android) — testowa instalacja (GitHub):

https://github.com/Woszik/NaviLas-releases

1) Wejdź w Releases i pobierz najnowszy navilas-*.apk
2) Zainstaluj (zezwól na instalację z tego źródła)
3) Play Protect może ostrzec — normalne przy APK spoza Play. Bierz tylko z powyższego linku.

Aktualizacje: przy starcie albo Wyszukiwanie → Sprawdź aktualizacje.
Kopia punktów: Lista → Zapisane → Kopia → Eksportuj / Importuj.
Źródła: https://github.com/Woszik/NaviLas (GPL-3.0)
```
