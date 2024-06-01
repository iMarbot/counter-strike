### Roster Details<br />
Team Name: ex-FLuffy Gangsters<br />
Roster: b1st, Djon, h1ghnesS, mo5kow, takanashi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [400](../standings_global.md)<br />
Regional Rank: [239]( ../standings_europe.md)<br />
Final Rank Value:  551.5<br />
<br />
Final Rank Value (551.5) = Starting Rank Value (510.2) + Head To Head Adjustments (41.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.2
- 400 + ( ( 0.054 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 510.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     5252 | 2024-02-29 | AURA                   | L   | 0.598      | -            | -                | -                | -         |    -6.59 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           16 |     5263 | 2024-02-29 | GenOne                 | L   | 0.598      | -            | -                | -                | -         |    -9.17 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           15 |     5693 | 2024-02-21 | Team Secret            | W   | 0.544      | 0.371        | 0.000 (0.000)    | 0.230 (0.047)    | 0 (0.000) |    11.20 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           14 |     5820 | 2024-02-19 | Lausanne-Sport Esports | W   | 0.531      | 0.371        | 0.002 (0.000)    | 0.257 (0.051)    | 0 (0.000) |    12.32 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           13 |     6106 | 2024-02-14 | ILIN                   | W   | 0.497      | 0.371        | 0.000 (0.000)    | 0.196 (0.036)    | 0 (0.000) |     8.13 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           12 |     6191 | 2024-02-12 | lajtbitexe             | W   | 0.484      | 0.371        | 0.001 (0.000)    | 0.069 (0.012)    | 0 (0.000) |     9.14 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           11 |     6214 | 2024-02-12 | Soda Gaming            | W   | 0.483      | 0.371        | 0.000 (0.000)    | 0.098 (0.018)    | 0 (0.000) |    10.16 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|           10 |     6304 | 2024-02-09 | DMS                    | L   | 0.463      | -            | -                | -                | -         |    -3.57 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            9 |     6403 | 2024-02-05 | ex-Hot Headed Gaming   | W   | 0.438      | 0.371        | 0.000 (0.000)    | 0.086 (0.014)    | 0 (0.000) |     6.80 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            8 |     6601 | 2024-02-02 | Endpoint               | L   | 0.417      | -            | -                | -                | -         |    -1.14 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            7 |     6678 | 2024-02-01 | ARCRED                 | W   | 0.410      | 0.371        | 0.000 (0.000)    | 0.630 (0.096)    | 0 (0.000) |    10.67 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            6 |     7028 | 2024-01-26 | 9Pandas                | L   | 0.371      | -            | -                | -                | -         |    -0.27 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            5 |     7040 | 2024-01-26 | Entropiq               | L   | 0.370      | -            | -                | -                | -         |    -3.42 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            4 |     8021 | 2024-01-10 | Zero Tenacity          | L   | 0.265      | -            | -                | -                | -         |    -0.32 | b1st, Djon, h1ghnesS, mo5kow, takanashi      |
|            3 |     8507 | 2023-12-17 | 1win Academy           | L   | 0.102      | -            | -                | -                | -         |    -1.15 | 7tetsu, b1st, h1ghnesS, mo5kow, takanashi    |
|            2 |     8647 | 2023-12-16 | Donstu Esports         | L   | 0.095      | -            | -                | -                | -         |    -1.43 | 7tetsu, b1st, h1ghnesS, mo5kow, takanashi    |
|            1 |     9463 | 2023-12-02 | Lausanne-Sport Esports | L   | 0.004      | -            | -                | -                | -         |    -0.05 | arbnorz, Diviiii, Razzmo, Wonderful_Y, xReal |

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
