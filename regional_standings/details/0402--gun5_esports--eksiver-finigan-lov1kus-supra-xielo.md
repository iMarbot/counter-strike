### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: eksiver, FinigaN, lov1kus, supra, xiELO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [402](../standings_global.md)<br />
Regional Rank: [241]( ../standings_europe.md)<br />
Final Rank Value:  560.4<br />
<br />
Final Rank Value (560.4) = Starting Rank Value (524.3) + Head To Head Adjustments (36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.221[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 524.3
- 400 + ( ( 0.061 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 524.3


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
|           19 |     6225 | 2024-02-15 | L&G                 | W   | 0.504      | 0.371        | 0.000 (0.000)    | 0.029 (0.005)    | 0 (0.000) |     7.49 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           18 |     6234 | 2024-02-15 | Insilio             | L   | 0.503      | -            | -                | -                | -         |    -1.56 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           17 |     6488 | 2024-02-09 | FAVBET Team         | W   | 0.464      | 0.371        | 0.008 (0.001)    | 0.845 (0.146)    | 0 (0.000) |    12.13 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           16 |     7351 | 2024-01-24 | RUBY                | L   | 0.357      | -            | -                | -                | -         |    -1.39 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           15 |     7355 | 2024-01-24 | FORZE Youngsters    | L   | 0.357      | -            | -                | -                | -         |    -3.80 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           14 |     7357 | 2024-01-24 | Soda Gaming         | L   | 0.357      | -            | -                | -                | -         |    -3.90 | eksiver, FinigaN, lov1kus, supra, xiELO  |
|           13 |     7766 | 2024-01-17 | Sprout              | L   | 0.312      | -            | -                | -                | -         |    -4.56 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           12 |     7781 | 2024-01-17 | VaselineWorms       | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.418 (0.019)    | 0 (0.000) |     7.14 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           11 |     7805 | 2024-01-17 | ex-KRC Genk Esports | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.173 (0.008)    | 0 (0.000) |     7.08 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|           10 |     7886 | 2024-01-16 | Endpoint            | L   | 0.305      | -            | -                | -                | -         |    -0.91 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            9 |     7928 | 2024-01-16 | 777 Esports         | W   | 0.304      | 0.143        | 0.029 (0.001)    | 0.463 (0.020)    | 0 (0.000) |     7.44 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            8 |     8256 | 2024-01-10 | HEROIC              | L   | 0.265      | -            | -                | -                | -         |    -0.01 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            7 |     8285 | 2024-01-10 | FAVBET Team         | W   | 0.264      | 0.143        | 0.008 (0.000)    | 0.845 (0.032)    | 0 (0.000) |     7.17 | FinigaN, lov1kus, supra, xiELO, znxxX    |
|            6 |     8654 | 2023-12-19 | Pera Esports        | L   | 0.117      | -            | -                | -                | -         |    -0.38 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            5 |     8657 | 2023-12-19 | Metizport           | L   | 0.116      | -            | -                | -                | -         |    -0.28 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            4 |     8661 | 2023-12-19 | Soda Gaming         | W   | 0.116      | 0.333        | 0.000 (0.000)    | 0.119 (0.005)    | 0 (0.000) |     2.43 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            3 |     8841 | 2023-12-16 | EYEBALLERS          | L   | 0.098      | -            | -                | -                | -         |    -0.31 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            2 |     8859 | 2023-12-16 | ex-sYnck            | W   | 0.097      | 0.294        | 0.000 (0.000)    | 0.255 (0.007)    | 0 (0.000) |     2.34 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |
|            1 |     9749 | 2023-12-02 | JANO Esports        | L   | 0.004      | -            | -                | -                | -         |    -0.02 | FinigaN, lov1kus, ResoLuxe, supra, xiELO |

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
