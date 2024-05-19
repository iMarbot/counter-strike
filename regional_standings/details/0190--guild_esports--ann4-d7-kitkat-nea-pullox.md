### Roster Details<br />
Team Name: Guild Esports<br />
Roster: Ann4, D7, KiTKaT, Nea, pullox<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [190](../standings_global.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
Final Rank Value:  736.4<br />
<br />
Final Rank Value (736.4) = Starting Rank Value (713.3) + Head To Head Adjustments (23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.3
- 400 + ( ( 0.158 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 713.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      632 | 2024-04-21 | Fearless Cheetahs  | W   | 1.000      | 0.331        | 0.014 (0.004)    | 0.199 (0.066)    | 0 (0.000) |    15.41 | Ann4, D7, KiTKaT, Nea, pullox |
|           12 |      722 | 2024-04-20 | Let Her Cook       | L   | 1.000      | -            | -                | -                | -         |   -20.79 | Ann4, D7, KiTKaT, Nea, pullox |
|           11 |      815 | 2024-04-19 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -7.96 | Ann4, D7, KiTKaT, Nea, pullox |
|           10 |     1221 | 2024-04-10 | NIP Impact         | W   | 1.000      | 0.331        | 0.011 (0.004)    | 0.344 (0.114)    | 0 (0.000) |    16.89 | Ann4, D7, KiTKaT, Nea, pullox |
|            9 |     1412 | 2024-04-06 | NIP Impact         | L   | 1.000      | -            | -                | -                | -         |   -15.65 | Ann4, D7, KiTKaT, Nea, pullox |
|            8 |     1421 | 2024-04-06 | Permitta W         | W   | 1.000      | 0.262        | 0.000 (0.000)    | 0.070 (0.018)    | 0 (0.000) |     6.57 | Ann4, D7, KiTKaT, Nea, pullox |
|            7 |     1692 | 2024-03-28 | BIG EQUIPA         | W   | 0.945      | 0.331        | 0.004 (0.001)    | 0.300 (0.094)    | 0 (0.000) |    14.99 | Ann4, D7, KiTKaT, Nea, pullox |
|            6 |     1977 | 2024-03-21 | Astralis Women     | W   | 0.899      | 0.331        | 0.007 (0.002)    | 0.101 (0.030)    | 0 (0.000) |    10.49 | Ann4, D7, KiTKaT, Nea, pullox |
|            5 |     2311 | 2024-03-13 | ENCE Athena        | L   | 0.845      | -            | -                | -                | -         |   -13.64 | Ann4, D7, KiTKaT, Nea, pullox |
|            4 |     3168 | 2024-02-24 | BIG EQUIPA         | L   | 0.724      | -            | -                | -                | -         |   -12.31 | Ann4, D7, KiTKaT, Nea, pullox |
|            3 |     3180 | 2024-02-24 | Fearless Cheetahs  | W   | 0.723      | 0.143        | 0.014 (0.001)    | 0.199 (0.021)    | 0 (0.000) |    10.36 | Ann4, D7, KiTKaT, Nea, pullox |
|            2 |     3615 | 2024-02-14 | Team Spirit Female | W   | 0.659      | 0.143        | 0.011 (0.001)    | 0.205 (0.019)    | 0 (0.000) |     9.70 | Ann4, D7, KiTKaT, Nea, pullox |
|            1 |     3625 | 2024-02-14 | Astralis Women     | W   | 0.658      | 0.143        | 0.007 (0.001)    | 0.101 (0.009)    | 0 (0.000) |     9.02 | Ann4, D7, KiTKaT, Nea, pullox |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,600.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
