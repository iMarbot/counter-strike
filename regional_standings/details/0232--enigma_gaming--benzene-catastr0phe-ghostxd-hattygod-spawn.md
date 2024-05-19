### Roster Details<br />
Team Name: Enigma Gaming<br />
Roster: Benzene, Catastr0phE, ghostxD, hattygOD, SpawN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [232](../standings_global.md)<br />
Regional Rank: [40]( ../standings_asia.md)<br />
Final Rank Value:  679.5<br />
<br />
Final Rank Value (679.5) = Starting Rank Value (665.3) + Head To Head Adjustments (14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.3
- 400 + ( ( 0.134 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 665.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     3807 | 2024-02-09 | Grayfox Esports    | L   | 0.622      | -            | -                | -                | -         |    -9.34 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|           10 |     4120 | 2024-01-31 | Firedup Gaming     | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.019 (0.002)    | 0 (0.000) |     4.76 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            9 |     4202 | 2024-01-29 | Marcos Gaming      | W   | 0.550      | 0.143        | 0.086 (0.007)    | 0.087 (0.007)    | 0 (0.000) |    11.67 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            8 |     4227 | 2024-01-28 | True Rippers       | L   | 0.543      | -            | -                | -                | -         |    -4.45 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            7 |     4285 | 2024-01-27 | Gods Reign         | W   | 0.537      | 0.143        | 0.174 (0.013)    | 0.479 (0.037)    | 0 (0.000) |    13.54 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            6 |     4330 | 2024-01-26 | Grayfox Esports    | L   | 0.531      | -            | -                | -                | -         |    -7.75 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            5 |     4359 | 2024-01-25 | Firedup Gaming     | W   | 0.524      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     4.82 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            4 |     4764 | 2024-01-17 | Myth Avenue Gaming | L   | 0.469      | -            | -                | -                | -         |    -6.48 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            3 |     5297 | 2023-12-21 | Wasted Potential   | W   | 0.291      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     3.44 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            2 |     5305 | 2023-12-20 | Marcos Gaming      | W   | 0.284      | 0.143        | 0.086 (0.003)    | 0.087 (0.004)    | 0 (0.000) |     6.42 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            1 |     5408 | 2023-12-16 | Marcos Gaming      | L   | 0.262      | -            | -                | -                | -         |    -2.41 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($183.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-26 |      0.531 | $180.49        | $95.80          |
| 2023-12-21 |      0.291 | $300.60        | $87.48          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
