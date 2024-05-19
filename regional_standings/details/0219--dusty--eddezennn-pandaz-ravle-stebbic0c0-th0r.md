### Roster Details<br />
Team Name: DUSTY<br />
Roster: EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [219](../standings_global.md)<br />
Regional Rank: [144]( ../standings_europe.md)<br />
Final Rank Value:  696.7<br />
<br />
Final Rank Value (696.7) = Starting Rank Value (782.2) + Head To Head Adjustments (-85.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.203[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 782.2
- 400 + ( ( 0.193 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 782.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      635 | 2024-04-21 | KUUSAMO.gg              | L   | 1.000      | -            | -                | -                | -             |   -12.85 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           29 |      804 | 2024-04-19 | Heimo Esports           | L   | 1.000      | -            | -                | -                | -             |   -13.78 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           28 |      809 | 2024-04-19 | RoundsGG                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.170 (0.024)    | false (0.000) |    14.35 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           27 |      938 | 2024-04-17 | SINNERS Academy         | L   | 1.000      | -            | -                | -                | -             |   -17.52 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           26 |     1809 | 2024-03-26 | Team Sampi              | L   | 0.932      | -            | -                | -                | -             |    -5.25 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           25 |     1888 | 2024-03-23 | SAGA Esports            | W   | 0.912      | 0.143        | 0.006 (0.001)    | 0.133 (0.017)    | true (0.912)  |     9.87 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           24 |     1927 | 2024-03-22 | AURORA (Icelandic team) | W   | 0.906      | 0.143        | 0.000 (0.000)    | 0.037 (0.005)    | true (0.906)  |     4.41 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           23 |     2125 | 2024-03-17 | Breiðablik              | W   | 0.872      | 0.143        | 0.000 (0.000)    | 0.115 (0.014)    | false (0.000) |     7.30 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           22 |     2687 | 2024-03-05 | TopTab Club             | L   | 0.792      | -            | -                | -                | -             |   -18.77 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           21 |     2856 | 2024-03-02 | SINNERS Esports         | L   | 0.772      | -            | -                | -                | -             |    -4.74 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           20 |     3479 | 2024-02-17 | Þór                     | L   | 0.679      | -            | -                | -                | -             |   -15.91 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           19 |     3854 | 2024-02-06 | Young Prodigies         | W   | 0.606      | 0.143        | 0.000 (0.000)    | 0.065 (0.006)    | false (0.000) |     2.47 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           18 |     3936 | 2024-02-04 | Metizport               | L   | 0.590      | -            | -                | -                | -             |    -3.20 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           17 |     4060 | 2024-02-01 | Ármann                  | L   | 0.573      | -            | -                | -                | -             |   -14.55 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           16 |     4170 | 2024-01-29 | GODSENT                 | L   | 0.553      | -            | -                | -                | -             |    -8.35 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           15 |     4248 | 2024-01-27 | Raptors Esports Club    | L   | 0.540      | -            | -                | -                | -             |   -13.43 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           14 |     4249 | 2024-01-27 | PUGSTAR5 (British team) | W   | 0.539      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     1.76 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           13 |     4549 | 2024-01-20 | FH                      | W   | 0.492      | 0.143        | 0.000 (0.000)    | 0.040 (0.003)    | false (0.000) |     1.59 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           12 |     4641 | 2024-01-18 | ÍA Akranes              | W   | 0.479      | -            | -                | -                | false (0.000) |     1.54 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           11 |     4989 | 2024-01-11 | SAGA Esports            | W   | 0.432      | 0.143        | 0.006 (0.000)    | 0.133 (0.008)    | false (0.000) |     3.81 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|           10 |     5446 | 2023-12-16 | 1win                    | L   | 0.259      | -            | -                | -                | -             |    -4.63 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            9 |     5609 | 2023-12-14 | CYBER.MD                | W   | 0.246      | 0.284        | 0.000 (0.000)    | 0.008 (0.001)    | false (0.000) |     1.40 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            8 |     5637 | 2023-12-13 | Enosis (Slovak team)    | W   | 0.239      | -            | -                | -                | -             |     0.80 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            7 |     5865 | 2023-12-07 | ÍBV Esports             | W   | 0.200      | -            | -                | -                | -             |     0.66 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            6 |     6195 | 2023-11-30 | Breiðablik              | L   | 0.152      | -            | -                | -                | -             |    -3.98 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            5 |     6660 | 2023-11-19 | SAGA Esports            | W   | 0.079      | 0.143        | 0.006 (0.000)    | 0.133 (0.002)    | -             |     0.68 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            4 |     6663 | 2023-11-19 | Þór                     | W   | 0.079      | 0.143        | -                | 0.169 (0.002)    | -             |     0.44 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            3 |     6912 | 2023-11-14 | Young Prodigies         | W   | 0.046      | -            | -                | -                | -             |     0.15 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            2 |     6916 | 2023-11-14 | ÍA Akranes              | W   | 0.046      | -            | -                | -                | -             |     0.15 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |
|            1 |     7121 | 2023-11-09 | Þór                     | W   | 0.013      | -            | -                | -                | -             |     0.07 | EddezeNNN, PANDAZ, RavlE, StebbiC0C0, TH0R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,408.36)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.912 | $2,540.09      | $2,317.71       |
| 2023-12-16 |      0.259 | $350.00        | $90.64          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
