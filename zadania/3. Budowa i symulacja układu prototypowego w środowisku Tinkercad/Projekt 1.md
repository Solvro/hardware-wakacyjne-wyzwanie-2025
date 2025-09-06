### ***Najdejszła wiekopomna*** chwila ~
Zadaniem waszym jest zaprojektowanie, złożenie i zaprogramowanie zegarka w środowisku Tinkercad.
Korzystamy z ograniczonych zasobów środowiska symulacyjnego dlatego pierwszym waszym podzadaniem będzie stworzenie podobnych komponentów do naszych tj.
1. Zrobić z 4 jednocyfrowych wyświetlaczy 7-seg  jeden czterocyfrowy. (Wspólna anoda)
2. Podłączyć piny z odpowiednimi resystorami żeby diody nie wybuchły.
3. Podłączyć piezo i tmp36

4. Połączyć przyciski (czy dać rezystor w szeregu czy nie? A jeśli tak to czemu?)

Będą dodatkowe punkty za estetyczne poprowadzenie kabelków.

# Połączone? No to program

Pamiętajcie że ten program steruje fizyczną elektroniką (tutaj w symulatorze, ale IRL na płytce nie ma przebacz)

Program się musi składać z m.in.:
- zadeklarowania co robi dany pin
- przemiatania wyświetlacza
- kombinacji cyfra->kod na 7seg
- odczytu stanu przycisku
- handlera przycisków
- handlera buzzera
- handlera TMP36 

Handler przycisków ma pozwolić na wyświetlenie temperatury i zmianę godziny, ale jak dodacie jakieś funkcje to się nie obrażę

Buzzer niech też chociaż raz zabrzmi

Magiczny wzór na temperaturę z tmp36:
```c
  int odczyt = analogRead(TEMP_PIN);
  float napiecie = odczyt * (5.0 / 1023.0);
  float temperatura = (napiecie - 0.5) * 100.0;
```


Jak pewnie się domyślacie, chatgpt robi to w 5 sekund, ALE
- prawdopodobnie coś zepsuje i trzeba będzie naprawić
- napisze wam kod, który jak już zadziała, to nie będziecie wiedzieli jak działa

Stąd wielka prośba. Postarajcie się sami to napisać. Jak nie będzie wychodziło to ofc korzystajcie z narzędzi jakich chcecie, ale przez cały czas miejcie kontrolę i wiedzę nad tym co jest napisane w środku.

Jedyne co potrzebne mi jest to link do waszej symulacji z możliwością zobaczenia kodu (pls, kodu nie bloczków)

Pozostaje mi jedynie życzyć wam powodzenia :innocent: