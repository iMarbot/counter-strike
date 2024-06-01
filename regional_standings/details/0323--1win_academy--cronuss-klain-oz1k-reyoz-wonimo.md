### Roster Details<br />
Team Name: 1win Academy<br />
Roster: cronuss, klain, oz1k, reyoz, wonimo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [323](../standings_global.md)<br />
Regional Rank: [196]( ../standings_europe.md)<br />
Final Rank Value:  625.8<br />
<br />
Final Rank Value (625.8) = Starting Rank Value (610.2) + Head To Head Adjustments (15.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.2
- 400 + ( ( 0.103 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 610.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |       76 | 2024-05-29 | V1dar Gaming        | L   | 1.000      | -            | -                | -                | -         |    -7.50 | cronuss, klain, oz1k, reyoz, wonimo    |
|           13 |      564 | 2024-05-21 | TOR                 | L   | 1.000      | -            | -                | -                | -         |    -7.91 | cronuss, klain, oz1k, reyoz, wonimo    |
|           12 |      968 | 2024-05-17 | Team PeeP           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.247 (0.035)    | 0 (0.000) |    12.78 | cronuss, klain, oz1k, reyoz, wonimo    |
|           11 |      987 | 2024-05-17 | VaselineWorms       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.424 (0.061)    | 0 (0.000) |    19.93 | cronuss, klain, oz1k, reyoz, wonimo    |
|           10 |     5006 | 2024-03-04 | Team Space          | L   | 0.625      | -            | -                | -                | -         |    -4.64 | 7tetsu, cronuss, klain, spiker, wonimo |
|            9 |     7994 | 2024-01-10 | V1dar Gaming        | L   | 0.265      | -            | -                | -                | -         |    -3.97 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            8 |     8008 | 2024-01-10 | DOM TOWAROWY        | W   | 0.265      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.92 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            7 |     8443 | 2023-12-17 | cs2Ctonjeu          | W   | 0.105      | 0.284        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.61 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            6 |     8482 | 2023-12-17 | VP.Prodigy          | L   | 0.103      | -            | -                | -                | -         |    -0.71 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            5 |     8507 | 2023-12-17 | ex-FLuffy Gangsters | W   | 0.102      | 0.143        | 0.000 (0.000)    | 0.093 (0.001)    | 0 (0.000) |     1.15 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            4 |     8573 | 2023-12-16 | DUSTY               | W   | 0.098      | 0.284        | 0.006 (0.000)    | 0.148 (0.004)    | 0 (0.000) |     2.07 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            3 |     8646 | 2023-12-16 | ARCRED              | L   | 0.095      | -            | -                | -                | -         |    -0.85 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            2 |     8783 | 2023-12-14 | HEYDERS             | W   | 0.085      | 0.284        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.21 | cronuss, klain, oz1k, sstr1ct, wonimo  |
|            1 |     8823 | 2023-12-13 | venom               | W   | 0.078      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.58 | cronuss, klain, oz1k, sstr1ct, wonimo  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
