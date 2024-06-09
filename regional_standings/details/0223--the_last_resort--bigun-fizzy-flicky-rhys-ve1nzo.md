### Roster Details<br />
Team Name: The Last Resort<br />
Roster: Bigun, Fizzy, Flicky, Rhys, ve1nzo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [223](../standings_global.md)<br />
Regional Rank: [150]( ../standings_europe.md)<br />
Final Rank Value:  706.4<br />
<br />
Final Rank Value (706.4) = Starting Rank Value (666.2) + Head To Head Adjustments (40.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.216[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.2
- 400 + ( ( 0.131 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 666.2


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
|           15 |      567 | 2024-05-21 | EXO Clan             | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.579 (0.083)    | 0 (0.000) |    20.19 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           14 |     1062 | 2024-05-16 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -6.51 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           13 |     1251 | 2024-05-14 | ROYALS               | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.143 (0.020)    | 0 (0.000) |    14.80 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           12 |     1564 | 2024-05-09 | Raptors Esports Club | L   | 1.000      | -            | -                | -                | -         |   -10.68 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           11 |     1682 | 2024-05-07 | Part Timers          | L   | 1.000      | -            | -                | -                | -         |   -15.07 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           10 |     1730 | 2024-05-06 | ex-K10               | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.517 (0.074)    | 0 (0.000) |    19.51 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|            9 |     2048 | 2024-04-30 | Team Invictum        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.175 (0.025)    | 0 (0.000) |    15.33 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|            8 |     2335 | 2024-04-25 | Halal5               | W   | 0.971      | 0.143        | 0.001 (0.000)    | 0.110 (0.015)    | 0 (0.000) |    15.61 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|            7 |     2449 | 2024-04-23 | FearFerox            | L   | 0.958      | -            | -                | -                | -         |   -16.24 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|            6 |     5712 | 2024-02-24 | Part Timers          | L   | 0.563      | -            | -                | -                | -         |    -7.04 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            5 |     5732 | 2024-02-24 | Reason Gaming        | W   | 0.562      | 0.143        | 0.004 (0.000)    | 0.133 (0.011)    | 1 (0.562) |    11.85 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            4 |     5756 | 2024-02-23 | Raptors Esports Club | L   | 0.558      | -            | -                | -                | -         |    -5.20 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            3 |     6471 | 2024-02-09 | Souls-Land           | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.079 (0.005)    | 0 (0.000) |     4.41 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            2 |     6478 | 2024-02-09 | RKB Fatties          | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.72 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            1 |     6757 | 2024-02-03 | ex-K10               | L   | 0.423      | -            | -                | -                | -         |    -3.48 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
