### Roster Details<br />
Team Name: Flamengo Esports<br />
Roster: Alisson, ALLE, caike, danoco, zock9<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [324](../standings_global.md)<br />
Regional Rank: [76]( ../standings_americas.md)<br />
Final Rank Value:  567.9<br />
<br />
Final Rank Value (567.9) = Starting Rank Value (541.9) + Head To Head Adjustments (26.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 541.9
- 400 + ( ( 0.072 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 541.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2251 | 2024-03-14 | MIBR Academy   | L   | 0.853      | -            | -                | -                | -             |    -7.10 | Alisson, ALLE, caike, danoco, zock9   |
|           11 |     2271 | 2024-03-14 | RED Canids     | L   | 0.851      | -            | -                | -                | -             |    -2.55 | Alisson, ALLE, caike, danoco, zock9   |
|           10 |     2394 | 2024-03-11 | MIBR Academy   | W   | 0.833      | 0.303        | 0.011 (0.003)    | 0.455 (0.115)    | false (0.000) |    19.64 | Alisson, ALLE, caike, danoco, zock9   |
|            9 |     2455 | 2024-03-10 | FURIA Academy  | L   | 0.825      | -            | -                | -                | -             |   -12.85 | Alisson, ALLE, danoco, voltera, zock9 |
|            8 |     3335 | 2024-02-20 | Team Solid     | L   | 0.700      | -            | -                | -                | -             |    -4.04 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            7 |     3338 | 2024-02-20 | Sharks Esports | W   | 0.699      | 0.143        | 0.063 (0.006)    | 0.343 (0.034)    | false (0.000) |    19.23 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            6 |     3390 | 2024-02-19 | Galorys        | W   | 0.694      | 0.143        | 0.048 (0.005)    | 0.598 (0.059)    | false (0.000) |    18.53 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            5 |     3519 | 2024-02-16 | Galorys        | L   | 0.673      | -            | -                | -                | -             |    -3.38 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            4 |     3540 | 2024-02-16 | LA RUGONETA    | L   | 0.671      | -            | -                | -                | -             |   -10.11 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            3 |     3589 | 2024-02-15 | Case Esports   | L   | 0.665      | -            | -                | -                | -             |    -3.54 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            2 |     3665 | 2024-02-13 | 9z Academy     | W   | 0.653      | 0.303        | 0.003 (0.001)    | 0.237 (0.047)    | false (0.000) |    13.74 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            1 |     3734 | 2024-02-12 | Fluxo          | L   | 0.644      | -            | -                | -                | -             |    -1.55 | ALLE, danoco, LUCAS1, ph1, zock9      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
