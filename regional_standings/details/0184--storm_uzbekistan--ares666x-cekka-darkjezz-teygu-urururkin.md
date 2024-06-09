### Roster Details<br />
Team Name: Storm Uzbekistan<br />
Roster: ares666x, CEKKA, dARkjezz, teygu, uRuRuRkiN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [184](../standings_global.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
Final Rank Value:  742.7<br />
<br />
Final Rank Value (742.7) = Starting Rank Value (769.4) + Head To Head Adjustments (-26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.356[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.161[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.4
- 400 + ( ( 0.182 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 769.4


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
|           13 |       16 | 2024-05-29 | olds                 | L   | 1.000      | -            | -                | -                | -         |   -24.81 | ares666x, CEKKA, dARkjezz, teygu, uRuRuRkiN      |
|           12 |     2579 | 2024-04-21 | Nasaf Gaming         | W   | 0.941      | 0.143        | 0.007 (0.001)    | 0.020 (0.003)    | 1 (0.941) |    10.26 | CEKKA, dARkjezz, epis, Jlaska, teygu             |
|           11 |     4419 | 2024-03-16 | Nasaf Gaming         | W   | 0.704      | 0.143        | 0.007 (0.001)    | 0.020 (0.002)    | 0 (0.000) |     8.02 | CEKKA, dARkjezz, epis, Jlaska, teygu             |
|           10 |     6284 | 2024-02-14 | RealGamers           | L   | 0.497      | -            | -                | -                | -         |   -10.47 | CEKKA, dARkjezz, jaw1ko, Jlaska, teygu           |
|            9 |     8427 | 2024-01-08 | JiJieHao             | L   | 0.251      | -            | -                | -                | -         |    -6.47 | CEKKA, CHEHOL, dARkjezz, jmqa, uRuRuRkiN         |
|            8 |     8581 | 2023-12-25 | Depo                 | L   | 0.156      | -            | -                | -                | -         |    -3.13 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            7 |     8589 | 2023-12-23 | Cyber Generation     | W   | 0.143      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 1 (0.143) |     1.20 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            6 |     8642 | 2023-12-20 | inVictus Gaming Club | W   | 0.123      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.123) |     0.63 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            5 |     8662 | 2023-12-19 | Bermood              | W   | 0.115      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 1 (0.115) |     0.43 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            4 |     8759 | 2023-12-17 | Depo                 | L   | 0.102      | -            | -                | -                | -         |    -2.06 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            3 |     8775 | 2023-12-17 | Cyber Generation     | W   | 0.101      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 1 (0.101) |     0.85 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            2 |     8901 | 2023-12-16 | Depo                 | L   | 0.095      | -            | -                | -                | -         |    -1.94 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            1 |     8922 | 2023-12-16 | Cyber Generation     | W   | 0.095      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 1 (0.095) |     0.79 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,638.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.941 | $4,735.78      | $4,457.55       |
| 2023-12-25 |      0.156 | $846.90        | $132.13         |
| 2023-12-17 |      0.102 | $482.15        | $49.29          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
