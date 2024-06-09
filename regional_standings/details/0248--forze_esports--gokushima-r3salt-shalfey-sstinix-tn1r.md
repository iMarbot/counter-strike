### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: gokushima, r3salt, shalfey, sstiNiX, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [248](../standings_global.md)<br />
Regional Rank: [163]( ../standings_europe.md)<br />
Final Rank Value:  690.1<br />
<br />
Final Rank Value (690.1) = Starting Rank Value (664.4) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.238[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 664.4
- 400 + ( ( 0.130 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 664.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     6960 | 2024-01-30 | Sashi Esport        | L   | 0.398      | -            | -                | -                | -         |    -1.37 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|            9 |     6978 | 2024-01-30 | GUN5 Esports        | W   | 0.397      | 0.143        | 0.000 (0.000)    | 0.143 (0.008)    | 0 (0.000) |     5.02 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|            8 |     7003 | 2024-01-29 | ex-Preasy Esport    | W   | 0.392      | 0.143        | 0.052 (0.003)    | 0.381 (0.021)    | 0 (0.000) |     9.84 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|            7 |     7027 | 2024-01-29 | TSM                 | W   | 0.392      | 0.143        | 0.011 (0.001)    | 0.170 (0.009)    | 0 (0.000) |     7.70 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|            6 |     9223 | 2023-12-10 | 3DMAX               | L   | 0.058      | -            | -                | -                | -         |    -0.32 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            5 |     9285 | 2023-12-09 | SINNERS Esports     | W   | 0.051      | 0.500        | 0.011 (0.000)    | 0.582 (0.015)    | 0 (0.000) |     1.41 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            4 |     9369 | 2023-12-08 | Apeks               | W   | 0.044      | 0.500        | 0.085 (0.002)    | 0.345 (0.008)    | 0 (0.000) |     1.33 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            3 |     9438 | 2023-12-07 | Team Spirit Academy | W   | 0.037      | 0.500        | 0.004 (0.000)    | 0.229 (0.004)    | 0 (0.000) |     0.70 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            2 |     9500 | 2023-12-06 | Team Space          | W   | 0.031      | 0.500        | 0.009 (0.000)    | 0.457 (0.007)    | 0 (0.000) |     0.72 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            1 |     9565 | 2023-12-05 | KOI                 | W   | 0.024      | 0.500        | 0.027 (0.000)    | 0.455 (0.006)    | 0 (0.000) |     0.65 | gokushima, Krad, r3salt, shalfey, tN1R    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($690.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
