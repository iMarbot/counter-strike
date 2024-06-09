### Roster Details<br />
Team Name: MIBR Academy<br />
Roster: bobz, brn$, JLK, mlhzin, Nicks<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [303](../standings_global.md)<br />
Regional Rank: [67]( ../standings_americas.md)<br />
Final Rank Value:  644.0<br />
<br />
Final Rank Value (644.0) = Starting Rank Value (668.6) + Head To Head Adjustments (-24.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.6
- 400 + ( ( 0.132 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 668.6


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
|           18 |      107 | 2024-05-28 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -16.04 | bobz, brn$, JLK, mlhzin, Nicks |
|           17 |      154 | 2024-05-27 | Imperium Nexus eSports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     6.25 | bobz, brn$, JLK, mlhzin, Nicks |
|           16 |      201 | 2024-05-26 | 2Game Esports          | L   | 1.000      | -            | -                | -                | -         |   -16.08 | bobz, brn$, JLK, mlhzin, Nicks |
|           15 |      203 | 2024-05-26 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -16.78 | bobz, brn$, JLK, mlhzin, Nicks |
|           14 |      261 | 2024-05-25 | Alcateia Esports       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.27 | bobz, brn$, JLK, mlhzin, Nicks |
|           13 |      336 | 2024-05-24 | bebidarosa             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |     9.72 | bobz, brn$, JLK, mlhzin, Nicks |
|           12 |      343 | 2024-05-24 | Full House Gaming      | L   | 1.000      | -            | -                | -                | -         |   -16.48 | bobz, brn$, JLK, mlhzin, Nicks |
|           11 |      392 | 2024-05-23 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -14.86 | bobz, brn$, JLK, mlhzin, Nicks |
|           10 |      455 | 2024-05-22 | Romanticos             | L   | 1.000      | -            | -                | -                | -         |   -23.00 | bobz, brn$, JLK, mlhzin, Nicks |
|            9 |      654 | 2024-05-20 | Sharks Youngsters      | L   | 1.000      | -            | -                | -                | -         |   -17.62 | bobz, brn$, JLK, mlhzin, Nicks |
|            8 |      964 | 2024-05-17 | bebidarosa             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |     9.64 | bobz, brn$, JLK, mlhzin, Nicks |
|            7 |     1679 | 2024-05-07 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    15.90 | bobz, brn$, card, max, mlhzin  |
|            6 |     1681 | 2024-05-07 | 9z Academy             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.311 (0.044)    | 0 (0.000) |    12.65 | bobz, brn$, card, max, mlhzin  |
|            5 |     1726 | 2024-05-06 | paiN Gaming Academy    | L   | 1.000      | -            | -                | -                | -         |   -15.00 | bobz, brn$, card, max, mlhzin  |
|            4 |     1819 | 2024-05-04 | Yawara E-Sports        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.319 (0.046)    | 0 (0.000) |    14.94 | bobz, brn$, card, max, mlhzin  |
|            3 |     1973 | 2024-05-01 | Romanticos             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |     8.01 | bobz, brn$, card, max, mlhzin  |
|            2 |     1990 | 2024-05-01 | ex-Martians            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.064 (0.009)    | 0 (0.000) |    12.19 | bobz, brn$, card, max, mlhzin  |
|            1 |     2047 | 2024-04-30 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    16.69 | bobz, brn$, card, max, mlhzin  |

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
