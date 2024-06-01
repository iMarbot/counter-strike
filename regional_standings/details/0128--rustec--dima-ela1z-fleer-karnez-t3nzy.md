### Roster Details<br />
Team Name: Rustec<br />
Roster: Dima, eLa1z, Fleer, KaRnez, t3nzy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [128](../standings_global.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
Final Rank Value:  811.9<br />
<br />
Final Rank Value (811.9) = Starting Rank Value (809.6) + Head To Head Adjustments (2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.193[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 809.6
- 400 + ( ( 0.201 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 809.6


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
|           21 |      262 | 2024-05-25 | Permitta Esports          | W   | 1.000      | 0.372        | 0.029 (0.011)    | 1.000 (0.372)    | 0 (0.000) |    15.40 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           20 |      267 | 2024-05-25 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -14.78 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           19 |      339 | 2024-05-24 | polizej                   | L   | 1.000      | -            | -                | -                | -         |   -26.12 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           18 |      347 | 2024-05-24 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -20.22 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           17 |      487 | 2024-05-22 | Team Spirit Academy       | W   | 1.000      | 0.372        | -                | 0.192 (0.071)    | 0 (0.000) |    12.36 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           16 |      592 | 2024-05-21 | ex-Turów Zgorzelec Esport | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.375 (0.140)    | 0 (0.000) |    12.10 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           15 |      676 | 2024-05-20 | MOUZ NXT                  | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.950 (0.353)    | 0 (0.000) |    23.64 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           14 |      685 | 2024-05-20 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -12.15 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           13 |     1075 | 2024-05-16 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -20.64 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           12 |     1140 | 2024-05-15 | 1win                      | W   | 1.000      | 0.372        | 0.050 (0.019)    | 0.887 (0.330)    | 0 (0.000) |    23.11 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           11 |     1157 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.510 (0.190)    | 0 (0.000) |    17.90 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|           10 |     1247 | 2024-05-14 | los kogutos               | L   | 1.000      | -            | -                | -                | -         |   -11.54 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            9 |     1264 | 2024-05-14 | kONO.ECF                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.778 (0.290)    | 0 (0.000) |    21.05 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            8 |     2551 | 2024-04-20 | Soda Gaming               | L   | 0.938      | -            | -                | -                | -         |   -22.96 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            7 |     2556 | 2024-04-20 | Quixal                    | W   | 0.937      | 0.143        | 0.002 (0.000)    | 0.245 (0.033)    | 0 (0.000) |     9.12 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            6 |     2768 | 2024-04-18 | VaselineWorms             | W   | 0.923      | 0.372        | 0.000 (0.000)    | 0.424 (0.146)    | 0 (0.000) |     9.43 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            5 |     4214 | 2024-03-18 | Marsupy Gaming            | W   | 0.717      | 0.284        | 0.001 (0.000)    | 0.019 (0.004)    | 0 (0.000) |     6.10 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            4 |     4363 | 2024-03-15 | Orgless                   | W   | 0.698      | 0.284        | 0.000 (0.000)    | -                | -         |     3.92 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            3 |     5398 | 2024-02-26 | V1dar Gaming              | L   | 0.578      | -            | -                | -                | -         |   -11.71 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            2 |     5860 | 2024-02-18 | unluckyday                | L   | 0.525      | -            | -                | -                | -         |   -11.68 | Dima, eLa1z, Fleer, KaRnez, t3nzy |
|            1 |     8030 | 2024-01-10 | HEROIC                    | L   | 0.264      | -            | -                | -                | -         |    -0.04 | Dima, eLa1z, f0lya, KaRnez, t3NZY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($770.47)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-18 |      0.717 | $1,000.00      | $716.81         |
| 2024-02-20 |      0.537 | $100.00        | $53.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
