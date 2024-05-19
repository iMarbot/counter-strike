### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: b0RUP, kristou, niko, refrezh, TMB<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [85](../standings_global.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
Final Rank Value:  885.3<br />
<br />
Final Rank Value (885.3) = Starting Rank Value (848.9) + Head To Head Adjustments (36.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 848.9
- 400 + ( ( 0.226 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 848.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      155 | 2024-05-02 | Endpoint             | L   | 1.000      | -            | -                | -                | -             |   -13.82 | b0RUP, kristou, niko, refrezh, TMB        |
|            9 |     1799 | 2024-03-26 | Raptors Esports Club | L   | 0.932      | -            | -                | -                | -             |   -17.20 | BehinDx, Karrar, moz, PrimeOPI, wfn       |
|            8 |     1945 | 2024-03-22 | FORZE Esports        | L   | 0.904      | -            | -                | -                | -             |    -7.58 | gokushima, r3salt, SELLTER, shalfey, tN1R |
|            7 |     2107 | 2024-03-18 | Team Sampi           | W   | 0.876      | 0.371        | 0.108 (0.035)    | 0.709 (0.230)    | false (0.000) |    17.38 | fino, manguss, sAvana1, The eLiVe, ZEDKO  |
|            6 |     2180 | 2024-03-16 | Passion UA           | W   | 0.864      | 0.371        | 0.114 (0.037)    | 0.980 (0.314)    | false (0.000) |    15.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX |
|            5 |     2288 | 2024-03-14 | Entropiq             | W   | 0.849      | 0.371        | 0.001 (0.000)    | 0.436 (0.137)    | false (0.000) |    11.14 | Altekz, kristou, refrezh, roeJ, TMB       |
|            4 |     2435 | 2024-03-11 | Permitta Esports     | W   | 0.830      | 0.371        | 0.063 (0.019)    | 1.000 (0.308)    | false (0.000) |    17.33 | Altekz, kristou, refrezh, roeJ, TMB       |
|            3 |     2520 | 2024-03-09 | K10                  | W   | 0.816      | 0.371        | 0.015 (0.005)    | 0.418 (0.126)    | false (0.000) |    11.94 | Altekz, kristou, refrezh, roeJ, TMB       |
|            2 |     2586 | 2024-03-07 | Team Secret          | W   | 0.803      | 0.371        | 0.000 (0.000)    | 0.368 (0.110)    | false (0.000) |     6.65 | anarkez, innocent, Kind0, Maze, Tauson    |
|            1 |     2821 | 2024-03-03 | MOUZ NXT             | L   | 0.776      | -            | -                | -                | -             |    -5.32 | Burmylov, Chr1zN, Neityu, PR, sirah       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,636.71)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
