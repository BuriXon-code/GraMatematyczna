# Gra matematyczna!
## O grze...

### Gra polega na rozwiązywaniu zadań matematycznych o różnym poziomie trudności.

Do wyboru są 4 poziomy trudności różniących się między sobą rodzajem i trudnością poszczególnych zadań.

Gra dedykowana jest dzieciom bądź rodzicom dzieci uczących się działania z podstawowymi funktorami matematycznymi takimi jak dodawanie, odejmowanie, mnożenie czy potęgowanie.

### Gra została stworzona i działa w języku **polskim**; dostępna w wersji z i bez polskich znaków.

Plik "**gra**" to plik z grą w pełnej wersji, z tekstami zawierającymi polskie znaki.

Z kolei "**gra2**" nie zawiera polskich znaków, co wpływa jedynie na jej czytelność, nie burząc działania.

### Gra jest w 100% skryptem shell'owym.

Nie zawiera żadnych poleceń poza funkcjami bash oraz wbudowanymi komendami coreutils.

Nie wymaga instalacji dodatkowych pakietów.

## Aby zagrać w grę należy ...

Posiadać zainstalowany bash oraz coreutils.

### Pobieranie i instalacja :

```
git clone https://github.com/BuriXon-code/GraMatematyczna
cd GraMatematyczna
chmod +x gra*
```
### Uruchamianie :
```
./gra #aby uruchomić grę obsługującą polskie znaki
```
lub
```
./gra2 # aby uruchomić grę niezawierającą polskich znaków
```

### Przed pierwszym uruchomieniem :
Przed pierwszym uruchomieniem zalecane jest użycie flagi -h lub --help, aby zapoznać się z instrukcją dotyczącą gry.
```
./gra --help
```
lub 
```
./gra -h
```
lub 
```
./gra2 --help
```
lub 
```
./gra2 -h
```

## Możliwość zatrzymania skryptu - hasło administratora (rodzica) :
### Gra została zabezpieczona przed próbą zatrzymania sygnałem SIGINT (CTRL+C). Aby jednak ją zatrzymać, należy posiadać hasło administratora.
