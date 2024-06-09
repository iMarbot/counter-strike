### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, victoria, vilga<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [234](../standings_global.md)<br />
Regional Rank: [156]( ../standings_europe.md)<br />
Final Rank Value:  698.0<br />
<br />
Final Rank Value (698.0) = Starting Rank Value (691.7) + Head To Head Adjustments (6.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 691.7
- 400 + ( ( 0.144 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 691.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2540 | 2024-04-21 | ex-Guild Esports   | L   | 0.944      | -            | -                | -                | -         |   -14.92 | kr4sy, Ksu, t4tty, victoria, vilga |
|           14 |     2610 | 2024-04-20 | BIG EQUIPA         | L   | 0.937      | -            | -                | -                | -         |   -13.28 | kr4sy, Ksu, t4tty, victoria, vilga |
|           13 |     2752 | 2024-04-19 | 1win Gang          | W   | 0.930      | 0.331        | 0.004 (0.001)    | 0.118 (0.036)    | 0 (0.000) |    10.77 | kr4sy, Ksu, t4tty, victoria, vilga |
|           12 |     3177 | 2024-04-11 | Crescent           | W   | 0.877      | 0.331        | 0.007 (0.002)    | 0.228 (0.066)    | 0 (0.000) |    11.54 | kr4sy, Ksu, t4tty, victoria, vilga |
|           11 |     3435 | 2024-04-07 | NIP Impact         | L   | 0.849      | -            | -                | -                | -         |   -13.21 | kr4sy, Ksu, t4tty, victoria, vilga |
|           10 |     3491 | 2024-04-06 | Let Her Cook       | W   | 0.842      | 0.262        | 0.000 (0.000)    | 0.156 (0.034)    | 0 (0.000) |     8.78 | kr4sy, Ksu, t4tty, victoria, vilga |
|            9 |     3499 | 2024-04-06 | 5bites             | W   | 0.841      | 0.262        | 0.000 (0.000)    | 0.019 (0.004)    | 0 (0.000) |     5.48 | kr4sy, Ksu, t4tty, victoria, vilga |
|            8 |     3883 | 2024-03-27 | Team Spirit Female | W   | 0.778      | 0.331        | 0.005 (0.001)    | 0.216 (0.056)    | 0 (0.000) |    12.20 | kr4sy, Ksu, t4tty, victoria, vilga |
|            7 |     4182 | 2024-03-21 | Let Her Cook       | W   | 0.738      | 0.331        | 0.000 (0.000)    | 0.156 (0.038)    | 0 (0.000) |     7.91 | kr4sy, Ksu, t4tty, victoria, vilga |
|            6 |     4993 | 2024-03-06 | NAVI Javelins      | L   | 0.638      | -            | -                | -                | -         |    -6.74 | kr4sy, Ksu, t4tty, victoria, vilga |
|            5 |     5326 | 2024-03-02 | more whiskey       | L   | 0.611      | -            | -                | -                | -         |   -13.79 | kr4sy, Ksu, t4tty, victoria, vilga |
|            4 |     5604 | 2024-02-25 | 1win Gang          | W   | 0.571      | 0.250        | 0.004 (0.001)    | 0.118 (0.017)    | 0 (0.000) |     7.95 | kr4sy, Ksu, t4tty, victoria, vilga |
|            3 |     5611 | 2024-02-25 | Nemesis            | W   | 0.570      | 0.250        | 0.002 (0.000)    | 0.089 (0.013)    | 0 (0.000) |     7.32 | kr4sy, Ksu, t4tty, victoria, vilga |
|            2 |     5695 | 2024-02-24 | wwaves             | W   | 0.564      | 0.250        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |     4.57 | kr4sy, Ksu, t4tty, victoria, vilga |
|            1 |     5725 | 2024-02-24 | ex-Guild Esports   | L   | 0.562      | -            | -                | -                | -         |    -8.27 | kr4sy, Ksu, t4tty, victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,938.13)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.944 | $1,600.00      | $1,510.00       |
| 2024-02-25 |      0.571 | $750.00        | $428.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
