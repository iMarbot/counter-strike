### Roster Details<br />
Team Name: True Rippers<br />
Roster: Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [108](../standings_global.md)<br />
Regional Rank: [12]( ../standings_asia.md)<br />
Final Rank Value:  842.7<br />
<br />
Final Rank Value (842.7) = Starting Rank Value (854.7) + Head To Head Adjustments (-12.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.448[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.139[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.7
- 400 + ( ( 0.229 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 854.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      294 | 2024-04-29 | Carnival Gaming        | W   | 1.000      | 0.262        | 0.013 (0.003)    | 0.056 (0.015)    | 0 (0.000) |    10.14 | Crazy_Gamer, Defaulter, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           21 |     1627 | 2024-03-31 | Gods Reign             | L   | 0.963      | -            | -                | -                | -         |   -12.15 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           20 |     1656 | 2024-03-30 | Marcos Gaming          | W   | 0.956      | 0.143        | 0.003 (0.000)    | 0.118 (0.016)    | 0 (0.000) |    11.35 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           19 |     1672 | 2024-03-29 | Grayfox Esports        | W   | 0.950      | 0.143        | 0.010 (0.001)    | 0.264 (0.036)    | 0 (0.000) |     8.91 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           18 |     1681 | 2024-03-29 | Crescent (Indian team) | W   | 0.949      | 0.143        | -                | 0.066 (0.009)    | 0 (0.000) |     2.90 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           17 |     1703 | 2024-03-28 | Marcos Gaming          | L   | 0.944      | -            | -                | -                | -         |   -18.01 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           16 |     1708 | 2024-03-28 | Frag Theory            | W   | 0.943      | -            | -                | -                | 0 (0.000) |     2.51 | Crazy_Gamer, DEFAULTER, Gh0sTTTT, Mcg1LLzZz, Rossi   |
|           15 |     1872 | 2024-03-23 | Marcos Gaming          | L   | 0.915      | -            | -                | -                | -         |   -18.89 | Anasasis, Crazy_Gamer, DEFAULTER, Mcg1LLzZz, Rossi   |
|           14 |     2115 | 2024-03-17 | Made In 4No            | L   | 0.873      | -            | -                | -                | -         |   -19.05 | Crazy_Gamer, DEFAULTER, DiceDealer, Mcg1LLzZz, Rossi |
|           13 |     3782 | 2024-02-09 | Marcos Gaming          | W   | 0.628      | 0.435        | 0.086 (0.024)    | 0.087 (0.024)    | 1 (0.628) |     8.21 | DEFAULTER, Gh0sTTTT, kennyS, Mcg1LLzZz, Rossi        |
|           12 |     3833 | 2024-02-08 | Gods Reign             | W   | 0.616      | 0.435        | 0.010 (0.003)    | 0.022 (0.006)    | 1 (0.616) |     6.20 | DEFAULTER, DiceDealer, Gh0sTTTT, kennyS, Mcg1LLzZz   |
|           11 |     3872 | 2024-02-06 | Revolution             | L   | 0.603      | -            | -                | -                | -         |   -16.52 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|           10 |     4040 | 2024-02-02 | Firedup Gaming         | W   | 0.578      | -            | -                | -                | 0 (0.000) |     2.00 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            9 |     4126 | 2024-01-31 | Gods Reign             | W   | 0.563      | 0.143        | 0.174 (0.014)    | 0.479 (0.039)    | 0 (0.000) |     9.37 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            8 |     4227 | 2024-01-28 | Enigma Gaming          | W   | 0.543      | -            | -                | -                | 0 (0.000) |     4.45 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            7 |     4289 | 2024-01-27 | Marcos Gaming          | W   | 0.536      | 0.143        | 0.086 (0.007)    | 0.087 (0.007)    | -         |     7.46 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            6 |     4394 | 2024-01-24 | GR Gaming              | L   | 0.517      | -            | -                | -                | -         |    -9.24 | Defaulter, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            5 |     4515 | 2024-01-21 | Grayfox Esports        | W   | 0.496      | 0.262        | 0.010 (0.001)    | 0.264 (0.034)    | -         |     4.42 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            4 |     4521 | 2024-01-20 | Firedup Gaming         | W   | 0.495      | -            | -                | -                | -         |     1.98 | DEFAULTER, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            3 |     6412 | 2023-11-25 | Gods Reign             | W   | 0.122      | 0.262        | 0.174 (0.006)    | 0.479 (0.015)    | -         |     2.54 | Defaulter, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |
|            2 |     6653 | 2023-11-20 | Grayfox Esports        | W   | 0.083      | 0.143        | 0.010 (0.000)    | -                | -         |     0.76 | ghostxD, LuciA, Marzil, Rite2ace, SH4DY              |
|            1 |     6657 | 2023-11-19 | Marcos Gaming          | L   | 0.082      | -            | -                | -                | -         |    -1.41 | Defaulter, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,331.36)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-29 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-03-17 |      0.873 | $250.00        | $218.17         |
| 2024-02-10 |      0.630 | $12,000.00     | $7,556.39       |
| 2024-01-21 |      0.496 | $1,000.00      | $495.88         |
| 2023-11-25 |      0.122 | $500.00        | $60.93          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
