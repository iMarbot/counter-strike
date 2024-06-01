### Roster Details<br />
Team Name: Soda Gaming<br />
Roster: 2high, lunAtic, nestee, shadiy, snatchie<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [319](../standings_global.md)<br />
Regional Rank: [193]( ../standings_europe.md)<br />
Final Rank Value:  628.6<br />
<br />
Final Rank Value (628.6) = Starting Rank Value (557.0) + Head To Head Adjustments (71.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.065[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.077<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 557.0
- 400 + ( ( 0.077 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 557.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      465 | 2024-05-22 | Grannys Knockers   | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.355 (0.132)    | 0 (0.000) |    23.65 | 2high, lunAtic, nestee, shadiy, snatchie |
|           12 |      483 | 2024-05-22 | ARCRED             | L   | 1.000      | -            | -                | -                | -         |    -5.32 | 2high, lunAtic, nestee, shadiy, snatchie |
|           11 |      495 | 2024-05-22 | V1dar Gaming       | L   | 1.000      | -            | -                | -                | -         |    -8.53 | 2high, lunAtic, nestee, shadiy, snatchie |
|           10 |      608 | 2024-05-21 | Rhyno Esports      | L   | 1.000      | -            | -                | -                | -         |    -4.47 | 2high, lunAtic, nestee, shadiy, snatchie |
|            9 |     1065 | 2024-05-16 | Endpoint           | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.718 (0.267)    | 0 (0.000) |    26.87 | 2high, lunAtic, nestee, shadiy, snatchie |
|            8 |     1688 | 2024-05-07 | Entropiq           | L   | 1.000      | -            | -                | -                | -         |   -12.73 | 2high, lunAtic, nestee, shadiy, snatchie |
|            7 |     1732 | 2024-05-06 | VaselineWorms      | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.424 (0.158)    | 0 (0.000) |    18.33 | 2high, lunAtic, nestee, shadiy, snatchie |
|            6 |     1885 | 2024-05-03 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |   -14.34 | 2high, lunAtic, nestee, shadiy, snatchie |
|            5 |     1889 | 2024-05-03 | 500                | L   | 1.000      | -            | -                | -                | -         |    -6.75 | 2high, lunAtic, nestee, shadiy, snatchie |
|            4 |     1915 | 2024-05-02 | 1win               | L   | 1.000      | -            | -                | -                | -         |    -3.37 | 2high, lunAtic, nestee, shadiy, snatchie |
|            3 |     2493 | 2024-04-21 | Grannys Knockers   | W   | 0.943      | 0.143        | 0.006 (0.001)    | 0.355 (0.048)    | 0 (0.000) |    21.67 | 2high, lunAtic, nestee, shadiy, snatchie |
|            2 |     2551 | 2024-04-20 | Rustec             | W   | 0.938      | 0.143        | 0.003 (0.000)    | 0.283 (0.038)    | 0 (0.000) |    22.96 | 2high, lunAtic, nestee, shadiy, snatchie |
|            1 |     2569 | 2024-04-20 | ENRAGE             | W   | 0.937      | 0.143        | 0.000 (0.000)    | 0.082 (0.011)    | 0 (0.000) |    13.68 | 2high, lunAtic, nestee, shadiy, snatchie |

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
