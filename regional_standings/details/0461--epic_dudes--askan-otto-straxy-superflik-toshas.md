### Roster Details<br />
Team Name: EPIC DUDES<br />
Roster: Askan, otto, Straxy, superflik, toshas<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [461](../standings_global.md)<br />
Regional Rank: [279]( ../standings_europe.md)<br />
Final Rank Value:  382.5<br />
<br />
Final Rank Value (382.5) = Starting Rank Value (402.8) + Head To Head Adjustments (-20.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 402.8
- 400 + ( ( 0.001 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 402.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       53 | 2024-05-29 | Academy Cybersport XP | L   | 1.000      | -            | -                | -                | -         |   -15.63 | Askan, otto, Straxy, superflik, toshas |
|            9 |       88 | 2024-05-29 | ROSOMAHA              | L   | 1.000      | -            | -                | -                | -         |    -8.15 | Askan, otto, Straxy, superflik, toshas |
|            8 |     2415 | 2024-04-24 | lajtbitexe            | L   | 0.964      | -            | -                | -                | -         |    -7.99 | AdamJC, Askan, otto, Straxy, toshas    |
|            7 |     2570 | 2024-04-21 | 777 Esports           | L   | 0.942      | -            | -                | -                | -         |    -3.71 | Askan, otto, Speedy, Straxy, toshas    |
|            6 |     3738 | 2024-03-31 | 777 Esports           | L   | 0.804      | -            | -                | -                | -         |    -2.94 | Askan, Blacki, otto, Speedy, toshas    |
|            5 |     3794 | 2024-03-29 | Preasy Esport         | L   | 0.791      | -            | -                | -                | -         |    -2.68 | Askan, Blacki, otto, Speedy, toshas    |
|            4 |     3838 | 2024-03-28 | Young Gods            | W   | 0.783      | 0.289        | 0.000 (0.000)    | 0.021 (0.005)    | 0 (0.000) |    12.12 | Askan, Blacki, otto, Speedy, toshas    |
|            3 |     4185 | 2024-03-21 | Young Gods            | W   | 0.738      | 0.289        | 0.000 (0.000)    | 0.240 (0.051)    | 0 (0.000) |    16.18 | Askan, Blacki, otto, Speedy, toshas    |
|            2 |     4839 | 2024-03-09 | AURA                  | L   | 0.657      | -            | -                | -                | -         |    -3.53 | Askan, Distu, otto, Straxy, toshas     |
|            1 |     4977 | 2024-03-06 | Sissi State Punks     | L   | 0.638      | -            | -                | -                | -         |    -4.02 | Askan, cello, DreaM-, otto, Straxy     |

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
