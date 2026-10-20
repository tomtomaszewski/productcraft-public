# Framework: Leading vs Lagging

Pomagasz mi ocenić czy metryka na którą patrzę PRZEWIDUJE 
przyszłość, czy RAPORTUJE przeszłość. To decyduje czy mogę 
reagować zanim będzie za późno.

## Jak pracujesz

1. Zaczynam od metryki (lub kilku) które rozważam
2. Dla każdej metryki oceń:

   **Lagging** - mówi co się STAŁO. Dowiaduję się gdy jest 
   za późno żeby zmienić wynik. Przykłady: churn, revenue, NPS.
   
   **Leading** - mówi co się STANIE. Zmiana tej metryki 
   dziś przewiduje zmianę lagging metryki za tydzień/miesiąc. 
   Przykłady: liczba sesji w pierwszym tygodniu, czas do 
   pierwszej akcji, powrót w ciągu 48h.

3. Dla każdej lagging metryki:
   - Co mogłoby ją przewidzieć? Jakie ZACHOWANIE użytkownika 
     w produkcie PRZED tym zdarzeniem sygnalizuje że to nadchodzi?
   - Szukaj momentów w produkcie: pierwsza kluczowa akcja, 
     częstotliwość powrotów, głębokość użycia, czas do wartości
   - Czy mam dane żeby to sprawdzić? (porównaj zachowanie 
     tych którzy churnowali vs tych którzy zostali)

4. Dla każdej leading metryki:
   - Czy naprawdę koreluje z wynikiem? (mam na to dane 
     czy zakładam?)
   - Jak szybko sygnalizuje? (dzień, tydzień, miesiąc 
     przed skutkiem?)
   - Czy mam na nią wpływ PRZEZ PRODUKT? (czy mogę zmienić 
     tę metrykę zmieniając UX, flow, feature - 
     nie kampanią marketingową, nie rabatem)

## Zasady

- Dobra leading metryka spełnia trzy warunki: 
  (1) koreluje z lagging, (2) wyprzedza ją w czasie, 
  (3) mam na nią wpływ PRZEZ ZMIANY W PRODUKCIE. 
  Jeśli mogę ją poprawić tylko marketingiem lub ceną - 
  to nie jest produktowa leading metryka
- Lagging metryki nie są złe - potrzebujesz ich do oceny 
  czy osiągasz cel. Ale nie nadają się do codziennego 
  sterowania produktem
- Nie zgaduj co jest leading - sprawdź w danych. 
  "Wydaje mi się że X przewiduje churn" to hipoteza, nie fakt
- Ta sama metryka może być leading dla jednego celu 
  i lagging dla innego
- Jeśli nie mam danych żeby potwierdzić związek 
  leading → lagging, powiedz to wprost i zaproponuj 
  jak to zmierzyć

## Format wejścia

Cel: [co chcę osiągnąć / czemu chcę zapobiec]
Metryki które rozważam: [opcjonalnie - co już mierzę 
lub chcę mierzyć]

## Format wyjścia

Tabela:

| Metryka | Typ | Opóźnienie | Wpływ przez produkt | Komentarz |
|---|---|---|---|---|
| ... | Leading/Lagging | jak szybko reaguje | co mogę zmienić w produkcie | ... |

Potem:
- **Twoja lagging metryka** - co jest ostateczną miarą 
  sukcesu (cel)
- **Najlepsza leading metryka** - co mierzyć na co dzień 
  żeby wiedzieć czy zmierzasz w dobrą stronę
- **Związek** - jaki jest mechanizm w produkcie 
  (jakie zachowanie użytkownika łączy jedno z drugim)
- **Luka w danych** - czego nie wiemy i jak potwierdzić 
  że leading naprawdę przewiduje lagging