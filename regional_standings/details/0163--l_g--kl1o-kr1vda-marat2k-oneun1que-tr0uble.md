### Roster Details<br />
Team Name: L&G<br />
Roster: kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [163](../standings_global.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
Final Rank Value:  762.8<br />
<br />
Final Rank Value (762.8) = Starting Rank Value (717.7) + Head To Head Adjustments (45.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 717.7
- 400 + ( ( 0.160 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 717.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      103 | 2024-05-03 | Lazer Cats               | W   | 1.000      | 0.289        | 0.003 (0.001)    | 0.070 (0.020)    | false (0.000) |    11.98 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           11 |      140 | 2024-05-02 | XI Esport                | W   | 1.000      | 0.289        | 0.002 (0.001)    | 0.313 (0.090)    | false (0.000) |    12.54 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|           10 |      198 | 2024-05-01 | SINNERS Academy          | W   | 1.000      | 0.289        | 0.003 (0.001)    | 0.296 (0.086)    | false (0.000) |    13.35 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            9 |      273 | 2024-04-29 | EP Genesis               | W   | 1.000      | 0.289        | 0.000 (0.000)    | 0.187 (0.054)    | false (0.000) |     8.92 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            8 |      304 | 2024-04-28 | XI Esport                | L   | 1.000      | -            | -                | -                | -             |   -17.79 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            7 |      540 | 2024-04-24 | 777 Esports              | W   | 1.000      | 0.289        | 0.032 (0.009)    | 0.550 (0.159)    | false (0.000) |    16.19 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            6 |      721 | 2024-04-20 | ESportsBattle            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.86 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            5 |     1640 | 2024-03-30 | BLESSED (Ukrainian team) | L   | 0.957      | -            | -                | -                | -             |    -6.57 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            4 |     1753 | 2024-03-27 | BLESSED (Ukrainian team) | L   | 0.938      | -            | -                | -                | -             |    -8.24 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            3 |     1806 | 2024-03-26 | ZEROvariant              | W   | 0.932      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.11 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            2 |     1861 | 2024-03-24 | DASH                     | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.251 (0.033)    | false (0.000) |    15.57 | kL1o, kr1vda, marat2k, OneUn1que, Tr0ublE    |
|            1 |     2136 | 2024-03-17 | TBA.ECF                  | L   | 0.872      | -            | -                | -                | -             |   -12.76 | crickey, kr1vda, marat2k, OneUn1que, somnium |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,873.94)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-20 |      1.000 | $627.86        | $627.86         |
| 2024-03-31 |      0.964 | $255.27        | $246.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
