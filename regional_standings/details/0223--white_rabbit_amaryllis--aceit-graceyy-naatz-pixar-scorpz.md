### Roster Details<br />
Team Name: White Rabbit Amaryllis<br />
Roster: aCeit, Graceyy, nAAtz, Pixar, scorpz<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [223](../standings_global.md)<br />
Regional Rank: [38]( ../standings_asia.md)<br />
Final Rank Value:  692.8<br />
<br />
Final Rank Value (692.8) = Starting Rank Value (678.5) + Head To Head Adjustments (14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.5
- 400 + ( ( 0.140 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 678.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |       54 | 2024-05-04 | ATK Female             | W   | 1.000      | 0.233        | 0.011 (0.003)    | 0.201 (0.047)    | false (0.000) |    18.64 | aCeit, Graceyy, nAAtz, Pixar, scorpz    |
|           13 |       67 | 2024-05-04 | Aperture Gaming Female | W   | 1.000      | 0.233        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     8.85 | aCeit, Graceyy, nAAtz, Pixar, scorpz    |
|           12 |     1397 | 2024-04-06 | ATK Female             | L   | 1.000      | -            | -                | -                | -             |   -12.98 | aCeit, avo, Graceyy, Pixar, Va1n        |
|           11 |     1402 | 2024-04-06 | INVICTTA               | W   | 1.000      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     5.30 | aCeit, avo, Graceyy, Pixar, Va1n        |
|           10 |     2175 | 2024-03-16 | Aperture Gaming Female | W   | 0.865      | 0.233        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     8.20 | aCeit, avo, Graceyy, kanakikene, Pixar  |
|            9 |     2881 | 2024-03-02 | ATK Female             | L   | 0.771      | -            | -                | -                | -             |   -10.57 | aCeit, avo, Graceyy, Pixar, Va1n        |
|            8 |     2891 | 2024-03-02 | I T G I R L            | W   | 0.770      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.30 | aCeit, avo, Graceyy, Pixar, Va1n        |
|            7 |     3156 | 2024-02-24 | ATK Female             | L   | 0.725      | -            | -                | -                | -             |   -10.60 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            6 |     3161 | 2024-02-24 | INVICTTA               | W   | 0.724      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.87 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            5 |     3971 | 2024-02-03 | ATK Female             | L   | 0.585      | -            | -                | -                | -             |    -9.07 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            4 |     3992 | 2024-02-03 | INVICTTA               | W   | 0.584      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.09 | aCeit, EmmaD1lemma, mu, Pixar, scorpz   |
|            3 |     4265 | 2024-01-27 | ATK Female             | W   | 0.538      | 0.233        | 0.011 (0.001)    | 0.201 (0.025)    | false (0.000) |     8.79 | Graceyy, mu, nAAtz, scorpz, Starlight   |
|            2 |     6119 | 2023-12-02 | ATK Female             | L   | 0.164      | -            | -                | -                | -             |    -2.47 | aCeit, Graceyy, Pixar, Queen_za, scorpz |
|            1 |     6717 | 2023-11-18 | ATK Female             | L   | 0.071      | -            | -                | -                | -             |    -1.08 | Graceyy, mu, Pixar, Queen_za, scorpz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,338.46)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $350.00        | $350.00         |
| 2024-04-06 |      1.000 | $150.00        | $150.00         |
| 2024-03-16 |      0.865 | $350.00        | $302.63         |
| 2024-03-02 |      0.771 | $150.00        | $115.67         |
| 2024-02-24 |      0.725 | $150.00        | $108.70         |
| 2024-02-03 |      0.585 | $150.00        | $87.71          |
| 2024-01-27 |      0.538 | $350.00        | $188.42         |
| 2023-12-02 |      0.164 | $150.00        | $24.62          |
| 2023-11-18 |      0.071 | $150.00        | $10.71          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
