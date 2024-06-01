### Roster Details<br />
Team Name: Intense Game<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [139](../standings_global.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
Final Rank Value:  794.1<br />
<br />
Final Rank Value (794.1) = Starting Rank Value (702.0) + Head To Head Adjustments (92.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 702.0
- 400 + ( ( 0.148 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 702.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |       83 | 2024-05-29 | FURIA Esports Female    | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | 0 (0.000) |    14.43 | ckzao, diozera, fREQ, keiz, mxa |
|           36 |      102 | 2024-05-28 | FURIA Academy           | W   | 1.000      | 0.384        | -                | 0.169 (0.065)    | 0 (0.000) |     9.93 | ckzao, diozera, fREQ, keiz, mxa |
|           35 |     1043 | 2024-05-16 | paiN Gaming Academy     | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.374 (0.053)    | 0 (0.000) |    14.58 | bsd, ckzao, diozera, fREQ, mxa  |
|           34 |     1056 | 2024-05-16 | bebidarosa              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.63 | bsd, ckzao, diozera, fREQ, mxa  |
|           33 |     1302 | 2024-05-13 | Case Esports            | L   | 1.000      | -            | -                | -                | -         |   -12.15 | bsd, ckzao, diozera, fREQ, mxa  |
|           32 |     1343 | 2024-05-12 | ODDIK                   | L   | 1.000      | -            | -                | -                | -         |    -8.65 | bsd, ckzao, diozera, fREQ, mxa  |
|           31 |     1548 | 2024-05-09 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |    -5.00 | bsd, ckzao, diozera, fREQ, mxa  |
|           30 |     1641 | 2024-05-08 | Yawara E-Sports         | W   | 1.000      | 0.435        | 0.002 (0.001)    | 0.319 (0.139)    | 0 (0.000) |    11.07 | bsd, ckzao, diozera, fREQ, mxa  |
|           29 |     1734 | 2024-05-06 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |    -5.09 | bsd, ckzao, diozera, fREQ, mxa  |
|           28 |     2247 | 2024-04-26 | Vikings KR              | W   | 0.977      | 0.143        | 0.004 (0.001)    | -                | 0 (0.000) |    14.96 | bsd, ckzao, diozera, fREQ, mxa  |
|           27 |     2337 | 2024-04-24 | Hype Esports            | W   | 0.965      | -            | -                | -                | 0 (0.000) |     9.08 | bsd, ckzao, diozera, fREQ, mxa  |
|           26 |     2342 | 2024-04-24 | MIBR Academy            | W   | 0.965      | 0.143        | 0.005 (0.001)    | 0.439 (0.061)    | 0 (0.000) |    15.16 | bsd, ckzao, diozera, fREQ, mxa  |
|           25 |     2345 | 2024-04-24 | Sharks Youngsters       | W   | 0.965      | 0.143        | 0.003 (0.000)    | 0.422 (0.058)    | 0 (0.000) |    11.42 | bsd, ckzao, diozera, fREQ, mxa  |
|           24 |     2545 | 2024-04-20 | LaChampionsLiga         | L   | 0.938      | -            | -                | -                | -         |   -21.62 | bsd, ckzao, diozera, fREQ, mxa  |
|           23 |     3485 | 2024-04-04 | Galorys                 | L   | 0.831      | -            | -                | -                | -         |    -9.35 | bsd, ckzao, diozera, fREQ, mxa  |
|           22 |     3732 | 2024-03-28 | Sensei Team             | W   | 0.784      | 0.143        | -                | 0.482 (0.054)    | 0 (0.000) |    12.05 | bsd, ckzao, diozera, fREQ, mxa  |
|           21 |     3907 | 2024-03-25 | Vikings KR              | W   | 0.765      | 0.143        | 0.004 (0.000)    | -                | -         |    10.84 | bsd, ckzao, diozera, fREQ, mxa  |
|           20 |     3934 | 2024-03-24 | KRÜ Esports             | L   | 0.758      | -            | -                | -                | -         |    -9.50 | bsd, ckzao, diozera, mxa, Roz   |
|           19 |     4021 | 2024-03-22 | Dusty Roots             | W   | 0.745      | 0.262        | 0.003 (0.000)    | 0.425 (0.083)    | -         |     9.70 | bsd, ckzao, diozera, mxa, Roz   |
|           18 |     4059 | 2024-03-21 | eSports Recife          | W   | 0.738      | 0.143        | -                | 0.441 (0.047)    | -         |     9.77 | bsd, ckzao, diozera, fREQ, mxa  |
|           17 |     4075 | 2024-03-21 | Bounty Hunters Esports  | L   | 0.738      | -            | -                | -                | -         |   -17.02 | bsd, ckzao, diozera, fREQ, mxa  |
|           16 |     4118 | 2024-03-20 | Hawks                   | W   | 0.732      | -            | -                | -                | -         |    10.10 | bsd, ckzao, diozera, mxa, Roz   |
|           15 |     4155 | 2024-03-19 | MIBR Academy            | L   | 0.725      | -            | -                | -                | -         |   -11.45 | bsd, ckzao, diozera, mxa, Roz   |
|           14 |     4372 | 2024-03-15 | KRÜ Esports             | L   | 0.698      | -            | -                | -                | -         |    -9.28 | bsd, ckzao, diozera, mxa, Roz   |
|           13 |     4466 | 2024-03-13 | Fluxo                   | L   | 0.685      | -            | -                | -                | -         |    -3.91 | bsd, ckzao, diozera, mxa, Roz   |
|           12 |     4542 | 2024-03-12 | ex-Martians             | W   | 0.679      | -            | -                | -                | -         |     7.34 | bsd, ckzao, diozera, mxa, Roz   |
|           11 |     4552 | 2024-03-12 | MIBR Academy            | W   | 0.677      | 0.262        | 0.005 (0.001)    | 0.439 (0.078)    | -         |    10.37 | bsd, ckzao, diozera, mxa, Roz   |
|           10 |     4598 | 2024-03-11 | Yawara E-Sports         | W   | 0.671      | 0.262        | -                | 0.319 (0.056)    | -         |     9.38 | bsd, ckzao, diozera, mxa, Roz   |
|            9 |     4842 | 2024-03-06 | paiN Gaming Academy     | L   | 0.639      | -            | -                | -                | -         |   -10.09 | bsd, ckzao, diozera, mxa, Roz   |
|            8 |     4852 | 2024-03-06 | MIBR Academy            | W   | 0.638      | 0.143        | 0.005 (0.000)    | -                | -         |    10.64 | bsd, ckzao, diozera, mxa, Roz   |
|            7 |     4943 | 2024-03-05 | paiN Gaming Academy     | L   | 0.631      | -            | -                | -                | -         |   -10.24 | bsd, ckzao, diozera, mxa, Roz   |
|            6 |     5059 | 2024-03-03 | MIBR Academy            | W   | 0.619      | -            | -                | -                | -         |    10.17 | bsd, ckzao, diozera, mxa, Roz   |
|            5 |     5253 | 2024-02-29 | Yawara E-Sports         | W   | 0.598      | -            | -                | -                | -         |     9.07 | bsd, ckzao, diozera, mxa, Roz   |
|            4 |     5297 | 2024-02-28 | Bombril 1001 Utilidades | W   | 0.591      | -            | -                | -                | -         |     7.96 | bsd, ckzao, diozera, mxa, Roz   |
|            3 |     5347 | 2024-02-27 | Sharks Youngsters       | W   | 0.585      | -            | -                | -                | -         |     8.79 | bsd, ckzao, diozera, mxa, Roz   |
|            2 |     6076 | 2024-02-14 | Fluxo                   | L   | 0.499      | -            | -                | -                | -         |    -2.85 | bsd, ckzao, diozera, mxa, Roz   |
|            1 |     6698 | 2024-01-31 | paiN Gaming Academy     | L   | 0.405      | -            | -                | -                | -         |    -8.06 | bsd, ckzao, diozera, mxa, Roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($806.13)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.805 | $130.39        | $105.01         |
| 2024-03-24 |      0.758 | $500.00        | $379.03         |
| 2024-03-06 |      0.639 | $504.19        | $322.09         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
