### Roster Details<br />
Team Name: Wanted Goons Bandits<br />
Roster: ADK, jaydee, MamaAlien, PippySippy, Tippy<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [306](../standings_global.md)<br />
Regional Rank: [70]( ../standings_americas.md)<br />
Final Rank Value:  604.2<br />
<br />
Final Rank Value (604.2) = Starting Rank Value (663.1) + Head To Head Adjustments (-58.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.1
- 400 + ( ( 0.133 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 663.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      792 | 2024-04-19 | COVEN            | W   | 1.000      | 0.322        | 0.006 (0.002)    | 0.000 (0.000)    | 0 (0.000) |    11.79 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            9 |     1201 | 2024-04-10 | Team Karma       | L   | 1.000      | -            | -                | -                | -         |   -10.68 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            8 |     1381 | 2024-04-06 | Shimmer          | L   | 1.000      | -            | -                | -                | -         |    -9.56 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            7 |     1516 | 2024-04-03 | Shimmer          | L   | 0.987      | -            | -                | -                | -         |   -10.18 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            6 |     1683 | 2024-03-28 | FlyQuest RED     | L   | 0.947      | -            | -                | -                | -         |    -8.77 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            5 |     2293 | 2024-03-13 | Limitless Angels | L   | 0.847      | -            | -                | -                | -         |   -11.22 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            4 |     2596 | 2024-03-06 | Nouns.fe         | L   | 0.800      | -            | -                | -                | -         |   -11.33 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            3 |     4525 | 2024-01-20 | Shimmer          | L   | 0.494      | -            | -                | -                | -         |    -6.30 | jaydee, MamaAlien, PippySippy, Reef, Tippy |
|            2 |     6081 | 2023-12-02 | Nouns.fe         | L   | 0.167      | -            | -                | -                | -         |    -3.10 | jaydee, MamaAlien, PippySippy, Reef, Tippy |
|            1 |     6689 | 2023-11-18 | Totsugeki        | W   | 0.074      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.43 | Cloudy, MamaAlien, PippySippy, Reef, Tippy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,118.47)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-19 |      1.000 | $1,100.00      | $1,100.00       |
| 2023-11-18 |      0.074 | $250.00        | $18.47          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
