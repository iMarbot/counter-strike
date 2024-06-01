### Roster Details<br />
Team Name: showmakerz<br />
Roster: bsover, Doobs, jakoby, julle, Leon1das<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [392](../standings_global.md)<br />
Regional Rank: [234]( ../standings_europe.md)<br />
Final Rank Value:  559.9<br />
<br />
Final Rank Value (559.9) = Starting Rank Value (536.6) + Head To Head Adjustments (23.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.6
- 400 + ( ( 0.067 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 536.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      586 | 2024-05-21 | Kappa Bar           | L   | 1.000      | -            | -                | -                | -         |   -14.54 | bsover, Doobs, jakoby, julle, Leon1das         |
|           45 |     1313 | 2024-05-13 | Podwars             | L   | 1.000      | -            | -                | -                | -         |   -13.76 | bsover, julle, Leon1das, majkn, zeroxd         |
|           44 |     1678 | 2024-05-07 | Kario Mart          | W   | 1.000      | 0.143        | -                | 0.073 (0.010)    | 0 (0.000) |     9.32 | bsover, Doobs, jakoby, julle, Leon1das         |
|           43 |     2304 | 2024-04-25 | Begrip Gaming       | W   | 0.971      | 0.143        | 0.000 (0.000)    | 0.317 (0.044)    | 0 (0.000) |    14.34 | bsover, Doobs, jakoby, julle, Leon1das         |
|           42 |     2698 | 2024-04-19 | Curlews             | W   | 0.930      | -            | -                | -                | 0 (0.000) |     7.52 | bsover, Doobs, jakoby, julle, Leon1das         |
|           41 |     2814 | 2024-04-17 | playanfinest        | L   | 0.918      | -            | -                | -                | -         |   -19.98 | agoz, bsover, jakoby, Leon1das, majkn          |
|           40 |     2835 | 2024-04-17 | Begrip Gaming       | W   | 0.917      | 0.143        | 0.000 (0.000)    | 0.317 (0.042)    | 0 (0.000) |    14.32 | agoz, bsover, jakoby, Leon1das, majkn          |
|           39 |     3159 | 2024-04-10 | AURA                | L   | 0.871      | -            | -                | -                | -         |    -7.87 | bsover, Doobs, jakoby, julle, Leon1das         |
|           38 |     3171 | 2024-04-10 | regelett            | W   | 0.871      | 0.143        | -                | 0.129 (0.016)    | 0 (0.000) |     7.59 | bsover, Doobs, jakoby, julle, Leon1das         |
|           37 |     3243 | 2024-04-09 | Kappa Borr          | L   | 0.863      | -            | -                | -                | -         |   -16.05 | bsover, Doobs, jakoby, julle, Leon1das         |
|           36 |     3535 | 2024-04-03 | Podwars             | L   | 0.825      | -            | -                | -                | -         |   -10.50 | agoz, bsover, jakoby, julle, Leon1das          |
|           35 |     3540 | 2024-04-03 | AURA                | W   | 0.824      | 0.143        | 0.011 (0.001)    | 0.186 (0.022)    | 0 (0.000) |    18.08 | agoz, bsover, jakoby, julle, Leon1das          |
|           34 |     3599 | 2024-04-02 | Johnny Speeds       | L   | 0.817      | -            | -                | -                | -         |    -2.18 | bsover, Doobs, jakoby, julle, Leon1das         |
|           33 |     3784 | 2024-03-27 | Begrip Gaming       | W   | 0.778      | 0.143        | 0.000 (0.000)    | 0.317 (0.035)    | 0 (0.000) |    12.30 | bsover, Doobs, jakoby, julle, Leon1das         |
|           32 |     4001 | 2024-03-23 | Flying Angels       | L   | 0.750      | -            | -                | -                | -         |   -16.91 | bsover, jakoby, julle, KriLLe, Leon1das        |
|           31 |     4081 | 2024-03-21 | Alliance            | L   | 0.738      | -            | -                | -                | -         |    -3.80 | bsover, Doobs, jakoby, julle, Leon1das         |
|           30 |     4198 | 2024-03-18 | Kario Mart          | W   | 0.718      | 0.143        | -                | 0.073 (0.008)    | 0 (0.000) |     6.07 | bsover, Doobs, jakoby, julle, Leon1das         |
|           29 |     4728 | 2024-03-09 | Johnny Speeds       | L   | 0.656      | -            | -                | -                | -         |    -1.56 | bsover, jakoby, julle, Majkn, siz              |
|           28 |     6496 | 2024-02-03 | Sashi Esport        | L   | 0.424      | -            | -                | -                | -         |    -0.79 | agoz, bsover, jakoby, julle, Leon1das          |
|           27 |     6500 | 2024-02-03 | Sashi Esport        | W   | 0.424      | -            | -                | -                | 0 (0.000) |     6.87 | agoz, bsover, jakoby, julle, Leon1das          |
|           26 |     6509 | 2024-02-03 | Alliance            | W   | 0.424      | 0.143        | 0.004 (0.000)    | 0.529 (0.032)    | 0 (0.000) |    10.97 | agoz, bsover, jakoby, julle, Leon1das          |
|           25 |     6531 | 2024-02-03 | AURA                | W   | 0.424      | 0.143        | -                | 0.274 (0.017)    | -         |     7.70 | agoz, bsover, jakoby, julle, Leon1das          |
|           24 |     6598 | 2024-02-02 | Sashi Esport        | L   | 0.417      | -            | -                | -                | -         |    -0.67 | agoz, jakoby, julle, Leon1das, majkn           |
|           23 |     6606 | 2024-02-02 | Gaimin Gladiators   | W   | 0.417      | 0.143        | 0.092 (0.005)    | 0.711 (0.042)    | -         |    12.91 | agoz, jakoby, julle, Leon1das, majkn           |
|           22 |     6871 | 2024-01-28 | Permitta Esports    | L   | 0.383      | -            | -                | -                | -         |    -1.07 | agoz, bsover, jakoby, julle, Leon1das          |
|           21 |     7831 | 2024-01-12 | Infinite Gaming     | L   | 0.278      | -            | -                | -                | -         |    -4.88 | agoz, bsover, julle, Leon1das, majkn           |
|           20 |     7868 | 2024-01-12 | ALTERNATE aTTaX     | W   | 0.278      | 0.143        | 0.004 (0.000)    | -                | -         |     6.53 | agoz, bsover, julle, Leon1das, majkn           |
|           19 |     8116 | 2024-01-09 | Sashi Esport        | L   | 0.257      | -            | -                | -                | -         |    -0.40 | bsover, Doobs, julle, Leon1das, majkn          |
|           18 |     8252 | 2024-01-03 | Begrip Gaming       | L   | 0.218      | -            | -                | -                | -         |    -2.75 | agoz, bsover, Doobs, julle, Leon1das           |
|           17 |     8259 | 2024-01-03 | onliners5           | W   | 0.217      | 0.143        | 0.001 (0.000)    | -                | -         |     4.13 | agoz, bsover, Doobs, julle, Leon1das           |
|           16 |     8305 | 2023-12-29 | monaco              | L   | 0.184      | -            | -                | -                | -         |    -2.33 | agoz, bsover, julle, Leon1das, majkn           |
|           15 |     8413 | 2023-12-18 | ARCRED              | L   | 0.110      | -            | -                | -                | -         |    -0.74 | agoz, bsover, Doobs, julle, Leon1das           |
|           14 |     8417 | 2023-12-18 | Sashi Esport        | W   | 0.109      | -            | -                | -                | -         |     1.78 | agoz, bsover, Doobs, julle, Leon1das           |
|           13 |     8419 | 2023-12-18 | Sprout              | L   | 0.109      | -            | -                | -                | -         |    -1.59 | agoz, bsover, Doobs, julle, Leon1das           |
|           12 |     8775 | 2023-12-14 | Beyonce Enjoyers    | W   | 0.085      | -            | -                | -                | -         |     0.84 | agoz, bsover, Doobs, julle, Leon1das           |
|           11 |     8778 | 2023-12-14 | SERA Esport         | W   | 0.085      | -            | -                | -                | -         |     1.10 | agoz, bsover, Doobs, julle, Leon1das           |
|           10 |     8816 | 2023-12-13 | Kappa Bar           | W   | 0.078      | -            | -                | -                | -         |     1.19 | agoz, bsover, Doobs, julle, Leon1das           |
|            9 |     8838 | 2023-12-13 | latch gibb          | W   | 0.077      | -            | -                | -                | -         |     1.03 | agoz, bsover, Doobs, julle, Leon1das           |
|            8 |     8841 | 2023-12-13 | angelnumbers        | W   | 0.077      | 0.143        | 0.001 (0.000)    | -                | -         |     1.57 | agoz, bsover, Doobs, julle, Leon1das           |
|            7 |     8866 | 2023-12-12 | ishjarnor           | L   | 0.071      | -            | -                | -                | -         |    -1.53 | DORFEN, Flink, rozenn, wiking, z1egers         |
|            6 |     8870 | 2023-12-12 | flowskola           | W   | 0.071      | -            | -                | -                | -         |     0.71 | Chawzyyy, magi, MistFire, realyummy, Svedjehed |
|            5 |     8923 | 2023-12-11 | ex-KRC Genk Esports | L   | 0.064      | -            | -                | -                | -         |    -0.72 | CrePoW, Philong, ReFuZR, Wumbo, yOOm           |
|            4 |     9213 | 2023-12-06 | XI Esport           | W   | 0.031      | 0.333        | 0.001 (0.000)    | -                | -         |     0.69 | bsover, Doobs, julle, Leon1das, majkn          |
|            3 |     9296 | 2023-12-05 | ROSOMAHA            | W   | 0.024      | -            | -                | -                | -         |     0.45 | bsover, Doobs, julle, Leon1das, majkn          |
|            2 |     9375 | 2023-12-03 | Pera Esports        | L   | 0.010      | -            | -                | -                | -         |    -0.03 | agoz, bsover, Doobs, Leon1das, majkn           |
|            1 |     9469 | 2023-12-02 | Betera Esports      | L   | 0.004      | -            | -                | -                | -         |    -0.02 | agoz, bsover, Doobs, julle, majkn              |

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
