### Roster Details<br />
Team Name: Intense Game<br />
Roster: ckzao, diozera, fREQ, keiz, mxa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [151](../standings_global.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
Final Rank Value:  778.6<br />
<br />
Final Rank Value (778.6) = Starting Rank Value (700.6) + Head To Head Adjustments (78.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.243[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.6
- 400 + ( ( 0.148 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 700.6


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
|           36 |       90 | 2024-05-29 | FURIA Esports Female    | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | 0 (0.000) |    15.08 | ckzao, diozera, fREQ, keiz, mxa |
|           35 |      109 | 2024-05-28 | FURIA Academy           | W   | 1.000      | 0.384        | -                | 0.169 (0.065)    | 0 (0.000) |    10.48 | ckzao, diozera, fREQ, keiz, mxa |
|           34 |     1066 | 2024-05-16 | bebidarosa              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.65 | ckzao, diozera, fREQ, keiz, mxa |
|           33 |     1313 | 2024-05-13 | Case Esports            | L   | 1.000      | -            | -                | -                | -         |   -12.14 | bsd, ckzao, diozera, fREQ, mxa  |
|           32 |     1355 | 2024-05-12 | ODDIK                   | L   | 1.000      | -            | -                | -                | -         |    -8.82 | bsd, ckzao, diozera, fREQ, mxa  |
|           31 |     1563 | 2024-05-09 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |    -5.05 | bsd, ckzao, diozera, fREQ, mxa  |
|           30 |     1659 | 2024-05-08 | Yawara E-Sports         | W   | 1.000      | 0.435        | 0.002 (0.001)    | 0.319 (0.139)    | 0 (0.000) |    11.10 | bsd, ckzao, diozera, fREQ, mxa  |
|           29 |     1757 | 2024-05-06 | RED Canids              | L   | 1.000      | -            | -                | -                | -         |    -5.13 | bsd, ckzao, diozera, fREQ, mxa  |
|           28 |     2283 | 2024-04-26 | Vikings KR              | W   | 0.977      | 0.143        | 0.004 (0.001)    | 0.313 (0.044)    | 0 (0.000) |    14.96 | bsd, ckzao, diozera, fREQ, mxa  |
|           27 |     2378 | 2024-04-24 | Hype Esports            | W   | 0.965      | -            | -                | -                | 0 (0.000) |     9.06 | bsd, ckzao, diozera, fREQ, mxa  |
|           26 |     2383 | 2024-04-24 | MIBR Academy            | W   | 0.965      | 0.143        | 0.005 (0.001)    | 0.448 (0.062)    | 0 (0.000) |    15.17 | bsd, ckzao, diozera, fREQ, mxa  |
|           25 |     2386 | 2024-04-24 | Sharks Youngsters       | W   | 0.965      | 0.143        | 0.003 (0.000)    | 0.407 (0.056)    | 0 (0.000) |    11.02 | bsd, ckzao, diozera, fREQ, mxa  |
|           24 |     2598 | 2024-04-20 | LaChampionsLiga         | L   | 0.938      | -            | -                | -                | -         |   -21.58 | bsd, ckzao, diozera, fREQ, mxa  |
|           23 |     3570 | 2024-04-04 | Galorys                 | L   | 0.831      | -            | -                | -                | -         |    -9.71 | bsd, ckzao, diozera, fREQ, mxa  |
|           22 |     3826 | 2024-03-28 | Sensei Team             | W   | 0.784      | 0.143        | -                | 0.482 (0.054)    | 0 (0.000) |    12.05 | bsd, ckzao, diozera, fREQ, mxa  |
|           21 |     4004 | 2024-03-25 | Vikings KR              | W   | 0.765      | 0.143        | 0.004 (0.000)    | -                | 0 (0.000) |    10.82 | bsd, ckzao, diozera, fREQ, mxa  |
|           20 |     4030 | 2024-03-24 | KRÜ Esports             | L   | 0.758      | -            | -                | -                | -         |    -9.47 | bsd, ckzao, diozera, mxa, Roz   |
|           19 |     4119 | 2024-03-22 | Dusty Roots             | W   | 0.745      | 0.262        | 0.003 (0.000)    | 0.425 (0.083)    | -         |     9.70 | bsd, ckzao, diozera, mxa, Roz   |
|           18 |     4157 | 2024-03-21 | eSports Recife          | W   | 0.738      | 0.143        | -                | 0.441 (0.047)    | -         |     9.78 | bsd, ckzao, diozera, fREQ, mxa  |
|           17 |     4173 | 2024-03-21 | Bounty Hunters Esports  | L   | 0.738      | -            | -                | -                | -         |   -16.96 | bsd, ckzao, diozera, fREQ, mxa  |
|           16 |     4218 | 2024-03-20 | Hawks                   | W   | 0.732      | -            | -                | -                | -         |    10.10 | bsd, ckzao, diozera, mxa, Roz   |
|           15 |     4257 | 2024-03-19 | MIBR Academy            | L   | 0.725      | -            | -                | -                | -         |   -11.41 | bsd, ckzao, diozera, mxa, Roz   |
|           14 |     4480 | 2024-03-15 | KRÜ Esports             | L   | 0.698      | -            | -                | -                | -         |    -9.25 | bsd, ckzao, diozera, mxa, Roz   |
|           13 |     4580 | 2024-03-13 | Fluxo                   | L   | 0.685      | -            | -                | -                | -         |    -3.75 | bsd, ckzao, diozera, mxa, Roz   |
|           12 |     4661 | 2024-03-12 | ex-Martians             | W   | 0.679      | -            | -                | -                | -         |     7.38 | bsd, ckzao, diozera, mxa, Roz   |
|           11 |     4672 | 2024-03-12 | MIBR Academy            | W   | 0.677      | 0.262        | 0.005 (0.001)    | 0.448 (0.079)    | -         |    10.42 | bsd, ckzao, diozera, mxa, Roz   |
|           10 |     4720 | 2024-03-11 | Yawara E-Sports         | W   | 0.671      | 0.262        | -                | 0.319 (0.056)    | -         |     9.41 | bsd, ckzao, diozera, mxa, Roz   |
|            9 |     4973 | 2024-03-06 | paiN Gaming Academy     | L   | 0.639      | -            | -                | -                | -         |   -10.13 | bsd, ckzao, diozera, mxa, Roz   |
|            8 |     4983 | 2024-03-06 | MIBR Academy            | W   | 0.638      | 0.143        | 0.005 (0.000)    | -                | -         |    10.71 | bsd, ckzao, diozera, mxa, Roz   |
|            7 |     5082 | 2024-03-05 | paiN Gaming Academy     | L   | 0.631      | -            | -                | -                | -         |   -10.28 | bsd, ckzao, diozera, mxa, Roz   |
|            6 |     5205 | 2024-03-03 | MIBR Academy            | W   | 0.619      | 0.143        | 0.005 (0.000)    | -                | -         |    10.23 | bsd, ckzao, diozera, mxa, Roz   |
|            5 |     5402 | 2024-02-29 | Yawara E-Sports         | W   | 0.598      | -            | -                | -                | -         |     9.10 | bsd, ckzao, diozera, mxa, Roz   |
|            4 |     5448 | 2024-02-28 | Bombril 1001 Utilidades | W   | 0.591      | -            | -                | -                | -         |     7.98 | bsd, ckzao, diozera, mxa, Roz   |
|            3 |     5499 | 2024-02-27 | Sharks Youngsters       | W   | 0.585      | -            | -                | -                | -         |     8.40 | bsd, ckzao, diozera, mxa, Roz   |
|            2 |     6257 | 2024-02-14 | Fluxo                   | L   | 0.499      | -            | -                | -                | -         |    -2.86 | bsd, ckzao, diozera, mxa, Roz   |
|            1 |     6907 | 2024-01-31 | paiN Gaming Academy     | L   | 0.405      | -            | -                | -                | -         |    -8.07 | bsd, ckzao, diozera, mxa, Roz   |

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
