### Roster Details<br />
Team Name: Atrix Esports<br />
Roster: bokor, LyttleZ, mari, s1non, sofiaxyz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [255](../standings_global.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
Final Rank Value:  659.2<br />
<br />
Final Rank Value (659.2) = Starting Rank Value (689.6) + Head To Head Adjustments (-30.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.6
- 400 + ( ( 0.146 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 689.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      343 | 2024-04-27 | FURIA Esports Female      | L   | 1.000      | -            | -                | -                | -             |   -10.89 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|           13 |      346 | 2024-04-27 | ODDIK Academy             | L   | 1.000      | -            | -                | -                | -             |   -16.99 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|           12 |      799 | 2024-04-19 | Illusion (Brazilian team) | W   | 1.000      | 0.332        | 0.008 (0.003)    | 0.035 (0.012)    | false (0.000) |    12.05 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|           11 |     1165 | 2024-04-11 | DIVINA Female             | W   | 1.000      | 0.332        | 0.009 (0.003)    | 0.078 (0.026)    | false (0.000) |    15.30 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|           10 |     1470 | 2024-04-04 | MIBR Female               | L   | 0.993      | -            | -                | -                | -             |   -14.40 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            9 |     1853 | 2024-03-24 | Rocket.GG                 | L   | 0.919      | -            | -                | -                | -             |   -16.11 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            8 |     1854 | 2024-03-24 | NIGERIA ACADEMY           | W   | 0.919      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.59 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            7 |     1877 | 2024-03-23 | Bulls 95                  | W   | 0.914      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.87 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            6 |     1958 | 2024-03-21 | FURIA Esports Female      | L   | 0.900      | -            | -                | -                | -             |    -9.15 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            5 |     2247 | 2024-03-14 | GENKID4M4                 | W   | 0.853      | 0.332        | 0.008 (0.002)    | 0.052 (0.015)    | false (0.000) |    13.36 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            4 |     2599 | 2024-03-06 | Fluxo Demons              | L   | 0.800      | -            | -                | -                | -             |    -6.21 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            3 |     4530 | 2024-01-20 | Baludinhas                | L   | 0.493      | -            | -                | -                | -             |    -8.60 | bokor, LyttleZ, mari, s1non, sofiaxyz  |
|            2 |     6767 | 2023-11-17 | MIBR Female               | L   | 0.065      | -            | -                | -                | -             |    -0.88 | bokor, LyttleZ, mari, s1non, yodinha2k |
|            1 |     6798 | 2023-11-16 | Fluxo Demons              | L   | 0.060      | -            | -                | -                | -             |    -0.38 | bokor, LyttleZ, mari, s1non, yodinha2k |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,611.53)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-19 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-03-25 |      0.927 | $79.96         | $74.12          |
| 2023-11-18 |      0.073 | $509.59        | $37.42          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
