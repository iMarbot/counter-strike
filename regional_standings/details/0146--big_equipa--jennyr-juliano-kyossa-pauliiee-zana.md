### Roster Details<br />
Team Name: BIG EQUIPA<br />
Roster: JennyR, juliano, kyossa, pauliiee, Zana<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [146](../standings_global.md)<br />
Regional Rank: [100]( ../standings_europe.md)<br />
Final Rank Value:  775.7<br />
<br />
Final Rank Value (775.7) = Starting Rank Value (701.5) + Head To Head Adjustments (74.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.5
- 400 + ( ( 0.152 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 701.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      693 | 2024-04-20 | Fearless Cheetahs     | W   | 1.000      | 0.331        | 0.014 (0.004)    | 0.199 (0.066)    | false (0.000) |    14.31 | JennyR, juliano, kyossa, pauliiee, Zana |
|           14 |      813 | 2024-04-19 | NIP Impact            | W   | 1.000      | 0.331        | 0.011 (0.004)    | 0.344 (0.114)    | false (0.000) |    15.53 | JennyR, juliano, kyossa, pauliiee, Zana |
|           13 |     1373 | 2024-04-07 | Team Pigeons          | L   | 1.000      | -            | -                | -                | -             |    -9.39 | JennyR, juliano, kyossa, pauliiee, Zana |
|           12 |     1411 | 2024-04-06 | Team Spirit Female    | W   | 1.000      | 0.262        | 0.011 (0.003)    | 0.205 (0.054)    | false (0.000) |    13.00 | JennyR, juliano, kyossa, pauliiee, Zana |
|           11 |     1482 | 2024-04-04 | ENCE Athena           | W   | 0.992      | 0.331        | 0.009 (0.003)    | 0.244 (0.080)    | false (0.000) |    13.83 | JennyR, juliano, kyossa, pauliiee, Zana |
|           10 |     1692 | 2024-03-28 | Guild Esports         | L   | 0.945      | -            | -                | -                | -             |   -14.99 | JennyR, juliano, kyossa, pauliiee, Zana |
|            9 |     2260 | 2024-03-14 | Team Pigeons          | L   | 0.852      | -            | -                | -                | -             |    -8.75 | JennyR, juliano, kyossa, pauliiee, Zana |
|            8 |     2609 | 2024-03-06 | Astralis Women        | W   | 0.799      | 0.331        | 0.007 (0.002)    | 0.101 (0.027)    | false (0.000) |     8.81 | JennyR, juliano, kyossa, pauliiee, Zana |
|            7 |     2787 | 2024-03-03 | FORZE Ladies          | W   | 0.779      | 0.250        | 0.002 (0.000)    | 0.057 (0.011)    | false (0.000) |     8.99 | JennyR, juliano, kyossa, pauliiee, Zana |
|            6 |     2810 | 2024-03-03 | NIP Impact            | W   | 0.778      | 0.250        | 0.011 (0.002)    | 0.344 (0.067)    | false (0.000) |    11.86 | JennyR, juliano, kyossa, pauliiee, Zana |
|            5 |     2874 | 2024-03-02 | Nemesis (Female team) | W   | 0.771      | 0.250        | 0.000 (0.000)    | 0.051 (0.010)    | false (0.000) |     5.32 | JennyR, juliano, kyossa, pauliiee, Zana |
|            4 |     3106 | 2024-02-25 | NAVI Javelins         | L   | 0.731      | -            | -                | -                | -             |    -7.04 | JennyR, juliano, kyossa, pauliiee, Zana |
|            3 |     3112 | 2024-02-25 | Let Her Cook          | W   | 0.730      | 0.143        | 0.000 (0.000)    | 0.191 (0.020)    | false (0.000) |     6.93 | JennyR, juliano, kyossa, pauliiee, Zana |
|            2 |     3168 | 2024-02-24 | Guild Esports         | W   | 0.724      | 0.143        | 0.010 (0.001)    | 0.194 (0.020)    | false (0.000) |    12.31 | JennyR, juliano, kyossa, pauliiee, Zana |
|            1 |     3181 | 2024-02-24 | ELITE (Female team)   | W   | 0.723      | -            | -                | -                | -             |     3.51 | JennyR, juliano, kyossa, pauliiee, Zana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($584.08)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
