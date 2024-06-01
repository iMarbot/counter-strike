### Roster Details<br />
Team Name: 777 Esports<br />
Roster: Affava, Hagmeister, qzr, Viktha, wenba<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [152](../standings_global.md)<br />
Regional Rank: [106]( ../standings_europe.md)<br />
Final Rank Value:  775.5<br />
<br />
Final Rank Value (775.5) = Starting Rank Value (758.2) + Head To Head Adjustments (17.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.2
- 400 + ( ( 0.176 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 758.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       73 | 2024-05-29 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -16.48 | Affava, Hagmeister, qzr, Viktha, wenba         |
|           40 |      213 | 2024-05-26 | Metizport X          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.210 (0.030)    | 0 (0.000) |    12.57 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           39 |      870 | 2024-05-18 | DMS                  | L   | 1.000      | -            | -                | -                | -         |    -9.95 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           38 |     1015 | 2024-05-17 | Team Space           | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.457 (0.065)    | 0 (0.000) |    18.78 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           37 |     1093 | 2024-05-16 | RoundsGG             | W   | 1.000      | 0.143        | -                | 0.202 (0.029)    | 0 (0.000) |     7.37 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           36 |     1142 | 2024-05-15 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -16.53 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           35 |     1433 | 2024-05-11 | Metizport X          | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.210 (0.030)    | 0 (0.000) |    13.14 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           34 |     2102 | 2024-04-28 | Apeks Legends        | W   | 0.990      | -            | -                | -                | 0 (0.000) |     3.44 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           33 |     2162 | 2024-04-27 | Sashi Esport         | L   | 0.984      | -            | -                | -                | -         |    -2.12 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           32 |     2185 | 2024-04-27 | Preasy Esport        | W   | 0.983      | 0.143        | 0.008 (0.001)    | 0.642 (0.090)    | 0 (0.000) |    15.43 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           31 |     2239 | 2024-04-26 | Sashi Esport         | L   | 0.978      | -            | -                | -                | -         |    -2.02 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           30 |     2245 | 2024-04-26 | Esport Harte         | W   | 0.977      | -            | -                | -                | 0 (0.000) |     7.94 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           29 |     2252 | 2024-04-26 | JANO Esports         | W   | 0.977      | 0.143        | 0.003 (0.000)    | 0.392 (0.055)    | 0 (0.000) |    15.27 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           28 |     2259 | 2024-04-26 | Preasy Esport        | L   | 0.977      | -            | -                | -                | -         |   -15.77 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           27 |     2383 | 2024-04-24 | L&G                  | L   | 0.963      | -            | -                | -                | -         |   -14.39 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           26 |     2454 | 2024-04-22 | Wizard esports       | W   | 0.950      | 0.143        | 0.004 (0.001)    | -                | 0 (0.000) |     9.65 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           25 |     2489 | 2024-04-21 | Apeks                | L   | 0.944      | -            | -                | -                | -         |   -18.50 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           24 |     2497 | 2024-04-21 | Akta mannen          | W   | 0.943      | -            | -                | -                | 0 (0.000) |     3.36 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           23 |     2517 | 2024-04-21 | EPIC DUDES           | W   | 0.942      | -            | -                | -                | -         |     3.78 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           22 |     2951 | 2024-04-15 | Metizport X          | L   | 0.904      | -            | -                | -                | -         |   -17.10 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           21 |     3023 | 2024-04-13 | En av de lette       | L   | 0.890      | -            | -                | -                | -         |   -14.93 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           20 |     3291 | 2024-04-08 | Static               | W   | 0.857      | -            | -                | -                | -         |     4.49 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           19 |     3443 | 2024-04-05 | Natus Vincere Junior | L   | 0.837      | -            | -                | -                | -         |   -14.76 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           18 |     3496 | 2024-04-04 | SINNERS Academy      | W   | 0.830      | 0.289        | 0.001 (0.000)    | 0.227 (0.055)    | -         |     7.75 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           17 |     3597 | 2024-04-02 | Preasy Esport        | W   | 0.817      | 0.289        | 0.008 (0.002)    | 0.642 (0.152)    | -         |    12.53 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           16 |     3645 | 2024-03-31 | EPIC DUDES           | W   | 0.804      | -            | -                | -                | -         |     3.00 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           15 |     3668 | 2024-03-30 | Apeks Rebels         | L   | 0.797      | -            | -                | -                | -         |   -19.87 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           14 |     3892 | 2024-03-26 | Sashi Academy        | W   | 0.770      | 0.289        | 0.001 (0.000)    | 0.088 (0.020)    | -         |     7.75 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           13 |     4029 | 2024-03-22 | Natus Vincere Junior | W   | 0.744      | 0.289        | 0.006 (0.001)    | 0.422 (0.091)    | -         |     9.40 | Affava, artstyle, Hagmeister, MadeInRed, wenba |
|           12 |     4204 | 2024-03-18 | Nordix Esport        | W   | 0.718      | -            | -                | -                | -         |     7.38 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           11 |     4248 | 2024-03-17 | INFURITY Gaming      | W   | 0.711      | -            | -                | -                | -         |     4.41 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           10 |     4489 | 2024-03-13 | Static               | W   | 0.684      | -            | -                | -                | -         |     4.18 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            9 |     4612 | 2024-03-11 | Vanir                | W   | 0.671      | -            | -                | -                | -         |     3.40 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            8 |     4653 | 2024-03-10 | Foxed Gaming         | W   | 0.664      | -            | -                | -                | -         |     3.80 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            7 |     4707 | 2024-03-09 | Cashout Cavaliers    | W   | 0.657      | -            | -                | -                | -         |     2.37 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            6 |     4866 | 2024-03-06 | INFURITY Gaming      | W   | 0.637      | -            | -                | -                | -         |     4.09 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            5 |     6198 | 2024-02-12 | INFURITY Gaming      | W   | 0.484      | -            | -                | -                | -         |     3.09 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            4 |     6420 | 2024-02-05 | Bitfix Gaming        | W   | 0.437      | -            | -                | -                | -         |     1.71 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            3 |     6614 | 2024-02-02 | Metizport            | L   | 0.417      | -            | -                | -                | -         |    -2.98 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            2 |     7679 | 2024-01-16 | GUN5 Esports         | L   | 0.304      | -            | -                | -                | -         |    -7.44 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            1 |     9373 | 2023-12-03 | Dreamchasers         | W   | 0.010      | -            | -                | -                | -         |     0.04 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,669.73)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $3,968.68      | $3,968.68       |
| 2024-04-27 |      0.984 | $2,675.66      | $2,633.29       |
| 2024-04-13 |      0.890 | $1,371.91      | $1,221.00       |
| 2024-04-05 |      0.837 | $1,000.00      | $836.94         |
| 2023-12-03 |      0.010 | $1,000.00      | $9.81           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
