### Roster Details<br />
Team Name: Sharks Esports<br />
Roster: doc, drg, rdnzao, supLexN1, togs<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [206](../standings_global.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
Final Rank Value:  718.5<br />
<br />
Final Rank Value (718.5) = Starting Rank Value (714.7) + Head To Head Adjustments (3.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 714.7
- 400 + ( ( 0.155 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 714.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2285 | 2024-04-26 | TYLOO         | L   | 0.977      | -            | -                | -                | -         |    -7.54 | doc, drg, rdnzao, supLexN1, togs |
|           11 |     2356 | 2024-04-25 | M80           | L   | 0.970      | -            | -                | -                | -         |    -1.38 | doc, drg, rdnzao, supLexN1, togs |
|           10 |     2471 | 2024-04-23 | Team Vitality | L   | 0.956      | -            | -                | -                | -         |    -0.07 | doc, drg, rdnzao, supLexN1, togs |
|            9 |     2954 | 2024-04-16 | w7m esports   | L   | 0.912      | -            | -                | -                | -         |   -10.89 | doc, drg, rdnzao, supLexN1, togs |
|            8 |     3135 | 2024-04-12 | Galorys       | L   | 0.885      | -            | -                | -                | -         |    -9.84 | doc, drg, rdnzao, supLexN1, togs |
|            7 |     3172 | 2024-04-11 | paiN Gaming   | L   | 0.878      | -            | -                | -                | -         |    -0.28 | doc, drg, rdnzao, supLexN1, togs |
|            6 |     3361 | 2024-04-08 | paiN Gaming   | L   | 0.857      | -            | -                | -                | -         |    -0.27 | doc, drg, rdnzao, supLexN1, togs |
|            5 |     3425 | 2024-04-07 | BESTIA        | W   | 0.849      | 0.435        | 0.026 (0.010)    | 0.500 (0.184)    | 0 (0.000) |    19.89 | doc, drg, rdnzao, supLexN1, togs |
|            4 |     3452 | 2024-04-06 | ODDIK         | W   | 0.844      | 0.143        | 0.017 (0.002)    | 0.494 (0.060)    | 0 (0.000) |    20.30 | doc, drg, rdnzao, supLexN1, togs |
|            3 |     3529 | 2024-04-05 | paiN Gaming   | L   | 0.837      | -            | -                | -                | -         |    -0.19 | doc, drg, rdnzao, supLexN1, togs |
|            2 |     3672 | 2024-04-02 | BESTIA        | L   | 0.819      | -            | -                | -                | -         |    -5.67 | doc, drg, rdnzao, supLexN1, togs |
|            1 |     3677 | 2024-04-02 | MIBR          | L   | 0.818      | -            | -                | -                | -         |    -0.27 | doc, drg, rdnzao, supLexN1, togs |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,500.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
