### Roster Details<br />
Team Name: SoJoga<br />
Roster: alove, Farw, Patoz1k, pkN, telezin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [361](../standings_global.md)<br />
Regional Rank: [92]( ../standings_americas.md)<br />
Final Rank Value:  596.6<br />
<br />
Final Rank Value (596.6) = Starting Rank Value (630.2) + Head To Head Adjustments (-33.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.2
- 400 + ( ( 0.113 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 630.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      818 | 2024-05-18 | Hawks             | L   | 1.000      | -            | -                | -                | -         |   -15.04 | alove, Farw, Patoz1k, pkN, telezin     |
|           16 |      825 | 2024-05-18 | CSGONET           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.084 (0.012)    | 0 (0.000) |    10.17 | alove, Farw, Patoz1k, pkN, telezin     |
|           15 |      833 | 2024-05-18 | NIGERIA 96        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | 0 (0.000) |    15.25 | alove, Farw, Patoz1k, pkN, telezin     |
|           14 |      846 | 2024-05-18 | Peak Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.74 | alove, Farw, Patoz1k, pkN, telezin     |
|           13 |     2231 | 2024-04-26 | naocopulas        | L   | 0.978      | -            | -                | -                | -         |   -20.39 | alove, Farw, Patoz1k, pkN, telezin     |
|           12 |     3063 | 2024-04-12 | eSports Recife    | L   | 0.885      | -            | -                | -                | -         |   -12.34 | Farw, Patoz1k, pkN, telezin, zhoki     |
|           11 |     3975 | 2024-03-23 | Floripa Stars     | L   | 0.751      | -            | -                | -                | -         |   -12.02 | Farw, k1not1, Patoz1k, pkN, telezin    |
|           10 |     3981 | 2024-03-23 | pugdesonesto      | W   | 0.751      | 0.143        | 0.001 (0.000)    | 0.146 (0.016)    | 0 (0.000) |    10.40 | Farw, k1not1, Patoz1k, pkN, telezin    |
|            9 |     3993 | 2024-03-23 | Full House Gaming | L   | 0.751      | -            | -                | -                | -         |   -11.37 | arcz, balencyy, lucky-, RoDfps_, shun7 |
|            8 |     4789 | 2024-03-07 | Sharks Youngsters | L   | 0.645      | -            | -                | -                | -         |   -10.09 | Farw, k1not1, Patoz1k, pkN, telezin    |
|            7 |     5445 | 2024-02-25 | Hawks             | L   | 0.571      | -            | -                | -                | -         |    -9.15 | Colt, k1not1, Patoz1k, pkN, telezin    |
|            6 |     5476 | 2024-02-24 | phantom troupe    | W   | 0.566      | 0.143        | 0.000 (0.000)    | 0.111 (0.009)    | 0 (0.000) |     8.01 | Colt, k1not1, Patoz1k, pkN, telezin    |
|            5 |     5489 | 2024-02-24 | Salão do Corte    | W   | 0.566      | 0.143        | 0.000 (0.000)    | 0.046 (0.004)    | 0 (0.000) |     8.42 | Colt, k1not1, Patoz1k, pkN, telezin    |
|            4 |     5494 | 2024-02-24 | Fluxo Demons      | W   | 0.565      | 0.143        | 0.026 (0.002)    | 0.264 (0.021)    | 0 (0.000) |    13.45 | goddess, julih, poppins, r4ul, yungher |
|            3 |     5503 | 2024-02-24 | pugdesonesto      | W   | 0.565      | 0.143        | 0.001 (0.000)    | 0.146 (0.012)    | 0 (0.000) |     8.55 | freitas, Machado, ntx, Thuister, vzn   |
|            2 |     5508 | 2024-02-24 | Hawks             | L   | 0.564      | -            | -                | -                | -         |    -8.49 | guidimon, KUN, nacho, nasher, pablek   |
|            1 |     5520 | 2024-02-24 | QUASE             | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     5.80 | Colt, k1not1, Patoz1k, pkN, telezin    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($111.64)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
