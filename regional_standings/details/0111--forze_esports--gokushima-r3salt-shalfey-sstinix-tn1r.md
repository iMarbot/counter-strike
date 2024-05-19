### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: gokushima, r3salt, shalfey, sstiNiX, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [111](../standings_global.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
Final Rank Value:  834.3<br />
<br />
Final Rank Value (834.3) = Starting Rank Value (777.8) + Head To Head Adjustments (56.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.367[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.8
- 400 + ( ( 0.190 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 777.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     4134 | 2024-01-30 | Sashi Esport        | L   | 0.559      | -            | -                | -                | -         |    -3.99 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           29 |     4163 | 2024-01-29 | Preasy Esport       | W   | 0.553      | 0.143        | 0.106 (0.008)    | 0.421 (0.033)    | 0 (0.000) |    12.39 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           28 |     4565 | 2024-01-20 | Preasy Esport       | L   | 0.490      | -            | -                | -                | -         |    -4.68 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           27 |     4600 | 2024-01-19 | Aurora Gaming       | W   | 0.486      | 0.143        | 1.000 (0.069)    | 0.799 (0.055)    | 0 (0.000) |    15.10 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           26 |     4665 | 2024-01-18 | HEROIC              | L   | 0.478      | -            | -                | -                | -         |    -0.10 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           25 |     5680 | 2023-12-12 | ENCE                | L   | 0.229      | -            | -                | -                | -         |    -0.12 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           24 |     5703 | 2023-12-11 | SAW                 | W   | 0.224      | 0.384        | 0.263 (0.023)    | 0.590 (0.051)    | 0 (0.000) |     6.88 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           23 |     5715 | 2023-12-10 | 3DMAX               | L   | 0.219      | -            | -                | -                | -         |    -2.12 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           22 |     5764 | 2023-12-09 | SINNERS Esports     | W   | 0.212      | 0.500        | 0.038 (0.004)    | 0.534 (0.057)    | 0 (0.000) |     4.93 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           21 |     5833 | 2023-12-08 | Apeks               | W   | 0.205      | 0.500        | 0.253 (0.026)    | 0.459 (0.047)    | 0 (0.000) |     6.25 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           20 |     5887 | 2023-12-07 | Team Spirit Academy | W   | 0.199      | 0.500        | 0.021 (0.002)    | 0.422 (0.042)    | 0 (0.000) |     3.19 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           19 |     5897 | 2023-12-07 | EYEBALLERS          | W   | 0.197      | 0.384        | 0.051 (0.004)    | 0.533 (0.040)    | 0 (0.000) |     4.42 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           18 |     5929 | 2023-12-06 | Team Space          | W   | 0.192      | 0.500        | -                | 0.201 (0.019)    | 0 (0.000) |     2.59 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           17 |     5979 | 2023-12-05 | KOI                 | W   | 0.186      | 0.500        | 0.066 (0.006)    | 0.537 (0.050)    | 0 (0.000) |     4.76 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           16 |     5992 | 2023-12-05 | Preasy Esport       | L   | 0.184      | -            | -                | -                | -         |    -1.61 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           15 |     6331 | 2023-11-28 | GODSENT             | W   | 0.137      | 0.384        | 0.026 (0.001)    | 0.423 (0.022)    | 0 (0.000) |     2.24 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           14 |     6604 | 2023-11-21 | Ex-Anonymo Esports  | W   | 0.090      | -            | -                | -                | -         |     1.38 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           13 |     6700 | 2023-11-18 | Apeks               | L   | 0.072      | -            | -                | -                | -         |    -0.07 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           12 |     6764 | 2023-11-17 | For The Win Esports | W   | 0.066      | -            | -                | -                | -         |     0.73 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           11 |     6830 | 2023-11-16 | Team Space          | W   | 0.058      | -            | -                | -                | -         |     0.81 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           10 |     6863 | 2023-11-15 | Team Space          | W   | 0.052      | -            | -                | -                | -         |     0.73 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            9 |     6868 | 2023-11-15 | TBA.ECF             | W   | 0.052      | -            | -                | -                | -         |     0.50 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            8 |     6879 | 2023-11-15 | Hatred              | W   | 0.052      | -            | -                | -                | -         |     0.40 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            7 |     6897 | 2023-11-15 | ALTERNATE aTTaX     | W   | 0.050      | 0.435        | 0.110 (0.002)    | -                | -         |     1.35 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            6 |     6984 | 2023-11-13 | Gaimin Gladiators   | L   | 0.037      | -            | -                | -                | -         |    -0.03 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|            5 |     7009 | 2023-11-12 | The Witchers        | W   | 0.031      | -            | -                | -                | -         |     0.49 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            4 |     7051 | 2023-11-11 | EYEBALLERS          | L   | 0.025      | -            | -                | -                | -         |    -0.23 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            3 |     7127 | 2023-11-09 | Zero Tenacity       | W   | 0.012      | -            | -                | -                | -         |     0.28 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            2 |     7181 | 2023-11-08 | SAW                 | W   | 0.005      | -            | -                | -                | -         |     0.16 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            1 |     7207 | 2023-11-08 | Pompa Team          | L   | 0.004      | -            | -                | -                | -         |    -0.09 | gokushima, Krad, r3salt, shalfey, tN1R    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,000.72)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.239 | $1,000.00      | $238.59         |
| 2023-12-10 |      0.219 | $12,000.00     | $2,622.78       |
| 2023-11-18 |      0.070 | $2,000.00      | $139.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
