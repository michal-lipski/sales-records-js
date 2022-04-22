Bonus Calculator
================
 
## Wymagania
 
### Indywidualny bonus dla sprzedawcy
 
Zadanie polega na zaimplementowaniu funkcjonalności wyliczenia bonusu jaki otrzyma sprzedawca w danym roku.
Każdy sprzedawca ma ustalony miesięczny plan sprzedażowy. Od sprzedaży która przekroczy plan dostaje bonus, wyliczony na podstawie prowizji, pomniejszony o podatek. Bonus roczny skład się z sumy bonusów za wszystkie miesiące w danym roku.
 
*Przykładowe założenia*
 
|Plan sprzedażowy (Traget)|   Prowizja (Commission)|   Podatek (Tax) | 
|-----|----------------------|-------------------------|
| 11 000 |    10%        |                        19%|

 
*Przykład wyliczenia bonusu*
 
|Suma sprzedaży  |Plan sprzedażowy (Target)|    Prowizja (Commission) |       Podatek (Tax)  | Bonus|
|----------|-----|----------------------|-------------------------|---|
|12 000    | 11 000 |    10%        |                        10%|                90.0|
|12 000    | 15 000 |    10% |                        10%|                0.0|
|12 000    | 12 000|    10% |                    10%|                0.0|
 
*Przykład zakładając plan sprzedażowy = 11 000, prowizję 10% i podatek 10%*:
 
|data|Sprzedaż|    	 
|---|-----|
|20.12.2019| 12 000 |
|25.03.2020| 1 000 |
|01.04.2020| 6 000 |
|10.04.2020| 6 000 |
|03.06.2020| 12 000 |

Wynikowy bonus za rok 2020 to 180 zł.
  
 
