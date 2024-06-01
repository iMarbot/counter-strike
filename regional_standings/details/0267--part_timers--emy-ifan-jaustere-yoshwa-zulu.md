### Roster Details<br />
Team Name: Part Timers<br />
Roster: eMy, ifan, JAUSTERE, Yoshwa, Zulu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [267](../standings_global.md)<br />
Regional Rank: [170]( ../standings_europe.md)<br />
Final Rank Value:  665.8<br />
<br />
Final Rank Value (665.8) = Starting Rank Value (719.1) + Head To Head Adjustments (-53.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.179[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.1
- 400 + ( ( 0.157 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 719.1


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
|           22 |       60 | 2024-05-29 | L&G                     | L   | 1.000      | -            | -                | -                | -         |   -10.39 | eMy, ifan, JAUSTERE, Yoshwa, Zulu             |
|           21 |      559 | 2024-05-21 | Team Invictum           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.175 (0.025)    | 0 (0.000) |    15.10 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           20 |     1054 | 2024-05-16 | Halal5                  | L   | 1.000      | -            | -                | -                | -         |   -16.03 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           19 |     1136 | 2024-05-15 | FearFerox               | L   | 1.000      | -            | -                | -                | -         |   -17.92 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           18 |     1550 | 2024-05-09 | EXO Clan                | L   | 1.000      | -            | -                | -                | -         |    -7.74 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           17 |     1664 | 2024-05-07 | The Last Resort         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.178 (0.025)    | 0 (0.000) |    15.73 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           16 |     1872 | 2024-05-03 | Verdant                 | L   | 1.000      | -            | -                | -                | -         |    -8.34 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           15 |     1954 | 2024-05-01 | ROYALS                  | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.143 (0.020)    | 0 (0.000) |    15.92 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           14 |     2018 | 2024-04-30 | Raptors Esports Club    | L   | 1.000      | -            | -                | -                | -         |    -8.31 | eMy, ifan, Yoshwa, Ziimzey, Zulu              |
|           13 |     4158 | 2024-03-19 | ex-K10                  | L   | 0.725      | -            | -                | -                | -         |    -7.72 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           12 |     4471 | 2024-03-13 | TEAM MAX                | L   | 0.685      | -            | -                | -                | -         |   -15.50 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           11 |     4547 | 2024-03-12 | Verdant                 | L   | 0.678      | -            | -                | -                | -         |    -4.99 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|           10 |     4588 | 2024-03-11 | UHKA eSports            | W   | 0.671      | 0.333        | 0.000 (0.000)    | 0.018 (0.004)    | 0 (0.000) |     3.22 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            9 |     4696 | 2024-03-09 | HAVENs                  | W   | 0.658      | 0.333        | 0.000 (0.000)    | 0.040 (0.009)    | 0 (0.000) |     3.19 | keni, proxi, v1trage, WIPSKY, yaankz          |
|            8 |     4794 | 2024-03-07 | HyperSpirit             | L   | 0.645      | -            | -                | -                | -         |   -10.23 | eMy, ifan, Rhys, Yoshwa, Ziimzey              |
|            7 |     5497 | 2024-02-24 | Raptors Esports Club    | L   | 0.565      | -            | -                | -                | -         |    -6.22 | BehinDx, Karrar, moz, PrimeOPI, wfn           |
|            6 |     5528 | 2024-02-24 | Team Invictum           | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.175 (0.014)    | 1 (0.564) |     7.46 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|            5 |     5552 | 2024-02-24 | The Last Resort         | W   | 0.563      | 0.143        | 0.000 (0.000)    | 0.178 (0.014)    | 1 (0.563) |     7.88 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo          |
|            4 |     5571 | 2024-02-24 | Souls-Land              | W   | 0.562      | 0.143        | 0.000 (0.000)    | 0.079 (0.006)    | 1 (0.562) |     4.40 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt |
|            3 |     5597 | 2024-02-23 | ex-K10                  | L   | 0.558      | -            | -                | -                | -         |    -6.28 | CYPHER, ifan, JackB, JAUSTERE, Yoshwa         |
|            2 |     6284 | 2024-02-09 | ex-Raptors Esports Club | L   | 0.465      | -            | -                | -                | -         |    -8.62 | ifan, JAUSTERE, m0g, Rhys, Yoshwa             |
|            1 |     6286 | 2024-02-09 | Katana Gaming           | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.09 | ifan, JAUSTERE, m0g, Rhys, Yoshwa             |

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
