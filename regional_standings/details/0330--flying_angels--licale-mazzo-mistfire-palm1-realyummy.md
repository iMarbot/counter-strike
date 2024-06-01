### Roster Details<br />
Team Name: Flying Angels<br />
Roster: Licale, Mazzo, MistFire, PALM1, realyummy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [330](../standings_global.md)<br />
Regional Rank: [199]( ../standings_europe.md)<br />
Final Rank Value:  620.4<br />
<br />
Final Rank Value (620.4) = Starting Rank Value (642.8) + Head To Head Adjustments (-22.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.208[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 642.8
- 400 + ( ( 0.119 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 642.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      340 | 2024-05-24 | WompWomp        | L   | 1.000      | -            | -                | -                | -         |   -14.55 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|           15 |     1304 | 2024-05-13 | Podwars         | L   | 1.000      | -            | -                | -                | -         |   -15.82 | DH, Licale, Mazzo, MistFire, realyummy     |
|           14 |     1314 | 2024-05-13 | dopp123         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.21 | DH, Licale, Mazzo, MistFire, realyummy     |
|           13 |     1432 | 2024-05-11 | AURA            | L   | 1.000      | -            | -                | -                | -         |   -12.01 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|           12 |     1479 | 2024-05-11 | Johnny Speeds   | L   | 1.000      | -            | -                | -                | -         |    -3.53 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|           11 |     1859 | 2024-05-03 | regelett        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.129 (0.018)    | 0 (0.000) |     7.16 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|           10 |     1861 | 2024-05-03 | Supermatch      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     7.03 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            9 |     1866 | 2024-05-03 | snyggmix        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     6.34 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            8 |     1952 | 2024-05-01 | Podwars         | L   | 1.000      | -            | -                | -                | -         |   -14.72 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            7 |     1957 | 2024-05-01 | AURA            | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.186 (0.027)    | 0 (0.000) |    19.57 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            6 |     2809 | 2024-04-17 | playanfinest    | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |     7.15 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            5 |     2831 | 2024-04-17 | Rok paus vid 45 | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.025 (0.003)    | 0 (0.000) |     6.70 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            4 |     2832 | 2024-04-17 | ishjarnor       | W   | 0.917      | 0.143        | 0.000 (0.000)    | 0.059 (0.008)    | 0 (0.000) |     6.37 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            3 |     3172 | 2024-04-10 | AURA            | L   | 0.870      | -            | -                | -                | -         |    -9.94 | Licale, Mazzo, MistFire, PALM1, realyummy  |
|            2 |     3541 | 2024-04-03 | Johnny Speeds   | L   | 0.824      | -            | -                | -                | -         |    -2.85 | Cryveng, majkn, MistFire, PALM1, realyummy |
|            1 |     4326 | 2024-03-16 | smuuttikusilkki | L   | 0.704      | -            | -                | -                | -         |   -15.53 | kurtaliz, mazzo, MistFire, realyummy, zern |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($460.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
