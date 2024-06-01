### Roster Details<br />
Team Name: Team Karma<br />
Roster: artStar, Ellie, EMUHLEET, olya, rain<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [227](../standings_global.md)<br />
Regional Rank: [48]( ../standings_americas.md)<br />
Final Rank Value:  704.8<br />
<br />
Final Rank Value (704.8) = Starting Rank Value (684.8) + Head To Head Adjustments (20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.8
- 400 + ( ( 0.140 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 684.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       22 | 2024-05-29 | Wildcard Gaming      | L   | 1.000      | -            | -                | -                | -         |    -5.60 | artStar, Ellie, EMUHLEET, olya, rain |
|            9 |       30 | 2024-05-29 | LotionDrinkers23     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.71 | artStar, Ellie, EMUHLEET, olya, rain |
|            8 |      198 | 2024-05-26 | TSM Shimmer          | L   | 1.000      | -            | -                | -                | -         |   -13.28 | artStar, Ellie, EMUHLEET, olya, rain |
|            7 |     2667 | 2024-04-19 | cleanup crew         | W   | 0.932      | 0.322        | 0.004 (0.001)    | 0.054 (0.016)    | 0 (0.000) |    11.18 | artStar, Ellie, EMUHLEET, olya, rain |
|            6 |     3147 | 2024-04-10 | Wanted Goons Bandits | W   | 0.872      | 0.322        | 0.003 (0.001)    | 0.039 (0.011)    | 0 (0.000) |     9.64 | artStar, Ellie, EMUHLEET, olya, rain |
|            5 |     3527 | 2024-04-03 | Limitless Angels     | W   | 0.825      | 0.322        | 0.005 (0.001)    | 0.109 (0.029)    | 0 (0.000) |    12.44 | artStar, Ellie, EMUHLEET, olya, rain |
|            4 |     3768 | 2024-03-27 | Nouns.fe             | W   | 0.779      | 0.322        | 0.006 (0.001)    | 0.080 (0.020)    | 0 (0.000) |    11.85 | artStar, Ellie, EMUHLEET, olya, rain |
|            3 |     4052 | 2024-03-21 | TSM Shimmer          | L   | 0.739      | -            | -                | -                | -         |   -10.05 | artStar, Ellie, EMUHLEET, olya, rain |
|            2 |     4458 | 2024-03-13 | FlyQuest RED         | L   | 0.686      | -            | -                | -                | -         |    -7.22 | artStar, Ellie, EMUHLEET, olya, rain |
|            1 |     4782 | 2024-03-07 | COVEN                | W   | 0.646      | 0.322        | 0.003 (0.001)    | 0.014 (0.003)    | 0 (0.000) |     6.28 | artStar, Ellie, EMUHLEET, olya, rain |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,084.78)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $500.00        | $500.00         |
| 2024-04-19 |      0.932 | $1,700.00      | $1,584.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
