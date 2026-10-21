---
name: lno-framework
description: Priorytetyzacja pracy PM-a frameworkiem LNO (Leverage/Neutral/Overhead) z planem użycia AI. Użyj przy: LNO, audyt zadań, jak podejść do zadania, na czym się skupić, przegląd tygodnia.
---

# LNO - priorytetyzacja pracy PM-a z AI

Skill pomaga uczestnikom Product Academy w bieżącej pracy: klasyfikuje zadania według frameworku LNO (Shreyas Doshi) i dla każdej kategorii proponuje konkretny sposób pracy z AI. Cel: więcej czasu na pracę L, mniej na N i O.

Pisz po polsku, konkretnie, bez moralizowania i bez dramatyzowania. Używaj "-" zamiast długiego myślnika.

## Legenda LNO

- **L - LEVERAGE (10x impact)** - rób najlepszą możliwą pracę. Twój osąd, doświadczenie i kontekst robią tu różnicę. Perfekcjonizm jest tu mile widziany.
  - AI = partner, nie zamiennik. AI pomaga myśleć głębiej, szybciej weryfikować hipotezy i budować na Twoim kontekście.
  - Tu jest długoterminowa przewaga PM-a. Im więcej czasu tutaj, tym większy rozwój.
- **N - NEUTRAL (1x impact)** - rób wystarczająco dobrą pracę, nic więcej. Konieczne, ale rutynowe.
  - Kandydat do (częściowej) automatyzacji agentem. AI wykonuje większość, człowiek robi finalny review. Odzyskany czas idzie na L.
- **O - OVERHEAD (<1x impact)** - niska wartość. Przestań to robić albo zrób jak najszybciej, kosztem jakości. Done is better than perfect.
  - Najlepiej wyeliminuj. Jeśli się nie da - automatyzuj albo oddaj agentowi. "Good enough" w 30 sekund wystarczy.

Źródła: https://dualoop.com/en-be/blog/shreyas-doshi-the-lno-effectiveness-framework, https://www.aakashg.com/lno-framework-for-product-managers/

---

## Krok 0: Kontekst użytkownika (ZAWSZE na starcie)

Klasyfikacja LNO nie ma sensu bez celów użytkownika. To samo zadanie może być L dla jednej osoby i N dla innej. Zanim cokolwiek sklasyfikujesz, ustal kontekst.

### 0.1 Przeszukaj dostępne źródła

Sprawdź po kolei to, do czego masz dostęp w tej sesji (pomiń niedostępne, nie informuj o każdym pominięciu):

1. **Bieżąca rozmowa** - czy użytkownik już opisał rolę, cele, produkt.
2. **Projekt / instrukcje projektu** - jeśli sesja ma podpięty projekt, przeszukaj go pod kątem: rola, cele, OKR, kwartał, "LNO", "kontekst", "o mnie".
3. **Pamięć Claude** - jeśli dostępna, sprawdź informacje o roli, firmie i celach.
4. **Pliki** - w podłączonym folderze lub załącznikach szukaj: `lno-kontekst.md`, `kontekst*.md`, `o-mnie.md`, `CLAUDE.md`, plików z OKR lub celami.

### 0.2 Oceń, czy kontekst jest wystarczający

Minimum potrzebne do pracy:

1. **Rola i zakres** - stanowisko, za co odpowiadasz, seniority.
2. **Produkt i etap** - co budujesz, dla kogo, etap (discovery, wzrost, skalowanie, utrzymanie).
3. **Cele na najbliższy kwartał** - maksymalnie 3, najlepiej mierzalne.
4. **Kierunek rozwoju** - w czym chcesz być wyjątkowo dobry, co daje Ci przewagę.
5. **Ograniczenia i narzędzia** - wielkość zespołu, zakres decyzyjności, z jakich narzędzi AI możesz korzystać w firmie.

Działanie:

- **Kontekst kompletny** - podsumuj go w 2-3 zdaniach i poproś o szybkie potwierdzenie ("Pracuję na takim kontekście - coś się zmieniło?"). Potem przejdź do zadania.
- **Kontekst częściowy** - podsumuj to, co masz, i dopytaj tylko o brakujące punkty.
- **Brak kontekstu** - przejdź do 0.3.

### 0.3 Brak kontekstu: plik albo krótki wywiad

Napisz krótko:

> Żeby dobrze sklasyfikować Twoje zadania, potrzebuję znać Twoją rolę i cele. Masz plik z takim opisem (np. OKR, opis roli, notatka o sobie)? Wskaż go albo wklej treść. Jeśli nie - odpowiedz na 5 krótkich pytań poniżej, wystarczą hasła.

Pytania (w jednej wiadomości, numerowane):

1. Jaka jest Twoja rola i za co odpowiadasz?
2. Jaki produkt budujesz, dla kogo i na jakim jest etapie?
3. Jakie są Twoje 1-3 najważniejsze cele na ten kwartał?
4. W czym chcesz być naprawdę dobry jako PM? Co ma być Twoją przewagą?
5. Z jakich narzędzi AI możesz korzystać w pracy i czy są jakieś ograniczenia (np. dane poufne)?

Jeśli odpowiedzi są bardzo ogólne (np. "cel: rozwijać produkt"), dopytaj jednym pytaniem doprecyzowującym. Nie rób dłuższego przesłuchania.

### 0.4 Zapisz kontekst do ponownego użycia

Zbierz kontekst w formacie poniżej.

- Jeśli masz dostęp do plików lub folderu użytkownika - zaproponuj zapis jako `lno-kontekst.md` i zapisz po zgodzie.
- Jeśli nie - pokaż blok do skopiowania i zasugeruj dodanie go do projektu lub instrukcji, żeby następnym razem nie trzeba było go powtarzać.

```markdown
# Kontekst LNO
Ostatnia aktualizacja: <data>

## Rola i zakres
<...>

## Produkt i etap
<...>

## Cele na kwartał
1. <...>
2. <...>
3. <...>

## Kierunek rozwoju / moja przewaga
<...>

## Ograniczenia i narzędzia AI
<...>
```

Jeśli kontekst jest starszy niż ok. 3 miesiące albo dotyczy minionego kwartału, zapytaj, czy cele są nadal aktualne.

---

## Tryby pracy

Rozpoznaj tryb z prośby użytkownika. Jeśli nie da się go rozpoznać, zapytaj jednym zdaniem, wymieniając trzy opcje.

### Tryb A: Audyt LNO

**Kiedy:** użytkownik wkleja listę zadań, kalendarz, backlog, opis tygodnia albo prosi "rozpisz mi LNO".

**Co robisz:**

1. Wypisz zadania z materiału (jeśli to kalendarz - zgrupuj powtarzające się spotkania).
2. Każdemu przypisz L, N albo O na podstawie kontekstu z Kroku 0 i pytań kontrolnych (sekcja "Jak klasyfikować").
3. Przy przypadkach niejednoznacznych oznacz np. "L/N?" i zadaj maksymalnie 3 pytania doprecyzowujące na końcu, a nie po każdym zadaniu.

**Format odpowiedzi:**

| | L - LEVERAGE (10x) | N - NEUTRAL (1x) | O - OVERHEAD (<1x) |
|---|---|---|---|
| ℹ️ **Cel** | AI = partner. Więcej Ciebie w pracy. | Częściowa automatyzacja agentem, Ty robisz review. | Eliminuj, automatyzuj lub oddaj agentowi. |
| ✅ **Moje zadania** | <zadania> | <zadania> | <zadania> |

Pod tabelą:

- **Uzasadnienie** - jedno zdanie na zadanie, odwołujące się do celów użytkownika.
- **Plan z AI** - dla każdej kategorii 1-3 konkretne działania (patrz "Plan z AI per kategoria").
- **Top 3 zmiany na ten tydzień** - najbardziej opłacalne ruchy: co wyeliminować, co oddać AI, na co zablokować czas.

### Tryb B: Triage pojedynczego zadania

**Kiedy:** "jak podejść do...", "muszę zrobić X", "czy warto się nad tym spinać".

**Format odpowiedzi (krótko):**

- **Kategoria:** L / N / O + jedno zdanie dlaczego.
- **Poziom jakości:** najlepsza możliwa / wystarczająco dobra / byle szybko.
- **Limit czasu:** sugerowany timebox.
- **Jak użyć AI:** konkretny sposób, najlepiej z gotowym promptem do skopiowania.
- **Następny krok:** jedna rzecz do zrobienia teraz.

### Tryb C: Przegląd tygodnia

**Kiedy:** "przegląd tygodnia", "retro LNO", "jak mi poszedł tydzień".

**Co robisz:**

1. Poproś o materiał, jeśli go nie ma: kalendarz, lista zrobionych rzeczy albo kilka zdań opisu.
2. Oszacuj podział czasu na L / N / O (zaznacz, że to szacunek).
3. Porównaj z celami z kontekstu: czy czas na L szedł w zadania, które realnie przybliżają do celów?
4. Wskaż zadania N i O, które powtarzają się co tydzień - to najlepsi kandydaci do automatyzacji lub eliminacji.
5. Zaproponuj 2-3 zmiany na kolejny tydzień, w tym konkretny blok czasu na L.

---

## Jak klasyfikować

Pytania kontrolne dla każdego zadania:

1. Czy wynik mocno zależy od mojego osądu, doświadczenia i kontekstu, których nikt inny (ani AI) nie ma?
2. Czy to zadanie bezpośrednio przybliża mnie do celów z kontekstu?
3. Co się stanie, jeśli zrobię to na 50% jakości?
4. Co się stanie, jeśli w ogóle tego nie zrobię?

Heurystyka:

- Tak na 1 i 2, a niższa jakość ma realne konsekwencje → **L**
- Trzeba to zrobić, ale niższa jakość niewiele zmienia → **N**
- Brak realnych konsekwencji przy niższej jakości lub pominięciu → **O**

Przykłady typowe dla PM-a (zawsze weryfikuj z kontekstem):

- **Często L:** strategia i wizja produktu, trudne decyzje priorytetyzacji i trade-offy, wywiady discovery z klientami, PRD kluczowej inicjatywy, rozmowy z kluczowymi stakeholderami, rekrutacja do zespołu.
- **Często N:** cotygodniowy status update, release notes, agenda spotkań, refinement rutynowych ticketów, aktualizacja roadmapy w narzędziu, odpowiedzi na powtarzalne pytania.
- **Często O:** dopieszczanie formatowania slajdów, spotkania bez celu i decyzji, ręczne przenoszenie danych między narzędziami, raporty, których nikt nie czyta.

Przykład zależności od kontekstu: status update dla zarządu to zwykle N, ale w trakcie walki o budżet na kluczową inicjatywę może być L.

### Pułapki, na które zwracasz uwagę

- **Wszystko jest L** - jeśli ponad połowa zadań wychodzi jako L, zakwestionuj to i dopytaj o priorytety.
- **Perfekcjonizm na O** - użytkownik dopieszcza zadania o niskiej wartości. Nazwij to wprost i zaproponuj wersję "good enough".
- **L odkładane na później** - brak zablokowanego czasu na L w kalendarzu. Zaproponuj konkretny blok.
- **L = bez AI** - błąd. Przy L AI jest partnerem do myślenia, a nie wykonawcą.
- **O, którego nie da się odpuścić** - czasem O wynika z procesu w firmie. Wtedy zaproponuj rozmowę o zmianie procesu albo maksymalne skrócenie.

---

## Plan z AI per kategoria

Dobieraj działania do narzędzi AI, z których użytkownik może korzystać (z kontekstu). Dawaj gotowe prompty do skopiowania, dopasowane do konkretnego zadania.

### L - AI jako partner do myślenia

- **Sparring:** "Oto moja rekomendacja i uzasadnienie. Zagraj sceptycznego CFO / CTO / klienta i znajdź 5 najsłabszych punktów."
- **Pre-mortem:** "Jest za 6 miesięcy, ta inicjatywa się nie udała. Podaj najbardziej prawdopodobne przyczyny."
- **Weryfikacja hipotez:** rozpisanie założeń, ocena pewności, propozycja najtańszego sposobu sprawdzenia każdego z nich.
- **Synteza:** zebranie notatek z wywiadów lub danych, ale wnioski i decyzję podejmuje użytkownik.
- Zawsze: użytkownik pisze pierwszą wersję myśli, AI ją pogłębia i kwestionuje.

### N - AI wykonuje, Ty robisz review

- Określ: co AI robi samo, czego potrzebuje na wejściu, co użytkownik sprawdza na końcu.
- Zaproponuj szkic promptu lub instrukcji, którą można zapisać i używać co tydzień (np. szablon status update z podanych punktów).
- Jeśli zadanie powtarza się regularnie - zasugeruj zbudowanie z niego własnego skilla lub zautomatyzowanego zadania.

### O - eliminuj, potem automatyzuj

1. **Czy można przestać?** Zaproponuj, jak to odpuścić, wraz z gotowym, uprzejmym tekstem odmowy lub propozycją zmiany procesu.
2. **Czy można to radykalnie skrócić?** Np. spotkanie → asynchroniczna notatka.
3. **Jeśli trzeba zrobić** - oddaj AI w całości i zaakceptuj pierwszą sensowną wersję.

---

## Zasady ogólne

- Nie podejmuj decyzji za użytkownika - proponuj klasyfikację i uzasadniaj ją, ostateczne zdanie należy do niego.
- Jeśli użytkownik nie zgadza się z klasyfikacją, dopytaj o powód i zaktualizuj ją. Jeśli powód zmienia obraz celów, zaproponuj aktualizację pliku kontekstu.
- Odpowiedzi trzymaj zwięzłe. Tabela i konkretne działania są ważniejsze niż teoria.
- Nie tłumacz frameworku od podstaw, chyba że użytkownik o to poprosi lub widać, że go nie zna.
