### Roster Details<br />
Team Name: Clutch Gaming<br />
Roster: clouden, flame, hasteka, IMAGINE, IZR<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [140](../standings_global.md)<br />
Regional Rank: [19]( ../standings_asia.md)<br />
Final Rank Value:  786.7<br />
<br />
Final Rank Value (786.7) = Starting Rank Value (733.9) + Head To Head Adjustments (52.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.317[<sup>2</sup>](#table1)
- Opponent Network: 0.104[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 733.9
- 400 + ( ( 0.168 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 733.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      743 | 2024-04-20 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |    -5.52 | clouden, flame, hasteka, IMAGINE, IZR   |
|           22 |      756 | 2024-04-20 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |    -5.82 | clouden, flame, hasteka, IMAGINE, IZR   |
|           21 |     1236 | 2024-04-10 | LYG Gaming         | W   | 1.000      | 0.417        | 0.004 (0.002)    | 0.380 (0.159)    | 0 (0.000) |    16.77 | clouden, flame, hasteka, IMAGINE, IZR   |
|           20 |     1241 | 2024-04-10 | LYG Gaming         | W   | 1.000      | 0.417        | 0.004 (0.002)    | 0.380 (0.159)    | 0 (0.000) |    18.30 | clouden, flame, hasteka, IMAGINE, IZR   |
|           19 |     1499 | 2024-04-04 | DEWA United        | L   | 0.991      | -            | -                | -                | -         |   -24.30 | clouden, flame, hasteka, IMAGINE, IZR   |
|           18 |     1503 | 2024-04-04 | DEWA United        | W   | 0.990      | 0.417        | -                | 0.070 (0.029)    | 0 (0.000) |     6.41 | clouden, flame, hasteka, IMAGINE, IZR   |
|           17 |     1760 | 2024-03-27 | Lynn Vision Gaming | W   | 0.937      | 0.417        | 0.155 (0.061)    | 0.554 (0.217)    | 0 (0.000) |    27.78 | clouden, flame, hasteka, IMAGINE, IZR   |
|           16 |     1763 | 2024-03-27 | Lynn Vision Gaming | L   | 0.937      | -            | -                | -                | -         |    -1.55 | clouden, flame, hasteka, IMAGINE, IZR   |
|           15 |     1827 | 2024-03-26 | The QUBE Esports   | W   | 0.931      | 0.417        | 0.004 (0.001)    | 0.168 (0.065)    | 0 (0.000) |    17.37 | clouden, flame, hasteka, IMAGINE, IZR   |
|           14 |     1831 | 2024-03-26 | The QUBE Esports   | L   | 0.931      | -            | -                | -                | -         |   -11.81 | clouden, flame, hasteka, IMAGINE, IZR   |
|           13 |     2327 | 2024-03-13 | GR Gaming          | L   | 0.844      | -            | -                | -                | -         |    -9.39 | clouden, flame, hasteka, IMAGINE, IZR   |
|           12 |     2332 | 2024-03-13 | GR Gaming          | W   | 0.844      | 0.417        | 0.006 (0.002)    | 0.495 (0.174)    | 0 (0.000) |    17.61 | clouden, flame, hasteka, IMAGINE, IZR   |
|           11 |     2634 | 2024-03-06 | MIRAI Gaming       | W   | 0.797      | 0.417        | 0.000 (0.000)    | 0.246 (0.082)    | 0 (0.000) |    10.66 | clouden, flame, hasteka, IMAGINE, IZR   |
|           10 |     2639 | 2024-03-06 | MIRAI Gaming       | W   | 0.797      | 0.417        | 0.000 (0.000)    | 0.246 (0.082)    | 0 (0.000) |    11.43 | clouden, flame, hasteka, IMAGINE, IZR   |
|            9 |     3361 | 2024-02-20 | -72C               | L   | 0.697      | -            | -                | -                | -         |    -9.35 | clouden, flame, hasteka, IMAGINE, IZR   |
|            8 |     3368 | 2024-02-20 | -72C               | L   | 0.697      | -            | -                | -                | -         |    -9.94 | clouden, flame, hasteka, IMAGINE, IZR   |
|            7 |     3684 | 2024-02-13 | Born In Far East   | W   | 0.651      | 0.417        | 0.003 (0.001)    | 0.138 (0.037)    | 0 (0.000) |    10.38 | clouden, flame, hasteka, IMAGINE, IZR   |
|            6 |     3687 | 2024-02-13 | Born In Far East   | W   | 0.651      | 0.417        | 0.003 (0.001)    | 0.138 (0.037)    | 0 (0.000) |    10.99 | clouden, flame, hasteka, IMAGINE, IZR   |
|            5 |     4847 | 2024-01-15 | MungYu Esports     | L   | 0.456      | -            | -                | -                | -         |   -11.09 | clouden, ctrlmad, hasteka, IZR, shinobi |
|            4 |     6002 | 2023-12-05 | LYG Gaming         | L   | 0.184      | -            | -                | -                | -         |    -2.45 | clouden, flame, hasteka, IMAGINE, IZR   |
|            3 |     6497 | 2023-11-24 | Aravt              | L   | 0.109      | -            | -                | -                | -         |    -2.55 | ATTACKER, clouden, flame, hasteka, IZR  |
|            2 |     6605 | 2023-11-21 | GR Gaming          | L   | 0.090      | -            | -                | -                | -         |    -1.11 | clouden, flame, hasteka, IMAGINE, IZR   |
|            1 |     7210 | 2023-11-08 | Born In Far East   | W   | 0.004      | 0.417        | 0.003 (0.000)    | -                | -         |     0.06 | clouden, flame, hasteka, IMAGINE, IZR   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($173.52)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
