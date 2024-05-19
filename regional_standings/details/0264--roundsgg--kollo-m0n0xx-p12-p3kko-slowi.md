### Roster Details<br />
Team Name: RoundsGG<br />
Roster: Kollo, m0n0xx, p12, p3kko, sLowi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [264](../standings_global.md)<br />
Regional Rank: [165]( ../standings_europe.md)<br />
Final Rank Value:  653.1<br />
<br />
Final Rank Value (653.1) = Starting Rank Value (732.4) + Head To Head Adjustments (-79.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.203[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.060[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.4
- 400 + ( ( 0.168 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 732.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      201 | 2024-05-01 | HOTU                | L   | 1.000      | -            | -                | -                | -         |    -9.52 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           34 |      270 | 2024-04-29 | RUBY                | L   | 1.000      | -            | -                | -                | -         |    -4.96 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           33 |      363 | 2024-04-27 | TOOMUCHVIDEOGAMES   | L   | 1.000      | -            | -                | -                | -         |   -20.76 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           32 |      531 | 2024-04-24 | Lilmix              | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.604 (0.224)    | 0 (0.000) |    17.10 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           31 |      578 | 2024-04-23 | Permitta Esports    | L   | 1.000      | -            | -                | -                | -         |    -5.92 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           30 |      809 | 2024-04-19 | DUSTY               | L   | 1.000      | -            | -                | -                | -         |   -14.35 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           29 |     1068 | 2024-04-14 | TOOMUCHVIDEOGAMES   | L   | 1.000      | -            | -                | -                | -         |   -21.39 | Kollo, m0n0xx, p12, p3kko, sLowi |
|           28 |     2794 | 2024-03-03 | Lilmix              | W   | 0.778      | 0.371        | 0.000 (0.000)    | 0.604 (0.175)    | 0 (0.000) |    10.01 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           27 |     2806 | 2024-03-03 | Soda Gaming         | L   | 0.778      | -            | -                | -                | -         |   -12.10 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           26 |     2861 | 2024-03-02 | FORZE Esports       | L   | 0.772      | -            | -                | -                | -         |    -2.43 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           25 |     2978 | 2024-02-28 | EsmagaB             | L   | 0.752      | -            | -                | -                | -         |    -9.32 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           24 |     3158 | 2024-02-24 | HAVU Gaming         | L   | 0.725      | -            | -                | -                | -         |    -7.24 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           23 |     3203 | 2024-02-23 | KUUSAMO.gg          | W   | 0.719      | 0.143        | 0.005 (0.001)    | 0.153 (0.016)    | 1 (0.719) |    13.19 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           22 |     3239 | 2024-02-22 | KUUSAMO.gg          | W   | 0.712      | 0.143        | 0.005 (0.001)    | 0.153 (0.016)    | 1 (0.712) |    13.65 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           21 |     3300 | 2024-02-21 | GUN5 Esports        | W   | 0.705      | 0.371        | 0.000 (0.000)    | 0.218 (0.057)    | 0 (0.000) |     9.44 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           20 |     3398 | 2024-02-19 | L&G                 | W   | 0.692      | 0.371        | -                | 0.064 (0.016)    | 0 (0.000) |     6.73 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           19 |     3414 | 2024-02-19 | VaselineWorms       | L   | 0.691      | -            | -                | -                | -         |   -11.74 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           18 |     3726 | 2024-02-12 | K10                 | L   | 0.645      | -            | -                | -                | -         |    -6.25 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           17 |     3841 | 2024-02-07 | BAKS Esports        | W   | 0.612      | 0.371        | 0.003 (0.001)    | 0.084 (0.019)    | 0 (0.000) |     8.48 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           16 |     3970 | 2024-02-03 | TOOMUCHVIDEOGAMES   | L   | 0.585      | -            | -                | -                | -         |   -13.80 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           15 |     4068 | 2024-02-01 | RUBY                | L   | 0.572      | -            | -                | -                | -         |    -4.69 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           14 |     4382 | 2024-01-24 | V1dar Gaming        | L   | 0.518      | -            | -                | -                | -         |   -11.01 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           13 |     4427 | 2024-01-23 | KRC Genk Esports    | W   | 0.512      | -            | -                | -                | 0 (0.000) |     2.21 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           12 |     4457 | 2024-01-22 | DASH                | L   | 0.506      | -            | -                | -                | -         |    -8.85 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           11 |     6264 | 2023-11-29 | 9Pandas             | W   | 0.145      | 0.371        | 0.085 (0.005)    | 0.661 (0.036)    | 0 (0.000) |     4.14 | Kollo, LYNXi, m0n0xx, p12, Welho |
|           10 |     6299 | 2023-11-28 | Team Spirit Academy | W   | 0.139      | 0.371        | 0.021 (0.001)    | 0.422 (0.022)    | 0 (0.000) |     2.62 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            9 |     6317 | 2023-11-28 | Ex-Anonymo Esports  | W   | 0.138      | 0.371        | 0.019 (0.001)    | -                | -         |     2.42 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            8 |     6352 | 2023-11-27 | SHIPACHI            | L   | 0.132      | -            | -                | -                | -         |    -3.39 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            7 |     6369 | 2023-11-27 | Aurora Young Blud   | W   | 0.132      | 0.371        | 0.017 (0.001)    | 0.422 (0.021)    | -         |     2.61 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            6 |     6550 | 2023-11-22 | ESCAPIST            | L   | 0.099      | -            | -                | -                | -         |    -2.31 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            5 |     6819 | 2023-11-16 | GODSENT             | L   | 0.058      | -            | -                | -                | -         |    -0.74 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            4 |     6825 | 2023-11-16 | INGLORIOUS          | L   | 0.058      | -            | -                | -                | -         |    -0.77 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            3 |     6885 | 2023-11-15 | BALLISTIC           | W   | 0.052      | -            | -                | -                | -         |     0.22 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            2 |     7089 | 2023-11-10 | Team Universe       | L   | 0.019      | -            | -                | -                | -         |    -0.39 | Kollo, LYNXi, m0n0xx, p12, Welho |
|            1 |     7142 | 2023-11-09 | Apeks Rebels        | L   | 0.011      | -            | -                | -                | -         |    -0.19 | Kollo, LYNXi, m0n0xx, p12, Welho |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18.87)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
