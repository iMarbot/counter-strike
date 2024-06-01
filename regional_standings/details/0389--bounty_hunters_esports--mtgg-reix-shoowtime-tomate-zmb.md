### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: MTGG, Reix, SHOOWTiME, Tomate, zmb<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [389](../standings_global.md)<br />
Regional Rank: [100]( ../standings_americas.md)<br />
Final Rank Value:  561.7<br />
<br />
Final Rank Value (561.7) = Starting Rank Value (512.1) + Head To Head Adjustments (49.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 512.1
- 400 + ( ( 0.055 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 512.1


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
|           10 |     3913 | 2024-03-25 | Bombril 1001 Utilidades | W   | 0.764      | 0.143        | 0.003 (0.000)    | 0.144 (0.016)    | 0 (0.000) |    16.49 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            9 |     4063 | 2024-03-21 | FURIA Academy           | L   | 0.738      | -            | -                | -                | -         |    -9.73 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            8 |     4075 | 2024-03-21 | Intense Game            | W   | 0.738      | 0.143        | 0.003 (0.000)    | 0.362 (0.038)    | 0 (0.000) |    17.02 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            7 |     4193 | 2024-03-18 | MIBR Academy            | L   | 0.718      | -            | -                | -                | -         |    -6.14 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            6 |     4371 | 2024-03-15 | Romanticos              | W   | 0.698      | 0.262        | 0.001 (0.000)    | 0.132 (0.024)    | 0 (0.000) |    14.55 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            5 |     4413 | 2024-03-14 | Hazap Esports           | W   | 0.691      | 0.262        | 0.000 (0.000)    | 0.037 (0.007)    | 0 (0.000) |    12.04 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            4 |     4644 | 2024-03-10 | KRÜ Esports             | L   | 0.665      | -            | -                | -                | -         |    -3.90 | lqk, MTGG, Reix, SHOOWTiME, souz4h   |
|            3 |     6397 | 2024-02-05 | paiN Gaming Academy     | L   | 0.438      | -            | -                | -                | -         |    -5.38 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |
|            2 |     6656 | 2024-02-01 | Formiguinhas            | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.28 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |
|            1 |     6807 | 2024-01-29 | FURIA Esports Female    | W   | 0.392      | 0.143        | 0.018 (0.001)    | 0.159 (0.009)    | 0 (0.000) |    10.34 | ber, MTGG, pedrinzy, Reix, SHOOWTiME |

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
