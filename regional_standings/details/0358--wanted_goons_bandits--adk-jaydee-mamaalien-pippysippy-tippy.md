### Roster Details<br />
Team Name: Wanted Goons Bandits<br />
Roster: ADK, jaydee, MamaAlien, PippySippy, Tippy<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [358](../standings_global.md)<br />
Regional Rank: [90]( ../standings_americas.md)<br />
Final Rank Value:  598.3<br />
<br />
Final Rank Value (598.3) = Starting Rank Value (650.5) + Head To Head Adjustments (-52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.5
- 400 + ( ( 0.123 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 650.5


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
|           12 |     2666 | 2024-04-19 | COVEN            | W   | 0.932      | 0.322        | 0.003 (0.001)    | 0.014 (0.004)    | 0 (0.000) |    11.03 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|           11 |     3147 | 2024-04-10 | Team Karma       | L   | 0.872      | -            | -                | -                | -         |    -9.64 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|           10 |     3361 | 2024-04-06 | TSM Shimmer      | L   | 0.846      | -            | -                | -                | -         |    -8.27 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            9 |     3528 | 2024-04-03 | TSM Shimmer      | L   | 0.825      | -            | -                | -                | -         |    -8.62 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            8 |     3725 | 2024-03-28 | FlyQuest RED     | L   | 0.786      | -            | -                | -                | -         |    -6.08 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            7 |     4117 | 2024-03-20 | cleanup crew     | L   | 0.733      | -            | -                | -                | -         |   -10.66 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            6 |     4459 | 2024-03-13 | Limitless Angels | L   | 0.686      | -            | -                | -                | -         |    -9.68 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            5 |     4839 | 2024-03-06 | Nouns.fe         | L   | 0.639      | -            | -                | -                | -         |    -9.71 | ADK, jaydee, MamaAlien, PippySippy, Tippy  |
|            4 |     6138 | 2024-02-13 | cleanup crew     | W   | 0.492      | 0.143        | 0.004 (0.000)    | 0.054 (0.004)    | 0 (0.000) |     7.95 | jaydee, MamaAlien, PippySippy, Reef, Tippy |
|            3 |     6895 | 2024-01-27 | FlyQuest RED     | L   | 0.379      | -            | -                | -                | -         |    -4.21 | jaydee, MamaAlien, PippySippy, Reef, Tippy |
|            2 |     7302 | 2024-01-20 | TSM Shimmer      | L   | 0.333      | -            | -                | -                | -         |    -4.25 | jaydee, MamaAlien, PippySippy, Reef, Tippy |
|            1 |     9428 | 2023-12-02 | Nouns.fe         | L   | 0.006      | -            | -                | -                | -         |    -0.09 | jaydee, MamaAlien, PippySippy, Reef, Tippy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,025.44)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
