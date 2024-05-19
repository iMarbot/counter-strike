### Roster Details<br />
Team Name: FORZE Youngsters<br />
Roster: boN11, kelieN, matusik, spirit, sstiNiX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [230](../standings_global.md)<br />
Regional Rank: [150]( ../standings_europe.md)<br />
Final Rank Value:  681.8<br />
<br />
Final Rank Value (681.8) = Starting Rank Value (684.4) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 684.4
- 400 + ( ( 0.143 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 684.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2494 | 2024-03-09 | ARCRED               | L   | 0.818      | -            | -                | -                | -         |    -7.99 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           18 |     2699 | 2024-03-05 | VP.Prodigy           | L   | 0.792      | -            | -                | -                | -         |    -6.76 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           17 |     2933 | 2024-02-29 | NOM Esports          | L   | 0.759      | -            | -                | -                | -         |   -12.63 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           16 |     3216 | 2024-02-23 | Insilio              | L   | 0.718      | -            | -                | -                | -         |    -4.33 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           15 |     3401 | 2024-02-19 | Aurora Young Blud    | W   | 0.692      | 0.371        | 0.017 (0.004)    | 0.422 (0.109)    | 0 (0.000) |    14.27 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           14 |     3407 | 2024-02-19 | Nemiga Gaming        | L   | 0.692      | -            | -                | -                | -         |    -0.68 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           13 |     3585 | 2024-02-15 | ILIN                 | L   | 0.665      | -            | -                | -                | -         |   -14.08 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           12 |     3672 | 2024-02-13 | Ex-Hot Headed Gaming | W   | 0.652      | 0.371        | 0.000 (0.000)    | 0.117 (0.028)    | 0 (0.000) |     4.86 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           11 |     3711 | 2024-02-12 | GODSENT              | W   | 0.646      | 0.371        | 0.026 (0.006)    | 0.423 (0.101)    | 0 (0.000) |    12.73 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           10 |     4257 | 2024-01-27 | Grindas              | W   | 0.539      | 0.371        | 0.002 (0.000)    | 0.332 (0.066)    | 0 (0.000) |     8.64 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            9 |     4471 | 2024-01-22 | Sashi Esport         | L   | 0.505      | -            | -                | -                | -         |    -1.95 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            8 |     5350 | 2023-12-17 | Kova Gaming          | W   | 0.266      | 0.310        | 0.002 (0.000)    | 0.009 (0.001)    | 0 (0.000) |     3.46 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            7 |     5374 | 2023-12-17 | Lewandownskie        | L   | 0.264      | -            | -                | -                | -         |    -4.34 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            6 |     5486 | 2023-12-16 | Insilio              | L   | 0.257      | -            | -                | -                | -         |    -1.75 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            5 |     5504 | 2023-12-16 | Griefers             | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.33 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            4 |     5577 | 2023-12-15 | Kova Gaming          | W   | 0.252      | 0.310        | 0.002 (0.000)    | 0.009 (0.001)    | 0 (0.000) |     3.27 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            3 |     5667 | 2023-12-12 | AKA HERO             | W   | 0.232      | 0.310        | 0.001 (0.000)    | 0.114 (0.008)    | 0 (0.000) |     2.97 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            2 |     5713 | 2023-12-10 | Desperados           | W   | 0.219      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.17 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            1 |     6701 | 2023-11-18 | Team Spirit Academy  | L   | 0.072      | -            | -                | -                | -         |    -0.77 | boN11, kelieN, matusik, spirit, sstiNiX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($531.02)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
