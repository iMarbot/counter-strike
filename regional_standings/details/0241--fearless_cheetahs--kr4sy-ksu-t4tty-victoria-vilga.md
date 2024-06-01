### Roster Details<br />
Team Name: Fearless Cheetahs<br />
Roster: kr4sy, Ksu, t4tty, victoria, vilga<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [241](../standings_global.md)<br />
Regional Rank: [159]( ../standings_europe.md)<br />
Final Rank Value:  691.3<br />
<br />
Final Rank Value (691.3) = Starting Rank Value (690.0) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 690.0
- 400 + ( ( 0.142 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 690.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2487 | 2024-04-21 | ex-Guild Esports   | L   | 0.944      | -            | -                | -                | -         |   -14.62 | kr4sy, Ksu, t4tty, victoria, vilga |
|           13 |     2557 | 2024-04-20 | BIG EQUIPA         | L   | 0.937      | -            | -                | -                | -         |   -12.93 | kr4sy, Ksu, t4tty, victoria, vilga |
|           12 |     2696 | 2024-04-19 | 1win Gang          | W   | 0.930      | 0.331        | 0.004 (0.001)    | 0.118 (0.036)    | 0 (0.000) |    11.07 | kr4sy, Ksu, t4tty, victoria, vilga |
|           11 |     3110 | 2024-04-11 | Crescent           | W   | 0.877      | 0.331        | 0.007 (0.002)    | 0.228 (0.066)    | 0 (0.000) |    12.36 | kr4sy, Ksu, t4tty, victoria, vilga |
|           10 |     3352 | 2024-04-07 | NIP Impact         | L   | 0.849      | -            | -                | -                | -         |   -12.87 | kr4sy, Ksu, t4tty, victoria, vilga |
|            9 |     3408 | 2024-04-06 | Let Her Cook       | W   | 0.842      | 0.262        | 0.000 (0.000)    | 0.137 (0.030)    | 0 (0.000) |     8.74 | kr4sy, Ksu, t4tty, victoria, vilga |
|            8 |     3416 | 2024-04-06 | 5bites             | W   | 0.841      | 0.262        | 0.000 (0.000)    | 0.019 (0.004)    | 0 (0.000) |     5.70 | kr4sy, Ksu, t4tty, victoria, vilga |
|            7 |     3790 | 2024-03-27 | Team Spirit Female | W   | 0.778      | 0.331        | 0.005 (0.001)    | 0.216 (0.056)    | 0 (0.000) |    12.55 | kr4sy, Ksu, t4tty, victoria, vilga |
|            6 |     4862 | 2024-03-06 | NAVI Javelins      | L   | 0.638      | -            | -                | -                | -         |    -6.69 | kr4sy, Ksu, t4tty, victoria, vilga |
|            5 |     5178 | 2024-03-02 | more whiskey       | L   | 0.611      | -            | -                | -                | -         |   -13.76 | kr4sy, Ksu, t4tty, victoria, vilga |
|            4 |     5446 | 2024-02-25 | 1win Gang          | W   | 0.571      | 0.250        | 0.004 (0.001)    | 0.118 (0.017)    | 0 (0.000) |     8.00 | kr4sy, Ksu, t4tty, victoria, vilga |
|            3 |     5453 | 2024-02-25 | Nemesis            | W   | 0.570      | 0.250        | 0.002 (0.000)    | 0.089 (0.013)    | 0 (0.000) |     7.37 | kr4sy, Ksu, t4tty, victoria, vilga |
|            2 |     5535 | 2024-02-24 | wwaves             | W   | 0.564      | 0.250        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |     4.60 | kr4sy, Ksu, t4tty, victoria, vilga |
|            1 |     5565 | 2024-02-24 | ex-Guild Esports   | L   | 0.562      | -            | -                | -                | -         |    -8.21 | kr4sy, Ksu, t4tty, victoria, vilga |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,938.13)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.944 | $1,600.00      | $1,510.00       |
| 2024-02-25 |      0.571 | $750.00        | $428.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
