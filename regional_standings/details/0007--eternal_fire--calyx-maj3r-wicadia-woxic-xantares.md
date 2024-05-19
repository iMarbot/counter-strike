### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [7](../standings_global.md)<br />
Regional Rank: [7]( ../standings_europe.md)<br />
Final Rank Value:  1728.5<br />
<br />
Final Rank Value (1728.5) = Starting Rank Value (1798.9) + Head To Head Adjustments (-70.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.720[<sup>1</sup>](#table2)
- Bounty Collected: 0.726[<sup>2</sup>](#table1)
- Opponent Network: 0.407[<sup>2</sup>](#table1)
- LAN Wins: 0.967[<sup>2</sup>](#table1)

The average of these factors is 0.705<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1798.9
- 400 + ( ( 0.705 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1798.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      358 | 2024-04-27 | SAW               | L   | 1.000      | -            | -                | -                | -         |   -26.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           40 |      427 | 2024-04-26 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |    -8.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           39 |      463 | 2024-04-25 | Fnatic            | W   | 1.000      | 0.889        | 0.334 (0.297)    | 0.683 (0.607)    | 1 (1.000) |     1.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           38 |      526 | 2024-04-24 | Imperial Esports  | W   | 1.000      | 0.889        | 0.674 (0.599)    | 0.549 (0.488)    | 1 (1.000) |     4.97 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      574 | 2024-04-23 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -23.96 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      705 | 2024-04-20 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |   -30.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      812 | 2024-04-19 | Sashi Esport      | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | -         |     0.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      836 | 2024-04-19 | BetBoom Team      | W   | 1.000      | 0.143        | 0.571 (0.082)    | -                | -         |     2.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1663 | 2024-03-29 | Natus Vincere     | L   | 0.951      | -            | -                | -                | -         |   -10.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1918 | 2024-03-23 | Virtus.pro        | W   | 0.910      | 1.000        | 0.454 (0.414)    | 0.416 (0.379)    | 1 (0.910) |    11.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1946 | 2024-03-22 | FaZe Clan         | W   | 0.904      | 1.000        | 1.000 (0.904)    | 0.566 (0.512)    | 1 (0.904) |    19.82 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1982 | 2024-03-21 | MOUZ              | L   | 0.898      | -            | -                | -                | -         |   -10.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1991 | 2024-03-21 | Team Vitality     | W   | 0.897      | 1.000        | 1.000 (0.897)    | 0.353 (0.317)    | 1 (0.897) |    17.19 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     2069 | 2024-03-19 | GamerLegion       | W   | 0.884      | 1.000        | 0.194 (0.171)    | 0.419 (0.370)    | 1 (0.884) |     5.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     2099 | 2024-03-18 | HEROIC            | L   | 0.877      | -            | -                | -                | -         |   -17.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     2130 | 2024-03-17 | PaiN Gaming       | W   | 0.872      | -            | -                | -                | 1 (0.872) |     0.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     2151 | 2024-03-17 | The MongolZ       | W   | 0.870      | 1.000        | 0.292 (0.254)    | 0.663 (0.577)    | 1 (0.870) |     7.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     3492 | 2024-02-17 | BetBoom Team      | W   | 0.678      | -            | -                | -                | 1 (0.678) |     2.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     3542 | 2024-02-16 | FaZe Clan         | L   | 0.671      | -            | -                | -                | -         |    -5.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     3602 | 2024-02-15 | Team Falcons      | W   | 0.663      | -            | -                | -                | 1 (0.663) |     2.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     3620 | 2024-02-14 | G2 Esports        | L   | 0.659      | -            | -                | -                | -         |    -8.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     3640 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.657      | -            | -                | -                | -         |     0.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     3885 | 2024-02-05 | Natus Vincere     | L   | 0.599      | -            | -                | -                | -         |    -5.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     3914 | 2024-02-04 | FaZe Clan         | L   | 0.592      | -            | -                | -                | -         |    -4.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     3999 | 2024-02-03 | Team Falcons      | W   | 0.584      | 1.000        | 0.431 (0.252)    | -                | -         |     1.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     4098 | 2024-01-31 | Rebels Gaming     | W   | 0.566      | 1.000        | -                | 0.376 (0.212)    | -         |     0.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     4118 | 2024-01-31 | BetBoom Team      | W   | 0.564      | 1.000        | 0.571 (0.322)    | 0.824 (0.465)    | -         |     2.69 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     4603 | 2024-01-19 | MOUZ              | W   | 0.485      | -            | -                | -                | -         |     9.18 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     4656 | 2024-01-18 | IKLA              | W   | 0.478      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     4672 | 2024-01-18 | Pera Esports      | W   | 0.478      | -            | -                | -                | -         |     0.12 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     6388 | 2023-11-26 | Monte             | L   | 0.125      | -            | -                | -                | -         |    -3.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     6403 | 2023-11-26 | MIBR              | W   | 0.123      | -            | -                | -                | -         |     1.26 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     6437 | 2023-11-25 | Nouns Esports     | W   | 0.118      | -            | -                | -                | -         |     0.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     6449 | 2023-11-25 | TYLOO             | W   | 0.116      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     6495 | 2023-11-24 | Nouns Esports     | L   | 0.110      | -            | -                | -                | -         |    -3.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     6641 | 2023-11-20 | 9Pandas           | L   | 0.085      | -            | -                | -                | -         |    -2.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     6664 | 2023-11-19 | MIBR              | W   | 0.078      | -            | -                | -                | -         |     0.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     6774 | 2023-11-17 | FURIA Esports     | W   | 0.065      | -            | -                | -                | -         |     0.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     6821 | 2023-11-16 | Fantazeri         | W   | 0.058      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     6938 | 2023-11-14 | BIG               | L   | 0.044      | -            | -                | -                | -         |    -1.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     7062 | 2023-11-11 | Aurora Gaming     | L   | 0.024      | -            | -                | -                | -         |    -0.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($64,837.55)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.41) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-03-31 |      0.965 | $45,000.00     | $43,435.42      |
| 2024-02-11 |      0.638 | $16,000.00     | $10,208.15      |
| 2023-11-26 |      0.125 | $20,000.00     | $2,500.46       |
| 2023-11-20 |      0.085 | $20,000.00     | $1,693.52       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
