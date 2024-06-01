### Roster Details<br />
Team Name: L&G<br />
Roster: kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [134](../standings_global.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
Final Rank Value:  802.7<br />
<br />
Final Rank Value (802.7) = Starting Rank Value (722.5) + Head To Head Adjustments (80.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.5
- 400 + ( ( 0.158 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 722.5


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
|           28 |       60 | 2024-05-29 | Part Timers        | W   | 1.000      | 0.333        | 0.001 (0.000)    | 0.147 (0.049)    | 0 (0.000) |    10.39 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           27 |      742 | 2024-05-19 | Permitta Esports   | L   | 1.000      | -            | -                | -                | -         |   -14.35 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           26 |      760 | 2024-05-19 | ENTERPRISE esports | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.809 (0.116)    | 0 (0.000) |    20.06 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           25 |      773 | 2024-05-19 | ENRAGE             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.06 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           24 |      885 | 2024-05-18 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |   -18.21 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           23 |      894 | 2024-05-18 | GOT                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.94 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           22 |     1383 | 2024-05-12 | Quixal             | W   | 1.000      | 0.143        | -                | 0.245 (0.035)    | 0 (0.000) |    10.30 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           21 |     1389 | 2024-05-12 | Wolves eSports     | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     7.45 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           20 |     1456 | 2024-05-11 | SACRAMENTO         | L   | 1.000      | -            | -                | -                | -         |   -20.95 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           19 |     1463 | 2024-05-11 | Wolves eSports     | W   | 1.000      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     7.78 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           18 |     1472 | 2024-05-11 | yengi              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.07 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           17 |     1828 | 2024-05-04 | los kogutos        | L   | 1.000      | -            | -                | -                | -         |   -11.44 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           16 |     1876 | 2024-05-03 | Lazer Cats         | W   | 1.000      | 0.289        | 0.003 (0.001)    | 0.228 (0.066)    | 0 (0.000) |    12.60 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           15 |     1914 | 2024-05-02 | XI Esport          | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.277 (0.080)    | 0 (0.000) |    10.62 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           14 |     1977 | 2024-05-01 | SINNERS Academy    | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.227 (0.066)    | -         |    11.10 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           13 |     2064 | 2024-04-29 | EP Genesis         | W   | 0.997      | 0.289        | -                | 0.208 (0.060)    | -         |     7.33 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           12 |     2100 | 2024-04-28 | XI Esport          | L   | 0.990      | -            | -                | -                | -         |   -19.68 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           11 |     2383 | 2024-04-24 | 777 Esports        | W   | 0.963      | 0.289        | 0.029 (0.008)    | 0.463 (0.129)    | -         |    14.39 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           10 |     2563 | 2024-04-20 | Lazer Cats         | W   | 0.937      | 0.143        | 0.003 (0.000)    | 0.228 (0.031)    | -         |    13.34 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            9 |     2588 | 2024-04-20 | ESportsBattle      | W   | 0.936      | -            | -                | -                | -         |     6.26 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            8 |     2637 | 2024-04-20 | lajtbitexe         | W   | 0.935      | -            | -                | -                | -         |     8.26 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            7 |     3659 | 2024-03-31 | Lazer Cats         | W   | 0.802      | 0.143        | 0.003 (0.000)    | -                | -         |    11.47 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            6 |     3678 | 2024-03-30 | FAVBET Team        | L   | 0.796      | -            | -                | -                | -         |    -6.53 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            5 |     3810 | 2024-03-27 | FAVBET Team        | L   | 0.777      | -            | -                | -                | -         |    -7.81 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            4 |     3869 | 2024-03-26 | ZEROvariant        | W   | 0.771      | -            | -                | -                | -         |     5.31 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            3 |     3945 | 2024-03-24 | DASH               | W   | 0.757      | 0.143        | -                | 0.358 (0.039)    | -         |    11.36 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            2 |     4261 | 2024-03-17 | kONO.ECF           | L   | 0.711      | -            | -                | -                | -         |    -6.10 | crickey, kr1vda, marat2k, OneUn1que, somnium |
|            1 |     4263 | 2024-03-17 | nomatter           | W   | 0.710      | -            | -                | -                | -         |     5.19 | crickey, kr1vda, marat2k, OneUn1que, somnium |

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
