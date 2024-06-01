### Roster Details<br />
Team Name: Corinthians Esports<br />
Roster: CutzMeretz, desh, Leomonster, Roz, zede<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [282](../standings_global.md)<br />
Regional Rank: [62]( ../standings_americas.md)<br />
Final Rank Value:  653.9<br />
<br />
Final Rank Value (653.9) = Starting Rank Value (616.4) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.213[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.106<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 616.4
- 400 + ( ( 0.106 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 616.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      100 | 2024-05-28 | MIBR Academy              | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    15.93 | CutzMeretz, desh, Leomonster, Roz, zede    |
|           16 |      164 | 2024-05-27 | United E-sports           | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.059 (0.008)    | 0 (0.000) |    13.80 | CutzMeretz, desh, Leomonster, Roz, zede    |
|           15 |      179 | 2024-05-27 | eSports Recife            | L   | 1.000      | -            | -                | -                | -         |   -10.98 | CutzMeretz, desh, Leomonster, Roz, zede    |
|           14 |      264 | 2024-05-25 | CS ao Contrario           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.66 | CutzMeretz, desh, Leomonster, Roz, zede    |
|           13 |     7701 | 2024-01-15 | Imperial Esports          | L   | 0.299      | -            | -                | -                | -         |    -0.05 | abr, Alisson, CutzMeretz, desh, Leomonster |
|           12 |     7748 | 2024-01-14 | Sharks Esports            | L   | 0.292      | -            | -                | -                | -         |    -1.71 | doc, drg, gafolo, rdnzao, togs             |
|           11 |     7754 | 2024-01-14 | KRÜ Esports               | W   | 0.291      | 0.143        | 0.019 (0.001)    | 0.272 (0.011)    | 0 (0.000) |     6.53 | abr, Alisson, CutzMeretz, desh, Leomonster |
|           10 |     7929 | 2024-01-11 | 2Game Esports             | L   | 0.271      | -            | -                | -                | -         |    -3.42 | Brnz1k, dok, dzt, santos, vhz              |
|            9 |     7985 | 2024-01-10 | Projeto KinGui            | W   | 0.266      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     2.64 | kln, Ltz, Machado, skl, void               |
|            8 |     8059 | 2024-01-09 | ODDIK                     | L   | 0.258      | -            | -                | -                | -         |    -1.19 | abr, Alisson, CutzMeretz, desh, Leomonster |
|            7 |     8067 | 2024-01-09 | TIMACETA                  | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.060 (0.002)    | 0 (0.000) |     4.20 | beg0d, bnc, cerolzin, farias, leleo        |
|            6 |     8172 | 2024-01-08 | pugdesonesto              | W   | 0.252      | 0.143        | 0.001 (0.000)    | 0.146 (0.005)    | 0 (0.000) |     4.31 | freitas, imoto, kxr, N3blina, Thuister     |
|            5 |     8392 | 2023-12-19 | ODDIK                     | L   | 0.118      | -            | -                | -                | -         |    -0.54 | abr, Alisson, CutzMeretz, desh, Leomonster |
|            4 |     8411 | 2023-12-18 | WINDINGO                  | W   | 0.111      | 0.303        | 0.001 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.80 | bichop, nasher, PREDI, restik, Righi       |
|            3 |     8593 | 2023-12-16 | ODDIK                     | L   | 0.098      | -            | -                | -                | -         |    -0.44 | abr, Alisson, CutzMeretz, desh, Leomonster |
|            2 |     8716 | 2023-12-15 | Case Esports              | L   | 0.092      | -            | -                | -                | -         |    -1.19 | abr, Alisson, CutzMeretz, desh, Leomonster |
|            1 |     8813 | 2023-12-13 | Arena Jogue Fácil Esports | W   | 0.079      | 0.143        | 0.000 (0.000)    | 0.038 (0.000)    | 0 (0.000) |     1.20 | Lineko, n9xtz, pigo, r1see, urban0         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
