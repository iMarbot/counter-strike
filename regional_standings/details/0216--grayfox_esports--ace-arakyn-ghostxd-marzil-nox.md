### Roster Details<br />
Team Name: Grayfox Esports<br />
Roster: Ace, arakyN, ghostxD, Marzil, Nox<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [216](../standings_global.md)<br />
Regional Rank: [37]( ../standings_asia.md)<br />
Final Rank Value:  698.1<br />
<br />
Final Rank Value (698.1) = Starting Rank Value (692.8) + Head To Head Adjustments (5.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.8
- 400 + ( ( 0.148 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 692.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     1440 | 2024-04-05 | Made In 4No            | W   | 0.998      | 0.270        | 0.025 (0.007)    | 0.126 (0.034)    | 0 (0.000) |    17.57 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           21 |     1615 | 2024-03-31 | R8 Esports             | W   | 0.965      | 0.242        | 0.002 (0.001)    | 0.008 (0.002)    | 0 (0.000) |     9.56 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           20 |     1672 | 2024-03-29 | True Rippers           | L   | 0.950      | -            | -                | -                | -         |    -8.91 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           19 |     1680 | 2024-03-29 | Carnival Gaming        | W   | 0.949      | 0.143        | 0.013 (0.002)    | 0.056 (0.008)    | 0 (0.000) |    16.94 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           18 |     1701 | 2024-03-28 | Frag Theory            | W   | 0.944      | 0.143        | 0.000 (0.000)    | 0.033 (0.004)    | 0 (0.000) |     5.86 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           17 |     1707 | 2024-03-28 | Marcos Gaming          | L   | 0.943      | -            | -                | -                | -         |   -11.72 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           16 |     1871 | 2024-03-23 | Gods Reign             | L   | 0.915      | -            | -                | -                | -         |    -7.11 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           15 |     2772 | 2024-03-04 | Gods Reign             | L   | 0.783      | -            | -                | -                | -         |    -7.00 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           14 |     2819 | 2024-03-03 | Marcos Gaming          | L   | 0.776      | -            | -                | -                | -         |   -10.99 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           13 |     2896 | 2024-03-02 | Crescent (Indian team) | W   | 0.770      | 0.143        | 0.000 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     3.94 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           12 |     3115 | 2024-02-25 | Gods Reign             | L   | 0.729      | -            | -                | -                | -         |    -6.73 | Ace, arakyN, ghostxD, Marzil, Nox       |
|           11 |     3647 | 2024-02-14 | TyPuCTbl               | L   | 0.657      | -            | -                | -                | -         |   -12.71 | arakyN, Marzil, Nox, SeeK, SH4DY        |
|           10 |     3807 | 2024-02-09 | Enigma Gaming          | W   | 0.622      | 0.303        | 0.001 (0.000)    | 0.068 (0.013)    | 0 (0.000) |     9.34 | Ace, arakyN, Marzil, Nox, SeeK          |
|            9 |     3910 | 2024-02-05 | Drippy Lab             | W   | 0.596      | 0.303        | 0.000 (0.000)    | 0.033 (0.006)    | 0 (0.000) |     2.96 | Ace, arakyN, Marzil, Nox, SeeK          |
|            8 |     3940 | 2024-02-03 | Team NKT               | L   | 0.589      | -            | -                | -                | -         |    -6.58 | Ace, arakyN, Marzil, Nox, SeeK          |
|            7 |     4002 | 2024-02-03 | SR Nacague             | W   | 0.583      | 0.303        | 0.000 (0.000)    | 0.022 (0.004)    | 0 (0.000) |     2.77 | Ace, arakyN, Marzil, Nox, SeeK          |
|            6 |     4330 | 2024-01-26 | Enigma Gaming          | W   | 0.531      | 0.143        | 0.001 (0.000)    | 0.068 (0.005)    | 0 (0.000) |     7.75 | Ace, arakyN, Marzil, Nox, SeeK          |
|            5 |     4397 | 2024-01-24 | Local Esports          | W   | 0.517      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.66 | Ace, arakyN, Marzil, Nox, SeeK          |
|            4 |     4515 | 2024-01-21 | True Rippers           | L   | 0.496      | -            | -                | -                | -         |    -4.42 | Ace, arakyN, Marzil, Nox, SeeK          |
|            3 |     4520 | 2024-01-20 | Frag Theory            | W   | 0.495      | -            | -                | -                | -         |     2.52 | Ace, arakyN, Marzil, Nox, SeeK          |
|            2 |     6653 | 2023-11-20 | True Rippers           | L   | 0.083      | -            | -                | -                | -         |    -0.76 | ghostxD, LuciA, Marzil, Rite2ace, SH4DY |
|            1 |     6680 | 2023-11-19 | Team Respect           | W   | 0.077      | -            | -                | -                | -         |     0.39 | ghostxD, LuciA, Marzil, Rite2ace, SH4DY |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,612.38)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-05 |      0.998 | $600.00        | $598.97         |
| 2024-03-31 |      0.965 | $250.00        | $241.24         |
| 2024-02-25 |      0.729 | $500.00        | $364.56         |
| 2024-01-26 |      0.531 | $300.82        | $159.67         |
| 2024-01-21 |      0.496 | $500.00        | $247.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
