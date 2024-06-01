### Roster Details<br />
Team Name: MIBR Academy<br />
Roster: bobz, brn$, JLK, mlhzin, Nicks<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [298](../standings_global.md)<br />
Regional Rank: [67]( ../standings_americas.md)<br />
Final Rank Value:  642.0<br />
<br />
Final Rank Value (642.0) = Starting Rank Value (669.7) + Head To Head Adjustments (-27.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.7
- 400 + ( ( 0.132 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 669.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      100 | 2024-05-28 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -15.93 | bobz, brn$, JLK, mlhzin, Nicks |
|           18 |      147 | 2024-05-27 | Imperium Nexus eSports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     6.31 | bobz, brn$, JLK, mlhzin, Nicks |
|           17 |      193 | 2024-05-26 | 2Game Esports          | L   | 1.000      | -            | -                | -                | -         |   -16.37 | bobz, brn$, JLK, mlhzin, Nicks |
|           16 |      195 | 2024-05-26 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -16.64 | bobz, brn$, JLK, mlhzin, Nicks |
|           15 |      253 | 2024-05-25 | Alcateia Esports       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.32 | bobz, brn$, JLK, mlhzin, Nicks |
|           14 |      327 | 2024-05-24 | bebidarosa             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |    10.06 | bobz, brn$, JLK, mlhzin, Nicks |
|           13 |      334 | 2024-05-24 | Full House Gaming      | L   | 1.000      | -            | -                | -                | -         |   -15.97 | bobz, brn$, JLK, mlhzin, Nicks |
|           12 |      383 | 2024-05-23 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -12.36 | bobz, brn$, JLK, mlhzin, Nicks |
|           11 |      449 | 2024-05-22 | Romanticos             | L   | 1.000      | -            | -                | -                | -         |   -19.00 | bobz, brn$, JLK, mlhzin, Nicks |
|           10 |      643 | 2024-05-20 | Sharks Youngsters      | L   | 1.000      | -            | -                | -                | -         |   -16.80 | bobz, brn$, JLK, mlhzin, Nicks |
|            9 |      952 | 2024-05-17 | bebidarosa             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |    10.10 | bobz, brn$, JLK, mlhzin, Nicks |
|            8 |     1050 | 2024-05-16 | paiN Gaming Academy    | L   | 1.000      | -            | -                | -                | -         |   -15.56 | bobz, brn$, JLK, mlhzin, Nicks |
|            7 |     1661 | 2024-05-07 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.374 (0.053)    | 0 (0.000) |    15.96 | bobz, brn$, card, max, mlhzin  |
|            6 |     1663 | 2024-05-07 | 9z Academy             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.311 (0.044)    | 0 (0.000) |    12.51 | bobz, brn$, card, max, mlhzin  |
|            5 |     1706 | 2024-05-06 | paiN Gaming Academy    | L   | 1.000      | -            | -                | -                | -         |   -14.95 | bobz, brn$, card, max, mlhzin  |
|            4 |     1796 | 2024-05-04 | Yawara E-Sports        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.319 (0.046)    | 0 (0.000) |    14.76 | bobz, brn$, card, max, mlhzin  |
|            3 |     1946 | 2024-05-01 | Romanticos             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    11.74 | bobz, brn$, card, max, mlhzin  |
|            2 |     1963 | 2024-05-01 | ex-Martians            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.064 (0.009)    | 0 (0.000) |    12.38 | bobz, brn$, card, max, mlhzin  |
|            1 |     2016 | 2024-04-30 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.374 (0.053)    | 0 (0.000) |    16.76 | bobz, brn$, card, max, mlhzin  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($984.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
