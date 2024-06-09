### Roster Details<br />
Team Name: L&G<br />
Roster: kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [136](../standings_global.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
Final Rank Value:  805.9<br />
<br />
Final Rank Value (805.9) = Starting Rank Value (724.0) + Head To Head Adjustments (81.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 724.0
- 400 + ( ( 0.159 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 724.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       62 | 2024-05-29 | Part Timers        | W   | 1.000      | 0.333        | 0.001 (0.000)    | 0.218 (0.073)    | 0 (0.000) |    10.83 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           27 |      754 | 2024-05-19 | Permitta Esports   | L   | 1.000      | -            | -                | -                | -         |   -13.64 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           26 |      772 | 2024-05-19 | ENTERPRISE esports | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.898 (0.128)    | 0 (0.000) |    20.49 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           25 |      785 | 2024-05-19 | ENRAGE             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.46 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           24 |      897 | 2024-05-18 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |   -18.05 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           23 |      906 | 2024-05-18 | GOT                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.11 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           22 |     1396 | 2024-05-12 | Quixal             | W   | 1.000      | 0.143        | -                | 0.245 (0.035)    | 0 (0.000) |    10.27 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           21 |     1402 | 2024-05-12 | Wolves eSports     | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     7.41 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           20 |     1469 | 2024-05-11 | SACRAMENTO         | L   | 1.000      | -            | -                | -                | -         |   -21.05 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           19 |     1476 | 2024-05-11 | Wolves eSports     | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     7.73 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           18 |     1485 | 2024-05-11 | yengi              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.04 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           17 |     1851 | 2024-05-04 | los kogutos        | L   | 1.000      | -            | -                | -                | -         |   -11.92 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           16 |     1900 | 2024-05-03 | Lazer Cats         | W   | 1.000      | 0.289        | 0.003 (0.001)    | 0.228 (0.066)    | 0 (0.000) |    12.48 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           15 |     1940 | 2024-05-02 | XI Esport          | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.277 (0.080)    | 0 (0.000) |    10.64 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           14 |     2005 | 2024-05-01 | SINNERS Academy    | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.227 (0.066)    | -         |    10.73 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           13 |     2099 | 2024-04-29 | EP Genesis         | W   | 0.997      | 0.289        | -                | 0.208 (0.060)    | -         |     7.24 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           12 |     2135 | 2024-04-28 | XI Esport          | L   | 0.990      | -            | -                | -                | -         |   -19.67 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           11 |     2427 | 2024-04-24 | 777 Esports        | W   | 0.963      | 0.289        | 0.029 (0.008)    | 0.463 (0.129)    | -         |    14.30 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           10 |     2616 | 2024-04-20 | Lazer Cats         | W   | 0.937      | 0.143        | 0.003 (0.000)    | 0.228 (0.031)    | -         |    13.21 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            9 |     2642 | 2024-04-20 | ESportsBattle      | W   | 0.936      | -            | -                | -                | -         |     6.16 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            8 |     2691 | 2024-04-20 | lajtbitexe         | W   | 0.935      | -            | -                | -                | -         |     8.97 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            7 |     3752 | 2024-03-31 | Lazer Cats         | W   | 0.802      | 0.143        | 0.003 (0.000)    | -                | -         |    11.35 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            6 |     3771 | 2024-03-30 | FAVBET Team        | L   | 0.796      | -            | -                | -                | -         |    -6.24 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            5 |     3903 | 2024-03-27 | FAVBET Team        | L   | 0.777      | -            | -                | -                | -         |    -7.46 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            4 |     3966 | 2024-03-26 | ZEROvariant        | W   | 0.771      | -            | -                | -                | -         |     5.25 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            3 |     4042 | 2024-03-24 | DASH               | W   | 0.757      | 0.143        | -                | 0.385 (0.042)    | -         |    11.67 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            2 |     4366 | 2024-03-17 | kONO.ECF           | L   | 0.711      | -            | -                | -                | -         |    -5.53 | crickey, kr1vda, marat2k, OneUn1que, somnium |
|            1 |     4368 | 2024-03-17 | nomatter           | W   | 0.710      | -            | -                | -                | -         |     5.16 | crickey, kr1vda, marat2k, OneUn1que, somnium |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,793.34)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-20 |      0.937 | $627.86        | $588.45         |
| 2024-03-31 |      0.803 | $255.27        | $204.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
