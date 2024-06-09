### Roster Details<br />
Team Name: Team Solid<br />
Roster: ALLE, destiny, gbb, Lcm, xureba<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [101](../standings_global.md)<br />
Regional Rank: [22]( ../standings_americas.md)<br />
Final Rank Value:  868.0<br />
<br />
Final Rank Value (868.0) = Starting Rank Value (876.6) + Head To Head Adjustments (-8.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.234<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.6
- 400 + ( ( 0.234 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 876.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |      136 | 2024-05-28 | 9z Academy                | W   | 1.000      | 0.384        | -                | 0.311 (0.120)    | 0 (0.000) |     6.88 | ALLE, destiny, gbb, Lcm, xureba |
|           58 |      445 | 2024-05-22 | w7m esports               | W   | 1.000      | 0.450        | 0.003 (0.001)    | 0.274 (0.123)    | 0 (0.000) |     9.88 | ALLE, destiny, gbb, Lcm, xureba |
|           57 |      449 | 2024-05-22 | w7m esports               | W   | 1.000      | 0.450        | 0.003 (0.001)    | 0.274 (0.123)    | 0 (0.000) |    10.68 | ALLE, destiny, gbb, Lcm, xureba |
|           56 |      746 | 2024-05-19 | Galorys                   | L   | 1.000      | -            | -                | -                | -         |   -15.63 | ALLE, destiny, gbb, Lcm, xureba |
|           55 |      840 | 2024-05-18 | Case Esports              | L   | 1.000      | -            | -                | -                | -         |   -15.09 | ALLE, destiny, gbb, Lcm, xureba |
|           54 |     1067 | 2024-05-16 | ODDIK                     | W   | 1.000      | 0.303        | 0.017 (0.005)    | 0.494 (0.150)    | 0 (0.000) |    17.64 | ALLE, destiny, gbb, Lcm, xureba |
|           53 |     1146 | 2024-05-15 | KRÜ Esports               | L   | 1.000      | -            | -                | -                | -         |   -16.15 | ALLE, destiny, gbb, Lcm, xureba |
|           52 |     1246 | 2024-05-14 | FURIA Academy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | ALLE, destiny, gbb, Lcm, xureba |
|           51 |     1311 | 2024-05-13 | ODDIK                     | L   | 1.000      | -            | -                | -                | -         |   -12.72 | ALLE, destiny, gbb, Lcm, xureba |
|           50 |     1500 | 2024-05-10 | KRÜ Esports               | L   | 1.000      | -            | -                | -                | -         |   -16.43 | ALLE, destiny, gbb, Lcm, xureba |
|           49 |     1618 | 2024-05-08 | RED Canids                | W   | 1.000      | 0.435        | 0.076 (0.033)    | 0.536 (0.233)    | 0 (0.000) |    22.50 | ALLE, destiny, gbb, Lcm, xureba |
|           48 |     1725 | 2024-05-06 | Yawara E-Sports           | W   | 1.000      | 0.435        | -                | 0.319 (0.139)    | 0 (0.000) |     7.70 | ALLE, destiny, gbb, Lcm, xureba |
|           47 |     2868 | 2024-04-17 | Fluxo                     | L   | 0.918      | -            | -                | -                | -         |    -7.13 | ALLE, CSO, gbb, Lcm, xureba     |
|           46 |     2955 | 2024-04-16 | paiN Gaming Academy       | W   | 0.912      | -            | -                | -                | 0 (0.000) |     8.56 | ALLE, CSO, gbb, Lcm, xureba     |
|           45 |     3148 | 2024-04-12 | ODDIK                     | L   | 0.883      | -            | -                | -                | -         |   -12.73 | ALLE, CSO, gbb, Lcm, xureba     |
|           44 |     3379 | 2024-04-08 | LA RUGONETA               | W   | 0.856      | -            | -                | -                | 0 (0.000) |     4.24 | ALLE, CSO, gbb, Lcm, xureba     |
|           43 |     3450 | 2024-04-06 | Fluxo                     | L   | 0.844      | -            | -                | -                | -         |    -7.30 | ALLE, CSO, gbb, Lcm, xureba     |
|           42 |     4528 | 2024-03-14 | RED Canids                | W   | 0.691      | 0.435        | 0.076 (0.023)    | 0.536 (0.161)    | 0 (0.000) |    15.26 | bnc, CSO, gbb, Lcm, xureba      |
|           41 |     4609 | 2024-03-13 | Fluxo                     | W   | 0.684      | 0.435        | 0.065 (0.019)    | 0.474 (0.141)    | -         |    15.74 | bnc, CSO, gbb, Lcm, xureba      |
|           40 |     4664 | 2024-03-12 | adalYamigos               | W   | 0.679      | -            | -                | -                | -         |     7.93 | bnc, CSO, gbb, Lcm, xureba      |
|           39 |     4673 | 2024-03-12 | FURIA Academy             | L   | 0.677      | -            | -                | -                | -         |   -17.40 | bnc, CSO, gbb, Lcm, xureba      |
|           38 |     4731 | 2024-03-11 | w7m esports               | W   | 0.671      | -            | -                | -                | -         |     9.84 | bnc, CSO, gbb, Lcm, xureba      |
|           37 |     4781 | 2024-03-10 | ODDIK                     | L   | 0.664      | -            | -                | -                | -         |    -8.32 | bnc, CSO, gbb, Lcm, xureba      |
|           36 |     4831 | 2024-03-09 | VELOX Argentina           | W   | 0.657      | -            | -                | -                | -         |     3.53 | bnc, CSO, gbb, Lcm, xureba      |
|           35 |     4944 | 2024-03-07 | w7m esports               | L   | 0.644      | -            | -                | -                | -         |   -11.05 | bnc, CSO, gbb, Lcm, xureba      |
|           34 |     4971 | 2024-03-06 | Fluxo                     | W   | 0.639      | 0.450        | 0.065 (0.019)    | 0.474 (0.136)    | -         |    14.65 | bnc, CSO, gbb, Lcm, xureba      |
|           33 |     4972 | 2024-03-06 | Fluxo                     | L   | 0.639      | -            | -                | -                | -         |    -5.44 | bnc, CSO, gbb, Lcm, xureba      |
|           32 |     5083 | 2024-03-05 | Sharks Esports            | L   | 0.631      | -            | -                | -                | -         |    -7.77 | bnc, CSO, gbb, Lcm, xureba      |
|           31 |     5093 | 2024-03-05 | Sharks Esports            | L   | 0.631      | -            | -                | -                | -         |    -8.19 | bnc, CSO, gbb, Lcm, xureba      |
|           30 |     5836 | 2024-02-21 | Case Esports              | L   | 0.546      | -            | -                | -                | -         |    -8.73 | bnc, CSO, gbb, Lcm, xureba      |
|           29 |     5845 | 2024-02-21 | Case Esports              | W   | 0.546      | 0.450        | 0.028 (0.007)    | 0.470 (0.116)    | -         |     8.65 | bnc, CSO, gbb, Lcm, xureba      |
|           28 |     5865 | 2024-02-21 | Fluxo                     | L   | 0.544      | -            | -                | -                | -         |    -5.93 | bnc, CSO, gbb, Lcm, xureba      |
|           27 |     5910 | 2024-02-20 | 9z Team                   | L   | 0.539      | -            | -                | -                | -         |    -1.89 | bnc, CSO, gbb, Lcm, xureba      |
|           26 |     5912 | 2024-02-20 | Flamengo Esports          | W   | 0.539      | -            | -                | -                | -         |     2.42 | bnc, CSO, gbb, Lcm, xureba      |
|           25 |     5917 | 2024-02-20 | Fluxo                     | W   | 0.538      | 0.143        | 0.065 (0.005)    | -                | -         |    11.39 | bnc, CSO, gbb, Lcm, xureba      |
|           24 |     5980 | 2024-02-19 | VELOX Argentina           | W   | 0.533      | -            | -                | -                | -         |     2.81 | bnc, CSO, gbb, Lcm, xureba      |
|           23 |     5999 | 2024-02-19 | Sharks Esports            | L   | 0.531      | -            | -                | -                | -         |    -7.50 | bnc, CSO, gbb, Lcm, xureba      |
|           22 |     6033 | 2024-02-18 | adalYamigos               | W   | 0.525      | -            | -                | -                | -         |     4.37 | bnc, CSO, gbb, Lcm, xureba      |
|           21 |     6200 | 2024-02-15 | Imperial Esports          | L   | 0.505      | -            | -                | -                | -         |    -0.40 | bnc, CSO, gbb, Lcm, xureba      |
|           20 |     6261 | 2024-02-14 | Galorys                   | W   | 0.499      | 0.143        | 0.022 (0.002)    | -                | -         |     6.99 | bnc, CSO, gbb, Lcm, xureba      |
|           19 |     8028 | 2024-01-13 | ODDIK                     | L   | 0.286      | -            | -                | -                | -         |    -3.55 | CSO, gbb, Lcm, nolkz, xureba    |
|           18 |     8184 | 2024-01-11 | KRÜ Esports               | L   | 0.271      | -            | -                | -                | -         |    -5.16 | CSO, gbb, Lcm, nolkz, xureba    |
|           17 |     8230 | 2024-01-10 | Os Guri da Net            | W   | 0.266      | -            | -                | -                | -         |     0.57 | CSO, gbb, Lcm, nolkz, xureba    |
|           16 |     8419 | 2024-01-08 | O Plano                   | L   | 0.253      | -            | -                | -                | -         |    -6.95 | CSO, gbb, Lcm, nolkz, xureba    |
|           15 |     8588 | 2023-12-23 | Case Esports              | L   | 0.143      | -            | -                | -                | -         |    -3.36 | CSO, gbb, Lcm, nolkz, xureba    |
|           14 |     8621 | 2023-12-21 | ODDIK                     | L   | 0.132      | -            | -                | -                | -         |    -1.73 | CSO, gbb, Lcm, nolkz, xureba    |
|           13 |     8635 | 2023-12-20 | Flamengo Esports          | W   | 0.125      | -            | -                | -                | -         |     0.47 | CSO, gbb, Lcm, nolkz, xureba    |
|           12 |     8666 | 2023-12-18 | ODDIK                     | W   | 0.112      | -            | -                | -                | -         |     2.07 | CSO, gbb, Lcm, nolkz, xureba    |
|           11 |     8689 | 2023-12-17 | Case Esports              | W   | 0.106      | -            | -                | -                | -         |     0.86 | CSO, gbb, Lcm, nolkz, xureba    |
|           10 |     8821 | 2023-12-16 | WINDINGO                  | L   | 0.098      | -            | -                | -                | -         |    -2.49 | CSO, gbb, Lcm, nolkz, xureba    |
|            9 |     9074 | 2023-12-13 | w7m esports               | L   | 0.079      | -            | -                | -                | -         |    -1.62 | CSO, gbb, Lcm, nolkz, xureba    |
|            8 |     9077 | 2023-12-13 | WINDINGO                  | W   | 0.078      | -            | -                | -                | -         |     0.48 | CSO, gbb, Lcm, nolkz, xureba    |
|            7 |     9142 | 2023-12-12 | Arena Jogue Fácil Esports | W   | 0.071      | -            | -                | -                | -         |     0.40 | CSO, gbb, Lcm, nolkz, xureba    |
|            6 |     9169 | 2023-12-11 | Meta Gaming               | W   | 0.065      | -            | -                | -                | -         |     0.20 | CSO, gbb, Lcm, nolkz, xureba    |
|            5 |     9276 | 2023-12-09 | unluckyyy                 | L   | 0.052      | -            | -                | -                | -         |    -1.45 | CSO, gbb, Lcm, nolkz, xureba    |
|            4 |     9359 | 2023-12-08 | inSanitY Sports           | W   | 0.045      | -            | -                | -                | -         |     0.15 | CSO, gbb, Lcm, nolkz, xureba    |
|            3 |     9478 | 2023-12-06 | Arena Jogue Fácil Esports | W   | 0.033      | -            | -                | -                | -         |     0.18 | CSO, gbb, Lcm, nolkz, xureba    |
|            2 |     9544 | 2023-12-05 | Case Esports              | W   | 0.025      | -            | -                | -                | -         |     0.20 | CSO, gbb, Lcm, nolkz, xureba    |
|            1 |     9715 | 2023-12-02 | Case Esports              | L   | 0.005      | -            | -                | -                | -         |    -0.12 | CSO, gbb, Lcm, nolkz, xureba    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,714.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,200.00      | $1,200.00       |
| 2024-03-14 |      0.691 | $25,000.00     | $17,284.72      |
| 2023-12-18 |      0.110 | $1,089.86      | $119.58         |
| 2023-12-17 |      0.106 | $1,000.00      | $105.69         |
| 2023-12-03 |      0.011 | $457.03        | $4.95           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
