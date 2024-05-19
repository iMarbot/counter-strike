### Roster Details<br />
Team Name: ALTERNATE aTTaX Evo<br />
Roster: devils, FoG, HuNt3rz, Miku, Rulz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [262](../standings_global.md)<br />
Regional Rank: [164]( ../standings_europe.md)<br />
Final Rank Value:  653.8<br />
<br />
Final Rank Value (653.8) = Starting Rank Value (711.7) + Head To Head Adjustments (-57.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.299[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.7
- 400 + ( ( 0.157 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 711.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      357 | 2024-04-27 | TeamOrangeGaming        | L   | 1.000      | -            | -                | -                | -             |   -10.26 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           15 |      388 | 2024-04-27 | Pandaric eSports        | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.000 (0.000)    | true (1.000)  |     9.42 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           14 |      524 | 2024-04-24 | Team Solid (Swiss team) | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.052 (0.007)    | false (0.000) |    10.54 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           13 |      630 | 2024-04-21 | Reveal (German team)    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     6.20 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           12 |     1148 | 2024-04-12 | OTHERSCANTBEAT          | L   | 1.000      | -            | -                | -                | -             |   -21.68 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           11 |     1478 | 2024-04-04 | Entropy Future          | W   | 0.992      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     5.92 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           10 |     1812 | 2024-03-26 | Sissi State Punks       | L   | 0.932      | -            | -                | -                | -             |   -12.33 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            9 |     1822 | 2024-03-26 | Wave Esports            | W   | 0.932      | 0.143        | 0.004 (0.000)    | 0.113 (0.015)    | false (0.000) |    13.00 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            8 |     1904 | 2024-03-23 | EP Genesis              | L   | 0.912      | -            | -                | -                | -             |   -18.77 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            7 |     2052 | 2024-03-19 | Metizport X             | L   | 0.885      | -            | -                | -                | -             |   -17.94 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            6 |     2622 | 2024-03-06 | Wave Esports            | W   | 0.798      | 0.143        | 0.004 (0.000)    | 0.113 (0.013)    | false (0.000) |    11.11 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            5 |     2756 | 2024-03-04 | OTHERSCANTBEAT          | L   | 0.785      | -            | -                | -                | -             |   -18.73 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            4 |     2780 | 2024-03-03 | SNOGARD Dragons         | L   | 0.779      | -            | -                | -                | -             |   -12.35 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            3 |     3071 | 2024-02-26 | Kappa Bar               | L   | 0.739      | -            | -                | -                | -             |   -13.86 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            2 |     3234 | 2024-02-22 | EVOPLAY                 | W   | 0.712      | 0.143        | 0.000 (0.000)    | 0.025 (0.003)    | false (0.000) |     5.38 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            1 |     4462 | 2024-01-22 | Wave Esports            | W   | 0.505      | 0.143        | 0.004 (0.000)    | 0.113 (0.008)    | false (0.000) |     6.41 | Anomatronik, devils, FoG, Miku, Rulz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($722.78)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $535.13        | $535.13         |
| 2024-03-26 |      0.932 | $108.40        | $101.06         |
| 2024-03-06 |      0.798 | $108.45        | $86.59          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
