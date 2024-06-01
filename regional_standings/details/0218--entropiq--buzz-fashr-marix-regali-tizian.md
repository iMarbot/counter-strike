### Roster Details<br />
Team Name: Entropiq<br />
Roster: Buzz, FASHR, Marix, regali, tiziaN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [218](../standings_global.md)<br />
Regional Rank: [147]( ../standings_europe.md)<br />
Final Rank Value:  711.0<br />
<br />
Final Rank Value (711.0) = Starting Rank Value (655.8) + Head To Head Adjustments (55.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.8
- 400 + ( ( 0.126 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 655.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      180 | 2024-05-27 | VENI VIDI VICI     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.075 (0.011)    | 0 (0.000) |    11.79 | Buzz, FASHR, Marix, regali, tiziaN |
|           20 |      192 | 2024-05-27 | brazylijski luz    | L   | 1.000      | -            | -                | -                | -         |    -9.19 | Buzz, FASHR, Marix, regali, tiziaN |
|           19 |      404 | 2024-05-23 | JANO Esports       | L   | 1.000      | -            | -                | -                | -         |   -15.51 | Buzz, FASHR, Marix, regali, tiziaN |
|           18 |      417 | 2024-05-23 | ALTERNATE aTTaX    | L   | 1.000      | -            | -                | -                | -         |    -9.06 | Buzz, FASHR, Marix, regali, tiziaN |
|           17 |      490 | 2024-05-22 | ENTERPRISE esports | L   | 1.000      | -            | -                | -                | -         |   -10.22 | Buzz, FASHR, Marix, regali, tiziaN |
|           16 |      584 | 2024-05-21 | los kogutos        | W   | 1.000      | 0.372        | 0.007 (0.002)    | 0.299 (0.111)    | 0 (0.000) |    21.41 | Buzz, FASHR, Marix, regali, tiziaN |
|           15 |      597 | 2024-05-21 | Nexus Gaming       | W   | 1.000      | 0.372        | 0.014 (0.005)    | 0.825 (0.307)    | 0 (0.000) |    21.73 | Buzz, FASHR, Marix, regali, tiziaN |
|           14 |      606 | 2024-05-21 | LEON Esports       | L   | 1.000      | -            | -                | -                | -         |   -14.65 | Buzz, FASHR, Marix, regali, tiziaN |
|           13 |      994 | 2024-05-17 | 1win               | L   | 1.000      | -            | -                | -                | -         |    -4.78 | Buzz, FASHR, Marix, regali, tiziaN |
|           12 |     1064 | 2024-05-16 | EXO Clan           | L   | 1.000      | -            | -                | -                | -         |   -10.56 | Buzz, FASHR, Marix, regali, tiziaN |
|           11 |     1076 | 2024-05-16 | GUN5 Esports       | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.326 (0.121)    | 0 (0.000) |    17.16 | Buzz, FASHR, Marix, regali, tiziaN |
|           10 |     1086 | 2024-05-16 | Nemiga Gaming      | W   | 1.000      | 0.372        | 0.366 (0.136)    | 0.830 (0.309)    | 0 (0.000) |    28.91 | Buzz, FASHR, Marix, regali, tiziaN |
|            9 |     1276 | 2024-05-14 | Permitta Esports   | W   | 1.000      | 0.372        | 0.029 (0.011)    | 1.000 (0.372)    | 0 (0.000) |    23.10 | Buzz, FASHR, Marix, regali, tiziaN |
|            8 |     1326 | 2024-05-13 | 1win               | L   | 1.000      | -            | -                | -                | -         |    -3.92 | Buzz, FASHR, Marix, regali, tiziaN |
|            7 |     1519 | 2024-05-10 | kONO.ECF           | L   | 1.000      | -            | -                | -                | -         |    -6.20 | Buzz, FASHR, Marix, regali, tiziaN |
|            6 |     1565 | 2024-05-09 | ThunderFlash       | L   | 1.000      | -            | -                | -                | -         |    -7.35 | Buzz, FASHR, Marix, regali, tiziaN |
|            5 |     1688 | 2024-05-07 | Soda Gaming        | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.134 (0.050)    | 0 (0.000) |    12.73 | Buzz, FASHR, Marix, regali, tiziaN |
|            4 |     1695 | 2024-05-07 | Johnny Speeds      | L   | 1.000      | -            | -                | -                | -         |    -3.82 | Buzz, FASHR, Marix, regali, tiziaN |
|            3 |     1716 | 2024-05-06 | DMS                | L   | 1.000      | -            | -                | -                | -         |    -8.97 | Buzz, FASHR, Marix, regali, tiziaN |
|            2 |     1744 | 2024-05-06 | EXO Clan           | W   | 1.000      | 0.333        | 0.013 (0.004)    | 0.510 (0.170)    | 0 (0.000) |    26.14 | Buzz, FASHR, Marix, regali, tiziaN |
|            1 |     1936 | 2024-05-02 | Johnny Speeds      | L   | 1.000      | -            | -                | -                | -         |    -3.49 | Buzz, FASHR, Marix, regali, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
