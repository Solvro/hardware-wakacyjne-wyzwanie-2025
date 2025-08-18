# Lista 2 - Podstawowe elementy cyfrowe układów elektronicznych

## Zadanie 1
Zbuduj układ kombinacyjny (na poziomie bramek) wyświetlający na wyświetlaczu 7 segmentowym (jedna pozycja, 10 cyfr, no chyba, że chce Ci się również od A do F) liczbę zakodowaną w NKB (Naturalny Kod Binarny). Zapisz dla jakiego rodzaju wyświetlacza jest to enkoder (wspólna katoda/anoda).
[!wyświetlacz_7_seg](Zadanie%201/image.png)

## Zadanie 2
Przeanalizuj przebieg czasowy podanych sygnałów. Przyjmij założenie, że dane odczytywane są na **falling_edge**. A czas ustalania sygnału jest natychmiastowy. Zapisz jakie bity zostaną odczytane po stronie odbiornika (chronologicznie)
[!przebieg_czasowy_sygnału](Zadanie%202/image.png)

## Zadanie 3

Zbuduj układ **multipleksera 4:1** na bramkach.

**Co to znaczy?**  
Multiplekser (MUX) to taki elektroniczny „przełącznik”, który wybiera **jedno wejście z wielu** i podaje je dalej na wyjście.

-   „4:1” oznacza, że mamy **4 wejścia** (nazwijmy je `I0, I1, I2, I3`) i **1 wyjście** (`Y`).
    
-   Dodatkowo mamy **linie adresowe** (`A0`, `A1`), czyli takie „przyciski sterujące”, które decydują, które wejście zostanie podłączone do wyjścia.
    

**Zasada działania (przykład):**

-   jeśli `A1A0 = 00` → na wyjściu `Y` pojawia się to, co było na `I0`
    
-   jeśli `A1A0 = 01` → `Y = I1`
    
-   jeśli `A1A0 = 10` → `Y = I2`
    
-   jeśli `A1A0 = 11` → `Y = I3`
    

**Twoje zadanie:**

1.  Narysuj schemat multipleksera 4:1 w postaci bramek z wejściami, wyjściem i liniami adresowymi (dodatkowe wejścia).
    
2.  Zapisz tabelę prawdy (czyli tabelę, która pokazuje, które wejście trafia na wyjście przy danych wartościach `A1`, `A0`).

Źródła obrazków:
- [Betlux](https://betlux.com/product/seven-segment-led-displays-common-anode-common-cathode-circuit.jpg)
- [Forbot](https://cdn.forbot.pl/blog/wp-content/uploads/2016/11/kursTC_7_2_wyswietlacz_7_SEG_v2.png)