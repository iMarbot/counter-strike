### Roster Details<br />
Team Name: Hyper5<br />
Roster: axZy, Lyme, Pikalee, pms, Shu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [337](../standings_global.md)<br />
Regional Rank: [53]( ../standings_asia.md)<br />
Final Rank Value:  617.2<br />
<br />
Final Rank Value (617.2) = Starting Rank Value (614.3) + Head To Head Adjustments (2.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.131[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.105<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 614.3
- 400 + ( ( 0.105 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 614.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     8595 | 2023-12-23 | Những Chàng Trai Đeo Kính | L   | 0.142      | -            | -                | -                | -         |    -2.11 | axZy, Lyme, Pikalee, pms, Shu        |
|           14 |     8776 | 2023-12-16 | EZ Esport                 | W   | 0.101      | 0.143        | 0.000 (0.000)    | 0.013 (0.000)    | 1 (0.101) |     1.49 | Lyme, Pikalee, pms, Richard, Shu     |
|           13 |     8785 | 2023-12-16 | Cao Huyết Áp              | W   | 0.101      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 1 (0.101) |     1.42 | Lyme, Pikalee, pms, Richard, Shu     |
|           12 |     8792 | 2023-12-16 | BiuTiPhuCanTri            | W   | 0.100      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.100) |     1.34 | Lyme, Pikalee, pms, Richard, Shu     |
|           11 |     8919 | 2023-12-16 | TUCNA                     | W   | 0.095      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.095) |     1.01 | Lyme, Pikalee, pms, Richard, Shu     |
|           10 |     8940 | 2023-12-15 | TUCNA                     | W   | 0.094      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 1 (0.094) |     1.00 | Lyme, Pikalee, pms, Richard, Shu     |
|            9 |     8962 | 2023-12-15 | 1PinG                     | W   | 0.093      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.093) |     0.70 | Lyme, Pikalee, pms, Richard, Shu     |
|            8 |     9014 | 2023-12-15 | The QUBE Esports          | L   | 0.089      | -            | -                | -                | -         |    -1.59 | Guckj, Lyme, Pikalee, pms, Shu       |
|            7 |     9199 | 2023-12-11 | DEWA United               | L   | 0.063      | -            | -                | -                | -         |    -1.00 | Guckj, Lyme, Pikalee, pms, Shu       |
|            6 |     9244 | 2023-12-10 | ZEUSGG                    | W   | 0.056      | 0.250        | 0.000 (0.000)    | 0.090 (0.001)    | 0 (0.000) |     0.77 | Guckj, Lyme, Pikalee, pms, Shu       |
|            5 |     9302 | 2023-12-09 | RAVENS                    | W   | 0.049      | 0.250        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.36 | Guckj, Lyme, Pikalee, pms, Shu       |
|            4 |     9448 | 2023-12-07 | Eruption                  | L   | 0.036      | -            | -                | -                | -         |    -0.60 | Guckj, Lyme, Pikalee, pms, Shu       |
|            3 |     9589 | 2023-12-05 | Guardian 5                | W   | 0.023      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Guckj, Lyme, Pikalee, pms, Shu       |
|            2 |     9688 | 2023-12-02 | Những Chàng Trai Đeo Kính | L   | 0.008      | -            | -                | -                | -         |    -0.12 | Lyme, Pikalee, pms, Shu, Soncam-1603 |
|            1 |     9690 | 2023-12-02 | ONS                       | W   | 0.007      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.07 | Lyme, Pikalee, pms, Shu, Soncam-1603 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($130.82)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.142 | $659.79        | $93.36          |
| 2023-12-16 |      0.101 | $288.36        | $29.22          |
| 2023-12-13 |      0.076 | $100.00        | $7.60           |
| 2023-12-02 |      0.008 | $82.34         | $0.64           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
