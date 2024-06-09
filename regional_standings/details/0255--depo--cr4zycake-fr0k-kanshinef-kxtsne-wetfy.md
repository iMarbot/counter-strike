### Roster Details<br />
Team Name: Depo<br />
Roster: Cr4zyCake, fr0k, kanshineF, KxtsnE, wetfy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [255](../standings_global.md)<br />
Regional Rank: [36]( ../standings_asia.md)<br />
Final Rank Value:  681.7<br />
<br />
Final Rank Value (681.7) = Starting Rank Value (663.3) + Head To Head Adjustments (18.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.259[<sup>1</sup>](#table2)
- Bounty Collected: 0.196[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.3
- 400 + ( ( 0.130 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 663.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       17 | 2024-05-29 | MetroTeam         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.79 | Cr4zyCake, fr0k, kanshineF, KxtsnE, wetfy        |
|           11 |       20 | 2024-05-29 | Cyber Generation  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     5.66 | Cr4zyCake, fr0k, kanshineF, KxtsnE, wetfy        |
|           10 |       21 | 2024-05-29 | olds              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | -         |     9.96 | Cr4zyCake, fr0k, kanshineF, KxtsnE, wetfy        |
|            9 |     6156 | 2024-02-16 | Revolution Gaming | L   | 0.510      | -            | -                | -                | -         |   -11.80 | Hitori, kanshineF, KxtsnE, unicum, wetfy         |
|            8 |     8581 | 2023-12-25 | Storm Uzbekistan  | W   | 0.156      | 0.143        | 0.015 (0.000)    | 0.036 (0.001)    | 1 (0.156) |     3.13 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            7 |     8646 | 2023-12-20 | Wakanda Cyber     | W   | 0.122      | 0.143        | -                | 0.000 (0.000)    | 1 (0.122) |     0.70 | captoun, du6ai, FERGANAA, frist4f, LightFeeling  |
|            6 |     8759 | 2023-12-17 | Storm Uzbekistan  | W   | 0.102      | 0.143        | 0.015 (0.000)    | 0.036 (0.001)    | 1 (0.102) |     2.06 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            5 |     8901 | 2023-12-16 | Storm Uzbekistan  | W   | 0.095      | 0.143        | 0.015 (0.000)    | 0.036 (0.000)    | 1 (0.095) |     1.94 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |
|            4 |     8923 | 2023-12-16 | Depo              | W   | 0.095      | 0.143        | 0.000 (0.000)    | -                | 1 (0.095) |     0.82 | aokah1ka, KxtsnE, lordsei, teygu, unicum         |
|            3 |     9670 | 2023-12-03 | STEALTH           | W   | 0.009      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.009) |     0.10 | Gilzera, Goodlikee, ner, R3LiFw0w, shiawase777   |
|            2 |     9788 | 2023-12-02 | STEALTH           | W   | 0.002      | 0.342        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.002) |     0.02 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |
|            1 |     9804 | 2023-12-01 | CUBE BY SND       | W   | 0.001      | 0.342        | 0.002 (0.000)    | 0.027 (0.000)    | 1 (0.001) |     0.02 | alkarenn, dosikzz, OxygeN, rinn, syph0           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($419.69)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-25 |      0.156 | $1,693.79      | $264.26         |
| 2023-12-17 |      0.102 | $1,044.66      | $106.79         |
| 2023-12-03 |      0.009 | $5,500.00      | $48.63          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
