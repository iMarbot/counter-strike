### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: bnc, KAISER, piria, Reix, SHOOWTiME<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [254](../standings_global.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
Final Rank Value:  683.4<br />
<br />
Final Rank Value (683.4) = Starting Rank Value (546.1) + Head To Head Adjustments (137.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 546.1
- 400 + ( ( 0.072 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 546.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       67 | 2024-05-29 | FURIA Academy           | W   | 1.000      | 0.384        | -                | 0.169 (0.065)    | 0 (0.000) |    13.35 | bnc, KAISER, piria, Reix, SHOOWTiME  |
|           16 |      130 | 2024-05-28 | eSports Recife          | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.441 (0.063)    | 0 (0.000) |    19.50 | bnc, KAISER, piria, Reix, SHOOWTiME  |
|           15 |      161 | 2024-05-27 | inSanitY Sports         | L   | 1.000      | -            | -                | -                | -         |   -12.72 | bnc, KAISER, piria, Reix, SHOOWTiME  |
|           14 |      203 | 2024-05-26 | MIBR Academy            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    16.78 | bnc, KAISER, piria, Reix, SHOOWTiME  |
|           13 |      257 | 2024-05-25 | United E-sports         | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |    13.67 | bnc, KAISER, piria, Reix, SHOOWTiME  |
|           12 |     2263 | 2024-04-26 | inSanitY Sports         | L   | 0.979      | -            | -                | -                | -         |   -14.78 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           11 |     2265 | 2024-04-26 | FURIA Esports Female    | W   | 0.978      | 0.143        | 0.018 (0.003)    | 0.159 (0.022)    | 0 (0.000) |    22.14 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           10 |     2379 | 2024-04-24 | Vikings KR              | L   | 0.965      | -            | -                | -                | -         |   -10.40 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            9 |     2384 | 2024-04-24 | Corinthians Esports     | W   | 0.965      | 0.143        | 0.002 (0.000)    | 0.458 (0.063)    | 0 (0.000) |    17.16 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            8 |     2388 | 2024-04-24 | Hawks                   | W   | 0.965      | 0.143        | 0.000 (0.000)    | 0.220 (0.030)    | 0 (0.000) |    15.85 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            7 |     2536 | 2024-04-21 | inSanitY Sports         | L   | 0.944      | -            | -                | -                | -         |   -13.85 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            6 |     2589 | 2024-04-20 | ODDIK                   | W   | 0.939      | 0.143        | 0.017 (0.002)    | 0.494 (0.066)    | 0 (0.000) |    24.93 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            5 |     2594 | 2024-04-20 | Bombril 1001 Utilidades | W   | 0.938      | 0.143        | 0.003 (0.000)    | 0.144 (0.019)    | 0 (0.000) |    19.53 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            4 |     2956 | 2024-04-16 | MIBR                    | L   | 0.912      | -            | -                | -                | -         |    -0.11 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            3 |     3307 | 2024-04-09 | Vikings KR              | L   | 0.864      | -            | -                | -                | -         |    -8.35 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            2 |     3572 | 2024-04-04 | Sensei Team             | W   | 0.831      | 0.143        | 0.003 (0.000)    | 0.482 (0.057)    | 0 (0.000) |    18.48 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            1 |     3825 | 2024-03-28 | Dusty Roots             | W   | 0.784      | 0.143        | 0.003 (0.000)    | 0.425 (0.048)    | -         |    16.14 | bnc, KAISER, Reix, SHOOWTiME, Tomate |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
