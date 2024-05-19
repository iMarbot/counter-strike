### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, victoria, vilga<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [201](../standings_global.md)<br />
Regional Rank: [133]( ../standings_europe.md)<br />
Final Rank Value:  713.3<br />
<br />
Final Rank Value (713.3) = Starting Rank Value (707.1) + Head To Head Adjustments (6.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 707.1
- 400 + ( ( 0.155 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 707.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      632 | 2024-04-21 | Guild Esports          | L   | 1.000      | -            | -                | -                | -             |   -15.41 | kr4sy, Ksu, t4tty, victoria, vilga |
|           11 |      693 | 2024-04-20 | BIG EQUIPA             | L   | 1.000      | -            | -                | -                | -             |   -14.31 | kr4sy, Ksu, t4tty, victoria, vilga |
|           10 |      818 | 2024-04-19 | 1win Gang              | W   | 1.000      | 0.331        | 0.007 (0.002)    | 0.061 (0.020)    | false (0.000) |    10.15 | kr4sy, Ksu, t4tty, victoria, vilga |
|            9 |     1168 | 2024-04-11 | Crescent (Female team) | W   | 1.000      | 0.331        | 0.008 (0.003)    | 0.187 (0.062)    | false (0.000) |    13.14 | kr4sy, Ksu, t4tty, victoria, vilga |
|            8 |     1374 | 2024-04-07 | NIP Impact             | L   | 1.000      | -            | -                | -                | -             |   -14.38 | kr4sy, Ksu, t4tty, victoria, vilga |
|            7 |     1414 | 2024-04-06 | Let Her Cook           | W   | 1.000      | 0.262        | 0.000 (0.000)    | 0.191 (0.050)    | false (0.000) |    10.06 | kr4sy, Ksu, t4tty, victoria, vilga |
|            6 |     1419 | 2024-04-06 | 5bites                 | W   | 1.000      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.17 | kr4sy, Ksu, t4tty, victoria, vilga |
|            5 |     1735 | 2024-03-27 | Team Spirit Female     | W   | 0.939      | 0.331        | 0.011 (0.004)    | 0.205 (0.064)    | false (0.000) |    14.65 | kr4sy, Ksu, t4tty, victoria, vilga |
|            4 |     2610 | 2024-03-06 | NAVI Javelins          | L   | 0.799      | -            | -                | -                | -             |    -7.12 | kr4sy, Ksu, t4tty, victoria, vilga |
|            3 |     3096 | 2024-02-25 | 1win Gang              | W   | 0.732      | 0.250        | 0.007 (0.001)    | 0.061 (0.011)    | false (0.000) |     9.92 | kr4sy, Ksu, t4tty, victoria, vilga |
|            2 |     3102 | 2024-02-25 | Nemesis (Female team)  | W   | 0.731      | 0.250        | 0.000 (0.000)    | 0.051 (0.009)    | false (0.000) |     5.64 | kr4sy, Ksu, t4tty, victoria, vilga |
|            1 |     3180 | 2024-02-24 | Guild Esports          | L   | 0.723      | -            | -                | -                | -             |   -10.36 | kr4sy, Ksu, t4tty, victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,148.92)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $1,600.00      | $1,600.00       |
| 2024-02-25 |      0.732 | $750.00        | $548.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
