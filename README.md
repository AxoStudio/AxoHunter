# AxoHuntersBETA

Witaj w repozytorium **AxoHuntersBETA** – Minecraftowego pluginu stworzonego dla serwera Bukkit/Spigot, który dodaje ekscytującą mechanikę polowania i ról (np. Szeryf, Medyk, Hunter) z dynamicznym systemem statystyk i placeholderów.

## Opis
AxoHuntersBETA to plugin, który umożliwia graczom wcielenie się w różne role w grze, takie jak Szeryf, Medyk czy Hunter. Zawiera system punktów, statystyk (zabójstwa, śmierci, wygrane) oraz integrację z PlaceholderAPI, aby wyświetlać dane na pasku bocznym (np. za pomocą pluginu TAB). Idealny dla serwerów z minigrami lub trybami survival z elementami rywalizacji.

## Funkcjonalności
- Różne role: Szeryf, Medyk, Hunter i domyślna rola.
- System punktów i statystyk (zabójstwa, śmierci, wygrane).
- Integracja z PlaceholderAPI dla dynamicznych komunikatów.
- Wyświetlanie czasu gry, liczby graczy i kolejki.
- Dedykowane paski boczne (scoreboards) dla każdej roli.

## Wymagania
- Minecraft Server z API Bukkit/Spigot (1.8+).
- Plugin **PlaceholderAPI** (do obsługi placeholderów).
- Plugin **TAB** (opcjonalny, do wyświetlania scoreboardów).

## Informacje
- Plugin jest płatny i nie będzie dostępny **source code** ani plik .jar bezpośrednio na GitHubie
- Cena za plugin to około **80PLN** nie jest bezpośrednio ustalona ponieważ plugin jest we wersji **Alpha**
- Plugin nie będzie dostępny publicznie ale będziesz mógł zagrać na serwerze na którym tryb będzie dostępny
- Po zakupie pluginu dostaniesz pełną wersje **.jar** oraz plugin jest do edytowania, możesz wszystko ustawić pod siebie od GUI pod Nazwy ról
- Plugin obsługuje kolory **&** np. **&c** czyli czerwony oraz obsługuje 3 pliki konfiguracyjne
- Jeśli chcesz zakupić plugin przedpremierowo wejdź na **dc.axostudio.pl** i dołącz na discord oraz kup plugin
- Plugin jest na wersję Paper/Spigot **1.20.4** oraz nie będzie aktualizowany pod względem wersji minecrafta **Jak narazie**

## Instalacja
1. Pobierz najnowszą wersję pluginu lub wejdź na serwer **axostudio.pl**.
2. Umieść plik `AxoHuntersBETA.jar` w folderze `plugins` na serwerze.
3. Zainstaluj PlaceholderAPI (i opcjonalnie TAB) w folderze `plugins`.
4. Uruchom serwer. Plugin automatycznie wygeneruje domyślny plik konfiguracyjny `config.yml`.
5. Dostosuj `config.yml` według potrzeb (patrz sekcja "Konfiguracja").
6. Przeładuj plugin komendą `/reload` lub zrestartuj serwer (zalecana).

## Konfiguracja
Po uruchomieniu plugin generuje plik `config.yml`. Przykładowa konfiguracja zintegrowana z TAB:
- Ustaw role w sekcji `conditions`, aby przełączać scoreboards (np. Szeryf, Medyk, Hunter).
- Dostosuj placeholdery (np. `%axohunter_points%`, `%axohunter_medic_kits%`) w scoreboardach.

## Komendy
- axohunter reload/koniec
- axostats reset all/<nick>
- axosklep 
- axopoints add/del <nick> <ilosc>
- lobby/spawn

## Autor
- FR Shadow (discord)
- AxoPL777 (minecraft)
- AxoStudio (serwer discord)

## Pomocnicy
- B0cianPL
- Reksio_o


