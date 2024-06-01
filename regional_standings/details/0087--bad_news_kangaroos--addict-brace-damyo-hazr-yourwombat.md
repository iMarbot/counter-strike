### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, HaZR, yourwombat<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [87](../standings_global.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
Final Rank Value:  894.9<br />
<br />
Final Rank Value (894.9) = Starting Rank Value (898.4) + Head To Head Adjustments (-3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.232[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.4
- 400 + ( ( 0.245 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 898.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      518 | 2024-05-22 | KZG                 | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     7.56 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           39 |      524 | 2024-05-22 | KZG                 | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     8.07 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           38 |      811 | 2024-05-18 | Mindfreak           | L   | 1.000      | -            | -                | -                | -         |   -19.42 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           37 |      934 | 2024-05-17 | Vantage Esports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.00 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           36 |      937 | 2024-05-17 | The Art of War      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.89 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           35 |      940 | 2024-05-17 | Fk Arnd Fnd Out     | L   | 1.000      | -            | -                | -                | -         |   -27.98 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           34 |     1201 | 2024-05-15 | Arcade Esports      | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.264 (0.088)    | 0 (0.000) |     6.47 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           33 |     1206 | 2024-05-15 | Arcade Esports      | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.264 (0.088)    | 0 (0.000) |     6.86 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           32 |     1882 | 2024-05-03 | FURIA Esports       | L   | 1.000      | -            | -                | -                | -         |    -2.42 | ADDICT, BRACE, damyo, HaZR, pz         |
|           31 |     1988 | 2024-05-01 | ENCE                | L   | 1.000      | -            | -                | -                | -         |    -2.66 | ADDICT, BRACE, damyo, HaZR, pz         |
|           30 |     2039 | 2024-04-30 | MOUZ                | L   | 1.000      | -            | -                | -                | -         |    -0.09 | ADDICT, BRACE, damyo, HaZR, pz         |
|           29 |     2641 | 2024-04-20 | FlyQuest            | L   | 0.935      | -            | -                | -                | -         |    -1.45 | ADDICT, BRACE, damyo, HaZR, pz         |
|           28 |     2655 | 2024-04-19 | Rooster             | W   | 0.934      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    11.60 | ADDICT, BRACE, damyo, HaZR, pz         |
|           27 |     2726 | 2024-04-19 | Mindfreak           | W   | 0.928      | -            | -                | -                | -         |     9.78 | ADDICT, BRACE, damyo, HaZR, pz         |
|           26 |     2735 | 2024-04-18 | Rooster             | L   | 0.927      | -            | -                | -                | -         |   -16.55 | ADDICT, BRACE, damyo, HaZR, pz         |
|           25 |     3201 | 2024-04-10 | Rooster             | W   | 0.868      | 0.333        | 0.014 (0.004)    | 0.229 (0.066)    | -         |    11.88 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           24 |     3206 | 2024-04-10 | Rooster             | L   | 0.868      | -            | -                | -                | -         |   -15.75 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           23 |     3574 | 2024-04-03 | DXA Esports         | W   | 0.822      | 0.333        | 0.005 (0.002)    | 0.196 (0.054)    | -         |     5.66 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           22 |     3577 | 2024-04-03 | DXA Esports         | W   | 0.821      | 0.333        | 0.005 (0.002)    | 0.196 (0.054)    | -         |     5.95 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           21 |     3831 | 2024-03-27 | Mindfreak           | L   | 0.775      | -            | -                | -                | -         |   -18.56 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           20 |     3832 | 2024-03-27 | Mindfreak           | W   | 0.775      | 0.333        | -                | 0.306 (0.079)    | -         |     5.69 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           19 |     4013 | 2024-03-23 | DXA Esports         | W   | 0.748      | -            | -                | -                | 1 (0.748) |     5.39 | ADDICT, BRACE, damyo, HaZR, pz         |
|           18 |     4017 | 2024-03-23 | Arcade Esports      | W   | 0.748      | -            | -                | -                | 1 (0.748) |     6.18 | ADDICT, BRACE, damyo, HaZR, pz         |
|           17 |     4145 | 2024-03-20 | Canon Event         | W   | 0.728      | -            | -                | -                | -         |     2.33 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           16 |     4146 | 2024-03-20 | Canon Event         | W   | 0.728      | -            | -                | -                | -         |     2.39 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           15 |     4342 | 2024-03-15 | Gods Reign          | L   | 0.701      | -            | -                | -                | -         |   -11.31 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           14 |     4398 | 2024-03-14 | Garuda Wisnu Voyage | W   | 0.694      | 0.435        | 0.006 (0.002)    | -                | 1 (0.694) |     2.58 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           13 |     4451 | 2024-03-14 | Aurora Gaming       | L   | 0.688      | -            | -                | -                | -         |    -1.18 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           12 |     4907 | 2024-03-06 | Vantage Esports     | W   | 0.636      | 0.333        | -                | 0.226 (0.048)    | -         |     4.13 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           11 |     4910 | 2024-03-06 | Vantage Esports     | W   | 0.635      | 0.333        | -                | 0.226 (0.048)    | -         |     4.29 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           10 |     5624 | 2024-02-22 | Rooster             | L   | 0.554      | -            | -                | -                | -         |   -10.72 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            9 |     5670 | 2024-02-22 | Vantage Esports     | W   | 0.548      | -            | -                | -                | -         |     3.66 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            8 |     5674 | 2024-02-21 | FlyQuest            | L   | 0.547      | -            | -                | -                | -         |    -0.85 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            7 |     7251 | 2024-01-22 | Rooster             | L   | 0.342      | -            | -                | -                | -         |    -6.92 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            6 |     7255 | 2024-01-21 | FlyQuest            | L   | 0.341      | -            | -                | -                | -         |    -0.56 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            5 |     7288 | 2024-01-21 | FlyQuest            | L   | 0.335      | -            | -                | -                | -         |    -0.55 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            4 |     7300 | 2024-01-20 | Rooster             | W   | 0.333      | -            | -                | -                | -         |     3.90 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            3 |     7435 | 2024-01-19 | FlyQuest            | W   | 0.321      | 0.143        | 0.114 (0.005)    | -                | -         |     9.64 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            2 |     7439 | 2024-01-18 | DXA Esports         | W   | 0.321      | -            | -                | -                | -         |     0.58 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            1 |     9439 | 2023-12-02 | Zero Tenacity       | L   | 0.005      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, HaZR, pz, Valiance      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,450.76)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-03-23 |      0.748 | $3,257.96      | $2,438.26       |
| 2024-03-16 |      0.703 | $5,000.00      | $3,512.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
