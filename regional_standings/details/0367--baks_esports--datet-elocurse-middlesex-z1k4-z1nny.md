### Roster Details<br />
Team Name: BAKS Esports<br />
Roster: datet, elocurse, Middlesex, z1k4, z1Nny<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [367](../standings_global.md)<br />
Regional Rank: [219]( ../standings_europe.md)<br />
Final Rank Value:  593.8<br />
<br />
Final Rank Value (593.8) = Starting Rank Value (628.9) + Head To Head Adjustments (-35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 628.9
- 400 + ( ( 0.112 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 628.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       84 | 2024-05-29 | FORZE Youngsters    | L   | 1.000      | -            | -                | -                | -         |   -21.40 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           23 |      114 | 2024-05-28 | ZEROvariant         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    12.64 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           22 |      744 | 2024-05-19 | TopTab Club         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.135 (0.019)    | 0 (0.000) |    11.11 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           21 |      794 | 2024-05-19 | Team PeeP           | L   | 1.000      | -            | -                | -                | -         |   -16.15 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           20 |      910 | 2024-05-18 | ZEROvariant         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    10.79 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           19 |      969 | 2024-05-17 | LYG Gaming          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.275 (0.039)    | 0 (0.000) |    22.42 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           18 |      985 | 2024-05-17 | YYHuT-1             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.62 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           17 |     1195 | 2024-05-15 | 5x404               | L   | 1.000      | -            | -                | -                | -         |   -19.24 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           16 |     3851 | 2024-03-26 | MANGANES            | L   | 0.772      | -            | -                | -                | -         |   -14.45 | datet, elocurse, Middlesex, z1k4, z1Nny    |
|           15 |     5237 | 2024-03-01 | Kappa Bar           | L   | 0.603      | -            | -                | -                | -         |   -11.44 | datet, elocurse, Middlesex, reyoz, twizell |
|           14 |     5258 | 2024-02-29 | lajtbitexe          | W   | 0.598      | 0.371        | 0.001 (0.000)    | 0.069 (0.015)    | 0 (0.000) |     8.79 | datet, elocurse, Middlesex, reyoz, twizell |
|           13 |     5332 | 2024-02-28 | ILIN                | L   | 0.590      | -            | -                | -                | -         |   -10.38 | datet, elocurse, Middlesex, reyoz, twizell |
|           12 |     5767 | 2024-02-20 | unluckyday          | L   | 0.537      | -            | -                | -                | -         |    -7.23 | datet, elocurse, Middlesex, reyoz, twizell |
|           11 |     5830 | 2024-02-19 | V1dar Gaming        | L   | 0.531      | -            | -                | -                | -         |    -7.34 | datet, elocurse, Middlesex, reyoz, twizell |
|           10 |     5858 | 2024-02-18 | L1ZUN4IKI           | W   | 0.525      | 0.284        | 0.000 (0.000)    | 0.014 (0.002)    | 0 (0.000) |     8.63 | datet, elocurse, Middlesex, reyoz, twizell |
|            9 |     6037 | 2024-02-15 | GamerLegion Academy | L   | 0.504      | -            | -                | -                | -         |    -4.35 | datet, elocurse, Middlesex, reyoz, twizell |
|            8 |     6089 | 2024-02-14 | Zero Tenacity       | L   | 0.498      | -            | -                | -                | -         |    -1.33 | datet, elocurse, Middlesex, reyoz, twizell |
|            7 |     6356 | 2024-02-07 | RoundsGG            | L   | 0.451      | -            | -                | -                | -         |    -7.82 | datet, elocurse, Middlesex, reyoz, twizell |
|            6 |     7837 | 2024-01-12 | UNiTY esports       | L   | 0.278      | -            | -                | -                | -         |    -1.45 | datet, elocurse, Middlesex, reyoz, twizell |
|            5 |     7855 | 2024-01-12 | RUSH B              | W   | 0.278      | 0.143        | 0.001 (0.000)    | 0.446 (0.018)    | 0 (0.000) |     5.93 | datet, elocurse, Middlesex, reyoz, twizell |
|            4 |     8506 | 2023-12-17 | VaselineWorms       | L   | 0.102      | -            | -                | -                | -         |    -1.22 | datet, elocurse, Middlesex, reyoz, twizell |
|            3 |     8583 | 2023-12-16 | Betera Esports      | L   | 0.098      | -            | -                | -                | -         |    -0.85 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            2 |     8597 | 2023-12-16 | PrizyvaNet          | W   | 0.097      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.67 | datet, elocurse, Middlesex, reyoz, twizell |
|            1 |     8645 | 2023-12-16 | Nemiga Gaming       | L   | 0.095      | -            | -                | -                | -         |    -0.09 | datet, elocurse, Middlesex, reyoz, twizell |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($322.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
