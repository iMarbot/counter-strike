### Roster Details<br />
Team Name: ThunderFlash<br />
Roster: AdrieN, hfah, Klameczka, sk1tt, yukitoro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [119](../standings_global.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
Final Rank Value:  825.3<br />
<br />
Final Rank Value (825.3) = Starting Rank Value (785.2) + Head To Head Adjustments (40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.380[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.194<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.2
- 400 + ( ( 0.194 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 785.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      144 | 2024-05-02 | V1dar Gaming           | L   | 1.000      | -            | -                | -                | -         |   -22.79 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|           12 |      194 | 2024-05-01 | TBA.ECF                | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.460 (0.171)    | 0 (0.000) |    14.68 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|           11 |      472 | 2024-04-25 | Passion UA             | W   | 1.000      | 0.371        | 0.114 (0.042)    | 0.980 (0.364)    | 0 (0.000) |    19.75 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|           10 |      533 | 2024-04-24 | Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -18.18 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            9 |      640 | 2024-04-21 | ENTERPRISE esports     | W   | 1.000      | 0.143        | 0.039 (0.006)    | 0.476 (0.068)    | 0 (0.000) |    20.41 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            8 |      729 | 2024-04-20 | Illuminar Gaming       | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.433 (0.062)    | 0 (0.000) |    17.83 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            7 |      832 | 2024-04-19 | AVEZ                   | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.160 (0.023)    | 0 (0.000) |    11.69 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            6 |     1170 | 2024-04-11 | HyperSpirit            | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.293 (0.109)    | 0 (0.000) |    13.41 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            5 |     1936 | 2024-03-22 | ENTERPRISE esports     | L   | 0.905      | -            | -                | -                | -         |    -8.74 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            4 |     1984 | 2024-03-21 | Mikstura1234           | W   | 0.898      | 0.143        | 0.003 (0.000)    | 0.110 (0.014)    | 0 (0.000) |     9.92 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            3 |     2024 | 2024-03-20 | Illuminar Gaming       | L   | 0.892      | -            | -                | -                | -         |   -12.62 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            2 |     2046 | 2024-03-19 | Turów Zgorzelec Esport | W   | 0.886      | 0.143        | 0.019 (0.002)    | 0.640 (0.081)    | 0 (0.000) |    14.83 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |
|            1 |     2094 | 2024-03-18 | LODIS                  | L   | 0.878      | -            | -                | -                | -         |   -20.08 | AdrieN, hfah, Klameczka, sk1tt, yukitoro |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,696.91)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
