### Roster Details<br />
Team Name: los kogutos<br />
Roster: chudy2k, darchevile, Enzo, Nami, yvro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [100](../standings_global.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
Final Rank Value:  868.7<br />
<br />
Final Rank Value (868.7) = Starting Rank Value (819.4) + Head To Head Adjustments (49.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 819.4
- 400 + ( ( 0.206 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 819.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      407 | 2024-05-23 | EXO Clan                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.579 (0.216)    | 0 (0.000) |    13.21 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           17 |      595 | 2024-05-21 | Entropiq                  | L   | 1.000      | -            | -                | -                | -         |   -21.25 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           16 |      684 | 2024-05-20 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -16.92 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           15 |     1169 | 2024-05-15 | ENTERPRISE esports        | L   | 1.000      | -            | -                | -                | -         |   -14.95 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           14 |     1257 | 2024-05-14 | Rustec                    | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.328 (0.122)    | 0 (0.000) |    12.52 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           13 |     1536 | 2024-05-10 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |   -13.99 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           12 |     1635 | 2024-05-08 | ENRAGE                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.32 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           11 |     1651 | 2024-05-08 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -24.33 | chudy2k, darchevile, Enzo, Nami, yvro    |
|           10 |     1694 | 2024-05-07 | Endpoint                  | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.770 (0.287)    | 0 (0.000) |    18.24 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            9 |     1740 | 2024-05-06 | MOUZ NXT                  | W   | 1.000      | 0.372        | 0.157 (0.058)    | 0.977 (0.364)    | 0 (0.000) |    22.16 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            8 |     1851 | 2024-05-04 | L&G                       | W   | 1.000      | 0.289        | 0.006 (0.002)    | 0.442 (0.128)    | 0 (0.000) |    11.92 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            7 |     1952 | 2024-05-02 | Lazer Cats                | W   | 1.000      | 0.289        | 0.003 (0.001)    | -                | 0 (0.000) |     9.79 | chudy2k, darchevile, eltrzzi, Enzo, Nami |
|            6 |     2056 | 2024-04-30 | XI Esport                 | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.277 (0.080)    | 0 (0.000) |     7.34 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            5 |     2106 | 2024-04-29 | V1dar Gaming              | W   | 0.997      | 0.372        | -                | 0.595 (0.221)    | 0 (0.000) |    10.89 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            4 |     2153 | 2024-04-28 | Natus Vincere Junior      | W   | 0.989      | 0.289        | 0.006 (0.002)    | 0.444 (0.127)    | 0 (0.000) |    12.64 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            3 |     2345 | 2024-04-25 | Raptors Esports Club      | W   | 0.970      | 0.289        | 0.007 (0.002)    | 0.406 (0.114)    | -         |    16.86 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            2 |     2409 | 2024-04-24 | ex-Turów Zgorzelec Esport | L   | 0.964      | -            | -                | -                | -         |   -17.82 | chudy2k, darchevile, Enzo, Nami, yvro    |
|            1 |     2972 | 2024-04-16 | Rhyno Esports             | W   | 0.910      | 0.372        | 0.029 (0.010)    | 0.567 (0.192)    | -         |    19.67 | chudy2k, darchevile, Enzo, Nami, yvro    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
