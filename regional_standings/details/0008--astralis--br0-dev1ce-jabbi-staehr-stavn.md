### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, dev1ce, jabbi, Staehr, stavn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [8](../standings_global.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
Final Rank Value:  1697.1<br />
<br />
Final Rank Value (1697.1) = Starting Rank Value (1675.5) + Head To Head Adjustments (21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.713[<sup>1</sup>](#table2)
- Bounty Collected: 0.711[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.773[<sup>2</sup>](#table1)

The average of these factors is 0.627<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1675.5
- 400 + ( ( 0.627 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1675.5


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
|           30 |      516 | 2024-05-22 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |   -18.98 | br0, dev1ce, jabbi, Staehr, stavn    |
|           29 |      614 | 2024-05-21 | Aurora Gaming      | W   | 1.000      | 0.769        | 0.492 (0.378)    | 0.616 (0.473)    | -         |     3.88 | br0, dev1ce, jabbi, Staehr, stavn    |
|           28 |      686 | 2024-05-20 | BetBoom Team       | W   | 1.000      | 0.769        | 0.390 (0.299)    | 0.712 (0.547)    | -         |     3.29 | br0, dev1ce, jabbi, Staehr, stavn    |
|           27 |      729 | 2024-05-19 | BIG                | W   | 1.000      | 0.769        | 0.235 (0.181)    | 0.304 (0.233)    | -         |     4.05 | br0, dev1ce, jabbi, Staehr, stavn    |
|           26 |     1448 | 2024-05-11 | Team Vitality      | L   | 1.000      | -            | -                | -                | -         |    -9.52 | br0, dev1ce, jabbi, Staehr, stavn    |
|           25 |     1517 | 2024-05-10 | Team Liquid        | W   | 1.000      | 0.889        | 0.513 (0.456)    | 0.621 (0.552)    | 1 (1.000) |    11.80 | br0, dev1ce, jabbi, Staehr, stavn    |
|           24 |     2370 | 2024-04-24 | FaZe Clan          | W   | 0.964      | 0.889        | 1.000 (0.857)    | 0.457 (0.391)    | 1 (0.964) |    24.76 | br0, dev1ce, jabbi, Staehr, stavn    |
|           23 |     2417 | 2024-04-23 | Eternal Fire       | W   | 0.956      | 0.889        | 1.000 (0.850)    | 0.402 (0.342)    | 1 (0.956) |    20.69 | br0, dev1ce, jabbi, Staehr, stavn    |
|           22 |     3049 | 2024-04-13 | FaZe Clan          | L   | 0.889      | -            | -                | -                | -         |    -4.66 | br0, dev1ce, jabbi, Staehr, stavn    |
|           21 |     3207 | 2024-04-10 | Virtus.pro         | W   | 0.868      | 0.624        | 0.271 (0.147)    | 0.331 (0.179)    | 1 (0.868) |    15.21 | br0, dev1ce, jabbi, Staehr, stavn    |
|           20 |     3269 | 2024-04-09 | FaZe Clan          | W   | 0.861      | 0.624        | 1.000 (0.538)    | 0.457 (0.246)    | 1 (0.861) |    23.22 | br0, dev1ce, jabbi, Staehr, stavn    |
|           19 |     3314 | 2024-04-08 | Steel Helmet       | W   | 0.854      | -            | -                | -                | 1 (0.854) |     0.13 | br0, dev1ce, jabbi, Staehr, stavn    |
|           18 |     5620 | 2024-02-23 | 9Pandas            | L   | 0.556      | -            | -                | -                | -         |   -16.31 | blameF, dev1ce, jabbi, Staehr, stavn |
|           17 |     5669 | 2024-02-22 | ENCE               | L   | 0.549      | -            | -                | -                | -         |   -12.95 | blameF, dev1ce, jabbi, Staehr, stavn |
|           16 |     5734 | 2024-02-21 | Monte              | W   | 0.542      | -            | -                | -                | 1 (0.542) |     2.31 | blameF, dev1ce, jabbi, Staehr, stavn |
|           15 |     5782 | 2024-02-20 | HEROIC             | L   | 0.536      | -            | -                | -                | -         |    -6.60 | blameF, dev1ce, jabbi, Staehr, stavn |
|           14 |     5816 | 2024-02-19 | Team Spirit        | L   | 0.531      | -            | -                | -                | -         |    -3.12 | blameF, dev1ce, jabbi, Staehr, stavn |
|           13 |     5843 | 2024-02-19 | Nexus Gaming       | W   | 0.530      | -            | -                | -                | 1 (0.530) |     0.25 | blameF, dev1ce, jabbi, Staehr, stavn |
|           12 |     6658 | 2024-02-01 | ENCE               | L   | 0.411      | -            | -                | -                | -         |   -10.45 | blameF, dev1ce, jabbi, Staehr, stavn |
|           11 |     6729 | 2024-01-31 | HEROIC             | L   | 0.403      | -            | -                | -                | -         |    -5.30 | blameF, dev1ce, jabbi, Staehr, stavn |
|           10 |     6881 | 2024-01-28 | BIG                | W   | 0.383      | 0.581        | -                | 0.304 (0.068)    | 1 (0.383) |     2.41 | blameF, dev1ce, jabbi, Staehr, stavn |
|            9 |     6991 | 2024-01-27 | Team Vitality      | L   | 0.376      | -            | -                | -                | -         |    -3.20 | blameF, dev1ce, jabbi, Staehr, stavn |
|            8 |     7181 | 2024-01-23 | Team Vitality      | W   | 0.350      | 0.581        | 0.696 (0.142)    | 0.320 (0.065)    | 1 (0.350) |     8.18 | blameF, dev1ce, jabbi, Staehr, stavn |
|            7 |     7227 | 2024-01-22 | Team Falcons       | W   | 0.344      | 0.581        | 0.355 (0.071)    | -                | -         |     2.84 | blameF, dev1ce, jabbi, Staehr, stavn |
|            6 |     7343 | 2024-01-20 | Pera Esports       | W   | 0.330      | -            | -                | -                | -         |     0.16 | blameF, dev1ce, jabbi, Staehr, stavn |
|            5 |     7406 | 2024-01-19 | AMKAL ESPORTS      | L   | 0.324      | -            | -                | -                | -         |    -9.50 | blameF, dev1ce, jabbi, Staehr, stavn |
|            4 |     7472 | 2024-01-18 | ex-Preasy Esport   | W   | 0.317      | -            | -                | -                | -         |     0.14 | blameF, dev1ce, jabbi, Staehr, stavn |
|            3 |     7475 | 2024-01-18 | ENTERPRISE esports | W   | 0.317      | -            | -                | -                | -         |     0.17 | blameF, dev1ce, jabbi, Staehr, stavn |
|            2 |     9169 | 2023-12-07 | FURIA Esports      | L   | 0.037      | -            | -                | -                | -         |    -0.92 | blameF, dev1ce, jabbi, Staehr, stavn |
|            1 |     9245 | 2023-12-06 | Virtus.pro         | L   | 0.028      | -            | -                | -                | -         |    -0.43 | blameF, dev1ce, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($118,895.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.40) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-05-12 |      1.000 | $45,000.00     | $45,000.00      |
| 2024-04-14 |      0.895 | $20,000.00     | $17,903.24      |
| 2024-02-11 |      0.477 | $2,500.00      | $1,192.36       |
| 2024-01-28 |      0.384 | $12,500.00     | $4,800.35       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
