### Roster Details<br />
Team Name: Mindfreak<br />
Roster: gump, pain, Sliimey, supar, tucks<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [123](../standings_global.md)<br />
Regional Rank: [14]( ../standings_asia.md)<br />
Final Rank Value:  818.7<br />
<br />
Final Rank Value (818.7) = Starting Rank Value (689.7) + Head To Head Adjustments (129.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.7
- 400 + ( ( 0.142 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 689.7


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
|           38 |      519 | 2024-05-22 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.94 | gump, pain, Sliimey, supar, tucks    |
|           37 |      522 | 2024-05-22 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.95 | gump, pain, Sliimey, supar, tucks    |
|           36 |      809 | 2024-05-18 | Fk Arnd Fnd Out    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.33 | gump, pain, rekonz, Sliimey, tucks   |
|           35 |      811 | 2024-05-18 | Bad News Kangaroos | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.241 (0.034)    | 0 (0.000) |    19.42 | gump, pain, rekonz, Sliimey, tucks   |
|           34 |      936 | 2024-05-17 | Fk Arnd Fnd Out    | L   | 1.000      | -            | -                | -                | -         |   -25.18 | gump, pain, rekonz, Sliimey, tucks   |
|           33 |      938 | 2024-05-17 | Vantage Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.45 | gump, pain, rekonz, Sliimey, tucks   |
|           32 |     1651 | 2024-05-08 | Arcade Esports     | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.264 (0.088)    | 0 (0.000) |    10.77 | gump, pain, Sliimey, supar, tucks    |
|           31 |     1653 | 2024-05-08 | Arcade Esports     | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.264 (0.088)    | 0 (0.000) |    11.68 | gump, pain, Sliimey, supar, tucks    |
|           30 |     2467 | 2024-04-22 | Vantage Esports    | W   | 0.949      | 0.333        | -                | 0.226 (0.071)    | 0 (0.000) |    10.55 | gump, pain, Sliimey, supar, tucks    |
|           29 |     2469 | 2024-04-22 | Vantage Esports    | W   | 0.948      | 0.333        | -                | 0.226 (0.071)    | 0 (0.000) |    11.40 | gump, pain, Sliimey, supar, tucks    |
|           28 |     2726 | 2024-04-19 | Bad News Kangaroos | L   | 0.928      | -            | -                | -                | -         |    -9.78 | gump, pain, Sliimey, supar, tucks    |
|           27 |     2734 | 2024-04-18 | FlyQuest           | L   | 0.927      | -            | -                | -                | -         |    -0.70 | gump, pain, Sliimey, supar, tucks    |
|           26 |     2797 | 2024-04-18 | DXA Esports        | W   | 0.921      | -            | -                | -                | 0 (0.000) |    10.23 | gump, pain, Sliimey, supar, tucks    |
|           25 |     2860 | 2024-04-17 | KZG                | W   | 0.915      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |    12.18 | gump, pain, Sliimey, supar, tucks    |
|           24 |     2872 | 2024-04-17 | 500x               | W   | 0.915      | -            | -                | -                | 0 (0.000) |     5.21 | gump, pain, Sliimey, supar, tucks    |
|           23 |     3199 | 2024-04-10 | DXA Esports        | W   | 0.868      | 0.333        | 0.005 (0.002)    | 0.196 (0.057)    | -         |    10.55 | gump, pain, Sliimey, supar, tucks    |
|           22 |     3204 | 2024-04-10 | DXA Esports        | W   | 0.868      | 0.333        | 0.005 (0.002)    | 0.196 (0.057)    | -         |    11.36 | gump, pain, Sliimey, supar, tucks    |
|           21 |     3573 | 2024-04-03 | Canon Event        | W   | 0.822      | -            | -                | -                | -         |     5.41 | gump, pain, Sliimey, supar, tucks    |
|           20 |     3576 | 2024-04-03 | Canon Event        | W   | 0.821      | -            | -                | -                | -         |     5.67 | gump, pain, Sliimey, supar, tucks    |
|           19 |     3831 | 2024-03-27 | Bad News Kangaroos | W   | 0.775      | 0.333        | 0.031 (0.008)    | 0.241 (0.062)    | -         |    18.56 | gump, pain, Sliimey, supar, tucks    |
|           18 |     3832 | 2024-03-27 | Bad News Kangaroos | L   | 0.775      | -            | -                | -                | -         |    -5.69 | gump, pain, Sliimey, supar, tucks    |
|           17 |     4906 | 2024-03-06 | Rooster            | L   | 0.636      | -            | -                | -                | -         |    -6.53 | Forleks, gump, Sliimey, supar, tucks |
|           16 |     4909 | 2024-03-06 | Rooster            | L   | 0.635      | -            | -                | -                | -         |    -6.86 | Forleks, gump, Sliimey, supar, tucks |
|           15 |     5733 | 2024-02-21 | KZG                | W   | 0.542      | 0.333        | 0.011 (0.002)    | 0.223 (0.040)    | -         |     8.55 | Forleks, gump, Sliimey, supar, tucks |
|           14 |     5737 | 2024-02-21 | KZG                | W   | 0.542      | 0.333        | 0.011 (0.002)    | 0.223 (0.040)    | -         |     8.96 | Forleks, gump, Sliimey, supar, tucks |
|           13 |     5789 | 2024-02-20 | Vantage Esports    | L   | 0.535      | -            | -                | -                | -         |    -9.52 | gump, Rickeh, Sliimey, supar, tucks  |
|           12 |     5796 | 2024-02-20 | TEAM RKON          | W   | 0.535      | -            | -                | -                | -         |     3.88 | gump, Rickeh, Sliimey, supar, tucks  |
|           11 |     5803 | 2024-02-19 | bbbbbb22           | W   | 0.535      | -            | -                | -                | -         |     2.60 | gump, Rickeh, Sliimey, supar, tucks  |
|           10 |     5855 | 2024-02-18 | FlyQuest           | L   | 0.528      | -            | -                | -                | -         |    -0.27 | gump, Rickeh, Sliimey, supar, tucks  |
|            9 |     5894 | 2024-02-18 | Vantage Esports    | W   | 0.522      | -            | -                | -                | -         |     7.26 | gump, Rickeh, Sliimey, supar, tucks  |
|            8 |     5902 | 2024-02-18 | gjdpdffileljhkj    | W   | 0.522      | -            | -                | -                | -         |     2.79 | gump, Rickeh, Sliimey, supar, tucks  |
|            7 |     5907 | 2024-02-17 | chessinpark        | W   | 0.521      | -            | -                | -                | -         |     2.69 | gump, Rickeh, Sliimey, supar, tucks  |
|            6 |     6132 | 2024-02-13 | KZG                | L   | 0.494      | -            | -                | -                | -         |    -7.11 | deStiny, gump, Sliimey, supar, tucks |
|            5 |     6172 | 2024-02-13 | DEMESIS            | W   | 0.488      | -            | -                | -                | -         |     2.56 | deStiny, gump, Sliimey, supar, tucks |
|            4 |     6177 | 2024-02-13 | Arcade Esports     | W   | 0.488      | -            | -                | -                | -         |     2.50 | deStiny, gump, Sliimey, supar, tucks |
|            3 |     6224 | 2024-02-11 | Bad News Kangaroos | L   | 0.481      | -            | -                | -                | -         |    -8.47 | dangeR, gump, Sliimey, supar, tucks  |
|            2 |     6250 | 2024-02-11 | KZG                | W   | 0.475      | 0.143        | 0.011 (0.001)    | -                | -         |     8.11 | dangeR, gump, Sliimey, supar, tucks  |
|            1 |     6392 | 2024-02-06 | Chinggis Warriors  | W   | 0.442      | -            | -                | -                | -         |     2.32 | dangeR, gump, Sliimey, supar, tucks  |

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
