### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: Easy, FinigaN, SELLTER, tN1R, xiELO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [142](../standings_global.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
Final Rank Value:  790.8<br />
<br />
Final Rank Value (790.8) = Starting Rank Value (656.2) + Head To Head Adjustments (134.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.332[<sup>2</sup>](#table1)
- Opponent Network: 0.172[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.2
- 400 + ( ( 0.126 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 656.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      117 | 2024-05-28 | polizej            | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.68 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           19 |      138 | 2024-05-28 | Permitta Esports   | L   | 1.000      | -            | -                | -                | -         |   -16.09 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           18 |      233 | 2024-05-26 | DMS                | W   | 1.000      | 0.435        | 0.000 (0.000)    | 0.751 (0.326)    | 0 (0.000) |    20.50 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           17 |      294 | 2024-05-25 | ENTERPRISE esports | L   | 1.000      | -            | -                | -                | -         |   -12.79 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           16 |      333 | 2024-05-24 | SINNERS Esports    | L   | 1.000      | -            | -                | -                | -         |    -8.77 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           15 |      388 | 2024-05-23 | Team Sampi         | L   | 1.000      | -            | -                | -                | -         |    -8.73 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           14 |      496 | 2024-05-22 | Nexus Gaming       | W   | 1.000      | 0.372        | 0.014 (0.005)    | 0.825 (0.307)    | 0 (0.000) |    17.82 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           13 |      702 | 2024-05-20 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |    -7.05 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           12 |      854 | 2024-05-18 | NOM Esports        | W   | 1.000      | 0.143        | -                | 0.360 (0.051)    | 0 (0.000) |    12.48 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           11 |      900 | 2024-05-18 | Nemiga Gaming      | W   | 1.000      | 0.143        | 0.366 (0.052)    | 0.830 (0.119)    | 0 (0.000) |    27.21 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|           10 |     1010 | 2024-05-17 | 1win               | L   | 1.000      | -            | -                | -                | -         |    -6.05 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            9 |     1060 | 2024-05-16 | Team Space         | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.457 (0.065)    | 0 (0.000) |    20.62 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            8 |     1076 | 2024-05-16 | Entropiq           | L   | 1.000      | -            | -                | -                | -         |   -17.16 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            7 |     1142 | 2024-05-15 | 777 Esports        | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.463 (0.066)    | 0 (0.000) |    16.53 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            6 |     1176 | 2024-05-15 | Rhyno Esports      | W   | 1.000      | 0.372        | 0.029 (0.011)    | 0.518 (0.193)    | 0 (0.000) |    24.47 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            5 |     1257 | 2024-05-14 | Endpoint           | L   | 1.000      | -            | -                | -                | -         |    -7.86 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            4 |     1279 | 2024-05-14 | Passion UA         | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | 0 (0.000) |    24.44 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            3 |     1315 | 2024-05-13 | ARROW              | W   | 1.000      | 0.372        | 0.002 (0.001)    | 0.344 (0.128)    | 0 (0.000) |    17.55 | Easy, FinigaN, SELLTER, tN1R, xiELO  |
|            2 |     1394 | 2024-05-12 | Team PeeP          | W   | 1.000      | -            | -                | -                | -         |    10.98 | FinigaN, SELLTER, tN1R, tried, xiELO |
|            1 |     3354 | 2024-04-07 | VP.Prodigy         | W   | 0.849      | 0.143        | 0.008 (0.001)    | 0.752 (0.091)    | -         |    19.79 | FinigaN, SELLTER, tN1R, tried, xiELO |

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
