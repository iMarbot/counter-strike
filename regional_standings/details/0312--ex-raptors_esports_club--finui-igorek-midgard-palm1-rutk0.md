### Roster Details<br />
Team Name: ex-Raptors Esports Club<br />
Roster: Finui, Igorek, Midgard, PALM1, Rutk0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [312](../standings_global.md)<br />
Regional Rank: [191]( ../standings_europe.md)<br />
Final Rank Value:  630.9<br />
<br />
Final Rank Value (630.9) = Starting Rank Value (645.5) + Head To Head Adjustments (-14.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.194[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.059[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.5
- 400 + ( ( 0.121 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 645.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     4192 | 2024-03-18 | NeedMoreBullets  | W   | 0.718      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     5.08 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           15 |     4257 | 2024-03-17 | FearFerox        | L   | 0.711      | -            | -                | -                | -         |   -11.36 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           14 |     4585 | 2024-03-11 | Voracity Esports | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.46 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           13 |     4663 | 2024-03-10 | Virtuoso Squad   | L   | 0.664      | -            | -                | -                | -         |   -14.60 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           12 |     4935 | 2024-03-05 | naChille         | L   | 0.631      | -            | -                | -                | -         |   -10.12 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           11 |     5574 | 2024-02-24 | ROYALS           | L   | 0.562      | -            | -                | -                | -         |    -7.82 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|           10 |     5592 | 2024-02-23 | Katana Gaming    | W   | 0.559      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.559) |     3.24 | duck, J0SH, Loordd, Proq, Ties             |
|            9 |     6284 | 2024-02-09 | Part Timers      | W   | 0.465      | 0.143        | 0.001 (0.000)    | 0.147 (0.010)    | 0 (0.000) |     8.62 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|            8 |     6287 | 2024-02-09 | Reason Gaming    | W   | 0.465      | 0.143        | 0.004 (0.000)    | 0.133 (0.009)    | 0 (0.000) |    10.37 | Finui, Igorek, Midgard, PALM1, Rutk0       |
|            7 |     6857 | 2024-01-28 | ROYALS           | L   | 0.385      | -            | -                | -                | -         |    -4.99 | Finui, Igorek, OxidE, PALM1, Rutk0         |
|            6 |     6912 | 2024-01-27 | Shaman Esports   | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     2.78 | AliBond, godkU, Jared, maniac, Ourob       |
|            5 |     6918 | 2024-01-27 | DUSTY            | W   | 0.379      | 0.143        | 0.006 (0.000)    | 0.148 (0.008)    | 0 (0.000) |     7.63 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            4 |     6929 | 2024-01-27 | Part Timers      | L   | 0.378      | -            | -                | -                | -         |    -8.30 | ifan, isk, m0g, Rhys, Ziimzey              |
|            3 |     7024 | 2024-01-26 | EXO Clan         | L   | 0.371      | -            | -                | -                | -         |    -1.60 | Finui, Igorek, OxidE, PALM1, Rutk0         |
|            2 |     7026 | 2024-01-26 | Part Timers      | W   | 0.371      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | 0 (0.000) |     3.55 | eMy, ifan, isk, Rhys, Ziimzey              |
|            1 |     7075 | 2024-01-25 | EXO Clan         | L   | 0.365      | -            | -                | -                | -         |    -1.57 | Finui, Igorek, OxidE, PALM1, Rutk0         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($114.27)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
