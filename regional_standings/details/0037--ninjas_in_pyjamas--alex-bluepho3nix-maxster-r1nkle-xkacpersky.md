### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, BluePho3nix, maxster, r1nkle, xKacpersky<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [37](../standings_global.md)<br />
Regional Rank: [28]( ../standings_europe.md)<br />
Final Rank Value:  1160.8<br />
<br />
Final Rank Value (1160.8) = Starting Rank Value (1116.1) + Head To Head Adjustments (44.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.618[<sup>1</sup>](#table2)
- Bounty Collected: 0.429[<sup>2</sup>](#table1)
- Opponent Network: 0.174[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.361<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1116.1
- 400 + ( ( 0.361 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1116.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |       25 | 2024-05-05 | FlyQuest                 | L   | 1.000      | -            | -                | -                | -         |    -6.34 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           18 |       60 | 2024-05-04 | HEROIC                   | W   | 1.000      | 0.889        | 0.243 (0.216)    | 0.537 (0.478)    | 1 (1.000) |    29.01 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           17 |      101 | 2024-05-03 | BOSS                     | W   | 1.000      | 0.889        | 0.051 (0.045)    | 0.293 (0.260)    | 1 (1.000) |     6.04 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           16 |      150 | 2024-05-02 | Pera Esports             | L   | 1.000      | -            | -                | -                | -         |   -25.38 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           15 |      243 | 2024-04-30 | HEROIC                   | L   | 1.000      | -            | -                | -                | -         |    -1.98 | alex, BluePho3nix, maxster, r1nkle, xKacpersky |
|           14 |      931 | 2024-04-17 | 3DMAX                    | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.393 (0.056)    | 0 (0.000) |     7.85 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           13 |     1146 | 2024-04-12 | OG                       | L   | 1.000      | -            | -                | -                | -         |    -7.99 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           12 |     1177 | 2024-04-11 | BetBoom Team             | L   | 1.000      | -            | -                | -                | -         |    -6.35 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           11 |     1286 | 2024-04-09 | Gods Reign               | W   | 1.000      | 0.687        | 0.174 (0.120)    | 0.479 (0.329)    | 0 (0.000) |     5.71 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|           10 |     1481 | 2024-04-04 | Aurora Gaming            | L   | 0.992      | -            | -                | -                | -         |    -3.47 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            9 |     1496 | 2024-04-04 | Metizport                | W   | 0.991      | 0.143        | 0.188 (0.027)    | 1.000 (0.142)    | 0 (0.000) |    15.36 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            8 |     1531 | 2024-04-03 | Aurora Gaming            | L   | 0.985      | -            | -                | -                | -         |    -3.30 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            7 |     1556 | 2024-04-03 | Team Sampi               | L   | 0.983      | -            | -                | -                | -         |   -21.56 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            6 |     1574 | 2024-04-02 | BLESSED (Ukrainian team) | W   | 0.978      | 0.143        | 0.018 (0.003)    | 0.781 (0.109)    | 0 (0.000) |     8.10 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            5 |     1583 | 2024-04-02 | Monte                    | W   | 0.977      | 0.143        | 0.199 (0.028)    | 0.378 (0.053)    | 0 (0.000) |    21.90 | alex, BluePho3nix, maxster, r1nkle, REZ        |
|            4 |     1729 | 2024-03-27 | 500                      | W   | 0.939      | 0.143        | -                | 0.660 (0.089)    | 0 (0.000) |     7.08 | alex, BluePho3nix, maxster, REZ, Silence       |
|            3 |     1738 | 2024-03-27 | Verdant                  | W   | 0.939      | 0.143        | 0.027 (0.004)    | 0.662 (0.089)    | 0 (0.000) |     6.91 | alex, BluePho3nix, maxster, REZ, Silence       |
|            2 |     1752 | 2024-03-27 | Raptors Esports Club     | W   | 0.938      | 0.143        | 0.017 (0.002)    | -                | 0 (0.000) |     5.26 | alex, BluePho3nix, maxster, REZ, Silence       |
|            1 |     1805 | 2024-03-26 | Zero Tenacity            | W   | 0.932      | 0.143        | 0.095 (0.013)    | 1.000 (0.133)    | -         |     7.95 | alex, BluePho3nix, maxster, REZ, Silence       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($38,250.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.24) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-04-14 |      1.000 | $26,250.00     | $26,250.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
