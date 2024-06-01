### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: delle, Fabbelit0, simpan, TIM, tvs<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [401](../standings_global.md)<br />
Regional Rank: [240]( ../standings_europe.md)<br />
Final Rank Value:  549.5<br />
<br />
Final Rank Value (549.5) = Starting Rank Value (525.7) + Head To Head Adjustments (23.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.7
- 400 + ( ( 0.062 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 525.7


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
|           13 |      463 | 2024-05-22 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |    -3.33 | delle, Fabbelit0, simpan, TIM, tvs   |
|           12 |      482 | 2024-05-22 | FLuffy Gangsters  | L   | 1.000      | -            | -                | -                | -         |   -10.52 | delle, Fabbelit0, simpan, TIM, tvs   |
|           11 |     1256 | 2024-05-14 | NOM Esports       | L   | 1.000      | -            | -                | -                | -         |   -10.34 | delle, Fabbelit0, simpan, TIM, tvs   |
|           10 |     1708 | 2024-05-06 | Copenhagen Wolves | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.309 (0.115)    | 0 (0.000) |    18.14 | delle, Fabbelit0, simpan, TIM, tvs   |
|            9 |     1765 | 2024-05-05 | LODIS             | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |    17.26 | delle, Fabbelit0, simpan, TIM, tvs   |
|            8 |     1970 | 2024-05-01 | ADEPTS            | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | 0 (0.000) |    24.75 | delle, Fabbelit0, simpan, TIM, tvs   |
|            7 |     2243 | 2024-04-26 | TopTab Club       | W   | 0.978      | 0.372        | 0.000 (0.000)    | 0.135 (0.049)    | 0 (0.000) |    16.54 | delle, Fabbelit0, simpan, TIM, tvs   |
|            6 |     2439 | 2024-04-22 | Verdant           | L   | 0.951      | -            | -                | -                | -         |    -3.24 | delle, Fabbelit0, simpan, TIM, tvs   |
|            5 |     2938 | 2024-04-15 | EXO Clan          | L   | 0.904      | -            | -                | -                | -         |    -1.61 | delle, Fabbelit0, simpan, TIM, tvs   |
|            4 |     3170 | 2024-04-10 | plusW             | L   | 0.871      | -            | -                | -                | -         |   -11.41 | delle, dezt, phzy, TIM, tvs          |
|            3 |     3283 | 2024-04-08 | VP.Prodigy        | L   | 0.857      | -            | -                | -                | -         |    -3.74 | delle, Evarizta, Fabbelit0, TIM, tvs |
|            2 |     4726 | 2024-03-09 | Alliance          | L   | 0.656      | -            | -                | -                | -         |    -2.77 | delle, dezt, TIM, tvs, upE           |
|            1 |     6534 | 2024-02-03 | Sashi Esport      | L   | 0.424      | -            | -                | -                | -         |    -5.86 | delle, dZ, simpan, treckiz, tvs      |

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
