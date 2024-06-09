### Roster Details<br />
Team Name: Lausanne-Sport Esports<br />
Roster: berzerk, msn2k, SBT, SeBreeZe, xReal<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [215](../standings_global.md)<br />
Regional Rank: [144]( ../standings_europe.md)<br />
Final Rank Value:  710.3<br />
<br />
Final Rank Value (710.3) = Starting Rank Value (763.4) + Head To Head Adjustments (-53.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.315[<sup>2</sup>](#table1)
- Opponent Network: 0.130[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 763.4
- 400 + ( ( 0.179 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 763.4


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
|           31 |      403 | 2024-05-23 | ENRAGE                    | L   | 1.000      | -            | -                | -                | -         |   -23.99 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           30 |      586 | 2024-05-21 | FLuffy Gangsters          | L   | 1.000      | -            | -                | -                | -         |   -17.46 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           29 |     1156 | 2024-05-15 | Raptors Esports Club      | L   | 1.000      | -            | -                | -                | -         |   -13.77 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           28 |     1272 | 2024-05-14 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -14.63 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           27 |     1582 | 2024-05-09 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -6.01 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           26 |     1590 | 2024-05-09 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -10.35 | berzerk, msn2k, SBT, SeBreeZe, xReal |
|           25 |     2016 | 2024-05-01 | VP.Prodigy                | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.829 (0.309)    | 0 (0.000) |    16.49 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           24 |     2094 | 2024-04-29 | LEON Esports              | L   | 0.997      | -            | -                | -                | -         |   -18.31 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           23 |     2406 | 2024-04-24 | RoundsGG                  | W   | 0.964      | 0.372        | 0.000 (0.000)    | 0.251 (0.090)    | 0 (0.000) |     9.48 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           22 |     2559 | 2024-04-21 | RushOnGrandpa             | W   | 0.943      | 0.143        | 0.001 (0.000)    | 0.129 (0.017)    | 0 (0.000) |     6.48 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           21 |     2653 | 2024-04-20 | New Era                   | W   | 0.936      | 0.143        | 0.000 (0.000)    | 0.069 (0.009)    | 0 (0.000) |     5.35 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           20 |     2659 | 2024-04-20 | GenOne Academy            | W   | 0.936      | -            | -                | -                | 0 (0.000) |     3.65 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           19 |     2670 | 2024-04-20 | Assos                     | W   | 0.936      | -            | -                | -                | 0 (0.000) |     3.48 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           18 |     2684 | 2024-04-20 | MixeurMagimix             | W   | 0.935      | -            | -                | -                | 0 (0.000) |     3.30 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           17 |     2760 | 2024-04-19 | LODIS                     | W   | 0.930      | 0.372        | 0.001 (0.000)    | 0.140 (0.048)    | 0 (0.000) |     8.78 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           16 |     2832 | 2024-04-18 | DASH                      | L   | 0.922      | -            | -                | -                | -         |   -16.39 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           15 |     3182 | 2024-04-11 | FAVBET Team               | W   | 0.877      | 0.372        | 0.008 (0.003)    | 0.845 (0.276)    | 0 (0.000) |    20.29 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           14 |     3191 | 2024-04-11 | Grannys Knockers          | W   | 0.876      | 0.372        | 0.006 (0.002)    | 0.517 (0.169)    | 0 (0.000) |    15.14 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           13 |     3975 | 2024-03-26 | Metizport                 | L   | 0.771      | -            | -                | -                | -         |    -3.37 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           12 |     5766 | 2024-02-23 | CYBERSHOKE Esports        | L   | 0.557      | -            | -                | -                | -         |   -11.73 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           11 |     5878 | 2024-02-21 | UNiTY esports             | W   | 0.544      | 0.371        | 0.021 (0.004)    | 0.766 (0.155)    | -         |    11.68 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           10 |     5926 | 2024-02-20 | Rhyno Esports             | L   | 0.537      | -            | -                | -                | -         |    -3.62 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            9 |     5991 | 2024-02-19 | FLuffy Gangsters          | L   | 0.531      | -            | -                | -                | -         |   -11.53 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            8 |     6491 | 2024-02-09 | GenOne                    | L   | 0.463      | -            | -                | -                | -         |    -9.57 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            7 |     6513 | 2024-02-08 | INGLORIOUS                | L   | 0.458      | -            | -                | -                | -         |    -7.75 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            6 |     6817 | 2024-02-02 | Team Spirit Academy       | L   | 0.417      | -            | -                | -                | -         |    -7.25 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            5 |     6865 | 2024-02-01 | los kogutos               | W   | 0.411      | -            | -                | -                | -         |     2.74 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            4 |     6886 | 2024-02-01 | Nemiga Gaming             | W   | 0.410      | 0.371        | 0.358 (0.055)    | 0.895 (0.136)    | -         |    12.07 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            3 |     6933 | 2024-01-31 | HOTU                      | W   | 0.404      | 0.371        | 0.004 (0.001)    | 0.580 (0.087)    | -         |     7.91 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            2 |     7020 | 2024-01-29 | Fnatic                    | L   | 0.392      | -            | -                | -                | -         |    -1.33 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            1 |     7261 | 2024-01-26 | Permitta Esports          | L   | 0.370      | -            | -                | -                | -         |    -2.90 | Diviiii, msn2k, SBT, SeBreeZe, xReal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($603.30)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
