### Roster Details<br />
Team Name: Apeks<br />
Roster: CacaNito, jkaem, nawwk, sense, STYKO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [32](../standings_global.md)<br />
Regional Rank: [22]( ../standings_europe.md)<br />
Final Rank Value:  1231.4<br />
<br />
Final Rank Value (1231.4) = Starting Rank Value (1229.8) + Head To Head Adjustments (1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.483[<sup>1</sup>](#table2)
- Bounty Collected: 0.449[<sup>2</sup>](#table1)
- Opponent Network: 0.141[<sup>2</sup>](#table1)
- LAN Wins: 0.559[<sup>2</sup>](#table1)

The average of these factors is 0.408<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1229.8
- 400 + ( ( 0.408 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1229.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |     2171 | 2024-04-27 | MIBR               | L   | 0.986      | -            | -                | -                | -         |    -4.28 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           47 |     2326 | 2024-04-25 | Aurora Gaming      | W   | 0.974      | 0.500        | 0.492 (0.240)    | 0.573 (0.279)    | 1 (0.974) |    21.82 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           46 |     2332 | 2024-04-25 | sunday school      | W   | 0.972      | -            | -                | -                | 1 (0.972) |     1.49 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           45 |     2804 | 2024-04-18 | BetBoom Team       | L   | 0.924      | -            | -                | -                | -         |    -9.97 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           44 |     2808 | 2024-04-18 | DMS                | W   | 0.924      | 0.143        | -                | 0.754 (0.099)    | -         |     3.46 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           43 |     2818 | 2024-04-18 | AMKAL ESPORTS      | W   | 0.923      | 0.143        | 0.146 (0.019)    | 0.565 (0.075)    | -         |    12.67 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           42 |     2874 | 2024-04-17 | Insilio            | W   | 0.918      | 0.143        | -                | 0.717 (0.094)    | -         |     5.86 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           41 |     3190 | 2024-04-11 | Aurora Gaming      | L   | 0.877      | -            | -                | -                | -         |    -7.62 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           40 |     3237 | 2024-04-10 | AMKAL ESPORTS      | L   | 0.871      | -            | -                | -                | -         |   -17.11 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           39 |     3310 | 2024-04-09 | Fnatic             | W   | 0.864      | 0.143        | 0.147 (0.018)    | 0.480 (0.059)    | -         |    11.01 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           38 |     3327 | 2024-04-09 | KOI                | W   | 0.863      | -            | -                | -                | -         |     7.28 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           37 |     3362 | 2024-04-08 | Fnatic             | L   | 0.857      | -            | -                | -                | -         |   -16.14 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           36 |     3383 | 2024-04-08 | GUN5 Esports       | W   | 0.856      | -            | -                | -                | -         |     1.17 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           35 |     3646 | 2024-04-03 | Monte              | L   | 0.823      | -            | -                | -                | -         |   -12.25 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           34 |     3685 | 2024-04-02 | Aurora Gaming      | L   | 0.817      | -            | -                | -                | -         |    -7.48 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           33 |     3694 | 2024-04-02 | B8                 | W   | 0.816      | 0.143        | 0.168 (0.020)    | 0.963 (0.112)    | -         |    10.37 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           32 |     4280 | 2024-03-19 | Legacy             | L   | 0.723      | -            | -                | -                | -         |   -16.11 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           31 |     4325 | 2024-03-18 | Imperial Esports   | L   | 0.716      | -            | -                | -                | -         |    -4.73 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           30 |     4350 | 2024-03-17 | AMKAL ESPORTS      | W   | 0.711      | 1.000        | 0.146 (0.104)    | 0.565 (0.402)    | 1 (0.711) |     8.33 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           29 |     4391 | 2024-03-17 | paiN Gaming        | L   | 0.709      | -            | -                | -                | -         |    -3.13 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           28 |     4682 | 2024-03-12 | Metizport          | L   | 0.677      | -            | -                | -                | -         |   -15.67 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           27 |     4719 | 2024-03-11 | Virtus.pro         | L   | 0.671      | -            | -                | -                | -         |    -1.72 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           26 |     4743 | 2024-03-11 | KOI                | W   | 0.670      | -            | -                | -                | -         |     5.19 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           25 |     5901 | 2024-02-21 | Gaimin Gladiators  | W   | 0.542      | 0.143        | -                | 0.727 (0.056)    | 1 (0.542) |     8.69 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           24 |     5957 | 2024-02-20 | Monte              | W   | 0.536      | 0.143        | 0.181 (0.014)    | -                | 1 (0.536) |    10.49 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           23 |     5994 | 2024-02-19 | Cloud9             | L   | 0.531      | -            | -                | -                | -         |    -3.31 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           22 |     6017 | 2024-02-19 | OG                 | W   | 0.529      | 0.143        | 0.277 (0.021)    | -                | 1 (0.529) |     7.17 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           21 |     6416 | 2024-02-11 | Metizport          | L   | 0.478      | -            | -                | -                | -         |   -12.02 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           20 |     6430 | 2024-02-11 | 3DMAX              | W   | 0.477      | -            | -                | -                | -         |     2.49 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           19 |     6462 | 2024-02-10 | Metizport          | W   | 0.470      | -            | -                | -                | -         |     2.82 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           18 |     6465 | 2024-02-10 | ex-Anonymo Esports | W   | 0.469      | -            | -                | -                | -         |     0.86 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           17 |     6662 | 2024-02-04 | Natus Vincere      | L   | 0.430      | -            | -                | -                | -         |    -0.39 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           16 |     6702 | 2024-02-03 | Complexity Gaming  | L   | 0.424      | -            | -                | -                | -         |    -2.05 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           15 |     6791 | 2024-02-02 | BIG                | W   | 0.418      | 1.000        | 0.215 (0.090)    | 0.304 (0.127)    | 1 (0.418) |     9.63 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           14 |     6868 | 2024-02-01 | FURIA Esports      | W   | 0.411      | 1.000        | 0.138 (0.057)    | 0.267 (0.110)    | 1 (0.411) |     9.95 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           13 |     6932 | 2024-01-31 | Team Spirit        | L   | 0.404      | -            | -                | -                | -         |    -0.30 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           12 |     7784 | 2024-01-17 | esmagaB            | L   | 0.311      | -            | -                | -                | -         |    -8.77 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           11 |     7815 | 2024-01-17 | EC BANGA           | W   | 0.311      | -            | -                | -                | -         |     0.09 | CacaNito, jkaem, nawwk, sense, STYKO  |
|           10 |     8695 | 2023-12-17 | Virtus.pro         | L   | 0.105      | -            | -                | -                | -         |    -0.23 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            9 |     8717 | 2023-12-17 | Monte              | W   | 0.104      | 0.500        | 0.181 (0.009)    | -                | 1 (0.104) |     2.03 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            8 |     8978 | 2023-12-15 | The MongolZ        | W   | 0.092      | -            | -                | -                | 1 (0.092) |     2.60 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            7 |     8997 | 2023-12-15 | GamerLegion        | W   | 0.091      | -            | -                | -                | -         |     1.39 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            6 |     9369 | 2023-12-08 | FORZE Esports      | L   | 0.044      | -            | -                | -                | -         |    -1.33 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            5 |     9437 | 2023-12-07 | EYEBALLERS         | W   | 0.037      | -            | -                | -                | -         |     0.17 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            4 |     9502 | 2023-12-06 | 3DMAX              | L   | 0.031      | -            | -                | -                | -         |    -0.81 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            3 |     9572 | 2023-12-05 | Team Space         | W   | 0.024      | -            | -                | -                | -         |     0.08 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            2 |     9652 | 2023-12-03 | FURIA Esports      | L   | 0.010      | -            | -                | -                | -         |    -0.07 | CacaNito, jkaem, kyxsan, nawwk, sense |
|            1 |     9772 | 2023-12-02 | ENCE               | W   | 0.003      | -            | -                | -                | -         |     0.00 | CacaNito, jkaem, kyxsan, nawwk, sense |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,680.42)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      0.988 | $10,000.00     | $9,881.02       |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2024-02-11 |      0.477 | $10,000.00     | $4,769.44       |
| 2023-12-17 |      0.105 | $20,000.00     | $2,102.31       |
| 2023-12-10 |      0.058 | $8,500.00      | $488.75         |
| 2023-12-03 |      0.010 | $40,000.00     | $400.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
