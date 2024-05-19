### Roster Details<br />
Team Name: AVEZ<br />
Roster: AntyVirus, przemeklovel, smooho, SpavaQ, Yamii<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [225](../standings_global.md)<br />
Regional Rank: [147]( ../standings_europe.md)<br />
Final Rank Value:  687.9<br />
<br />
Final Rank Value (687.9) = Starting Rank Value (677.5) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.318[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.5
- 400 + ( ( 0.140 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 677.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      832 | 2024-04-19 | ThunderFlash             | L   | 1.000      | -            | -                | -                | -             |   -11.69 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           12 |     1047 | 2024-04-15 | M1 Gaming                | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.035 (0.005)    | false (0.000) |    12.82 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           11 |     1174 | 2024-04-11 | 9INE Academy             | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.171 (0.024)    | false (0.000) |    16.20 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           10 |     1231 | 2024-04-10 | DEEZ NUTS                | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.094 (0.013)    | false (0.000) |    16.64 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            9 |     1277 | 2024-04-09 | Permitta Esports         | L   | 1.000      | -            | -                | -                | -             |    -6.42 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            8 |     2533 | 2024-03-08 | GamerLegion Academy      | L   | 0.811      | -            | -                | -                | -             |    -7.34 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            7 |     2577 | 2024-03-07 | BLESSED (Ukrainian team) | L   | 0.804      | -            | -                | -                | -             |    -5.53 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            6 |     3145 | 2024-02-24 | KOMNATA                  | L   | 0.725      | -            | -                | -                | -             |   -11.74 | hotd0g, jcobbb, killkapi, misho, nawrot         |
|            5 |     4089 | 2024-02-01 | EXO Clan                 | L   | 0.570      | -            | -                | -                | -             |    -4.49 | Adam9130, AwaykeN, bevve, dobbo, Duplicate      |
|            4 |     4149 | 2024-01-30 | Natus Vincere Youth      | W   | 0.558      | 0.289        | 0.013 (0.002)    | 0.306 (0.049)    | false (0.000) |    10.19 | cmtry, dziugss, froz1k, qzr, UNBR0KEN           |
|            3 |     4196 | 2024-01-29 | Sashi Academy            | L   | 0.552      | -            | -                | -                | -             |    -9.15 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            2 |     4386 | 2024-01-24 | Begrip Gaming            | W   | 0.518      | 0.289        | 0.001 (0.000)    | 0.196 (0.029)    | false (0.000) |     7.34 | Ariant0, Karma, Reedz, shateri, titulus         |
|            1 |     4816 | 2024-01-16 | Young Gods               | W   | 0.465      | 0.289        | 0.000 (0.000)    | 0.204 (0.028)    | false (0.000) |     3.63 | Cham, Focus, MaiL09, viz, Wonder                |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,148.25)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $739.38        | $739.38         |
| 2024-03-09 |      0.818 | $500.00        | $408.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
