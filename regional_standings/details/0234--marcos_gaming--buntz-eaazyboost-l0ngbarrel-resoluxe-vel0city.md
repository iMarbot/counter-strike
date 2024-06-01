### Roster Details<br />
Team Name: Marcos Gaming<br />
Roster: BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [234](../standings_global.md)<br />
Regional Rank: [30]( ../standings_asia.md)<br />
Final Rank Value:  700.0<br />
<br />
Final Rank Value (700.0) = Starting Rank Value (675.4) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.4
- 400 + ( ( 0.135 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 675.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3696 | 2024-03-30 | True Rippers    | L   | 0.795      | -            | -                | -                | -         |   -10.94 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|           12 |     3715 | 2024-03-29 | Gods Reign      | L   | 0.789      | -            | -                | -                | -         |    -5.73 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|           11 |     3751 | 2024-03-28 | True Rippers    | W   | 0.783      | 0.143        | 0.025 (0.003)    | 0.241 (0.027)    | 0 (0.000) |    13.43 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|           10 |     3755 | 2024-03-28 | Grayfox Esports | W   | 0.782      | 0.143        | 0.004 (0.000)    | 0.204 (0.023)    | 0 (0.000) |    11.02 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            9 |     3956 | 2024-03-24 | Gods Reign      | L   | 0.755      | -            | -                | -                | -         |    -5.57 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            8 |     3958 | 2024-03-23 | True Rippers    | W   | 0.754      | 0.262        | 0.025 (0.005)    | 0.241 (0.048)    | 0 (0.000) |    13.92 | Anasasis, Crazy_Gamer, DEFAULTER, Mcg1LLzZz, Rossi |
|            7 |     4567 | 2024-03-12 | TyPuCTbl        | L   | 0.676      | -            | -                | -                | -         |   -12.50 | AceQx, Forceboy, Leoo, majorK-, xds                |
|            6 |     4974 | 2024-03-05 | Gods Reign      | L   | 0.629      | -            | -                | -                | -         |    -4.97 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn             |
|            5 |     5110 | 2024-03-03 | Grayfox Esports | W   | 0.615      | 0.143        | 0.004 (0.000)    | 0.204 (0.018)    | 0 (0.000) |     9.26 | Ace, arakyN, ghostxD, Marzil, Nox                  |
|            4 |     5193 | 2024-03-02 | Gods Reign      | W   | 0.610      | 0.143        | 0.086 (0.007)    | 0.461 (0.040)    | 0 (0.000) |    14.67 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            3 |     5206 | 2024-03-02 | 2ez Gaming      | W   | 0.609      | 0.143        | 0.001 (0.000)    | 0.095 (0.008)    | 0 (0.000) |     8.51 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            2 |     5775 | 2024-02-20 | Re-wonation     | W   | 0.536      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.00 | BuNTz, EaazyBoost, L0ngBarrel, ResoLuxe, vel0city  |
|            1 |     5841 | 2024-02-19 | 2ez Gaming      | L   | 0.530      | -            | -                | -                | -         |    -9.46 | bb1, iFRAGEZ, p7, Recoilmaster, ShinChAn           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($442.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-24 |      0.755 | $500.00        | $377.34         |
| 2024-02-21 |      0.543 | $120.63        | $65.49          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
