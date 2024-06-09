### Roster Details<br />
Team Name: True Rippers<br />
Roster: Crazy_Gamer, DayMake, Defaulter, Mcg1LLzZz, Rossi<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [186](../standings_global.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
Final Rank Value:  741.7<br />
<br />
Final Rank Value (741.7) = Starting Rank Value (762.5) + Head To Head Adjustments (-20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.049[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 762.5
- 400 + ( ( 0.178 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 762.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      242 | 2024-05-26 | Gods Reign      | L   | 1.000      | -            | -                | -                | -         |   -11.42 | Crazy_Gamer, DayMake, Defaulter, Mcg1LLzZz, Rossi    |
|           30 |      246 | 2024-05-25 | Carnival Gaming | W   | 1.000      | 0.262        | 0.002 (0.000)    | 0.022 (0.006)    | 0 (0.000) |     8.91 | Crazy_Gamer, DayMake, Defaulter, Mcg1LLzZz, Rossi    |
|           29 |     2123 | 2024-04-28 | Carnival Gaming | W   | 0.994      | 0.262        | 0.002 (0.000)    | 0.022 (0.006)    | 0 (0.000) |     9.53 | Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           28 |     2152 | 2024-04-28 | Gods Reign      | L   | 0.989      | -            | -                | -                | -         |   -10.69 | Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           27 |     2225 | 2024-04-27 | Gods Reign      | L   | 0.983      | -            | -                | -                | -         |   -11.51 | Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           26 |     2248 | 2024-04-27 | Grayfox Esports | W   | 0.982      | 0.143        | 0.004 (0.001)    | 0.204 (0.029)    | 0 (0.000) |    11.47 | Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           25 |     3525 | 2024-04-05 | love birds      | L   | 0.837      | -            | -                | -                | -         |   -13.29 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           24 |     3543 | 2024-04-05 | khatru peek     | W   | 0.835      | 0.270        | 0.001 (0.000)    | 0.046 (0.010)    | 0 (0.000) |     8.78 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           23 |     3753 | 2024-03-31 | Gods Reign      | L   | 0.801      | -            | -                | -                | -         |    -7.28 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           22 |     3789 | 2024-03-30 | Marcos Gaming   | W   | 0.795      | 0.143        | -                | 0.091 (0.010)    | 0 (0.000) |    10.89 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           21 |     3807 | 2024-03-29 | Grayfox Esports | W   | 0.789      | 0.143        | 0.004 (0.000)    | 0.204 (0.023)    | 0 (0.000) |     9.74 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           20 |     3817 | 2024-03-29 | Crescent        | W   | 0.788      | -            | -                | -                | 0 (0.000) |     5.38 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           19 |     3844 | 2024-03-28 | Marcos Gaming   | L   | 0.783      | -            | -                | -                | -         |   -13.47 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           18 |     3849 | 2024-03-28 | Frag Theory     | W   | 0.782      | -            | -                | -                | 0 (0.000) |     3.32 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           17 |     4056 | 2024-03-23 | Marcos Gaming   | L   | 0.754      | -            | -                | -                | -         |   -13.95 | Anasasis, Crazy_Gamer, DEFAULTER, Mcg1LLzZz, Rossi   |
|           16 |     4339 | 2024-03-17 | Made In 4No     | L   | 0.712      | -            | -                | -                | -         |   -13.31 | Crazy_Gamer, DEFAULTER, DiceDealer, Mcg1LLzZz, Rossi |
|           15 |     4367 | 2024-03-17 | st4rboys        | W   | 0.711      | 0.242        | 0.014 (0.002)    | 0.088 (0.015)    | 0 (0.000) |     8.16 | Crazy_Gamer, DEFAULTER, DiceDealer, Mcg1LLzZz, Rossi |
|           14 |     5252 | 2024-03-03 | Gods Reign      | L   | 0.616      | -            | -                | -                | -         |    -7.26 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           13 |     5256 | 2024-03-03 | 2ez Gaming      | W   | 0.615      | 0.143        | -                | 0.095 (0.008)    | -         |     6.15 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           12 |     5342 | 2024-03-02 | Grayfox Esports | L   | 0.610      | -            | -                | -                | -         |   -12.16 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           11 |     5356 | 2024-03-02 | Accuracy Gaming | W   | 0.609      | -            | -                | -                | -         |     2.11 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           10 |     6470 | 2024-02-09 | Marcos Gaming   | W   | 0.467      | 0.435        | 0.031 (0.006)    | -                | 1 (0.467) |     6.87 | DEFAULTER, Gh0sTTTT, kennyS, Mcg1LLzZz, Rossi        |
|            9 |     6590 | 2024-02-06 | Revolution      | L   | 0.442      | -            | -                | -                | -         |   -11.23 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            8 |     6829 | 2024-02-02 | Firedup Gaming  | W   | 0.417      | -            | -                | -                | -         |     3.60 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            7 |     6951 | 2024-01-31 | Gods Reign      | L   | 0.402      | -            | -                | -                | -         |    -7.71 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            6 |     7054 | 2024-01-29 | 2ez Gaming      | W   | 0.389      | -            | -                | -                | -         |     3.46 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            5 |     7102 | 2024-01-28 | Enigma Gaming   | W   | 0.382      | 0.143        | 0.004 (0.000)    | -                | -         |     4.55 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            4 |     7212 | 2024-01-27 | Gods Reign      | W   | 0.375      | 0.143        | 0.086 (0.005)    | 0.461 (0.025)    | -         |     8.15 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            3 |     7367 | 2024-01-24 | GR Gaming       | L   | 0.356      | -            | -                | -                | -         |    -5.44 | Defaulter, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            2 |     7533 | 2024-01-21 | Grayfox Esports | W   | 0.335      | 0.262        | 0.004 (0.000)    | 0.204 (0.018)    | -         |     3.95 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            1 |     7540 | 2024-01-20 | Firedup Gaming  | W   | 0.334      | -            | -                | -                | -         |     2.96 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,630.63)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $500.00        | $500.00         |
| 2024-04-28 |      0.994 | $1,000.00      | $994.31         |
| 2024-03-17 |      0.712 | $250.00        | $177.90         |
| 2024-02-10 |      0.469 | $12,000.00     | $5,623.61       |
| 2024-01-21 |      0.335 | $1,000.00      | $334.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
