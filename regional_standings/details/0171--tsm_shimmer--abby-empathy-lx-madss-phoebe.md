### Roster Details<br />
Team Name: TSM Shimmer<br />
Roster: abby, empathy, Lx, madss, Phoebe<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [171](../standings_global.md)<br />
Regional Rank: [35]( ../standings_americas.md)<br />
Final Rank Value:  763.0<br />
<br />
Final Rank Value (763.0) = Starting Rank Value (724.8) + Head To Head Adjustments (38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 724.8
- 400 + ( ( 0.160 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 724.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      204 | 2024-05-26 | FlyQuest RED           | L   | 1.000      | -            | -                | -                | -         |   -12.10 | abby, empathy, Lx, madss, Phoebe            |
|           39 |      206 | 2024-05-26 | Team Karma             | W   | 1.000      | 0.303        | 0.007 (0.002)    | 0.139 (0.042)    | 0 (0.000) |    13.27 | abby, empathy, Lx, madss, Phoebe            |
|           38 |      247 | 2024-05-25 | Limitless Angels       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.79 | abby, empathy, Lx, madss, Phoebe            |
|           37 |      255 | 2024-05-25 | Transgressions         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.87 | abby, empathy, Lx, madss, Phoebe            |
|           36 |      557 | 2024-05-21 | Nouns Esports          | L   | 1.000      | -            | -                | -                | -         |    -7.04 | abby, empathy, Lx, madss, Phoebe            |
|           35 |      562 | 2024-05-21 | The Krubby Krabs       | L   | 1.000      | -            | -                | -                | -         |   -24.67 | abby, empathy, Lx, madss, Phoebe            |
|           34 |      577 | 2024-05-21 | Party Astronauts       | L   | 1.000      | -            | -                | -                | -         |    -8.14 | abby, empathy, Lx, madss, Phoebe            |
|           33 |     1770 | 2024-05-05 | Limitless Angels       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.44 | bungee, Celi, erin, Fawx, mira              |
|           32 |     1816 | 2024-05-04 | Aware Impact           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | Cloudy, CocoCR, eepy.rain, gadfly, Lexa     |
|           31 |     2718 | 2024-04-19 | Limitless Angels       | W   | 0.932      | 0.322        | 0.005 (0.002)    | 0.109 (0.033)    | 0 (0.000) |    10.50 | abby, empathy, Lx, madss, Phoebe            |
|           30 |     3034 | 2024-04-14 | FlyQuest RED           | L   | 0.898      | -            | -                | -                | -         |   -11.17 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa |
|           29 |     3065 | 2024-04-13 | Nouns.fe               | W   | 0.892      | 0.250        | 0.006 (0.001)    | 0.080 (0.018)    | 0 (0.000) |     9.65 | ashe, katalyyst, Knopk@, lunari, toasty     |
|           28 |     3166 | 2024-04-11 | COVEN                  | W   | 0.879      | 0.322        | 0.003 (0.001)    | -                | 0 (0.000) |     5.44 | abby, empathy, Lx, madss, Phoebe            |
|           27 |     3405 | 2024-04-07 | Limitless Angels       | W   | 0.852      | 0.250        | 0.005 (0.001)    | 0.109 (0.023)    | 0 (0.000) |    10.29 | daria, Fawx, mira, PiggyKiki, rbn           |
|           26 |     3444 | 2024-04-06 | Wanted Goons Bandits   | W   | 0.846      | 0.250        | 0.003 (0.001)    | 0.039 (0.008)    | 0 (0.000) |     8.28 | ADK, jaydee, MamaAlien, PippySippy, Tippy   |
|           25 |     3615 | 2024-04-03 | Wanted Goons Bandits   | W   | 0.825      | 0.322        | 0.003 (0.001)    | 0.039 (0.010)    | -         |     8.62 | abby, empathy, Lx, madss, Phoebe            |
|           24 |     3862 | 2024-03-27 | cleanup crew           | W   | 0.779      | 0.322        | 0.004 (0.001)    | 0.054 (0.013)    | -         |     9.93 | ARIANARCHIST, Bubzy, gadfly, paula, shelby  |
|           23 |     4116 | 2024-03-22 | Peeker's Advantage     | L   | 0.746      | -            | -                | -                | -         |   -13.73 | abby, empathy, Lx, madss, Phoebe            |
|           22 |     4150 | 2024-03-21 | Team Karma             | W   | 0.739      | 0.322        | 0.007 (0.002)    | 0.139 (0.033)    | -         |    10.05 | artStar, Ellie, EMUHLEET, olya, rain        |
|           21 |     4212 | 2024-03-20 | ELO Throwers           | W   | 0.733      | -            | -                | -                | -         |     7.30 | abby, empathy, Lx, madss, Phoebe            |
|           20 |     4253 | 2024-03-19 | Persona Esports        | W   | 0.726      | -            | -                | -                | -         |     5.84 | ChaZzuM, Ecl9pse, J13K, jcr, Outback        |
|           19 |     4515 | 2024-03-14 | Nouns.fe               | W   | 0.693      | 0.322        | 0.006 (0.001)    | 0.080 (0.018)    | -         |     9.59 | ashe, jesscas, katalyyst, lunari, tokkis    |
|           18 |     4969 | 2024-03-06 | FlyQuest RED           | L   | 0.640      | -            | -                | -                | -         |    -7.43 | abby, empathy, Lx, madss, Phoebe            |
|           17 |     5204 | 2024-03-03 | FlyQuest RED           | L   | 0.619      | -            | -                | -                | -         |    -7.58 | abby, empathy, Lx, madss, Phoebe            |
|           16 |     5593 | 2024-02-25 | FlyQuest RED           | L   | 0.572      | -            | -                | -                | -         |    -7.54 | abby, empathy, Lx, madss, Phoebe            |
|           15 |     5633 | 2024-02-24 | Radiant Rebels         | W   | 0.566      | -            | -                | -                | -         |     4.23 | bMAX, exclude, jance., Knopk@, sunnypp      |
|           14 |     6649 | 2024-02-04 | FlyQuest RED           | L   | 0.432      | -            | -                | -                | -         |    -5.99 | abby, empathy, Lx, madss, Phoebe            |
|           13 |     6689 | 2024-02-03 | Limitless Angels       | W   | 0.426      | 0.250        | -                | 0.109 (0.012)    | -         |     5.64 | abby, empathy, Lx, madss, Phoebe            |
|           12 |     7062 | 2024-01-28 | FlyQuest RED           | L   | 0.386      | -            | -                | -                | -         |    -5.52 | abby, empathy, Lx, madss, Phoebe            |
|           11 |     7112 | 2024-01-27 | unotevenafart          | W   | 0.379      | -            | -                | -                | -         |     1.66 | abby, empathy, Lx, madss, Phoebe            |
|           10 |     7503 | 2024-01-21 | NA savers              | W   | 0.339      | -            | -                | -                | -         |     3.75 | abby, empathy, Lx, Phoebe, raynee           |
|            9 |     7545 | 2024-01-20 | Wanted Goons Bandits   | W   | 0.333      | -            | -                | -                | -         |     4.25 | jaydee, MamaAlien, PippySippy, Reef, Tippy  |
|            8 |     7943 | 2024-01-15 | NRG                    | L   | 0.300      | -            | -                | -                | -         |    -3.27 | abby, chigen, empathy, Lx, phoebe           |
|            7 |     8411 | 2024-01-08 | Bloons Tower Defense 6 | L   | 0.254      | -            | -                | -                | -         |    -6.24 | Frost, Lethality, miilo, SaberCat, trzzy    |
|            6 |     8688 | 2023-12-17 | Limitless Angels       | W   | 0.106      | -            | -                | -                | -         |     1.43 | chigen, empathy, Lx, Phoebe, vanessa        |
|            5 |     8799 | 2023-12-16 | Nouns.fe               | W   | 0.100      | -            | -                | -                | -         |     1.33 | chigen, empathy, Lx, Phoebe, vanessa        |
|            4 |     9364 | 2023-12-08 | FURIA Esports Female   | L   | 0.044      | -            | -                | -                | -         |    -0.52 | Aidy, Bouchard, empathy, Lx, Phoebe         |
|            3 |     9381 | 2023-12-08 | NAVI Javelins          | L   | 0.043      | -            | -                | -                | -         |    -0.58 | Aidy, Bouchard, empathy, Lx, Phoebe         |
|            2 |     9631 | 2023-12-03 | Nouns.fe               | W   | 0.012      | -            | -                | -                | -         |     0.16 | ARIANARCHIST, ashe, lunari, raynee, Rice    |
|            1 |     9705 | 2023-12-02 | fren                   | W   | 0.006      | -            | -                | -                | -         |     0.03 | Cloudy_y, gadfly, gone, katalyyst, power    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,174.72)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-05-25 |      1.000 | $750.00        | $750.00         |
| 2024-05-05 |      1.000 | $750.00        | $750.00         |
| 2024-04-14 |      0.898 | $250.00        | $224.58         |
| 2024-04-07 |      0.852 | $750.00        | $638.96         |
| 2024-03-24 |      0.760 | $700.00        | $531.71         |
| 2024-03-03 |      0.619 | $250.00        | $154.73         |
| 2024-02-25 |      0.572 | $250.00        | $143.06         |
| 2024-01-21 |      0.339 | $750.00        | $254.18         |
| 2023-12-10 |      0.057 | $4,000.00      | $227.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
