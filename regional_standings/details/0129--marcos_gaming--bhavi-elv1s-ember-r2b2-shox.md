### Roster Details<br />
Team Name: Marcos Gaming<br />
Roster: Bhavi, ELV1S, EmbeR, R2B2, shox<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [129](../standings_global.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
Final Rank Value:  807.2<br />
<br />
Final Rank Value (807.2) = Starting Rank Value (823.9) + Head To Head Adjustments (-16.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.290[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.070[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 823.9
- 400 + ( ( 0.214 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 823.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     3779 | 2024-02-10 | Pak Boyz        | W   | 0.630      | 0.435        | 0.032 (0.009)    | 0.059 (0.016)    | true (0.630)  |     4.92 | Bhavi, ELV1S, EmbeR, R2B2, shox                   |
|           14 |     3782 | 2024-02-09 | True Rippers    | L   | 0.628      | -            | -                | -                | -             |    -8.21 | Bhavi, ELV1S, EmbeR, R2B2, shox                   |
|           13 |     4054 | 2024-02-02 | Gods Reign      | W   | 0.576      | 0.143        | 0.174 (0.014)    | 0.479 (0.039)    | false (0.000) |    10.98 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|           12 |     4154 | 2024-01-30 | Firedup Gaming  | W   | 0.557      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | false (0.000) |     2.91 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|           11 |     4202 | 2024-01-29 | Enigma Gaming   | L   | 0.550      | -            | -                | -                | -             |   -11.67 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|           10 |     4289 | 2024-01-27 | True Rippers    | L   | 0.536      | -            | -                | -                | -             |    -7.46 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|            9 |     4567 | 2024-01-20 | Carnival Gaming | L   | 0.490      | -            | -                | -                | -             |    -9.80 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|            8 |     5298 | 2023-12-21 | ROG Academy     | W   | 0.290      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | false (0.000) |     1.26 | arakyn, BrOCK, KillSwiTcH, SeeK, vrenyy           |
|            7 |     5305 | 2023-12-20 | Enigma Gaming   | L   | 0.284      | -            | -                | -                | -             |    -6.42 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn               |
|            6 |     5401 | 2023-12-17 | Gods Reign      | W   | 0.263      | 0.262        | 0.174 (0.012)    | 0.479 (0.033)    | false (0.000) |     5.62 | Bhavi, ELV1S, EmbeR, Nox, reV3nnnn                |
|            5 |     5408 | 2023-12-16 | Enigma Gaming   | W   | 0.262      | 0.262        | 0.001 (0.000)    | 0.068 (0.005)    | false (0.000) |     2.41 | Bhavi, ELV1S, EmbeR, Nox, reV3nnnn                |
|            4 |     6535 | 2023-11-22 | Carnival Gaming | L   | 0.102      | -            | -                | -                | -             |    -2.07 | Bhavi, Elvis, EmbeR, R2B2, reV3nnnn               |
|            3 |     6609 | 2023-11-21 | Carnival Gaming | W   | 0.090      | 0.143        | 0.013 (0.000)    | 0.056 (0.001)    | false (0.000) |     1.01 | Benzene, Catastr0phE, hattygOD, Rider, SpawN      |
|            2 |     6657 | 2023-11-19 | True Rippers    | W   | 0.082      | 0.143        | 0.059 (0.001)    | 0.272 (0.003)    | false (0.000) |     1.41 | Defaulter, DiceDealer, Gh0sTTTT, Mcg1LLzZz, Rossi |
|            1 |     6722 | 2023-11-18 | RGW Esports     | L   | 0.071      | -            | -                | -                | -             |    -1.66 | Benzene, Bhavi, Elvis, hattygOD, R2B2             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,648.04)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-10 |      0.630 | $20,000.00     | $12,593.98      |
| 2024-01-20 |      0.490 | $1,503.76      | $736.77         |
| 2023-12-21 |      0.291 | $60.12         | $17.50          |
| 2023-12-17 |      0.263 | $1,000.00      | $262.94         |
| 2023-11-22 |      0.102 | $360.19        | $36.85          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
