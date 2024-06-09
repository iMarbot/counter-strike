### Roster Details<br />
Team Name: Imperial Esports<br />
Roster: decenty, felps, HEN1, noway, VINI<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [21](../standings_global.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
Final Rank Value:  1369.8<br />
<br />
Final Rank Value (1369.8) = Starting Rank Value (1550.7) + Head To Head Adjustments (-180.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.700[<sup>1</sup>](#table2)
- Bounty Collected: 0.511[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 0.794[<sup>2</sup>](#table1)

The average of these factors is 0.566<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1550.7
- 400 + ( ( 0.566 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1550.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           88 |      443 | 2024-05-22 | 9z Team             | W   | 1.000      | 0.450        | 0.107 (0.048)    | 0.547 (0.246)    | -         |     9.01 | decenty, felps, HEN1, noway, VINI |
|           87 |      447 | 2024-05-22 | 9z Team             | W   | 1.000      | 0.450        | 0.107 (0.048)    | 0.547 (0.246)    | -         |     9.70 | decenty, felps, HEN1, noway, VINI |
|           86 |      461 | 2024-05-22 | Sharks Esports      | L   | 1.000      | -            | -                | -                | -         |   -28.33 | decenty, felps, HEN1, noway, VINI |
|           85 |      479 | 2024-05-22 | Sharks Esports      | W   | 1.000      | -            | -                | -                | -         |     2.81 | decenty, felps, HEN1, noway, VINI |
|           84 |      555 | 2024-05-21 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |   -28.54 | decenty, felps, HEN1, noway, VINI |
|           83 |      573 | 2024-05-21 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |   -29.30 | decenty, felps, HEN1, noway, VINI |
|           82 |     1073 | 2024-05-16 | 9z Team             | W   | 1.000      | 0.384        | -                | 0.547 (0.210)    | -         |     8.28 | decenty, felps, HEN1, noway, VINI |
|           81 |     1164 | 2024-05-15 | Fluxo               | W   | 1.000      | -            | -                | -                | -         |     4.87 | decenty, felps, HEN1, noway, VINI |
|           80 |     1234 | 2024-05-14 | w7m esports         | W   | 1.000      | -            | -                | -                | -         |     0.72 | decenty, felps, HEN1, noway, VINI |
|           79 |     1236 | 2024-05-14 | w7m esports         | W   | 1.000      | -            | -                | -                | -         |     0.73 | decenty, felps, HEN1, noway, VINI |
|           78 |     1247 | 2024-05-14 | BESTIA              | W   | 1.000      | -            | -                | -                | -         |     1.70 | decenty, felps, HEN1, noway, VINI |
|           77 |     1334 | 2024-05-13 | KRÜ Esports         | W   | 1.000      | -            | -                | -                | -         |     1.31 | decenty, felps, HEN1, noway, VINI |
|           76 |     1510 | 2024-05-10 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |   -29.98 | decenty, felps, HEN1, noway, VINI |
|           75 |     1678 | 2024-05-07 | ODDIK               | W   | 1.000      | 0.435        | -                | 0.494 (0.214)    | -         |     1.77 | decenty, felps, HEN1, noway, VINI |
|           74 |     1782 | 2024-05-05 | inSanitY Sports     | W   | 1.000      | -            | -                | -                | -         |     0.41 | decenty, felps, HEN1, noway, VINI |
|           73 |     2303 | 2024-04-26 | SAW                 | L   | 0.976      | -            | -                | -                | -         |   -19.26 | decenty, felps, HEN1, noway, VINI |
|           72 |     2412 | 2024-04-24 | Eternal Fire        | L   | 0.964      | -            | -                | -                | -         |    -4.13 | decenty, felps, HEN1, noway, VINI |
|           71 |     2458 | 2024-04-23 | FaZe Clan           | L   | 0.957      | -            | -                | -                | -         |    -1.77 | decenty, felps, HEN1, noway, VINI |
|           70 |     2601 | 2024-04-20 | paiN Gaming         | L   | 0.938      | -            | -                | -                | -         |   -11.72 | decenty, felps, HEN1, noway, VINI |
|           69 |     2714 | 2024-04-19 | paiN Gaming         | W   | 0.933      | 0.589        | 0.463 (0.255)    | 0.547 (0.300)    | 1 (0.933) |    17.36 | decenty, felps, HEN1, noway, VINI |
|           68 |     2733 | 2024-04-19 | paiN Gaming         | L   | 0.931      | -            | -                | -                | -         |   -11.34 | decenty, felps, HEN1, noway, VINI |
|           67 |     2792 | 2024-04-18 | MIBR                | L   | 0.926      | -            | -                | -                | -         |   -10.23 | decenty, felps, HEN1, noway, VINI |
|           66 |     2796 | 2024-04-18 | 9z Team             | W   | 0.926      | 0.589        | 0.107 (0.058)    | 0.547 (0.298)    | 1 (0.926) |     6.36 | decenty, felps, HEN1, noway, VINI |
|           65 |     2801 | 2024-04-18 | Fluxo               | W   | 0.925      | -            | -                | -                | -         |     2.79 | decenty, felps, HEN1, noway, VINI |
|           64 |     2812 | 2024-04-18 | Metizport           | W   | 0.924      | 0.589        | -                | 0.698 (0.379)    | 1 (0.924) |     2.72 | decenty, felps, HEN1, noway, VINI |
|           63 |     2998 | 2024-04-15 | MIBR                | L   | 0.904      | -            | -                | -                | -         |   -11.06 | decenty, felps, HEN1, noway, VINI |
|           62 |     3039 | 2024-04-14 | paiN Gaming         | W   | 0.897      | 0.435        | 0.463 (0.181)    | 0.547 (0.213)    | -         |    16.87 | decenty, felps, HEN1, noway, VINI |
|           61 |     3069 | 2024-04-13 | RED Canids          | W   | 0.892      | -            | -                | -                | -         |     2.29 | decenty, felps, HEN1, noway, VINI |
|           60 |     3168 | 2024-04-11 | adalYamigos         | W   | 0.879      | -            | -                | -                | -         |     0.53 | decenty, felps, HEN1, noway, VINI |
|           59 |     3186 | 2024-04-11 | paiN Gaming         | L   | 0.877      | -            | -                | -                | -         |   -10.41 | decenty, felps, HEN1, noway, VINI |
|           58 |     3222 | 2024-04-10 | Fluxo               | L   | 0.872      | -            | -                | -                | -         |   -25.12 | decenty, felps, HEN1, noway, VINI |
|           57 |     3223 | 2024-04-10 | Fluxo               | W   | 0.872      | -            | -                | -                | -         |     2.14 | decenty, felps, HEN1, noway, VINI |
|           56 |     3255 | 2024-04-10 | MIBR                | L   | 0.870      | -            | -                | -                | -         |   -12.69 | decenty, felps, HEN1, noway, VINI |
|           55 |     3325 | 2024-04-09 | paiN Gaming         | W   | 0.863      | 0.143        | 0.463 (0.057)    | -                | -         |    15.89 | decenty, felps, HEN1, noway, VINI |
|           54 |     3407 | 2024-04-07 | RED Canids          | W   | 0.852      | -            | -                | -                | -         |     1.79 | decenty, felps, HEN1, noway, VINI |
|           53 |     3411 | 2024-04-07 | FURIA Academy       | W   | 0.850      | -            | -                | -                | -         |     0.23 | decenty, felps, HEN1, noway, VINI |
|           52 |     3559 | 2024-04-04 | ODDIK               | W   | 0.832      | -            | -                | -                | -         |     1.09 | decenty, felps, HEN1, noway, VINI |
|           51 |     3562 | 2024-04-04 | ODDIK               | W   | 0.832      | -            | -                | -                | -         |     1.11 | decenty, felps, HEN1, noway, VINI |
|           50 |     3573 | 2024-04-04 | BESTIA              | W   | 0.831      | -            | -                | -                | -         |     1.09 | decenty, felps, HEN1, noway, VINI |
|           49 |     3616 | 2024-04-03 | Case Esports        | W   | 0.825      | -            | -                | -                | -         |     0.64 | decenty, felps, HEN1, noway, VINI |
|           48 |     3619 | 2024-04-03 | Case Esports        | W   | 0.825      | -            | -                | -                | -         |     0.64 | decenty, felps, HEN1, noway, VINI |
|           47 |     4107 | 2024-03-23 | FaZe Clan           | L   | 0.749      | -            | -                | -                | -         |    -1.64 | decenty, felps, HEN1, noway, VINI |
|           46 |     4140 | 2024-03-22 | Team Vitality       | L   | 0.743      | -            | -                | -                | -         |    -3.31 | decenty, felps, HEN1, noway, VINI |
|           45 |     4155 | 2024-03-21 | Team Spirit         | L   | 0.738      | -            | -                | -                | -         |    -1.94 | decenty, felps, HEN1, noway, VINI |
|           44 |     4197 | 2024-03-21 | Virtus.pro          | W   | 0.736      | 1.000        | 0.271 (0.199)    | 0.331 (0.244)    | 1 (0.736) |    17.91 | decenty, felps, HEN1, noway, VINI |
|           43 |     4240 | 2024-03-20 | GamerLegion         | W   | 0.730      | 1.000        | 0.075 (0.055)    | -                | 1 (0.730) |     5.13 | decenty, felps, HEN1, noway, VINI |
|           42 |     4273 | 2024-03-19 | Gaimin Gladiators   | L   | 0.724      | -            | -                | -                | -         |   -17.46 | decenty, felps, HEN1, noway, VINI |
|           41 |     4325 | 2024-03-18 | Apeks               | W   | 0.716      | 1.000        | 0.085 (0.061)    | 0.345 (0.247)    | 1 (0.716) |     4.73 | decenty, felps, HEN1, noway, VINI |
|           40 |     4355 | 2024-03-17 | HEROIC              | L   | 0.711      | -            | -                | -                | -         |    -4.96 | decenty, felps, HEN1, noway, VINI |
|           39 |     4390 | 2024-03-17 | ENCE                | W   | 0.710      | 1.000        | 0.202 (0.143)    | -                | 1 (0.710) |     9.83 | decenty, felps, HEN1, noway, VINI |
|           38 |     4914 | 2024-03-07 | Monte               | L   | 0.645      | -            | -                | -                | -         |   -15.13 | decenty, felps, HEN1, noway, VINI |
|           37 |     5224 | 2024-03-03 | paiN Gaming         | W   | 0.617      | -            | -                | -                | 1 (0.617) |    12.11 | decenty, felps, HEN1, noway, VINI |
|           36 |     5325 | 2024-03-02 | M80                 | W   | 0.611      | -            | -                | -                | 1 (0.611) |     4.36 | decenty, felps, HEN1, noway, VINI |
|           35 |     5367 | 2024-03-01 | NRG                 | W   | 0.605      | -            | -                | -                | 1 (0.605) |     0.61 | decenty, felps, HEN1, noway, VINI |
|           34 |     5598 | 2024-02-25 | Fluxo               | L   | 0.571      | -            | -                | -                | -         |   -16.90 | decenty, felps, HEN1, noway, VINI |
|           33 |     5691 | 2024-02-24 | BESTIA              | W   | 0.564      | -            | -                | -                | -         |     0.89 | decenty, felps, HEN1, noway, VINI |
|           32 |     5788 | 2024-02-22 | BESTIA              | L   | 0.552      | -            | -                | -                | -         |   -16.62 | decenty, felps, HEN1, noway, VINI |
|           31 |     5798 | 2024-02-22 | FURIA Esports       | L   | 0.551      | -            | -                | -                | -         |   -11.28 | decenty, felps, HEN1, noway, VINI |
|           30 |     5846 | 2024-02-21 | 2Game Esports       | W   | 0.546      | -            | -                | -                | -         |     0.16 | decenty, felps, HEN1, noway, VINI |
|           29 |     5849 | 2024-02-21 | 2Game Esports       | W   | 0.546      | -            | -                | -                | -         |     0.16 | decenty, felps, HEN1, noway, VINI |
|           28 |     5888 | 2024-02-21 | LA RUGONETA         | W   | 0.543      | -            | -                | -                | -         |     0.09 | decenty, felps, HEN1, noway, VINI |
|           27 |     6097 | 2024-02-17 | adalYamigos         | W   | 0.518      | -            | -                | -                | -         |     0.15 | decenty, felps, HEN1, noway, VINI |
|           26 |     6148 | 2024-02-16 | Galorys             | W   | 0.511      | -            | -                | -                | -         |     0.30 | decenty, felps, HEN1, noway, VINI |
|           25 |     6153 | 2024-02-16 | Galorys             | W   | 0.511      | -            | -                | -                | -         |     0.30 | decenty, felps, HEN1, noway, VINI |
|           24 |     6195 | 2024-02-15 | 9z Team             | W   | 0.506      | -            | -                | -                | -         |     3.24 | decenty, felps, HEN1, noway, VINI |
|           23 |     6197 | 2024-02-15 | Fluxo               | W   | 0.505      | -            | -                | -                | -         |     0.75 | decenty, felps, HEN1, noway, VINI |
|           22 |     6200 | 2024-02-15 | Team Solid          | W   | 0.505      | -            | -                | -                | -         |     0.40 | decenty, felps, HEN1, noway, VINI |
|           21 |     6260 | 2024-02-14 | Yawara E-Sports     | W   | 0.499      | -            | -                | -                | -         |     0.17 | decenty, felps, HEN1, noway, VINI |
|           20 |     6319 | 2024-02-13 | RED Canids          | W   | 0.493      | -            | -                | -                | -         |     0.83 | decenty, felps, HEN1, noway, VINI |
|           19 |     6320 | 2024-02-13 | RED Canids          | L   | 0.492      | -            | -                | -                | -         |   -14.77 | decenty, felps, HEN1, noway, VINI |
|           18 |     6651 | 2024-02-04 | 9z Team             | W   | 0.432      | -            | -                | -                | -         |     2.64 | decenty, felps, HEN1, noway, VINI |
|           17 |     6695 | 2024-02-03 | MIBR                | W   | 0.425      | -            | -                | -                | -         |     7.87 | decenty, felps, HEN1, noway, VINI |
|           16 |     6780 | 2024-02-02 | BESTIA              | W   | 0.420      | -            | -                | -                | -         |     0.55 | decenty, felps, HEN1, noway, VINI |
|           15 |     6784 | 2024-02-02 | 9z Team             | L   | 0.419      | -            | -                | -                | -         |   -10.73 | decenty, felps, HEN1, noway, VINI |
|           14 |     6786 | 2024-02-02 | BESTIA              | W   | 0.419      | -            | -                | -                | -         |     0.51 | decenty, felps, HEN1, noway, VINI |
|           13 |     7065 | 2024-01-28 | Hype Esports        | W   | 0.385      | -            | -                | -                | -         |     0.04 | decenty, felps, HEN1, noway, VINI |
|           12 |     7068 | 2024-01-28 | LA RUGONETA         | W   | 0.385      | -            | -                | -                | -         |     0.05 | decenty, felps, HEN1, noway, VINI |
|           11 |     7126 | 2024-01-27 | FURIA Academy       | W   | 0.379      | -            | -                | -                | -         |     0.06 | decenty, felps, HEN1, noway, VINI |
|           10 |     7298 | 2024-01-25 | Yawara E-Sports     | L   | 0.366      | -            | -                | -                | -         |   -11.43 | decenty, felps, HEN1, noway, VINI |
|            9 |     7332 | 2024-01-24 | 9z Team             | W   | 0.359      | -            | -                | -                | -         |     1.98 | decenty, felps, HEN1, noway, VINI |
|            8 |     7406 | 2024-01-23 | BESTIA              | W   | 0.352      | -            | -                | -                | -         |     0.41 | decenty, felps, HEN1, noway, VINI |
|            7 |     7443 | 2024-01-22 | Hype Esports        | W   | 0.346      | -            | -                | -                | -         |     0.03 | decenty, felps, HEN1, noway, VINI |
|            6 |     7504 | 2024-01-21 | paiN Gaming         | W   | 0.338      | -            | -                | -                | -         |     6.51 | decenty, felps, HEN1, noway, VINI |
|            5 |     7563 | 2024-01-20 | Fluxo               | W   | 0.331      | -            | -                | -                | -         |     0.44 | decenty, felps, HEN1, noway, VINI |
|            4 |     7632 | 2024-01-19 | BESTIA              | L   | 0.326      | -            | -                | -                | -         |    -9.91 | decenty, felps, HEN1, noway, VINI |
|            3 |     7638 | 2024-01-19 | Galorys             | W   | 0.325      | -            | -                | -                | -         |     0.19 | decenty, felps, HEN1, noway, VINI |
|            2 |     7874 | 2024-01-16 | Legacy              | L   | 0.305      | -            | -                | -                | -         |    -9.17 | decenty, felps, HEN1, noway, VINI |
|            1 |     7950 | 2024-01-15 | Corinthians Esports | W   | 0.299      | -            | -                | -                | -         |     0.05 | decenty, felps, HEN1, noway, VINI |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($111,936.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-16 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-05-12 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-04-20 |      0.938 | $50,000.00     | $46,898.15      |
| 2024-04-15 |      0.904 | $15,000.00     | $13,566.67      |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-02-25 |      0.571 | $15,000.00     | $8,570.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
