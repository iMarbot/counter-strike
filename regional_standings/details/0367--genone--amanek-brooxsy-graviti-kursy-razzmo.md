### Roster Details<br />
Team Name: GenOne<br />
Roster: AMANEK, Brooxsy, Graviti, Kursy, Razzmo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [367](../standings_global.md)<br />
Regional Rank: [219]( ../standings_europe.md)<br />
Final Rank Value:  597.8<br />
<br />
Final Rank Value (597.8) = Starting Rank Value (543.1) + Head To Head Adjustments (54.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.052[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 543.1
- 400 + ( ( 0.070 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 543.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     5156 | 2024-03-04 | 3DMAX                | L   | 0.625      | -            | -                | -                | -         |    -2.30 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           12 |     5292 | 2024-03-02 | BetBoom Team         | L   | 0.611      | -            | -                | -                | -         |    -0.24 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           11 |     5387 | 2024-03-01 | HOTU                 | W   | 0.603      | 0.371        | 0.004 (0.001)    | 0.580 (0.130)    | 0 (0.000) |    15.46 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|           10 |     5413 | 2024-02-29 | FLuffy Gangsters     | W   | 0.598      | 0.371        | 0.000 (0.000)    | 0.394 (0.087)    | 0 (0.000) |    10.72 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            9 |     5702 | 2024-02-24 | Eternal Fire Academy | W   | 0.563      | 0.371        | 0.003 (0.001)    | 0.078 (0.016)    | 0 (0.000) |    10.94 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            8 |     5818 | 2024-02-22 | Insilio              | L   | 0.550      | -            | -                | -                | -         |    -1.84 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            7 |     5870 | 2024-02-21 | Team Secret          | L   | 0.544      | -            | -                | -                | -         |    -6.20 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            6 |     5937 | 2024-02-20 | Permitta Esports     | L   | 0.537      | -            | -                | -                | -         |    -1.56 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            5 |     6118 | 2024-02-17 | RUBY                 | L   | 0.517      | -            | -                | -                | -         |    -1.85 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            4 |     6163 | 2024-02-16 | The Chosen Few       | W   | 0.510      | 0.371        | 0.000 (0.000)    | 0.262 (0.050)    | 0 (0.000) |    12.16 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            3 |     6342 | 2024-02-13 | Aurora Young Blud    | W   | 0.490      | 0.371        | 0.008 (0.002)    | 0.506 (0.092)    | 0 (0.000) |    12.33 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            2 |     6517 | 2024-02-08 | VP.Prodigy           | W   | 0.457      | 0.371        | 0.008 (0.001)    | 0.829 (0.141)    | 0 (0.000) |    12.45 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            1 |     6617 | 2024-02-05 | lajtbitexe           | L   | 0.437      | -            | -                | -                | -         |    -5.35 | AMANEK, bibu, Graviti, Kursy, Razzmo    |

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
