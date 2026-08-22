# NaviLas — releases

Publiczny kanał dystrybucji aplikacji **NaviLas** (Android).

Kod źródłowy jest w prywatnym repozytorium [NaviLas](https://github.com/Woszik/NaviLas). Tutaj publikujemy pliki APK i manifest aktualizacji dla aplikacji zainstalowanej na telefonie.

## Co robi NaviLas

NaviLas pomaga znaleźć **miejsca odpoczynku w lasach** (BDL / „Czas w Lesie”):

- wyszukiwanie w promieniu od GPS, punktu na mapie lub miejscowości,
- mapa z wynikami i strefami „Zanocuj w lesie”,
- analiza dojazdu drogą (samochód / motocykl),
- dane BDL offline,
- zapisywanie ulubionych miejsc z kategoriami.

## Wymagania

- Android 8.0+ (API 26)
- Uprawnienie lokalizacji (wyszukiwanie od GPS)
- Internet (pierwsze wyszukiwanie online; dane BDL można pobrać offline)

## Instalacja (pierwszy raz)

1. Wejdź w **[Releases](../../releases)** i pobierz najnowszy plik `navilas-*.apk`.
2. Na telefonie zezwól na instalację z **nieznanego źródła** (przeglądarka / menedżer plików).
3. Otwórz pobrany APK i zainstaluj.

## Aktualizacje w aplikacji

Zainstalowana aplikacja co 24 h (oraz ręcznie z ekranu Wyszukiwanie) sprawdza plik [`latest.json`](latest.json). Gdy jest nowsza wersja, pojawia się dialog **Aktualizuj** — pobieranie i instalacja odbywają się bez przeglądarki.

## Pliki w tym repo

| Plik | Opis |
|------|------|
| `latest.json` | Manifest aktualnej wersji (versionCode, URL APK, SHA-256) |
| Releases → `navilas-*.apk` | Podpisane paczki instalacyjne |

---

Pytania i zgłoszenia błędów: przez Issues w repo źródłowym (dla współpracowników).
