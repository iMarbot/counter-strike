### Roster Details<br />
Team Name: CYBERSHOKE Esports<br />
Roster: fen2k, FenomeN, flamie, Re1GN, sh1nejezzz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [264](../standings_global.md)<br />
Regional Rank: [170]( ../standings_europe.md)<br />
Final Rank Value:  674.0<br />
<br />
Final Rank Value (674.0) = Starting Rank Value (602.6) + Head To Head Adjustments (71.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.103[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 602.6
- 400 + ( ( 0.100 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 602.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     4484 | 2024-03-15 | Insilio                | L   | 0.698      | -            | -                | -                | -         |    -3.46 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           20 |     4728 | 2024-03-11 | kONO.ECF               | W   | 0.671      | 0.371        | 0.013 (0.003)    | 0.853 (0.213)    | 0 (0.000) |    17.18 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           19 |     4779 | 2024-03-10 | Zero Tenacity          | W   | 0.664      | 0.371        | 0.147 (0.036)    | 1.000 (0.247)    | 0 (0.000) |    18.70 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           18 |     5008 | 2024-03-06 | FAVBET Team            | L   | 0.637      | -            | -                | -                | -         |    -3.98 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           17 |     5338 | 2024-03-02 | 1win                   | L   | 0.610      | -            | -                | -                | -         |    -2.93 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           16 |     5385 | 2024-03-01 | ex-K10                 | W   | 0.603      | 0.371        | 0.005 (0.001)    | 0.517 (0.116)    | 0 (0.000) |    14.26 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           15 |     5766 | 2024-02-23 | Lausanne-Sport Esports | W   | 0.557      | 0.371        | 0.002 (0.000)    | 0.306 (0.063)    | 0 (0.000) |    11.73 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           14 |     5819 | 2024-02-22 | NOM Esports            | W   | 0.550      | 0.371        | 0.000 (0.000)    | 0.360 (0.074)    | 0 (0.000) |     8.87 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           13 |     5867 | 2024-02-21 | kONO.ECF               | L   | 0.544      | -            | -                | -                | -         |    -2.48 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           12 |     5927 | 2024-02-20 | Kappa Bar              | W   | 0.537      | 0.371        | 0.000 (0.000)    | 0.062 (0.012)    | 0 (0.000) |     6.45 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           11 |     6003 | 2024-02-19 | Team Secret            | L   | 0.531      | -            | -                | -                | -         |    -7.22 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|           10 |     6112 | 2024-02-17 | ARCRED                 | W   | 0.517      | 0.371        | 0.000 (0.000)    | 0.630 (0.121)    | 0 (0.000) |    11.85 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            9 |     6155 | 2024-02-16 | Endpoint               | L   | 0.511      | -            | -                | -                | -         |    -2.21 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            8 |     6226 | 2024-02-15 | Entropiq               | W   | 0.504      | 0.371        | 0.000 (0.000)    | 0.241 (0.045)    | 0 (0.000) |     9.80 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            7 |     6403 | 2024-02-12 | DMS                    | W   | 0.483      | 0.371        | 0.000 (0.000)    | 0.754 (0.135)    | 0 (0.000) |    10.41 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            6 |     6931 | 2024-01-31 | ex-Anonymo Esports     | L   | 0.404      | -            | -                | -                | -         |    -3.75 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            5 |     6981 | 2024-01-30 | Eternal Fire Academy   | L   | 0.397      | -            | -                | -                | -         |    -5.12 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            4 |     7799 | 2024-01-17 | Ninjas in Pyjamas      | L   | 0.311      | -            | -                | -                | -         |    -2.94 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            3 |     8109 | 2024-01-12 | LOADING                | L   | 0.278      | -            | -                | -                | -         |    -6.63 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            2 |     8246 | 2024-01-10 | ex-Anonymo Esports     | L   | 0.265      | -            | -                | -                | -         |    -3.03 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |
|            1 |     8258 | 2024-01-10 | INGLORIOUS             | W   | 0.265      | 0.143        | 0.001 (0.000)    | 0.223 (0.008)    | 0 (0.000) |     5.83 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz |

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
