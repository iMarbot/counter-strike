### Roster Details<br />
Team Name: Team Universe<br />
Roster: HoLLy, Lastík, Mix, semtex, suplicK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [288](../standings_global.md)<br />
Regional Rank: [178]( ../standings_europe.md)<br />
Final Rank Value:  624.3<br />
<br />
Final Rank Value (624.3) = Starting Rank Value (605.5) + Head To Head Adjustments (18.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.231[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.5
- 400 + ( ( 0.104 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 605.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2574 | 2024-03-07 | Dynamo Eclot                | L   | 0.805      | -            | -                | -                | -         |    -1.34 | HoLLy, Lastík, Mix, semtex, suplicK     |
|           11 |     2623 | 2024-03-06 | BRUTE                       | W   | 0.798      | 0.143        | 0.000 (0.000)    | 0.122 (0.014)    | 0 (0.000) |    10.17 | HoLLy, Lastík, pandi7o, semtex, suplicK |
|           10 |     2753 | 2024-03-04 | SINNERS Esports             | L   | 0.785      | -            | -                | -                | -         |    -2.60 | HoLLy, Lastík, Mix, semtex, suplicK     |
|            9 |     3038 | 2024-02-27 | Lan Party Hotel             | W   | 0.744      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.37 | HoLLy, Lastík, Mix, semtex, suplicK     |
|            8 |     3075 | 2024-02-26 | ANDROMEDA                   | W   | 0.737      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.45 | HoLLy, Lastík, Mix, semtex, suplicK     |
|            7 |     6602 | 2023-11-21 | Lazer Cats                  | L   | 0.091      | -            | -                | -                | -         |    -1.36 | HoLLy, Lastík, MAXX, Mix, semtex        |
|            6 |     6679 | 2023-11-19 | WOPA Esport                 | W   | 0.077      | 0.303        | 0.009 (0.000)    | 0.485 (0.011)    | 0 (0.000) |     1.75 | brzer, buNNy, Gnøffe, Leakz, LUMSEN     |
|            5 |     6979 | 2023-11-13 | Apeks Rebels                | W   | 0.038      | 0.289        | 0.005 (0.000)    | 0.071 (0.001)    | 0 (0.000) |     0.74 | HoLLy, Lastík, MAXX, Mix, semtex        |
|            4 |     7058 | 2023-11-11 | UNiTY esports (Slovak team) | L   | 0.025      | -            | -                | -                | -         |    -0.08 | Levi, luko, M1key, NIO, Pechyn          |
|            3 |     7089 | 2023-11-10 | RoundsGG                    | W   | 0.019      | 0.289        | 0.000 (0.000)    | 0.170 (0.001)    | 0 (0.000) |     0.39 | HoLLy, Lastík, MAXX, Mix, semtex        |
|            2 |     7098 | 2023-11-10 | ROSOMAHA                    | W   | 0.018      | 0.289        | 0.000 (0.000)    | 0.136 (0.001)    | 0 (0.000) |     0.29 | HoLLy, Lastík, MAXX, Mix, semtex        |
|            1 |     7177 | 2023-11-08 | LODIS                       | W   | 0.005      | 0.289        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.04 | Flayy, freo, kisserek, Majster, n0tice  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($75.46)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
