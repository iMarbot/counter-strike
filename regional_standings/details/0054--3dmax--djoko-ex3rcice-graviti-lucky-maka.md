### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [54](../standings_global.md)<br />
Regional Rank: [39]( ../standings_europe.md)<br />
Final Rank Value:  996.3<br />
<br />
Final Rank Value (996.3) = Starting Rank Value (948.4) + Head To Head Adjustments (47.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.425[<sup>2</sup>](#table1)
- Opponent Network: 0.154[<sup>2</sup>](#table1)
- LAN Wins: 0.074[<sup>2</sup>](#table1)

The average of these factors is 0.276<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 948.4
- 400 + ( ( 0.276 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 948.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      218 | 2024-05-01 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -5.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           38 |      253 | 2024-04-30 | BetBoom Team        | W   | 1.000      | 0.384        | 0.571 (0.219)    | 0.824 (0.317)    | 0 (0.000) |    28.75 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           37 |      611 | 2024-04-22 | Guild Eagles        | W   | 1.000      | 0.384        | 0.037 (0.014)    | 0.586 (0.225)    | 0 (0.000) |    18.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           36 |      931 | 2024-04-17 | Ninjas in Pyjamas   | L   | 1.000      | -            | -                | -                | -         |    -7.85 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           35 |      968 | 2024-04-17 | BLEED Esports       | W   | 1.000      | 0.384        | 0.284 (0.109)    | 0.644 (0.248)    | 0 (0.000) |    22.04 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           34 |     1073 | 2024-04-14 | BetBoom Team        | L   | 1.000      | -            | -                | -                | -         |    -2.52 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           33 |     1184 | 2024-04-11 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -16.22 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           32 |     1586 | 2024-04-02 | Permitta Esports    | W   | 0.977      | 0.384        | 0.063 (0.024)    | 1.000 (0.376)    | 0 (0.000) |    14.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           31 |     1747 | 2024-03-27 | AURA (Swedish team) | L   | 0.938      | -            | -                | -                | -         |   -25.78 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           30 |     1814 | 2024-03-26 | ILLYRIANS           | W   | 0.932      | -            | -                | -                | 0 (0.000) |     6.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka   |
|           29 |     1989 | 2024-03-21 | Fnatic              | L   | 0.898      | -            | -                | -                | -         |    -5.33 | Djoko, Ex3rcice, Lucky, Maka, NBK-      |
|           28 |     2066 | 2024-03-19 | GUN5 Esports        | W   | 0.884      | -            | -                | -                | 0 (0.000) |     4.98 | Djoko, Ex3rcice, Lucky, Maka, NBK-      |
|           27 |     2698 | 2024-03-05 | FORZE Esports       | L   | 0.792      | -            | -                | -                | -         |    -7.85 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           26 |     2740 | 2024-03-04 | GenOne              | W   | 0.786      | -            | -                | -                | 0 (0.000) |     3.22 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           25 |     2768 | 2024-03-04 | Fnatic              | L   | 0.784      | -            | -                | -                | -         |    -5.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           24 |     3538 | 2024-02-16 | 9Pandas             | L   | 0.671      | -            | -                | -                | -         |    -6.10 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           23 |     3587 | 2024-02-15 | Into The Breach     | W   | 0.665      | 0.143        | 0.022 (0.002)    | -                | 1 (0.665) |     7.48 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           22 |     3621 | 2024-02-14 | KOI                 | L   | 0.659      | -            | -                | -                | -         |    -7.57 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           21 |     3636 | 2024-02-14 | Team Falcons        | L   | 0.658      | -            | -                | -                | -         |    -1.74 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           20 |     3754 | 2024-02-11 | Apeks               | L   | 0.638      | -            | -                | -                | -         |    -1.66 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           19 |     3791 | 2024-02-09 | Fnatic              | W   | 0.625      | 0.143        | 0.334 (0.030)    | 0.683 (0.061)    | 0 (0.000) |    15.82 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           18 |     3794 | 2024-02-09 | Endpoint            | W   | 0.625      | 0.143        | -                | 0.785 (0.070)    | 0 (0.000) |     7.30 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           17 |     4144 | 2024-01-30 | Permitta Esports    | L   | 0.558      | -            | -                | -                | -         |    -7.89 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           16 |     4157 | 2024-01-29 | Team Space          | W   | 0.553      | -            | -                | -                | -         |     4.02 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           15 |     4173 | 2024-01-29 | Passion UA          | W   | 0.553      | 0.143        | 0.114 (0.009)    | 0.980 (0.077)    | -         |     9.40 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           14 |     4507 | 2024-01-21 | Preasy Esport       | L   | 0.497      | -            | -                | -                | -         |    -7.33 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           13 |     4542 | 2024-01-20 | 9Pandas             | L   | 0.492      | -            | -                | -                | -         |    -4.35 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           12 |     4564 | 2024-01-20 | Zero Tenacity       | W   | 0.490      | 0.143        | 0.095 (0.007)    | 1.000 (0.070)    | -         |     7.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           11 |     4607 | 2024-01-19 | OG                  | L   | 0.484      | -            | -                | -                | -         |    -1.75 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|           10 |     4653 | 2024-01-18 | Cloud9              | L   | 0.478      | -            | -                | -                | -         |    -0.15 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            9 |     4662 | 2024-01-18 | JANO Esports        | W   | 0.478      | -            | -                | -                | -         |     4.26 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            8 |     5715 | 2023-12-10 | FORZE Esports       | W   | 0.219      | -            | -                | -                | -         |     2.12 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            7 |     5888 | 2023-12-07 | SINNERS Esports     | W   | 0.199      | 0.500        | 0.038 (0.004)    | 0.534 (0.053)    | -         |     3.50 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            6 |     5931 | 2023-12-06 | Apeks               | W   | 0.192      | 0.500        | 0.253 (0.024)    | 0.459 (0.044)    | -         |     5.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            5 |     6462 | 2023-11-24 | GamerLegion         | L   | 0.112      | -            | -                | -                | -         |    -0.09 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            4 |     6492 | 2023-11-24 | Virtus.pro          | L   | 0.110      | -            | -                | -                | -         |    -0.05 | Djoko, Ex3rcice, hAdji, Lucky, Maka     |
|            3 |     6835 | 2023-11-16 | TSM                 | L   | 0.057      | -            | -                | -                | -         |    -1.44 | CYPHER, interz, JACKZ, MoDo, valde      |
|            2 |     6862 | 2023-11-15 | Ex-Anonymo Esports  | L   | 0.052      | -            | -                | -                | -         |    -1.20 | lunAtic, reiko, SaMey, Sobol, virtuoso  |
|            1 |     7004 | 2023-11-12 | Into The Breach     | W   | 0.031      | -            | -                | -                | -         |     0.31 | bodyy, Bymas, CRUC1AL, misutaaa, rallen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,820.60)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-04-14 |      1.000 | $4,354.95      | $4,354.95       |
| 2023-12-10 |      0.219 | $17,000.00     | $3,715.60       |
| 2023-11-26 |      0.125 | $2,000.00      | $250.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
