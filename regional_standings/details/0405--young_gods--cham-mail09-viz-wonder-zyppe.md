### Roster Details<br />
Team Name: Young Gods<br />
Roster: Cham, MaiL09, viz, Wonder, Zyppe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [405](../standings_global.md)<br />
Regional Rank: [244]( ../standings_europe.md)<br />
Final Rank Value:  557.0<br />
<br />
Final Rank Value (557.0) = Starting Rank Value (536.5) + Head To Head Adjustments (20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.5
- 400 + ( ( 0.067 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 536.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       94 | 2024-05-29 | 5W Gaming            | L   | 1.000      | -            | -                | -                | -         |   -17.96 | Cham, MaiL09, viz, Wonder, Zyppe   |
|           27 |      459 | 2024-05-22 | Denial               | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.138 (0.051)    | 0 (0.000) |    18.02 | Cham, Focus, MaiL09, viz, Wonder   |
|           26 |      672 | 2024-05-20 | ex-KRC Genk Esports  | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.173 (0.064)    | 0 (0.000) |    20.63 | Cham, Focus, MaiL09, viz, Wonder   |
|           25 |     1174 | 2024-05-15 | Insilio              | L   | 1.000      | -            | -                | -                | -         |    -2.60 | Cham, Focus, MaiL09, viz, Wonder   |
|           24 |     1504 | 2024-05-10 | Rok paus vid 45      | L   | 1.000      | -            | -                | -                | -         |   -17.00 | Cham, Focus, MaiL09, viz, Wonder   |
|           23 |     1526 | 2024-05-10 | RoundsGG             | L   | 1.000      | -            | -                | -                | -         |   -14.57 | Cham, Focus, MaiL09, viz, Wonder   |
|           22 |     1624 | 2024-05-08 | AURA                 | L   | 1.000      | -            | -                | -                | -         |    -9.41 | Cham, Focus, MaiL09, viz, Wonder   |
|           21 |     1650 | 2024-05-08 | WOPA Esport          | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    23.52 | Cham, Focus, MaiL09, viz, Wonder   |
|           20 |     1737 | 2024-05-06 | VP.Prodigy           | L   | 1.000      | -            | -                | -                | -         |    -6.18 | Cham, Focus, MaiL09, viz, Wonder   |
|           19 |     1897 | 2024-05-03 | LOADING              | L   | 1.000      | -            | -                | -                | -         |   -16.23 | Cham, Focus, MaiL09, viz, Wonder   |
|           18 |     2011 | 2024-05-01 | esmagaB              | L   | 1.000      | -            | -                | -                | -         |    -6.68 | Cham, Focus, MaiL09, viz, Wonder   |
|           17 |     2349 | 2024-04-25 | Copenhagen Wolves    | W   | 0.970      | 0.372        | 0.000 (0.000)    | 0.387 (0.140)    | 0 (0.000) |    19.32 | Cham, Focus, MaiL09, viz, Wonder   |
|           16 |     3007 | 2024-04-15 | Eternal Fire Academy | W   | 0.904      | 0.372        | 0.000 (0.000)    | 0.136 (0.046)    | 0 (0.000) |    12.83 | Cham, Focus, MaiL09, viz, Wonder   |
|           15 |     3015 | 2024-04-15 | ex-K10               | L   | 0.903      | -            | -                | -                | -         |    -5.56 | Cham, Focus, MaiL09, viz, Wonder   |
|           14 |     3138 | 2024-04-12 | Begrip Gaming        | W   | 0.884      | 0.143        | 0.000 (0.000)    | 0.317 (0.040)    | 0 (0.000) |    14.86 | Cham, Focus, MaiL09, viz, Wonder   |
|           13 |     3493 | 2024-04-06 | Metizport            | L   | 0.842      | -            | -                | -                | -         |    -1.22 | Cham, Focus, MaiL09, viz, Wonder   |
|           12 |     3581 | 2024-04-04 | Lemoncats            | W   | 0.830      | 0.143        | 0.000 (0.000)    | 0.101 (0.012)    | 0 (0.000) |    12.36 | Cham, Focus, MaiL09, viz, Wonder   |
|           11 |     3792 | 2024-03-29 | Lilmix               | L   | 0.791      | -            | -                | -                | -         |    -6.23 | Cham, Focus, MaiL09, viz, Wonder   |
|           10 |     4185 | 2024-03-21 | EPIC DUDES           | L   | 0.738      | -            | -                | -                | -         |   -16.18 | Cham, Focus, MaiL09, viz, Wonder   |
|            9 |     4274 | 2024-03-19 | Kario Mart           | W   | 0.724      | 0.143        | 0.000 (0.000)    | 0.073 (0.008)    | 0 (0.000) |     6.66 | Cham, Focus, MaiL09, viz, Wonder   |
|            8 |     4411 | 2024-03-16 | Begrip Gaming        | W   | 0.705      | 0.143        | 0.000 (0.000)    | 0.317 (0.032)    | 0 (0.000) |    13.10 | Cham, Focus, MaiL09, viz, Wonder   |
|            7 |     4423 | 2024-03-16 | smuuttikusilkki      | W   | 0.704      | 0.143        | 0.000 (0.000)    | 0.079 (0.008)    | 0 (0.000) |     9.93 | Cham, Focus, MaiL09, viz, Wonder   |
|            6 |     4426 | 2024-03-16 | sexsavers            | W   | 0.704      | -            | -                | -                | -         |     7.40 | Cham, Focus, MaiL09, viz, Wonder   |
|            5 |     4536 | 2024-03-14 | Lemondogs            | L   | 0.691      | -            | -                | -                | -         |    -7.93 | Cham, Focus, MaiL09, viz, Wonder   |
|            4 |     7573 | 2024-01-20 | Begrip Gaming        | L   | 0.331      | -            | -                | -                | -         |    -4.05 | Cham, Focus, MaiL09, viz, Wonder   |
|            3 |     7933 | 2024-01-16 | AVEZ                 | L   | 0.304      | -            | -                | -                | -         |    -1.29 | Cham, Focus, MaiL09, viz, Wonder   |
|            2 |     8514 | 2024-01-03 | RawkAndRawl          | L   | 0.217      | -            | -                | -                | -         |    -4.66 | Focus, MaiL09, meinz, viz, Wonder  |
|            1 |     9551 | 2023-12-05 | Begrip Gaming        | L   | 0.025      | -            | -                | -                | -         |    -0.31 | Focus, Lindcs, MaiL09, viz, Wonder |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
