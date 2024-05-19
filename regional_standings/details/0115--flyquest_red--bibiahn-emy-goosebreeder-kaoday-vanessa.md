### Roster Details<br />
Team Name: FlyQuest RED<br />
Roster: BiBiAhn, emy, GooseBreeder, Kaoday, vanessa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [115](../standings_global.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
Final Rank Value:  828.3<br />
<br />
Final Rank Value (828.3) = Starting Rank Value (739.1) + Head To Head Adjustments (89.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 739.1
- 400 + ( ( 0.171 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 739.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      791 | 2024-04-19 | Nouns.fe                   | W   | 1.000      | 0.322        | 0.012 (0.004)    | 0.090 (0.029)    | 0 (0.000) |     8.69 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|           12 |     1061 | 2024-04-14 | Shimmer                    | W   | 1.000      | 0.250        | 0.026 (0.007)    | 0.354 (0.089)    | 0 (0.000) |    14.42 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|           11 |     1086 | 2024-04-13 | Limitless Angels           | W   | 1.000      | 0.250        | 0.011 (0.003)    | 0.133 (0.033)    | 0 (0.000) |    10.93 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|           10 |     1464 | 2024-04-04 | COVEN                      | W   | 0.993      | 0.322        | 0.006 (0.002)    | 0.000 (0.000)    | 0 (0.000) |     5.65 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            9 |     1683 | 2024-03-28 | Wanted Goons Bandits       | W   | 0.947      | 0.322        | 0.007 (0.002)    | 0.038 (0.012)    | 0 (0.000) |     8.77 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            8 |     2008 | 2024-03-20 | Limitless Angels           | W   | 0.894      | 0.322        | 0.011 (0.003)    | 0.133 (0.038)    | 0 (0.000) |    11.09 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            7 |     2138 | 2024-03-17 | LAG Gaming (American team) | L   | 0.871      | -            | -                | -                | -         |    -9.37 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            6 |     2292 | 2024-03-13 | Team Karma                 | W   | 0.847      | 0.322        | 0.011 (0.003)    | 0.131 (0.036)    | 0 (0.000) |    10.67 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            5 |     2595 | 2024-03-06 | Shimmer                    | W   | 0.801      | 0.322        | 0.026 (0.007)    | 0.354 (0.091)    | 0 (0.000) |    11.36 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            4 |     2776 | 2024-03-03 | Shimmer                    | W   | 0.780      | 0.250        | 0.026 (0.005)    | 0.354 (0.069)    | 0 (0.000) |    11.87 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            3 |     2822 | 2024-03-02 | Nouns.fe                   | W   | 0.774      | 0.250        | 0.012 (0.002)    | 0.090 (0.017)    | 0 (0.000) |    10.49 | BiBiAhn, emy, GooseBreeder, Kaoday, vanessa    |
|            2 |     5785 | 2023-12-09 | HSG                        | L   | 0.210      | -            | -                | -                | -         |    -3.83 | BiBiAhn, GooseBreeder, Kaoday, madss, uhKelsie |
|            1 |     5851 | 2023-12-08 | Fluxo Demons               | L   | 0.203      | -            | -                | -                | -         |    -1.59 | BiBiAhn, GooseBreeder, Kaoday, madss, uhKelsie |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,206.74)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $750.00        | $750.00         |
| 2024-03-03 |      0.780 | $750.00        | $584.98         |
| 2023-12-10 |      0.218 | $4,000.00      | $871.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
