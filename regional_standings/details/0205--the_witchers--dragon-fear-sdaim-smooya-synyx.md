### Roster Details<br />
Team Name: The Witchers<br />
Roster: Dragon, fear, Sdaim, smooya, synyx<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [205](../standings_global.md)<br />
Regional Rank: [138]( ../standings_europe.md)<br />
Final Rank Value:  719.3<br />
<br />
Final Rank Value (719.3) = Starting Rank Value (708.2) + Head To Head Adjustments (11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.2
- 400 + ( ( 0.152 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 708.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     7870 | 2024-01-16 | EYEBALLERS             | L   | 0.305      | -            | -                | -                | -         |    -2.36 | Dragon, fear, Sdaim, smooya, synyx  |
|           24 |     7879 | 2024-01-16 | Linx Legacy Madagaskar | W   | 0.305      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     2.31 | Dragon, fear, Sdaim, smooya, synyx  |
|           23 |     7887 | 2024-01-16 | Phantom Troupe         | W   | 0.305      | 0.143        | 0.000 (0.000)    | 0.094 (0.004)    | 0 (0.000) |     2.31 | Dragon, fear, Sdaim, smooya, synyx  |
|           22 |     7918 | 2024-01-16 | L&G                    | W   | 0.304      | 0.143        | 0.000 (0.000)    | 0.029 (0.001)    | 0 (0.000) |     2.50 | Dragon, fear, Sdaim, smooya, synyx  |
|           21 |     8088 | 2024-01-12 | Gaimin Gladiators      | L   | 0.278      | -            | -                | -                | -         |    -0.36 | Dragon, fear, Sdaim, smooya, synyx  |
|           20 |     8105 | 2024-01-12 | Viperio                | W   | 0.278      | 0.143        | -                | 0.219 (0.009)    | 0 (0.000) |     2.87 | Dragon, fear, Sdaim, smooya, synyx  |
|           19 |     8279 | 2024-01-10 | IKLA                   | L   | 0.265      | -            | -                | -                | -         |    -5.82 | Dragon, fear, Sdaim, smooya, synyx  |
|           18 |     8372 | 2024-01-09 | Entropiq               | L   | 0.257      | -            | -                | -                | -         |    -4.88 | Dragon, fear, Sdaim, smooya, synyx  |
|           17 |     8555 | 2023-12-30 | Metizport              | W   | 0.190      | 0.371        | 0.088 (0.006)    | 0.698 (0.049)    | 0 (0.000) |     4.84 | Dragon, fear, Sdaim, smooya, synyx  |
|           16 |     8556 | 2023-12-30 | Alliance               | W   | 0.189      | 0.371        | 0.004 (0.000)    | 0.529 (0.037)    | 0 (0.000) |     4.25 | Dragon, fear, Sdaim, smooya, synyx  |
|           15 |     8569 | 2023-12-28 | Aurora Young Blud      | W   | 0.177      | 0.371        | 0.008 (0.001)    | 0.506 (0.033)    | 0 (0.000) |     3.47 | Dragon, fear, Sdaim, smooya, synyx  |
|           14 |     8573 | 2023-12-27 | esmagaB                | W   | 0.171      | 0.371        | 0.008 (0.001)    | 0.564 (0.036)    | 0 (0.000) |     3.77 | Dragon, fear, Sdaim, smooya, synyx  |
|           13 |     8680 | 2023-12-18 | NOM Esports            | L   | 0.108      | -            | -                | -                | -         |    -2.02 | Dragon, fear, Sdaim, smooya, synyx  |
|           12 |     8839 | 2023-12-16 | INGLORIOUS             | L   | 0.098      | -            | -                | -                | -         |    -1.37 | bevve, fear, Sdaim, smooya, synyx   |
|           11 |     8847 | 2023-12-16 | Sashi Esport           | W   | 0.098      | 0.294        | -                | 0.091 (0.003)    | 0 (0.000) |     0.92 | bevve, fear, Sdaim, smooya, synyx   |
|           10 |     8894 | 2023-12-16 | Team Spirit Academy    | L   | 0.096      | -            | -                | -                | -         |    -1.41 | Dragon, fear, Sdaim, smooya, synyx  |
|            9 |     9058 | 2023-12-14 | Zero Tenacity          | W   | 0.082      | 0.333        | 0.147 (0.004)    | 1.000 (0.027)    | 0 (0.000) |     2.31 | Dragon, fear, Sdaim, smooya, synyx  |
|            8 |     9153 | 2023-12-12 | brazylijski luz        | W   | 0.070      | 0.333        | 0.013 (0.000)    | 0.514 (0.012)    | -         |     1.41 | Dragon, fear, Sdaim, smooya, synyx  |
|            7 |     9249 | 2023-12-10 | Passion UA             | L   | 0.056      | -            | -                | -                | -         |    -0.25 | fear, Sdaim, smooya, soulfly, synyx |
|            6 |     9371 | 2023-12-08 | Sashi Esport           | L   | 0.044      | -            | -                | -                | -         |    -0.16 | Dragon, fear, Sdaim, smooya, synyx  |
|            5 |     9503 | 2023-12-06 | ALTERNATE aTTaX        | L   | 0.031      | -            | -                | -                | -         |    -0.14 | fear, Sdaim, smooya, soulfly, synyx |
|            4 |     9527 | 2023-12-06 | detoks                 | L   | 0.028      | -            | -                | -                | -         |    -0.68 | fear, Sdaim, smooya, soulfly, synyx |
|            3 |     9583 | 2023-12-05 | RUSH B                 | L   | 0.024      | -            | -                | -                | -         |    -0.32 | fear, Sdaim, smooya, soulfly, synyx |
|            2 |     9625 | 2023-12-04 | Endpoint               | L   | 0.016      | -            | -                | -                | -         |    -0.10 | fear, Sdaim, smooya, soulfly, synyx |
|            1 |     9795 | 2023-12-02 | M1X                    | W   | 0.002      | 0.303        | 0.000 (0.000)    | -                | -         |     0.02 | fear, Sdaim, smooya, soulfly, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,850.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
