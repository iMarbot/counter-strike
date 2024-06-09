### Roster Details<br />
Team Name: The QUBE Esports<br />
Roster: aNSeLMO, deadsh9t, hoolig4n, me1o, Randy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [396](../standings_global.md)<br />
Regional Rank: [60]( ../standings_asia.md)<br />
Final Rank Value:  567.7<br />
<br />
Final Rank Value (567.7) = Starting Rank Value (565.2) + Head To Head Adjustments (2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.179[<sup>1</sup>](#table2)
- Bounty Collected: 0.146[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.081<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 565.2
- 400 + ( ( 0.081 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 565.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     6298 | 2024-02-14 | The Huns Esports | L   | 0.496      | -            | -                | -                | -         |    -2.24 | aNSeLMO, deadsh9t, hoolig4n, me1o, Randy           |
|            9 |     8675 | 2023-12-18 | MIRAI Gaming     | W   | 0.109      | 0.143        | 0.000 (0.000)    | 0.200 (0.003)    | 0 (0.000) |     2.37 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            8 |     8744 | 2023-12-17 | Eruption         | W   | 0.102      | 0.143        | 0.000 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.75 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            7 |     8892 | 2023-12-16 | Born In Far East | L   | 0.096      | -            | -                | -                | -         |    -0.93 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            6 |     9014 | 2023-12-15 | Hyper5           | W   | 0.089      | 0.143        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     1.59 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            5 |     9154 | 2023-12-12 | DEWA United      | L   | 0.069      | -            | -                | -                | -         |    -0.95 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            4 |     9245 | 2023-12-10 | Eruption         | L   | 0.056      | -            | -                | -                | -         |    -0.81 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            3 |     9304 | 2023-12-09 | ZEUSGG           | W   | 0.049      | 0.250        | 0.000 (0.000)    | 0.090 (0.001)    | 0 (0.000) |     0.78 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            2 |     9449 | 2023-12-07 | MIRAI Gaming     | W   | 0.036      | 0.250        | 0.000 (0.000)    | 0.200 (0.002)    | 0 (0.000) |     0.78 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            1 |     9592 | 2023-12-05 | RAVENS           | W   | 0.023      | 0.250        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.20 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7.60)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
