### Roster Details<br />
Team Name: The Last Resort<br />
Roster: Bigun, Fizzy, Flicky, Rhys, ve1nzo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [256](../standings_global.md)<br />
Regional Rank: [162]( ../standings_europe.md)<br />
Final Rank Value:  659.0<br />
<br />
Final Rank Value (659.0) = Starting Rank Value (676.7) + Head To Head Adjustments (-17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 676.7
- 400 + ( ( 0.139 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 676.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      230 | 2024-04-30 | Team Invictum          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | false (0.000) |    10.63 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           19 |      460 | 2024-04-25 | Halal5                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.27 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           18 |      560 | 2024-04-23 | FearFerox              | L   | 1.000      | -            | -                | -                | -             |   -17.20 | Bigun, Fizzy, Flicky, Rhys, ve1nzo   |
|           17 |     2254 | 2024-03-14 | Part Timers            | L   | 0.852      | -            | -                | -                | -             |   -19.15 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           16 |     2364 | 2024-03-12 | EXO Clan               | L   | 0.839      | -            | -                | -                | -             |    -6.32 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           15 |     2674 | 2024-03-05 | Linx Legacy Madagaskar | L   | 0.792      | -            | -                | -                | -             |   -19.16 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           14 |     2972 | 2024-02-28 | Viperio                | W   | 0.753      | 0.143        | 0.000 (0.000)    | 0.321 (0.035)    | false (0.000) |    11.33 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           13 |     3013 | 2024-02-27 | K10                    | L   | 0.746      | -            | -                | -                | -             |    -6.85 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           12 |     3169 | 2024-02-24 | Rum Bumpers            | L   | 0.724      | -            | -                | -                | -             |   -11.63 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           11 |     3184 | 2024-02-24 | Reason Gaming          | W   | 0.723      | 0.143        | 0.010 (0.001)    | 0.163 (0.017)    | true (0.723)  |    14.13 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|           10 |     3201 | 2024-02-23 | Raptors Esports Club   | L   | 0.720      | -            | -                | -                | -             |    -6.90 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            9 |     3341 | 2024-02-20 | Verdant                | W   | 0.699      | 0.143        | 0.027 (0.003)    | 0.662 (0.066)    | false (0.000) |    18.53 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            8 |     3436 | 2024-02-18 | Souls-Land             | W   | 0.686      | 0.143        | 0.000 (0.000)    | 0.096 (0.009)    | false (0.000) |     4.21 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            7 |     3441 | 2024-02-18 | Team Invictum          | W   | 0.686      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.54 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            6 |     3570 | 2024-02-15 | Dreams To Legends      | W   | 0.666      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.68 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            5 |     3783 | 2024-02-09 | Souls-Land             | W   | 0.626      | 0.143        | 0.000 (0.000)    | 0.096 (0.009)    | false (0.000) |     4.24 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            4 |     3787 | 2024-02-09 | RKB Fatties            | W   | 0.626      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.59 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            3 |     3810 | 2024-02-08 | Raptors Esports Club   | L   | 0.619      | -            | -                | -                | -             |    -5.13 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            2 |     3986 | 2024-02-03 | K10                    | L   | 0.584      | -            | -                | -                | -             |    -4.40 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo |
|            1 |     6349 | 2023-11-27 | Raptors Esports Club   | L   | 0.132      | -            | -                | -                | -             |    -1.06 | AdamJC, Bigun, Flicky, ve1nzo, Wiiam |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92.06)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
