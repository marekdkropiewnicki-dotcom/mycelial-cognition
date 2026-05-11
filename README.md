# MYC·OS — Mycelial Cognition

> Generatywny art viewer. Rozproszone myślenie zapisane jako stygmergiczna sieć strzępek.

**Live:** https://marekdkropiewnicki-dotcom.github.io/mycelial-cognition/

Wizualizacja sieci grzybniowej (hyphae) jako akt rozproszonego poznania. Strzępki rosną, rozgałęziają się i łączą (anastomoza), zostawiając ślad w polu odżywczym, który prowadzi kolejne pokolenia. Czas zapisany jest w warstwach koloru: narodziny, dojrzałość, pamięć.

## Uruchomienie

Otwórz `index.html` w przeglądarce lub odwiedź live site powyżej. Brak buildu, brak zależności — czysty p5.js z CDN.

## Sterowanie

- **Ziarno** — deterministyczny seed (Poprzednie / Następne / Losowe / Regeneruj)
- **Liczba początkowych strzępek** — ile hyf startuje na płótnie
- **Skala pola odżywczego** — gęstość pola Perlina prowadzącego wzrost
- **Tempo wzrostu** — długość kroku
- **Prawdopodobieństwo rozgałęzienia** — szansa na bifurkację
- **Promień anastomozy** — odległość, w której strzępki się łączą
- **Paleta** — schemat kolorystyczny

## Stack

- [p5.js 1.7.0](https://p5js.org/) (CDN)
- Google Fonts: Poppins + Lora
- Vanilla HTML/CSS, jeden plik (`index.html`)
- Hosting: GitHub Pages

## Licencja

MIT
