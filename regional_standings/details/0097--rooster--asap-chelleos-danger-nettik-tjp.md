### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, nettik, TjP<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [97](../standings_global.md)<br />
Regional Rank: [8]( ../standings_asia.md)<br />
Final Rank Value:  876.9<br />
<br />
Final Rank Value (876.9) = Starting Rank Value (815.0) + Head To Head Adjustments (61.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.103[<sup>2</sup>](#table1)

The average of these factors is 0.204<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 815.0
- 400 + ( ( 0.204 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 815.0


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
|           45 |      527 | 2024-05-22 | Vantage Esports    | W   | 1.000      | 0.333        | -                | 0.226 (0.075)    | 0 (0.000) |     8.01 | asap, chelleos, dangeR, nettik, TjP     |
|           44 |      530 | 2024-05-22 | Vantage Esports    | W   | 1.000      | 0.333        | -                | 0.226 (0.075)    | 0 (0.000) |     8.57 | asap, chelleos, dangeR, nettik, TjP     |
|           43 |     1212 | 2024-05-15 | Canon Event        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.14 | asap, chelleos, dangeR, nettik, TjP     |
|           42 |     1217 | 2024-05-15 | Canon Event        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.25 | asap, chelleos, dangeR, nettik, TjP     |
|           41 |     1668 | 2024-05-08 | KZG                | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     8.17 | asap, chelleos, dangeR, nettik, TjP     |
|           40 |     1672 | 2024-05-08 | KZG                | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.223 (0.074)    | 0 (0.000) |     8.76 | asap, chelleos, dangeR, nettik, TjP     |
|           39 |     2256 | 2024-04-26 | MIBR               | L   | 0.980      | -            | -                | -                | -         |    -0.54 | asap, chelleos, dangeR, nettik, TjP     |
|           38 |     2321 | 2024-04-26 | KZG                | W   | 0.975      | 0.500        | 0.011 (0.005)    | 0.223 (0.109)    | 1 (0.975) |     9.15 | asap, chelleos, dangeR, nettik, TjP     |
|           37 |     2327 | 2024-04-25 | Rebels Gaming      | L   | 0.973      | -            | -                | -                | -         |    -6.46 | asap, chelleos, dangeR, nettik, TjP     |
|           36 |     2709 | 2024-04-19 | Bad News Kangaroos | L   | 0.934      | -            | -                | -                | -         |   -12.08 | asap, chelleos, dangeR, nettik, TjP     |
|           35 |     2783 | 2024-04-19 | FlyQuest           | L   | 0.928      | -            | -                | -                | -         |    -1.00 | asap, chelleos, dangeR, nettik, TjP     |
|           34 |     2786 | 2024-04-19 | Gen.G Esports      | L   | 0.928      | -            | -                | -                | -         |   -25.50 | asap, chelleos, dangeR, nettik, TjP     |
|           33 |     2791 | 2024-04-18 | Bad News Kangaroos | W   | 0.927      | 0.143        | 0.031 (0.004)    | -                | 0 (0.000) |    16.00 | asap, chelleos, dangeR, nettik, TjP     |
|           32 |     2855 | 2024-04-17 | Rare Atom          | L   | 0.921      | -            | -                | -                | -         |   -17.42 | asap, chelleos, dangeR, nettik, TjP     |
|           31 |     2915 | 2024-04-17 | Arcade Esports     | W   | 0.915      | -            | -                | -                | 0 (0.000) |     8.14 | asap, chelleos, dangeR, nettik, TjP     |
|           30 |     2918 | 2024-04-17 | Canon Event        | W   | 0.915      | -            | -                | -                | 0 (0.000) |     2.88 | asap, chelleos, dangeR, nettik, TjP     |
|           29 |     2936 | 2024-04-17 | Double-Down        | W   | 0.915      | -            | -                | -                | -         |     2.00 | asap, chelleos, dangeR, nettik, TjP     |
|           28 |     3277 | 2024-04-10 | Bad News Kangaroos | L   | 0.868      | -            | -                | -                | -         |   -12.51 | asap, chelleos, dangeR, nettik, TjP     |
|           27 |     3283 | 2024-04-10 | Bad News Kangaroos | W   | 0.868      | 0.333        | 0.031 (0.009)    | 0.241 (0.070)    | -         |    15.07 | asap, chelleos, dangeR, nettik, TjP     |
|           26 |     3924 | 2024-03-27 | Arcade Esports     | W   | 0.775      | 0.333        | 0.006 (0.002)    | 0.280 (0.072)    | -         |     7.79 | asap, chelleos, dangeR, nettik, TjP     |
|           25 |     3930 | 2024-03-27 | Arcade Esports     | W   | 0.775      | 0.333        | 0.006 (0.002)    | 0.280 (0.072)    | -         |     8.27 | asap, chelleos, dangeR, nettik, TjP     |
|           24 |     4630 | 2024-03-13 | FlyQuest           | L   | 0.682      | -            | -                | -                | -         |    -0.80 | asap, chelleos, dangeR, nettik, TjP     |
|           23 |     4636 | 2024-03-13 | FlyQuest           | L   | 0.682      | -            | -                | -                | -         |    -0.80 | asap, chelleos, dangeR, nettik, TjP     |
|           22 |     5040 | 2024-03-06 | Mindfreak          | W   | 0.636      | 0.333        | -                | 0.306 (0.065)    | -         |     6.46 | asap, chelleos, dangeR, nettik, TjP     |
|           21 |     5046 | 2024-03-06 | Mindfreak          | W   | 0.635      | 0.333        | -                | 0.306 (0.065)    | -         |     6.79 | asap, chelleos, dangeR, nettik, TjP     |
|           20 |     5781 | 2024-02-23 | FlyQuest           | L   | 0.555      | -            | -                | -                | -         |    -0.57 | asap, chelleos, dangeR, nettik, TjP     |
|           19 |     5784 | 2024-02-22 | Bad News Kangaroos | W   | 0.554      | 0.143        | 0.031 (0.002)    | -                | -         |    10.61 | asap, chelleos, dangeR, nettik, TjP     |
|           18 |     5832 | 2024-02-22 | FlyQuest           | L   | 0.548      | -            | -                | -                | -         |    -0.54 | asap, chelleos, dangeR, nettik, TjP     |
|           17 |     5834 | 2024-02-21 | Vantage Esports    | W   | 0.547      | -            | -                | -                | -         |     5.59 | asap, chelleos, dangeR, nettik, TjP     |
|           16 |     5898 | 2024-02-21 | DXA Esports        | W   | 0.542      | 0.333        | 0.005 (0.001)    | -                | -         |     5.57 | asap, chelleos, dangeR, nettik, TjP     |
|           15 |     5903 | 2024-02-21 | DXA Esports        | W   | 0.542      | -            | -                | -                | -         |     5.81 | asap, chelleos, dangeR, nettik, TjP     |
|           14 |     6880 | 2024-02-01 | M80                | L   | 0.410      | -            | -                | -                | -         |    -0.90 | asap, chelleos, nettik, Rackem, TjP     |
|           13 |     6921 | 2024-01-31 | Virtus.pro         | L   | 0.404      | -            | -                | -                | -         |    -0.08 | asap, chelleos, nettik, Rackem, TjP     |
|           12 |     7290 | 2024-01-26 | Bad News Kangaroos | L   | 0.368      | -            | -                | -                | -         |    -8.42 | asap, chelleos, nettik, Rackem, TjP     |
|           11 |     7323 | 2024-01-25 | Mindfreak          | W   | 0.361      | -            | -                | -                | -         |     3.89 | asap, chelleos, nettik, Rackem, TjP     |
|           10 |     7376 | 2024-01-24 | Blitz              | W   | 0.355      | -            | -                | -                | -         |     1.52 | asap, chelleos, nettik, Rackem, TjP     |
|            9 |     7388 | 2024-01-23 | 500x               | W   | 0.355      | -            | -                | -                | -         |     1.71 | asap, chelleos, nettik, Rackem, TjP     |
|            8 |     7439 | 2024-01-22 | Mindfreak          | L   | 0.347      | -            | -                | -                | -         |    -7.41 | asap, chelleos, nettik, Rackem, TjP     |
|            7 |     7494 | 2024-01-22 | Bad News Kangaroos | W   | 0.342      | 0.143        | 0.031 (0.002)    | -                | -         |     6.87 | asap, chelleos, nettik, Rackem, TjP     |
|            6 |     7497 | 2024-01-21 | Mindfreak          | L   | 0.341      | -            | -                | -                | -         |    -7.37 | asap, chelleos, nettik, Rackem, TjP     |
|            5 |     7538 | 2024-01-20 | FlyQuest           | L   | 0.334      | -            | -                | -                | -         |    -0.33 | asap, chelleos, nettik, Rackem, TjP     |
|            4 |     7543 | 2024-01-20 | Bad News Kangaroos | L   | 0.333      | -            | -                | -                | -         |    -3.95 | asap, chelleos, nettik, Rackem, TjP     |
|            3 |     7681 | 2024-01-19 | Mindfreak          | W   | 0.321      | -            | -                | -                | -         |     3.13 | asap, chelleos, nettik, Rackem, TjP     |
|            2 |     7689 | 2024-01-18 | StevosFirstCS2     | W   | 0.321      | -            | -                | -                | -         |     1.40 | asap, chelleos, nettik, Rackem, TjP     |
|            1 |     9805 | 2023-12-01 | KZG                | W   | 0.001      | -            | -                | -                | -         |     0.01 | asap, chelleos, nettik, Rackem, vanilla |

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
