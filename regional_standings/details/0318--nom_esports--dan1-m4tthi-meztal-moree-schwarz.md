### Roster Details<br />
Team Name: NOM Esports<br />
Roster: dan1, m4tthi, meztal, MOREE, Schwarz<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [318](../standings_global.md)<br />
Regional Rank: [50]( ../standings_asia.md)<br />
Final Rank Value:  631.9<br />
<br />
Final Rank Value (631.9) = Starting Rank Value (628.0) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 628.0
- 400 + ( ( 0.112 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 628.0


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
|           50 |      102 | 2024-05-29 | LEON Esports         | L   | 1.000      | -            | -                | -                | -         |   -10.34 | dan1, m4tthi, meztal, MOREE, Schwarz  |
|           49 |      229 | 2024-05-26 | Dynamo Eclot         | L   | 1.000      | -            | -                | -                | -         |    -6.57 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           48 |      266 | 2024-05-25 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -10.44 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           47 |      362 | 2024-05-24 | Verdant              | L   | 1.000      | -            | -                | -                | -         |    -6.08 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           46 |      500 | 2024-05-22 | HyperSpirit          | L   | 1.000      | -            | -                | -                | -         |   -10.99 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           45 |      511 | 2024-05-22 | DASH                 | L   | 1.000      | -            | -                | -                | -         |   -15.63 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           44 |      678 | 2024-05-20 | RoundsGG             | L   | 1.000      | -            | -                | -                | -         |   -20.72 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           43 |      866 | 2024-05-18 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -12.24 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           42 |      966 | 2024-05-17 | Rare Atom            | W   | 1.000      | 0.143        | 0.022 (0.003)    | -                | 0 (0.000) |    22.68 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           41 |     1266 | 2024-05-14 | Kappa Bar            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.45 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           40 |     1304 | 2024-05-14 | Heimo Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.25 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           39 |     1346 | 2024-05-13 | Rare Atom            | L   | 1.000      | -            | -                | -                | -         |    -6.92 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           38 |     1494 | 2024-05-11 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |    -6.28 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           37 |     1520 | 2024-05-10 | ADEPTS               | L   | 1.000      | -            | -                | -                | -         |   -15.11 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           36 |     1577 | 2024-05-09 | TopTab Club          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.97 | dan1, davie, hotd0g, m4tthi, meztal   |
|           35 |     1599 | 2024-05-09 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.70 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           34 |     1713 | 2024-05-07 | Viperio              | L   | 1.000      | -            | -                | -                | -         |   -13.50 | dan1, eku, hotd0g, m4tthi, meztal     |
|           33 |     1793 | 2024-05-05 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.47 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           32 |     1835 | 2024-05-04 | 1win                 | L   | 1.000      | -            | -                | -                | -         |    -5.57 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           31 |     1918 | 2024-05-03 | UNiTY esports        | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | 0 (0.000) |    23.02 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           30 |     2081 | 2024-04-30 | GamerLegion Academy  | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | 0 (0.000) |    23.03 | dan1, eku, hotd0g, meztal, MOREE      |
|           29 |     2317 | 2024-04-26 | Preasy Esport        | W   | 0.975      | 0.333        | 0.008 (0.003)    | 0.705 (0.229)    | 0 (0.000) |    18.27 | dan1, eku, hotd0g, meztal, MOREE      |
|           28 |     2765 | 2024-04-19 | JANO Esports         | L   | 0.929      | -            | -                | -                | -         |   -11.29 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           27 |     2829 | 2024-04-18 | RUBY                 | L   | 0.923      | -            | -                | -                | -         |    -5.05 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           26 |     2912 | 2024-04-17 | Team Sampi           | W   | 0.916      | 0.143        | 0.039 (0.005)    | 0.677 (0.089)    | 0 (0.000) |    25.36 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           25 |     3288 | 2024-04-10 | Viperio              | L   | 0.868      | -            | -                | -                | -         |   -10.91 | jce, m4tthi, meztal, MOREE, stressarN |
|           24 |     3846 | 2024-03-28 | ROSOMAHA             | L   | 0.782      | -            | -                | -                | -         |   -15.05 | aidKiT, dan1, meztal, MOREE, shushan  |
|           23 |     4113 | 2024-03-23 | Illuminar Gaming     | L   | 0.748      | -            | -                | -                | -         |    -7.62 | aidKiT, dan1, meztal, MOREE, shushan  |
|           22 |     4759 | 2024-03-11 | MOUZ NXT             | L   | 0.668      | -            | -                | -                | -         |    -1.90 | dan1, Libido, meztal, MOREE, ultimate |
|           21 |     4860 | 2024-03-09 | Astralis Talent      | W   | 0.656      | 0.303        | 0.012 (0.002)    | 0.452 (0.090)    | 0 (0.000) |    16.23 | dan1, Libido, meztal, MOREE, ultimate |
|           20 |     4897 | 2024-03-08 | Natus Vincere Junior | W   | 0.648      | 0.303        | 0.010 (0.002)    | 0.290 (0.057)    | 0 (0.000) |    14.50 | dan1, Libido, meztal, MOREE, ultimate |
|           19 |     4960 | 2024-03-07 | MOUZ NXT             | L   | 0.642      | -            | -                | -                | -         |    -1.42 | dan1, Libido, meztal, MOREE, ultimate |
|           18 |     5173 | 2024-03-04 | KamKom               | L   | 0.625      | -            | -                | -                | -         |   -15.96 | dan1, Libido, meztal, MOREE, ultimate |
|           17 |     5196 | 2024-03-04 | ENCE Academy         | W   | 0.623      | 0.303        | 0.012 (0.002)    | 0.337 (0.064)    | -         |    14.59 | dan1, Libido, meztal, MOREE, ultimate |
|           16 |     5310 | 2024-03-02 | ex-Sprout            | L   | 0.611      | -            | -                | -                | -         |   -10.44 | dan1, Libido, meztal, MOREE, ultimate |
|           15 |     5375 | 2024-03-01 | Endpoint             | L   | 0.604      | -            | -                | -                | -         |    -3.67 | dan1, Libido, meztal, MOREE, ultimate |
|           14 |     5400 | 2024-02-29 | FORZE Youngsters     | W   | 0.598      | -            | -                | -                | -         |    10.20 | dan1, Libido, meztal, MOREE, ultimate |
|           13 |     5492 | 2024-02-28 | Passion UA           | W   | 0.588      | 0.303        | 0.057 (0.010)    | 1.000 (0.178)    | -         |    15.47 | dan1, Libido, meztal, MOREE, ultimate |
|           12 |     5718 | 2024-02-24 | Verdant              | W   | 0.563      | 0.303        | 0.014 (0.002)    | 1.000 (0.170)    | -         |    15.62 | dan1, Libido, meztal, MOREE, ultimate |
|           11 |     5797 | 2024-02-22 | INGLORIOUS           | W   | 0.551      | -            | -                | -                | -         |    12.03 | dan1, Libido, meztal, MOREE, ultimate |
|           10 |     5809 | 2024-02-22 | Zero Tenacity        | L   | 0.551      | -            | -                | -                | -         |    -1.67 | dan1, Libido, meztal, MOREE, ultimate |
|            9 |     5819 | 2024-02-22 | CYBERSHOKE Esports   | L   | 0.550      | -            | -                | -                | -         |    -8.87 | dan1, Libido, meztal, MOREE, ultimate |
|            8 |     5943 | 2024-02-20 | Nemiga Gaming        | L   | 0.536      | -            | -                | -                | -         |    -0.50 | dan1, Libido, meztal, MOREE, ultimate |
|            7 |     6215 | 2024-02-15 | VP.Prodigy           | L   | 0.504      | -            | -                | -                | -         |    -3.46 | dan1, Libido, meztal, MOREE, ultimate |
|            6 |     6382 | 2024-02-12 | FAVBET Team          | W   | 0.484      | 0.371        | -                | 0.845 (0.152)    | -         |    11.42 | dan1, Libido, meztal, MOREE, ultimate |
|            5 |     6397 | 2024-02-12 | HOTU                 | L   | 0.484      | -            | -                | -                | -         |    -3.21 | dan1, Libido, meztal, MOREE, ultimate |
|            4 |     6421 | 2024-02-11 | INGLORIOUS           | L   | 0.477      | -            | -                | -                | -         |    -4.89 | dan1, Libido, meztal, MOREE, ultimate |
|            3 |     6429 | 2024-02-11 | Viperio              | W   | 0.477      | -            | -                | -                | -         |     8.09 | dan1, Libido, meztal, MOREE, ultimate |
|            2 |     6457 | 2024-02-10 | Lilmix               | L   | 0.470      | -            | -                | -                | -         |    -3.35 | dan1, Libido, meztal, MOREE, ultimate |
|            1 |     8430 | 2024-01-08 | 15 Average Gaming    | L   | 0.251      | -            | -                | -                | -         |    -5.46 | dan1, meztal, MOREE, ultimate, Zax1e  |

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
