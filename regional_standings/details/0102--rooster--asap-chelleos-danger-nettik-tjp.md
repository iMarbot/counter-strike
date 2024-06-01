### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, nettik, TjP<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [102](../standings_global.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
Final Rank Value:  866.3<br />
<br />
Final Rank Value (866.3) = Starting Rank Value (811.2) + Head To Head Adjustments (55.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.287[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.103[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 811.2
- 400 + ( ( 0.202 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 811.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      520 | 2024-05-22 | Vantage Esports    | W   | 1.000      | 0.333        | -                | 0.226 (0.075)    | 0 (0.000) |     7.54 | asap, chelleos, dangeR, nettik, TjP     |
|           40 |      523 | 2024-05-22 | Vantage Esports    | W   | 1.000      | 0.333        | -                | 0.226 (0.075)    | 0 (0.000) |     8.05 | asap, chelleos, dangeR, nettik, TjP     |
|           39 |     1202 | 2024-05-15 | Canon Event        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.41 | asap, chelleos, dangeR, nettik, TjP     |
|           38 |     1207 | 2024-05-15 | Canon Event        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.53 | asap, chelleos, dangeR, nettik, TjP     |
|           37 |     1650 | 2024-05-08 | KZG                | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     8.91 | asap, chelleos, dangeR, nettik, TjP     |
|           36 |     1654 | 2024-05-08 | KZG                | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     9.58 | asap, chelleos, dangeR, nettik, TjP     |
|           35 |     2220 | 2024-04-26 | MIBR               | L   | 0.980      | -            | -                | -                | -         |    -0.50 | asap, chelleos, dangeR, nettik, TjP     |
|           34 |     2284 | 2024-04-26 | KZG                | W   | 0.975      | 0.500        | 0.011 (0.005)    | 0.223 (0.109)    | 1 (0.975) |    10.06 | asap, chelleos, dangeR, nettik, TjP     |
|           33 |     2290 | 2024-04-25 | Rebels Gaming      | L   | 0.973      | -            | -                | -                | -         |    -6.32 | asap, chelleos, dangeR, nettik, TjP     |
|           32 |     2655 | 2024-04-19 | Bad News Kangaroos | L   | 0.934      | -            | -                | -                | -         |   -11.60 | asap, chelleos, dangeR, nettik, TjP     |
|           31 |     2727 | 2024-04-19 | FlyQuest           | L   | 0.928      | -            | -                | -                | -         |    -0.96 | asap, chelleos, dangeR, nettik, TjP     |
|           30 |     2730 | 2024-04-19 | Gen.G Esports      | L   | 0.928      | -            | -                | -                | -         |   -25.25 | asap, chelleos, dangeR, nettik, TjP     |
|           29 |     2735 | 2024-04-18 | Bad News Kangaroos | W   | 0.927      | 0.143        | 0.031 (0.004)    | -                | 0 (0.000) |    16.55 | asap, chelleos, dangeR, nettik, TjP     |
|           28 |     2799 | 2024-04-17 | Rare Atom          | L   | 0.921      | -            | -                | -                | -         |   -16.85 | asap, chelleos, dangeR, nettik, TjP     |
|           27 |     2858 | 2024-04-17 | Arcade Esports     | W   | 0.915      | 0.143        | 0.006 (0.001)    | -                | 0 (0.000) |     9.06 | asap, chelleos, dangeR, nettik, TjP     |
|           26 |     2861 | 2024-04-17 | Canon Event        | W   | 0.915      | -            | -                | -                | 0 (0.000) |     3.23 | asap, chelleos, dangeR, nettik, TjP     |
|           25 |     2878 | 2024-04-17 | Double-Down        | W   | 0.915      | -            | -                | -                | -         |     2.17 | asap, chelleos, dangeR, nettik, TjP     |
|           24 |     3201 | 2024-04-10 | Bad News Kangaroos | L   | 0.868      | -            | -                | -                | -         |   -11.88 | asap, chelleos, dangeR, nettik, TjP     |
|           23 |     3206 | 2024-04-10 | Bad News Kangaroos | W   | 0.868      | 0.333        | 0.031 (0.009)    | 0.241 (0.070)    | -         |    15.75 | asap, chelleos, dangeR, nettik, TjP     |
|           22 |     4906 | 2024-03-06 | Mindfreak          | W   | 0.636      | 0.333        | -                | 0.306 (0.065)    | -         |     6.53 | asap, chelleos, dangeR, nettik, TjP     |
|           21 |     4909 | 2024-03-06 | Mindfreak          | W   | 0.635      | 0.333        | -                | 0.306 (0.065)    | -         |     6.86 | asap, chelleos, dangeR, nettik, TjP     |
|           20 |     5621 | 2024-02-23 | FlyQuest           | L   | 0.555      | -            | -                | -                | -         |    -0.57 | asap, chelleos, dangeR, nettik, TjP     |
|           19 |     5624 | 2024-02-22 | Bad News Kangaroos | W   | 0.554      | 0.143        | 0.031 (0.002)    | -                | -         |    10.72 | asap, chelleos, dangeR, nettik, TjP     |
|           18 |     5671 | 2024-02-22 | FlyQuest           | L   | 0.548      | -            | -                | -                | -         |    -0.54 | asap, chelleos, dangeR, nettik, TjP     |
|           17 |     5673 | 2024-02-21 | Vantage Esports    | W   | 0.547      | -            | -                | -                | -         |     5.41 | asap, chelleos, dangeR, nettik, TjP     |
|           16 |     5732 | 2024-02-21 | DXA Esports        | W   | 0.542      | 0.333        | 0.005 (0.001)    | 0.196 (0.035)    | -         |     5.69 | asap, chelleos, dangeR, nettik, TjP     |
|           15 |     5736 | 2024-02-21 | DXA Esports        | W   | 0.542      | 0.333        | 0.005 (0.001)    | 0.196 (0.035)    | -         |     5.94 | asap, chelleos, dangeR, nettik, TjP     |
|           14 |     6671 | 2024-02-01 | M80                | L   | 0.410      | -            | -                | -                | -         |    -0.84 | asap, chelleos, nettik, Rackem, TjP     |
|           13 |     6710 | 2024-01-31 | Virtus.pro         | L   | 0.404      | -            | -                | -                | -         |    -0.08 | asap, chelleos, nettik, Rackem, TjP     |
|           12 |     7064 | 2024-01-26 | Bad News Kangaroos | L   | 0.368      | -            | -                | -                | -         |    -8.37 | asap, chelleos, nettik, Rackem, TjP     |
|           11 |     7094 | 2024-01-25 | Mindfreak          | W   | 0.361      | -            | -                | -                | -         |     3.94 | asap, chelleos, nettik, Rackem, TjP     |
|           10 |     7141 | 2024-01-24 | Blitz              | W   | 0.355      | -            | -                | -                | -         |     1.55 | asap, chelleos, nettik, Rackem, TjP     |
|            9 |     7153 | 2024-01-23 | 500x               | W   | 0.355      | -            | -                | -                | -         |     1.74 | asap, chelleos, nettik, Rackem, TjP     |
|            8 |     7198 | 2024-01-22 | Mindfreak          | L   | 0.347      | -            | -                | -                | -         |    -7.36 | asap, chelleos, nettik, Rackem, TjP     |
|            7 |     7251 | 2024-01-22 | Bad News Kangaroos | W   | 0.342      | 0.143        | 0.031 (0.002)    | -                | -         |     6.92 | asap, chelleos, nettik, Rackem, TjP     |
|            6 |     7254 | 2024-01-21 | Mindfreak          | L   | 0.341      | -            | -                | -                | -         |    -7.32 | asap, chelleos, nettik, Rackem, TjP     |
|            5 |     7295 | 2024-01-20 | FlyQuest           | L   | 0.334      | -            | -                | -                | -         |    -0.32 | asap, chelleos, nettik, Rackem, TjP     |
|            4 |     7300 | 2024-01-20 | Bad News Kangaroos | L   | 0.333      | -            | -                | -                | -         |    -3.90 | asap, chelleos, nettik, Rackem, TjP     |
|            3 |     7434 | 2024-01-19 | Mindfreak          | W   | 0.321      | -            | -                | -                | -         |     3.18 | asap, chelleos, nettik, Rackem, TjP     |
|            2 |     7442 | 2024-01-18 | StevosFirstCS2     | W   | 0.321      | -            | -                | -                | -         |     1.43 | asap, chelleos, nettik, Rackem, TjP     |
|            1 |     9523 | 2023-12-01 | KZG                | W   | 0.001      | -            | -                | -                | -         |     0.01 | asap, chelleos, nettik, Rackem, vanilla |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,157.40)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      0.988 | $3,000.00      | $2,964.31       |
| 2024-02-11 |      0.477 | $2,500.00      | $1,192.36       |
| 2023-12-01 |      0.001 | $750.00        | $0.73           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
