### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, HaZR, yourwombat<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [89](../standings_global.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
Final Rank Value:  895.7<br />
<br />
Final Rank Value (895.7) = Starting Rank Value (898.2) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.232[<sup>2</sup>](#table1)

The average of these factors is 0.245<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.2
- 400 + ( ( 0.245 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 898.2


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
|           42 |      525 | 2024-05-22 | KZG                 | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     7.24 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           41 |      531 | 2024-05-22 | KZG                 | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     7.72 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           40 |      823 | 2024-05-18 | Mindfreak           | L   | 1.000      | -            | -                | -                | -         |   -19.40 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           39 |      946 | 2024-05-17 | Vantage Esports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.78 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           38 |      949 | 2024-05-17 | The Art of War      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.88 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           37 |      952 | 2024-05-17 | Fk Arnd Fnd Out     | L   | 1.000      | -            | -                | -                | -         |   -28.00 | BRACE, damyo, HaZR, Roflko, yourwombat |
|           36 |     1211 | 2024-05-15 | Arcade Esports      | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.280 (0.093)    | 0 (0.000) |     6.18 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           35 |     1216 | 2024-05-15 | Arcade Esports      | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.280 (0.093)    | 0 (0.000) |     6.54 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           34 |     1907 | 2024-05-03 | FURIA Esports       | L   | 1.000      | -            | -                | -                | -         |    -2.44 | ADDICT, BRACE, damyo, HaZR, pz         |
|           33 |     2018 | 2024-05-01 | ENCE                | L   | 1.000      | -            | -                | -                | -         |    -2.66 | ADDICT, BRACE, damyo, HaZR, pz         |
|           32 |     2072 | 2024-04-30 | MOUZ                | L   | 1.000      | -            | -                | -                | -         |    -0.09 | ADDICT, BRACE, damyo, HaZR, pz         |
|           31 |     2695 | 2024-04-20 | FlyQuest            | L   | 0.935      | -            | -                | -                | -         |    -1.41 | ADDICT, BRACE, damyo, HaZR, pz         |
|           30 |     2709 | 2024-04-19 | Rooster             | W   | 0.934      | 0.143        | 0.014 (0.002)    | -                | 0 (0.000) |    12.08 | ADDICT, BRACE, damyo, HaZR, pz         |
|           29 |     2782 | 2024-04-19 | Mindfreak           | W   | 0.928      | -            | -                | -                | -         |     9.73 | ADDICT, BRACE, damyo, HaZR, pz         |
|           28 |     2791 | 2024-04-18 | Rooster             | L   | 0.927      | -            | -                | -                | -         |   -16.00 | ADDICT, BRACE, damyo, HaZR, pz         |
|           27 |     3277 | 2024-04-10 | Rooster             | W   | 0.868      | 0.333        | 0.014 (0.004)    | 0.229 (0.066)    | -         |    12.51 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           26 |     3283 | 2024-04-10 | Rooster             | L   | 0.868      | -            | -                | -                | -         |   -15.07 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           25 |     3661 | 2024-04-03 | DXA Esports         | W   | 0.822      | 0.333        | 0.005 (0.002)    | 0.196 (0.054)    | -         |     5.62 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           24 |     3665 | 2024-04-03 | DXA Esports         | W   | 0.821      | 0.333        | 0.005 (0.002)    | 0.196 (0.054)    | -         |     5.91 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           23 |     3925 | 2024-03-27 | Mindfreak           | L   | 0.775      | -            | -                | -                | -         |   -18.52 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           22 |     3927 | 2024-03-27 | Mindfreak           | W   | 0.775      | 0.333        | -                | 0.306 (0.079)    | -         |     5.73 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           21 |     4111 | 2024-03-23 | DXA Esports         | W   | 0.748      | -            | -                | -                | 1 (0.748) |     5.36 | ADDICT, BRACE, damyo, HaZR, pz         |
|           20 |     4115 | 2024-03-23 | Arcade Esports      | W   | 0.748      | -            | -                | -                | 1 (0.748) |     7.03 | ADDICT, BRACE, damyo, HaZR, pz         |
|           19 |     4247 | 2024-03-20 | Canon Event         | W   | 0.728      | -            | -                | -                | -         |     2.25 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           18 |     4248 | 2024-03-20 | Canon Event         | W   | 0.728      | -            | -                | -                | -         |     2.31 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           17 |     4449 | 2024-03-15 | Gods Reign          | L   | 0.701      | -            | -                | -                | -         |   -12.01 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           16 |     4508 | 2024-03-14 | Garuda Wisnu Voyage | W   | 0.694      | 0.435        | 0.006 (0.002)    | -                | 1 (0.694) |     2.58 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           15 |     4565 | 2024-03-14 | Aurora Gaming       | L   | 0.688      | -            | -                | -                | -         |    -1.23 | ADDICT, HaZR, pz, Valiance, yourwombat |
|           14 |     5043 | 2024-03-06 | Vantage Esports     | W   | 0.636      | 0.333        | -                | 0.226 (0.048)    | -         |     4.37 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           13 |     5049 | 2024-03-06 | Vantage Esports     | W   | 0.635      | 0.333        | -                | 0.226 (0.048)    | -         |     4.54 | ADDICT, BRACE, damyo, HaZR, yourwombat |
|           12 |     5784 | 2024-02-22 | Rooster             | L   | 0.554      | -            | -                | -                | -         |   -10.61 | ADDICT, BRACE, Hatz, HaZR, pz          |
|           11 |     5831 | 2024-02-22 | Vantage Esports     | W   | 0.548      | -            | -                | -                | -         |     3.88 | ADDICT, BRACE, Hatz, HaZR, pz          |
|           10 |     5835 | 2024-02-21 | FlyQuest            | L   | 0.547      | -            | -                | -                | -         |    -0.83 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            9 |     5897 | 2024-02-21 | FlyQuest            | L   | 0.542      | -            | -                | -                | -         |    -0.83 | ADDICT, BRACE, HaZR, pz, yourwombat    |
|            8 |     5902 | 2024-02-21 | FlyQuest            | L   | 0.542      | -            | -                | -                | -         |    -0.84 | ADDICT, BRACE, HaZR, pz, yourwombat    |
|            7 |     7494 | 2024-01-22 | Rooster             | L   | 0.342      | -            | -                | -                | -         |    -6.87 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            6 |     7498 | 2024-01-21 | FlyQuest            | L   | 0.341      | -            | -                | -                | -         |    -0.56 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            5 |     7531 | 2024-01-21 | FlyQuest            | L   | 0.335      | -            | -                | -                | -         |    -0.55 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            4 |     7543 | 2024-01-20 | Rooster             | W   | 0.333      | -            | -                | -                | -         |     3.95 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            3 |     7682 | 2024-01-19 | FlyQuest            | W   | 0.321      | 0.143        | 0.114 (0.005)    | -                | -         |     9.65 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            2 |     7686 | 2024-01-18 | DXA Esports         | W   | 0.321      | -            | -                | -                | -         |     0.58 | ADDICT, BRACE, Hatz, HaZR, pz          |
|            1 |     9721 | 2023-12-02 | Zero Tenacity       | L   | 0.005      | -            | -                | -                | -         |    -0.04 | ADDICT, BRACE, HaZR, pz, Valiance      |

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
