### Roster Details<br />
Team Name: Sissi State Punks<br />
Roster: Cl34v3rs, farmaG, hayanh, OneLion, Spexy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [235](../standings_global.md)<br />
Regional Rank: [155]( ../standings_europe.md)<br />
Final Rank Value:  699.3<br />
<br />
Final Rank Value (699.3) = Starting Rank Value (672.7) + Head To Head Adjustments (26.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 672.7
- 400 + ( ( 0.134 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 672.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |       50 | 2024-05-29 | Lazer Cats          | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    16.15 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           21 |      282 | 2024-05-25 | ARROW               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.344 (0.049)    | 0 (0.000) |    18.36 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           20 |     1312 | 2024-05-13 | mYinsanity          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.124 (0.018)    | 0 (0.000) |    14.25 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           19 |     1351 | 2024-05-12 | ALTERNATE aTTaX     | L   | 1.000      | -            | -                | -                | -         |    -4.90 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           18 |     2072 | 2024-04-29 | TeamOrangeGaming    | L   | 0.997      | -            | -                | -                | -         |   -10.45 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           17 |     2189 | 2024-04-27 | TeamOrangeGaming    | L   | 0.983      | -            | -                | -                | -         |   -11.67 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           16 |     2453 | 2024-04-22 | Wave Esports        | W   | 0.950      | 0.143        | 0.001 (0.000)    | 0.143 (0.019)    | 0 (0.000) |    11.36 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           15 |     2953 | 2024-04-15 | SNOGARD Dragons     | L   | 0.903      | -            | -                | -                | -         |   -10.97 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           14 |     3279 | 2024-04-08 | EVOPLAY             | W   | 0.858      | 0.143        | 0.000 (0.000)    | 0.015 (0.002)    | 0 (0.000) |    10.75 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           13 |     3553 | 2024-04-03 | ARROW               | L   | 0.823      | -            | -                | -                | -         |   -11.57 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           12 |     3877 | 2024-03-26 | ALTERNATE aTTaX Evo | W   | 0.771      | 0.143        | 0.002 (0.000)    | 0.239 (0.026)    | 0 (0.000) |    12.76 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           11 |     3891 | 2024-03-26 | Pandaric eSports    | W   | 0.771      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.51 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           10 |     4292 | 2024-03-17 | SNOGARD Dragons     | L   | 0.709      | -            | -                | -                | -         |    -8.66 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            9 |     4303 | 2024-03-16 | ARROW               | L   | 0.705      | -            | -                | -                | -         |    -8.46 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            8 |     4378 | 2024-03-15 | Wave Esports        | W   | 0.697      | 0.143        | 0.001 (0.000)    | 0.143 (0.014)    | 0 (0.000) |     9.14 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            7 |     4415 | 2024-03-14 | SNOGARD Dragons     | W   | 0.691      | 0.143        | 0.004 (0.000)    | 0.137 (0.014)    | 0 (0.000) |    13.34 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            6 |     4846 | 2024-03-06 | EPIC DUDES          | W   | 0.638      | 0.143        | 0.000 (0.000)    | 0.042 (0.004)    | 0 (0.000) |     4.01 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            5 |     4875 | 2024-03-06 | TeamOrangeGaming    | L   | 0.637      | -            | -                | -                | -         |    -6.38 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            4 |     5076 | 2024-03-03 | TeamOrangeGaming    | L   | 0.618      | -            | -                | -                | -         |    -6.21 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            3 |     5169 | 2024-03-02 | Wave Esports        | L   | 0.611      | -            | -                | -                | -         |   -10.78 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            2 |     5690 | 2024-02-21 | OTHERSCANTBEAT      | W   | 0.545      | -            | -                | -                | -         |     3.01 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            1 |     7841 | 2024-01-12 | ex-sYnck            | L   | 0.278      | -            | -                | -                | -         |    -3.98 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,255.68)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.984 | $267.57        | $263.22         |
| 2024-03-26 |      0.771 | $216.79        | $167.20         |
| 2024-03-17 |      0.710 | $1,089.86      | $773.37         |
| 2024-03-06 |      0.638 | $81.34         | $51.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
