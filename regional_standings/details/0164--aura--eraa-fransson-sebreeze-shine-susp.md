### Roster Details<br />
Team Name: AURA<br />
Roster: eraa, FRANSSON, SeBreeZe, SHiNE, susp<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [164](../standings_global.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
Final Rank Value:  762.3<br />
<br />
Final Rank Value (762.3) = Starting Rank Value (734.5) + Head To Head Adjustments (27.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 734.5
- 400 + ( ( 0.164 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 734.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      328 | 2024-05-24 | WompWomp        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.110 (0.016)    | 0 (0.000) |    11.44 | eraa, FRANSSON, SeBreeZe, SHiNE, susp     |
|           11 |      358 | 2024-05-24 | Rok paus vid 45 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |     7.86 | eraa, FRANSSON, SeBreeZe, SHiNE, susp     |
|           10 |     1432 | 2024-05-11 | Flying Angels   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.213 (0.030)    | 1 (1.000) |    12.01 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            9 |     1459 | 2024-05-11 | Lilmix          | L   | 1.000      | -            | -                | -                | -         |   -12.82 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            8 |     1603 | 2024-05-08 | ishjarnor       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.059 (0.008)    | 0 (0.000) |     4.41 | eraa, FRANSSON, SeBreeZe, SHiNE, susp     |
|            7 |     1605 | 2024-05-08 | Rok paus vid 45 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |     7.07 | eraa, FRANSSON, SeBreeZe, SHiNE, susp     |
|            6 |     1610 | 2024-05-08 | Young Gods      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.240 (0.034)    | 0 (0.000) |     9.48 | eraa, FRANSSON, SeBreeZe, SHiNE, susp     |
|            5 |     1957 | 2024-05-01 | Flying Angels   | L   | 1.000      | -            | -                | -                | -         |   -19.57 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            4 |     3156 | 2024-04-10 | Begrip Gaming   | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.317 (0.039)    | 0 (0.000) |     8.18 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            3 |     3159 | 2024-04-10 | showmakerz      | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.201 (0.025)    | 0 (0.000) |     7.87 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            2 |     3172 | 2024-04-10 | Flying Angels   | W   | 0.870      | 0.143        | 0.002 (0.000)    | 0.213 (0.027)    | 0 (0.000) |     9.94 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |
|            1 |     3540 | 2024-04-03 | showmakerz      | L   | 0.824      | -            | -                | -                | -         |   -18.08 | bobeksde, eraa, FRANSSON, SeBreeZe, SHiNE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,247.61)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-24 |      1.000 | $2,327.13      | $2,327.13       |
| 2024-05-11 |      1.000 | $920.48        | $920.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
