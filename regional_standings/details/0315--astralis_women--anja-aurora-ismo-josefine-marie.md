### Roster Details<br />
Team Name: Astralis Women<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [315](../standings_global.md)<br />
Regional Rank: [192]( ../standings_europe.md)<br />
Final Rank Value:  595.2<br />
<br />
Final Rank Value (595.2) = Starting Rank Value (674.2) + Head To Head Adjustments (-79.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.056[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 674.2
- 400 + ( ( 0.138 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 674.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      814 | 2024-04-19 | ENCE Athena                | L   | 1.000      | -            | -                | -                | -             |   -11.38 | anja, aurora, Ismo, josefine, marie       |
|           20 |     1070 | 2024-04-14 | NAVI Javelins              | L   | 1.000      | -            | -                | -                | -             |    -6.58 | anja, aurora, Ismo, josefine, marie       |
|           19 |     1102 | 2024-04-13 | NIP Impact                 | L   | 1.000      | -            | -                | -                | -             |    -9.34 | anja, aurora, Ismo, josefine, marie       |
|           18 |     1144 | 2024-04-12 | Permitta W                 | W   | 1.000      | 0.303        | 0.000 (0.000)    | 0.070 (0.021)    | false (0.000) |    11.20 | anja, aurora, Ismo, josefine, marie       |
|           17 |     1167 | 2024-04-11 | Team Pigeons               | L   | 1.000      | -            | -                | -                | -             |    -4.54 | anja, aurora, Ismo, josefine, marie       |
|           16 |     1224 | 2024-04-10 | Team Pigeons               | L   | 1.000      | -            | -                | -                | -             |    -4.74 | anja, aurora, Ismo, josefine, marie       |
|           15 |     1328 | 2024-04-08 | Permitta W                 | W   | 1.000      | 0.303        | 0.000 (0.000)    | 0.070 (0.021)    | false (0.000) |    10.78 | anja, aurora, Ismo, josefine, marie       |
|           14 |     1532 | 2024-04-03 | NIP Impact                 | L   | 0.985      | -            | -                | -                | -             |   -11.04 | anja, aurora, Ismo, josefine, marie       |
|           13 |     1977 | 2024-03-21 | Guild Esports              | L   | 0.899      | -            | -                | -                | -             |   -10.49 | anja, aurora, Ismo, josefine, marie       |
|           12 |     2609 | 2024-03-06 | BIG EQUIPA                 | L   | 0.799      | -            | -                | -                | -             |    -8.81 | anja, aurora, Ismo, josefine, marie       |
|           11 |     3154 | 2024-02-24 | 1win Gang                  | L   | 0.725      | -            | -                | -                | -             |   -11.25 | anja, aurora, Ismo, josefine, marie       |
|           10 |     3179 | 2024-02-24 | Nemesis (Female team)      | L   | 0.723      | -            | -                | -                | -             |   -16.48 | anja, aurora, Ismo, josefine, marie       |
|            9 |     3439 | 2024-02-18 | FORZE Ladies               | W   | 0.686      | 0.143        | 0.002 (0.000)    | 0.057 (0.006)    | false (0.000) |    10.32 | anja, aurora, Ismo, josefine, marie       |
|            8 |     3446 | 2024-02-18 | Team Spirit Female         | L   | 0.685      | -            | -                | -                | -             |    -9.73 | anja, aurora, Ismo, josefine, marie       |
|            7 |     3485 | 2024-02-17 | 5bites                     | W   | 0.679      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.93 | anja, aurora, Ismo, josefine, marie       |
|            6 |     3625 | 2024-02-14 | Guild Esports              | L   | 0.658      | -            | -                | -                | -             |    -9.02 | anja, aurora, Ismo, josefine, marie       |
|            5 |     6048 | 2023-12-03 | Team Finland (Female team) | L   | 0.171      | -            | -                | -                | -             |    -2.70 | amyb, miLo, oona, Siljeeeh, Waldee        |
|            4 |     6059 | 2023-12-03 | Team Sweden (Female team)  | W   | 0.170      | 0.143        | 0.000 (0.000)    | 0.017 (0.000)    | true (0.170)  |     1.56 | anja, aurora, Ismo, josefine, marie       |
|            3 |     6063 | 2023-12-03 | Team Norway (Female team)  | W   | 0.169      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | true (0.169)  |     0.98 | anja, aurora, Ismo, josefine, marie       |
|            2 |     6124 | 2023-12-02 | Team Iceland (Female team) | W   | 0.164      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | true (0.164)  |     0.92 | Eneka, Jazzycakes, nutellaalb, S1u, tania |
|            1 |     6135 | 2023-12-02 | Team Finland (Female team) | L   | 0.163      | -            | -                | -                | -             |    -2.58 | anja, aurora, Ismo, josefine, marie       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,095.18)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $850.00        | $850.00         |
| 2023-12-03 |      0.171 | $1,437.91      | $245.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
