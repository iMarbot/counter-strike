### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, es3tag, headtr1ck, k0nfig, REZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [175](../standings_global.md)<br />
Regional Rank: [122]( ../standings_europe.md)<br />
Final Rank Value:  760.1<br />
<br />
Final Rank Value (760.1) = Starting Rank Value (749.6) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.338[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 749.6
- 400 + ( ( 0.172 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 749.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     6237 | 2024-02-15 | SAW                 | L   | 0.503      | -            | -                | -                | -         |    -0.58 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|           11 |     6285 | 2024-02-14 | AMKAL ESPORTS       | L   | 0.497      | -            | -                | -                | -         |    -1.28 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|           10 |     6293 | 2024-02-14 | Eternal Fire        | L   | 0.496      | -            | -                | -                | -         |    -0.04 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            9 |     7040 | 2024-01-29 | Dynamo Eclot        | L   | 0.392      | -            | -                | -                | -         |    -1.74 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            8 |     7273 | 2024-01-26 | G2 Esports          | L   | 0.370      | -            | -                | -                | -         |    -0.04 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            7 |     7425 | 2024-01-23 | Complexity Gaming   | W   | 0.350      | 0.581        | 0.260 (0.053)    | 0.219 (0.044)    | 1 (0.350) |    10.90 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            6 |     7493 | 2024-01-22 | G2 Esports          | L   | 0.342      | -            | -                | -                | -         |    -0.03 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            5 |     7762 | 2024-01-17 | 500                 | L   | 0.312      | -            | -                | -                | -         |    -4.53 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            4 |     7767 | 2024-01-17 | Team Spirit Academy | W   | 0.312      | 0.143        | 0.004 (0.000)    | 0.229 (0.010)    | 0 (0.000) |     4.80 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            3 |     7799 | 2024-01-17 | CYBERSHOKE Esports  | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.147 (0.007)    | 0 (0.000) |     2.94 | alex, es3tag, headtr1ck, k0nfig, REZ  |
|            2 |     9659 | 2023-12-03 | Alliance            | W   | 0.010      | 0.143        | 0.004 (0.000)    | 0.529 (0.001)    | 1 (0.010) |     0.20 | es3tag, k0nfig, maxster, REZ, Silence |
|            1 |     9746 | 2023-12-02 | GODSENT             | L   | 0.004      | -            | -                | -                | -         |    -0.08 | es3tag, k0nfig, maxster, REZ, Silence |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,337.86)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-28 |      0.384 | $8,500.00      | $3,264.24       |
| 2023-12-03 |      0.011 | $6,710.26      | $73.63          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
