### Roster Details<br />
Team Name: Marcos Gaming<br />
Roster: BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [180](../standings_global.md)<br />
Regional Rank: [26]( ../standings_asia.md)<br />
Final Rank Value:  743.1<br />
<br />
Final Rank Value (743.1) = Starting Rank Value (701.6) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.6
- 400 + ( ( 0.152 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 701.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1656 | 2024-03-30 | True Rippers    | L   | 0.956      | -            | -                | -                | -             |   -11.35 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            9 |     1674 | 2024-03-29 | Gods Reign      | L   | 0.950      | -            | -                | -                | -             |    -9.36 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            8 |     1703 | 2024-03-28 | True Rippers    | W   | 0.944      | 0.143        | 0.059 (0.008)    | 0.272 (0.037)    | false (0.000) |    18.01 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            7 |     1707 | 2024-03-28 | Grayfox Esports | W   | 0.943      | 0.143        | 0.010 (0.001)    | 0.264 (0.036)    | false (0.000) |    11.72 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            6 |     1870 | 2024-03-24 | Gods Reign      | L   | 0.916      | -            | -                | -                | -             |    -9.01 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            5 |     1872 | 2024-03-23 | True Rippers    | W   | 0.915      | 0.262        | 0.059 (0.014)    | 0.272 (0.065)    | false (0.000) |    18.89 | Anasasis, Crazy_Gamer, DEFAULTER, Mcg1LLzZz, Rossi |
|            4 |     2710 | 2024-03-05 | Gods Reign      | L   | 0.790      | -            | -                | -                | -             |    -8.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn             |
|            3 |     2819 | 2024-03-03 | Grayfox Esports | W   | 0.776      | 0.143        | 0.010 (0.001)    | 0.264 (0.029)    | false (0.000) |    10.99 | Ace, arakyN, ghostxD, Marzil, Nox                  |
|            2 |     2885 | 2024-03-02 | Gods Reign      | W   | 0.771      | 0.143        | 0.174 (0.019)    | 0.479 (0.053)    | false (0.000) |    16.66 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            1 |     3363 | 2024-02-20 | Re-wonation     | W   | 0.697      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.27 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($541.99)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-24 |      0.916 | $500.00        | $457.87         |
| 2024-02-20 |      0.697 | $120.63        | $84.12          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
