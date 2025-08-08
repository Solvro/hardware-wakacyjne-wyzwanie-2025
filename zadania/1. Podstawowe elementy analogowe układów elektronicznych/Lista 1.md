# Zadania: Podstawowe elementy analogowe układów elektronicznych

## 1. Rezystancja zastępcza
- **Zadanie**: Oblicz rezystancję zastępczą dla kilku połączonych rezystorów (szeregowo, równolegle, mieszanie).
- **Cel**: Zrozumieć jak obliczać Rz w różnych konfiguracjach.
- **Przypominajka**: Rezystancję zastępczą dla oporników ustawionych szeregowo liczymy dodając ich wartości, a ustawionych równolegle dodając odwrotności ich wartości, czyli np. 1/R 

![Zadanie 1](Zadanie%201/zadanie1.png)


## 2. Dzielnik napięcia
- **Zadanie**: Zaprojektuj dzielnik napięcia z 12 V na 5 V.
- **Cel**: Umieć wyliczyć wartości R1 i R2 dla konkretnego napięcia wyjściowego.
- **Przypominajka**: Dzielnik napięcia polega na stosunku rezystancji oporników, Przyda się tu wzór Uwy = Uwe × (R2 / (R1 + R2))

![Zadanie 2](Zadanie%202/zadanie2.png)

## 3. Dobór rezystora do diod LED
- **Zadanie**: Oblicz wartość rezystora R dla dwóch diod LED wytrzymujących maksymalnie 15 mA w szeregu.
- **Cel**: Wiedzieć jak dobrać rezystor do ograniczenia prądu w układzie z diodami.
- **Przypominajka**:  Prawo Ohma w typowym wydaniu. R = (Uzas - Udiody) / I. Dioda jak będzie miała mniej prądu niż wartość maksymalna to będzie ciemniej świecić - Ale ma świecić i sie nie spalić :smile:

![Zadanie 3](Zadanie%203/zadanie3.png)

## 4. Tranzystor NPN jako przełącznik
- **Zadanie**: Zbuduj układ z tranzystorem NPN działającym w trybie kluczowania (przełącznik). Twoim celem jest sterowanie diodą LED tak, aby świeciła tylko wtedy, gdy do bazy tranzystora podany jest odpowiedni sygnał. Dobierz rezystor bazowy R1, który zapewni wystarczający prąd bazy, by tranzystor wszedł w stan nasycenia.

- **Dane do zadania**:
  - Zasilanie: 5 V
  - Dioda LED: max 15 mA
  - Spadek napięcia na LED: ~2.0 V
  - Spadek napięcia kolektor-emiter w nasyceniu: U<sub>CE(sat)</sub> ≈ 0.2 V
  - Spadek napięcia baza-emiter: U<sub>BE</sub> ≈ 0.7 V
  - Załóż wymagany prąd bazy: I<sub>B</sub> = 1.5 mA (dla zapewnienia nasycenia)

Cel:
Zrozumieć działanie tranzystora jako przełącznika prądowego, w którym mały prąd bazy steruje większym prądem kolektora.

![Zadanie 4](Zadanie%204/zadanie4.png)

## 5. Odczytywanie wartości z rezystorów
- **Zadanie**: Odczytaj wartość z rezystora SMD i THT (kolorowy kod paskowy / oznaczenia cyfrowe).
- **Cel**: Umieć rozpoznać i zidentyfikować wartość rezystancji z oznaczeń.

![Zadanie 5 THT](Zadanie%205/zadanie5_THT.webp)

![Zadanie 5 SMD](Zadanie%205/zadanie5_SMD.jpg)

## 6. Podłączenie mierników
- **Zadanie**: Podłącz do układu woltomierz i amperomierz tak aby zmierzyć ile prądu i napięcia jest wykorzystywane przez diodę led.
- **Cel**: Wiedzieć gdzie i jak poprawnie wpiąć mierniki w obwód (równolegle/szeregowo).

![Zadanie 6](Zadanie%206/zadanie6.png)
