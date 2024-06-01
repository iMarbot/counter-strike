### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, isak, maxster, r1nkle, REZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [42](../standings_global.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
Final Rank Value:  1080.5<br />
<br />
Final Rank Value (1080.5) = Starting Rank Value (1080.9) + Head To Head Adjustments (-0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.519[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.173[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.334<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1080.9
- 400 + ( ( 0.334 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1080.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      730 | 2024-05-19 | Sangal Esports       | L   | 1.000      | -            | -                | -                | -         |   -17.73 | alex, isak, maxster, r1nkle, REZ               |
|           22 |      852 | 2024-05-18 | Metizport            | L   | 1.000      | -            | -                | -                | -         |   -16.58 | alex, isak, maxster, r1nkle, REZ               |
|           21 |     1059 | 2024-05-16 | Sangal Esports       | W   | 1.000      | 0.500        | 0.166 (0.083)    | 0.577 (0.288)    | 0 (0.000) |    11.68 | alex, isak, maxster, r1nkle, REZ               |
|           20 |     1778 | 2024-05-05 | FlyQuest             | L   | 1.000      | -            | -                | -                | -         |    -4.29 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           19 |     1819 | 2024-05-04 | HEROIC               | W   | 1.000      | 0.889        | 0.322 (0.286)    | 0.463 (0.412)    | 1 (1.000) |    29.81 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           18 |     1874 | 2024-05-03 | BOSS                 | W   | 1.000      | 0.889        | 0.016 (0.014)    | 0.315 (0.280)    | 1 (1.000) |     7.73 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           17 |     1923 | 2024-05-02 | Pera Esports         | L   | 1.000      | -            | -                | -                | -         |   -23.89 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |     2031 | 2024-04-30 | HEROIC               | L   | 1.000      | -            | -                | -                | -         |    -1.31 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |     2760 | 2024-04-18 | brazylijski luz      | L   | 0.923      | -            | -                | -                | -         |   -24.27 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           14 |     2826 | 2024-04-17 | 3DMAX                | W   | 0.918      | 0.143        | 0.106 (0.014)    | -                | 0 (0.000) |     8.00 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           13 |     3083 | 2024-04-12 | OG                   | L   | 0.883      | -            | -                | -                | -         |    -9.87 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           12 |     3121 | 2024-04-11 | BetBoom Team         | L   | 0.877      | -            | -                | -                | -         |    -5.97 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     3241 | 2024-04-09 | Gods Reign           | W   | 0.864      | 0.687        | 0.086 (0.051)    | 0.461 (0.273)    | 0 (0.000) |     6.55 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     3492 | 2024-04-04 | Aurora Gaming        | L   | 0.830      | -            | -                | -                | -         |    -3.73 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     3508 | 2024-04-04 | Metizport            | W   | 0.829      | 0.143        | 0.088 (0.010)    | 0.698 (0.083)    | 0 (0.000) |    12.57 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     3549 | 2024-04-03 | Aurora Gaming        | L   | 0.824      | -            | -                | -                | -         |    -3.61 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     3575 | 2024-04-03 | Team Sampi           | L   | 0.822      | -            | -                | -                | -         |   -17.63 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     3594 | 2024-04-02 | FAVBET Team          | W   | 0.817      | 0.143        | 0.008 (0.001)    | 0.666 (0.078)    | 0 (0.000) |     6.92 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     3606 | 2024-04-02 | Monte                | W   | 0.816      | 0.143        | 0.181 (0.021)    | -                | 0 (0.000) |    17.08 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     3781 | 2024-03-27 | 500                  | W   | 0.778      | 0.143        | -                | 0.479 (0.053)    | 0 (0.000) |     5.67 | alex, BluePho3nix, maxster, REZ, Silence       |
|            3 |     3793 | 2024-03-27 | Verdant              | W   | 0.778      | 0.143        | 0.014 (0.002)    | 1.000 (0.111)    | 0 (0.000) |     7.29 | alex, BluePho3nix, maxster, REZ, Silence       |
|            2 |     3808 | 2024-03-27 | Raptors Esports Club | W   | 0.777      | 0.143        | -                | 0.406 (0.045)    | -         |     5.04 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     3868 | 2024-03-26 | Zero Tenacity        | W   | 0.771      | 0.143        | 0.147 (0.016)    | 1.000 (0.110)    | -         |    10.07 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($35,526.56)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.12) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-04-14 |      0.896 | $26,250.00     | $23,526.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
