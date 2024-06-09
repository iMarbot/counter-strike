### Roster Details<br />
Team Name: Limitless Angels<br />
Roster: daria, Fawx, mira, PiggyKiki, rbn<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [283](../standings_global.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
Final Rank Value:  657.3<br />
<br />
Final Rank Value (657.3) = Starting Rank Value (673.4) + Head To Head Adjustments (-16.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 673.4
- 400 + ( ( 0.135 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 673.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2718 | 2024-04-19 | TSM Shimmer          | L   | 0.932      | -            | -                | -                | -         |   -10.50 | daria, Fawx, mira, PiggyKiki, rbn                |
|           13 |     3067 | 2024-04-13 | FlyQuest RED         | L   | 0.892      | -            | -                | -                | -         |    -8.03 | daria, Fawx, mira, PiggyKiki, rbn                |
|           12 |     3167 | 2024-04-11 | Nouns.fe             | W   | 0.879      | 0.322        | 0.006 (0.002)    | 0.080 (0.023)    | 0 (0.000) |    13.71 | daria, Fawx, mira, PiggyKiki, rbn                |
|           11 |     3405 | 2024-04-07 | TSM Shimmer          | L   | 0.852      | -            | -                | -                | -         |   -10.29 | daria, Fawx, mira, PiggyKiki, rbn                |
|           10 |     3445 | 2024-04-06 | Equity Gaming        | W   | 0.846      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.78 | daria, Fawx, mira, PiggyKiki, rbn                |
|            9 |     3614 | 2024-04-03 | Team Karma           | L   | 0.825      | -            | -                | -                | -         |   -12.44 | daria, Fawx, mira, PiggyKiki, rbn                |
|            8 |     3818 | 2024-03-28 | COVEN                | W   | 0.786      | 0.322        | 0.003 (0.001)    | 0.014 (0.004)    | 0 (0.000) |     7.32 | daria, Fawx, mira, PiggyKiki, rbn                |
|            7 |     4216 | 2024-03-20 | FlyQuest RED         | L   | 0.733      | -            | -                | -                | -         |    -7.43 | daria, Fawx, mira, PiggyKiki, rbn                |
|            6 |     4573 | 2024-03-13 | Wanted Goons Bandits | W   | 0.686      | 0.322        | 0.003 (0.001)    | 0.039 (0.009)    | 0 (0.000) |     9.68 | daria, Fawx, mira, PiggyKiki, rbn                |
|            5 |     4911 | 2024-03-07 | cleanup crew         | W   | 0.646      | 0.322        | 0.004 (0.001)    | 0.054 (0.011)    | 0 (0.000) |     9.74 | daria, Fawx, mira, PiggyKiki, rbn                |
|            4 |     6689 | 2024-02-03 | TSM Shimmer          | L   | 0.426      | -            | -                | -                | -         |    -5.64 | abby, empathy, Lx, madss, Phoebe                 |
|            3 |     7547 | 2024-01-20 | NA savers            | L   | 0.333      | -            | -                | -                | -         |    -6.16 | ARIANARCHIST, bungee, cinnamon, madss, PiggyKiki |
|            2 |     8688 | 2023-12-17 | TSM Shimmer          | L   | 0.106      | -            | -                | -                | -         |    -1.43 | chigen, empathy, Lx, Phoebe, vanessa             |
|            1 |     8809 | 2023-12-16 | fren                 | W   | 0.099      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.56 | Cloudy_y, gadfly, gone, katalyyst, LadyLotus     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,637.76)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-19 |      0.932 | $1,500.00      | $1,398.33       |
| 2024-04-07 |      0.852 | $250.00        | $212.99         |
| 2023-12-17 |      0.106 | $250.00        | $26.44          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
