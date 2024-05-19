### Roster Details<br />
Team Name: GUN5 Esports<br />
Roster: FinigaN, lov1kus, supra, xiELO, znxxX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [244](../standings_global.md)<br />
Regional Rank: [156]( ../standings_europe.md)<br />
Final Rank Value:  670.6<br />
<br />
Final Rank Value (670.6) = Starting Rank Value (645.9) + Head To Head Adjustments (24.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.246[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.124<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.9
- 400 + ( ( 0.124 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 645.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     4697 | 2024-01-17 | Sprout                   | L   | 0.473      | -            | -                | -                | -         |   -10.83 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           16 |     4711 | 2024-01-17 | VaselineWorms            | W   | 0.473      | 0.143        | 0.001 (0.000)    | 0.164 (0.011)    | 0 (0.000) |     7.34 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           15 |     4730 | 2024-01-17 | Ex-KRC Genk Esports      | W   | 0.472      | 0.143        | 0.008 (0.001)    | 0.181 (0.012)    | 0 (0.000) |    10.25 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           14 |     4789 | 2024-01-16 | Endpoint                 | L   | 0.466      | -            | -                | -                | -         |    -3.95 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           13 |     4814 | 2024-01-16 | 777 Esports              | W   | 0.465      | 0.143        | 0.032 (0.002)    | 0.550 (0.037)    | 0 (0.000) |     9.11 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           12 |     5044 | 2024-01-10 | HEROIC                   | L   | 0.426      | -            | -                | -                | -         |    -0.04 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           11 |     5061 | 2024-01-10 | BLESSED (Ukrainian team) | W   | 0.426      | 0.143        | 0.018 (0.001)    | 0.781 (0.047)    | 0 (0.000) |     9.84 | FinigaN, lov1kus, supra, xiELO, znxxX     |
|           10 |     5314 | 2023-12-19 | Pera Esports             | L   | 0.278      | -            | -                | -                | -         |    -1.55 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            9 |     5316 | 2023-12-19 | Metizport                | L   | 0.277      | -            | -                | -                | -         |    -1.01 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            8 |     5320 | 2023-12-19 | Soda Gaming              | W   | 0.277      | 0.333        | 0.009 (0.001)    | 0.182 (0.017)    | 0 (0.000) |     5.80 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            7 |     5453 | 2023-12-16 | EYEBALLERS               | L   | 0.259      | -            | -                | -                | -         |    -1.24 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            6 |     6710 | 2023-11-18 | Team Spirit Academy      | L   | 0.072      | -            | -                | -                | -         |    -0.67 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            5 |     7017 | 2023-11-12 | Entropiq                 | W   | 0.030      | 0.143        | 0.001 (0.000)    | 0.436 (0.002)    | 0 (0.000) |     0.65 | FinigaN, L1GH7n1nG, lov1kus, supra, xiELO |
|            4 |     7073 | 2023-11-11 | GenOne                   | W   | 0.023      | 0.143        | 0.000 (0.000)    | 0.035 (0.000)    | 0 (0.000) |     0.34 | FinigaN, L1GH7n1nG, lov1kus, supra, xiELO |
|            3 |     7118 | 2023-11-09 | Insilio                  | W   | 0.013      | 0.143        | 0.020 (0.000)    | 0.875 (0.002)    | 0 (0.000) |     0.34 | FinigaN, L1GH7n1nG, lov1kus, supra, xiELO |
|            2 |     7120 | 2023-11-09 | Nemiga Gaming            | W   | 0.013      | 0.143        | 0.680 (0.001)    | 0.910 (0.002)    | 0 (0.000) |     0.39 | FinigaN, L1GH7n1nG, lov1kus, supra, xiELO |
|            1 |     7128 | 2023-11-09 | Verdant                  | L   | 0.012      | -            | -                | -                | -         |    -0.04 | FinigaN, L1GH7n1nG, lov1kus, supra, xiELO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($137.21)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
