### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: BaGyZ, MAGILA, Sidivo, slokkeR, StreakN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [127](../standings_global.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
Final Rank Value:  811.9<br />
<br />
Final Rank Value (811.9) = Starting Rank Value (774.9) + Head To Head Adjustments (37.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.9
- 400 + ( ( 0.184 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 774.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      235 | 2024-05-26 | EZ4ENCE             | W   | 1.000      | 0.143        | 0.005 (0.001)    | -                | 1 (1.000) |    10.93 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           23 |      465 | 2024-05-22 | Soda Gaming         | L   | 1.000      | -            | -                | -                | -         |   -23.65 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           22 |      481 | 2024-05-22 | UNiTY esports       | L   | 1.000      | -            | -                | -                | -         |   -13.34 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           21 |      500 | 2024-05-22 | FAVBET Team         | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.666 (0.248)    | 0 (0.000) |    23.20 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           20 |      565 | 2024-05-21 | ghoulsW             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.083 (0.012)    | 0 (0.000) |     5.34 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           19 |      593 | 2024-05-21 | GamerLegion Academy | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    17.43 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           18 |      759 | 2024-05-19 | Monte Gen           | L   | 1.000      | -            | -                | -                | -         |   -14.73 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           17 |      772 | 2024-05-19 | pByTy3              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |     5.18 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           16 |      787 | 2024-05-19 | Quixal              | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.245 (0.035)    | 0 (0.000) |    12.65 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           15 |      923 | 2024-05-18 | EZ4ENCE             | W   | 1.000      | 0.143        | 0.005 (0.001)    | -                | 0 (0.000) |    12.39 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           14 |      928 | 2024-05-18 | SACRAMENTO          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.083 (0.012)    | 0 (0.000) |    11.46 | BaGyZ, MAGILA, Sidivo, slokkeR, StreakN         |
|           13 |     1447 | 2024-05-11 | kONO.ECF            | L   | 1.000      | -            | -                | -                | -         |    -8.61 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           12 |     1453 | 2024-05-11 | Project G           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.46 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|           11 |     1518 | 2024-05-10 | ILLYRIANS           | L   | 1.000      | -            | -                | -                | -         |   -16.67 | BledarD, Caleyy, Dementor, HYPERI1, vAloN       |
|           10 |     1830 | 2024-05-04 | fragmatic           | W   | 1.000      | 0.143        | -                | 0.118 (0.017)    | -         |     7.86 | bodik, Litovka, mattloo, rinji2k, shiny         |
|            9 |     1835 | 2024-05-04 | Team Flow           | W   | 1.000      | 0.143        | -                | 0.165 (0.024)    | -         |     6.80 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|            8 |     1841 | 2024-05-04 | yengi               | W   | 1.000      | -            | -                | -                | -         |     3.44 | Frosty4k, LauriD, Tommy, VertZu, zmaiL          |
|            7 |     2493 | 2024-04-21 | Soda Gaming         | L   | 0.943      | -            | -                | -                | -         |   -21.67 | 2high, lunAtic, nestee, shadiy, snatchie        |
|            6 |     2550 | 2024-04-20 | RUSH B              | W   | 0.938      | 0.143        | 0.001 (0.000)    | 0.446 (0.060)    | -         |    16.18 | BaGyZ, MAGILA, Sidivo, slokker, StreakN         |
|            5 |     2568 | 2024-04-20 | TopTab Club         | W   | 0.937      | 0.143        | -                | 0.135 (0.018)    | -         |     5.93 | ADntZ, feetje, keembo, maQuein, rezn9           |
|            4 |     6701 | 2024-01-31 | ex-K10              | L   | 0.404      | -            | -                | -                | -         |    -5.36 | dox, Rezst, shyyne, Tree, yz0                   |
|            3 |     9030 | 2023-12-09 | Wolves eSports      | L   | 0.050      | -            | -                | -                | -         |    -1.10 | Berzius, Darkas, Misterio, OniX, PoKe           |
|            2 |     9450 | 2023-12-02 | FreeESPI            | L   | 0.004      | -            | -                | -                | -         |    -0.10 | fierre, maty, spardaus, tAk, tooizera           |
|            1 |     9499 | 2023-12-02 | Daugava             | W   | 0.002      | 0.143        | 0.000 (0.000)    | -                | 1 (0.002) |     0.01 | AwwEzz, BaGyZ, MAGILA, Prochas, Sidivo          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,657.74)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $1,628.22      | $1,628.22       |
| 2023-12-17 |      0.103 | $218.15        | $22.48          |
| 2023-12-02 |      0.004 | $1,633.90      | $7.03           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
