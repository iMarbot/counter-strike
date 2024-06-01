### Roster Details<br />
Team Name: JANO Esports<br />
Roster: allu, Cliqq, Jerppa, Sm1llee, Villeboe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [202](../standings_global.md)<br />
Regional Rank: [136]( ../standings_europe.md)<br />
Final Rank Value:  722.6<br />
<br />
Final Rank Value (722.6) = Starting Rank Value (776.3) + Head To Head Adjustments (-53.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.3
- 400 + ( ( 0.185 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 776.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      397 | 2024-05-23 | Passion UA             | L   | 1.000      | -            | -                | -                | -         |    -6.86 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           43 |      404 | 2024-05-23 | Entropiq               | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.220 (0.082)    | 0 (0.000) |    15.51 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           42 |      408 | 2024-05-23 | FAVBET Team            | L   | 1.000      | -            | -                | -                | -         |    -5.20 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           41 |      603 | 2024-05-21 | Tropic                 | L   | 1.000      | -            | -                | -                | -         |   -23.15 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           40 |     1071 | 2024-05-16 | LODIS                  | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |     9.45 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           39 |     1077 | 2024-05-16 | ENRAGE                 | W   | 1.000      | 0.372        | 0.000 (0.000)    | -                | 0 (0.000) |     8.10 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           38 |     1173 | 2024-05-15 | ARROW                  | L   | 1.000      | -            | -                | -                | -         |   -15.62 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           37 |     1311 | 2024-05-13 | kONO.ECF               | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.778 (0.290)    | 0 (0.000) |    23.31 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           36 |     1554 | 2024-05-09 | Raptors Esports Club   | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    21.48 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           35 |     1561 | 2024-05-09 | FLuffy Gangsters       | W   | 1.000      | 0.372        | -                | 0.315 (0.117)    | 0 (0.000) |    11.71 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           34 |     1627 | 2024-05-08 | VaselineWorms          | L   | 1.000      | -            | -                | -                | -         |   -17.25 | allu, Cliqq, Jerppa, Sm1llee, Villeboe |
|           33 |     2175 | 2024-04-27 | Sashi Esport           | L   | 0.984      | -            | -                | -                | -         |    -1.54 | allu, doto, Jerppa, juho, Sm1llee      |
|           32 |     2201 | 2024-04-27 | Heimo Esports          | L   | 0.982      | -            | -                | -                | -         |   -14.87 | allu, doto, Jerppa, juho, Sm1llee      |
|           31 |     2236 | 2024-04-26 | Sashi Esport           | L   | 0.978      | -            | -                | -                | -         |    -1.69 | allu, doto, Jerppa, juho, Sm1llee      |
|           30 |     2240 | 2024-04-26 | Preasy Esport          | L   | 0.978      | -            | -                | -                | -         |   -14.44 | allu, doto, Jerppa, juho, Sm1llee      |
|           29 |     2246 | 2024-04-26 | Static                 | W   | 0.977      | -            | -                | -                | 0 (0.000) |     7.92 | allu, doto, Jerppa, juho, Sm1llee      |
|           28 |     2252 | 2024-04-26 | 777 Esports            | L   | 0.977      | -            | -                | -                | -         |   -15.27 | allu, doto, Jerppa, juho, Sm1llee      |
|           27 |     2258 | 2024-04-26 | Esport Harte           | W   | 0.977      | -            | -                | -                | 0 (0.000) |     8.63 | allu, doto, Jerppa, juho, Sm1llee      |
|           26 |     2276 | 2024-04-26 | GamerLegion Academy    | L   | 0.976      | -            | -                | -                | -         |   -10.75 | allu, doto, Jerppa, juho, Sm1llee      |
|           25 |     2362 | 2024-04-24 | LEON Esports           | L   | 0.964      | -            | -                | -                | -         |   -16.96 | Aerial, allu, Cliqq, Jerppa, Sm1llee   |
|           24 |     2429 | 2024-04-23 | LEON Esports           | W   | 0.956      | 0.143        | 0.001 (0.000)    | 0.564 (0.077)    | 0 (0.000) |    13.19 | allu, doto, Jerppa, juho, Sm1llee      |
|           23 |     2442 | 2024-04-22 | GamerLegion Academy    | L   | 0.951      | -            | -                | -                | -         |   -11.74 | allu, doto, Jerppa, juho, Sm1llee      |
|           22 |     2584 | 2024-04-20 | HAVU Gaming            | W   | 0.936      | 0.143        | 0.004 (0.000)    | -                | 0 (0.000) |    13.15 | allu, doto, Jerppa, juho, Sm1llee      |
|           21 |     2649 | 2024-04-20 | Sangal Esports         | L   | 0.934      | -            | -                | -                | -         |    -5.76 | allu, doto, Jerppa, juho, Sm1llee      |
|           20 |     2709 | 2024-04-19 | NOM Esports            | W   | 0.929      | 0.143        | -                | 0.360 (0.048)    | -         |    11.25 | allu, doto, Jerppa, juho, Sm1llee      |
|           19 |     2870 | 2024-04-17 | RUBY                   | L   | 0.915      | -            | -                | -                | -         |    -8.08 | allu, doto, Jerppa, juho, Sm1llee      |
|           18 |     2882 | 2024-04-16 | MOUZ NXT               | L   | 0.914      | -            | -                | -                | -         |    -3.97 | allu, doto, Jerppa, juho, Sm1llee      |
|           17 |     2944 | 2024-04-15 | VP.Prodigy             | W   | 0.904      | 0.372        | 0.008 (0.003)    | 0.752 (0.253)    | -         |    17.45 | Aerial, allu, Cliqq, Jerppa, Sm1llee   |
|           16 |     2952 | 2024-04-15 | MOUZ NXT               | L   | 0.903      | -            | -                | -                | -         |    -3.58 | Aerial, allu, Cliqq, Jerppa, Sm1llee   |
|           15 |     2989 | 2024-04-14 | Heimo Esports          | L   | 0.896      | -            | -                | -                | -         |   -14.40 | allu, doto, Jerppa, juho, Sm1llee      |
|           14 |     3091 | 2024-04-12 | Zero Tenacity          | W   | 0.881      | 0.371        | 0.147 (0.048)    | 1.000 (0.326)    | -         |    21.47 | allu, doto, Jerppa, juho, Sm1llee      |
|           13 |     3315 | 2024-04-08 | Permitta Esports       | L   | 0.854      | -            | -                | -                | -         |    -7.26 | allu, doto, Jerppa, juho, Sm1llee      |
|           12 |     3399 | 2024-04-06 | Johnny Speeds          | L   | 0.843      | -            | -                | -                | -         |    -5.26 | allu, doto, Jerppa, juho, Sm1llee      |
|           11 |     4314 | 2024-03-16 | HANE                   | L   | 0.704      | -            | -                | -                | -         |   -17.88 | allu, doto, jelo, Jerppa, Sm1llee      |
|           10 |     4379 | 2024-03-15 | Regnum                 | L   | 0.697      | -            | -                | -                | -         |   -14.97 | allu, doto, jelo, Jerppa, Sm1llee      |
|            9 |     4766 | 2024-03-08 | INGLORIOUS             | W   | 0.649      | 0.384        | 0.001 (0.000)    | 0.214 (0.053)    | -         |    11.29 | allu, doto, jelo, Jerppa, Sm1llee      |
|            8 |     5048 | 2024-03-04 | Endpoint               | L   | 0.623      | -            | -                | -                | -         |    -6.14 | allu, doto, jelo, Jerppa, Sm1llee      |
|            7 |     5126 | 2024-03-02 | Gaimin Gladiators      | L   | 0.612      | -            | -                | -                | -         |    -1.20 | allu, doto, jelo, Jerppa, Sm1llee      |
|            6 |     5151 | 2024-03-02 | Linx Legacy Madagaskar | W   | 0.611      | -            | -                | -                | -         |     3.66 | allu, doto, jelo, Jerppa, Sm1llee      |
|            5 |     6508 | 2024-02-03 | Heimo Esports          | L   | 0.424      | -            | -                | -                | -         |    -7.67 | allu, doto, jelo, Jerppa, Sm1llee      |
|            4 |     6520 | 2024-02-03 | yengi                  | W   | 0.424      | -            | -                | -                | -         |     1.44 | allu, doto, jelo, Jerppa, Sm1llee      |
|            3 |     6816 | 2024-01-29 | 9Pandas                | L   | 0.392      | -            | -                | -                | -         |    -1.16 | allu, doto, jelo, Jerppa, Sm1llee      |
|            2 |     9448 | 2023-12-02 | ARCRED                 | L   | 0.004      | -            | -                | -                | -         |    -0.07 | allu, doto, jelo, Jerppa, Sm1llee      |
|            1 |     9467 | 2023-12-02 | GUN5 Esports           | W   | 0.004      | -            | -                | -                | -         |     0.03 | allu, doto, jelo, Jerppa, Sm1llee      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($915.43)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.984 | $802.70        | $789.99         |
| 2024-03-18 |      0.717 | $175.00        | $125.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
