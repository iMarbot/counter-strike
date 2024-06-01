### Roster Details<br />
Team Name: Final Form<br />
Roster: cypress, mcniff, raw1, slump, Think<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [270](../standings_global.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
Final Rank Value:  662.2<br />
<br />
Final Rank Value (662.2) = Starting Rank Value (675.3) + Head To Head Adjustments (-13.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.320[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.3
- 400 + ( ( 0.135 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 675.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |        6 | 2024-05-29 | VitaPLUR          | L   | 1.000      | -            | -                | -                | -         |   -22.05 | cypress, mcniff, raw1, slump, Think        |
|           10 |     4050 | 2024-03-21 | Strife Esports    | L   | 0.740      | -            | -                | -                | -         |   -10.32 | Gabie, J0LZ, Melio, TENSKEE, YuZ           |
|            9 |     4457 | 2024-03-13 | Revenge Nation    | L   | 0.686      | -            | -                | -                | -         |    -9.95 | cypress, mcniff, raw1, slump, Think        |
|            8 |     4580 | 2024-03-11 | Xiaoma Gaming     | W   | 0.673      | 0.371        | 0.005 (0.001)    | 0.075 (0.019)    | 0 (0.000) |    12.13 | cypress, mcniff, raw1, slump, Think        |
|            7 |     4687 | 2024-03-09 | Snakes Den Gaming | W   | 0.660      | 0.371        | 0.002 (0.000)    | 0.054 (0.013)    | 0 (0.000) |     8.85 | CoolComs, FxRE, ItsYaBoiGavin, JoSoo, NoVa |
|            6 |     4778 | 2024-03-07 | The Nomads        | W   | 0.647      | 0.371        | 0.002 (0.000)    | 0.056 (0.013)    | 0 (0.000) |     6.29 | cypress, mcniff, raw1, slump, Think        |
|            5 |     4925 | 2024-03-05 | KingsOfTheNorth   | W   | 0.633      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.51 | Cled, Crisp, flixera, thE_pLuG, Waveum     |
|            4 |     8943 | 2023-12-10 | Akimbo Esports    | L   | 0.060      | -            | -                | -                | -         |    -1.40 | flixxy, Florence, Keiti, niise, Noxio      |
|            3 |     8947 | 2023-12-10 | Strife Esports    | W   | 0.060      | 0.143        | 0.011 (0.000)    | 0.204 (0.002)    | 0 (0.000) |     1.00 | cypress, mcniff, raw1, Slash, slump        |
|            2 |     9194 | 2023-12-06 | Zero MarksMen     | L   | 0.033      | -            | -                | -                | -         |    -0.78 | Bear, clipzera, drayza, jrose, moose       |
|            1 |     9252 | 2023-12-05 | Villainous        | L   | 0.027      | -            | -                | -                | -         |    -0.43 | cypress, mcniff, raw1, Slash, slump        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,258.33)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
