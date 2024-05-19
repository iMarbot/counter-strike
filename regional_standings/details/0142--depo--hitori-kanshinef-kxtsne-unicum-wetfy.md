### Roster Details<br />
Team Name: Depo<br />
Roster: Hitori, kanshineF, KxtsnE, unicum, wetfy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [142](../standings_global.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
Final Rank Value:  783.3<br />
<br />
Final Rank Value (783.3) = Starting Rank Value (783.0) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.225[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 783.0
- 400 + ( ( 0.193 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 783.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3531 | 2024-02-16 | R-EVOLUTION           | L   | 0.671      | -            | -                | -                | -            |   -17.65 | Hitori, kanshineF, KxtsnE, unicum, wetfy         |
|           11 |     5265 | 2023-12-25 | Cyber Generation      | W   | 0.317      | 0.143        | 0.002 (0.000)    | 0.044 (0.002)    | true (0.317) |     3.22 | BEASTOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|           10 |     5307 | 2023-12-20 | Wakanda Cyber         | W   | 0.283      | 0.143        | -                | 0.000 (0.000)    | true (0.283) |     0.87 | captoun, du6ai, FERGANAA, frist4f, LightFeeling  |
|            9 |     5391 | 2023-12-17 | Storm Uzbekistan      | W   | 0.263      | 0.143        | 0.001 (0.000)    | 0.009 (0.000)    | true (0.263) |     2.41 | BEASFOFEAST, CEKKA, dARkjezz, hawachi, uRuRuRkiN |
|            8 |     5496 | 2023-12-16 | Storm Uzbekistan      | W   | 0.256      | 0.143        | 0.001 (0.000)    | 0.009 (0.000)    | true (0.256) |     2.35 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |
|            7 |     5517 | 2023-12-16 | Depo                  | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | true (0.256) |     1.93 | aokah1ka, KxtsnE, lordsei, teygu, unicum         |
|            6 |     6055 | 2023-12-03 | STEALTH (Kazakh team) | W   | 0.170      | 0.342        | 0.004 (0.000)    | 0.020 (0.001)    | true (0.170) |     1.96 | Gilzera, Goodlikee, ner, R3LiFw0w, shiawase777   |
|            5 |     6132 | 2023-12-02 | STEALTH (Kazakh team) | W   | 0.163      | 0.342        | 0.004 (0.000)    | 0.020 (0.001)    | true (0.163) |     1.89 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |
|            4 |     6147 | 2023-12-01 | CUBE BY SND           | W   | 0.162      | 0.342        | 0.013 (0.001)    | 0.138 (0.008)    | true (0.162) |     1.85 | alkarenn, dosikzz, OxygeN, rinn, syph0           |
|            3 |     6678 | 2023-11-19 | Depo                  | W   | 0.077      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | true (0.077) |     0.60 | BEASFOFEAST, CEKKA, KxtsnE, lordsei, teygu       |
|            2 |     6746 | 2023-11-18 | Bushido Gaming        | W   | 0.070      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | true (0.070) |     0.52 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |
|            1 |     6751 | 2023-11-18 | META (Uzbek team)     | W   | 0.069      | 0.143        | 0.000 (0.000)    | -                | -            |     0.37 | fr0k, Hitori, icyvlone, kanshineF, wetfy         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,834.79)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-25 |      0.317 | $1,693.79      | $537.07         |
| 2023-12-17 |      0.263 | $1,044.66      | $275.05         |
| 2023-12-03 |      0.170 | $5,500.00      | $934.49         |
| 2023-11-19 |      0.077 | $1,145.63      | $88.18          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
