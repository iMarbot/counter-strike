### Roster Details<br />
Team Name: Phantom Troupe<br />
Roster: HoLLy, Lastík, Mix, semtex, suplicK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [424](../standings_global.md)<br />
Regional Rank: [256]( ../standings_europe.md)<br />
Final Rank Value:  535.0<br />
<br />
Final Rank Value (535.0) = Starting Rank Value (507.6) + Head To Head Adjustments (27.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.207[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 507.6
- 400 + ( ( 0.053 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 507.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     4710 | 2024-03-11 | Virtuoso Squad  | L   | 0.671      | -            | -                | -                | -         |   -11.62 | HoLLy, Lastík, Mix, semtex, suplicK      |
|           10 |     4768 | 2024-03-10 | DUSTY           | W   | 0.665      | 0.333        | 0.006 (0.001)    | 0.148 (0.033)    | 0 (0.000) |    14.52 | HoLLy, Lastík, Mix, semtex, suplicK      |
|            9 |     4920 | 2024-03-07 | Viperio         | L   | 0.645      | -            | -                | -                | -         |    -6.83 | HoLLy, Lastík, Mix, semtex, suplicK      |
|            8 |     4942 | 2024-03-07 | Dynamo Eclot    | L   | 0.644      | -            | -                | -                | -         |    -0.85 | HoLLy, Lastík, Mix, semtex, suplicK      |
|            7 |     5007 | 2024-03-06 | BRUTE           | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.157 (0.014)    | 0 (0.000) |    11.48 | HoLLy, Lastík, pandi7o, semtex, suplicK  |
|            6 |     5097 | 2024-03-05 | Griefers        | W   | 0.631      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.53 | HoLLy, Lastík, Mix, semtex, suplicK      |
|            5 |     5179 | 2024-03-04 | SINNERS Esports | L   | 0.624      | -            | -                | -                | -         |    -1.24 | HoLLy, Lastík, Mix, semtex, suplicK      |
|            4 |     5530 | 2024-02-27 | Lan Party Hotel | W   | 0.583      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     6.41 | czMarv, FABULOUSSS, lojzo, st2warD, Volt |
|            3 |     5577 | 2024-02-26 | ANDROMEDA       | W   | 0.576      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.28 | bevve, gejmzilla, Pepo, T4gg3D, woozzzi  |
|            2 |     7887 | 2024-01-16 | The Witchers    | L   | 0.305      | -            | -                | -                | -         |    -2.31 | Dragon, fear, Sdaim, smooya, synyx       |
|            1 |     7917 | 2024-01-16 | Maknitude       | W   | 0.304      | 0.143        | 0.001 (0.000)    | 0.020 (0.001)    | 0 (0.000) |     4.96 | Diirty, sly, Smokey, Speedie, sSen       |

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
