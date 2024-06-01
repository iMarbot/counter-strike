### Roster Details<br />
Team Name: SNOGARD Dragons<br />
Roster: kryptoN, LapeX, mave, ND, Shairoe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [217](../standings_global.md)<br />
Regional Rank: [146]( ../standings_europe.md)<br />
Final Rank Value:  711.2<br />
<br />
Final Rank Value (711.2) = Starting Rank Value (744.0) + Head To Head Adjustments (-32.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.149[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 744.0
- 400 + ( ( 0.169 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 744.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      488 | 2024-05-22 | Wave Esports        | L   | 1.000      | -            | -                | -                | -         |   -21.71 | kryptoN, LapeX, mave, ND, Shairoe  |
|           18 |     1139 | 2024-05-15 | TeamOrangeGaming    | L   | 1.000      | -            | -                | -                | -         |   -13.25 | kryptoN, LapeX, mave, ND, Shairoe  |
|           17 |     1346 | 2024-05-12 | ALTERNATE aTTaX     | L   | 1.000      | -            | -                | -                | -         |    -7.38 | kryptoN, LapeX, mave, ND, Shairoe  |
|           16 |     1955 | 2024-05-01 | ARROW               | L   | 1.000      | -            | -                | -                | -         |   -16.02 | kryptoN, LapeX, mave, ND, Shairoe  |
|           15 |     2353 | 2024-04-24 | EVOPLAY             | W   | 0.964      | 0.143        | 0.000 (0.000)    | 0.015 (0.002)    | 0 (0.000) |     8.18 | kryptoN, LapeX, mave, ND, Shairoe  |
|           14 |     2953 | 2024-04-15 | Sissi State Punks   | W   | 0.903      | 0.143        | 0.004 (0.001)    | 0.226 (0.029)    | 0 (0.000) |    10.97 | kryptoN, LapeX, mave, ND, Shairoe  |
|           13 |     3179 | 2024-04-10 | mYinsanity          | W   | 0.870      | 0.143        | 0.001 (0.000)    | 0.124 (0.015)    | 0 (0.000) |    10.62 | kryptoN, LapeX, mave, ND, Shairoe  |
|           12 |     4279 | 2024-03-17 | ARROW               | L   | 0.710      | -            | -                | -                | -         |   -10.52 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|           11 |     4292 | 2024-03-17 | Sissi State Punks   | W   | 0.709      | 0.143        | 0.004 (0.000)    | 0.226 (0.023)    | 1 (0.709) |     8.66 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|           10 |     4321 | 2024-03-16 | TeamOrangeGaming    | W   | 0.704      | 0.143        | 0.006 (0.001)    | 0.235 (0.024)    | 1 (0.704) |    11.81 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            9 |     4415 | 2024-03-14 | Sissi State Punks   | L   | 0.691      | -            | -                | -                | -         |   -13.34 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            8 |     5025 | 2024-03-04 | TeamOrangeGaming    | W   | 0.625      | 0.143        | 0.006 (0.001)    | 0.235 (0.021)    | 0 (0.000) |    11.47 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            7 |     5062 | 2024-03-03 | ALTERNATE aTTaX Evo | L   | 0.618      | -            | -                | -                | -         |   -10.76 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            6 |     5314 | 2024-02-28 | EPIC DUDES          | W   | 0.591      | 0.143        | 0.000 (0.000)    | 0.048 (0.004)    | 0 (0.000) |     3.76 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            5 |     5646 | 2024-02-22 | EVOPLAY             | L   | 0.551      | -            | -                | -                | -         |   -11.83 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            4 |     5868 | 2024-02-18 | Wave Esports        | W   | 0.524      | 0.143        | 0.001 (0.000)    | 0.143 (0.011)    | 0 (0.000) |     5.58 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            3 |     6829 | 2024-01-29 | OTHERSCANTBEAT      | W   | 0.391      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.56 | LapeX, ND, sehza, Shairoe, SnacKZ1 |
|            2 |     9018 | 2023-12-09 | mYinsanity          | L   | 0.051      | -            | -                | -                | -         |    -1.05 | kryptoN, LapeX, MoJo, ND, sehza    |
|            1 |     9105 | 2023-12-08 | AKA HERO            | W   | 0.044      | 0.143        | 0.001 (0.000)    | 0.100 (0.001)    | 0 (0.000) |     0.45 | kryptoN, LapeX, MoJo, ND, sehza    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,281.07)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $108.57        | $108.57         |
| 2024-03-17 |      0.710 | $1,634.79      | $1,160.06       |
| 2023-12-10 |      0.058 | $215.47        | $12.45          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
