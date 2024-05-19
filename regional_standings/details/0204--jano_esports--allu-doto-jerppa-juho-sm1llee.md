### Roster Details<br />
Team Name: JANO Esports<br />
Roster: allu, doto, Jerppa, juho, Sm1llee<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [204](../standings_global.md)<br />
Regional Rank: [136]( ../standings_europe.md)<br />
Final Rank Value:  709.8<br />
<br />
Final Rank Value (709.8) = Starting Rank Value (769.0) + Head To Head Adjustments (-59.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.311[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.186<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.0
- 400 + ( ( 0.186 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 769.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      359 | 2024-04-27 | Sashi Esport           | L   | 1.000      | -            | -                | -                | -             |    -1.45 | allu, doto, Jerppa, juho, Sm1llee    |
|           39 |      379 | 2024-04-27 | Heimo Esports          | L   | 1.000      | -            | -                | -                | -             |   -14.35 | allu, doto, Jerppa, juho, Sm1llee    |
|           38 |      402 | 2024-04-26 | Sashi Esport           | L   | 1.000      | -            | -                | -                | -             |    -1.59 | allu, doto, Jerppa, juho, Sm1llee    |
|           37 |      406 | 2024-04-26 | Preasy Esport          | L   | 1.000      | -            | -                | -                | -             |   -16.75 | allu, doto, Jerppa, juho, Sm1llee    |
|           36 |      412 | 2024-04-26 | Static                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.226 (0.032)    | false (0.000) |     7.21 | allu, doto, Jerppa, juho, Sm1llee    |
|           35 |      418 | 2024-04-26 | 777 Esports            | L   | 1.000      | -            | -                | -                | -             |   -16.91 | allu, doto, Jerppa, juho, Sm1llee    |
|           34 |      425 | 2024-04-26 | Esport Harte           | W   | 1.000      | -            | -                | -                | false (0.000) |     8.84 | allu, doto, Jerppa, juho, Sm1llee    |
|           33 |      441 | 2024-04-26 | GamerLegion Academy    | L   | 1.000      | -            | -                | -                | -             |    -9.45 | allu, doto, Jerppa, juho, Sm1llee    |
|           32 |      476 | 2024-04-25 | Turów Zgorzelec Esport | W   | 1.000      | 0.371        | 0.019 (0.007)    | 0.640 (0.238)    | false (0.000) |    16.97 | Aerial, allu, Cliqq, Jerppa, Sm1llee |
|           31 |      519 | 2024-04-24 | LEON Esports           | L   | 1.000      | -            | -                | -                | -             |   -17.92 | Aerial, allu, Cliqq, Jerppa, Sm1llee |
|           30 |      586 | 2024-04-23 | LEON Esports           | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.357 (0.051)    | false (0.000) |    13.39 | allu, doto, Jerppa, juho, Sm1llee    |
|           29 |      596 | 2024-04-22 | GamerLegion Academy    | L   | 1.000      | -            | -                | -                | -             |   -10.46 | allu, doto, Jerppa, juho, Sm1llee    |
|           28 |      717 | 2024-04-20 | HAVU Gaming            | W   | 1.000      | 0.143        | 0.024 (0.003)    | 0.213 (0.030)    | false (0.000) |    17.17 | allu, doto, Jerppa, juho, Sm1llee    |
|           27 |      777 | 2024-04-20 | Sangal Esports         | L   | 1.000      | -            | -                | -                | -             |   -12.98 | allu, doto, Jerppa, juho, Sm1llee    |
|           26 |      829 | 2024-04-19 | NOM Esports            | W   | 1.000      | 0.143        | -                | 0.374 (0.053)    | false (0.000) |    13.45 | allu, doto, Jerppa, juho, Sm1llee    |
|           25 |      970 | 2024-04-17 | RUBY                   | L   | 1.000      | -            | -                | -                | -             |    -8.43 | allu, doto, Jerppa, juho, Sm1llee    |
|           24 |      982 | 2024-04-17 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -             |    -4.64 | allu, doto, Jerppa, juho, Sm1llee    |
|           23 |     1037 | 2024-04-15 | VP.Prodigy             | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.762 (0.283)    | false (0.000) |    19.83 | Aerial, allu, Cliqq, Jerppa, Sm1llee |
|           22 |     1045 | 2024-04-15 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -             |    -4.34 | Aerial, allu, Cliqq, Jerppa, Sm1llee |
|           21 |     1076 | 2024-04-14 | Heimo Esports          | L   | 1.000      | -            | -                | -                | -             |   -15.36 | allu, doto, Jerppa, juho, Sm1llee    |
|           20 |     1154 | 2024-04-12 | Zero Tenacity          | W   | 1.000      | 0.371        | 0.095 (0.035)    | 1.000 (0.371)    | false (0.000) |    22.34 | allu, doto, Jerppa, juho, Sm1llee    |
|           19 |     1353 | 2024-04-08 | Permitta Esports       | L   | 1.000      | -            | -                | -                | -             |    -8.54 | allu, doto, Jerppa, juho, Sm1llee    |
|           18 |     1407 | 2024-04-06 | Johnny Speeds          | L   | 1.000      | -            | -                | -                | -             |    -9.91 | allu, doto, Jerppa, juho, Sm1llee    |
|           17 |     2170 | 2024-03-16 | HANE                   | L   | 0.865      | -            | -                | -                | -             |   -21.81 | allu, doto, jelo, Jerppa, Sm1llee    |
|           16 |     2216 | 2024-03-15 | Regnum                 | L   | 0.858      | -            | -                | -                | -             |   -17.11 | allu, doto, jelo, Jerppa, Sm1llee    |
|           15 |     2543 | 2024-03-08 | INGLORIOUS             | W   | 0.810      | 0.384        | 0.005 (0.002)    | 0.358 (0.111)    | false (0.000) |    15.55 | allu, doto, jelo, Jerppa, Sm1llee    |
|           14 |     2767 | 2024-03-04 | Endpoint               | L   | 0.784      | -            | -                | -                | -             |    -9.86 | allu, doto, jelo, Jerppa, Sm1llee    |
|           13 |     2831 | 2024-03-02 | Gaimin Gladiators      | L   | 0.773      | -            | -                | -                | -             |    -0.86 | allu, doto, jelo, Jerppa, Sm1llee    |
|           12 |     2853 | 2024-03-02 | Linx Legacy Madagaskar | W   | 0.772      | -            | -                | -                | false (0.000) |     3.99 | allu, doto, jelo, Jerppa, Sm1llee    |
|           11 |     3953 | 2024-02-03 | Heimo Esports          | L   | 0.585      | -            | -                | -                | -             |   -10.55 | allu, doto, jelo, Jerppa, Sm1llee    |
|           10 |     3961 | 2024-02-03 | Northern Star Gaming   | W   | 0.585      | -            | -                | -                | -             |     1.93 | allu, doto, jelo, Jerppa, Sm1llee    |
|            9 |     4185 | 2024-01-29 | 9Pandas                | L   | 0.553      | -            | -                | -                | -             |    -1.98 | allu, doto, jelo, Jerppa, Sm1llee    |
|            8 |     4598 | 2024-01-19 | Permitta Esports       | L   | 0.486      | -            | -                | -                | -             |    -3.59 | Aerial, allu, doto, jelo, Sm1llee    |
|            7 |     4646 | 2024-01-18 | OG                     | L   | 0.479      | -            | -                | -                | -             |    -0.71 | Aerial, allu, doto, jelo, Sm1llee    |
|            6 |     4662 | 2024-01-18 | 3DMAX                  | L   | 0.478      | -            | -                | -                | -             |    -4.26 | Aerial, allu, doto, jelo, Sm1llee    |
|            5 |     4774 | 2024-01-16 | Aurora Young Blud      | W   | 0.467      | 0.143        | 0.017 (0.001)    | 0.422 (0.028)    | -             |     8.48 | Aerial, allu, doto, jelo, Sm1llee    |
|            4 |     4778 | 2024-01-16 | Ex-Anonymo Esports     | W   | 0.466      | 0.143        | 0.019 (0.001)    | -                | -             |     8.08 | Aerial, allu, doto, jelo, Sm1llee    |
|            3 |     4791 | 2024-01-16 | 9INE                   | W   | 0.466      | -            | -                | -                | -             |     4.05 | Aerial, allu, doto, jelo, Sm1llee    |
|            2 |     4810 | 2024-01-16 | INGLORIOUS             | W   | 0.465      | 0.143        | 0.005 (0.000)    | 0.358 (0.024)    | -             |     7.84 | Aerial, allu, doto, jelo, Sm1llee    |
|            1 |     4930 | 2024-01-12 | Nexus Gaming           | L   | 0.439      | -            | -                | -                | -             |    -4.46 | Aerial, allu, doto, jelo, Sm1llee    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($956.32)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $802.70        | $802.70         |
| 2024-03-18 |      0.878 | $175.00        | $153.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
