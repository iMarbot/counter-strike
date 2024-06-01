### Roster Details<br />
Team Name: GenOne<br />
Roster: AMANEK, Brooxsy, Graviti, Kursy, Razzmo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [368](../standings_global.md)<br />
Regional Rank: [220]( ../standings_europe.md)<br />
Final Rank Value:  592.9<br />
<br />
Final Rank Value (592.9) = Starting Rank Value (539.5) + Head To Head Adjustments (53.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.069<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 539.5
- 400 + ( ( 0.069 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 539.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     5010 | 2024-03-04 | 3DMAX                | L   | 0.625      | -            | -                | -                | -         |    -2.26 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           12 |     5144 | 2024-03-02 | BetBoom Team         | L   | 0.611      | -            | -                | -                | -         |    -0.24 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           11 |     5238 | 2024-03-01 | HOTU                 | W   | 0.603      | 0.371        | 0.004 (0.001)    | 0.524 (0.117)    | 0 (0.000) |    15.39 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|           10 |     5263 | 2024-02-29 | ex-FLuffy Gangsters  | W   | 0.598      | 0.371        | 0.000 (0.000)    | 0.093 (0.021)    | 0 (0.000) |     9.17 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            9 |     5542 | 2024-02-24 | Eternal Fire Academy | W   | 0.563      | 0.371        | 0.003 (0.001)    | 0.078 (0.016)    | 0 (0.000) |    11.13 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            8 |     5658 | 2024-02-22 | Insilio              | L   | 0.550      | -            | -                | -                | -         |    -1.79 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            7 |     5707 | 2024-02-21 | Team Secret          | L   | 0.544      | -            | -                | -                | -         |    -6.13 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            6 |     5769 | 2024-02-20 | Permitta Esports     | L   | 0.537      | -            | -                | -                | -         |    -1.61 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            5 |     5945 | 2024-02-17 | RUBY                 | L   | 0.517      | -            | -                | -                | -         |    -1.84 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            4 |     5989 | 2024-02-16 | The Chosen Few       | W   | 0.510      | 0.371        | 0.002 (0.000)    | 0.262 (0.050)    | 0 (0.000) |    12.49 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            3 |     6157 | 2024-02-13 | Aurora Young Blud    | W   | 0.490      | 0.371        | 0.008 (0.002)    | 0.506 (0.092)    | 0 (0.000) |    12.33 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            2 |     6329 | 2024-02-08 | VP.Prodigy           | W   | 0.457      | 0.371        | 0.008 (0.001)    | 0.752 (0.128)    | 0 (0.000) |    12.31 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            1 |     6418 | 2024-02-05 | lajtbitexe           | L   | 0.437      | -            | -                | -                | -         |    -5.61 | AMANEK, bibu, Graviti, Kursy, Razzmo    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
