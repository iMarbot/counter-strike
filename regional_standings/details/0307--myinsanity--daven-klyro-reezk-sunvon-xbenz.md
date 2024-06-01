### Roster Details<br />
Team Name: mYinsanity<br />
Roster: DAVEN, klyrO, reezk, Sunvon, Xbenz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [307](../standings_global.md)<br />
Regional Rank: [188]( ../standings_europe.md)<br />
Final Rank Value:  636.8<br />
<br />
Final Rank Value (636.8) = Starting Rank Value (637.0) + Head To Head Adjustments (-0.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.194[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.0
- 400 + ( ( 0.116 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 637.0


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
|           10 |      696 | 2024-05-20 | ARROW               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.344 (0.049)    | 0 (0.000) |    20.31 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            9 |     1312 | 2024-05-13 | Sissi State Punks   | L   | 1.000      | -            | -                | -                | -         |   -14.25 | DAVEN, klyrO, Rand, reezk, Xbenz      |
|            8 |     1983 | 2024-05-01 | ALTERNATE aTTaX Evo | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.239 (0.034)    | 0 (0.000) |    18.25 | DAVEN, klyrO, Rand, reezk, Xbenz      |
|            7 |     2302 | 2024-04-25 | Team Solid          | L   | 0.971      | -            | -                | -                | -         |   -16.75 | DAVEN, klyrO, NoRulezZ, reezk, Sunvon |
|            6 |     2441 | 2024-04-22 | TeamOrangeGaming    | L   | 0.951      | -            | -                | -                | -         |   -10.28 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            5 |     2833 | 2024-04-17 | Wave Esports        | L   | 0.917      | -            | -                | -                | -         |   -17.20 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            4 |     3179 | 2024-04-10 | SNOGARD Dragons     | L   | 0.870      | -            | -                | -                | -         |   -10.62 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            3 |     3370 | 2024-04-06 | Team Rayvenclaw     | W   | 0.844      | 0.143        | 0.000 (0.000)    | 0.048 (0.006)    | 0 (0.000) |     7.97 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            2 |     3436 | 2024-04-05 | Wave Esports        | W   | 0.838      | 0.143        | 0.001 (0.000)    | 0.143 (0.017)    | 0 (0.000) |    10.82 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |
|            1 |     3620 | 2024-04-01 | EVOPLAY             | W   | 0.811      | 0.143        | 0.000 (0.000)    | 0.015 (0.002)    | 0 (0.000) |    11.60 | DAVEN, klyrO, reezk, Sunvon, Xbenz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($436.69)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $162.85        | $162.85         |
| 2024-04-28 |      0.990 | $276.53        | $273.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
