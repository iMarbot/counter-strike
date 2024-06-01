### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: eksiver, FinigaN, lov1kus, supra, xiELO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [390](../standings_global.md)<br />
Regional Rank: [232]( ../standings_europe.md)<br />
Final Rank Value:  560.8<br />
<br />
Final Rank Value (560.8) = Starting Rank Value (522.4) + Head To Head Adjustments (38.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 522.4
- 400 + ( ( 0.060 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 522.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     6044 | 2024-02-15 | L&G                 | W   | 0.504      | 0.371        | 0.000 (0.000)    | 0.029 (0.005)    | 0 (0.000) |     7.22 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           17 |     6053 | 2024-02-15 | Insilio             | L   | 0.503      | -            | -                | -                | -         |    -1.55 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           16 |     6300 | 2024-02-09 | FAVBET Team         | W   | 0.464      | 0.371        | 0.008 (0.001)    | 0.666 (0.115)    | 0 (0.000) |    12.07 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           15 |     7118 | 2024-01-24 | RUBY                | L   | 0.357      | -            | -                | -                | -         |    -1.33 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           14 |     7122 | 2024-01-24 | FORZE Youngsters    | L   | 0.357      | -            | -                | -                | -         |    -4.12 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           13 |     7517 | 2024-01-17 | Sprout              | L   | 0.312      | -            | -                | -                | -         |    -4.57 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           12 |     7532 | 2024-01-17 | VaselineWorms       | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.424 (0.019)    | 0 (0.000) |     7.14 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           11 |     7556 | 2024-01-17 | ex-KRC Genk Esports | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.120 (0.005)    | 0 (0.000) |     6.33 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           10 |     7637 | 2024-01-16 | Endpoint            | L   | 0.305      | -            | -                | -                | -         |    -0.92 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            9 |     7679 | 2024-01-16 | 777 Esports         | W   | 0.304      | 0.143        | 0.029 (0.001)    | 0.463 (0.020)    | 0 (0.000) |     7.44 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            8 |     8002 | 2024-01-10 | HEROIC              | L   | 0.265      | -            | -                | -                | -         |    -0.01 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            7 |     8031 | 2024-01-10 | FAVBET Team         | W   | 0.264      | 0.143        | 0.008 (0.000)    | 0.666 (0.025)    | 0 (0.000) |     7.16 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            6 |     8397 | 2023-12-19 | Pera Esports        | L   | 0.117      | -            | -                | -                | -         |    -0.36 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            5 |     8400 | 2023-12-19 | Metizport           | L   | 0.116      | -            | -                | -                | -         |    -0.28 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            4 |     8404 | 2023-12-19 | Soda Gaming         | W   | 0.116      | 0.333        | 0.000 (0.000)    | 0.098 (0.004)    | 0 (0.000) |     2.33 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            3 |     8581 | 2023-12-16 | EYEBALLERS          | L   | 0.098      | -            | -                | -                | -         |    -0.31 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            2 |     8598 | 2023-12-16 | ex-sYnck            | W   | 0.097      | 0.294        | 0.000 (0.000)    | 0.206 (0.006)    | 0 (0.000) |     2.24 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            1 |     9467 | 2023-12-02 | JANO Esports        | L   | 0.004      | -            | -                | -                | -         |    -0.03 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |

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
