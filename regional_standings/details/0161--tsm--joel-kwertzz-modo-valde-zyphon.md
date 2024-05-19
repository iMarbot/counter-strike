### Roster Details<br />
Team Name: TSM<br />
Roster: joel, KWERTZZ, MoDo, valde, Zyphon<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [161](../standings_global.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
Final Rank Value:  763.7<br />
<br />
Final Rank Value (763.7) = Starting Rank Value (727.3) + Head To Head Adjustments (36.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.345[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 727.3
- 400 + ( ( 0.165 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 727.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     1215 | 2024-04-10 | FORZE Esports                | L   | 1.000      | -            | -                | -                | -             |    -3.28 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           13 |     1280 | 2024-04-09 | Betera Esports               | W   | 1.000      | 0.500        | 0.036 (0.018)    | 0.315 (0.157)    | false (0.000) |    21.19 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           12 |     1480 | 2024-04-04 | 9Pandas                      | L   | 0.992      | -            | -                | -                | -             |    -2.83 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     1572 | 2024-04-02 | KOI                          | L   | 0.979      | -            | -                | -                | -             |    -4.11 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     1687 | 2024-03-28 | 9INE Academy                 | W   | 0.946      | 0.500        | 0.005 (0.002)    | 0.171 (0.081)    | false (0.000) |    11.49 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            9 |     1745 | 2024-03-27 | Metizport                    | L   | 0.938      | -            | -                | -                | -             |    -2.74 | joel, KWERTZZ, poizon, valde, Zyphon |
|            8 |     1800 | 2024-03-26 | TBA.ECF                      | W   | 0.932      | 0.143        | 0.000 (0.000)    | 0.460 (0.061)    | false (0.000) |    15.33 | joel, KWERTZZ, poizon, valde, Zyphon |
|            7 |     2034 | 2024-03-20 | VP.Prodigy                   | L   | 0.890      | -            | -                | -                | -             |    -9.46 | joel, KWERTZZ, poizon, valde, Zyphon |
|            6 |     2789 | 2024-03-03 | The Chosen Few               | L   | 0.779      | -            | -                | -                | -             |    -8.89 | joel, KWERTZZ, poizon, valde, Zyphon |
|            5 |     2798 | 2024-03-03 | Nexus Gaming                 | W   | 0.778      | 0.143        | 0.031 (0.003)    | 0.772 (0.086)    | false (0.000) |    18.47 | joel, KWERTZZ, poizon, valde, Zyphon |
|            4 |     2837 | 2024-03-02 | Balkan Bears (Romanian team) | W   | 0.773      | 0.143        | 0.000 (0.000)    | 0.027 (0.003)    | false (0.000) |     6.41 | joel, KWERTZZ, poizon, valde, Zyphon |
|            3 |     2850 | 2024-03-02 | SIUUUU                       | W   | 0.772      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.45 | joel, KWERTZZ, poizon, valde, Zyphon |
|            2 |     4801 | 2024-01-16 | RUBY                         | L   | 0.465      | -            | -                | -                | -             |    -4.56 | interz, JACKZ, joel, MoDo, valde     |
|            1 |     5033 | 2024-01-10 | HAVU Gaming                  | L   | 0.426      | -            | -                | -                | -             |    -4.02 | interz, JACKZ, joel, MoDo, valde     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
