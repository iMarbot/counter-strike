### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: gokushima, r3salt, shalfey, sstiNiX, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [203](../standings_global.md)<br />
Regional Rank: [137]( ../standings_europe.md)<br />
Final Rank Value:  722.1<br />
<br />
Final Rank Value (722.1) = Starting Rank Value (693.1) + Head To Head Adjustments (29.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.286[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.1
- 400 + ( ( 0.144 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 693.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     6747 | 2024-01-30 | Sashi Esport        | L   | 0.398      | -            | -                | -                | -         |    -1.62 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           17 |     6762 | 2024-01-30 | GUN5 Esports        | W   | 0.397      | 0.143        | -                | 0.143 (0.008)    | 0 (0.000) |     4.47 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           16 |     6787 | 2024-01-29 | ex-Preasy Esport    | W   | 0.392      | 0.143        | 0.052 (0.003)    | 0.381 (0.021)    | 0 (0.000) |     9.40 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           15 |     6811 | 2024-01-29 | TSM                 | W   | 0.392      | 0.143        | 0.011 (0.001)    | 0.146 (0.008)    | 0 (0.000) |     6.85 | gokushima, r3salt, shalfey, sstiNiX, tN1R |
|           14 |     7356 | 2024-01-20 | ex-Preasy Esport    | L   | 0.329      | -            | -                | -                | -         |    -2.40 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           13 |     7401 | 2024-01-19 | Aurora Gaming       | W   | 0.324      | 0.143        | 0.492 (0.023)    | 0.616 (0.029)    | 0 (0.000) |    10.09 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           12 |     7462 | 2024-01-18 | ex-sYnck            | L   | 0.318      | -            | -                | -                | -         |    -4.66 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           11 |     7478 | 2024-01-18 | HEROIC              | L   | 0.317      | -            | -                | -                | -         |    -0.03 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|           10 |     8895 | 2023-12-12 | ENCE                | L   | 0.068      | -            | -                | -                | -         |    -0.04 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|            9 |     8936 | 2023-12-11 | SAW                 | W   | 0.063      | 0.384        | 0.112 (0.003)    | 0.388 (0.009)    | 0 (0.000) |     1.92 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|            8 |     8957 | 2023-12-10 | 3DMAX               | L   | 0.058      | -            | -                | -                | -         |    -0.36 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            7 |     9019 | 2023-12-09 | SINNERS Esports     | W   | 0.051      | 0.500        | 0.011 (0.000)    | 0.560 (0.014)    | 0 (0.000) |     1.35 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            6 |     9101 | 2023-12-08 | Apeks               | W   | 0.044      | 0.500        | 0.085 (0.002)    | 0.345 (0.008)    | 0 (0.000) |     1.32 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            5 |     9165 | 2023-12-07 | Team Spirit Academy | W   | 0.037      | 0.500        | 0.004 (0.000)    | -                | 0 (0.000) |     0.65 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            4 |     9183 | 2023-12-07 | EYEBALLERS          | W   | 0.036      | 0.384        | 0.012 (0.000)    | 0.508 (0.007)    | 0 (0.000) |     0.88 | gokushima, kelieN, r3salt, shalfey, tN1R  |
|            3 |     9219 | 2023-12-06 | Team Space          | W   | 0.031      | 0.500        | 0.009 (0.000)    | 0.457 (0.007)    | 0 (0.000) |     0.69 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            2 |     9283 | 2023-12-05 | KOI                 | W   | 0.024      | 0.500        | 0.027 (0.000)    | 0.430 (0.005)    | -         |     0.63 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            1 |     9302 | 2023-12-05 | ex-Preasy Esport    | L   | 0.023      | -            | -                | -                | -         |    -0.17 | gokushima, kelieN, r3salt, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($767.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.078 | $1,000.00      | $77.52          |
| 2023-12-10 |      0.058 | $12,000.00     | $690.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
