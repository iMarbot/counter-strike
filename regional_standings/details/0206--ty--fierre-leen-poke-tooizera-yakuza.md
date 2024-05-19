### Roster Details<br />
Team Name: TY<br />
Roster: fierre, LeeN, PoKe, tooizera, yakuza<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [206](../standings_global.md)<br />
Regional Rank: [138]( ../standings_europe.md)<br />
Final Rank Value:  707.0<br />
<br />
Final Rank Value (707.0) = Starting Rank Value (694.1) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.1
- 400 + ( ( 0.148 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 694.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     5178 | 2024-01-06 | Natus Vincere Junior  | W   | 0.397      | 0.354        | 0.025 (0.003)    | 0.492 (0.069)    | false (0.000) |     8.42 | fierre, LeeN, PoKe, tooizera, yakuza     |
|           14 |     5190 | 2024-01-05 | PSYCHOACTiVE          | W   | 0.390      | 0.354        | 0.000 (0.000)    | 0.019 (0.003)    | false (0.000) |     3.67 | fierre, LeeN, PoKe, tooizera, yakuza     |
|           13 |     5274 | 2023-12-23 | Natus Vincere Junior  | W   | 0.304      | 0.354        | 0.025 (0.003)    | 0.492 (0.053)    | false (0.000) |     6.80 | fierre, LeeN, PoKe, tooizera, yakuza     |
|           12 |     5290 | 2023-12-22 | ROSOMAHA              | W   | 0.297      | 0.354        | 0.000 (0.000)    | 0.136 (0.014)    | false (0.000) |     3.82 | fierre, LeeN, PoKe, tooizera, yakuza     |
|           11 |     5876 | 2023-12-07 | RUSH B (Russian team) | L   | 0.199      | -            | -                | -                | -             |    -2.28 | fierre, maty, spardaus, tooizera, yakuza |
|           10 |     5983 | 2023-12-05 | BIG Academy           | L   | 0.185      | -            | -                | -                | -             |    -1.83 | ArroW, hyped, MRC9, pr1metapz, skyye     |
|            9 |     6208 | 2023-11-30 | TSM                   | L   | 0.151      | -            | -                | -                | -             |    -2.28 | CYPHER, interz, JACKZ, MoDo, valde       |
|            8 |     6250 | 2023-11-29 | Galaxy Gaming         | L   | 0.145      | -            | -                | -                | -             |    -2.88 | Ay0k, bond1e, D3Nse, denzori, fjoe       |
|            7 |     6268 | 2023-11-29 | Grindas               | L   | 0.145      | -            | -                | -                | -             |    -2.22 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo   |
|            6 |     6273 | 2023-11-29 | HOTDodgers            | W   | 0.144      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     0.73 | Arkana, Bunny, CoolGirl, Ikrid, MalunaZ  |
|            5 |     6303 | 2023-11-28 | TEAM ZOO BAR          | L   | 0.139      | -            | -                | -                | -             |    -3.25 | fierre, maty, spardaus, tooizera, yakuza |
|            4 |     6313 | 2023-11-28 | Lilmix                | W   | 0.138      | 0.371        | 0.000 (0.000)    | 0.098 (0.005)    | false (0.000) |     2.23 | dex, L00m1, melonhead, quix, SeBreeZe    |
|            3 |     6504 | 2023-11-23 | Lemondogs             | W   | 0.106      | 0.371        | 0.000 (0.000)    | 0.252 (0.010)    | false (0.000) |     1.14 | fierre, maty, spardaus, tooizera, yakuza |
|            2 |     6515 | 2023-11-23 | Ex-Hot Headed Gaming  | W   | 0.105      | 0.371        | 0.000 (0.000)    | 0.117 (0.005)    | false (0.000) |     0.89 | fierre, maty, spardaus, tooizera, yakuza |
|            1 |     7164 | 2023-11-08 | MOUZ NXT              | L   | 0.006      | -            | -                | -                | -             |    -0.02 | Chr1zN, Neityu, Nexius, PR, sirah        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,792.29)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
