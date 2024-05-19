### Roster Details<br />
Team Name: AGO esports<br />
Roster: Chill, Dementor, DEPRESHN, Svedjehed, tAk<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [269](../standings_global.md)<br />
Regional Rank: [168]( ../standings_europe.md)<br />
Final Rank Value:  646.1<br />
<br />
Final Rank Value (646.1) = Starting Rank Value (651.9) + Head To Head Adjustments (-5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 651.9
- 400 + ( ( 0.127 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 651.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     5588 | 2023-12-15 | NOM Esports          | L   | 0.251      | -            | -                | -                | -             |    -3.44 | Chill, Dementor, DEPRESHN, Svedjehed, tAk      |
|           13 |     5706 | 2023-12-11 | WOPA Esport          | L   | 0.223      | -            | -                | -                | -             |    -2.35 | Dementor, DEPRESHN, sh3nanigan, Svedjehed, tAk |
|           12 |     5770 | 2023-12-09 | Ex-Anonymo Esports   | L   | 0.211      | -            | -                | -                | -             |    -2.18 | Chill, Dementor, DEPRESHN, Svedjehed, tAk      |
|           11 |     5842 | 2023-12-08 | Sprout Academy       | W   | 0.204      | 0.303        | 0.000 (0.000)    | 0.001 (0.000)    | false (0.000) |     1.83 | Dementor, DEPRESHN, sh3nanigan, Svedjehed, tAk |
|           10 |     6025 | 2023-12-04 | WOPA Esport          | L   | 0.176      | -            | -                | -                | -             |    -1.87 | Dementor, DEPRESHN, sh3nanigan, Svedjehed, tAk |
|            9 |     6395 | 2023-11-26 | Kappa Bar            | L   | 0.125      | -            | -                | -                | -             |    -1.83 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            8 |     6493 | 2023-11-24 | Natus Vincere Junior | W   | 0.110      | 0.303        | 0.025 (0.001)    | 0.492 (0.016)    | false (0.000) |     2.61 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            7 |     6523 | 2023-11-23 | Illuminar Gaming     | L   | 0.104      | -            | -                | -                | -             |    -1.18 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            6 |     6610 | 2023-11-21 | Astralis Talent      | W   | 0.089      | 0.303        | 0.030 (0.001)    | 0.613 (0.017)    | false (0.000) |     2.42 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            5 |     6705 | 2023-11-18 | ENTERPRISE esports   | L   | 0.072      | -            | -                | -                | -             |    -0.35 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            4 |     6810 | 2023-11-16 | Ex-Anonymo Esports   | W   | 0.059      | 0.143        | 0.019 (0.000)    | 0.295 (0.002)    | false (0.000) |     1.22 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            3 |     6921 | 2023-11-14 | ENTERPRISE esports   | L   | 0.045      | -            | -                | -                | -             |    -0.22 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            2 |     7022 | 2023-11-12 | Lazer Cats           | L   | 0.029      | -            | -                | -                | -             |    -0.50 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|            1 |     7206 | 2023-11-08 | Astralis Talent      | L   | 0.004      | -            | -                | -                | -             |    -0.01 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($624.72)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
