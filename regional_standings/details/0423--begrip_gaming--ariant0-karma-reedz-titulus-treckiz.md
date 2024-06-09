### Roster Details<br />
Team Name: Begrip Gaming<br />
Roster: Ariant0, Karma, Reedz, titulus, treckiz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [423](../standings_global.md)<br />
Regional Rank: [255]( ../standings_europe.md)<br />
Final Rank Value:  535.2<br />
<br />
Final Rank Value (535.2) = Starting Rank Value (611.8) + Head To Head Adjustments (-76.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.195[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 611.8
- 400 + ( ( 0.104 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 611.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      400 | 2024-05-23 | Johnny Speeds         | L   | 1.000      | -            | -                | -                | -         |    -1.82 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           41 |      925 | 2024-05-18 | EC BANGA              | L   | 1.000      | -            | -                | -                | -         |   -18.86 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           40 |     1499 | 2024-05-10 | Rok paus vid 45       | L   | 1.000      | -            | -                | -                | -         |   -16.55 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           39 |     1502 | 2024-05-10 | snyggmix              | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     9.01 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           38 |     1505 | 2024-05-10 | Podwars               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.133 (0.019)    | 0 (0.000) |    19.03 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           37 |     1572 | 2024-05-09 | Kappa Borr            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.127 (0.018)    | 0 (0.000) |    14.52 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           36 |     1829 | 2024-05-04 | Lemoncats             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    14.85 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           35 |     1886 | 2024-05-03 | Odjur                 | L   | 1.000      | -            | -                | -                | -         |   -17.51 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           34 |     1987 | 2024-05-01 | Podwars               | L   | 1.000      | -            | -                | -                | -         |   -10.66 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           33 |     2341 | 2024-04-25 | showmakerz            | L   | 0.971      | -            | -                | -                | -         |   -14.23 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           32 |     2393 | 2024-04-24 | Johnny Speeds         | L   | 0.964      | -            | -                | -                | -         |    -1.94 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           31 |     2892 | 2024-04-17 | showmakerz            | L   | 0.917      | -            | -                | -                | -         |   -14.20 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           30 |     2968 | 2024-04-16 | Full Kareta           | W   | 0.910      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     7.07 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           29 |     3138 | 2024-04-12 | Young Gods            | L   | 0.884      | -            | -                | -                | -         |   -14.86 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           28 |     3227 | 2024-04-10 | AURA                  | L   | 0.871      | -            | -                | -                | -         |    -8.22 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           27 |     3229 | 2024-04-10 | plusW                 | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.094 (0.012)    | 0 (0.000) |    13.11 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           26 |     3232 | 2024-04-10 | ishjarnor             | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.059 (0.007)    | 0 (0.000) |     7.54 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           25 |     3523 | 2024-04-05 | regelett              | W   | 0.837      | 0.143        | 0.000 (0.000)    | 0.129 (0.015)    | 0 (0.000) |     7.58 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           24 |     3877 | 2024-03-27 | showmakerz            | L   | 0.778      | -            | -                | -                | -         |   -12.17 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           23 |     4100 | 2024-03-23 | KILLBOX               | L   | 0.750      | -            | -                | -                | -         |   -15.16 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           22 |     4235 | 2024-03-20 | E-Town Gaming         | W   | 0.731      | -            | -                | -                | 0 (0.000) |     5.94 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           21 |     4361 | 2024-03-17 | Kappa Borr            | L   | 0.711      | -            | -                | -                | -         |   -14.03 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           20 |     4411 | 2024-03-16 | Young Gods            | L   | 0.705      | -            | -                | -                | -         |   -13.10 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           19 |     4415 | 2024-03-16 | HANE                  | W   | 0.704      | -            | -                | -                | 0 (0.000) |     8.20 | jocab, L00m1, maxster, SeBreeZe, Silence   |
|           18 |     4436 | 2024-03-16 | Eld                   | W   | 0.703      | -            | -                | -                | -         |     5.24 | L1ndfors, QUAK, s1m0n, Weppling, yTa       |
|           17 |     4818 | 2024-03-09 | XI Esport             | L   | 0.658      | -            | -                | -                | -         |    -9.00 | Ariant0, Karma, nimaaz, Reedz, shateri     |
|           16 |     5089 | 2024-03-05 | EP Genesis            | L   | 0.631      | -            | -                | -                | -         |   -11.84 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           15 |     5191 | 2024-03-04 | GamerLegion Academy   | L   | 0.623      | -            | -                | -                | -         |    -5.48 | Darber, Goody, leaf, nestee, rud           |
|           14 |     5337 | 2024-03-02 | Preasy Esport         | L   | 0.610      | -            | -                | -                | -         |    -4.86 | beccie, Equip, Griller, Skejs, VireZ       |
|           13 |     5613 | 2024-02-25 | Natus Vincere Junior  | W   | 0.570      | 0.289        | 0.006 (0.001)    | 0.444 (0.073)    | -         |    12.47 | cmtry, dziugss, froz1k, qzr, UNBR0KEN      |
|           12 |     5879 | 2024-02-21 | Dynamo Eclot Thunders | W   | 0.543      | 0.289        | -                | 0.026 (0.004)    | -         |     3.85 | Ariant0, Karma, Reedz, shateri, titulus    |
|           11 |     7359 | 2024-01-24 | AVEZ                  | L   | 0.357      | -            | -                | -                | -         |    -2.28 | Ariant0, Karma, Reedz, shateri, titulus    |
|           10 |     7573 | 2024-01-20 | Young Gods            | W   | 0.331      | 0.289        | -                | 0.240 (0.023)    | -         |     4.05 | Cham, Focus, MaiL09, viz, Wonder           |
|            9 |     7934 | 2024-01-16 | ex-KRC Genk Esports   | L   | 0.303      | -            | -                | -                | -         |    -3.49 | AyeZ, CrePoW, Philong, Wumbo, yOOm         |
|            8 |     8500 | 2024-01-03 | Lilmix                | L   | 0.218      | -            | -                | -                | -         |    -3.97 | Ariant0, Karma, Reedz, shateri, titulus    |
|            7 |     8508 | 2024-01-03 | showmakerz            | W   | 0.218      | 0.143        | -                | 0.201 (0.006)    | -         |     2.79 | Ariant0, Karma, Reedz, shateri, titulus    |
|            6 |     8518 | 2024-01-03 | Kappa Bar             | W   | 0.217      | -            | -                | -                | -         |     2.62 | Ariant0, Karma, Reedz, shateri, titulus    |
|            5 |     9436 | 2023-12-07 | Monte Gen             | L   | 0.037      | -            | -                | -                | -         |    -0.34 | Gizmy, leen, n0te, ryu, shield             |
|            4 |     9512 | 2023-12-06 | GamerLegion Academy   | L   | 0.030      | -            | -                | -                | -         |    -0.20 | aNdu, Darber, leaf, nestee, rud            |
|            3 |     9547 | 2023-12-05 | angelnumbers          | L   | 0.025      | -            | -                | -                | -         |    -0.36 | Ariant0, Karma, Reedz, shateri, titulus    |
|            2 |     9551 | 2023-12-05 | Young Gods            | W   | 0.025      | -            | -                | -                | -         |     0.31 | Focus, Lindcs, MaiL09, viz, Wonder         |
|            1 |     9620 | 2023-12-04 | Monte Gen             | W   | 0.017      | 0.289        | 0.007 (0.000)    | -                | -         |     0.37 | Gizmy, leen, n0te, ryu, shield             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22.08)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
