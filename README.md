# Bumps Results

Cambridge and Oxford Bumps results.

## Format

Results are stored in two formats:

1. [ad_format](#ad_format)
1. [tg_format](#tg_format)

The ad_format results are considered canonical and tg_format results are derived from them. Additionally, Torpids results are only present in ad_format due to limitations of the tg_format.

## ad_format

A format devised by Anu Dudhia. See his [Oxford Bumps Charts](http://eodg.atm.ox.ac.uk/user/dudhia/rowing/bumps/) page for more details.

Here is an example

    EIGHTS 2014
     4  7  92   = NDay, NDiv, NCrew
     13  Men's Div I (6.45)
    Pembroke                    0  -1   0   0
    Christ Church              -1   0   0   0
    Oriel                       1   1   0   0
    University                  0  -1  -1   0
    Wolfson                    -1  -1   0   0
    Magdalen                    1   1   0   0
    St Catherine's             -1   0  -1   0
    Trinity                     1   1   1   0
    Balliol                     0   0   1   0
    Worcester                   0   0   0  -1
    Hertford                   -1  -1  -1   0
    S.E.H.                      1   0  -1   0
    Keble                       0   1   1   1
     13  Men's Div II (5.45)
    Wadham                      0   0   1   0
    Lincoln                     0   0   0  -1
    St John's                   0   0  -1   0
    St Anne's                  -1   0  -1  -1
    New College                 1   0   1   1
    Brasenose                  -1   1   1   0
    L.M.H.                      1  -1   0   1
    Exeter                     -1  -1  -1  -1
    Mansfield                   1   0   0   0
    Jesus                       0   1   0  -1
    Christ Church II            0  -1  -1  -1
    Somerville                 -1  -1  -1  -1
    St Peter's                  1   1   1   1
     13  Men's Div III (4.45)
    Pembroke II                -1   0   1   1
    Oriel II                    1   1   1   1
    Corpus Christi              0   0   0   1
    Queen's                     0   0   0   0
    Merton                      0   0  -1   0
    St Hugh's                   0   0   1   0
    New College II              0   0   0   0
    S.E.H. II                   0  -1  -1  -1
    Linacre                     0   1   0  -1
    University II               0  -1  -1   0
    St Antony's                -1  -1  -1  -1
    Magdalen II                 1   1   1   1
    Trinity II                 -1   0   1   0
     13  Men's Div IV (3.40)
    Wadham II                   1   1   1   1
    Balliol II                  0   0   0   1
    St Catherine's II          -1  -1  -1  -1
    Worcester II                1   0  -1  -1
    Keble II                    0   1   1   0
    Wolfson II                  0  -1  -1  -1
    Merton II                  -1  -1  -1  -1
    Jesus II                    1   1   1   1
    Brasenose II                0   1   1   1
    Lincoln II                 -1   0  -1  -1
    Green Templeton             1   0   1   1
    Hertford II                 0  -1   0   1
    St Peter's II              -1  -1  -1   0
     13  Men's Div V (2.20)
    Osler House                 1   1   1   1
    St John's II                0   1   0   0
    St Hilda's                  0   0   1   0
    Christ Church III           0  -1   1  -1
    Pembroke III               -1  -1  -1  -1
    Regent's Park               1   1  -1   1
    St Anne's II                0   1   0  -1
    Jesus III                   0   0   1   1
    Wadham III                  0   0  -1  -1
    Queen's II                  0  -1  -1  -1
    St Benet's Hall            -1  -1  -1   0
    Wolfson III                 1   1   1   1
    Somerville II               0   1   1   1
     13  Men's Div VI (1.15)*
    L.M.H. II                   0   0  -1  -1
    Trinity III                 0  -1  -1  -1
    University III             -1   0   1   1
    Green Templeton II          1   1   2   1
    St Hugh's II               -1   0  -1  -1
    Oriel III                   1   0   0   1
    New College III             0  -1  -1  -1
    St Hilda's II              -1  -3  -1  -1
    Wolfson IV                  1   1   1   0
    Brasenose III               0  -1   0  -1
    St Hugh's III               0   1   0   1
    Magdalen III               -1  -1  -1   2
    S.E.H. III                  1   3   1   1
     14  Men's Div VII (12.00)*
    St John's III              -1   0   1  -1
    Pembroke IV                 1   1   1   1
    Magdalen IV                -1  -1  -1   0
    Corpus Christi II           1   0  -1   0
    Hertford III               -1  -1   0   0
    Mansfield II                1   1   1   0
    Keble III                  -1  -1  -1   0
    Linacre II                  1   1   1   0
    University IV              -1  -1  -1   0
    Trinity IV                  1   1   0   0
    St Anne's III               0   1   1   0
    Keble IV                   -1   0   0   0
    Merton III                  1   0   1   0
    Somerville III              0   0   0   0

The performance of a single crew is represented on a single line. The number of places it moves each day is represented by a sequence of numbers. Positive if the crew has moved up, and negative if the crew has moved down.

A value of -99 means the crew did not race that day and has dropped out of the event.

## tg_format

A format devised by Tim Granger. See his [Bumps Chart Generation](http://www.mcshane.org/bumps/create.html) page for the original description.

Here is an example

    Set,Town Bumps
    Short,Town Bumps
    Gender,Women
    Year,2016

    Division,City 1,Cantabs 1,99 1,City 2,Rob Roy 1,X-Press 1,Cantabs 2,St Neots 1,City 3,Chesterton 1,Champs 1,City 4,Camb Veterans 1,Cantabs 3,99 2,Champs 2,Rob Roy 2
    Division,99 3,St Radegund 1,City 5,City 6,Champs 3,Champs 4,Cantabs 4,Champs 5,City 7,Isle of Ely 1,Rob Roy 3,99 4,St Neots 2,Cantabs 5,X-Press 2,Cantabs 6,Champs 6
    Division,Rob Roy 4,Chesterton 2,City 8,Cantabs 7,St Radegund 2,Chesterton 3,99 5,Cantabs 8,99 6,Champs 7,Cantabs 9,X-Press 3,Cantabs 10,X-Press 4,Cantabs 11

    Results
    uruurrrurrr ururruuururr urrrururrurrrr
    rruurrrrrrru rrrrurruururu ruruurrruurrr
    rrruurruurr rruruuururur uruuuruuurr
    rrrruurrurrr rruuuuruuru rruuuurrrrrrrr

The first four lines describe the event. Then comes the starting order for each division. Finally we have the results for each day.

Results start with the bottom crew in each division (the sandwich crew for all but the lowest division).

| Entry | Explanation            |
| ----- | ---------------------- |
| r     | rowed over             |
| u     | bumped up one place    |
| o3    | overbumped up 3 places |
| e-2   | moved down 2 places    |

A crew which has been (over)bumped down does not need an entry as it is implied by the entry for the crew which bumped up.

Crews are typically represented by an [abbreviation](abbreviations.txt).

## Acknowledgements

Results based on charts produced by:

* [Bumps Charts Archive](http://www.mcshane.org/bumps/)
* [Cambridgeshire Rowing Association](http://www.crarowing.co.uk/town-bumps/about-the-cra-town-bumps/results/historic-bumps-results)
* [History of the Cantabrigian Rowing Club 1950-2010](http://www.cantabsrowing.org.uk/history-of-the-cantabrigian-rowing-club-1950-2010/)
* [Oxford University Rowing Clubs](http://www.ourcs.co.uk/)
* [Cambridge University Combined Boat Clubs](https://www.cucbc.org/)
* [The Bumps](http://www.thebumps.co.uk/)
* [Oxford Bumps Charts](http://eodg.atm.ox.ac.uk/user/dudhia/rowing/bumps/)
