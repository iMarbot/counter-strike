### Roster Details<br />
Team Name: NOM Esports<br />
Roster: dan1, m4tthi, meztal, MOREE, Schwarz<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [315](../standings_global.md)<br />
Regional Rank: [51]( ../standings_asia.md)<br />
Final Rank Value:  629.6<br />
<br />
Final Rank Value (629.6) = Starting Rank Value (625.6) + Head To Head Adjustments (4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.6
- 400 + ( ( 0.111 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 625.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |       95 | 2024-05-29 | LEON Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.48 | dan1, m4tthi, meztal, MOREE, Schwarz  |
|           49 |      221 | 2024-05-26 | Dynamo Eclot         | L   | 1.000      | -            | -                | -                | -         |    -6.26 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           48 |      258 | 2024-05-25 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -10.10 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           47 |      353 | 2024-05-24 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -6.17 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           46 |      494 | 2024-05-22 | HyperSpirit          | L   | 1.000      | -            | -                | -                | -         |   -10.88 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           45 |      504 | 2024-05-22 | DASH                 | L   | 1.000      | -            | -                | -                | -         |   -16.47 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           44 |      667 | 2024-05-20 | RoundsGG             | L   | 1.000      | -            | -                | -                | -         |   -21.74 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           43 |      854 | 2024-05-18 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -12.48 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           42 |      954 | 2024-05-17 | Rare Atom            | W   | 1.000      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    22.68 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           41 |     1256 | 2024-05-14 | Kappa Bar            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.34 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           40 |     1293 | 2024-05-14 | Heimo Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.19 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           39 |     1334 | 2024-05-13 | Rare Atom            | L   | 1.000      | -            | -                | -                | -         |    -6.92 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           38 |     1481 | 2024-05-11 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |    -6.50 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           37 |     1507 | 2024-05-10 | ADEPTS               | L   | 1.000      | -            | -                | -                | -         |   -14.14 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           36 |     1562 | 2024-05-09 | TopTab Club          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.02 | dan1, davie, hotd0g, m4tthi, meztal   |
|           35 |     1583 | 2024-05-09 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.72 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           34 |     1693 | 2024-05-07 | Viperio              | L   | 1.000      | -            | -                | -                | -         |   -13.55 | dan1, eku, hotd0g, m4tthi, meztal     |
|           33 |     1770 | 2024-05-05 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.47 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           32 |     1812 | 2024-05-04 | 1win                 | L   | 1.000      | -            | -                | -                | -         |    -5.43 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           31 |     1893 | 2024-05-03 | UNiTY esports        | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | 0 (0.000) |    23.39 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           30 |     2047 | 2024-04-30 | GamerLegion Academy  | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | 0 (0.000) |    23.06 | dan1, eku, hotd0g, meztal, MOREE      |
|           29 |     2280 | 2024-04-26 | Preasy Esport        | W   | 0.975      | 0.333        | 0.008 (0.003)    | 0.642 (0.209)    | 0 (0.000) |    18.16 | dan1, eku, hotd0g, meztal, MOREE      |
|           28 |     2709 | 2024-04-19 | JANO Esports         | L   | 0.929      | -            | -                | -                | -         |   -11.25 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           27 |     2773 | 2024-04-18 | RUBY                 | L   | 0.923      | -            | -                | -                | -         |    -5.06 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           26 |     2855 | 2024-04-17 | Team Sampi           | W   | 0.916      | 0.143        | 0.039 (0.005)    | 0.665 (0.087)    | 0 (0.000) |    25.31 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           25 |     3210 | 2024-04-10 | Viperio              | L   | 0.868      | -            | -                | -                | -         |   -10.96 | jce, m4tthi, meztal, MOREE, stressarN |
|           24 |     3753 | 2024-03-28 | ROSOMAHA             | L   | 0.782      | -            | -                | -                | -         |   -15.35 | aidKiT, dan1, meztal, MOREE, shushan  |
|           23 |     4015 | 2024-03-23 | Illuminar Gaming     | L   | 0.748      | -            | -                | -                | -         |    -7.59 | aidKiT, dan1, meztal, MOREE, shushan  |
|           22 |     4636 | 2024-03-11 | MOUZ NXT             | L   | 0.668      | -            | -                | -                | -         |    -2.03 | dan1, Libido, meztal, MOREE, ultimate |
|           21 |     4735 | 2024-03-09 | Astralis Talent      | W   | 0.656      | 0.303        | 0.012 (0.002)    | 0.452 (0.090)    | 0 (0.000) |    16.21 | dan1, Libido, meztal, MOREE, ultimate |
|           20 |     4769 | 2024-03-08 | Natus Vincere Junior | W   | 0.648      | 0.303        | 0.010 (0.002)    | 0.290 (0.057)    | 0 (0.000) |    14.48 | dan1, Libido, meztal, MOREE, ultimate |
|           19 |     4829 | 2024-03-07 | MOUZ NXT             | L   | 0.642      | -            | -                | -                | -         |    -1.53 | dan1, Libido, meztal, MOREE, ultimate |
|           18 |     5027 | 2024-03-04 | KamKom               | L   | 0.625      | -            | -                | -                | -         |   -15.95 | dan1, Libido, meztal, MOREE, ultimate |
|           17 |     5050 | 2024-03-04 | ENCE Academy         | W   | 0.623      | 0.303        | 0.012 (0.002)    | 0.337 (0.064)    | -         |    14.57 | dan1, Libido, meztal, MOREE, ultimate |
|           16 |     5162 | 2024-03-02 | ex-Sprout            | L   | 0.611      | -            | -                | -                | -         |   -10.40 | dan1, Libido, meztal, MOREE, ultimate |
|           15 |     5226 | 2024-03-01 | Endpoint             | L   | 0.604      | -            | -                | -                | -         |    -3.69 | dan1, Libido, meztal, MOREE, ultimate |
|           14 |     5251 | 2024-02-29 | FORZE Youngsters     | W   | 0.598      | -            | -                | -                | -         |     9.34 | dan1, Libido, meztal, MOREE, ultimate |
|           13 |     5340 | 2024-02-28 | Passion UA           | W   | 0.588      | 0.303        | 0.057 (0.010)    | 1.000 (0.178)    | -         |    15.36 | dan1, Libido, meztal, MOREE, ultimate |
|           12 |     5558 | 2024-02-24 | Verdant              | W   | 0.563      | 0.303        | 0.014 (0.002)    | 1.000 (0.170)    | -         |    15.58 | dan1, Libido, meztal, MOREE, ultimate |
|           11 |     5637 | 2024-02-22 | INGLORIOUS           | W   | 0.551      | -            | -                | -                | -         |    11.94 | dan1, Libido, meztal, MOREE, ultimate |
|           10 |     5649 | 2024-02-22 | Zero Tenacity        | L   | 0.551      | -            | -                | -                | -         |    -1.55 | dan1, Libido, meztal, MOREE, ultimate |
|            9 |     5659 | 2024-02-22 | CYBERSHOKE Esports   | L   | 0.550      | -            | -                | -                | -         |    -6.27 | dan1, Libido, meztal, MOREE, ultimate |
|            8 |     5774 | 2024-02-20 | Nemiga Gaming        | L   | 0.536      | -            | -                | -                | -         |    -0.47 | dan1, Libido, meztal, MOREE, ultimate |
|            7 |     6036 | 2024-02-15 | VP.Prodigy           | L   | 0.504      | -            | -                | -                | -         |    -3.70 | dan1, Libido, meztal, MOREE, ultimate |
|            6 |     6195 | 2024-02-12 | FAVBET Team          | W   | 0.484      | 0.371        | -                | 0.666 (0.120)    | -         |    11.39 | dan1, Libido, meztal, MOREE, ultimate |
|            5 |     6210 | 2024-02-12 | HOTU                 | L   | 0.484      | -            | -                | -                | -         |    -3.33 | dan1, Libido, meztal, MOREE, ultimate |
|            4 |     6233 | 2024-02-11 | INGLORIOUS           | L   | 0.477      | -            | -                | -                | -         |    -4.93 | dan1, Libido, meztal, MOREE, ultimate |
|            3 |     6241 | 2024-02-11 | Viperio              | W   | 0.477      | -            | -                | -                | -         |     7.88 | dan1, Libido, meztal, MOREE, ultimate |
|            2 |     6269 | 2024-02-10 | Lilmix               | L   | 0.470      | -            | -                | -                | -         |    -3.11 | dan1, Libido, meztal, MOREE, ultimate |
|            1 |     8176 | 2024-01-08 | 15 Average Gaming    | L   | 0.251      | -            | -                | -                | -         |    -5.43 | dan1, meztal, MOREE, ultimate, Zax1e  |

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
