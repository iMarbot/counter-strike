### Roster Details<br />
Team Name: Kappa Borr<br />
Roster: JiBe, Ludwig, slinger, virree, zen<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [436](../standings_global.md)<br />
Regional Rank: [265]( ../standings_europe.md)<br />
Final Rank Value:  513.9<br />
<br />
Final Rank Value (513.9) = Starting Rank Value (478.1) + Head To Head Adjustments (35.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.140[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 478.1
- 400 + ( ( 0.038 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 478.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      485 | 2024-05-22 | regelett      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.129 (0.018)    | 0 (0.000) |    12.00 | JiBe, Ludwig, slinger, virree, zen        |
|           10 |     1572 | 2024-05-09 | Begrip Gaming | L   | 1.000      | -            | -                | -                | -         |   -14.52 | JiBe, Ludwig, slinger, virree, zen        |
|            9 |     3322 | 2024-04-09 | showmakerz    | W   | 0.863      | 0.143        | 0.000 (0.000)    | 0.201 (0.025)    | 0 (0.000) |    16.21 | JiBe, Ludwig, slinger, virree, zen        |
|            8 |     3465 | 2024-04-06 | plusW         | L   | 0.843      | -            | -                | -                | -         |   -11.54 | JiBe, Ludwig, slinger, virree, zen        |
|            7 |     3887 | 2024-03-27 | Kappa Bar     | L   | 0.778      | -            | -                | -                | -         |   -11.38 | JiBe, Ludwig, slinger, virree, zen        |
|            6 |     4269 | 2024-03-19 | Lemondogs     | W   | 0.724      | 0.143        | 0.000 (0.000)    | 0.314 (0.032)    | 0 (0.000) |    14.78 | JiBe, Ludwig, slinger, virree, zen        |
|            5 |     4361 | 2024-03-17 | Begrip Gaming | W   | 0.711      | 0.143        | 0.000 (0.000)    | 0.317 (0.032)    | 0 (0.000) |    14.03 | JiBe, Ludwig, slinger, virree, zen        |
|            4 |     4830 | 2024-03-09 | Alliance      | L   | 0.657      | -            | -                | -                | -         |    -2.29 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     4836 | 2024-03-09 | AURA          | W   | 0.657      | 0.143        | 0.000 (0.000)    | 0.274 (0.026)    | 0 (0.000) |    15.41 | jayzaR, Ludwig, Twinkey, virree, zen      |
|            2 |     4857 | 2024-03-09 | Eld           | W   | 0.656      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.07 | jayzaR, Ludwig, Twinkey, virree, zen      |
|            1 |     6431 | 2024-02-11 | Sashi Esport  | L   | 0.477      | -            | -                | -                | -         |    -4.92 | b0RUP, Fessor, n1Xen, niko, nut nut       |

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
