### Roster Details<br />
Team Name: Fluxo Demons<br />
Roster: annaEX, goddess, josi, julih, yungher<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [84](../standings_global.md)<br />
Regional Rank: [20]( ../standings_americas.md)<br />
Final Rank Value:  904.0<br />
<br />
Final Rank Value (904.0) = Starting Rank Value (864.4) + Head To Head Adjustments (39.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.282[<sup>2</sup>](#table1)
- Opponent Network: 0.035[<sup>2</sup>](#table1)
- LAN Wins: 0.209[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 864.4
- 400 + ( ( 0.228 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 864.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     1773 | 2024-05-05 | Illusion             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.50 | annaEX, goddess, josi, julih, yungher    |
|           26 |     1821 | 2024-05-04 | HUMBLE.gg            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.77 | annaEX, goddess, josi, julih, yungher    |
|           25 |     2529 | 2024-04-21 | FURIA Esports Female | W   | 0.945      | 0.333        | 0.018 (0.006)    | 0.159 (0.050)    | 1 (0.945) |    11.95 | annaEX, goddess, julih, poppins, yungher |
|           24 |     2551 | 2024-04-21 | MIBR Female          | W   | 0.943      | 0.333        | 0.015 (0.005)    | 0.227 (0.071)    | 1 (0.943) |     8.79 | annaEX, goddess, julih, poppins, yungher |
|           23 |     2727 | 2024-04-19 | FURIA Esports Female | W   | 0.931      | 0.332        | 0.018 (0.006)    | 0.159 (0.049)    | 0 (0.000) |    12.78 | annaEX, goddess, julih, poppins, yungher |
|           22 |     3066 | 2024-04-13 | w7m esports Female   | W   | 0.892      | 0.250        | 0.010 (0.002)    | 0.091 (0.020)    | 0 (0.000) |     6.61 | annaEX, Babs, goddess, julih, yungher    |
|           21 |     3073 | 2024-04-13 | Five7                | W   | 0.891      | -            | -                | -                | 0 (0.000) |     3.55 | annaEX, Babs, goddess, julih, yungher    |
|           20 |     3226 | 2024-04-10 | GENKID4M4            | W   | 0.871      | 0.332        | 0.004 (0.001)    | 0.032 (0.009)    | 0 (0.000) |     6.10 | annaEX, goddess, julih, poppins, yungher |
|           19 |     3446 | 2024-04-06 | MIBR Female          | L   | 0.845      | -            | -                | -                | -         |   -18.61 | annaEX, goddess, josi, julih, poppins    |
|           18 |     3449 | 2024-04-06 | Five7                | W   | 0.845      | -            | -                | -                | -         |     3.28 | annaEX, goddess, josi, julih, poppins    |
|           17 |     3566 | 2024-04-04 | Illusion             | W   | 0.831      | -            | -                | -                | -         |     4.73 | annaEX, goddess, julih, poppins, yungher |
|           16 |     3872 | 2024-03-27 | ex-DIVINA Female     | W   | 0.778      | 0.332        | 0.004 (0.001)    | 0.053 (0.014)    | -         |     5.99 | annaEX, goddess, julih, poppins, yungher |
|           15 |     4219 | 2024-03-20 | MIBR Female          | W   | 0.732      | 0.332        | 0.015 (0.004)    | 0.227 (0.055)    | -         |     6.68 | annaEX, goddess, julih, poppins, yungher |
|           14 |     4521 | 2024-03-14 | w7m esports Female   | W   | 0.692      | 0.332        | 0.010 (0.002)    | 0.091 (0.021)    | -         |     6.26 | annaEX, goddess, julih, poppins, yungher |
|           13 |     4974 | 2024-03-06 | Atrix Esports        | W   | 0.638      | 0.332        | 0.006 (0.001)    | 0.190 (0.040)    | -         |     5.80 | annaEX, goddess, julih, poppins, yungher |
|           12 |     5263 | 2024-03-02 | Five7                | W   | 0.612      | -            | -                | -                | -         |     2.83 | annaEX, goddess, josi, julih, yungher    |
|           11 |     5654 | 2024-02-24 | SoJoga               | L   | 0.565      | -            | -                | -                | -         |   -13.45 | goddess, julih, poppins, r4ul, yungher   |
|           10 |     5658 | 2024-02-24 | spotlight            | W   | 0.565      | -            | -                | -                | -         |     2.40 | goddess, julih, poppins, r4ul, yungher   |
|            9 |     5672 | 2024-02-24 | Myth e-Sports        | L   | 0.564      | -            | -                | -                | -         |   -14.13 | goddess, julih, poppins, r4ul, yungher   |
|            8 |     5678 | 2024-02-24 | podmaldito           | W   | 0.564      | -            | -                | -                | -         |     3.31 | goddess, julih, poppins, r4ul, yungher   |
|            7 |     6691 | 2024-02-03 | Brasil Storm Female  | W   | 0.426      | -            | -                | -                | -         |     2.83 | cellax, coldizinha, croma, eleveN, xan   |
|            6 |     6693 | 2024-02-03 | MIBR Female          | W   | 0.425      | 0.250        | 0.015 (0.002)    | 0.227 (0.024)    | -         |     4.50 | annaEX, goddess, josi, julih, yungher    |
|            5 |     7151 | 2024-01-27 | SOLOVE               | L   | 0.378      | -            | -                | -                | -         |    -9.55 | goddess, julih, nani, poppins, yungher   |
|            4 |     7166 | 2024-01-27 | Romanticos           | L   | 0.378      | -            | -                | -                | -         |    -9.21 | goddess, julih, nani, poppins, yungher   |
|            3 |     9242 | 2023-12-10 | NAVI Javelins        | L   | 0.056      | -            | -                | -                | -         |    -1.10 | goddess, julih, nani, poppins, yungher   |
|            2 |     9375 | 2023-12-08 | Team Pigeons         | W   | 0.044      | -            | -                | -                | 1 (0.044) |     0.52 | goddess, julih, nani, poppins, yungher   |
|            1 |     9392 | 2023-12-08 | FlyQuest RED         | W   | 0.042      | -            | -                | -                | 1 (0.042) |     0.47 | goddess, julih, nani, poppins, yungher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,874.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $750.00        | $750.00         |
| 2024-04-21 |      0.945 | $5,000.00      | $4,726.39       |
| 2024-04-13 |      0.892 | $750.00        | $669.10         |
| 2024-04-06 |      0.845 | $250.00        | $211.37         |
| 2024-03-02 |      0.612 | $750.00        | $459.08         |
| 2024-02-03 |      0.426 | $750.00        | $319.48         |
| 2023-12-10 |      0.057 | $13,000.00     | $739.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
