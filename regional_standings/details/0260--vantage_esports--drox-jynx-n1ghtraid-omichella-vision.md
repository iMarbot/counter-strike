### Roster Details<br />
Team Name: Vantage Esports<br />
Roster: Drox, Jynx, N1ghtraid, Omichella, vision<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [260](../standings_global.md)<br />
Regional Rank: [37]( ../standings_asia.md)<br />
Final Rank Value:  676.8<br />
<br />
Final Rank Value (676.8) = Starting Rank Value (661.1) + Head To Head Adjustments (15.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.213[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.043[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.1
- 400 + ( ( 0.128 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 661.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      527 | 2024-05-22 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           43 |      530 | 2024-05-22 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -8.57 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           42 |      946 | 2024-05-17 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |    -7.78 | Drox, Jynx, Omichella, SkulL, vision        |
|           41 |      947 | 2024-05-17 | Arcade Esports     | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.280 (0.040)    | 0 (0.000) |    13.96 | Drox, Jynx, Omichella, SkulL, vision        |
|           40 |      950 | 2024-05-17 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |   -10.48 | Drox, Jynx, Omichella, SkulL, vision        |
|           39 |     2519 | 2024-04-22 | Mindfreak          | L   | 0.949      | -            | -                | -                | -         |   -11.65 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           38 |     2521 | 2024-04-22 | Mindfreak          | L   | 0.948      | -            | -                | -                | -         |   -12.62 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           37 |     2920 | 2024-04-17 | Arcade Esports     | L   | 0.915      | -            | -                | -                | -         |   -15.67 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           36 |     2937 | 2024-04-17 | Imports            | W   | 0.915      | -            | -                | -                | 0 (0.000) |     3.67 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           35 |     3278 | 2024-04-10 | Arcade Esports     | W   | 0.868      | 0.333        | 0.006 (0.002)    | 0.280 (0.081)    | 0 (0.000) |    12.44 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           34 |     3284 | 2024-04-10 | Arcade Esports     | W   | 0.868      | 0.333        | 0.006 (0.002)    | 0.280 (0.081)    | 0 (0.000) |    13.42 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           33 |     3657 | 2024-04-03 | KZG                | W   | 0.822      | 0.333        | 0.011 (0.003)    | 0.223 (0.061)    | 0 (0.000) |    12.14 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           32 |     3666 | 2024-04-03 | KZG                | W   | 0.821      | 0.333        | 0.011 (0.003)    | 0.223 (0.061)    | 0 (0.000) |    13.05 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           31 |     3923 | 2024-03-27 | Canon Event        | W   | 0.776      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     6.30 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           30 |     3928 | 2024-03-27 | Canon Event        | W   | 0.775      | -            | -                | -                | 0 (0.000) |     6.64 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           29 |     4629 | 2024-03-13 | DXA Esports        | L   | 0.682      | -            | -                | -                | -         |   -10.92 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           28 |     4637 | 2024-03-13 | DXA Esports        | W   | 0.682      | 0.333        | 0.005 (0.001)    | 0.196 (0.044)    | 0 (0.000) |    10.77 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           27 |     5043 | 2024-03-06 | Bad News Kangaroos | L   | 0.636      | -            | -                | -                | -         |    -4.37 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           26 |     5049 | 2024-03-06 | Bad News Kangaroos | L   | 0.635      | -            | -                | -                | -         |    -4.54 | Drox, Jynx, N1ghtraid, Omichella, vision    |
|           25 |     5831 | 2024-02-22 | Bad News Kangaroos | L   | 0.548      | -            | -                | -                | -         |    -3.88 | Drox, Omichella, SkulL, viridian, vision    |
|           24 |     5834 | 2024-02-21 | Rooster            | L   | 0.547      | -            | -                | -                | -         |    -5.59 | Drox, Omichella, SkulL, viridian, vision    |
|           23 |     5908 | 2024-02-20 | Arcade Esports     | W   | 0.541      | 0.143        | 0.006 (0.000)    | 0.280 (0.022)    | 0 (0.000) |     9.53 | Drox, Omichella, SkulL, viridian, vision    |
|           22 |     5959 | 2024-02-20 | Mindfreak          | W   | 0.535      | 0.143        | -                | 0.306 (0.023)    | -         |     9.24 | Drox, Omichella, SkulL, viridian, vision    |
|           21 |     5961 | 2024-02-20 | Blitz              | W   | 0.535      | 0.143        | -                | 0.089 (0.007)    | -         |     4.16 | Drox, Omichella, SkulL, viridian, vision    |
|           20 |     5971 | 2024-02-19 | Team RPG           | W   | 0.535      | -            | -                | -                | -         |     3.09 | Drox, Omichella, SkulL, viridian, vision    |
|           19 |     6067 | 2024-02-18 | Mindfreak          | L   | 0.522      | -            | -                | -                | -         |    -7.55 | Drox, Omichella, SkulL, viridian, vision    |
|           18 |     6071 | 2024-02-18 | LE-LUX Esports     | W   | 0.522      | -            | -                | -                | -         |     6.52 | Drox, Omichella, SkulL, viridian, vision    |
|           17 |     6078 | 2024-02-17 | Golf Club          | W   | 0.521      | -            | -                | -                | -         |     4.20 | Drox, Omichella, SkulL, viridian, vision    |
|           16 |     7321 | 2024-01-25 | Bad News Kangaroos | L   | 0.362      | -            | -                | -                | -         |    -6.21 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           15 |     7377 | 2024-01-24 | KZG                | W   | 0.355      | 0.143        | 0.011 (0.001)    | 0.223 (0.011)    | -         |     6.69 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           14 |     7385 | 2024-01-24 | WIDERALLY          | W   | 0.355      | -            | -                | -                | -         |     2.14 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           13 |     7610 | 2024-01-20 | FlyQuest           | L   | 0.328      | -            | -                | -                | -         |    -0.14 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           12 |     7621 | 2024-01-19 | StevosFirstCS2     | W   | 0.327      | -            | -                | -                | -         |     2.90 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           11 |     7685 | 2024-01-18 | Mindfreak          | L   | 0.321      | -            | -                | -                | -         |    -4.88 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           10 |     7747 | 2024-01-17 | Mindfreak          | L   | 0.314      | -            | -                | -                | -         |    -5.00 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            9 |     7841 | 2024-01-17 | FARMsim            | W   | 0.308      | -            | -                | -                | -         |     1.86 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            8 |     7846 | 2024-01-17 | Dracula Flow       | W   | 0.308      | -            | -                | -                | -         |     1.81 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            7 |     7969 | 2024-01-15 | DXA Esports        | L   | 0.295      | -            | -                | -                | -         |    -3.90 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            6 |     7979 | 2024-01-15 | Dracula Flow       | W   | 0.295      | -            | -                | -                | -         |     1.73 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            5 |     8772 | 2023-12-17 | Mindfreak          | L   | 0.102      | -            | -                | -                | -         |    -1.74 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            4 |     9024 | 2023-12-15 | DXA Esports        | W   | 0.088      | 0.270        | 0.005 (0.000)    | -                | -         |     1.62 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            3 |     9157 | 2023-12-12 | TEAM RKON          | W   | 0.068      | -            | -                | -                | -         |     0.60 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            2 |     9260 | 2023-12-10 | Golf Club          | W   | 0.055      | -            | -                | -                | -         |     0.45 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            1 |     9459 | 2023-12-07 | Dracula Flow       | W   | 0.035      | -            | -                | -                | -         |     0.21 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
