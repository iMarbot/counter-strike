### Roster Details<br />
Team Name: Sashi Academy<br />
Roster: Few, G0op, Mol011, ReXx, Sukker<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [417](../standings_global.md)<br />
Regional Rank: [250]( ../standings_europe.md)<br />
Final Rank Value:  544.3<br />
<br />
Final Rank Value (544.3) = Starting Rank Value (648.5) + Head To Head Adjustments (-104.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 648.5
- 400 + ( ( 0.122 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 648.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      173 | 2024-05-27 | XI Esport            | L   | 1.000      | -            | -                | -                | -         |    -9.87 | Few, G0op, Mol011, ReXx, Sukker |
|           27 |      180 | 2024-05-27 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |    -8.28 | Few, G0op, Mol011, ReXx, Sukker |
|           26 |      667 | 2024-05-20 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -0.74 | Few, G0op, Mol011, ReXx, Sukker |
|           25 |      676 | 2024-05-20 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |    -7.56 | Few, G0op, Mol011, ReXx, Sukker |
|           24 |      699 | 2024-05-20 | IMMAPROBLEM          | L   | 1.000      | -            | -                | -                | -         |   -15.04 | Few, G0op, Mol011, ReXx, Sukker |
|           23 |     1727 | 2024-05-06 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |    -8.56 | Few, G0op, Mol011, ReXx, Sukker |
|           22 |     1750 | 2024-05-06 | XI Esport            | L   | 1.000      | -            | -                | -                | -         |   -13.90 | Few, G0op, Mol011, ReXx, Sukker |
|           21 |     2087 | 2024-04-29 | Sashi Esport         | L   | 0.998      | -            | -                | -                | -         |    -0.90 | Few, G0op, Mol011, ReXx, Sukker |
|           20 |     2090 | 2024-04-29 | Copenhagen Wolves    | L   | 0.997      | -            | -                | -                | -         |   -12.50 | Few, G0op, Mol011, ReXx, Sukker |
|           19 |     2488 | 2024-04-22 | IMMAPROBLEM          | W   | 0.951      | 0.143        | 0.000 (0.000)    | 0.160 (0.022)    | 0 (0.000) |    11.35 | Few, G0op, Mol011, ReXx, Sukker |
|           18 |     2612 | 2024-04-20 | Preasy Esport        | L   | 0.937      | -            | -                | -                | -         |    -9.05 | Few, G0op, Mol011, ReXx, Sukker |
|           17 |     2828 | 2024-04-18 | Lazer Cats           | L   | 0.923      | -            | -                | -                | -         |   -11.44 | Few, G0op, Mol011, ReXx, Sukker |
|           16 |     2969 | 2024-04-16 | WOPA Esport          | L   | 0.910      | -            | -                | -                | -         |    -9.47 | Few, G0op, Mol011, ReXx, Sukker |
|           15 |     3010 | 2024-04-15 | Astralis Talent      | L   | 0.904      | -            | -                | -                | -         |    -7.11 | Few, G0op, Mol011, ReXx, Sukker |
|           14 |     3833 | 2024-03-28 | Natus Vincere Junior | L   | 0.784      | -            | -                | -                | -         |    -9.95 | Few, G0op, Mol011, ReXx, Sukker |
|           13 |     3989 | 2024-03-26 | 777 Esports          | L   | 0.770      | -            | -                | -                | -         |    -7.79 | Few, G0op, Mol011, ReXx, Sukker |
|           12 |     4134 | 2024-03-22 | BRUTE                | W   | 0.743      | 0.289        | 0.000 (0.000)    | 0.157 (0.034)    | 0 (0.000) |     8.77 | Few, G0op, Mol011, ReXx, Sukker |
|           11 |     5180 | 2024-03-04 | BRUTE                | L   | 0.624      | -            | -                | -                | -         |   -12.15 | Few, G0op, Mol011, ReXx, Sukker |
|           10 |     5322 | 2024-03-02 | FAVBET Team          | L   | 0.611      | -            | -                | -                | -         |    -4.32 | Few, G0op, Mol011, ReXx, Sukker |
|            9 |     6830 | 2024-02-02 | EXO Clan             | L   | 0.417      | -            | -                | -                | -         |    -1.82 | Few, G0op, Mol011, ReXx, Sukker |
|            8 |     6939 | 2024-01-31 | Preasy Esport        | W   | 0.403      | 0.289        | 0.008 (0.001)    | 0.705 (0.082)    | 0 (0.000) |     9.54 | Few, G0op, Mol011, ReXx, Sukker |
|            7 |     7050 | 2024-01-29 | AVEZ                 | W   | 0.391      | 0.289        | 0.006 (0.001)    | 0.285 (0.032)    | 0 (0.000) |     9.38 | Few, G0op, Mol011, ReXx, Sukker |
|            6 |     7194 | 2024-01-27 | Sampi NEXT           | W   | 0.377      | 0.289        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     2.42 | Few, G0op, Mol011, ReXx, Sukker |
|            5 |     7347 | 2024-01-24 | BRUTE                | W   | 0.357      | 0.289        | 0.000 (0.000)    | 0.157 (0.016)    | 0 (0.000) |     4.14 | Few, G0op, Mol011, ReXx, Sukker |
|            4 |     7509 | 2024-01-21 | EPIC DUDES           | W   | 0.338      | 0.289        | 0.000 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     3.12 | Few, G0op, Mol011, ReXx, Sukker |
|            3 |     7826 | 2024-01-17 | Preasy Esport        | L   | 0.310      | -            | -                | -                | -         |    -2.05 | Few, G0op, Mol011, ReXx, Sukker |
|            2 |     9044 | 2023-12-14 | cs2Ctonjeu           | L   | 0.085      | -            | -                | -                | -         |    -1.51 | ClinuO, Few, G0op, ReXx, zEden  |
|            1 |     9082 | 2023-12-13 | Memo_team            | W   | 0.078      | 0.284        | 0.001 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.13 | ClinuO, Few, G0op, ReXx, zEden  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($434.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-02 |      0.417 | $1,000.00      | $416.67         |
| 2023-12-17 |      0.105 | $175.00        | $18.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
