### Roster Details<br />
Team Name: Part Timers<br />
Roster: eMy, ifan, Yoshwa, Ziimzey, Zulu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [336](../standings_global.md)<br />
Regional Rank: [206]( ../standings_europe.md)<br />
Final Rank Value:  527.6<br />
<br />
Final Rank Value (527.6) = Starting Rank Value (500.3) + Head To Head Adjustments (27.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 500.3
- 400 + ( ( 0.051 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 500.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       99 | 2024-05-03 | Verdant                      | L   | 1.000      | -            | -                | -                | -             |    -3.81 | eMy, ifan, Yoshwa, Ziimzey, Zulu     |
|            9 |      177 | 2024-05-01 | ROYALS                       | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.061 (0.009)    | false (0.000) |    20.21 | eMy, ifan, Yoshwa, Ziimzey, Zulu     |
|            8 |      231 | 2024-04-30 | Raptors Esports Club         | L   | 1.000      | -            | -                | -                | -             |    -3.54 | eMy, ifan, Yoshwa, Ziimzey, Zulu     |
|            7 |     2047 | 2024-03-19 | K10                          | L   | 0.886      | -            | -                | -                | -             |    -4.18 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |
|            6 |     2254 | 2024-03-14 | The Last Resort              | W   | 0.852      | 0.143        | 0.001 (0.000)    | 0.240 (0.029)    | false (0.000) |    19.15 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |
|            5 |     2303 | 2024-03-13 | TEAM MAX (European mix-team) | L   | 0.846      | -            | -                | -                | -             |   -12.32 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |
|            4 |     2363 | 2024-03-12 | Verdant                      | L   | 0.839      | -            | -                | -                | -             |    -2.74 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |
|            3 |     2398 | 2024-03-11 | UHKA eSports                 | W   | 0.832      | 0.333        | 0.000 (0.000)    | 0.029 (0.008)    | false (0.000) |     9.42 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |
|            2 |     2483 | 2024-03-09 | HAVENs                       | W   | 0.819      | 0.333        | 0.000 (0.000)    | 0.031 (0.008)    | false (0.000) |    11.82 | keni, proxi, v1trage, WIPSKY, yaankz |
|            1 |     2560 | 2024-03-07 | HyperSpirit                  | L   | 0.806      | -            | -                | -                | -             |    -6.67 | eMy, ifan, Rhys, Yoshwa, Ziimzey     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
