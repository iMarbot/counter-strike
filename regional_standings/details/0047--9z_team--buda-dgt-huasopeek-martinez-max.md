### Roster Details<br />
Team Name: 9z Team<br />
Roster: buda, dgt, HUASOPEEK, Martinez, max<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [47](../standings_global.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
Final Rank Value:  1041.6<br />
<br />
Final Rank Value (1041.6) = Starting Rank Value (932.3) + Head To Head Adjustments (109.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.429[<sup>2</sup>](#table1)
- Opponent Network: 0.087[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 932.3
- 400 + ( ( 0.268 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 932.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      174 | 2024-05-01 | Case Esports             | W   | 1.000      | 0.450        | 0.027 (0.012)    | 0.401 (0.181)    | false (0.000) |     6.85 | buda, dgt, HUASOPEEK, Martinez, max |
|           38 |      179 | 2024-05-01 | Case Esports             | W   | 1.000      | 0.450        | 0.027 (0.012)    | 0.401 (0.181)    | false (0.000) |     7.28 | buda, dgt, HUASOPEEK, Martinez, max |
|           37 |      789 | 2024-04-19 | OG                       | L   | 1.000      | -            | -                | -                | -             |    -3.81 | buda, dgt, HUASOPEEK, Martinez, max |
|           36 |      860 | 2024-04-18 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -             |    -2.45 | buda, dgt, HUASOPEEK, Martinez, max |
|           35 |      866 | 2024-04-18 | FURIA Esports            | W   | 1.000      | 0.589        | 0.384 (0.226)    | 0.361 (0.213)    | true (1.000)  |    29.75 | buda, dgt, HUASOPEEK, Martinez, max |
|           34 |     1348 | 2024-04-08 | HEROIC                   | L   | 1.000      | -            | -                | -                | -             |    -0.89 | buda, dgt, HUASOPEEK, Martinez, max |
|           33 |     1359 | 2024-04-07 | G2 Esports               | L   | 1.000      | -            | -                | -                | -             |    -0.25 | buda, dgt, HUASOPEEK, Martinez, max |
|           32 |     1746 | 2024-03-27 | Natus Vincere Junior     | L   | 0.938      | -            | -                | -                | -             |   -19.84 | buda, dgt, HUASOPEEK, Martinez, max |
|           31 |     1801 | 2024-03-26 | INFURITY Gaming          | W   | 0.932      | -            | -                | -                | false (0.000) |     1.16 | buda, dgt, HUASOPEEK, Martinez, max |
|           30 |     3194 | 2024-02-23 | FURIA Esports            | W   | 0.720      | 0.143        | 0.384 (0.040)    | -                | false (0.000) |    21.89 | buda, dgt, HUASOPEEK, Martinez, max |
|           29 |     3204 | 2024-02-23 | BESTIA                   | W   | 0.719      | 0.143        | -                | 0.423 (0.043)    | false (0.000) |     6.87 | buda, dgt, HUASOPEEK, Martinez, max |
|           28 |     3230 | 2024-02-22 | FURIA Esports            | L   | 0.713      | -            | -                | -                | -             |    -0.70 | buda, dgt, HUASOPEEK, Martinez, max |
|           27 |     3238 | 2024-02-22 | BESTIA                   | W   | 0.712      | 0.143        | -                | 0.423 (0.043)    | false (0.000) |     6.56 | buda, dgt, HUASOPEEK, Martinez, max |
|           26 |     3333 | 2024-02-20 | Team Solid               | W   | 0.700      | 0.143        | 0.138 (0.014)    | -                | false (0.000) |     6.79 | buda, dgt, HUASOPEEK, Martinez, max |
|           25 |     3336 | 2024-02-20 | Case Esports             | W   | 0.700      | 0.143        | -                | 0.401 (0.040)    | false (0.000) |     6.90 | buda, dgt, HUASOPEEK, Martinez, max |
|           24 |     3337 | 2024-02-20 | Floripa Stars            | W   | 0.699      | -            | -                | -                | false (0.000) |     3.29 | buda, dgt, HUASOPEEK, Martinez, max |
|           23 |     3393 | 2024-02-19 | Hawks (Argentinian team) | W   | 0.694      | -            | -                | -                | -             |     3.19 | buda, dgt, HUASOPEEK, Martinez, max |
|           22 |     3455 | 2024-02-18 | LA RUGONETA              | L   | 0.684      | -            | -                | -                | -             |   -19.54 | buda, dgt, HUASOPEEK, Martinez, max |
|           21 |     3520 | 2024-02-16 | Fluxo                    | L   | 0.672      | -            | -                | -                | -             |   -10.27 | buda, dgt, HUASOPEEK, Martinez, max |
|           20 |     3563 | 2024-02-15 | Imperial Esports         | L   | 0.667      | -            | -                | -                | -             |    -0.93 | buda, dgt, HUASOPEEK, Martinez, max |
|           19 |     3564 | 2024-02-15 | Case Esports             | W   | 0.666      | -            | -                | -                | -             |     6.43 | buda, dgt, HUASOPEEK, Martinez, max |
|           18 |     3611 | 2024-02-14 | 2Game Esports            | W   | 0.660      | -            | -                | -                | -             |     1.92 | buda, dgt, HUASOPEEK, Martinez, max |
|           17 |     3708 | 2024-02-12 | LA RUGONETA              | W   | 0.646      | -            | -                | -                | -             |     1.68 | buda, dgt, HUASOPEEK, Martinez, max |
|           16 |     3913 | 2024-02-04 | Imperial Esports         | L   | 0.593      | -            | -                | -                | -             |    -0.79 | buda, dgt, HUASOPEEK, Martinez, max |
|           15 |     4007 | 2024-02-02 | Imperial Esports         | W   | 0.580      | 0.143        | 0.674 (0.056)    | 0.549 (0.045)    | -             |    17.55 | buda, dgt, HUASOPEEK, Martinez, max |
|           14 |     4010 | 2024-02-02 | ODDIK                    | W   | 0.579      | -            | -                | -                | -             |     8.06 | buda, dgt, HUASOPEEK, Martinez, max |
|           13 |     4373 | 2024-01-24 | Imperial Esports         | L   | 0.520      | -            | -                | -                | -             |    -0.54 | buda, dgt, HUASOPEEK, Martinez, max |
|           12 |     4421 | 2024-01-23 | Fluxo                    | W   | 0.513      | 0.143        | 0.153 (0.011)    | -                | -             |     9.29 | buda, dgt, HUASOPEEK, Martinez, max |
|           11 |     4450 | 2024-01-22 | Galorys                  | W   | 0.507      | 0.143        | -                | 0.598 (0.043)    | -             |     5.71 | buda, dgt, HUASOPEEK, Martinez, max |
|           10 |     4494 | 2024-01-21 | RED Canids               | L   | 0.501      | -            | -                | -                | -             |    -8.38 | buda, dgt, HUASOPEEK, Martinez, max |
|            9 |     4501 | 2024-01-21 | Sharks Esports           | W   | 0.498      | -            | -                | -                | -             |     6.70 | buda, dgt, HUASOPEEK, Martinez, max |
|            8 |     4537 | 2024-01-20 | ODDIK                    | L   | 0.492      | -            | -                | -                | -             |    -8.81 | buda, dgt, HUASOPEEK, Martinez, max |
|            7 |     4595 | 2024-01-19 | Legacy                   | L   | 0.486      | -            | -                | -                | -             |    -4.86 | buda, dgt, HUASOPEEK, Martinez, max |
|            6 |     4636 | 2024-01-18 | MIBR                     | W   | 0.480      | 0.143        | 0.654 (0.045)    | 0.616 (0.042)    | -             |    14.81 | buda, dgt, HUASOPEEK, Martinez, max |
|            5 |     4689 | 2024-01-17 | MIBR                     | W   | 0.473      | 0.143        | 0.654 (0.044)    | 0.616 (0.042)    | -             |    14.65 | buda, dgt, HUASOPEEK, Martinez, max |
|            4 |     4719 | 2024-01-17 | RED Canids               | W   | 0.472      | 0.143        | 0.108 (0.007)    | -                | -             |     7.72 | buda, dgt, HUASOPEEK, Martinez, max |
|            3 |     6420 | 2023-11-25 | Case Esports             | L   | 0.119      | -            | -                | -                | -             |    -2.89 | buda, dgt, HUASOPEEK, max, tge      |
|            2 |     6458 | 2023-11-24 | BESTIA                   | L   | 0.114      | -            | -                | -                | -             |    -2.37 | buda, dgt, HUASOPEEK, max, tge      |
|            1 |     6506 | 2023-11-23 | RED Canids               | W   | 0.105      | -            | -                | -                | -             |     1.61 | buda, dgt, HUASOPEEK, max, tge      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-14 |      1.000 | $4,000.00      | $4,000.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
