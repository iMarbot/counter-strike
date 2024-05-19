### Roster Details<br />
Team Name: Intense Game<br />
Roster: bsd, ckzao, diozera, fREQ, mxa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [156](../standings_global.md)<br />
Regional Rank: [27]( ../standings_americas.md)<br />
Final Rank Value:  771.8<br />
<br />
Final Rank Value (771.8) = Starting Rank Value (716.2) + Head To Head Adjustments (55.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 716.2
- 400 + ( ( 0.159 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 716.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |      413 | 2024-04-26 | Vikings KR                     | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.210 (0.030)    | false (0.000) |    15.74 | bsd, ckzao, diozera, fREQ, mxa      |
|           35 |      499 | 2024-04-24 | Hype E-Sports (Brazilian team) | W   | 1.000      | -            | -                | -                | false (0.000) |     7.07 | bsd, ckzao, diozera, fREQ, mxa      |
|           34 |      503 | 2024-04-24 | MIBR Academy                   | W   | 1.000      | 0.143        | 0.011 (0.002)    | 0.455 (0.065)    | false (0.000) |    14.53 | bsd, ckzao, diozera, fREQ, mxa      |
|           33 |      505 | 2024-04-24 | Sharks Youngsters              | W   | 1.000      | 0.143        | -                | 0.211 (0.030)    | false (0.000) |    10.75 | bsd, ckzao, diozera, fREQ, mxa      |
|           32 |      682 | 2024-04-20 | LaChampionsLiga                | L   | 1.000      | -            | -                | -                | -             |   -24.49 | bsd, ckzao, diozera, fREQ, mxa      |
|           31 |     1474 | 2024-04-04 | Galorys                        | L   | 0.992      | -            | -                | -                | -             |   -11.29 | bsd, ckzao, diozera, mxa, Roz       |
|           30 |     1689 | 2024-03-28 | Sensei Team                    | W   | 0.945      | 0.143        | 0.006 (0.001)    | 0.409 (0.055)    | false (0.000) |    14.02 | bsd, ckzao, diozera, mxa, Roz       |
|           29 |     1838 | 2024-03-25 | Vikings KR                     | W   | 0.926      | 0.143        | 0.009 (0.001)    | -                | false (0.000) |    12.69 | bsd, ckzao, diozera, mxa, Roz       |
|           28 |     1852 | 2024-03-24 | KRÜ Esports                    | L   | 0.919      | -            | -                | -                | -             |   -14.89 | bsd, ckzao, diozera, mxa, Roz       |
|           27 |     1928 | 2024-03-22 | Dusty Roots                    | W   | 0.906      | 0.262        | 0.005 (0.001)    | 0.352 (0.083)    | false (0.000) |    11.08 | bsd, ckzao, diozera, mxa, Roz       |
|           26 |     1960 | 2024-03-21 | 2024                           | W   | 0.899      | -            | -                | -                | false (0.000) |     9.32 | bsd, ckzao, diozera, mxa, Roz       |
|           25 |     1972 | 2024-03-21 | Bounty Hunters Esports         | L   | 0.899      | -            | -                | -                | -             |   -20.93 | bsd, ckzao, diozera, mxa, Roz       |
|           24 |     2009 | 2024-03-20 | Hawks (Argentinian team)       | W   | 0.893      | -            | -                | -                | false (0.000) |    12.59 | bsd, ckzao, diozera, mxa, Roz       |
|           23 |     2044 | 2024-03-19 | MIBR Academy                   | L   | 0.886      | -            | -                | -                | -             |   -13.59 | bsd, ckzao, diozera, mxa, Roz       |
|           22 |     2211 | 2024-03-15 | KRÜ Esports                    | L   | 0.859      | -            | -                | -                | -             |   -15.14 | bsd, ckzao, diozera, mxa, Roz       |
|           21 |     2299 | 2024-03-13 | Fluxo                          | L   | 0.846      | -            | -                | -                | -             |    -5.29 | bsd, ckzao, diozera, mxa, Roz       |
|           20 |     2359 | 2024-03-12 | Martians                       | W   | 0.840      | -            | -                | -                | false (0.000) |     8.15 | bsd, ckzao, diozera, mxa, Roz       |
|           19 |     2368 | 2024-03-12 | MIBR Academy                   | W   | 0.839      | 0.262        | 0.011 (0.002)    | 0.455 (0.100)    | -             |    13.05 | bsd, ckzao, diozera, mxa, Roz       |
|           18 |     2405 | 2024-03-11 | Yawara E-Sports                | W   | 0.832      | 0.262        | 0.005 (0.001)    | 0.361 (0.079)    | -             |    11.59 | bsd, ckzao, diozera, mxa, Roz       |
|           17 |     2605 | 2024-03-06 | MIBR Academy                   | W   | 0.799      | 0.143        | 0.011 (0.001)    | 0.455 (0.052)    | -             |    14.32 | bsd, ckzao, diozera, mxa, Roz       |
|           16 |     2777 | 2024-03-03 | MIBR Academy                   | W   | 0.780      | 0.143        | 0.011 (0.001)    | 0.455 (0.051)    | -             |    14.30 | bsd, ckzao, diozera, mxa, Roz       |
|           15 |     2935 | 2024-02-29 | Yawara E-Sports                | W   | 0.759      | 0.143        | 0.005 (0.001)    | 0.361 (0.039)    | -             |    12.65 | bsd, ckzao, diozera, mxa, Roz       |
|           14 |     2973 | 2024-02-28 | Bombril 1001 Utilidades        | W   | 0.752      | -            | -                | -                | -             |    10.66 | bsd, ckzao, diozera, mxa, Roz       |
|           13 |     3012 | 2024-02-27 | Sharks Youngsters              | W   | 0.746      | -            | -                | -                | -             |    11.97 | bsd, ckzao, diozera, mxa, Roz       |
|           12 |     3915 | 2024-02-04 | Bombril 1001 Utilidades        | L   | 0.592      | -            | -                | -                | -             |   -10.31 | bsd, ckzao, diozera, Domingues, Roz |
|           11 |     3945 | 2024-02-03 | MIBR Academy                   | L   | 0.586      | -            | -                | -                | -             |    -7.89 | bsd, ckzao, diozera, Domingues, Roz |
|           10 |     4347 | 2024-01-25 | RED Canids                     | L   | 0.527      | -            | -                | -                | -             |    -3.31 | bnc, bsd, ckzao, diozera, Roz       |
|            9 |     4738 | 2024-01-17 | Arena Jogue Fácil Esports      | L   | 0.472      | -            | -                | -                | -             |    -7.97 | bsd, ckzao, diozera, Domingues, Roz |
|            8 |     4880 | 2024-01-13 | BESTIA                         | L   | 0.447      | -            | -                | -                | -             |    -4.92 | bsd, ckzao, DANVIET, diozera, Roz   |
|            7 |     5302 | 2023-12-20 | Sharks Youngsters              | L   | 0.286      | -            | -                | -                | -             |    -4.79 | bsd, ckzao, DANVIET, diozera, Roz   |
|            6 |     5311 | 2023-12-19 | TIMACETA                       | L   | 0.279      | -            | -                | -                | -             |    -5.05 | bsd, ckzao, DANVIET, diozera, Roz   |
|            5 |     5349 | 2023-12-17 | Sharks Youngsters              | W   | 0.266      | -            | -                | -                | -             |     3.87 | bsd, ckzao, DANVIET, diozera, Roz   |
|            4 |     5447 | 2023-12-16 | Hype E-Sports (Brazilian team) | W   | 0.259      | -            | -                | -                | -             |     2.65 | bsd, ckzao, DANVIET, diozera, Roz   |
|            3 |     5604 | 2023-12-14 | Myth e-Sports                  | W   | 0.246      | -            | -                | -                | -             |     3.06 | bsd, ckzao, DANVIET, diozera, Roz   |
|            2 |     5614 | 2023-12-14 | TIMACETA                       | L   | 0.245      | -            | -                | -                | -             |    -4.49 | bsd, ckzao, DANVIET, diozera, Roz   |
|            1 |     5635 | 2023-12-13 | Sharks Youngsters              | L   | 0.239      | -            | -                | -                | -             |    -4.10 | bsd, ckzao, DANVIET, diozera, Roz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,255.67)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.967 | $130.39        | $126.05         |
| 2024-03-24 |      0.919 | $500.00        | $459.56         |
| 2024-03-06 |      0.799 | $504.19        | $402.77         |
| 2024-02-04 |      0.593 | $301.88        | $179.02         |
| 2023-12-20 |      0.286 | $308.12        | $88.27          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
