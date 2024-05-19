### Roster Details<br />
Team Name: 777 Esports<br />
Roster: Affava, Hagmeister, MadeInRed, Viktha, wenba<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [173](../standings_global.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
Final Rank Value:  751.4<br />
<br />
Final Rank Value (751.4) = Starting Rank Value (751.5) + Head To Head Adjustments (-0.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 751.5
- 400 + ( ( 0.177 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 751.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      306 | 2024-04-28 | Apeks Legends                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     3.40 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           32 |      349 | 2024-04-27 | Sashi Esport                    | L   | 1.000      | -            | -                | -                | -             |    -1.76 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           31 |      367 | 2024-04-27 | Preasy Esport                   | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.525 (0.075)    | false (0.000) |    14.91 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           30 |      405 | 2024-04-26 | Sashi Esport                    | L   | 1.000      | -            | -                | -                | -             |    -1.69 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           29 |      411 | 2024-04-26 | Esport Harte                    | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     9.11 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           28 |      418 | 2024-04-26 | JANO Esports                    | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.407 (0.058)    | false (0.000) |    16.91 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           27 |      426 | 2024-04-26 | Preasy Esport                   | L   | 1.000      | -            | -                | -                | -             |   -17.09 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           26 |      540 | 2024-04-24 | L&G                             | L   | 1.000      | -            | -                | -                | -             |   -16.19 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           25 |      607 | 2024-04-22 | Wizard esports (Norwegian team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     4.21 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           24 |      634 | 2024-04-21 | En av de lette                  | L   | 1.000      | -            | -                | -                | -             |   -15.11 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           23 |      642 | 2024-04-21 | Akta mannen                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     3.80 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           22 |      659 | 2024-04-21 | EPIC DUDES                      | W   | 1.000      | -            | -                | -                | false (0.000) |     4.45 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           21 |     1044 | 2024-04-15 | Metizport X                     | L   | 1.000      | -            | -                | -                | -             |   -23.27 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           20 |     1103 | 2024-04-13 | En av de lette                  | L   | 1.000      | -            | -                | -                | -             |   -17.43 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           19 |     1330 | 2024-04-08 | Static                          | W   | 1.000      | 0.143        | -                | 0.226 (0.032)    | false (0.000) |     4.92 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           18 |     1442 | 2024-04-05 | Natus Vincere Youth             | L   | 0.998      | -            | -                | -                | -             |   -17.75 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           17 |     1485 | 2024-04-04 | SINNERS Academy                 | W   | 0.992      | 0.289        | 0.003 (0.001)    | 0.296 (0.085)    | false (0.000) |    10.54 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           16 |     1576 | 2024-04-02 | Preasy Esport                   | W   | 0.978      | 0.289        | 0.007 (0.002)    | 0.525 (0.149)    | false (0.000) |    13.05 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           15 |     1616 | 2024-03-31 | EPIC DUDES                      | W   | 0.965      | -            | -                | -                | -             |     3.87 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           14 |     1631 | 2024-03-30 | Apeks Rebels                    | L   | 0.959      | -            | -                | -                | -             |   -18.52 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           13 |     1824 | 2024-03-26 | Sashi Academy                   | W   | 0.931      | 0.289        | 0.004 (0.001)    | 0.143 (0.038)    | -             |     9.81 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           12 |     1935 | 2024-03-22 | Natus Vincere Youth             | W   | 0.905      | 0.289        | 0.013 (0.003)    | 0.306 (0.080)    | -             |    11.21 | Affava, artstyle, Hagmeister, MadeInRed, wenba |
|           11 |     2087 | 2024-03-18 | Nordix Esport                   | W   | 0.879      | -            | -                | -                | -             |     4.18 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           10 |     2126 | 2024-03-17 | INFURITY Gaming                 | W   | 0.872      | 0.143        | -                | 0.274 (0.034)    | -             |     3.96 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            9 |     2317 | 2024-03-13 | Static                          | W   | 0.845      | 0.143        | -                | 0.226 (0.027)    | -             |     5.16 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            8 |     2415 | 2024-03-11 | Vanir                           | W   | 0.832      | -            | -                | -                | -             |     2.76 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            7 |     2451 | 2024-03-10 | Foxed Gaming                    | W   | 0.825      | -            | -                | -                | -             |     3.27 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            6 |     2493 | 2024-03-09 | Cashout Cavaliers               | W   | 0.818      | -            | -                | -                | -             |     3.04 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            5 |     2614 | 2024-03-06 | INFURITY Gaming                 | W   | 0.799      | 0.143        | -                | 0.274 (0.031)    | -             |     3.52 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            4 |     3716 | 2024-02-12 | INFURITY Gaming                 | W   | 0.645      | -            | -                | -                | -             |     2.78 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            3 |     3893 | 2024-02-05 | Bitfix Gaming                   | W   | 0.598      | -            | -                | -                | -             |     2.44 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            2 |     4032 | 2024-02-02 | Metizport                       | L   | 0.578      | -            | -                | -                | -             |    -3.44 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|            1 |     4814 | 2024-01-16 | GUN5 Esports                    | L   | 0.465      | -            | -                | -                | -             |    -9.11 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,045.85)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $2,675.66      | $2,675.66       |
| 2024-04-13 |      1.000 | $1,371.91      | $1,371.91       |
| 2024-04-05 |      0.998 | $1,000.00      | $998.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
