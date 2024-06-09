### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: brett, jason, nooz, PNDLM, sacrifice<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [132](../standings_global.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
Final Rank Value:  810.3<br />
<br />
Final Rank Value (810.3) = Starting Rank Value (952.9) + Head To Head Adjustments (-142.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.300[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 952.9
- 400 + ( ( 0.272 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 952.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |        7 | 2024-05-29 | Lore Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | brett, jason, nooz, PNDLM, sacrifice   |
|           41 |       14 | 2024-05-29 | Zero MarksMen    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.93 | brett, jason, nooz, PNDLM, sacrifice   |
|           40 |      534 | 2024-05-21 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -7.61 | brett, jason, nooz, PNDLM, sacrifice   |
|           39 |      536 | 2024-05-21 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.13 | brett, jason, nooz, PNDLM, sacrifice   |
|           38 |      544 | 2024-05-21 | Rent Money       | W   | 1.000      | 0.384        | 0.008 (0.003)    | 0.083 (0.032)    | 0 (0.000) |    13.89 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           37 |      548 | 2024-05-21 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -8.18 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           36 |      559 | 2024-05-21 | Rent Money       | L   | 1.000      | -            | -                | -                | -         |   -17.80 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           35 |      564 | 2024-05-21 | Elevate          | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.480 (0.185)    | 0 (0.000) |    18.91 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           34 |      580 | 2024-05-21 | FlyQuest RED     | W   | 1.000      | 0.384        | 0.016 (0.006)    | 0.220 (0.085)    | 0 (0.000) |    17.74 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           33 |      642 | 2024-05-20 | Take Flyte       | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    14.99 | brett, jason, nooz, PNDLM, sacrifice   |
|           32 |      647 | 2024-05-20 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -16.59 | brett, jason, nooz, PNDLM, sacrifice   |
|           31 |      738 | 2024-05-19 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.51 | brett, jason, nooz, PNDLM, sacrifice   |
|           30 |      951 | 2024-05-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.11 | brett, jason, nooz, PNDLM, sacrifice   |
|           29 |      953 | 2024-05-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.94 | brett, jason, nooz, PNDLM, sacrifice   |
|           28 |     1031 | 2024-05-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -10.96 | brett, jason, nooz, PNDLM, sacrifice   |
|           27 |     1036 | 2024-05-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -11.89 | brett, jason, nooz, PNDLM, sacrifice   |
|           26 |     1120 | 2024-05-15 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |     6.86 | brett, jason, nooz, PNDLM, sacrifice   |
|           25 |     1133 | 2024-05-15 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | -         |     7.29 | brett, jason, nooz, PNDLM, sacrifice   |
|           24 |     1227 | 2024-05-14 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |   -11.60 | brett, jason, nooz, PNDLM, sacrifice   |
|           23 |     1233 | 2024-05-14 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |   -12.61 | brett, jason, nooz, PNDLM, sacrifice   |
|           22 |     1552 | 2024-05-09 | Limitless        | W   | 1.000      | 0.477        | -                | 0.123 (0.059)    | -         |     8.40 | brett, jason, nooz, PNDLM, sacrifice   |
|           21 |     1558 | 2024-05-09 | Limitless        | L   | 1.000      | -            | -                | -                | -         |   -23.64 | brett, jason, nooz, PNDLM, sacrifice   |
|           20 |     2526 | 2024-04-21 | For Fun          | W   | 0.946      | 0.143        | 0.007 (0.001)    | -                | 1 (0.946) |    11.13 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           19 |     2527 | 2024-04-21 | Will to Win      | W   | 0.945      | -            | -                | -                | 1 (0.945) |     5.24 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           18 |     2530 | 2024-04-21 | dot Stats        | W   | 0.945      | -            | -                | -                | 1 (0.945) |     2.13 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           17 |     3210 | 2024-04-10 | One More Esports | L   | 0.873      | -            | -                | -                | -         |   -18.99 | intra, jason, LEARSI, PNDLM, sacrifice |
|           16 |     3215 | 2024-04-10 | One More Esports | W   | 0.873      | 0.477        | 0.005 (0.002)    | 0.166 (0.069)    | -         |     8.28 | intra, jason, LEARSI, PNDLM, sacrifice |
|           15 |     3553 | 2024-04-04 | BOSS             | L   | 0.833      | -            | -                | -                | -         |   -14.34 | intra, jason, LEARSI, PNDLM, sacrifice |
|           14 |     3555 | 2024-04-04 | BOSS             | L   | 0.832      | -            | -                | -                | -         |   -15.42 | intra, jason, LEARSI, PNDLM, sacrifice |
|           13 |     4456 | 2024-03-15 | NRG              | L   | 0.700      | -            | -                | -                | -         |   -12.40 | intra, jason, LEARSI, PNDLM, sacrifice |
|           12 |     4459 | 2024-03-15 | NRG              | W   | 0.700      | 0.477        | 0.010 (0.003)    | 0.555 (0.185)    | -         |     9.77 | intra, jason, LEARSI, PNDLM, sacrifice |
|           11 |     4900 | 2024-03-07 | LAG Gaming       | L   | 0.647      | -            | -                | -                | -         |   -10.19 | intra, jason, LEARSI, PNDLM, sacrifice |
|           10 |     4908 | 2024-03-07 | LAG Gaming       | W   | 0.646      | 0.477        | 0.013 (0.004)    | 0.335 (0.103)    | -         |    10.40 | intra, jason, LEARSI, PNDLM, sacrifice |
|            9 |     5741 | 2024-02-23 | Limitless        | L   | 0.560      | -            | -                | -                | -         |   -13.54 | intra, jason, LEARSI, PNDLM, sacrifice |
|            8 |     5844 | 2024-02-21 | One More Esports | L   | 0.546      | -            | -                | -                | -         |   -12.26 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     6138 | 2024-02-16 | Mythic           | L   | 0.513      | -            | -                | -                | -         |   -11.36 | intra, jason, LEARSI, PNDLM, sacrifice |
|            6 |     6141 | 2024-02-16 | LAG Gaming       | W   | 0.512      | 0.143        | 0.013 (0.001)    | -                | -         |     8.12 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     6188 | 2024-02-15 | Revenge Nation   | W   | 0.506      | 0.143        | 0.019 (0.001)    | -                | -         |     3.54 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     6253 | 2024-02-14 | Mythic           | L   | 0.500      | -            | -                | -                | -         |   -11.37 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     6254 | 2024-02-14 | Mythic           | L   | 0.500      | -            | -                | -                | -         |   -11.76 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     7226 | 2024-01-26 | LAG Gaming       | L   | 0.373      | -            | -                | -                | -         |    -6.14 | intra, Jason, LEARSI, PNDLM, sacrifice |
|            1 |     7233 | 2024-01-26 | The Nomads       | W   | 0.372      | -            | -                | -                | -         |     0.78 | intra, Jason, LEARSI, PNDLM, sacrifice |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,064.38)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,200.00      | $1,200.00       |
| 2024-05-21 |      1.000 | $3,750.00      | $3,750.00       |
| 2024-04-21 |      0.946 | $4,347.98      | $4,114.38       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
