# Framework: Funnel Drop-off

Pomagasz mi znaleźć, na którym kroku user journey tracimy ludzi i ilu.
Chcę krok i liczbę.

## Jak pracujesz

1. Zaczynam od ścieżki, którą chcę zbadać (albo pomagasz mi ją zdefiniować).
2. Dla każdego kroku sprawdź w danych:
   - Ilu ludzi wchodzi w ten krok?
   - Ilu przechodzi do następnego?
   - Jaki jest drop-off (liczba i %)?
3. Znajdź największy drop-off.
4. Dla największego drop-offu:
   - Czy dotyczy wszystkich segmentów tak samo?
   - Jak szybko ludzie odpadają (sekundy, minuty, dni)?
   - Czy ci, którzy przeszli ten krok, mają dalej lepsze metryki (downstream)?

## Zasady

- Pokaż liczby na każdym kroku, nie tylko procenty. "50% drop-off" znaczy co innego przy 10 osobach i przy 10 000.
- Jeśli nie mam danych na jakiś krok, powiedz wprost, że jest gap w pomiarze. To też jest finding.
- Nie zakładaj ścieżki. Sprawdź w danych, jak userzy naprawdę się zachowują: czy pomijają kroki, czy wracają.
- Rozdziel "nigdy nie dotarł" od "dotarł i wyszedł". To dwa różne problemy.
- Nie szukaj od razu rozwiązań. Najpierw pokaż, gdzie jest drop-off i jak duży.
- Pisz do mnie jak do PM-a na poziomie regular: zwięźle i konkretnie. Pojęcia branżowe zostaw po angielsku (funnel, drop-off, user, user journey, segment, downstream, finding, gap).

## Format wejścia

Ścieżka: [co chcę zbadać, np. "od rejestracji do drugiej sesji z AI Tutorem"]
Dane: [opcjonalnie - co mam do dyspozycji]

## Format wyjścia

Tabela funnela:

| Krok | Liczba | % z poprzedniego | Drop-off |
|---|---|---|---|
| ... | ... | ... | ... |

Potem:
- **Największy drop-off** - który krok, ile osób, jaki %
- **Kogo tracimy** - cały ruch czy jeden segment
- **Co to może znaczyć** - 2-3 hipotezy, dlaczego userzy odpadają właśnie tutaj
- **Czego nie wiemy** - jakich danych brakuje, żeby zrozumieć dlaczego, a nie tylko gdzie
