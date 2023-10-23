# Searx2vt #

Command line (CLI) client for
[SearxNG](https://github.com/searxng/searxng)

## Requirements ## 

 * tcl 8.6+
 * tcllib
 * tcl-tls
 
## Installation ##

Install dependencies:

    sudo apt-get install tcl tcllib tcl-tls

Define SEARX_ENDPOINT variable:

    echo "export SEARX_ENDPOINT=https://example.com/search" >> ~/.profile

Then put searx somewhere in your $PATH

## Usage ##

    searx : searx [options] query ...
    options:
     -p value             Search page number. Defaults to the first page <1>
     -e value             Comma-separated list of engines to query. Defaults to instance engines <>
     -w value             Wrap column for query content <72>
     --                   Forcibly stop option processing
     -help                Print this message
     -?                   Print this message
    
## Screenshots ##

    > searx wikipedia
    Wikipedia
    Wikipedia is a free online encyclopedia, created and edited by
    volunteers around the world and hosted by the Wikimedia Foundation.The
    English rock band the Kinks staged their first concert tou…The United
    Kingdom of Great Britain and Northern Ireland, co…Preceded by: Ken
    Livingstone: Succeeded by: Sadiq Khan: S…Thor: Love and Thunder is a
    2022 American superhero film b…Stranger Things is an American science
    fiction horror drama t…Penny Mordaunt - Wikipedia
    https://www.wikipedia.org/

