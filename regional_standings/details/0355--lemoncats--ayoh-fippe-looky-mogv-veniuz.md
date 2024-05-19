### Roster Details<br />
Team Name: Lemoncats<br />
Roster: Ayoh, fippe, looky, mogv, veniuz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [355](../standings_global.md)<br />
Regional Rank: [222]( ../standings_europe.md)<br />
Final Rank Value:  455.3<br />
<br />
Final Rank Value (455.3) = Starting Rank Value (465.0) + Head To Head Adjustments (-9.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.130[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.033<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 465.0
- 400 + ( ( 0.033 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 465.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       46 | 2024-05-04 | Begrip Gaming     | L   | 1.000      | -            | -                | -                | -             |   -12.72 | Ayoh, fippe, looky, mogv, veniuz    |
|           10 |      573 | 2024-04-23 | Curlews           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |    11.88 | Ayoh, fippe, looky, mogv, veniuz    |
|            9 |     1484 | 2024-04-04 | Young Gods        | L   | 0.992      | -            | -                | -                | -             |   -15.95 | Ayoh, fippe, looky, mogv, veniuz    |
|            8 |     2022 | 2024-03-20 | Full Kareta       | W   | 0.892      | 0.143        | 0.000 (0.000)    | 0.035 (0.004)    | false (0.000) |    10.96 | Ayoh, fippe, looky, mogv, veniuz    |
|            7 |     5665 | 2023-12-12 | HEYDERS           | L   | 0.232      | -            | -                | -                | -             |    -2.33 | Cham, Fraaank, otto, P1ke, Zendy    |
|            6 |     5720 | 2023-12-10 | TOOMUCHVIDEOGAMES | L   | 0.218      | -            | -                | -                | -             |    -3.01 | Ayoh, fippe, looky, mogv, simpan    |
|            5 |     5867 | 2023-12-07 | Oxuji Esports     | W   | 0.199      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.57 | Ayoh, fippe, looky, mogv, simpan    |
|            4 |     5967 | 2023-12-05 | LEON Esports      | L   | 0.186      | -            | -                | -                | -             |    -1.26 | Ayoh, fippe, looky, mogv, simpan    |
|            3 |     6675 | 2023-11-19 | Kappa Bar         | L   | 0.077      | -            | -                | -                | -             |    -0.80 | AlekS, b0bbzki, HugoXD, nomiss, zen |
|            2 |     6925 | 2023-11-14 | Young Gods        | W   | 0.045      | 0.143        | 0.000 (0.000)    | 0.204 (0.001)    | false (0.000) |     0.77 | Focus, Lindcs, MaiL09, viz, Wonder  |
|            1 |     7130 | 2023-11-09 | Kappa Bar         | W   | 0.012      | 0.143        | 0.001 (0.000)    | 0.009 (0.000)    | false (0.000) |     0.25 | Ayoh, fippe, looky, mogv, simpan    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
