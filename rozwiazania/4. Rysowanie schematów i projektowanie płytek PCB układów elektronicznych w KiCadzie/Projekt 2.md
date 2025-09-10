# Zadanie – Projekt PCB i Oprogramowanie Zegarka

Cześć,  
nadeszła ta chwila, w której musicie się trochę **namęczyć**.  

## Schemat

Do wykonania macie **układ na płytce PCB**, ale żeby to powstało, potrzebny będzie **schemat**.  
Na GitHub wrzuciłem projekt startowy – pobieracie go i **do schematu dorabiacie czujnik temperatury**:  
- własny symbol,  
- własny footprint w standardowej obudowie **TO-92**.  

*(Resztę oszczędzam – generalnie to powtarzanie tego samego 😉 ale przejżyjcie sobie w wolnej chwili właściwości danych rozwiązań)*

---

## PCB
- Gdy skończycie schemat, dodajcie elementy do PCB.  
- Ułóżcie je **dowolnie**, ale tak, aby możliwe było zaprogramowanie przez **Arduino UNO R3** (odpowiednie piny).  
- Gotowy projekt **pushujecie na branch**.

---

## Komponenty
Korzystamy m.in. z tych elementów:  
- [mikroprzełącznik tact TE Connectivity](https://www.tme.eu/pl/details/1-1825910-4/mikroprzelaczniki-tact/te-connectivity/)  
- [wyświetlacz LED 7-segmentowy Vishay](https://www.tme.eu/pl/details/tdcr1050m/wyswietlacze-led-7-segmentowe/vishay/)  
- [sygnalizator piezo z generatorem CRE Sound](https://www.tme.eu/pl/details/lpb1475b-to-12/sygnalizatory-piezoelektr-z-generatorem/cre-sound--electronics/lpb1475b-to-12-4-0-7-6-r-lab/)  
- [czujnik temperatury TMP36GT9Z (Analog Devices)](https://www.tme.eu/pl/details/tmp36gt9z/przetworniki-temperatury/analog-devices/)

---

## Oprogramowanie zegarka
Dodatkowo proszę was o wykonanie **oprogramowania** zegarka. Nie od nowa, tylko skorzystajcie z programu z symulatora i po prostu go dostosujcie pod wasz projekcik PCB. **Daczego?**, a bo będziecie musieli to zrobić na stacjo pod nasz projekt, więc im więcej sobie przygotujecie wcześniej, tym będzie wam wygodniej i łatwiej  

Funkcjonalności:  
- wyświetlanie **godzin i minut**,  
- miganie **dwukropka** co kilkaset ms (np. 0,5 s),  
- wejście w **tryb zmiany godziny** po kliknięciu przycisku (np. pierwszego z lewej),  
- **miganie edytowanej cyfry**, aby wskazać aktualną pozycję,  
- możliwość **zwiększenia wartości** cyfry (np. 12:00 → 13:00) przyciskiem,  
- możliwość **zmiany pozycji edycji** (np. z godzin na minuty) innym przyciskiem,  
- wyświetlenie **aktualnej temperatury** po kliknięciu przycisku  
  (pamiętajcie, że mamy specjalnego LED-a na znak stopnia `°`).  

---
