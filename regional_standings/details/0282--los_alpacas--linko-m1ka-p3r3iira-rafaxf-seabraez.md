### Roster Details<br />
Team Name: Los Alpacas<br />
Roster: Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [282](../standings_global.md)<br />
Regional Rank: [175]( ../standings_europe.md)<br />
Final Rank Value:  629.9<br />
<br />
Final Rank Value (629.9) = Starting Rank Value (638.2) + Head To Head Adjustments (-8.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 638.2
- 400 + ( ( 0.120 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 638.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     6240 | 2023-11-29 | Wu-Tang Clan        | L   | 0.146      | -            | -                | -                | -             |    -3.13 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|           11 |     6476 | 2023-11-24 | SAW                 | L   | 0.111      | -            | -                | -                | -             |    -0.03 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|           10 |     6559 | 2023-11-22 | Inferus eSports     | L   | 0.099      | -            | -                | -                | -             |    -2.11 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            9 |     6568 | 2023-11-22 | BIG Academy         | L   | 0.098      | -            | -                | -                | -             |    -0.83 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            8 |     6622 | 2023-11-20 | Endpoint            | L   | 0.086      | -            | -                | -                | -             |    -0.63 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            7 |     6639 | 2023-11-20 | For The Win Esports | L   | 0.085      | -            | -                | -                | -             |    -1.20 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            6 |     6682 | 2023-11-19 | Rhyno Esports       | L   | 0.077      | -            | -                | -                | -             |    -0.37 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            5 |     6734 | 2023-11-18 | For The Win Esports | L   | 0.070      | -            | -                | -                | -             |    -1.00 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            4 |     6884 | 2023-11-15 | Zero Tenacity       | W   | 0.052      | 0.371        | 0.095 (0.002)    | 1.000 (0.019)    | false (0.000) |     1.41 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            3 |     6976 | 2023-11-13 | ENTERPRISE esports  | L   | 0.038      | -            | -                | -                | -             |    -0.17 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            2 |     7136 | 2023-11-09 | V1dar Gaming        | L   | 0.012      | -            | -                | -                | -             |    -0.21 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |
|            1 |     7200 | 2023-11-08 | Entropiq            | L   | 0.004      | -            | -                | -                | -             |    -0.04 | Linko, M1KA, P3R3IIRA, rafaxF, SeabraEZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($288.45)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-11-25 |      0.118 | $1,368.66      | $160.94         |
| 2023-11-19 |      0.078 | $1,637.47      | $127.51         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
