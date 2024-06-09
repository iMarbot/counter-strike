### Roster Details<br />
Team Name: Rustec<br />
Roster: Dima, eLa1z, Fleer, KaRnez, t3nzy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [121](../standings_global.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
Final Rank Value:  830.0<br />
<br />
Final Rank Value (830.0) = Starting Rank Value (817.9) + Head To Head Adjustments (12.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 817.9
- 400 + ( ( 0.206 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 817.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      270 | 2024-05-25 | Permitta Esports          | W   | 1.000      | 0.372        | 0.025 (0.009)    | 1.000 (0.372)    | 0 (0.000) |    15.23 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           22 |      275 | 2024-05-25 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -15.23 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           21 |      348 | 2024-05-24 | polizej                   | L   | 1.000      | -            | -                | -                | -         |   -26.57 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           20 |      356 | 2024-05-24 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -20.78 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           19 |      493 | 2024-05-22 | Team Spirit Academy       | W   | 1.000      | 0.372        | -                | 0.219 (0.082)    | 0 (0.000) |    12.65 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           18 |      603 | 2024-05-21 | ex-Turów Zgorzelec Esport | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.491 (0.183)    | 0 (0.000) |    13.17 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           17 |      687 | 2024-05-20 | MOUZ NXT                  | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.977 (0.364)    | 0 (0.000) |    23.30 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           16 |      696 | 2024-05-20 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -12.41 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           15 |     1085 | 2024-05-16 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -21.18 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           14 |     1149 | 2024-05-15 | 1win                      | W   | 1.000      | 0.372        | 0.050 (0.019)    | 0.898 (0.334)    | 0 (0.000) |    22.34 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           13 |     1166 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.579 (0.216)    | 0 (0.000) |    17.59 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           12 |     1257 | 2024-05-14 | los kogutos               | L   | 1.000      | -            | -                | -                | -         |   -12.52 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           11 |     1275 | 2024-05-14 | kONO.ECF                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.853 (0.318)    | 0 (0.000) |    20.51 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           10 |     2604 | 2024-04-20 | Soda Gaming               | L   | 0.938      | -            | -                | -                | -         |   -23.08 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            9 |     2609 | 2024-04-20 | Quixal                    | W   | 0.937      | 0.143        | 0.002 (0.000)    | 0.245 (0.033)    | 0 (0.000) |     8.36 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            8 |     2824 | 2024-04-18 | VaselineWorms             | W   | 0.923      | 0.372        | 0.000 (0.000)    | 0.418 (0.144)    | 0 (0.000) |     8.53 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            7 |     2959 | 2024-04-16 | ex-KRC Genk Esports       | W   | 0.911      | 0.372        | -                | 0.173 (0.058)    | 0 (0.000) |     8.77 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            6 |     4234 | 2024-03-20 | GYROCOPTER_UA             | W   | 0.731      | 0.284        | 0.001 (0.000)    | -                | -         |     7.13 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            5 |     4319 | 2024-03-18 | Marsupy Gaming            | W   | 0.717      | 0.284        | 0.001 (0.000)    | -                | -         |     5.90 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            4 |     4471 | 2024-03-15 | Orgless                   | W   | 0.698      | -            | -                | -                | -         |     3.78 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            3 |     5555 | 2024-02-26 | V1dar Gaming              | L   | 0.578      | -            | -                | -                | -         |   -11.56 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            2 |     6032 | 2024-02-18 | unluckyday                | L   | 0.525      | -            | -                | -                | -         |   -11.83 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            1 |     8284 | 2024-01-10 | HEROIC                    | L   | 0.264      | -            | -                | -                | -         |    -0.04 | Dima, eLa1z, f0lya, KaRnez, t3NZY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($784.36)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.731 | $1,000.00      | $730.69         |
| 2024-02-20 |      0.537 | $100.00        | $53.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
