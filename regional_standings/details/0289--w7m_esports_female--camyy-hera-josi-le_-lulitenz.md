### Roster Details<br />
Team Name: w7m esports Female<br />
Roster: cAmyy, hera, josi, Le^, lulitenz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [289](../standings_global.md)<br />
Regional Rank: [63]( ../standings_americas.md)<br />
Final Rank Value:  651.5<br />
<br />
Final Rank Value (651.5) = Starting Rank Value (680.5) + Head To Head Adjustments (-29.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.331[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.138<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 680.5
- 400 + ( ( 0.138 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 680.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2535 | 2024-04-21 | FURIA Esports Female | L   | 0.944      | -            | -                | -                | -         |    -8.44 | cAmyy, hera, josi, Le^, lulitenz |
|           14 |     2729 | 2024-04-19 | ex-DIVINA Female     | W   | 0.931      | 0.332        | 0.004 (0.001)    | 0.053 (0.016)    | 0 (0.000) |    13.49 | cAmyy, hera, josi, Le^, lulitenz |
|           13 |     3066 | 2024-04-13 | Fluxo Demons         | L   | 0.892      | -            | -                | -                | -         |    -6.61 | cAmyy, hera, josi, Le^, lulitenz |
|           12 |     3072 | 2024-04-13 | SunDogs              | W   | 0.892      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.43 | cAmyy, hera, josi, Le^, lulitenz |
|           11 |     3171 | 2024-04-11 | MIBR Female          | L   | 0.878      | -            | -                | -                | -         |   -11.13 | cAmyy, hera, josi, Le^, lulitenz |
|           10 |     3871 | 2024-03-27 | Atrix Esports        | L   | 0.778      | -            | -                | -                | -         |   -11.96 | cAmyy, hera, josi, Le^, lulitenz |
|            9 |     4029 | 2024-03-24 | Rocket.GG            | L   | 0.758      | -            | -                | -                | -         |   -13.27 | cAmyy, hera, josi, Le^, lulitenz |
|            8 |     4065 | 2024-03-23 | Sensei Team          | L   | 0.752      | -            | -                | -                | -         |   -10.57 | cAmyy, hera, josi, Le^, lulitenz |
|            7 |     4066 | 2024-03-23 | Rocket.GG            | W   | 0.752      | 0.143        | 0.001 (0.000)    | 0.062 (0.007)    | 0 (0.000) |     9.53 | cAmyy, hera, josi, Le^, lulitenz |
|            6 |     4154 | 2024-03-21 | Illusion             | W   | 0.738      | 0.332        | 0.003 (0.001)    | 0.028 (0.007)    | 0 (0.000) |     9.35 | cAmyy, hera, josi, Le^, lulitenz |
|            5 |     4521 | 2024-03-14 | Fluxo Demons         | L   | 0.692      | -            | -                | -                | -         |    -6.26 | cAmyy, hera, josi, Le^, lulitenz |
|            4 |     4975 | 2024-03-06 | FURIA Esports Female | L   | 0.638      | -            | -                | -                | -         |    -7.41 | cAmyy, hera, josi, Le^, lulitenz |
|            3 |     5648 | 2024-02-24 | ex-DIVINA Female     | W   | 0.566      | 0.250        | 0.004 (0.001)    | 0.053 (0.007)    | 0 (0.000) |     8.04 | cAmyy, hera, josi, Le^, lulitenz |
|            2 |     6323 | 2024-02-13 | SunDogs              | W   | 0.492      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.67 | cAmyy, hera, josi, Le^, lulitenz |
|            1 |     8817 | 2023-12-16 | panela do rush       | L   | 0.099      | -            | -                | -                | -         |    -1.90 | cAmyy, hera, josi, Le^, lulitenz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,873.18)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.945 | $1,250.00      | $1,181.60       |
| 2024-04-19 |      0.931 | $1,300.00      | $1,210.63       |
| 2024-04-13 |      0.892 | $250.00        | $223.03         |
| 2024-03-25 |      0.766 | $119.94        | $91.86          |
| 2024-02-24 |      0.566 | $250.00        | $141.38         |
| 2023-12-16 |      0.099 | $250.00        | $24.69          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
