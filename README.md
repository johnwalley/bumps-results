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

A format devised by Tim Granger. See the [readme](https://github.com/mcshane-fire/bumps/blob/master/readme.txt) in his [bumps](https://github.com/mcshane-fire/bumps) repository for the original description.

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

The file has three sections:

1. Metadata about the racing
1. The starting order for each division
1. The results from racing

### Metadata

A set of `<keyword>,<value>` pairs, one per line. Only `Days` is optional and defaults to 4 if omitted.

| Keyword | Value                                          |
| ------- | ---------------------------------------------- |
| Set     | Name of the series of bumps racing             |
| Short   | Short version of the name above                |
| Gender  | `Men` or `Women`                               |
| Year    | Year of racing                                 |
| Days    | Number of days of racing (optional, default 4) |

### Divisions

One line per division, starting with `Division,` followed by a comma separated list of crew names.

Crew names can be written out in full or given as short codes. A short code is the club [abbreviation](abbreviations.txt) followed by an optional number (if omitted it defaults to 1). Different sets of abbreviations apply depending on the `Set` name in the metadata.

Crews from the same club must appear in the correct numerical order. A crew which does not follow this ordering can have a `*` after its number to suppress the numbering error.

### Results

This section starts with the keyword `Results`, followed by a set of result codes separated by commas or line breaks. Anything starting with a `#` character is treated as a comment and discarded, as is any unrecognised code.

Results are given for each day in order. Within a day, divisions are given in reverse order, the lowest division first. Within a division, results start with the bottom crew and proceed towards the top. For every division apart from the bottom division, the first result code is for the sandwich crew.

If there are not enough results for all days of racing then all subsequent divisions are assumed not to have been raced.

| Code       | Explanation                                                                                                                      |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------- |
| `r`        | Crew remained level for the day, likely rowing over                                                                              |
| `u`        | Crew bumped up one place, and the crew above went down one place                                                                 |
| `o<num>`   | Crew overbumped up `<num>` places, exchanging positions with the crew starting `<num>` places above                              |
| `t`        | Skips over all crews remaining in the current division, e.g. to indicate the division did not race                               |
| `x`        | Crew withdraws from racing this and following days. Division size is reduced by one on following days                            |
| `e<num>`   | Crew goes up `<num>` places. `<num>` can be negative for a crew going down                                                        |
| `v<num>`   | As `e<num>`, but the crew is shown with a lighter line to indicate they did not race that day                                    |
| `w<num>`   | The next `<num>` crews all went up by one, and the next crew went down `<num>` places                                            |
| `d(1.2.3)` | The division sizes change for the next day. Inside the parentheses is a dot separated list of division sizes                     |
| `p`        | The next crew with an `e` or `v` code receives a penalty bump after the `e`/`v` code has been applied                            |

For codes `u`, `o` and `w`, which give the results for multiple crews, no codes are included for the other crews involved.

For ease of reading, codes from each division are typically separated by a space, and results from each day are on a separate line.

## Acknowledgements

Results based on charts produced by:

* [Tim Granger's Bumps Charts](https://github.com/mcshane-fire/bumps)
* [Cambridgeshire Rowing Association](http://www.crarowing.co.uk/town-bumps/about-the-cra-town-bumps/results/historic-bumps-results)
* [History of the Cantabrigian Rowing Club 1950-2010](http://www.cantabsrowing.org.uk/history-of-the-cantabrigian-rowing-club-1950-2010/)
* [Oxford University Rowing Clubs](http://www.ourcs.co.uk/)
* [Cambridge University Combined Boat Clubs](https://www.cucbc.org/)
* [The Bumps](http://www.thebumps.co.uk/)
* [Oxford Bumps Charts](http://eodg.atm.ox.ac.uk/user/dudhia/rowing/bumps/)
