### Roster Details<br />
Team Name: Flamengo Esports<br />
Roster: Alisson, ALLE, caike, danoco, zock9<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [403](../standings_global.md)<br />
Regional Rank: [104]( ../standings_americas.md)<br />
Final Rank Value:  547.1<br />
<br />
Final Rank Value (547.1) = Starting Rank Value (529.7) + Head To Head Adjustments (17.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.7
- 400 + ( ( 0.064 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 529.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     4412 | 2024-03-14 | MIBR Academy   | L   | 0.692      | -            | -                | -                | -         |    -5.98 | Alisson, ALLE, caike, danoco, zock9   |
|           12 |     4433 | 2024-03-14 | RED Canids     | L   | 0.690      | -            | -                | -                | -         |    -1.44 | Alisson, ALLE, caike, danoco, zock9   |
|           11 |     4583 | 2024-03-11 | MIBR Academy   | W   | 0.672      | 0.303        | 0.005 (0.001)    | 0.439 (0.089)    | 0 (0.000) |    15.62 | Alisson, ALLE, caike, danoco, zock9   |
|           10 |     4657 | 2024-03-10 | FURIA Academy  | L   | 0.664      | -            | -                | -                | -         |    -9.46 | Alisson, ALLE, danoco, voltera, zock9 |
|            9 |     4748 | 2024-03-08 | adalYamigos    | L   | 0.651      | -            | -                | -                | -         |    -5.51 | Alisson, ALLE, danoco, voltera, zock9 |
|            8 |     5745 | 2024-02-20 | Team Solid     | L   | 0.539      | -            | -                | -                | -         |    -2.45 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            7 |     5749 | 2024-02-20 | Sharks Esports | W   | 0.538      | 0.143        | 0.031 (0.002)    | 0.365 (0.028)    | 0 (0.000) |    15.16 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            6 |     5809 | 2024-02-19 | Galorys        | W   | 0.533      | 0.143        | 0.022 (0.002)    | 0.585 (0.045)    | 0 (0.000) |    14.21 | Alisson, ALLE, danoco, LUCAS1, zock9  |
|            5 |     5971 | 2024-02-16 | Galorys        | L   | 0.512      | -            | -                | -                | -         |    -2.64 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            4 |     5993 | 2024-02-16 | LA RUGONETA    | L   | 0.510      | -            | -                | -                | -         |    -7.33 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            3 |     6048 | 2024-02-15 | Case Esports   | L   | 0.503      | -            | -                | -                | -         |    -2.10 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            2 |     6142 | 2024-02-13 | 9z Academy     | W   | 0.492      | 0.303        | 0.002 (0.000)    | 0.311 (0.046)    | 0 (0.000) |    10.52 | ALLE, danoco, LUCAS1, ph1, zock9      |
|            1 |     6216 | 2024-02-12 | Fluxo          | L   | 0.483      | -            | -                | -                | -         |    -1.25 | ALLE, danoco, LUCAS1, ph1, zock9      |

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
