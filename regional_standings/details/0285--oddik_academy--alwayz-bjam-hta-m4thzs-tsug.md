### Roster Details<br />
Team Name: ODDIK Academy<br />
Roster: alwayz, bjam, hta, m4thzs, tsug<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [285](../standings_global.md)<br />
Regional Rank: [61]( ../standings_americas.md)<br />
Final Rank Value:  627.2<br />
<br />
Final Rank Value (627.2) = Starting Rank Value (661.2) + Head To Head Adjustments (-34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.2
- 400 + ( ( 0.132 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 661.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      333 | 2024-04-27 | Sharks Youngsters          | L   | 1.000      | -            | -                | -                | -             |   -16.37 | alwayz, bjam, hta, m4thzs, tsug       |
|           12 |      339 | 2024-04-27 | Full House Gaming          | L   | 1.000      | -            | -                | -                | -             |   -15.45 | alwayz, bjam, hta, m4thzs, tsug       |
|           11 |      346 | 2024-04-27 | Atrix Esports              | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.165 (0.024)    | false (0.000) |    16.99 | alwayz, bjam, hta, m4thzs, tsug       |
|           10 |      352 | 2024-04-27 | MIBR Female                | W   | 1.000      | 0.143        | 0.027 (0.004)    | 0.199 (0.028)    | false (0.000) |    19.22 | alwayz, bjam, hta, m4thzs, tsug       |
|            9 |      995 | 2024-04-16 | Dusty Roots                | L   | 1.000      | -            | -                | -                | -             |   -14.86 | alwayz, bjam, hta, m4thzs, tsug       |
|            8 |     1093 | 2024-04-13 | Corinthians Esports        | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | false (0.000) |    17.11 | alwayz, bjam, hta, m4thzs, tsug       |
|            7 |     1095 | 2024-04-13 | Sensei Team                | L   | 1.000      | -            | -                | -                | -             |   -11.72 | alwayz, bjam, hta, m4thzs, tsug       |
|            6 |     1132 | 2024-04-12 | Sharks Youngsters          | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.211 (0.030)    | false (0.000) |    15.68 | alwayz, bjam, hta, m4thzs, tsug       |
|            5 |     1890 | 2024-03-23 | Formula 1 (Brazilian team) | L   | 0.912      | -            | -                | -                | -             |   -19.58 | alwayz, bjam, hta, m4thzs, tsug       |
|            4 |     1900 | 2024-03-23 | Corinthians Esports        | L   | 0.912      | -            | -                | -                | -             |   -13.53 | alwayz, bjam, hta, m4thzs, tsug       |
|            3 |     4205 | 2024-01-28 | Romanticos                 | L   | 0.546      | -            | -                | -                | -             |    -7.88 | Lukita, ronazik, Skr, Tatu, will1ZERA |
|            2 |     4245 | 2024-01-27 | Yawara E-Sports            | L   | 0.540      | -            | -                | -                | -             |    -6.83 | j0w, lash, PremiuM, ritz, stAx        |
|            1 |     4260 | 2024-01-27 | 2Game Esports B            | W   | 0.539      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.11 | alwayz, bjam, gaard, hta, tsug        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($359.05)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-01 |      1.000 | $153.99        | $153.99         |
| 2024-04-27 |      1.000 | $97.69         | $97.69          |
| 2024-01-30 |      0.560 | $191.86        | $107.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
