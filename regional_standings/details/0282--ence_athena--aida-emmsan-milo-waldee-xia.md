### Roster Details<br />
Team Name: ENCE Athena<br />
Roster: Aida, Emmsan, miLo, Waldee, xia<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [282](../standings_global.md)<br />
Regional Rank: [180]( ../standings_europe.md)<br />
Final Rank Value:  658.8<br />
<br />
Final Rank Value (658.8) = Starting Rank Value (674.2) + Head To Head Adjustments (-15.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.2
- 400 + ( ( 0.135 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 674.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      931 | 2024-05-18 | Nemesis            | L   | 1.000      | -            | -                | -                | -         |   -22.02 | Aida, Emmsan, miLo, Waldee, xia   |
|           21 |     2223 | 2024-04-27 | NIP Impact         | L   | 0.983      | -            | -                | -                | -         |   -14.14 | Aida, Emmsan, miLo, Waldee, xia   |
|           20 |     2232 | 2024-04-27 | Nemesis            | W   | 0.982      | 0.143        | 0.000 (0.000)    | 0.102 (0.014)    | 0 (0.000) |     8.36 | Aida, Emmsan, miLo, Waldee, xia   |
|           19 |     2244 | 2024-04-27 | wwaves             | W   | 0.982      | 0.143        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |     7.37 | Aida, Emmsan, miLo, Waldee, xia   |
|           18 |     2748 | 2024-04-19 | Astralis Women     | W   | 0.930      | 0.331        | 0.003 (0.001)    | 0.054 (0.016)    | 0 (0.000) |    10.99 | Aida, Emmsan, miLo, Waldee, xia   |
|           17 |     3409 | 2024-04-07 | ex-FORZE Ladies    | L   | 0.851      | -            | -                | -                | -         |   -13.86 | Aida, Emmsan, miLo, Waldee, xia   |
|           16 |     3423 | 2024-04-07 | wwaves             | W   | 0.849      | 0.250        | 0.000 (0.000)    | 0.051 (0.011)    | 0 (0.000) |     7.10 | Aida, Emmsan, miLo, Waldee, xia   |
|           15 |     3463 | 2024-04-06 | MAVKY              | W   | 0.843      | -            | -                | -                | 0 (0.000) |     4.71 | Aida, Emmsan, miLo, Waldee, xia   |
|           14 |     3487 | 2024-04-06 | Team Pigeons       | L   | 0.842      | -            | -                | -                | -         |    -9.29 | Aida, Emmsan, miLo, Waldee, xia   |
|           13 |     3496 | 2024-04-06 | 1win Gang          | W   | 0.841      | 0.262        | 0.004 (0.001)    | 0.118 (0.026)    | 0 (0.000) |    11.52 | Aida, Emmsan, miLo, Waldee, xia   |
|           12 |     3579 | 2024-04-04 | BIG EQUIPA         | L   | 0.830      | -            | -                | -                | -         |   -11.43 | Aida, Emmsan, miLo, Waldee, xia   |
|           11 |     3882 | 2024-03-27 | Team Pigeons       | L   | 0.778      | -            | -                | -                | -         |    -9.36 | Aida, Emmsan, miLo, Waldee, xia   |
|           10 |     4228 | 2024-03-20 | NIP Impact         | L   | 0.731      | -            | -                | -                | -         |   -12.33 | Aida, Emmsan, miLo, Waldee, xia   |
|            9 |     4595 | 2024-03-13 | ex-Guild Esports   | W   | 0.684      | 0.331        | 0.005 (0.001)    | 0.166 (0.037)    | 0 (0.000) |    11.15 | Aida, Emmsan, miLo, Waldee, xia   |
|            8 |     5622 | 2024-02-25 | NAVI Javelins      | L   | 0.569      | -            | -                | -                | -         |    -6.49 | Aida, Emmsan, miLo, Waldee, xia   |
|            7 |     5709 | 2024-02-24 | Team Spirit Female | W   | 0.563      | 0.143        | 0.005 (0.000)    | 0.216 (0.017)    | 0 (0.000) |     9.00 | Aida, Emmsan, miLo, Waldee, xia   |
|            6 |     5721 | 2024-02-24 | ex-FORZE Ladies    | W   | 0.562      | 0.143        | 0.005 (0.000)    | 0.164 (0.013)    | 0 (0.000) |     8.35 | Aida, Emmsan, miLo, Waldee, xia   |
|            5 |     6266 | 2024-02-14 | more whiskey       | W   | 0.498      | 0.143        | -                | 0.056 (0.004)    | 0 (0.000) |     4.83 | Aida, Emmsan, miLo, Waldee, xia   |
|            4 |     6276 | 2024-02-14 | Nemesis            | W   | 0.497      | 0.143        | 0.002 (0.000)    | 0.089 (0.006)    | -         |     7.10 | Aida, Emmsan, miLo, Waldee, xia   |
|            3 |     6666 | 2024-02-04 | NAVI Javelins      | L   | 0.430      | -            | -                | -                | -         |    -4.75 | Aida, Emmsan, miLo, Waldee, xia   |
|            2 |     6714 | 2024-02-03 | Nemesis            | W   | 0.424      | 0.250        | 0.001 (0.000)    | -                | -         |     6.25 | Aida, Emmsan, miLo, Waldee, xia   |
|            1 |     7179 | 2024-01-27 | more whiskey       | L   | 0.377      | -            | -                | -                | -         |    -8.36 | Emmsan, Hikomi, miLo, Waldee, xia |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,308.84)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.983 | $107.03        | $105.21         |
| 2024-04-21 |      0.944 | $1,050.00      | $990.94         |
| 2024-04-07 |      0.851 | $250.00        | $212.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
