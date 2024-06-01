### Roster Details<br />
Team Name: ex-Martians<br />
Roster: bpg, DexteR, kindg, spankeer, Straafer<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [405](../standings_global.md)<br />
Regional Rank: [105]( ../standings_americas.md)<br />
Final Rank Value:  545.1<br />
<br />
Final Rank Value (545.1) = Starting Rank Value (626.3) + Head To Head Adjustments (-81.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.3
- 400 + ( ( 0.111 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 626.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      647 | 2024-05-20 | TIME DE PESO        | L   | 1.000      | -            | -                | -                | -         |   -19.86 | bpg, DexteR, kindg, spankeer, Straafer     |
|           12 |     1046 | 2024-05-16 | 2Game Esports       | L   | 1.000      | -            | -                | -                | -         |   -12.30 | bpg, DexteR, kindg, spankeer, Straafer     |
|           11 |     1051 | 2024-05-16 | Vikings KR          | L   | 1.000      | -            | -                | -                | -         |    -9.73 | bpg, DexteR, kindg, spankeer, Straafer     |
|           10 |     1593 | 2024-05-08 | Sensei Team         | L   | 1.000      | -            | -                | -                | -         |    -9.93 | antonini, pedrinzy, proSHOW, prt, Straafer |
|            9 |     1945 | 2024-05-01 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |   -11.91 | abr, CutzMeretz, jz, legy, paqueta         |
|            8 |     1963 | 2024-05-01 | MIBR Academy        | L   | 1.000      | -            | -                | -                | -         |   -12.38 | bpg, impax, kindg, shine, spankeer         |
|            7 |     2015 | 2024-04-30 | Romanticos          | L   | 1.000      | -            | -                | -                | -         |   -15.42 | bpg, impax, kindg, shine, spankeer         |
|            6 |     2051 | 2024-04-29 | paiN Gaming Academy | L   | 0.998      | -            | -                | -                | -         |   -13.11 | bpg, impax, kindg, shine, spankeer         |
|            5 |     3618 | 2024-04-01 | Hawks               | W   | 0.812      | 0.143        | 0.000 (0.000)    | 0.220 (0.026)    | 0 (0.000) |    13.21 | bpg, impax, kindg, shine, spankeer         |
|            4 |     3966 | 2024-03-23 | eSports Recife      | W   | 0.752      | 0.143        | 0.002 (0.000)    | 0.441 (0.047)    | 0 (0.000) |    13.02 | DANVIET, farias, Lineko, PremiuM, xns      |
|            3 |     3977 | 2024-03-23 | Corinthians Esports | L   | 0.751      | -            | -                | -                | -         |    -9.35 | abr, CutzMeretz, desh, legy, Leomonster    |
|            2 |     3983 | 2024-03-23 | MIBR Female         | W   | 0.751      | 0.143        | 0.015 (0.002)    | 0.217 (0.023)    | 0 (0.000) |    13.87 | bpg, impax, kindg, shine, spankeer         |
|            1 |     4542 | 2024-03-12 | Intense Game        | L   | 0.679      | -            | -                | -                | -         |    -7.34 | bsd, ckzao, diozera, mxa, Roz              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
