### Roster Details<br />
Team Name: Complexity Gaming<br />
Roster: EliGE, floppy, Grim, hallzerk, JT<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [14](../standings_global.md)<br />
Regional Rank: [2]( ../standings_americas.md)<br />
Final Rank Value:  1551.3<br />
<br />
Final Rank Value (1551.3) = Starting Rank Value (1534.3) + Head To Head Adjustments (16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.638[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.871[<sup>2</sup>](#table1)

The average of these factors is 0.572<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1534.3
- 400 + ( ( 0.572 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1534.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |        6 | 2024-05-05 | Natus Vincere     | W   | 1.000      | 0.889        | 1.000 (0.889)    | 0.406 (0.361)    | 1 (1.000) |    28.48 | EliGE, floppy, Grim, hallzerk, JT |
|           27 |      149 | 2024-05-02 | HEROIC            | W   | 1.000      | 0.889        | 0.243 (0.216)    | 0.537 (0.478)    | 1 (1.000) |    20.83 | EliGE, floppy, Grim, hallzerk, JT |
|           26 |      242 | 2024-04-30 | Pera Esports      | W   | 1.000      | 0.889        | 0.065 (0.058)    | 0.324 (0.288)    | 1 (1.000) |     0.94 | EliGE, floppy, Grim, hallzerk, JT |
|           25 |     1865 | 2024-03-24 | FaZe Clan         | L   | 0.917      | -            | -                | -                | -         |    -2.33 | EliGE, floppy, Grim, hallzerk, JT |
|           24 |     1909 | 2024-03-23 | Team Vitality     | L   | 0.911      | -            | -                | -                | -         |    -3.32 | EliGE, floppy, Grim, hallzerk, JT |
|           23 |     1944 | 2024-03-22 | MOUZ              | L   | 0.904      | -            | -                | -                | -         |    -3.09 | EliGE, floppy, Grim, hallzerk, JT |
|           22 |     1976 | 2024-03-21 | HEROIC            | W   | 0.899      | 1.000        | 0.243 (0.218)    | 0.537 (0.483)    | 1 (0.899) |    21.81 | EliGE, floppy, Grim, hallzerk, JT |
|           21 |     1990 | 2024-03-21 | PaiN Gaming       | W   | 0.897      | 1.000        | -                | 0.156 (0.140)    | 1 (0.897) |     2.85 | EliGE, floppy, Grim, hallzerk, JT |
|           20 |     2570 | 2024-03-07 | OG                | L   | 0.805      | -            | -                | -                | -         |   -18.88 | EliGE, floppy, Grim, hallzerk, JT |
|           19 |     2728 | 2024-03-04 | Team Liquid       | W   | 0.786      | 0.143        | 0.125 (0.014)    | 0.546 (0.061)    | 1 (0.786) |     8.31 | EliGE, floppy, Grim, hallzerk, JT |
|           18 |     2781 | 2024-03-03 | FURIA Esports     | L   | 0.779      | -            | -                | -                | -         |    -9.08 | EliGE, floppy, Grim, hallzerk, JT |
|           17 |     2878 | 2024-03-02 | BOSS              | W   | 0.771      | 0.143        | 0.051 (0.006)    | 0.293 (0.032)    | 1 (0.771) |     0.84 | EliGE, floppy, Grim, hallzerk, JT |
|           16 |     2909 | 2024-03-01 | Elevate           | W   | 0.766      | 0.143        | 0.030 (0.003)    | 0.268 (0.029)    | 1 (0.766) |     0.44 | EliGE, floppy, Grim, hallzerk, JT |
|           15 |     3886 | 2024-02-05 | Team Falcons      | L   | 0.599      | -            | -                | -                | -         |   -13.05 | EliGE, floppy, Grim, hallzerk, JT |
|           14 |     3923 | 2024-02-04 | Team Spirit       | L   | 0.591      | -            | -                | -                | -         |    -2.70 | EliGE, floppy, Grim, hallzerk, JT |
|           13 |     3947 | 2024-02-03 | Apeks             | W   | 0.585      | 1.000        | 0.253 (0.148)    | 0.459 (0.269)    | 1 (0.585) |     6.73 | EliGE, floppy, Grim, hallzerk, JT |
|           12 |     4435 | 2024-01-23 | Ninjas in Pyjamas | L   | 0.511      | -            | -                | -                | -         |   -15.81 | EliGE, floppy, Grim, hallzerk, JT |
|           11 |     4484 | 2024-01-22 | Natus Vincere     | L   | 0.504      | -            | -                | -                | -         |    -1.35 | EliGE, floppy, Grim, hallzerk, JT |
|           10 |     4874 | 2024-01-13 | Party Astronauts  | W   | 0.447      | 0.143        | 0.036 (0.002)    | -                | -         |     0.25 | EliGE, floppy, Grim, hallzerk, JT |
|            9 |     4915 | 2024-01-12 | FLUFFY AIMERS     | W   | 0.441      | -            | -                | -                | -         |     0.12 | EliGE, floppy, Grim, hallzerk, JT |
|            8 |     5467 | 2023-12-16 | The MongolZ       | L   | 0.258      | -            | -                | -                | -         |    -2.76 | EliGE, floppy, Grim, hallzerk, JT |
|            7 |     5572 | 2023-12-15 | The MongolZ       | L   | 0.252      | -            | -                | -                | -         |    -2.68 | EliGE, floppy, Grim, hallzerk, JT |
|            6 |     6202 | 2023-11-30 | MOUZ              | L   | 0.152      | -            | -                | -                | -         |    -0.65 | EliGE, floppy, Grim, hallzerk, JT |
|            5 |     6217 | 2023-11-30 | FURIA Esports     | L   | 0.151      | -            | -                | -                | -         |    -1.59 | EliGE, floppy, Grim, hallzerk, JT |
|            4 |     6419 | 2023-11-25 | FaZe Clan         | L   | 0.119      | -            | -                | -                | -         |    -0.26 | EliGE, floppy, Grim, hallzerk, JT |
|            3 |     6470 | 2023-11-24 | Natus Vincere     | W   | 0.112      | 0.729        | 1.000 (0.081)    | 0.406 (0.033)    | 1 (0.112) |     3.22 | EliGE, floppy, Grim, hallzerk, JT |
|            2 |     6511 | 2023-11-23 | Team Vitality     | L   | 0.105      | -            | -                | -                | -         |    -0.38 | EliGE, floppy, Grim, hallzerk, JT |
|            1 |     6566 | 2023-11-22 | Astralis          | W   | 0.098      | -            | -                | -                | -         |     0.03 | EliGE, floppy, Grim, hallzerk, JT |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43,007.04)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.27) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2024-02-11 |      0.638 | $16,000.00     | $10,208.15      |
| 2024-01-28 |      0.545 | $5,000.00      | $2,725.46       |
| 2023-12-17 |      0.266 | $3,000.00      | $798.54         |
| 2023-12-03 |      0.171 | $5,000.00      | $855.32         |
| 2023-11-26 |      0.125 | $40,000.00     | $4,987.04       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
