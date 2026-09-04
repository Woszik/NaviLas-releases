# NaviLas — instalacja (GitHub)

Publiczne pliki APK aplikacji **NaviLas** (Android) oraz manifesty auto-update.

**Adres tego repozytorium:**  
https://github.com/Woszik/NaviLas-releases

**Kod źródłowy (GPL-3.0):** https://github.com/Woszik/NaviLas  
**Opinie i sugestie:** https://github.com/Woszik/NaviLas/issues

---

## Wybierz kanał świadomie

Na liście [Releases](https://github.com/Woszik/NaviLas-releases/releases) są **trzy poziomy oczekiwań**. Nie pobieraj „najnowszego APK z listy” bez sprawdzenia kanału — Nightly jest oznaczony jako **Pre-release**.

### Nightly (Pre-release) — testowanie pomysłów

Świeże buildy z rozwoju. **Praktycznie do weryfikacji pomysłów** — mogą być niestabilne i szybko się zmieniać.

Jeśli chcesz **pobawić się** nowościami: pobierz, używaj i **pisz opinie / sugestie** (Issues w repo kodu).

| | |
|--|--|
| Release | tag [`nightly`](https://github.com/Woszik/NaviLas-releases/releases/tag/nightly) (Pre-release) |
| Manifest | [`nightly.json`](https://github.com/Woszik/NaviLas-releases/blob/main/nightly.json) |
| W aplikacji | Ustawienia → Aktualizacje → **Nightly i nowsze** |

### Beta — użytkowanie testowe

Wersje do **publikowania i szerszego użytkowania**, na **ogólnych zasadach bety**: mogą zawierać błędy; funkcje mogą się jeszcze zmieniać. Domyślny kanał aktualizacji w aplikacji.

| | |
|--|--|
| **Aktualna Beta** | **[0.5.46](https://github.com/Woszik/NaviLas-releases/releases/tag/v0.5.46)** |
| Manifest | [`latest.json`](https://github.com/Woszik/NaviLas-releases/blob/main/latest.json) |
| W aplikacji | Ustawienia → Aktualizacje → **Beta i nowsze** (domyślnie) |

### Final — planowane

Docelowy kanał „produkcyjny”. Jak każda aplikacja może zawierać błędy — po wykryciu lub zgłoszeniu będą usuwane **w trybie priorytetowym**.

| | |
|--|--|
| Status | **jeszcze niedostępny** |
| Manifest | później `final.json` |
| W aplikacji | Ustawienia → Aktualizacje → **Tylko Final** (cisza, dopóki nie powstanie) |

---

## GitHub vs F-Droid

| Kanał | Skąd instalować | Aktualizacje |
|-------|-----------------|--------------|
| **GitHub** (to repo) | [Releases](https://github.com/Woszik/NaviLas-releases/releases) — wybierz Nightly / Beta / Final | In-app przy starcie lub „Sprawdź aktualizacje” |
| **F-Droid** | Klient F-Droid (po wejściu do katalogu) | Tylko F-Droid |

**Nie przełączaj GitHub ↔ F-Droid na jednym telefonie bez kopii zapasowej** — APK mają różne podpisy. Przed zmianą: **Lista → Zapisane → Kopia → Eksportuj**.

Nightly, Beta i Final na GitHubie mają **ten sam podpis** — kanał przełączasz w Ustawieniach bez reinstalacji.

---

## Co robi NaviLas

NaviLas pomaga znaleźć **miejsca odpoczynku w lasach** (dane BDL / „Czas w Lesie”):

- wyszukiwanie wokół GPS, punktu na mapie, miejscowości lub wzdłuż linii,
- przeglądanie i filtrowanie miejsc oraz dodatkowych obiektów BDL,
- mapa wyników i stref „Zanocuj w lesie”,
- dojazd samochodem lub motocyklem,
- przekazywanie celu do Google Maps, OsmAnd lub Cruiser,
- dane BDL offline,
- zapisywanie ulubionych miejsc z kategoriami,
- motyw System / Czujnik światła / Dzień / Noc,
- **eksport i import zapisanych miejsc** (kopia zapasowa w pliku JSON).

---

## Wymagania

- telefon z **Android 8.0** lub nowszym,
- dostęp do internetu (pierwsza instalacja i aktualizacje; wyszukiwanie może działać też na danych offline),
- uprawnienie **lokalizacji** (gdy szukasz od GPS).

---

## Instalacja z GitHub (pierwszy raz)

1. Otwórz: https://github.com/Woszik/NaviLas-releases
2. Wybierz kanał (wyżej) — dla większości osób start od **Beta**.
3. Wejdź w odpowiedni release i pobierz `navilas-*.apk`.
4. Zainstaluj (zezwól na instalację z tego źródła, jeśli system o to poprosi).

### Ostrzeżenie Google Play Protect

Ostrzeżenie przy instalacji APK spoza Google Play jest **normalne** — NaviLas nie jest w Sklepie Play. Instaluj wyłącznie z tego repozytorium.

Typowa ścieżka: **Więcej szczegółów** → **Zainstaluj bez skanowania**.

---

## Aktualizacje (kanał GitHub)

Po pierwszej instalacji:

- przy **starcie** aplikacja sprawdza nowszą wersję według wybranego kanału,
- możesz też: menu **⋮ → Sprawdź aktualizacje**,
- kanał zmieniasz w **⋮ → Ustawienia → Aktualizacje (GitHub)**.

---

## Kopia zapisanych miejsc (eksport / import)

1. **Lista** → **Zapisane** → **Kopia** → **Eksportuj zapisane…**
2. Po reinstalacji: **Importuj…** → **Scal** lub **Zastąp wszystko**

Szczegóły: menu **⋮ → O aplikacji**.

---

## Licencja

NaviLas — Copyright (C) 2026 Woszik.  
Program na licencji **GNU GPL v3**. Pełny tekst: https://github.com/Woszik/NaviLas/blob/main/LICENSE

---

## Pliki w tym repo

| Element | Opis |
|---------|------|
| [Releases](https://github.com/Woszik/NaviLas-releases/releases) | APK: Nightly (Pre-release), Beta (`vX.Y.Z`), później Final |
| [`nightly.json`](https://github.com/Woszik/NaviLas-releases/blob/main/nightly.json) | Manifest Nightly |
| [`latest.json`](https://github.com/Woszik/NaviLas-releases/blob/main/latest.json) | Manifest Beta |
| `final.json` | Manifest Final — gdy powstanie |

---

## Krótka wiadomość do skopiowania

```
NaviLas (Android) — instalacja z GitHub:

https://github.com/Woszik/NaviLas-releases

Wybierz kanał:
• Beta (zalecane na start) — użytkowanie testowe na zasadach bety
• Nightly (Pre-release) — zabawa świeżymi pomysłami + opinie/sugestie
• Final — jeszcze niedostępny (później: naprawy błędów priorytetowo)

1) Releases → odpowiedni release → navilas-*.apk
2) Play Protect może ostrzec — normalne. Więcej szczegółów → Zainstaluj bez skanowania.
3) Aktualizacje: start aplikacji albo ⋮ → Sprawdź aktualizacje (kanał w Ustawieniach).

Opinie: https://github.com/Woszik/NaviLas/issues
Źródła: https://github.com/Woszik/NaviLas (GPL-3.0)
```
