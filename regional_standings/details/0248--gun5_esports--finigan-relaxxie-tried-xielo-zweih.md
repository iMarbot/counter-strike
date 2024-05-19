### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: FinigaN, relaxxie, tried, xiELO, zweih<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [248](../standings_global.md)<br />
Regional Rank: [159]( ../standings_europe.md)<br />
Final Rank Value:  668.9<br />
<br />
Final Rank Value (668.9) = Starting Rank Value (617.6) + Head To Head Adjustments (51.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.6
- 400 + ( ( 0.110 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 617.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      593 | 2024-04-23 | 500                   | L   | 1.000      | -            | -                | -                | -             |    -7.06 | FinigaN, relaxxie, tried, xiELO, zweih |
|           20 |      622 | 2024-04-22 | RUBY                  | L   | 1.000      | -            | -                | -                | -             |    -5.08 | FinigaN, relaxxie, tried, xiELO, zweih |
|           19 |      707 | 2024-04-20 | Runners               | L   | 1.000      | -            | -                | -                | -             |   -26.13 | FinigaN, m1QUSE, tried, xiELO, zweih   |
|           18 |     1333 | 2024-04-08 | KOI                   | L   | 1.000      | -            | -                | -                | -             |    -3.49 | FinigaN, lov1kus, supra, tried, xiELO  |
|           17 |     1341 | 2024-04-08 | Apeks                 | L   | 1.000      | -            | -                | -                | -             |    -0.96 | FinigaN, lov1kus, supra, tried, xiELO  |
|           16 |     1376 | 2024-04-07 | VP.Prodigy            | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.762 (0.109)    | false (0.000) |    22.46 | FinigaN, SELLTER, tN1R, tried, xiELO   |
|           15 |     1604 | 2024-04-01 | GamerLegion           | L   | 0.970      | -            | -                | -                | -             |    -0.31 | FinigaN, lov1kus, supra, tried, xiELO  |
|           14 |     1815 | 2024-03-26 | FORZE Esports         | L   | 0.932      | -            | -                | -                | -             |    -2.20 | FinigaN, lov1kus, supra, tried, xiELO  |
|           13 |     2066 | 2024-03-19 | 3DMAX                 | L   | 0.884      | -            | -                | -                | -             |    -4.98 | FinigaN, lov1kus, supra, tried, xiELO  |
|           12 |     2696 | 2024-03-05 | Nemiga Gaming         | L   | 0.792      | -            | -                | -                | -             |    -0.74 | FinigaN, lov1kus, supra, tried, xiELO  |
|           11 |     2721 | 2024-03-04 | RUSH B (Russian team) | W   | 0.786      | 0.143        | 0.006 (0.001)    | 0.471 (0.053)    | false (0.000) |    15.90 | FinigaN, lov1kus, supra, tried, xiELO  |
|           10 |     2750 | 2024-03-04 | Guild Eagles          | W   | 0.786      | 0.143        | 0.037 (0.004)    | 0.586 (0.066)    | false (0.000) |    22.07 | FinigaN, lov1kus, supra, tried, xiELO  |
|            9 |     2832 | 2024-03-02 | Nexus Gaming          | L   | 0.773      | -            | -                | -                | -             |    -4.51 | FinigaN, lov1kus, supra, tried, xiELO  |
|            8 |     2845 | 2024-03-02 | Endpoint              | W   | 0.772      | 0.143        | 0.005 (0.001)    | 0.785 (0.087)    | false (0.000) |    18.37 | FinigaN, lov1kus, supra, tried, xiELO  |
|            7 |     2994 | 2024-02-28 | GenOne                | W   | 0.751      | 0.371        | 0.000 (0.000)    | 0.323 (0.090)    | false (0.000) |     9.78 | FinigaN, lov1kus, supra, tried, xiELO  |
|            6 |     3151 | 2024-02-24 | Ex-KRC Genk Esports   | W   | 0.725      | 0.371        | 0.008 (0.002)    | 0.181 (0.049)    | false (0.000) |    15.37 | FinigaN, lov1kus, supra, tried, xiELO  |
|            5 |     3213 | 2024-02-23 | V1dar Gaming          | L   | 0.718      | -            | -                | -                | -             |   -10.57 | FinigaN, lov1kus, supra, tried, xiELO  |
|            4 |     3251 | 2024-02-22 | Grindas               | L   | 0.712      | -            | -                | -                | -             |    -9.96 | FinigaN, lov1kus, supra, tried, xiELO  |
|            3 |     3300 | 2024-02-21 | RoundsGG              | L   | 0.705      | -            | -                | -                | -             |    -9.44 | FinigaN, lov1kus, supra, tried, xiELO  |
|            2 |     3307 | 2024-02-21 | VaselineWorms         | W   | 0.705      | 0.371        | 0.001 (0.000)    | 0.164 (0.043)    | false (0.000) |    11.66 | FinigaN, lov1kus, supra, tried, xiELO  |
|            1 |     3452 | 2024-02-18 | Nemiga Gaming         | W   | 0.684      | 0.371        | 0.680 (0.173)    | 0.910 (0.231)    | false (0.000) |    21.14 | FinigaN, lov1kus, supra, tried, xiELO  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
