### Roster Details<br />
Team Name: VENI VIDI VICI<br />
Roster: creZe, HenkkyG, naturaL, teCkoO, Tusi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [375](../standings_global.md)<br />
Regional Rank: [225]( ../standings_europe.md)<br />
Final Rank Value:  593.8<br />
<br />
Final Rank Value (593.8) = Starting Rank Value (624.3) + Head To Head Adjustments (-30.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 624.3
- 400 + ( ( 0.110 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 624.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |       54 | 2024-05-29 | Banger Gang           | L   | 1.000      | -            | -                | -                | -         |   -13.75 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|           12 |      188 | 2024-05-27 | Entropiq              | L   | 1.000      | -            | -                | -                | -         |   -11.61 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|           11 |      454 | 2024-05-22 | Team Sampi            | L   | 1.000      | -            | -                | -                | -         |    -3.85 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|           10 |      872 | 2024-05-18 | SINNERS Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.98 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            9 |     1079 | 2024-05-16 | Team Sampi            | L   | 1.000      | -            | -                | -                | -         |    -3.61 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            8 |     1543 | 2024-05-10 | SINNERS Academy       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.227 (0.032)    | 0 (0.000) |    17.05 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            7 |     1584 | 2024-05-09 | Dynamo Eclot Thunders | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.026 (0.004)    | 0 (0.000) |     6.67 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            6 |     4224 | 2024-03-20 | Banger Gang           | L   | 0.731      | -            | -                | -                | -         |   -10.56 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            5 |     4262 | 2024-03-19 | Maknitude             | W   | 0.725      | 0.310        | 0.001 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     8.27 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            4 |     4584 | 2024-03-13 | Young Ninjas          | L   | 0.685      | -            | -                | -                | -         |    -2.78 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            3 |     5411 | 2024-02-29 | BRUTE                 | L   | 0.598      | -            | -                | -                | -         |   -10.53 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            2 |     5468 | 2024-02-28 | SINNERS Academy       | W   | 0.591      | 0.143        | 0.001 (0.000)    | 0.227 (0.019)    | 0 (0.000) |     9.69 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |
|            1 |     5571 | 2024-02-26 | EP Genesis            | L   | 0.577      | -            | -                | -                | -         |   -11.47 | creZe, HenkkyG, naturaL, teCkoO, Tusi        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($262.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
