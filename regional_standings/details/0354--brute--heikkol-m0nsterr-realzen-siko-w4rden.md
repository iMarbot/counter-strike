### Roster Details<br />
Team Name: BRUTE<br />
Roster: heikkoL, m0nsterr, realzen, SiKO, w4rden<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [354](../standings_global.md)<br />
Regional Rank: [221]( ../standings_europe.md)<br />
Final Rank Value:  473.8<br />
<br />
Final Rank Value (473.8) = Starting Rank Value (517.6) + Head To Head Adjustments (-43.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.219[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 517.6
- 400 + ( ( 0.059 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 517.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      569 | 2024-04-23 | EP Genesis            | L   | 1.000      | -            | -                | -                | -             |   -12.41 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           17 |      828 | 2024-04-19 | Dynamo Eclot Thunders | L   | 1.000      | -            | -                | -                | -             |   -20.87 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           16 |     1415 | 2024-04-06 | Verdant               | L   | 1.000      | -            | -                | -                | -             |    -2.88 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           15 |     1589 | 2024-04-02 | ROSOMAHA              | L   | 0.977      | -            | -                | -                | -             |   -12.22 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           14 |     1821 | 2024-03-26 | Natus Vincere Youth   | L   | 0.932      | -            | -                | -                | -             |    -8.22 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           13 |     1941 | 2024-03-22 | Sashi Academy         | L   | 0.905      | -            | -                | -                | -             |    -9.38 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           12 |     2572 | 2024-03-07 | GamerLegion Academy   | L   | 0.805      | -            | -                | -                | -             |    -4.40 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           11 |     2623 | 2024-03-06 | Team Universe         | L   | 0.798      | -            | -                | -                | -             |   -10.17 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           10 |     2754 | 2024-03-04 | Sashi Academy         | W   | 0.785      | 0.289        | 0.004 (0.001)    | 0.143 (0.032)    | false (0.000) |    16.50 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            9 |     2758 | 2024-03-04 | Dynamo Eclot          | L   | 0.785      | -            | -                | -                | -             |    -0.76 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            8 |     2793 | 2024-03-03 | SINNERS Academy       | L   | 0.779      | -            | -                | -                | -             |    -8.22 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            7 |     2991 | 2024-02-28 | Preasy Esport         | W   | 0.751      | 0.289        | 0.007 (0.001)    | 0.525 (0.114)    | false (0.000) |    18.14 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            6 |     3033 | 2024-02-27 | EP Genesis            | L   | 0.745      | -            | -                | -                | -             |   -12.44 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            5 |     3072 | 2024-02-26 | SINNERS Academy       | W   | 0.738      | 0.143        | 0.003 (0.000)    | 0.296 (0.031)    | false (0.000) |    15.59 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            4 |     3150 | 2024-02-24 | Sampi NEXT            | W   | 0.725      | 0.289        | 0.000 (0.000)    | 0.039 (0.008)    | false (0.000) |    10.70 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            3 |     4380 | 2024-01-24 | Sashi Academy         | L   | 0.519      | -            | -                | -                | -             |    -5.18 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            2 |     4504 | 2024-01-21 | Preasy Esport         | L   | 0.498      | -            | -                | -                | -             |    -2.65 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            1 |     4742 | 2024-01-17 | EPIC DUDES            | W   | 0.472      | 0.289        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     5.03 | heikkoL, m0nsterr, realzen, SiKO, w4rden |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
