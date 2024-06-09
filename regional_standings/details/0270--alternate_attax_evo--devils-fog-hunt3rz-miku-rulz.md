### Roster Details<br />
Team Name: ALTERNATE aTTaX Evo<br />
Roster: devils, FoG, HuNt3rz, Miku, Rulz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [270](../standings_global.md)<br />
Regional Rank: [173]( ../standings_europe.md)<br />
Final Rank Value:  670.2<br />
<br />
Final Rank Value (670.2) = Starting Rank Value (700.8) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.104[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.8
- 400 + ( ( 0.148 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 700.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      476 | 2024-05-22 | eSports Cologne   | W   | 1.000      | 0.143        | -                | 0.101 (0.014)    | 0 (0.000) |     9.88 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           25 |      760 | 2024-05-19 | XPERION NXT       | L   | 1.000      | -            | -                | -                | -         |   -15.01 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           24 |      979 | 2024-05-17 | AKA HERO          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |    13.72 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           23 |     2012 | 2024-05-01 | mYinsanity        | L   | 1.000      | -            | -                | -                | -         |   -17.94 | DAVEN, klyrO, Rand, reezk, Xbenz     |
|           22 |     2208 | 2024-04-27 | TeamOrangeGaming  | L   | 0.984      | -            | -                | -                | -         |   -11.73 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           21 |     2249 | 2024-04-27 | Pandaric eSports  | W   | 0.982      | 0.143        | 0.001 (0.000)    | -                | 1 (0.982) |     8.13 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           20 |     2410 | 2024-04-24 | Team Solid        | W   | 0.964      | 0.143        | 0.002 (0.000)    | 0.091 (0.013)    | 0 (0.000) |    11.30 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           19 |     2537 | 2024-04-21 | Reveal            | W   | 0.944      | 0.143        | 0.000 (0.000)    | 0.055 (0.007)    | 0 (0.000) |    11.30 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           18 |     3151 | 2024-04-12 | OTHERSCANTBEAT    | L   | 0.882      | -            | -                | -                | -         |   -19.97 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           17 |     3574 | 2024-04-04 | Entropy Future    | W   | 0.831      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |    10.22 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           16 |     3974 | 2024-03-26 | Sissi State Punks | L   | 0.771      | -            | -                | -                | -         |   -12.42 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           15 |     3987 | 2024-03-26 | Wave Esports      | W   | 0.771      | 0.143        | 0.001 (0.000)    | 0.143 (0.016)    | 0 (0.000) |     9.32 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           14 |     4092 | 2024-03-23 | EP Genesis        | L   | 0.751      | -            | -                | -                | -         |   -16.28 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           13 |     4267 | 2024-03-19 | Metizport X       | L   | 0.724      | -            | -                | -                | -         |   -10.70 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           12 |     4976 | 2024-03-06 | TeamOrangeGaming  | L   | 0.638      | -            | -                | -                | -         |    -7.80 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           11 |     5005 | 2024-03-06 | Wave Esports      | W   | 0.637      | 0.143        | 0.001 (0.000)    | 0.143 (0.013)    | 0 (0.000) |     7.86 | devils, FoG, HuNt3rz, Miku, Rulz     |
|           10 |     5182 | 2024-03-04 | OTHERSCANTBEAT    | W   | 0.624      | -            | -                | -                | 0 (0.000) |     2.97 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            9 |     5208 | 2024-03-03 | SNOGARD Dragons   | W   | 0.618      | 0.143        | 0.004 (0.000)    | 0.137 (0.012)    | 0 (0.000) |    10.88 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            8 |     5449 | 2024-02-28 | TeamOrangeGaming  | L   | 0.591      | -            | -                | -                | -         |    -7.10 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            7 |     5570 | 2024-02-26 | Kappa Bar         | L   | 0.578      | -            | -                | -                | -         |   -13.37 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            6 |     5795 | 2024-02-22 | EVOPLAY           | W   | 0.551      | 0.143        | 0.000 (0.000)    | -                | -         |     6.67 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            5 |     5805 | 2024-02-22 | eSports Cologne   | W   | 0.551      | 0.143        | -                | 0.101 (0.008)    | -         |     4.21 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            4 |     5822 | 2024-02-22 | AVEZ              | L   | 0.550      | -            | -                | -                | -         |    -5.02 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            3 |     6038 | 2024-02-18 | ARROW             | L   | 0.525      | -            | -                | -                | -         |    -6.97 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            2 |     6922 | 2024-01-31 | EPIC DUDES        | W   | 0.404      | -            | -                | -                | -         |     2.86 | devils, FoG, HuNt3rz, Miku, Rulz     |
|            1 |     7462 | 2024-01-22 | Wave Esports      | W   | 0.344      | 0.143        | 0.001 (0.000)    | 0.143 (0.007)    | -         |     4.37 | Anomatronik, devils, FoG, Miku, Rulz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($679.23)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.984 | $535.13        | $526.44         |
| 2024-03-26 |      0.771 | $108.40        | $83.60          |
| 2024-03-06 |      0.638 | $108.45        | $69.20          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
