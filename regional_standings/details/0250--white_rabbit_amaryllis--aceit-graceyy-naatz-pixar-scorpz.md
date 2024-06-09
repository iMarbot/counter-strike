### Roster Details<br />
Team Name: White Rabbit Amaryllis<br />
Roster: aCeit, Graceyy, nAAtz, Pixar, scorpz<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [250](../standings_global.md)<br />
Regional Rank: [34]( ../standings_asia.md)<br />
Final Rank Value:  689.9<br />
<br />
Final Rank Value (689.9) = Starting Rank Value (660.0) + Head To Head Adjustments (29.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.0
- 400 + ( ( 0.128 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 660.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     1836 | 2024-05-04 | ATK Female             | W   | 1.000      | 0.233        | 0.005 (0.001)    | 0.138 (0.032)    | 0 (0.000) |    17.49 | aCeit, Graceyy, nAAtz, Pixar, scorpz    |
|           12 |     1850 | 2024-05-04 | Aperture Gaming Female | W   | 1.000      | 0.233        | 0.002 (0.000)    | 0.028 (0.006)    | 0 (0.000) |    12.55 | aCeit, Graceyy, nAAtz, Pixar, scorpz    |
|           11 |     3470 | 2024-04-06 | ATK Female             | L   | 0.843      | -            | -                | -                | -         |   -12.00 | aCeit, avo, Graceyy, Pixar, Va1n        |
|           10 |     3476 | 2024-04-06 | INVICTTA               | W   | 0.843      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.64 | aCeit, avo, Graceyy, Pixar, Va1n        |
|            9 |     4430 | 2024-03-16 | Aperture Gaming Female | W   | 0.704      | 0.233        | 0.002 (0.000)    | 0.028 (0.005)    | 0 (0.000) |     9.76 | aCeit, avo, Graceyy, kanakikene, Pixar  |
|            8 |     5336 | 2024-03-02 | ATK Female             | L   | 0.610      | -            | -                | -                | -         |    -8.93 | aCeit, avo, Graceyy, Pixar, Va1n        |
|            7 |     5350 | 2024-03-02 | I T G I R L            | W   | 0.609      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.60 | aCeit, avo, Graceyy, Pixar, Va1n        |
|            6 |     5697 | 2024-02-24 | ATK Female             | L   | 0.564      | -            | -                | -                | -         |    -8.69 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            5 |     5704 | 2024-02-24 | INVICTTA               | W   | 0.563      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.30 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            4 |     6735 | 2024-02-03 | ATK Female             | L   | 0.424      | -            | -                | -                | -         |    -6.78 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            3 |     6764 | 2024-02-03 | INVICTTA               | W   | 0.423      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.03 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            2 |     7174 | 2024-01-27 | ATK Female             | W   | 0.377      | 0.233        | 0.005 (0.000)    | 0.138 (0.012)    | 0 (0.000) |     5.98 | Graceyy, mu, nAAtz, scorpz, Starlight   |
|            1 |     9769 | 2023-12-02 | ATK Female             | L   | 0.003      | -            | -                | -                | -         |    -0.05 | aCeit, Graceyy, Pixar, Queen_za, scorpz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,094.84)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $350.00        | $350.00         |
| 2024-04-06 |      0.843 | $150.00        | $126.47         |
| 2024-03-16 |      0.704 | $350.00        | $246.26         |
| 2024-03-02 |      0.610 | $150.00        | $91.51          |
| 2024-02-24 |      0.564 | $150.00        | $84.54          |
| 2024-02-03 |      0.424 | $150.00        | $63.55          |
| 2024-01-27 |      0.377 | $350.00        | $132.05         |
| 2023-12-02 |      0.003 | $150.00        | $0.46           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
