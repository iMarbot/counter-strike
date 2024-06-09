### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Sliimey, supar, tucks<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [125](../standings_global.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
Final Rank Value:  820.5<br />
<br />
Final Rank Value (820.5) = Starting Rank Value (689.8) + Head To Head Adjustments (130.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.8
- 400 + ( ( 0.143 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 689.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      526 | 2024-05-22 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.92 | gump, pain, Sliimey, supar, tucks    |
|           37 |      529 | 2024-05-22 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.93 | gump, pain, Sliimey, supar, tucks    |
|           36 |      821 | 2024-05-18 | Fk Arnd Fnd Out    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.28 | gump, pain, rekonz, Sliimey, tucks   |
|           35 |      823 | 2024-05-18 | Bad News Kangaroos | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.241 (0.034)    | 0 (0.000) |    19.40 | gump, pain, rekonz, Sliimey, tucks   |
|           34 |      948 | 2024-05-17 | Fk Arnd Fnd Out    | L   | 1.000      | -            | -                | -                | -         |   -25.23 | gump, pain, rekonz, Sliimey, tucks   |
|           33 |      950 | 2024-05-17 | Vantage Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.48 | gump, pain, rekonz, Sliimey, tucks   |
|           32 |     1669 | 2024-05-08 | Arcade Esports     | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.280 (0.093)    | 0 (0.000) |    10.34 | gump, pain, Sliimey, supar, tucks    |
|           31 |     1671 | 2024-05-08 | Arcade Esports     | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.280 (0.093)    | 0 (0.000) |    11.19 | gump, pain, Sliimey, supar, tucks    |
|           30 |     2519 | 2024-04-22 | Vantage Esports    | W   | 0.949      | 0.333        | -                | 0.226 (0.071)    | 0 (0.000) |    11.65 | gump, pain, Sliimey, supar, tucks    |
|           29 |     2521 | 2024-04-22 | Vantage Esports    | W   | 0.948      | 0.333        | -                | 0.226 (0.071)    | 0 (0.000) |    12.62 | gump, pain, Sliimey, supar, tucks    |
|           28 |     2782 | 2024-04-19 | Bad News Kangaroos | L   | 0.928      | -            | -                | -                | -         |    -9.73 | gump, pain, Sliimey, supar, tucks    |
|           27 |     2790 | 2024-04-18 | FlyQuest           | L   | 0.927      | -            | -                | -                | -         |    -0.68 | gump, pain, Sliimey, supar, tucks    |
|           26 |     2853 | 2024-04-18 | DXA Esports        | W   | 0.921      | -            | -                | -                | 0 (0.000) |    10.18 | gump, pain, Sliimey, supar, tucks    |
|           25 |     2917 | 2024-04-17 | KZG                | W   | 0.915      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |    11.68 | gump, pain, Sliimey, supar, tucks    |
|           24 |     2929 | 2024-04-17 | 500x               | W   | 0.915      | -            | -                | -                | 0 (0.000) |     5.21 | gump, pain, Sliimey, supar, tucks    |
|           23 |     3275 | 2024-04-10 | DXA Esports        | W   | 0.868      | 0.333        | 0.005 (0.002)    | 0.196 (0.057)    | -         |    10.47 | gump, pain, Sliimey, supar, tucks    |
|           22 |     3281 | 2024-04-10 | DXA Esports        | W   | 0.868      | 0.333        | 0.005 (0.002)    | 0.196 (0.057)    | -         |    11.27 | gump, pain, Sliimey, supar, tucks    |
|           21 |     3660 | 2024-04-03 | Canon Event        | W   | 0.822      | -            | -                | -                | -         |     5.23 | gump, pain, Sliimey, supar, tucks    |
|           20 |     3664 | 2024-04-03 | Canon Event        | W   | 0.821      | -            | -                | -                | -         |     5.48 | gump, pain, Sliimey, supar, tucks    |
|           19 |     3925 | 2024-03-27 | Bad News Kangaroos | W   | 0.775      | 0.333        | 0.031 (0.008)    | 0.241 (0.062)    | -         |    18.52 | gump, pain, Sliimey, supar, tucks    |
|           18 |     3927 | 2024-03-27 | Bad News Kangaroos | L   | 0.775      | -            | -                | -                | -         |    -5.73 | gump, pain, Sliimey, supar, tucks    |
|           17 |     5040 | 2024-03-06 | Rooster            | L   | 0.636      | -            | -                | -                | -         |    -6.46 | Forleks, gump, Sliimey, supar, tucks |
|           16 |     5046 | 2024-03-06 | Rooster            | L   | 0.635      | -            | -                | -                | -         |    -6.79 | Forleks, gump, Sliimey, supar, tucks |
|           15 |     5899 | 2024-02-21 | KZG                | W   | 0.542      | 0.333        | 0.011 (0.002)    | 0.223 (0.040)    | -         |     8.47 | Forleks, gump, Sliimey, supar, tucks |
|           14 |     5904 | 2024-02-21 | KZG                | W   | 0.542      | 0.333        | 0.011 (0.002)    | 0.223 (0.040)    | -         |     8.88 | Forleks, gump, Sliimey, supar, tucks |
|           13 |     5959 | 2024-02-20 | Vantage Esports    | L   | 0.535      | -            | -                | -                | -         |    -9.24 | gump, Rickeh, Sliimey, supar, tucks  |
|           12 |     5966 | 2024-02-20 | TEAM RKON          | W   | 0.535      | -            | -                | -                | -         |     3.88 | gump, Rickeh, Sliimey, supar, tucks  |
|           11 |     5973 | 2024-02-19 | bbbbbb22           | W   | 0.535      | -            | -                | -                | -         |     2.60 | gump, Rickeh, Sliimey, supar, tucks  |
|           10 |     6027 | 2024-02-18 | FlyQuest           | L   | 0.528      | -            | -                | -                | -         |    -0.27 | gump, Rickeh, Sliimey, supar, tucks  |
|            9 |     6067 | 2024-02-18 | Vantage Esports    | W   | 0.522      | -            | -                | -                | -         |     7.55 | gump, Rickeh, Sliimey, supar, tucks  |
|            8 |     6075 | 2024-02-18 | gjdpdffileljhkj    | W   | 0.522      | -            | -                | -                | -         |     2.79 | gump, Rickeh, Sliimey, supar, tucks  |
|            7 |     6080 | 2024-02-17 | chessinpark        | W   | 0.521      | -            | -                | -                | -         |     2.69 | gump, Rickeh, Sliimey, supar, tucks  |
|            6 |     6313 | 2024-02-13 | KZG                | L   | 0.494      | -            | -                | -                | -         |    -7.13 | deStiny, gump, Sliimey, supar, tucks |
|            5 |     6357 | 2024-02-13 | DEMESIS            | W   | 0.488      | -            | -                | -                | -         |     2.56 | deStiny, gump, Sliimey, supar, tucks |
|            4 |     6362 | 2024-02-13 | Arcade Esports     | W   | 0.488      | -            | -                | -                | -         |     2.50 | deStiny, gump, Sliimey, supar, tucks |
|            3 |     6412 | 2024-02-11 | Bad News Kangaroos | L   | 0.481      | -            | -                | -                | -         |    -8.46 | dangeR, gump, Sliimey, supar, tucks  |
|            2 |     6438 | 2024-02-11 | KZG                | W   | 0.475      | 0.143        | 0.011 (0.001)    | -                | -         |     8.09 | dangeR, gump, Sliimey, supar, tucks  |
|            1 |     6588 | 2024-02-06 | Chinggis Warriors  | W   | 0.442      | -            | -                | -                | -         |     2.30 | dangeR, gump, Sliimey, supar, tucks  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($129.86)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
