### Roster Details<br />
Team Name: regain<br />
Roster: dvrk, joshy, rayxts, sasha, Zucar<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [327](../standings_global.md)<br />
Regional Rank: [76]( ../standings_americas.md)<br />
Final Rank Value:  624.0<br />
<br />
Final Rank Value (624.0) = Starting Rank Value (619.1) + Head To Head Adjustments (4.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.213[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 619.1
- 400 + ( ( 0.108 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 619.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |        4 | 2024-05-29 | Akimbo Esports  | L   | 1.000      | -            | -                | -                | -         |   -10.03 | dvrk, joshy, rayxts, sasha, Zucar  |
|           19 |      955 | 2024-05-17 | M80             | L   | 1.000      | -            | -                | -                | -         |    -0.71 | dvrk, joshy, rayxts, sasha, Zucar  |
|           18 |     1030 | 2024-05-16 | G3              | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.221 (0.032)    | 0 (0.000) |    24.67 | dvrk, joshy, rayxts, sasha, Zucar  |
|           17 |     1035 | 2024-05-16 | Take Flyte      | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.354 (0.051)    | 0 (0.000) |    22.90 | dvrk, joshy, rayxts, sasha, Zucar  |
|           16 |     1042 | 2024-05-16 | StandOnBusiness | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.71 | dvrk, joshy, rayxts, sasha, Zucar  |
|           15 |     2946 | 2024-04-16 | straykids       | L   | 0.912      | -            | -                | -                | -         |   -18.42 | dvrk, joshy, rayxts, sasha, Zucar  |
|           14 |     4804 | 2024-03-09 | G3              | L   | 0.660      | -            | -                | -                | -         |   -14.08 | dvrk, joshy, rayxts, sasha, Zucar  |
|           13 |     4904 | 2024-03-07 | eefsports       | L   | 0.647      | -            | -                | -                | -         |   -10.98 | dvrk, joshy, rayxts, sasha, Zucar  |
|           12 |     7753 | 2024-01-17 | Elevate         | L   | 0.313      | -            | -                | -                | -         |    -2.05 | DYLAN, joshy, rayxts, sasha, Zucar |
|           11 |     7865 | 2024-01-16 | NRG             | L   | 0.306      | -            | -                | -                | -         |    -2.28 | DYLAN, joshy, rayxts, sasha, Zucar |
|           10 |     7944 | 2024-01-15 | FLUFFY AIMERS   | W   | 0.300      | 0.143        | 0.001 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     4.61 | DYLAN, joshy, rayxts, sasha, Zucar |
|            9 |     8155 | 2024-01-11 | For Fun         | L   | 0.273      | -            | -                | -                | -         |    -2.63 | DYLAN, joshy, rayxts, sasha, Zucar |
|            8 |     8162 | 2024-01-11 | FN Esports      | W   | 0.273      | 0.143        | 0.001 (0.000)    | 0.027 (0.001)    | 0 (0.000) |     4.23 | DYLAN, joshy, rayxts, sasha, Zucar |
|            7 |     8218 | 2024-01-10 | Hyvern          | W   | 0.267      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.90 | DYLAN, joshy, rayxts, sasha, Zucar |
|            6 |     9343 | 2023-12-08 | MIGHT           | L   | 0.047      | -            | -                | -                | -         |    -0.61 | chante, dvrk, joshy, sasha, Zucar  |
|            5 |     9402 | 2023-12-07 | Hound           | W   | 0.040      | 0.371        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.28 | chante, dvrk, joshy, sasha, Zucar  |
|            4 |     9466 | 2023-12-06 | ex-CatEvil      | W   | 0.033      | 0.371        | 0.000 (0.000)    | 0.056 (0.001)    | 0 (0.000) |     0.50 | chante, dvrk, joshy, sasha, Zucar  |
|            3 |     9531 | 2023-12-05 | Akimbo Esports  | L   | 0.027      | -            | -                | -                | -         |    -0.25 | chante, dvrk, joshy, sasha, Zucar  |
|            2 |     9692 | 2023-12-02 | Take Flyte      | L   | 0.006      | -            | -                | -                | -         |    -0.06 | dvrk, DYLAN, rayxts, sasha, Zucar  |
|            1 |     9698 | 2023-12-02 | FLUFFY AIMERS   | W   | 0.006      | 0.294        | 0.001 (0.000)    | 0.026 (0.000)    | 0 (0.000) |     0.09 | dvrk, DYLAN, rayxts, sasha, Zucar  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59.90)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
