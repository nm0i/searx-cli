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

