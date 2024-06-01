### Roster Details<br />
Team Name: iNation<br />
Roster: aidKiT, c0llins, Dragon, emi, xicoz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [173](../standings_global.md)<br />
Regional Rank: [119]( ../standings_europe.md)<br />
Final Rank Value:  754.6<br />
<br />
Final Rank Value (754.6) = Starting Rank Value (653.2) + Head To Head Adjustments (101.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.168[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 653.2
- 400 + ( ( 0.124 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 653.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      272 | 2024-05-25 | Zero Tenacity   | L   | 1.000      | -            | -                | -                | -         |    -5.29 | aidKiT, c0llins, Dragon, emi, xicoz           |
|           11 |      295 | 2024-05-25 | UNiTY esports   | W   | 1.000      | 0.371        | 0.021 (0.008)    | 0.766 (0.284)    | 0 (0.000) |    20.90 | aidKiT, c0llins, Dragon, emi, xicoz           |
|           10 |      363 | 2024-05-24 | ex-Guild Eagles | L   | 1.000      | -            | -                | -                | -         |    -7.86 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            9 |      620 | 2024-05-21 | kONO.ECF        | W   | 1.000      | 0.371        | 0.013 (0.005)    | 0.778 (0.288)    | 0 (0.000) |    22.48 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            8 |     1370 | 2024-05-12 | Regnum          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.050 (0.007)    | 0 (0.000) |    11.27 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            7 |     1386 | 2024-05-12 | GOT             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     4.96 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            6 |     2178 | 2024-04-27 | ILLYRIANS       | W   | 0.983      | 0.143        | 0.000 (0.000)    | 0.319 (0.045)    | 0 (0.000) |    17.40 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            5 |     2198 | 2024-04-27 | GOT             | W   | 0.982      | 0.143        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |     5.55 | aidKiT, c0llins, Dragon, emi, xicoz           |
|            4 |     2761 | 2024-04-18 | BetBoom Team    | L   | 0.923      | -            | -                | -                | -         |    -0.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte       |
|            3 |     2828 | 2024-04-17 | ARCRED          | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.630 (0.083)    | 0 (0.000) |    19.41 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx        |
|            2 |     3669 | 2024-03-30 | Sangrija        | W   | 0.797      | 0.143        | 0.000 (0.000)    | 0.022 (0.002)    | 1 (0.797) |     8.50 | andr1x, illya, kdaN, RiiL3, zecco             |
|            1 |     3687 | 2024-03-30 | Kum sa Kosova   | W   | 0.796      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.796) |     4.80 | bromare, Harambasaa, ralelele, revchuk, ZON1X |

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
