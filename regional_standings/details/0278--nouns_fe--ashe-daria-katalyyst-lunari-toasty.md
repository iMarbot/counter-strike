### Roster Details<br />
Team Name: Nouns.fe<br />
Roster: ashe, daria, katalyyst, lunari, toasty<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [278](../standings_global.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
Final Rank Value:  632.0<br />
<br />
Final Rank Value (632.0) = Starting Rank Value (685.1) + Head To Head Adjustments (-53.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.230[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.1
- 400 + ( ( 0.144 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 685.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       38 | 2024-05-04 | Limitless Angels     | L   | 1.000      | -            | -                | -                | -             |   -15.33 | ashe, daria, katalyyst, lunari, toasty   |
|           10 |      791 | 2024-04-19 | FlyQuest RED         | L   | 1.000      | -            | -                | -                | -             |    -8.69 | ashe, jesscas, katalyyst, lunari, tokkis |
|            9 |     1085 | 2024-04-13 | Shimmer              | L   | 1.000      | -            | -                | -                | -             |   -10.53 | ashe, katalyyst, Knopk@, lunari, toasty  |
|            8 |     1163 | 2024-04-11 | Limitless Angels     | L   | 1.000      | -            | -                | -                | -             |   -15.28 | ashe, jesscas, katalyyst, lunari, tokkis |
|            7 |     1718 | 2024-03-27 | Team Karma           | L   | 0.940      | -            | -                | -                | -             |   -14.85 | ashe, jesscas, katalyyst, lunari, tokkis |
|            6 |     1957 | 2024-03-21 | COVEN                | W   | 0.900      | 0.322        | 0.006 (0.002)    | 0.000 (0.000)    | false (0.000) |     8.39 | ashe, jesscas, katalyyst, lunari, tokkis |
|            5 |     2161 | 2024-03-16 | Radiant Rebels       | W   | 0.867      | 0.250        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.79 | ashe, jesscas, katalyyst, lunari, Rice   |
|            4 |     2242 | 2024-03-14 | Shimmer              | L   | 0.854      | -            | -                | -                | -             |   -12.09 | ashe, jesscas, katalyyst, lunari, tokkis |
|            3 |     2596 | 2024-03-06 | Wanted Goons Bandits | W   | 0.800      | 0.322        | 0.007 (0.002)    | 0.038 (0.010)    | false (0.000) |    11.33 | ashe, jesscas, katalyyst, lunari, tokkis |
|            2 |     2822 | 2024-03-02 | FlyQuest RED         | L   | 0.774      | -            | -                | -                | -             |   -10.49 | ashe, jesscas, katalyyst, lunari, Rice   |
|            1 |     3663 | 2024-02-13 | COVEN                | W   | 0.653      | 0.143        | 0.006 (0.001)    | 0.000 (0.000)    | false (0.000) |     6.59 | ashe, jesscas, katalyyst, lunari, Rice   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,950.47)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-19 |      1.000 | $1,300.00      | $1,300.00       |
| 2024-03-16 |      0.867 | $750.00        | $650.47         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
