### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: Chawzyyy, draken, Lekr0, Ro1f, spooke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [59](../standings_global.md)<br />
Regional Rank: [44]( ../standings_europe.md)<br />
Final Rank Value:  964.7<br />
<br />
Final Rank Value (964.7) = Starting Rank Value (857.5) + Head To Head Adjustments (107.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.424[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.169[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 857.5
- 400 + ( ( 0.231 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 857.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |       19 | 2024-05-05 | NOM Esports                 | W   | 1.000      | 0.333        | -                | 0.374 (0.125)    | false (0.000) |     6.75 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           32 |       88 | 2024-05-04 | Copenhagen Wolves           | W   | 1.000      | 0.333        | -                | 0.417 (0.139)    | false (0.000) |     4.84 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |      161 | 2024-05-02 | Entropiq                    | W   | 1.000      | -            | -                | -                | false (0.000) |     1.36 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |      223 | 2024-05-01 | BLESSED (Ukrainian team)    | L   | 1.000      | -            | -                | -                | -             |   -16.67 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |      386 | 2024-04-27 | Copenhagen Wolves           | W   | 1.000      | 0.333        | -                | 0.417 (0.139)    | false (0.000) |     4.47 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           28 |      508 | 2024-04-24 | BRANDMAN                    | W   | 1.000      | -            | -                | -                | false (0.000) |     2.68 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |      510 | 2024-04-24 | Begrip Gaming               | W   | 1.000      | -            | -                | -                | false (0.000) |     3.06 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           26 |      900 | 2024-04-18 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    13.89 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           25 |     1018 | 2024-04-16 | Viperio                     | W   | 1.000      | 0.333        | 0.006 (0.002)    | -                | false (0.000) |     8.80 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           24 |     1077 | 2024-04-14 | Verdant                     | W   | 1.000      | 0.333        | 0.027 (0.009)    | 0.662 (0.221)    | false (0.000) |    15.53 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     1150 | 2024-04-12 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    13.34 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     1354 | 2024-04-08 | GamerLegion Academy         | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.567 (0.189)    | -             |    15.01 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     1365 | 2024-04-07 | Alliance                    | W   | 1.000      | 0.143        | 0.017 (0.002)    | -                | -             |    14.66 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           20 |     1377 | 2024-04-07 | Metizport                   | L   | 1.000      | -            | -                | -                | -             |    -5.79 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           19 |     1407 | 2024-04-06 | JANO Esports                | W   | 1.000      | -            | -                | -                | -             |     9.91 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           18 |     1504 | 2024-04-04 | Illuminar Gaming            | W   | 0.990      | 0.333        | 0.008 (0.003)    | 0.433 (0.143)    | -             |    14.20 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           17 |     1524 | 2024-04-03 | Lilmix                      | L   | 0.986      | -            | -                | -                | -             |   -24.23 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     1525 | 2024-04-03 | Flying Angels               | W   | 0.985      | -            | -                | -                | -             |     1.96 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     1906 | 2024-03-23 | KUUSAMO.gg                  | W   | 0.912      | -            | -                | -                | -             |    11.00 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     1908 | 2024-03-23 | Flying Angels               | W   | 0.911      | -            | -                | -                | -             |     1.93 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     1910 | 2024-03-23 | Rok paus vid 45             | W   | 0.911      | -            | -                | -                | -             |     1.95 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     2507 | 2024-03-09 | Alliance                    | L   | 0.817      | -            | -                | -                | -             |   -12.68 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     2511 | 2024-03-09 | Pungrottorna                | W   | 0.817      | -            | -                | -                | -             |     2.68 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     2679 | 2024-03-05 | B8                          | L   | 0.792      | -            | -                | -                | -             |    -8.63 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     2688 | 2024-03-05 | Insilio                     | W   | 0.792      | 0.143        | 0.020 (0.002)    | -                | -             |    16.18 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     2693 | 2024-03-05 | Sashi Esport                | W   | 0.792      | 0.143        | 0.193 (0.022)    | 1.000 (0.113)    | -             |    17.91 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     2725 | 2024-03-04 | Runners                     | W   | 0.786      | -            | -                | -                | -             |     1.86 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            6 |     2746 | 2024-03-04 | RUBY                        | W   | 0.786      | 0.143        | 0.012 (0.001)    | -                | -             |    14.75 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            5 |     2903 | 2024-03-02 | Astralis Talent             | L   | 0.769      | -            | -                | -                | -             |    -9.05 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            4 |     3043 | 2024-02-27 | Lilmix                      | W   | 0.744      | 0.303        | -                | 0.604 (0.136)    | -             |     6.02 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            3 |     3058 | 2024-02-26 | ALTERNATE aTTaX             | L   | 0.739      | -            | -                | -                | -             |    -7.39 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            2 |     3221 | 2024-02-23 | Turów Zgorzelec Esport      | L   | 0.717      | -            | -                | -                | -             |   -12.21 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            1 |     3965 | 2024-02-03 | Gaimin Gladiators           | L   | 0.585      | -            | -                | -                | -             |    -0.94 | chawzyyy, L00m1, Lekr0, spooke, truth     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,936.59)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-18 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-04-07 |      1.000 | $936.59        | $936.59         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
