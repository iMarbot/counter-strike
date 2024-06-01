### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: brett, jason, nooz, PNDLM, sacrifice<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [130](../standings_global.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
Final Rank Value:  810.5<br />
<br />
Final Rank Value (810.5) = Starting Rank Value (953.7) + Head To Head Adjustments (-143.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.300[<sup>2</sup>](#table1)

The average of these factors is 0.272<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 953.7
- 400 + ( ( 0.272 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 953.7


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
|           42 |        7 | 2024-05-29 | Lore Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.32 | brett, jason, nooz, PNDLM, sacrifice   |
|           41 |       14 | 2024-05-29 | Zero MarksMen    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.92 | brett, jason, nooz, PNDLM, sacrifice   |
|           40 |      527 | 2024-05-21 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -7.61 | brett, jason, nooz, PNDLM, sacrifice   |
|           39 |      529 | 2024-05-21 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.13 | brett, jason, nooz, PNDLM, sacrifice   |
|           38 |      536 | 2024-05-21 | Rent Money       | W   | 1.000      | 0.384        | 0.008 (0.003)    | 0.083 (0.032)    | 0 (0.000) |    13.89 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           37 |      539 | 2024-05-21 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -8.22 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           36 |      548 | 2024-05-21 | Rent Money       | L   | 1.000      | -            | -                | -                | -         |   -17.80 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           35 |      553 | 2024-05-21 | Elevate          | W   | 1.000      | 0.384        | 0.012 (0.005)    | 0.475 (0.183)    | 0 (0.000) |    18.91 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           34 |      569 | 2024-05-21 | FlyQuest RED     | W   | 1.000      | 0.384        | 0.016 (0.006)    | 0.220 (0.085)    | 0 (0.000) |    17.75 | brett, Fr3nk1e, jason, nooz, sacrifice |
|           33 |      631 | 2024-05-20 | Take Flyte       | W   | 1.000      | 0.477        | 0.006 (0.003)    | 0.354 (0.169)    | 0 (0.000) |    15.17 | brett, jason, nooz, PNDLM, sacrifice   |
|           32 |      636 | 2024-05-20 | Take Flyte       | L   | 1.000      | -            | -                | -                | -         |   -16.39 | brett, jason, nooz, PNDLM, sacrifice   |
|           31 |      726 | 2024-05-19 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.50 | brett, jason, nooz, PNDLM, sacrifice   |
|           30 |      939 | 2024-05-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.09 | brett, jason, nooz, PNDLM, sacrifice   |
|           29 |      941 | 2024-05-17 | Elevate          | L   | 1.000      | -            | -                | -                | -         |   -10.91 | brett, jason, nooz, PNDLM, sacrifice   |
|           28 |     1019 | 2024-05-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -10.96 | brett, jason, nooz, PNDLM, sacrifice   |
|           27 |     1024 | 2024-05-16 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -11.89 | brett, jason, nooz, PNDLM, sacrifice   |
|           26 |     1110 | 2024-05-15 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |     6.87 | brett, jason, nooz, PNDLM, sacrifice   |
|           25 |     1123 | 2024-05-15 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | -         |     7.31 | brett, jason, nooz, PNDLM, sacrifice   |
|           24 |     1217 | 2024-05-14 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |   -11.85 | brett, jason, nooz, PNDLM, sacrifice   |
|           23 |     1223 | 2024-05-14 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |   -12.89 | brett, jason, nooz, PNDLM, sacrifice   |
|           22 |     1537 | 2024-05-09 | Limitless        | W   | 1.000      | 0.477        | -                | 0.123 (0.059)    | -         |     8.38 | brett, jason, nooz, PNDLM, sacrifice   |
|           21 |     1543 | 2024-05-09 | Limitless        | L   | 1.000      | -            | -                | -                | -         |   -23.65 | brett, jason, nooz, PNDLM, sacrifice   |
|           20 |     2473 | 2024-04-21 | For Fun          | W   | 0.946      | 0.143        | 0.007 (0.001)    | -                | 1 (0.946) |    11.14 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           19 |     2474 | 2024-04-21 | Will to Win      | W   | 0.945      | -            | -                | -                | 1 (0.945) |     5.24 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           18 |     2477 | 2024-04-21 | dot Stats        | W   | 0.945      | -            | -                | -                | 1 (0.945) |     2.12 | ayy, brett, Fr3nk1e, jason, PNDLM      |
|           17 |     3139 | 2024-04-10 | One More Esports | L   | 0.873      | -            | -                | -                | -         |   -18.99 | intra, jason, LEARSI, PNDLM, sacrifice |
|           16 |     3144 | 2024-04-10 | One More Esports | W   | 0.873      | 0.477        | 0.005 (0.002)    | 0.166 (0.069)    | -         |     8.27 | intra, jason, LEARSI, PNDLM, sacrifice |
|           15 |     3468 | 2024-04-04 | BOSS             | L   | 0.833      | -            | -                | -                | -         |   -14.31 | intra, jason, LEARSI, PNDLM, sacrifice |
|           14 |     3470 | 2024-04-04 | BOSS             | L   | 0.832      | -            | -                | -                | -         |   -15.39 | intra, jason, LEARSI, PNDLM, sacrifice |
|           13 |     4349 | 2024-03-15 | NRG              | L   | 0.700      | -            | -                | -                | -         |   -12.41 | intra, jason, LEARSI, PNDLM, sacrifice |
|           12 |     4352 | 2024-03-15 | NRG              | W   | 0.700      | 0.477        | 0.010 (0.003)    | 0.555 (0.185)    | -         |     9.75 | intra, jason, LEARSI, PNDLM, sacrifice |
|           11 |     4772 | 2024-03-07 | LAG Gaming       | L   | 0.647      | -            | -                | -                | -         |   -10.18 | intra, jason, LEARSI, PNDLM, sacrifice |
|           10 |     4780 | 2024-03-07 | LAG Gaming       | W   | 0.646      | 0.477        | 0.013 (0.004)    | 0.335 (0.103)    | -         |    10.40 | intra, jason, LEARSI, PNDLM, sacrifice |
|            9 |     5581 | 2024-02-23 | Limitless        | L   | 0.560      | -            | -                | -                | -         |   -13.55 | intra, jason, LEARSI, PNDLM, sacrifice |
|            8 |     5683 | 2024-02-21 | One More Esports | L   | 0.546      | -            | -                | -                | -         |   -12.26 | ayy, jason, LEARSI, PNDLM, sacrifice   |
|            7 |     5965 | 2024-02-16 | Mythic           | L   | 0.513      | -            | -                | -                | -         |   -11.49 | intra, jason, LEARSI, PNDLM, sacrifice |
|            6 |     5968 | 2024-02-16 | LAG Gaming       | W   | 0.512      | 0.143        | 0.013 (0.001)    | -                | -         |     8.11 | intra, jason, LEARSI, PNDLM, sacrifice |
|            5 |     6012 | 2024-02-15 | Revenge Nation   | W   | 0.506      | 0.143        | 0.019 (0.001)    | -                | -         |     3.54 | intra, jason, LEARSI, PNDLM, sacrifice |
|            4 |     6072 | 2024-02-14 | Mythic           | L   | 0.500      | -            | -                | -                | -         |   -11.50 | intra, jason, LEARSI, PNDLM, sacrifice |
|            3 |     6073 | 2024-02-14 | Mythic           | L   | 0.500      | -            | -                | -                | -         |   -11.89 | intra, jason, LEARSI, PNDLM, sacrifice |
|            2 |     7006 | 2024-01-26 | LAG Gaming       | L   | 0.373      | -            | -                | -                | -         |    -6.14 | intra, Jason, LEARSI, PNDLM, sacrifice |
|            1 |     7013 | 2024-01-26 | The Nomads       | W   | 0.372      | -            | -                | -                | -         |     0.78 | intra, Jason, LEARSI, PNDLM, sacrifice |

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
