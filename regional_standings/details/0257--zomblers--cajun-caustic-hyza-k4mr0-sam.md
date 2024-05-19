### Roster Details<br />
Team Name: Zomblers<br />
Roster: CAJUN, caustic, hyza, K4mr0, sam<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [257](../standings_global.md)<br />
Regional Rank: [51]( ../standings_americas.md)<br />
Final Rank Value:  657.3<br />
<br />
Final Rank Value (657.3) = Starting Rank Value (669.4) + Head To Head Adjustments (-12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.4
- 400 + ( ( 0.136 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 669.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      983 | 2024-04-16 | NRG                        | L   | 1.000      | -            | -                | -                | -         |   -11.44 | CAJUN, caustic, hyza, K4mr0, sam   |
|            9 |     2389 | 2024-03-11 | Pryde                      | W   | 0.834      | 0.371        | 0.000 (0.000)    | 0.043 (0.013)    | 0 (0.000) |     5.14 | CAJUN, caustic, K4mr0, Marro, sam  |
|            8 |     2442 | 2024-03-10 | KingsOfTheNorth            | W   | 0.827      | 0.371        | 0.004 (0.001)    | 0.026 (0.008)    | 0 (0.000) |    12.20 | CAJUN, caustic, K4mr0, Marro, sam  |
|            7 |     3558 | 2024-02-15 | Limitless                  | L   | 0.667      | -            | -                | -                | -         |    -9.73 | CAJUN, K4mr0, Marro, sam, seziwana |
|            6 |     4299 | 2024-01-26 | Limitless                  | L   | 0.534      | -            | -                | -                | -         |    -8.04 | CAJUN, K4mr0, Marro, sam, X-23     |
|            5 |     4637 | 2024-01-18 | Nouns Esports              | L   | 0.480      | -            | -                | -                | -         |    -8.11 | CAJUN, K4mr0, Marro, sam, seziwana |
|            4 |     4683 | 2024-01-17 | FPL Friends                | W   | 0.474      | 0.143        | 0.005 (0.000)    | 0.028 (0.002)    | 0 (0.000) |     7.51 | CAJUN, K4mr0, Marro, sam, seziwana |
|            3 |     4822 | 2024-01-15 | Party Astronauts           | L   | 0.461      | -            | -                | -                | -         |    -4.66 | CAJUN, K4mr0, Marro, sam, seziwana |
|            2 |     5020 | 2024-01-10 | MIGHT                      | L   | 0.428      | -            | -                | -                | -         |    -5.82 | CAJUN, K4mr0, Marro, sam, seziwana |
|            1 |     5137 | 2024-01-08 | LAG Gaming (American team) | W   | 0.415      | 0.143        | 0.033 (0.002)    | 0.405 (0.024)    | 0 (0.000) |    10.81 | CAJUN, K4mr0, Marro, sam, seziwana |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,042.65)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
