### Roster Details<br />
Team Name: Astralis<br />
Roster: br0, dev1ce, jabbi, Staehr, stavn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [10](../standings_global.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
Final Rank Value:  1602.7<br />
<br />
Final Rank Value (1602.7) = Starting Rank Value (1543.0) + Head To Head Adjustments (59.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.573[<sup>1</sup>](#table2)
- Bounty Collected: 0.642[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.887[<sup>2</sup>](#table1)

The average of these factors is 0.576<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1543.0
- 400 + ( ( 0.576 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1543.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      527 | 2024-04-24 | FaZe Clan     | W   | 1.000      | 0.889        | 1.000 (0.889)    | 0.566 (0.503)    | true (1.000) |    27.57 | br0, dev1ce, jabbi, Staehr, stavn    |
|           22 |      574 | 2024-04-23 | Eternal Fire  | W   | 1.000      | 0.889        | 0.409 (0.364)    | 0.462 (0.411)    | true (1.000) |    23.96 | br0, dev1ce, jabbi, Staehr, stavn    |
|           21 |     1120 | 2024-04-13 | FaZe Clan     | L   | 1.000      | -            | -                | -                | -            |    -3.37 | br0, dev1ce, jabbi, Staehr, stavn    |
|           20 |     1256 | 2024-04-10 | Virtus.pro    | W   | 1.000      | 0.624        | 0.454 (0.284)    | 0.416 (0.260)    | true (1.000) |    22.62 | br0, dev1ce, jabbi, Staehr, stavn    |
|           19 |     1311 | 2024-04-09 | FaZe Clan     | W   | 1.000      | 0.624        | 1.000 (0.624)    | 0.566 (0.354)    | true (1.000) |    28.73 | br0, dev1ce, jabbi, Staehr, stavn    |
|           18 |     1352 | 2024-04-08 | Steel Helmet  | W   | 1.000      | 0.624        | 0.025 (0.016)    | 0.174 (0.108)    | true (1.000) |     0.34 | br0, dev1ce, jabbi, Staehr, stavn    |
|           17 |     3222 | 2024-02-23 | 9Pandas       | L   | 0.717      | -            | -                | -                | -            |   -20.10 | blameF, dev1ce, jabbi, Staehr, stavn |
|           16 |     3265 | 2024-02-22 | ENCE          | L   | 0.710      | -            | -                | -                | -            |   -10.22 | blameF, dev1ce, jabbi, Staehr, stavn |
|           15 |     3326 | 2024-02-21 | Monte         | W   | 0.703      | 0.143        | 0.199 (0.020)    | 0.378 (0.038)    | true (0.703) |     7.01 | blameF, dev1ce, jabbi, Staehr, stavn |
|           14 |     3370 | 2024-02-20 | HEROIC        | L   | 0.697      | -            | -                | -                | -            |    -6.37 | blameF, dev1ce, jabbi, Staehr, stavn |
|           13 |     3395 | 2024-02-19 | Team Spirit   | L   | 0.692      | -            | -                | -                | -            |    -2.90 | blameF, dev1ce, jabbi, Staehr, stavn |
|           12 |     3420 | 2024-02-19 | Nexus Gaming  | W   | 0.691      | 0.143        | -                | 0.772 (0.076)    | true (0.691) |     0.64 | blameF, dev1ce, jabbi, Staehr, stavn |
|           11 |     4064 | 2024-02-01 | ENCE          | L   | 0.572      | -            | -                | -                | -            |    -9.66 | blameF, dev1ce, jabbi, Staehr, stavn |
|           10 |     4119 | 2024-01-31 | HEROIC        | L   | 0.564      | -            | -                | -                | -            |    -5.90 | blameF, dev1ce, jabbi, Staehr, stavn |
|            9 |     4224 | 2024-01-28 | BIG           | W   | 0.544      | 0.581        | 0.470 (0.149)    | 0.400 (0.127)    | true (0.544) |     6.10 | blameF, dev1ce, jabbi, Staehr, stavn |
|            8 |     4288 | 2024-01-27 | Team Vitality | L   | 0.537      | -            | -                | -                | -            |    -1.98 | blameF, dev1ce, jabbi, Staehr, stavn |
|            7 |     4431 | 2024-01-23 | Team Vitality | W   | 0.512      | 0.581        | 1.000 (0.297)    | 0.353 (0.105)    | true (0.512) |    14.41 | blameF, dev1ce, jabbi, Staehr, stavn |
|            6 |     4469 | 2024-01-22 | Team Falcons  | W   | 0.505      | 0.581        | 0.431 (0.127)    | 0.161 (0.047)    | true (0.505) |     4.43 | blameF, dev1ce, jabbi, Staehr, stavn |
|            5 |     4557 | 2024-01-20 | Pera Esports  | W   | 0.491      | -            | -                | -                | -            |     0.56 | blameF, dev1ce, jabbi, Staehr, stavn |
|            4 |     4604 | 2024-01-19 | AMKAL ESPORTS | L   | 0.485      | -            | -                | -                | -            |   -12.93 | blameF, dev1ce, jabbi, Staehr, stavn |
|            3 |     4658 | 2024-01-18 | Preasy Esport | W   | 0.478      | 0.143        | 0.106 (0.007)    | -                | -            |     0.62 | blameF, dev1ce, jabbi, Staehr, stavn |
|            2 |     5889 | 2023-12-07 | FURIA Esports | L   | 0.198      | -            | -                | -                | -            |    -2.12 | blameF, dev1ce, jabbi, Staehr, stavn |
|            1 |     5952 | 2023-12-06 | Virtus.pro    | L   | 0.190      | -            | -                | -                | -            |    -1.76 | blameF, dev1ce, jabbi, Staehr, stavn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($28,408.68)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-02-11 |      0.638 | $2,500.00      | $1,595.02       |
| 2024-01-28 |      0.545 | $12,500.00     | $6,813.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
