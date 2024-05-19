### Roster Details<br />
Team Name: Lausanne-Sport Esports<br />
Roster: Diviiii, msn2k, SBT, SeBreeZe, xReal<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [172](../standings_global.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
Final Rank Value:  751.7<br />
<br />
Final Rank Value (751.7) = Starting Rank Value (749.1) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.358[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 749.1
- 400 + ( ( 0.176 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 749.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      650 | 2024-04-21 | RushOnGrandpa               | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.176 (0.025)    | false (0.000) |     8.35 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           16 |      732 | 2024-04-20 | New Era (French team)       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.110 (0.016)    | false (0.000) |     7.15 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           15 |      737 | 2024-04-20 | GenOne Academy              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | false (0.000) |     4.72 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           14 |      748 | 2024-04-20 | Assos                       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | false (0.000) |     4.58 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           13 |      760 | 2024-04-20 | MixeurMagimix               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.35 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           12 |     1813 | 2024-03-26 | Metizport                   | L   | 0.932      | -            | -                | -                | -             |    -2.51 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           11 |     3211 | 2024-02-23 | CYBERSHOKE Esports          | L   | 0.718      | -            | -                | -                | -             |   -11.32 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|           10 |     3309 | 2024-02-21 | UNiTY esports (Slovak team) | W   | 0.705      | 0.371        | 0.055 (0.014)    | 0.727 (0.190)    | false (0.000) |    16.29 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            9 |     3348 | 2024-02-20 | Rhyno Esports               | L   | 0.698      | -            | -                | -                | -             |    -6.08 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            8 |     3399 | 2024-02-19 | FLuffy Gangsters            | L   | 0.692      | -            | -                | -                | -             |   -14.71 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            7 |     3796 | 2024-02-09 | GenOne                      | L   | 0.624      | -            | -                | -                | -             |   -13.99 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            6 |     3816 | 2024-02-08 | INGLORIOUS                  | L   | 0.619      | -            | -                | -                | -             |    -8.67 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            5 |     4031 | 2024-02-02 | Team Spirit Academy         | L   | 0.578      | -            | -                | -                | -             |    -8.09 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            4 |     4080 | 2024-02-01 | Nemiga Gaming               | W   | 0.571      | 0.371        | 0.680 (0.144)    | 0.910 (0.193)    | false (0.000) |    17.22 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            3 |     4112 | 2024-01-31 | HOTU                        | W   | 0.565      | 0.371        | 0.011 (0.002)    | 0.323 (0.068)    | false (0.000) |     9.68 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            2 |     4177 | 2024-01-29 | Fnatic                      | L   | 0.553      | -            | -                | -                | -             |    -1.04 | Diviiii, msn2k, SBT, SeBreeZe, xReal |
|            1 |     4317 | 2024-01-26 | Permitta Esports            | L   | 0.531      | -            | -                | -                | -             |    -3.38 | Diviiii, msn2k, SBT, SeBreeZe, xReal |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($640.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
