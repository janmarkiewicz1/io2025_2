# Ulubiony serial - Ted Lasso

### Zadanie 1 - Ted Lasso
Twoim zadaniem jest obliczenie liczby punktów zdobytych przez AFC Richmond w 1. sezonie oraz sprawdzenie czy udało się zdobyć mistrzostwo. Za jedno zwycięstwo przyznawane są 3 punkty, za remis 1 punkt, za przegraną 0 punktów. Jeśli liczba punktów będzie wyższa niż 80 punktów to oznacza, że AFC Richmond zostało mistrzem Anglii w tym sezonie, w innym wypadku zajęli niższe miejsce. Zadanie powinno być stworzona jako funkcja o nazwie mistrz_ted_lasso

Dane wejściowe: 15 zwycięstw (int), 8 remisów (int), 12 porażek (int)

Dane wyjściowe: string (ile AFC Richmond ma punktów i czy są mistrzami czy nie)

```python
wynik = int
def mistrz_ted_lasso(zwyciestwo, remis, przegrana):
    wynik = 3 * zwyciestwo + 1 * remis + 0 * przegrana
    return wynik
mistrz_ted_lasso(15, 8, 12)
```
