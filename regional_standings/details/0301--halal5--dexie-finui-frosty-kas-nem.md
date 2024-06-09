### Roster Details<br />
Team Name: Halal5<br />
Roster: dexie, Finui, Frosty, kas, Nem<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [301](../standings_global.md)<br />
Regional Rank: [187]( ../standings_europe.md)<br />
Final Rank Value:  644.6<br />
<br />
Final Rank Value (644.6) = Starting Rank Value (675.8) + Head To Head Adjustments (-31.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.8
- 400 + ( ( 0.136 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 675.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      120 | 2024-05-28 | Raptors Esports Club | L   | 1.000      | -            | -                | -                | -         |    -9.96 | dexie, Finui, Frosty, kas, Nem     |
|           11 |      285 | 2024-05-25 | Full Metal Jacket    | L   | 1.000      | -            | -                | -                | -         |   -12.28 | Aza, churley, Jackmon, lemowel, N8 |
|           10 |      291 | 2024-05-25 | KING & QUEEN'S       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     5.77 | dexie, dragSy, JamesBT, kas, Nem   |
|            9 |      569 | 2024-05-21 | Raptors Esports Club | L   | 1.000      | -            | -                | -                | -         |   -10.55 | dexie, Finui, Frosty, kas, Nem     |
|            8 |     1064 | 2024-05-16 | Part Timers          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.218 (0.031)    | 0 (0.000) |    16.68 | dexie, Finui, Frosty, kas, Nem     |
|            7 |     1252 | 2024-05-14 | ex-K10               | L   | 1.000      | -            | -                | -                | -         |   -11.39 | dexie, Finui, Frosty, kas, Nem     |
|            6 |     1314 | 2024-05-13 | FearFerox            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    14.71 | dexie, Finui, Frosty, kas, Nem     |
|            5 |     1566 | 2024-05-09 | Team Invictum        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.175 (0.025)    | 0 (0.000) |    17.21 | dexie, Finui, Frosty, kas, Nem     |
|            4 |     1621 | 2024-05-08 | ROYALS               | L   | 1.000      | -            | -                | -                | -         |   -14.47 | dexie, Finui, Frosty, kas, Nem     |
|            3 |     1683 | 2024-05-07 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -6.94 | dexie, Finui, Frosty, kas, Nem     |
|            2 |     2050 | 2024-04-30 | EXO Clan             | L   | 1.000      | -            | -                | -                | -         |    -4.31 | dexie, Finui, Frosty, kas, Nem     |
|            1 |     2335 | 2024-04-25 | The Last Resort      | L   | 0.971      | -            | -                | -                | -         |   -15.61 | dexie, Finui, Frosty, kas, Nem     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($271.37)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
