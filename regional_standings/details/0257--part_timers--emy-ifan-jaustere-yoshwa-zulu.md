### Roster Details<br />
Team Name: Part Timers<br />
Roster: eMy, ifan, JAUSTERE, Yoshwa, Zulu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [257](../standings_global.md)<br />
Regional Rank: [167]( ../standings_europe.md)<br />
Final Rank Value:  679.8<br />
<br />
Final Rank Value (679.8) = Starting Rank Value (733.3) + Head To Head Adjustments (-53.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.179[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 733.3
- 400 + ( ( 0.164 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 733.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       62 | 2024-05-29 | L&G                     | L   | 1.000      | -            | -                | -                | -         |   -10.83 | eMy, ifan, JAUSTERE, Yoshwa, Zulu             |
|           29 |      570 | 2024-05-21 | Team Invictum           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.175 (0.025)    | 0 (0.000) |    14.53 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           28 |     1064 | 2024-05-16 | Halal5                  | L   | 1.000      | -            | -                | -                | -         |   -16.68 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           27 |     1145 | 2024-05-15 | FearFerox               | L   | 1.000      | -            | -                | -                | -         |   -18.58 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           26 |     1565 | 2024-05-09 | EXO Clan                | L   | 1.000      | -            | -                | -                | -         |    -7.83 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           25 |     1682 | 2024-05-07 | The Last Resort         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.178 (0.025)    | 0 (0.000) |    15.07 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           24 |     1896 | 2024-05-03 | Verdant                 | L   | 1.000      | -            | -                | -                | -         |    -8.52 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           23 |     1981 | 2024-05-01 | ROYALS                  | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.143 (0.020)    | 0 (0.000) |    14.66 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           22 |     2049 | 2024-04-30 | Raptors Esports Club    | L   | 1.000      | -            | -                | -                | -         |    -9.14 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           21 |     2451 | 2024-04-23 | ex-K10                  | L   | 0.958      | -            | -                | -                | -         |   -12.42 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           20 |     4260 | 2024-03-19 | ex-K10                  | L   | 0.725      | -            | -                | -                | -         |    -8.43 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           19 |     4585 | 2024-03-13 | TEAM MAX                | L   | 0.685      | -            | -                | -                | -         |   -16.25 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           18 |     4666 | 2024-03-12 | Verdant                 | L   | 0.678      | -            | -                | -                | -         |    -5.67 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           17 |     4709 | 2024-03-11 | UHKA eSports            | W   | 0.671      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     2.73 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           16 |     4821 | 2024-03-09 | HAVENs                  | W   | 0.658      | 0.333        | 0.000 (0.000)    | 0.040 (0.009)    | 0 (0.000) |     2.71 | keni, proxi, v1trage, WIPSKY, yaankz          |
|           15 |     4923 | 2024-03-07 | HyperSpirit             | L   | 0.645      | -            | -                | -                | -         |   -11.26 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           14 |     5500 | 2024-02-27 | Team Invictum           | W   | 0.585      | -            | -                | -                | 0 (0.000) |     2.13 | ifan, JAUSTERE, Rhys, Yoshwa, Ziimzey         |
|           13 |     5657 | 2024-02-24 | Raptors Esports Club    | L   | 0.565      | -            | -                | -                | -         |    -7.22 | BehinDx, Karrar, moz, PrimeOPI, wfn           |
|           12 |     5688 | 2024-02-24 | Team Invictum           | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.175 (0.014)    | 1 (0.564) |     6.65 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|           11 |     5712 | 2024-02-24 | The Last Resort         | W   | 0.563      | 0.143        | 0.000 (0.000)    | 0.178 (0.014)    | 1 (0.563) |     7.04 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo          |
|           10 |     5731 | 2024-02-24 | Souls-Land              | W   | 0.562      | 0.143        | -                | 0.079 (0.006)    | 1 (0.562) |     3.70 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt |
|            9 |     5757 | 2024-02-23 | ex-K10                  | L   | 0.558      | -            | -                | -                | -         |    -6.89 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|            8 |     5853 | 2024-02-21 | Raptors Esports Club    | W   | 0.545      | 0.143        | 0.007 (0.001)    | 0.406 (0.032)    | 0 (0.000) |    10.63 | CYPHER, eMy, ifan, Yoshwa, Ziimzey            |
|            7 |     5921 | 2024-02-20 | Souls-Land              | W   | 0.538      | 0.143        | -                | 0.079 (0.006)    | -         |     3.62 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            6 |     6207 | 2024-02-15 | The Neighbours          | W   | 0.505      | 0.143        | 0.005 (0.000)    | -                | -         |     6.12 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            5 |     6329 | 2024-02-13 | Dreams To Legends       | W   | 0.491      | -            | -                | -                | -         |     3.25 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            4 |     6472 | 2024-02-09 | ex-Raptors Esports Club | L   | 0.465      | -            | -                | -                | -         |    -8.90 | ifan, JAUSTERE, m0g, Rhys, Yoshwa             |
|            3 |     6474 | 2024-02-09 | Katana Gaming           | W   | 0.465      | -            | -                | -                | -         |     1.95 | ifan, JAUSTERE, m0g, Rhys, Yoshwa             |
|            2 |     6540 | 2024-02-07 | ex-K10                  | W   | 0.451      | 0.143        | 0.005 (0.000)    | 0.517 (0.033)    | -         |     9.32 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            1 |     6565 | 2024-02-06 | Viperio                 | L   | 0.445      | -            | -                | -                | -         |    -9.04 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($288.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
