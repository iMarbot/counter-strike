### Roster Details<br />
Team Name: Grayfox Esports<br />
Roster: Ace, arakyN, ghostxD, Marzil, Nox<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [283](../standings_global.md)<br />
Regional Rank: [46]( ../standings_asia.md)<br />
Final Rank Value:  652.8<br />
<br />
Final Rank Value (652.8) = Starting Rank Value (674.0) + Head To Head Adjustments (-21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.296[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.0
- 400 + ( ( 0.135 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 674.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     2213 | 2024-04-27 | True Rippers    | L   | 0.982      | -            | -                | -                | -         |   -11.47 | Ace, arakyN, ghostxD, Marzil, Nox |
|           27 |     2283 | 2024-04-26 | ROG Academy     | W   | 0.975      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     5.46 | Ace, arakyN, ghostxD, Marzil, Nox |
|           26 |     3374 | 2024-04-06 | love birds      | L   | 0.844      | -            | -                | -                | -         |    -9.70 | Ace, arakyN, ghostxD, Marzil, Nox |
|           25 |     3440 | 2024-04-05 | Made In 4No     | W   | 0.837      | 0.270        | 0.010 (0.002)    | 0.106 (0.024)    | 0 (0.000) |    14.88 | Ace, arakyN, ghostxD, Marzil, Nox |
|           24 |     3637 | 2024-03-31 | st4rboys        | L   | 0.805      | -            | -                | -                | -         |   -12.34 | Ace, arakyN, ghostxD, Marzil, Nox |
|           23 |     3643 | 2024-03-31 | R8 Esports      | W   | 0.804      | 0.242        | 0.000 (0.000)    | -                | 0 (0.000) |     7.70 | Ace, arakyN, ghostxD, Marzil, Nox |
|           22 |     3713 | 2024-03-29 | True Rippers    | L   | 0.789      | -            | -                | -                | -         |    -9.77 | Ace, arakyN, ghostxD, Marzil, Nox |
|           21 |     3722 | 2024-03-29 | Carnival Gaming | W   | 0.788      | 0.143        | 0.002 (0.000)    | 0.022 (0.002)    | 0 (0.000) |    10.80 | Ace, arakyN, ghostxD, Marzil, Nox |
|           20 |     3749 | 2024-03-28 | Frag Theory     | W   | 0.783      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     4.93 | Ace, arakyN, ghostxD, Marzil, Nox |
|           19 |     3755 | 2024-03-28 | Marcos Gaming   | L   | 0.782      | -            | -                | -                | -         |   -11.02 | Ace, arakyN, ghostxD, Marzil, Nox |
|           18 |     3957 | 2024-03-23 | Gods Reign      | L   | 0.754      | -            | -                | -                | -         |    -5.01 | Ace, arakyN, ghostxD, Marzil, Nox |
|           17 |     5053 | 2024-03-04 | Gods Reign      | L   | 0.622      | -            | -                | -                | -         |    -4.44 | Ace, arakyN, ghostxD, Marzil, Nox |
|           16 |     5110 | 2024-03-03 | Marcos Gaming   | L   | 0.615      | -            | -                | -                | -         |    -9.26 | Ace, arakyN, ghostxD, Marzil, Nox |
|           15 |     5194 | 2024-03-02 | True Rippers    | W   | 0.610      | 0.143        | 0.025 (0.002)    | 0.241 (0.021)    | 0 (0.000) |    12.15 | Ace, arakyN, ghostxD, Marzil, Nox |
|           14 |     5208 | 2024-03-02 | Crescent        | W   | 0.609      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.49 | Ace, arakyN, ghostxD, Marzil, Nox |
|           13 |     5469 | 2024-02-25 | Gods Reign      | L   | 0.568      | -            | -                | -                | -         |    -3.99 | Ace, arakyN, ghostxD, Marzil, Nox |
|           12 |     5471 | 2024-02-24 | Carnival Gaming | W   | 0.568      | 0.262        | 0.002 (0.000)    | 0.022 (0.003)    | 0 (0.000) |     7.72 | Ace, arakyN, ghostxD, Marzil, Nox |
|           11 |     6120 | 2024-02-14 | TyPuCTbl        | L   | 0.496      | -            | -                | -                | -         |    -9.11 | arakyN, Marzil, Nox, SeeK, SH4DY  |
|           10 |     6223 | 2024-02-12 | DEWA United     | L   | 0.481      | -            | -                | -                | -         |    -6.69 | Ace, arakyN, Marzil, Nox, SeeK    |
|            9 |     6316 | 2024-02-09 | Enigma Gaming   | W   | 0.461      | 0.303        | 0.004 (0.001)    | 0.035 (0.005)    | 0 (0.000) |     7.16 | Ace, arakyN, Marzil, Nox, SeeK    |
|            8 |     6388 | 2024-02-06 | dreamScape      | L   | 0.443      | -            | -                | -                | -         |    -7.88 | Ace, arakyN, Marzil, Nox, SeeK    |
|            7 |     6442 | 2024-02-05 | Drippy Lab      | W   | 0.435      | 0.303        | -                | 0.017 (0.002)    | 0 (0.000) |     2.34 | Ace, arakyN, Marzil, Nox, SeeK    |
|            6 |     6482 | 2024-02-03 | Team NKT        | L   | 0.428      | -            | -                | -                | -         |    -5.51 | Ace, arakyN, Marzil, Nox, SeeK    |
|            5 |     6573 | 2024-02-03 | SR Nacague      | W   | 0.422      | 0.303        | -                | 0.013 (0.002)    | -         |     2.23 | Ace, arakyN, Marzil, Nox, SeeK    |
|            4 |     7050 | 2024-01-26 | Enigma Gaming   | W   | 0.370      | 0.143        | 0.004 (0.000)    | 0.035 (0.002)    | -         |     6.17 | Ace, arakyN, Marzil, Nox, SeeK    |
|            3 |     7135 | 2024-01-24 | Local Esports   | W   | 0.356      | -            | -                | -                | -         |     2.00 | Ace, arakyN, Marzil, Nox, SeeK    |
|            2 |     7290 | 2024-01-21 | True Rippers    | L   | 0.335      | -            | -                | -                | -         |    -3.95 | Ace, arakyN, Marzil, Nox, SeeK    |
|            1 |     7296 | 2024-01-20 | Frag Theory     | W   | 0.334      | -            | -                | -                | -         |     1.86 | Ace, arakyN, Marzil, Nox, SeeK    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,269.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-06 |      0.844 | $600.00        | $506.17         |
| 2024-03-31 |      0.805 | $250.00        | $201.15         |
| 2024-02-25 |      0.568 | $500.00        | $284.03         |
| 2024-01-26 |      0.370 | $300.82        | $111.22         |
| 2024-01-21 |      0.335 | $500.00        | $167.41         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
