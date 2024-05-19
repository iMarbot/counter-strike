### Roster Details<br />
Team Name: KUUSAMO.gg<br />
Roster: 8Juho8, epik, joeski, Puteli, rbm<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [170](../standings_global.md)<br />
Regional Rank: [114]( ../standings_europe.md)<br />
Final Rank Value:  755.7<br />
<br />
Final Rank Value (755.7) = Starting Rank Value (795.7) + Head To Head Adjustments (-39.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.252[<sup>2</sup>](#table1)

The average of these factors is 0.199<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 795.7
- 400 + ( ( 0.199 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 795.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      484 | 2024-04-25 | XI Esport          | L   | 1.000      | -            | -                | -                | -         |   -20.32 | 8Juho8, epik, joeski, Puteli, rbm |
|           10 |      635 | 2024-04-21 | DUSTY              | W   | 1.000      | 0.289        | 0.015 (0.004)    | 0.233 (0.067)    | 0 (0.000) |    12.85 | 8Juho8, epik, joeski, Puteli, rbm |
|            9 |      948 | 2024-04-17 | XI Esport          | L   | 1.000      | -            | -                | -                | -         |   -20.64 | 8Juho8, epik, joeski, Puteli, rbm |
|            8 |     1906 | 2024-03-23 | Johnny Speeds      | L   | 0.912      | -            | -                | -                | -         |   -11.00 | 8Juho8, epik, joeski, Puteli, rbm |
|            7 |     1907 | 2024-03-23 | KILLBOX            | W   | 0.911      | 0.143        | 0.000 (0.000)    | 0.032 (0.004)    | 0 (0.000) |     4.66 | 8Juho8, epik, joeski, Puteli, rbm |
|            6 |     1912 | 2024-03-23 | RektGeT            | W   | 0.911      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.90 | 8Juho8, epik, joeski, Puteli, rbm |
|            5 |     2868 | 2024-03-02 | ENCE Prospects     | W   | 0.772      | 0.143        | 0.003 (0.000)    | 0.027 (0.003)    | 1 (0.772) |     8.27 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            4 |     2897 | 2024-03-02 | SatulanHaistelijat | W   | 0.770      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.770) |     2.60 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            3 |     3203 | 2024-02-23 | RoundsGG           | L   | 0.719      | -            | -                | -                | -         |   -13.19 | 8Juho8, epik, joeski, Puteli, rbm |
|            2 |     3208 | 2024-02-23 | ENCE Prospects     | W   | 0.719      | 0.143        | 0.003 (0.000)    | 0.027 (0.003)    | 1 (0.719) |     7.60 | 8Juho8, epik, joeski, Puteli, rbm |
|            1 |     3239 | 2024-02-22 | RoundsGG           | L   | 0.712      | -            | -                | -                | -         |   -13.65 | 8Juho8, epik, joeski, Puteli, rbm |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($837.56)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
