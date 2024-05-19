### Roster Details<br />
Team Name: Betera Esports<br />
Roster: alex666, El1an, lollipop21k, MaSvAl, nifee<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [91](../standings_global.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
Final Rank Value:  873.9<br />
<br />
Final Rank Value (873.9) = Starting Rank Value (812.2) + Head To Head Adjustments (61.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.410[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.2
- 400 + ( ( 0.208 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 812.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1280 | 2024-04-09 | TSM                   | L   | 1.000      | -            | -                | -                | -         |   -21.19 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           17 |     1486 | 2024-04-04 | SAW                   | L   | 0.992      | -            | -                | -                | -         |    -1.23 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           16 |     1528 | 2024-04-03 | System5               | W   | 0.985      | 0.500        | 0.000 (0.000)    | 0.061 (0.030)    | 0 (0.000) |     4.16 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           15 |     1695 | 2024-03-28 | Monte                 | W   | 0.945      | 0.500        | 0.199 (0.094)    | 0.378 (0.179)    | 0 (0.000) |    28.00 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           14 |     1751 | 2024-03-27 | Verdant               | L   | 0.938      | -            | -                | -                | -         |   -12.89 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|           13 |     1794 | 2024-03-26 | PARIVISION            | W   | 0.932      | 0.143        | 0.003 (0.000)    | 0.374 (0.050)    | 0 (0.000) |    15.69 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|           12 |     2220 | 2024-03-15 | Pera Esports          | W   | 0.858      | 0.500        | 0.065 (0.028)    | 0.324 (0.139)    | 0 (0.000) |    15.24 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           11 |     2309 | 2024-03-13 | RUSH B (Russian team) | L   | 0.846      | -            | -                | -                | -         |   -15.77 | alex666, El1an, lollipop21k, MaSvAl, nifee |
|           10 |     2694 | 2024-03-05 | Insilio               | L   | 0.792      | -            | -                | -                | -         |    -8.47 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            9 |     2719 | 2024-03-04 | HAVU Gaming           | W   | 0.786      | 0.143        | 0.024 (0.003)    | -                | 0 (0.000) |    11.23 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            8 |     2742 | 2024-03-04 | Sangal Esports        | W   | 0.786      | 0.143        | 0.000 (0.000)    | 0.350 (0.039)    | 0 (0.000) |     9.05 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            7 |     3062 | 2024-02-26 | Sashi Esport          | L   | 0.739      | -            | -                | -                | -         |    -5.58 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            6 |     3765 | 2024-02-10 | Viperio               | W   | 0.632      | 0.143        | 0.000 (0.000)    | 0.321 (0.029)    | 0 (0.000) |     5.49 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            5 |     3770 | 2024-02-10 | Team Rayvenclaw       | W   | 0.632      | -            | -                | -                | 0 (0.000) |     1.49 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            4 |     3800 | 2024-02-09 | Monte Gen             | W   | 0.624      | 0.333        | 0.019 (0.004)    | 0.155 (0.032)    | 0 (0.000) |    10.37 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            3 |     3832 | 2024-02-08 | BIG Academy           | W   | 0.616      | 0.333        | 0.027 (0.006)    | 0.219 (0.045)    | 0 (0.000) |    10.07 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            2 |     3865 | 2024-02-06 | Team Secret           | W   | 0.604      | 0.333        | -                | 0.368 (0.074)    | -         |     5.77 | alex666, lollipop21k, MaSvAl, nifee, sad   |
|            1 |     4199 | 2024-01-29 | EsmagaB               | W   | 0.551      | 0.333        | 0.016 (0.003)    | 0.559 (0.102)    | -         |    10.26 | alex666, lollipop21k, MaSvAl, nifee, sad   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,743.06)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-20 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-02-09 |      0.624 | $6,000.00      | $3,743.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
