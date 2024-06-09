### Roster Details<br />
Team Name: Team LRP Poland<br />
Roster: dezz, Masi, njuki, s0ki, Xydoo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [218](../standings_global.md)<br />
Regional Rank: [147]( ../standings_europe.md)<br />
Final Rank Value:  709.2<br />
<br />
Final Rank Value (709.2) = Starting Rank Value (729.2) + Head To Head Adjustments (-19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 729.2
- 400 + ( ( 0.162 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 729.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     1429 | 2024-05-11 | AVEZ                | L   | 1.000      | -            | -                | -                | -         |    -9.45 | dezz, Masi, njuki, s0ki, Xydoo           |
|           12 |     1444 | 2024-05-11 | akceptuj            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.028 (0.004)    | 1 (1.000) |    12.74 | dezz, Masi, njuki, s0ki, Xydoo           |
|           11 |     1474 | 2024-05-11 | Back2TheGame        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.003 (0.000)    | 1 (1.000) |    10.12 | dezz, Masi, njuki, s0ki, Xydoo           |
|           10 |     1481 | 2024-05-11 | AVEZ                | L   | 1.000      | -            | -                | -                | -         |    -9.59 | dezz, Masi, njuki, s0ki, Xydoo           |
|            9 |     4824 | 2024-03-09 | EP Genesis          | L   | 0.658      | -            | -                | -                | -         |   -14.85 | Ag3NTK, njuki, Rafex, s0ki, Xydoo        |
|            8 |     5077 | 2024-03-05 | ADEPTS              | L   | 0.631      | -            | -                | -                | -         |    -7.01 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            7 |     8368 | 2024-01-09 | Dynamo Eclot        | L   | 0.257      | -            | -                | -                | -         |    -0.87 | Blytz, Dytor, forsyy, kreaz, nbqq        |
|            6 |     9415 | 2023-12-07 | NOM Esports         | L   | 0.038      | -            | -                | -                | -         |    -0.74 | AdrieN, Fugor, njuki, s0ki, Xydoo        |
|            5 |     9498 | 2023-12-06 | Monte Gen           | L   | 0.031      | -            | -                | -                | -         |    -0.43 | AdrieN, Fugor, njuki, s0ki, Xydoo        |
|            4 |     9558 | 2023-12-05 | VP.Prodigy          | L   | 0.025      | -            | -                | -                | -         |    -0.27 | AdrieN, Fugor, njuki, s0ki, Xydoo        |
|            3 |     9570 | 2023-12-05 | Preasy Esport       | W   | 0.024      | 0.289        | 0.008 (0.000)    | 0.705 (0.005)    | 0 (0.000) |     0.54 | beccie, Equip, Griller, Skejs, tauy0y0   |
|            2 |     9617 | 2023-12-04 | GamerLegion Academy | L   | 0.018      | -            | -                | -                | -         |    -0.19 | AdrieN, Fugor, njuki, s0ki, Xydoo        |
|            1 |     9743 | 2023-12-02 | ROSOMAHA            | W   | 0.004      | 0.289        | 0.000 (0.000)    | 0.145 (0.000)    | 0 (0.000) |     0.04 | D0nii, Maggent, rendY, skcH, Зippoch     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($375.43)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
