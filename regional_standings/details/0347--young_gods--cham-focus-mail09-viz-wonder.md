### Roster Details<br />
Team Name: Young Gods<br />
Roster: Cham, Focus, MaiL09, viz, Wonder<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [347](../standings_global.md)<br />
Regional Rank: [215]( ../standings_europe.md)<br />
Final Rank Value:  496.3<br />
<br />
Final Rank Value (496.3) = Starting Rank Value (495.7) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.169[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.048<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.7
- 400 + ( ( 0.048 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 495.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      100 | 2024-05-03 | LOADING (French team) | L   | 1.000      | -            | -                | -                | -             |   -19.99 | Cham, Focus, MaiL09, viz, Wonder      |
|           21 |      202 | 2024-05-01 | EsmagaB               | L   | 1.000      | -            | -                | -                | -             |    -5.16 | Cham, Focus, MaiL09, viz, Wonder      |
|           20 |      471 | 2024-04-25 | Copenhagen Wolves     | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.417 (0.155)    | false (0.000) |    20.83 | Cham, Focus, MaiL09, viz, Wonder      |
|           19 |     1039 | 2024-04-15 | Eternal Fire Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | false (0.000) |    16.84 | Cham, Focus, MaiL09, viz, Wonder      |
|           18 |     1136 | 2024-04-12 | Begrip Gaming         | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.196 (0.028)    | false (0.000) |    19.70 | Cham, Focus, MaiL09, viz, Wonder      |
|           17 |     1416 | 2024-04-06 | Metizport             | L   | 1.000      | -            | -                | -                | -             |    -0.69 | Cham, Focus, MaiL09, viz, Wonder      |
|           16 |     1484 | 2024-04-04 | Lemoncats             | W   | 0.992      | 0.143        | 0.000 (0.000)    | 0.076 (0.011)    | false (0.000) |    15.95 | Cham, Focus, MaiL09, viz, Wonder      |
|           15 |     1659 | 2024-03-29 | Lilmix                | L   | 0.952      | -            | -                | -                | -             |    -8.95 | Cham, Focus, MaiL09, viz, Wonder      |
|           14 |     1697 | 2024-03-28 | EPIC DUDES            | L   | 0.944      | -            | -                | -                | -             |   -16.65 | Fabbelit0, Focus, upE, viz, Wonder    |
|           13 |     1846 | 2024-03-25 | Sampi NEXT            | W   | 0.924      | 0.289        | 0.000 (0.000)    | 0.039 (0.010)    | false (0.000) |    15.21 | Fabbelit0, Focus, MaiL09, upE, Wonder |
|           12 |     1980 | 2024-03-21 | EPIC DUDES            | L   | 0.899      | -            | -                | -                | -             |   -16.34 | Cham, Focus, MaiL09, viz, Wonder      |
|           11 |     2059 | 2024-03-19 | Kario Mart            | W   | 0.885      | 0.143        | 0.000 (0.000)    | 0.068 (0.009)    | false (0.000) |    11.10 | Cham, Focus, MaiL09, viz, Wonder      |
|           10 |     2262 | 2024-03-14 | Lemondogs             | L   | 0.852      | -            | -                | -                | -             |    -8.66 | Cham, Focus, MaiL09, viz, Wonder      |
|            9 |     4546 | 2024-01-20 | Begrip Gaming         | L   | 0.492      | -            | -                | -                | -             |    -4.32 | Cham, Focus, MaiL09, viz, Wonder      |
|            8 |     4816 | 2024-01-16 | AVEZ                  | L   | 0.465      | -            | -                | -                | -             |    -3.63 | Cham, Focus, MaiL09, viz, Wonder      |
|            7 |     5213 | 2024-01-03 | RawkAndRawl           | L   | 0.379      | -            | -                | -                | -             |    -7.36 | Focus, MaiL09, meinz, viz, Wonder     |
|            6 |     5965 | 2023-12-05 | Begrip Gaming         | L   | 0.186      | -            | -                | -                | -             |    -1.73 | Focus, Lindcs, MaiL09, viz, Wonder    |
|            5 |     6306 | 2023-11-28 | LODIS                 | L   | 0.139      | -            | -                | -                | -             |    -2.73 | Focus, Lindcs, MaiL09, viz, Wonder    |
|            4 |     6483 | 2023-11-24 | FALKE ESPORTS         | L   | 0.111      | -            | -                | -                | -             |    -1.75 | Focus, Lindcs, MaiL09, viz, Wonder    |
|            3 |     6882 | 2023-11-15 | Kappa Bar             | L   | 0.052      | -            | -                | -                | -             |    -0.60 | Focus, Lindcs, MaiL09, viz, Wonder    |
|            2 |     6925 | 2023-11-14 | Lemoncats             | L   | 0.045      | -            | -                | -                | -             |    -0.77 | Focus, Lindcs, MaiL09, viz, Wonder    |
|            1 |     7134 | 2023-11-09 | Alliance              | W   | 0.012      | 0.143        | 0.017 (0.000)    | 0.729 (0.001)    | false (0.000) |     0.33 | Focus, Lindcs, MaiL09, viz, Wonder    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
