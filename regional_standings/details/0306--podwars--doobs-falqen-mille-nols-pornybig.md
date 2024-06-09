### Roster Details<br />
Team Name: Podwars<br />
Roster: Doobs, falqen, mille, nOLS, PornyBig<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [306](../standings_global.md)<br />
Regional Rank: [191]( ../standings_europe.md)<br />
Final Rank Value:  641.0<br />
<br />
Final Rank Value (641.0) = Starting Rank Value (638.1) + Head To Head Adjustments (2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.1
- 400 + ( ( 0.117 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 638.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      213 | 2024-05-26 | Team Stockholm  | L   | 1.000      | -            | -                | -                | -         |   -14.32 | Doobs, falqen, mille, nOLS, PornyBig   |
|           11 |      216 | 2024-05-26 | Team Göteborg   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.08 | Doobs, falqen, mille, nOLS, PornyBig   |
|           10 |     1315 | 2024-05-13 | Flying Angels   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.213 (0.030)    | 0 (0.000) |    15.81 | Doobs, falqen, mille, nOLS, PornyBig   |
|            9 |     1325 | 2024-05-13 | showmakerz      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.201 (0.029)    | 0 (0.000) |    13.91 | Doobs, falqen, mille, nOLS, PornyBig   |
|            8 |     1505 | 2024-05-10 | Begrip Gaming   | L   | 1.000      | -            | -                | -                | -         |   -19.03 | Doobs, falqen, mille, nOLS, PornyBig   |
|            7 |     1625 | 2024-05-08 | Rok paus vid 45 | L   | 1.000      | -            | -                | -                | -         |   -21.75 | Doobs, falqen, mille, nOLS, PornyBig   |
|            6 |     1977 | 2024-05-01 | WompWomp        | L   | 1.000      | -            | -                | -                | -         |   -17.08 | Doobs, falqen, Gibsand, nOLS, PornyBig |
|            5 |     1979 | 2024-05-01 | Flying Angels   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.213 (0.030)    | 0 (0.000) |    14.72 | Doobs, falqen, Gibsand, nOLS, PornyBig |
|            4 |     1987 | 2024-05-01 | Begrip Gaming   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.317 (0.045)    | 0 (0.000) |    10.66 | Doobs, falqen, Gibsand, nOLS, PornyBig |
|            3 |     3621 | 2024-04-03 | Lilmix          | L   | 0.825      | -            | -                | -                | -         |    -8.65 | Doobs, falqen, Gibsand, nOLS, PornyBig |
|            2 |     3622 | 2024-04-03 | showmakerz      | W   | 0.825      | 0.143        | 0.000 (0.000)    | 0.201 (0.024)    | 0 (0.000) |    10.66 | Doobs, falqen, Gibsand, nOLS, PornyBig |
|            1 |     3624 | 2024-04-03 | Lemondogs       | W   | 0.824      | 0.143        | 0.000 (0.000)    | 0.314 (0.037)    | 0 (0.000) |    11.93 | Doobs, falqen, Gibsand, nOLS, PornyBig |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($460.21)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
