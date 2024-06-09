### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: MTGG, Reix, SHOOWTiME, Tomate, zmb<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [401](../standings_global.md)<br />
Regional Rank: [101]( ../standings_americas.md)<br />
Final Rank Value:  562.4<br />
<br />
Final Rank Value (562.4) = Starting Rank Value (511.8) + Head To Head Adjustments (50.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.8
- 400 + ( ( 0.055 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 511.8


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
|           10 |     4010 | 2024-03-25 | Bombril 1001 Utilidades | W   | 0.764      | 0.143        | 0.003 (0.000)    | 0.144 (0.016)    | 0 (0.000) |    16.43 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            9 |     4161 | 2024-03-21 | FURIA Academy           | L   | 0.738      | -            | -                | -                | -         |    -9.79 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            8 |     4173 | 2024-03-21 | Intense Game            | W   | 0.738      | 0.143        | 0.003 (0.000)    | 0.334 (0.035)    | 0 (0.000) |    16.96 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            7 |     4297 | 2024-03-18 | MIBR Academy            | L   | 0.718      | -            | -                | -                | -         |    -6.17 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            6 |     4479 | 2024-03-15 | Romanticos              | W   | 0.698      | 0.262        | 0.001 (0.000)    | 0.132 (0.024)    | 0 (0.000) |    14.51 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            5 |     4527 | 2024-03-14 | Hazap Esports           | W   | 0.691      | 0.262        | 0.000 (0.000)    | 0.037 (0.007)    | 0 (0.000) |    12.01 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            4 |     4767 | 2024-03-10 | KRÜ Esports             | L   | 0.665      | -            | -                | -                | -         |    -3.92 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            3 |     6593 | 2024-02-05 | paiN Gaming Academy     | L   | 0.438      | -            | -                | -                | -         |    -5.43 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |
|            2 |     6861 | 2024-02-01 | Formiguinhas            | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     5.61 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |
|            1 |     7023 | 2024-01-29 | FURIA Esports Female    | W   | 0.392      | 0.143        | 0.018 (0.001)    | 0.159 (0.009)    | 0 (0.000) |    10.34 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |

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
