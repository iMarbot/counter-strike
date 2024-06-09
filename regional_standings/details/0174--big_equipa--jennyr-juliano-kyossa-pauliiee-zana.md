### Roster Details<br />
Team Name: BIG EQUIPA<br />
Roster: JennyR, juliano, kyossa, pauliiee, Zana<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [174](../standings_global.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
Final Rank Value:  760.6<br />
<br />
Final Rank Value (760.6) = Starting Rank Value (690.4) + Head To Head Adjustments (70.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.252[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 690.4
- 400 + ( ( 0.143 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 690.4


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
|           23 |      814 | 2024-05-19 | NAVI Javelins      | L   | 1.000      | -            | -                | -                | -         |   -12.24 | JennyR, juliano, kyossa, pauliiee, Zana |
|           22 |      895 | 2024-05-18 | Nemesis            | W   | 1.000      | 0.281        | -                | 0.102 (0.029)    | 0 (0.000) |     6.46 | JennyR, juliano, kyossa, pauliiee, Zana |
|           21 |      930 | 2024-05-18 | 5bites             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.34 | JennyR, juliano, kyossa, pauliiee, Zana |
|           20 |     2610 | 2024-04-20 | Fearless Cheetahs  | W   | 0.937      | 0.331        | 0.006 (0.002)    | 0.149 (0.046)    | 0 (0.000) |    13.28 | JennyR, juliano, kyossa, pauliiee, Zana |
|           19 |     2747 | 2024-04-19 | NIP Impact         | W   | 0.930      | 0.331        | 0.007 (0.002)    | 0.303 (0.093)    | 0 (0.000) |    13.19 | JennyR, juliano, kyossa, pauliiee, Zana |
|           18 |     3434 | 2024-04-07 | Team Pigeons       | L   | 0.849      | -            | -                | -                | -         |   -11.39 | JennyR, juliano, kyossa, pauliiee, Zana |
|           17 |     3488 | 2024-04-06 | Team Spirit Female | W   | 0.842      | 0.262        | 0.005 (0.001)    | 0.216 (0.048)    | 0 (0.000) |    11.00 | JennyR, juliano, kyossa, pauliiee, Zana |
|           16 |     3497 | 2024-04-06 | ex-FORZE Ladies    | W   | 0.841      | 0.262        | 0.005 (0.001)    | 0.164 (0.036)    | 0 (0.000) |    10.21 | JennyR, juliano, kyossa, pauliiee, Zana |
|           15 |     3579 | 2024-04-04 | ENCE Athena        | W   | 0.830      | 0.331        | 0.004 (0.001)    | 0.215 (0.059)    | 0 (0.000) |    11.43 | JennyR, juliano, kyossa, pauliiee, Zana |
|           14 |     3830 | 2024-03-28 | ex-Guild Esports   | L   | 0.784      | -            | -                | -                | -         |   -12.72 | JennyR, juliano, kyossa, pauliiee, Zana |
|           13 |     4534 | 2024-03-14 | Team Pigeons       | L   | 0.691      | -            | -                | -                | -         |   -10.09 | JennyR, juliano, kyossa, pauliiee, Zana |
|           12 |     4992 | 2024-03-06 | Astralis Women     | W   | 0.638      | 0.331        | 0.003 (0.001)    | -                | 0 (0.000) |     6.94 | JennyR, juliano, kyossa, pauliiee, Zana |
|           11 |     5216 | 2024-03-03 | ex-FORZE Ladies    | W   | 0.618      | 0.250        | 0.005 (0.001)    | 0.164 (0.025)    | 0 (0.000) |     8.21 | JennyR, juliano, kyossa, pauliiee, Zana |
|           10 |     5245 | 2024-03-03 | NIP Impact         | W   | 0.617      | 0.250        | 0.007 (0.001)    | 0.303 (0.047)    | 0 (0.000) |     8.73 | JennyR, juliano, kyossa, pauliiee, Zana |
|            9 |     5328 | 2024-03-02 | Nemesis            | W   | 0.610      | -            | -                | -                | -         |     7.16 | JennyR, juliano, kyossa, pauliiee, Zana |
|            8 |     5616 | 2024-02-25 | NAVI Javelins      | L   | 0.570      | -            | -                | -                | -         |    -6.75 | JennyR, juliano, kyossa, pauliiee, Zana |
|            7 |     5623 | 2024-02-25 | Let Her Cook       | W   | 0.569      | -            | -                | -                | -         |     5.40 | JennyR, juliano, kyossa, pauliiee, Zana |
|            6 |     5711 | 2024-02-24 | ex-Guild Esports   | W   | 0.563      | -            | -                | -                | -         |     9.23 | JennyR, juliano, kyossa, pauliiee, Zana |
|            5 |     5726 | 2024-02-24 | ELITE              | W   | 0.562      | -            | -                | -                | -         |     2.81 | JennyR, juliano, kyossa, pauliiee, Zana |
|            4 |     6719 | 2024-02-03 | gDEBbl             | L   | 0.424      | -            | -                | -                | -         |   -10.20 | JennyR, juliano, kyossa, pauliiee, Zana |
|            3 |     7080 | 2024-01-28 | Questionmark       | W   | 0.384      | -            | -                | -                | -         |     4.72 | JennyR, juliano, kyossa, pauliiee, Zana |
|            2 |     7093 | 2024-01-28 | Team Spirit Female | W   | 0.383      | 0.250        | 0.005 (0.001)    | 0.216 (0.021)    | -         |     5.79 | JennyR, juliano, kyossa, pauliiee, Zana |
|            1 |     7176 | 2024-01-27 | ex-FORZE Ladies    | W   | 0.377      | 0.250        | 0.005 (0.000)    | 0.164 (0.015)    | -         |     5.72 | JennyR, juliano, kyossa, pauliiee, Zana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($751.20)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-03 |      0.618 | $750.00        | $463.28         |
| 2024-01-28 |      0.384 | $750.00        | $287.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />