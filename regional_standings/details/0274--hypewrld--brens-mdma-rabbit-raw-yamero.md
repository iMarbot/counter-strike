### Roster Details<br />
Team Name: hypewrld<br />
Roster: Brens, MDmA, rabbit, rAW, Yamero<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [274](../standings_global.md)<br />
Regional Rank: [176]( ../standings_europe.md)<br />
Final Rank Value:  665.5<br />
<br />
Final Rank Value (665.5) = Starting Rank Value (710.4) + Head To Head Adjustments (-44.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.4
- 400 + ( ( 0.153 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 710.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      920 | 2024-05-18 | Necrotic Esports | L   | 1.000      | -            | -                | -                | -         |   -22.07 | Brens, MDmA, rabbit, rAW, Yamero      |
|           17 |     1408 | 2024-05-12 | KUNGI            | L   | 1.000      | -            | -                | -                | -         |   -14.82 | Brens, flAir, rabbit, rAW, Yamero     |
|           16 |     1490 | 2024-05-11 | EC BANGA         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     6.89 | Brens, flAir, rabbit, rAW, Yamero     |
|           15 |     1781 | 2024-05-05 | atpūties         | L   | 1.000      | -            | -                | -                | -         |   -11.80 | Brens, rabbit, rAW, sqreet, Yamero    |
|           14 |     1804 | 2024-05-05 | CyberMAN         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.081 (0.012)    | 1 (1.000) |     7.37 | Brens, rabbit, rAW, sqreet, Yamero    |
|           13 |     2960 | 2024-04-16 | MightyWolves     | W   | 0.911      | 0.143        | 0.000 (0.000)    | 0.075 (0.010)    | 0 (0.000) |     6.74 | Brens, rabbit, rAW, sqreet, Yamero    |
|           12 |     3311 | 2024-04-09 | HAVENs           | W   | 0.864      | 0.143        | 0.000 (0.000)    | 0.040 (0.005)    | 0 (0.000) |     4.31 | Brens, rabbit, rAW, sqreet, Yamero    |
|           11 |     3413 | 2024-04-07 | EC BANGA         | L   | 0.850      | -            | -                | -                | -         |   -20.43 | Brens, rabbit, rAW, sqreet, Yamero    |
|           10 |     3732 | 2024-03-31 | sunshine!        | W   | 0.804      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.36 | Brens, rabbit, rAW, sqreet, Yamero    |
|            9 |     4266 | 2024-03-19 | CyberMAN         | W   | 0.724      | 0.143        | 0.000 (0.000)    | 0.081 (0.008)    | 0 (0.000) |     5.36 | Brens, rabbit, rAW, sqreet, Yamero    |
|            8 |     4674 | 2024-03-12 | LusHi            | W   | 0.677      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.21 | Brens, rabbit, rAW, sqreet, Yamero    |
|            7 |     4777 | 2024-03-10 | atpūties         | L   | 0.664      | -            | -                | -                | -         |    -8.91 | Brens, rabbit, rAW, sqreet, Yamero    |
|            6 |     5685 | 2024-02-24 | KUNGI            | L   | 0.564      | -            | -                | -                | -         |    -9.28 | Brens, flairr, rabbit, sqreet, Yamero |
|            5 |     5730 | 2024-02-24 | Wolves eSports   | W   | 0.562      | 0.143        | 0.002 (0.000)    | 0.109 (0.009)    | 1 (0.562) |     6.74 | Brens, flairr, rabbit, sqreet, Yamero |
|            4 |     9047 | 2023-12-14 | AKA HERO         | L   | 0.085      | -            | -                | -                | -         |    -1.68 | Brens, flairr, rabbit, sqreet, yamero |
|            3 |     9103 | 2023-12-13 | ENCE Prospects   | W   | 0.077      | 0.310        | 0.001 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     1.09 | Brens, flairr, rabbit, sqreet, yamero |
|            2 |     9146 | 2023-12-12 | HAVENs           | W   | 0.071      | 0.310        | 0.000 (0.000)    | 0.040 (0.001)    | 0 (0.000) |     0.34 | Brens, flairr, rabbit, sqreet, yamero |
|            1 |     9187 | 2023-12-11 | Kova Gaming      | L   | 0.064      | -            | -                | -                | -         |    -1.32 | Brens, flairr, rabbit, sqreet, yamero |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($527.03)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $215.44        | $215.44         |
| 2024-02-24 |      0.564 | $487.51        | $275.04         |
| 2023-12-17 |      0.104 | $350.00        | $36.56          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
