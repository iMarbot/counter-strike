### Roster Details<br />
Team Name: IMMAPROBLEM<br />
Roster: Damkilde, J3nsyy, NoProblemGuy, notaN, vester<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [377](../standings_global.md)<br />
Regional Rank: [225]( ../standings_europe.md)<br />
Final Rank Value:  577.3<br />
<br />
Final Rank Value (577.3) = Starting Rank Value (526.1) + Head To Head Adjustments (51.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.1
- 400 + ( ( 0.062 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 526.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      160 | 2024-05-27 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -1.07 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           27 |      177 | 2024-05-27 | XI Esport           | L   | 1.000      | -            | -                | -                | -         |   -11.21 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           26 |      684 | 2024-05-20 | WOPA Esport         | L   | 1.000      | -            | -                | -                | -         |    -8.13 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           25 |      688 | 2024-05-20 | Sashi Academy       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.088 (0.013)    | 0 (0.000) |    15.03 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           24 |     1723 | 2024-05-06 | Copenhagen Wolves   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.309 (0.044)    | 0 (0.000) |    17.53 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           23 |     1729 | 2024-05-06 | WOPA Esport         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    23.87 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           22 |     2058 | 2024-04-29 | XI Esport           | W   | 0.997      | 0.143        | 0.001 (0.000)    | 0.277 (0.039)    | 0 (0.000) |    21.34 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           21 |     2440 | 2024-04-22 | Sashi Academy       | L   | 0.951      | -            | -                | -                | -         |   -11.38 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           20 |     2444 | 2024-04-22 | Preasy Esport       | L   | 0.951      | -            | -                | -                | -         |    -7.39 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           19 |     2451 | 2024-04-22 | Astralis Talent     | L   | 0.950      | -            | -                | -                | -         |    -4.63 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           18 |     2939 | 2024-04-15 | Sashi Esport        | L   | 0.904      | -            | -                | -                | -         |    -1.34 | Damkilde, J3nsyy, NoProblemGuy, notaN, vester |
|           17 |     4197 | 2024-03-18 | Kronjyllands Esport | W   | 0.718      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     9.59 | daxy, J3nsyy, NoProblemGuy, notaN, vester     |
|           16 |     4607 | 2024-03-11 | Team Atlantic       | L   | 0.671      | -            | -                | -                | -         |   -10.70 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           15 |     4849 | 2024-03-06 | Copenhagen Wolves   | L   | 0.638      | -            | -                | -                | -         |    -7.70 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           14 |     4859 | 2024-03-06 | Preasy Esport       | L   | 0.638      | -            | -                | -                | -         |    -3.87 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           13 |     4878 | 2024-03-06 | Astralis Talent     | W   | 0.637      | 0.143        | 0.012 (0.001)    | 0.452 (0.041)    | 0 (0.000) |    18.01 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           12 |     4953 | 2024-03-05 | XI Esport           | W   | 0.631      | 0.143        | 0.001 (0.000)    | 0.277 (0.025)    | 0 (0.000) |    13.71 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           11 |     4963 | 2024-03-05 | WOPA Esport         | L   | 0.631      | -            | -                | -                | -         |    -3.88 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|           10 |     4999 | 2024-03-04 | Pera Esports        | L   | 0.625      | -            | -                | -                | -         |    -2.27 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            9 |     5131 | 2024-03-02 | Lilmix              | L   | 0.611      | -            | -                | -                | -         |    -3.14 | Brillo, dex, poiii, quix, zyyx                |
|            8 |     5403 | 2024-02-26 | AURA                | L   | 0.578      | -            | -                | -                | -         |    -6.08 | Damkilde, daxy, J3nsyy, notaN, vester         |
|            7 |     6376 | 2024-02-06 | XI Esport           | L   | 0.444      | -            | -                | -                | -         |    -4.42 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            6 |     6378 | 2024-02-06 | Team Atlantic       | W   | 0.444      | 0.143        | 0.000 (0.000)    | 0.074 (0.005)    | 0 (0.000) |     6.73 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            5 |     6401 | 2024-02-05 | Copenhagen Wolves   | W   | 0.438      | 0.143        | 0.000 (0.000)    | 0.309 (0.019)    | 0 (0.000) |     8.96 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            4 |     6409 | 2024-02-05 | Preasy Esport       | L   | 0.438      | -            | -                | -                | -         |    -2.17 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            3 |     7207 | 2024-01-22 | Astralis Talent     | W   | 0.345      | 0.143        | 0.012 (0.001)    | 0.452 (0.022)    | 0 (0.000) |     9.83 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            2 |     7217 | 2024-01-22 | Sashi Esport        | L   | 0.344      | -            | -                | -                | -         |    -2.11 | Damkilde, daxy, NoProblemGuy, notaN, vester   |
|            1 |     7230 | 2024-01-22 | WOPA Esport         | L   | 0.344      | -            | -                | -                | -         |    -1.90 | Damkilde, daxy, NoProblemGuy, notaN, vester   |

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
