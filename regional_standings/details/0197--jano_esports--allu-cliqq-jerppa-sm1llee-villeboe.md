### Roster Details<br />
Team Name: JANO Esports<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [197](../standings_global.md)<br />
Regional Rank: [134]( ../standings_europe.md)<br />
Final Rank Value:  727.2<br />
<br />
Final Rank Value (727.2) = Starting Rank Value (787.3) + Head To Head Adjustments (-60.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 787.3
- 400 + ( ( 0.191 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 787.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |       45 | 2024-05-29 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -3.95 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           48 |      405 | 2024-05-23 | Passion UA                | L   | 1.000      | -            | -                | -                | -         |    -6.86 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           47 |      412 | 2024-05-23 | Entropiq                  | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.220 (0.082)    | 0 (0.000) |    15.31 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           46 |      416 | 2024-05-23 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |    -5.64 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           45 |      614 | 2024-05-21 | Tropic                    | L   | 1.000      | -            | -                | -                | -         |   -23.48 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           44 |     1081 | 2024-05-16 | LODIS                     | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |     9.59 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           43 |     1087 | 2024-05-16 | ENRAGE                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.05 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           42 |     1183 | 2024-05-15 | ARROW                     | L   | 1.000      | -            | -                | -                | -         |   -17.06 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           41 |     1322 | 2024-05-13 | kONO.ECF                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.853 (0.318)    | 0 (0.000) |    23.19 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           40 |     1569 | 2024-05-09 | Raptors Esports Club      | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    19.54 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           39 |     1576 | 2024-05-09 | FLuffy Gangsters          | W   | 1.000      | 0.372        | -                | 0.394 (0.147)    | 0 (0.000) |    12.50 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           38 |     1644 | 2024-05-08 | VaselineWorms             | L   | 1.000      | -            | -                | -                | -         |   -17.88 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           37 |     2210 | 2024-04-27 | Sashi Esport              | L   | 0.984      | -            | -                | -                | -         |    -1.67 | allu, doto, Jerppa, juho, Sm1llee      |
|           36 |     2236 | 2024-04-27 | Heimo Esports             | L   | 0.982      | -            | -                | -                | -         |   -15.45 | allu, doto, Jerppa, juho, Sm1llee      |
|           35 |     2272 | 2024-04-26 | Sashi Esport              | L   | 0.978      | -            | -                | -                | -         |    -1.83 | allu, doto, Jerppa, juho, Sm1llee      |
|           34 |     2276 | 2024-04-26 | Preasy Esport             | L   | 0.978      | -            | -                | -                | -         |   -14.89 | allu, doto, Jerppa, juho, Sm1llee      |
|           33 |     2282 | 2024-04-26 | Static                    | W   | 0.977      | -            | -                | -                | 0 (0.000) |     7.43 | allu, doto, Jerppa, juho, Sm1llee      |
|           32 |     2288 | 2024-04-26 | 777 Esports               | L   | 0.977      | -            | -                | -                | -         |   -15.89 | allu, doto, Jerppa, juho, Sm1llee      |
|           31 |     2294 | 2024-04-26 | Esport Harte              | W   | 0.977      | -            | -                | -                | 0 (0.000) |     8.07 | allu, doto, Jerppa, juho, Sm1llee      |
|           30 |     2313 | 2024-04-26 | GamerLegion Academy       | L   | 0.976      | -            | -                | -                | -         |   -11.44 | allu, doto, Jerppa, juho, Sm1llee      |
|           29 |     2354 | 2024-04-25 | ex-Turów Zgorzelec Esport | W   | 0.970      | 0.372        | 0.006 (0.002)    | 0.491 (0.177)    | 0 (0.000) |    16.00 | allu, Cliqq, doto, Jerppa, Sm1llee     |
|           28 |     2403 | 2024-04-24 | LEON Esports              | L   | 0.964      | -            | -                | -                | -         |   -16.89 | allu, Cliqq, doto, Jerppa, Sm1llee     |
|           27 |     2477 | 2024-04-23 | LEON Esports              | W   | 0.956      | 0.143        | 0.001 (0.000)    | 0.564 (0.077)    | 0 (0.000) |    13.26 | allu, doto, Jerppa, juho, Sm1llee      |
|           26 |     2490 | 2024-04-22 | GamerLegion Academy       | L   | 0.951      | -            | -                | -                | -         |   -11.85 | allu, doto, Jerppa, juho, Sm1llee      |
|           25 |     2638 | 2024-04-20 | HAVU Gaming               | W   | 0.936      | 0.143        | 0.004 (0.000)    | -                | -         |    13.10 | allu, doto, Jerppa, juho, Sm1llee      |
|           24 |     2703 | 2024-04-20 | Sangal Esports            | L   | 0.934      | -            | -                | -                | -         |    -4.92 | allu, doto, Jerppa, juho, Sm1llee      |
|           23 |     2765 | 2024-04-19 | NOM Esports               | W   | 0.929      | -            | -                | -                | -         |    11.29 | allu, doto, Jerppa, juho, Sm1llee      |
|           22 |     2927 | 2024-04-17 | RUBY                      | L   | 0.915      | -            | -                | -                | -         |    -8.02 | allu, doto, Jerppa, juho, Sm1llee      |
|           21 |     2940 | 2024-04-16 | MOUZ NXT                  | L   | 0.914      | -            | -                | -                | -         |    -3.80 | allu, doto, Jerppa, juho, Sm1llee      |
|           20 |     3005 | 2024-04-15 | VP.Prodigy                | W   | 0.904      | 0.372        | 0.008 (0.003)    | 0.829 (0.279)    | -         |    18.10 | allu, Cliqq, doto, Jerppa, Sm1llee     |
|           19 |     3016 | 2024-04-15 | MOUZ NXT                  | L   | 0.903      | -            | -                | -                | -         |    -3.40 | allu, Cliqq, doto, Jerppa, Sm1llee     |
|           18 |     3054 | 2024-04-14 | Heimo Esports             | L   | 0.896      | -            | -                | -                | -         |   -14.33 | allu, doto, Jerppa, juho, Sm1llee      |
|           17 |     3157 | 2024-04-12 | Zero Tenacity             | W   | 0.881      | 0.371        | 0.147 (0.048)    | 1.000 (0.326)    | -         |    21.21 | allu, doto, Jerppa, juho, Sm1llee      |
|           16 |     3396 | 2024-04-08 | Permitta Esports          | L   | 0.854      | -            | -                | -                | -         |    -6.90 | allu, doto, Jerppa, juho, Sm1llee      |
|           15 |     3482 | 2024-04-06 | Johnny Speeds             | L   | 0.843      | -            | -                | -                | -         |    -5.22 | allu, doto, Jerppa, juho, Sm1llee      |
|           14 |     3605 | 2024-04-04 | Gaimin Gladiators         | L   | 0.828      | -            | -                | -                | -         |    -1.25 | allu, doto, Jerppa, juho, Sm1llee      |
|           13 |     4420 | 2024-03-16 | HANE                      | L   | 0.704      | -            | -                | -                | -         |   -17.89 | allu, doto, jelo, Jerppa, Sm1llee      |
|           12 |     4487 | 2024-03-15 | Regnum                    | L   | 0.697      | -            | -                | -                | -         |   -14.97 | allu, doto, jelo, Jerppa, Sm1llee      |
|           11 |     4684 | 2024-03-12 | kONO.ECF                  | L   | 0.676      | -            | -                | -                | -         |    -6.74 | allu, doto, jelo, Jerppa, Sm1llee      |
|           10 |     4894 | 2024-03-08 | INGLORIOUS                | W   | 0.649      | 0.384        | 0.001 (0.000)    | 0.223 (0.056)    | -         |    11.23 | allu, doto, jelo, Jerppa, Sm1llee      |
|            9 |     5194 | 2024-03-04 | Endpoint                  | L   | 0.623      | -            | -                | -                | -         |    -6.25 | allu, doto, jelo, Jerppa, Sm1llee      |
|            8 |     5274 | 2024-03-02 | Gaimin Gladiators         | L   | 0.612      | -            | -                | -                | -         |    -1.23 | allu, doto, jelo, Jerppa, Sm1llee      |
|            7 |     5299 | 2024-03-02 | Linx Legacy Madagaskar    | W   | 0.611      | -            | -                | -                | -         |     3.54 | allu, doto, jelo, Jerppa, Sm1llee      |
|            6 |     5444 | 2024-02-29 | Sashi Esport              | L   | 0.595      | -            | -                | -                | -         |    -3.14 | allu, doto, jelo, Jerppa, Sm1llee      |
|            5 |     6711 | 2024-02-03 | Heimo Esports             | L   | 0.424      | -            | -                | -                | -         |    -7.86 | allu, doto, jelo, Jerppa, Sm1llee      |
|            4 |     6723 | 2024-02-03 | yengi                     | W   | 0.424      | -            | -                | -                | -         |     1.36 | allu, doto, jelo, Jerppa, Sm1llee      |
|            3 |     7032 | 2024-01-29 | 9Pandas                   | L   | 0.392      | -            | -                | -                | -         |    -1.16 | allu, doto, jelo, Jerppa, Sm1llee      |
|            2 |     9730 | 2023-12-02 | ARCRED                    | L   | 0.004      | -            | -                | -                | -         |    -0.07 | allu, doto, jelo, Jerppa, Sm1llee      |
|            1 |     9749 | 2023-12-02 | GUN5 Esports              | W   | 0.004      | -            | -                | -                | -         |     0.02 | allu, doto, jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($917.86)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.984 | $802.70        | $789.99         |
| 2024-03-20 |      0.731 | $175.00        | $127.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
