### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [83](../standings_global.md)<br />
Regional Rank: [61]( ../standings_europe.md)<br />
Final Rank Value:  888.2<br />
<br />
Final Rank Value (888.2) = Starting Rank Value (844.6) + Head To Head Adjustments (43.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.070[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.6
- 400 + ( ( 0.224 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 844.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      816 | 2024-04-19 | Crescent (Female team) | W   | 1.000      | 0.331        | 0.008 (0.003)    | 0.187 (0.062)    | 0 (0.000) |     6.87 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |      999 | 2024-04-16 | Team Pigeons           | W   | 1.000      | 0.303        | 0.094 (0.029)    | 0.402 (0.122)    | 0 (0.000) |    18.93 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     1043 | 2024-04-15 | NIP Impact             | W   | 1.000      | 0.303        | 0.011 (0.003)    | 0.344 (0.104)    | 0 (0.000) |    11.68 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     1070 | 2024-04-14 | Astralis Women         | W   | 1.000      | 0.303        | 0.007 (0.002)    | 0.101 (0.031)    | 0 (0.000) |     6.58 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     1115 | 2024-04-13 | Team Pigeons           | L   | 1.000      | -            | -                | -                | -         |   -11.87 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     1181 | 2024-04-11 | Team Spirit Female     | W   | 1.000      | 0.303        | 0.011 (0.003)    | 0.205 (0.062)    | 0 (0.000) |     7.89 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     1292 | 2024-04-09 | NIP Impact             | L   | 1.000      | -            | -                | -                | -         |   -19.74 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     1483 | 2024-04-04 | Team Spirit Female     | W   | 0.992      | 0.331        | 0.011 (0.004)    | 0.205 (0.067)    | 0 (0.000) |     8.81 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     1533 | 2024-04-03 | Let Her Cook           | L   | 0.985      | -            | -                | -                | -         |   -26.05 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     2261 | 2024-03-14 | 1win Gang              | W   | 0.852      | -            | -                | -                | 0 (0.000) |     5.42 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     2610 | 2024-03-06 | Fearless Cheetahs      | W   | 0.799      | 0.331        | 0.014 (0.004)    | 0.199 (0.053)    | -         |     7.12 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     3106 | 2024-02-25 | BIG EQUIPA             | W   | 0.731      | 0.143        | -                | 0.300 (0.031)    | -         |     7.04 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     3111 | 2024-02-25 | ENCE Athena            | W   | 0.730      | -            | -                | -                | -         |     7.02 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     3165 | 2024-02-24 | Crescent (Female team) | W   | 0.724      | -            | -                | -                | -         |     7.03 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     3917 | 2024-02-04 | VIOLET                 | W   | 0.592      | -            | -                | -                | -         |     4.42 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     5724 | 2023-12-10 | Team Pigeons           | L   | 0.218      | -            | -                | -                | -         |    -3.10 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     5731 | 2023-12-10 | Fluxo Demons           | W   | 0.217      | 0.524        | 0.065 (0.007)    | 0.289 (0.033)    | 1 (0.217) |     4.30 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     5779 | 2023-12-09 | FURIA Esports Female   | W   | 0.210      | 0.524        | 0.048 (0.005)    | -                | 1 (0.210) |     3.13 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     5834 | 2023-12-08 | NOFEAR5                | L   | 0.205      | -            | -                | -                | -         |    -4.19 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     5843 | 2023-12-08 | Shimmer                | W   | 0.204      | 0.524        | 0.026 (0.003)    | 0.354 (0.038)    | 1 (0.204) |     2.31 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,855.79)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-16 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-02-25 |      0.731 | $633.95        | $463.37         |
| 2024-02-04 |      0.592 | $750.00        | $443.92         |
| 2023-12-10 |      0.218 | $25,000.00     | $5,448.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
