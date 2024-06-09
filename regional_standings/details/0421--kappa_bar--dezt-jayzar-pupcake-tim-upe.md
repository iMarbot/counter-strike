### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: dezt, jayzaR, pupcake, TIM, upE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [421](../standings_global.md)<br />
Regional Rank: [253]( ../standings_europe.md)<br />
Final Rank Value:  539.1<br />
<br />
Final Rank Value (539.1) = Starting Rank Value (526.5) + Head To Head Adjustments (12.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.5
- 400 + ( ( 0.062 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 526.5


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
|           27 |     5386 | 2024-03-01 | BAKS Esports         | W   | 0.603      | 0.371        | 0.001 (0.000)    | 0.171 (0.038)    | 0 (0.000) |    11.41 | dezt, jayzaR, pupcake, TIM, upE           |
|           26 |     5412 | 2024-02-29 | AVEZ                 | L   | 0.598      | -            | -                | -                | -         |    -2.80 | dezt, jayzaR, pupcake, TIM, upE           |
|           25 |     5570 | 2024-02-26 | ALTERNATE aTTaX Evo  | W   | 0.578      | 0.289        | 0.002 (0.000)    | 0.239 (0.040)    | 0 (0.000) |    13.37 | dezt, jayzaR, pupcake, TIM, upE           |
|           24 |     5807 | 2024-02-22 | FAVBET Team          | L   | 0.551      | -            | -                | -                | -         |    -2.86 | dezt, jayzaR, pupcake, TIM, upE           |
|           23 |     5927 | 2024-02-20 | CYBERSHOKE Esports   | L   | 0.537      | -            | -                | -                | -         |    -6.45 | dezt, jayzaR, pupcake, TIM, upE           |
|           22 |     5989 | 2024-02-19 | ex-Hot Headed Gaming | L   | 0.531      | -            | -                | -                | -         |    -8.91 | dezt, jayzaR, pupcake, TIM, upE           |
|           21 |     6331 | 2024-02-13 | RUBY                 | L   | 0.491      | -            | -                | -                | -         |    -1.47 | dezt, jayzaR, pupcake, TIM, upE           |
|           20 |     6486 | 2024-02-09 | GamerLegion Academy  | W   | 0.464      | 0.371        | 0.018 (0.003)    | 0.691 (0.119)    | 0 (0.000) |    12.15 | dezt, jayzaR, pupcake, TIM, upE           |
|           19 |     6623 | 2024-02-05 | Nemiga Gaming        | L   | 0.437      | -            | -                | -                | -         |    -0.25 | dezt, jayzaR, pupcake, TIM, upE           |
|           18 |     6741 | 2024-02-03 | Sashi Esport         | L   | 0.424      | -            | -                | -                | -         |    -0.67 | dezt, jayzaR, pupcake, TIM, upE           |
|           17 |     6872 | 2024-02-01 | Gaimin Gladiators    | L   | 0.411      | -            | -                | -                | -         |    -0.20 | dezt, jayzaR, pupcake, TIM, upE           |
|           16 |     6911 | 2024-01-31 | Passion UA           | L   | 0.404      | -            | -                | -                | -         |    -0.82 | dezt, jayzaR, pupcake, TIM, upE           |
|           15 |     6930 | 2024-01-31 | ALTERNATE aTTaX      | L   | 0.404      | -            | -                | -                | -         |    -0.89 | dezt, jayzaR, pupcake, TIM, upE           |
|           14 |     6964 | 2024-01-30 | LODIS                | W   | 0.398      | 0.371        | 0.001 (0.000)    | 0.140 (0.021)    | 0 (0.000) |     8.39 | dezt, jayzaR, pupcake, TIM, upE           |
|           13 |     7339 | 2024-01-24 | esmagaB              | L   | 0.358      | -            | -                | -                | -         |    -1.45 | dezt, jayzaR, pupcake, TIM, upE           |
|           12 |     8114 | 2024-01-12 | Insilio              | L   | 0.278      | -            | -                | -                | -         |    -0.96 | dezt, jayzaR, pupcake, TIM, upE           |
|           11 |     8260 | 2024-01-10 | XI Esport            | L   | 0.265      | -            | -                | -                | -         |    -2.42 | dezt, jayzaR, pupcake, TIM, upE           |
|           10 |     8518 | 2024-01-03 | Begrip Gaming        | L   | 0.217      | -            | -                | -                | -         |    -2.62 | dezt, jayzaR, pupcake, TIM, upE           |
|            9 |     8752 | 2023-12-17 | angelnumbers         | L   | 0.102      | -            | -                | -                | -         |    -1.11 | JiBe, nomiss, Twinkey, VIRREE, zen        |
|            8 |     9059 | 2023-12-14 | Astralis Talent      | L   | 0.082      | -            | -                | -                | -         |    -0.26 | ANSG1, JBOEN, kiR, kroK, tOPZ             |
|            7 |     9079 | 2023-12-13 | showmakerz           | L   | 0.078      | -            | -                | -                | -         |    -1.18 | agoz, bsover, Doobs, julle, Leon1das      |
|            6 |     9091 | 2023-12-13 | Lilmix               | W   | 0.078      | 0.143        | 0.000 (0.000)    | 0.044 (0.000)    | 0 (0.000) |     1.32 | dezt, jayzaR, pupcake, TIM, upE           |
|            5 |     9104 | 2023-12-13 | Homegrown            | W   | 0.077      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.80 | Gibsand, kurtaliz, meinz, wiking, z1egers |
|            4 |     9158 | 2023-12-12 | detoks               | L   | 0.068      | -            | -                | -                | -         |    -1.16 | dezt, jayzaR, pupcake, TIM, upE           |
|            3 |     9201 | 2023-12-11 | Sashi Esport         | W   | 0.063      | 0.303        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     1.12 | dezt, jayzaR, pupcake, TIM, upE           |
|            2 |     9307 | 2023-12-09 | Lilmix               | W   | 0.049      | 0.303        | 0.000 (0.000)    | 0.044 (0.001)    | 0 (0.000) |     0.84 | jayzaR, pupcake, TIM, tvs, upE            |
|            1 |     9593 | 2023-12-05 | Sashi Esport         | L   | 0.022      | -            | -                | -                | -         |    -0.30 | jayzaR, pupcake, TIM, tvs, upE            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
