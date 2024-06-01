### Roster Details<br />
Team Name: Begrip Gaming<br />
Roster: Ariant0, Karma, Reedz, titulus, treckiz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [412](../standings_global.md)<br />
Regional Rank: [248]( ../standings_europe.md)<br />
Final Rank Value:  534.3<br />
<br />
Final Rank Value (534.3) = Starting Rank Value (611.9) + Head To Head Adjustments (-77.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.195[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 611.9
- 400 + ( ( 0.104 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 611.9


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
|           42 |      392 | 2024-05-23 | Johnny Speeds         | L   | 1.000      | -            | -                | -                | -         |    -1.82 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           41 |      913 | 2024-05-18 | EC BANGA              | L   | 1.000      | -            | -                | -                | -         |   -18.83 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           40 |     1486 | 2024-05-10 | Rok paus vid 45       | L   | 1.000      | -            | -                | -                | -         |   -16.51 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           39 |     1489 | 2024-05-10 | snyggmix              | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     9.04 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           38 |     1492 | 2024-05-10 | Podwars               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.133 (0.019)    | 0 (0.000) |    19.07 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           37 |     1557 | 2024-05-09 | Kappa Borr            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.127 (0.018)    | 0 (0.000) |    14.55 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           36 |     1806 | 2024-05-04 | Lemoncats             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    14.87 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           35 |     1862 | 2024-05-03 | Odjur                 | L   | 1.000      | -            | -                | -                | -         |   -17.46 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           34 |     1960 | 2024-05-01 | Podwars               | L   | 1.000      | -            | -                | -                | -         |   -10.61 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           33 |     2304 | 2024-04-25 | showmakerz            | L   | 0.971      | -            | -                | -                | -         |   -14.34 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           32 |     2352 | 2024-04-24 | Johnny Speeds         | L   | 0.964      | -            | -                | -                | -         |    -1.94 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           31 |     2835 | 2024-04-17 | showmakerz            | L   | 0.917      | -            | -                | -                | -         |   -14.32 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           30 |     2908 | 2024-04-16 | Full Kareta           | W   | 0.910      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     7.09 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           29 |     3072 | 2024-04-12 | Young Gods            | L   | 0.884      | -            | -                | -                | -         |   -14.89 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           28 |     3156 | 2024-04-10 | AURA                  | L   | 0.871      | -            | -                | -                | -         |    -8.18 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           27 |     3158 | 2024-04-10 | plusW                 | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.094 (0.012)    | 0 (0.000) |    13.26 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           26 |     3161 | 2024-04-10 | ishjarnor             | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.059 (0.007)    | 0 (0.000) |     7.58 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           25 |     3439 | 2024-04-05 | regelett              | W   | 0.837      | 0.143        | 0.000 (0.000)    | 0.129 (0.015)    | 0 (0.000) |     7.62 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           24 |     3784 | 2024-03-27 | showmakerz            | L   | 0.778      | -            | -                | -                | -         |   -12.30 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           23 |     4003 | 2024-03-23 | KILLBOX               | L   | 0.750      | -            | -                | -                | -         |   -15.13 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           22 |     4134 | 2024-03-20 | E-Town Gaming         | W   | 0.731      | -            | -                | -                | 0 (0.000) |     5.97 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           21 |     4256 | 2024-03-17 | Kappa Borr            | L   | 0.711      | -            | -                | -                | -         |   -14.01 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           20 |     4305 | 2024-03-16 | Young Gods            | L   | 0.705      | -            | -                | -                | -         |   -13.13 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           19 |     4309 | 2024-03-16 | HANE                  | W   | 0.704      | -            | -                | -                | 0 (0.000) |     8.23 | jocab, L00m1, maxster, SeBreeZe, Silence   |
|           18 |     4330 | 2024-03-16 | Eld                   | W   | 0.703      | -            | -                | -                | -         |     5.27 | L1ndfors, QUAK, s1m0n, Weppling, yTa       |
|           17 |     4693 | 2024-03-09 | XI Esport             | L   | 0.658      | -            | -                | -                | -         |    -9.03 | Ariant0, Karma, nimaaz, Reedz, shateri     |
|           16 |     4949 | 2024-03-05 | EP Genesis            | L   | 0.631      | -            | -                | -                | -         |   -11.82 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           15 |     5045 | 2024-03-04 | GamerLegion Academy   | L   | 0.623      | -            | -                | -                | -         |    -5.33 | Darber, Goody, leaf, nestee, rud           |
|           14 |     5189 | 2024-03-02 | Preasy Esport         | L   | 0.610      | -            | -                | -                | -         |    -4.99 | beccie, Equip, Griller, Skejs, VireZ       |
|           13 |     5455 | 2024-02-25 | Natus Vincere Junior  | W   | 0.570      | 0.289        | 0.006 (0.001)    | 0.422 (0.070)    | -         |    12.39 | cmtry, dziugss, froz1k, qzr, UNBR0KEN      |
|           12 |     5716 | 2024-02-21 | Dynamo Eclot Thunders | W   | 0.543      | 0.289        | -                | 0.026 (0.004)    | -         |     3.87 | Ariant0, Karma, Reedz, shateri, titulus    |
|           11 |     7124 | 2024-01-24 | AVEZ                  | L   | 0.357      | -            | -                | -                | -         |    -2.51 | Ariant0, Karma, Reedz, shateri, titulus    |
|           10 |     7329 | 2024-01-20 | Young Gods            | W   | 0.331      | 0.289        | -                | 0.240 (0.023)    | -         |     4.03 | Cham, Focus, MaiL09, viz, Wonder           |
|            9 |     7685 | 2024-01-16 | ex-KRC Genk Esports   | L   | 0.303      | -            | -                | -                | -         |    -4.34 | AyeZ, CrePoW, Philong, Wumbo, yOOm         |
|            8 |     8244 | 2024-01-03 | Lilmix                | L   | 0.218      | -            | -                | -                | -         |    -4.03 | Ariant0, Karma, Reedz, shateri, titulus    |
|            7 |     8252 | 2024-01-03 | showmakerz            | W   | 0.218      | 0.143        | -                | 0.201 (0.006)    | -         |     2.75 | Ariant0, Karma, Reedz, shateri, titulus    |
|            6 |     8262 | 2024-01-03 | Kappa Bar             | W   | 0.217      | -            | -                | -                | -         |     2.61 | Ariant0, Karma, Reedz, shateri, titulus    |
|            5 |     9163 | 2023-12-07 | Monte Gen             | L   | 0.037      | -            | -                | -                | -         |    -0.34 | Gizmy, leen, n0te, ryu, shield             |
|            4 |     9231 | 2023-12-06 | GamerLegion Academy   | L   | 0.030      | -            | -                | -                | -         |    -0.21 | aNdu, Darber, leaf, nestee, rud            |
|            3 |     9265 | 2023-12-05 | angelnumbers          | L   | 0.025      | -            | -                | -                | -         |    -0.36 | Ariant0, Karma, Reedz, shateri, titulus    |
|            2 |     9269 | 2023-12-05 | Young Gods            | W   | 0.025      | -            | -                | -                | -         |     0.31 | Focus, Lindcs, MaiL09, viz, Wonder         |
|            1 |     9338 | 2023-12-04 | Monte Gen             | W   | 0.017      | 0.289        | 0.007 (0.000)    | -                | -         |     0.37 | Gizmy, leen, n0te, ryu, shield             |

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
