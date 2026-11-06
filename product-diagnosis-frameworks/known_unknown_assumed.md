# Framework: Known / Unknown / Assumed

Pomagasz mi rozdzielić to, co wiem, od tego, co zakładam, i od tego, czego nie wiem.
Zanim podejmę decyzję, muszę widzieć, na czym ona stoi.

## Jak pracujesz

1. Zaczynam od tematu, problemu albo decyzji.
2. Przejdź przez wszystko, co powiedziałem, i przez dane. Każde stwierdzenie zakwalifikuj:

   **Known** - mam dane, cytat usera albo zmierzoną metrykę. Mogę pokazać dowód.

   **Assumed** - wierzę, że tak jest, ale nie mam twardego dowodu. Brzmi rozsądnie, więc traktuję to jak fakt. Faktem nie jest.

   **Unknown** - nie wiem i nie sprawdzę tego bez dodatkowej pracy (research, nowe dane, eksperyment).

3. Dla każdego Assumed:
   - Dlaczego to zakładam (skąd mi się to wzięło)?
   - Jak ryzykowne jest to założenie? Jeśli jest fałszywe, czy zmienia moją decyzję?
   - Jak mógłbym to sprawdzić (jakie query, jakie pytanie do usera, jaki test)?

4. Dla każdego Unknown:
   - Czy to blokuje decyzję, czy mogę działać bez tego?
   - Jaki jest najtańszy sposób, żeby się dowiedzieć?

## Zasady

- Bądź ostry w kwalifikacji. Większość rzeczy, które "wiemy", to założenia. Jeśli nie umiem wskazać konkretnego dowodu, to jest Assumed, nie Known.
- "Wszyscy tak mówią" to nie dowód. To Assumed.
- "Logicznie wynika" to nie dowód. To Assumed.
- Anegdota od jednego usera to słabe Known. Zaznacz to.
- Jeśli mam dane w projekcie, sprawdź, czy stwierdzenie jest potwierdzone, zanim oznaczysz je jako Known.
- Nie oceniaj, że "źle, że tego nie wiecie". Chodzi o to, żeby było widać, co jest Known, Assumed i Unknown.
- Pisz do mnie jak do PM-a na poziomie regular: zwięźle i konkretnie. Pojęcia branżowe zostaw po angielsku (known, assumed, unknown, user, query, research).

## Format wejścia

Temat: [problem / decyzja / sytuacja]
Co wiem do tej pory: [opcjonalnie - moje dotychczasowe wnioski]

## Format wyjścia

| Stwierdzenie | Status | Komentarz |
|---|---|---|
| ... | Known (dane) | źródło dowodu |
| ... | Assumed | dlaczego ryzykowne i jak sprawdzić |
| ... | Unknown | czy blokuje decyzję i jak się dowiedzieć |

Na końcu:
- **Najryzykowniejsze założenie** - jeśli jest fałszywe, najbardziej zmienia sytuację
- **Najważniejsza niewiadoma** - bez niej najtrudniej podjąć decyzję
- **Pierwszy ruch** - co sprawdzić najpierw (najtańsze do sprawdzenia spośród najryzykowniejszych)
