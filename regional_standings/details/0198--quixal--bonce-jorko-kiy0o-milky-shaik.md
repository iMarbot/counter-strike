### Roster Details<br />
Team Name: Quixal<br />
Roster: bonce, Jorko, kiy0o, milky, shaiK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [198](../standings_global.md)<br />
Regional Rank: [134]( ../standings_europe.md)<br />
Final Rank Value:  725.0<br />
<br />
Final Rank Value (725.0) = Starting Rank Value (662.4) + Head To Head Adjustments (62.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 662.4
- 400 + ( ( 0.129 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 662.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |       53 | 2024-05-29 | Oxuji Esports      | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.037 (0.012)    | 0 (0.000) |     7.29 | bonce, Jorko, kiy0o, milky, shaiK        |
|           15 |      787 | 2024-05-19 | Grannys Knockers   | L   | 1.000      | -            | -                | -                | -         |   -12.65 | bonce, Jorko, kiy0o, milky, shaiK        |
|           14 |      861 | 2024-05-18 | ENTERPRISE esports | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.809 (0.116)    | 0 (0.000) |    23.72 | bonce, Jorko, kiy0o, milky, shaiK        |
|           13 |      869 | 2024-05-18 | Lazer Cats         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.228 (0.033)    | 0 (0.000) |    17.68 | bonce, Jorko, kiy0o, milky, shaiK        |
|           12 |      882 | 2024-05-18 | ROSOMAHA           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.124 (0.018)    | 0 (0.000) |    11.42 | bonce, Jorko, kiy0o, milky, shaiK        |
|           11 |      889 | 2024-05-18 | Illuminar Gaming   | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.403 (0.058)    | 0 (0.000) |    20.84 | bonce, Jorko, kiy0o, milky, shaiK        |
|           10 |     1383 | 2024-05-12 | L&G                | L   | 1.000      | -            | -                | -                | -         |   -10.30 | bonce, Jorko, kiy0o, milky, shaiK        |
|            9 |     1391 | 2024-05-12 | ROAD2ROAD          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.77 | bonce, Jorko, kiy0o, milky, shaiK        |
|            8 |     2556 | 2024-04-20 | Rustec             | L   | 0.937      | -            | -                | -                | -         |    -9.12 | Jorko, kiy0o, milky, s1an, shaiK         |
|            7 |     4024 | 2024-03-22 | Falcons Esport     | L   | 0.745      | -            | -                | -                | -         |   -12.06 | bonce, Jorko, kiy0o, nibito, s1an        |
|            6 |     4070 | 2024-03-21 | Banger Gang        | W   | 0.738      | 0.310        | 0.002 (0.000)    | 0.046 (0.011)    | 0 (0.000) |    10.68 | gAndhi, hatex, licaNy, Rip, Viresse      |
|            5 |     4123 | 2024-03-20 | ex-RED             | W   | 0.731      | 0.310        | 0.001 (0.000)    | 0.065 (0.015)    | 0 (0.000) |    10.04 | bonce, Jorko, kiy0o, nibito, s1an        |
|            4 |     4159 | 2024-03-19 | Ravens Esports     | W   | 0.725      | 0.310        | 0.001 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     7.34 | Latent, PRoZZoR, stan, SuperMarioM8, Yin |
|            3 |     4194 | 2024-03-18 | Coolermaster       | W   | 0.718      | 0.310        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     4.65 | duster, h4br, LESHIYvls, st1per, wacko   |
|            2 |     4468 | 2024-03-13 | Banger Gang        | L   | 0.685      | -            | -                | -                | -         |   -11.20 | gAndhi, hatex, licaNy, Rip, Viresse      |
|            1 |     8822 | 2023-12-13 | HEYDERS            | L   | 0.078      | -            | -                | -                | -         |    -1.52 | bonce, Dafra1D, Jorko, kiy0o, s1an       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($525.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
