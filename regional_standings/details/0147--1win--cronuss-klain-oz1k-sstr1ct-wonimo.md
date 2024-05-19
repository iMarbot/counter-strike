### Roster Details<br />
Team Name: 1win<br />
Roster: cronuss, klain, oz1k, sstr1ct, wonimo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [147](../standings_global.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
Final Rank Value:  775.3<br />
<br />
Final Rank Value (775.3) = Starting Rank Value (732.7) + Head To Head Adjustments (42.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.264[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.7
- 400 + ( ( 0.168 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 732.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2423 | 2024-03-11 | Insilio                     | L   | 0.831      | -            | -                | -                | -             |    -6.38 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           20 |     2463 | 2024-03-10 | VP.Prodigy                  | W   | 0.824      | 0.371        | 0.029 (0.009)    | 0.762 (0.233)    | false (0.000) |    16.10 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           19 |     2677 | 2024-03-05 | ARCRED                      | L   | 0.792      | -            | -                | -                | -             |   -10.47 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           18 |     2738 | 2024-03-04 | Team Space                  | L   | 0.786      | -            | -                | -                | -             |   -14.05 | 7tetsu, cronuss, klain, spiker, wonimo     |
|           17 |     2883 | 2024-03-02 | CYBERSHOKE Esports          | W   | 0.771      | 0.371        | 0.004 (0.001)    | 0.220 (0.063)    | false (0.000) |    11.03 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           16 |     2945 | 2024-02-29 | BLESSED (Ukrainian team)    | L   | 0.759      | -            | -                | -                | -             |    -9.85 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           15 |     2987 | 2024-02-28 | UNiTY esports (Slovak team) | W   | 0.752      | 0.371        | 0.055 (0.015)    | 0.727 (0.203)    | false (0.000) |    14.60 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           14 |     3104 | 2024-02-25 | VaselineWorms               | W   | 0.731      | 0.371        | 0.001 (0.000)    | 0.164 (0.045)    | false (0.000) |     7.82 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           13 |     3296 | 2024-02-21 | Golden Sword                | W   | 0.705      | 0.371        | 0.000 (0.000)    | -                | false (0.000) |     2.41 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           12 |     3400 | 2024-02-19 | ALTERNATE aTTaX             | W   | 0.692      | 0.371        | 0.110 (0.028)    | 0.723 (0.186)    | false (0.000) |    17.33 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           11 |     3573 | 2024-02-15 | Copenhagen Wolves           | W   | 0.666      | 0.371        | 0.000 (0.000)    | 0.417 (0.103)    | false (0.000) |     7.15 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|           10 |     3582 | 2024-02-15 | Lemondogs                   | W   | 0.665      | 0.371        | 0.000 (0.000)    | 0.252 (0.062)    | false (0.000) |     6.06 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            9 |     3676 | 2024-02-13 | V1dar Gaming                | W   | 0.652      | 0.371        | -                | 0.345 (0.084)    | false (0.000) |     7.29 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            8 |     3680 | 2024-02-13 | Nemiga Gaming               | L   | 0.651      | -            | -                | -                | -             |    -0.67 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            7 |     5037 | 2024-01-10 | V1dar Gaming                | L   | 0.426      | -            | -                | -                | -             |    -9.31 | 1mpala, 4X1s, Alv, lom1k, torox            |
|            6 |     5048 | 2024-01-10 | DOM TOWAROWY                | W   | 0.426      | -            | -                | -                | false (0.000) |     1.78 | bonjorno, michat, misho, moonwalk, stussyy |
|            5 |     5377 | 2023-12-17 | VP.Prodigy                  | L   | 0.264      | -            | -                | -                | -             |    -3.02 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            4 |     5446 | 2023-12-16 | DUSTY                       | W   | 0.259      | 0.284        | 0.015 (0.001)    | 0.233 (0.017)    | -             |     4.63 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            3 |     5502 | 2023-12-16 | ARCRED                      | L   | 0.256      | -            | -                | -                | -             |    -2.90 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            2 |     5610 | 2023-12-14 | HEYDERS                     | W   | 0.246      | 0.284        | 0.000 (0.000)    | 0.017 (0.001)    | -             |     2.54 | cronuss, klain, oz1k, sstr1ct, wonimo      |
|            1 |     6439 | 2023-11-25 | Team QUAZAR                 | W   | 0.117      | -            | -                | -                | -             |     0.50 | cronuss, klain, oz1k, sstr1ct, wonimo      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($258.98)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
