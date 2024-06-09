### Roster Details<br />
Team Name: M1X<br />
Roster: ammar, gejmzilla, prelideN, rilax, v1w<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [351](../standings_global.md)<br />
Regional Rank: [210]( ../standings_europe.md)<br />
Final Rank Value:  607.3<br />
<br />
Final Rank Value (607.3) = Starting Rank Value (602.0) + Head To Head Adjustments (5.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.215[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.010[<sup>2</sup>](#table1)

The average of these factors is 0.099<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 602.0
- 400 + ( ( 0.099 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 602.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1847 | 2024-05-04 | ILLYRIANS     | L   | 1.000      | -            | -                | -                | -         |   -10.11 | ammar, gejmzilla, prelideN, rilax, v1w       |
|           11 |     1861 | 2024-05-04 | Regnum        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.050 (0.007)    | 0 (0.000) |    15.83 | ammar, gejmzilla, prelideN, rilax, v1w       |
|           10 |     1913 | 2024-05-03 | Kum sa Kosova | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.54 | ammar, arbnorz, gejmzilla, prelideN, rilax   |
|            9 |     5147 | 2024-03-04 | HAVU Gaming   | L   | 0.625      | -            | -                | -                | -         |    -5.83 | gejmzilla, kressy, PrelideN, rilax, v1w      |
|            8 |     7035 | 2024-01-29 | PARIVISION    | L   | 0.392      | -            | -                | -                | -         |    -1.71 | gejmzilla, PALM1, PrelideN, rilax, zur1s     |
|            7 |     7899 | 2024-01-16 | esmagaB       | L   | 0.304      | -            | -                | -                | -         |    -1.90 | Ag1l, aragornN, NOPEEj, pr, rafaxF           |
|            6 |     7921 | 2024-01-16 | BIT eSports   | W   | 0.304      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.34 | Krimson, NinjaStyle, r1ch, RaY5ive, Z1gaZaga |
|            5 |     8747 | 2023-12-17 | Midnight      | L   | 0.102      | -            | -                | -                | -         |    -1.65 | ammar, cerber, deb0, gejmzilla, v1w          |
|            4 |     8842 | 2023-12-16 | Ezezepanamera | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.098) |     0.75 | dilla, gmart1nii, MELLOWi, muLche, noaHH2    |
|            3 |     9516 | 2023-12-06 | Passion UA    | L   | 0.029      | -            | -                | -                | -         |    -0.08 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            2 |     9656 | 2023-12-03 | HamaKura      | W   | 0.010      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.07 | ammar, cerber, deb0, gejmzilla, v1w          |
|            1 |     9795 | 2023-12-02 | The Witchers  | L   | 0.002      | -            | -                | -                | -         |    -0.02 | fear, Sdaim, smooya, soulfly, synyx          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($66.55)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.104 | $545.37        | $56.73          |
| 2023-12-03 |      0.010 | $1,000.00      | $9.81           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
