# Searx-cli #

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
     -p value             Search page number <1>
     -e value             Comma-separated list of engines to query <>
     -c value             Wrap column for description text <72>
     -nd                  Do not display descriptions
     -n value             Limit number of displayed results <50>
     --                   Forcibly stop option processing
     -help                Print this message
     -?                   Print this message
        
## Screenshots ##

    ~> searx -n 2 wikipedia
    
    1: Wikipedia
    Wikipedia is a free online encyclopedia, created and edited by
    volunteers around the world and hosted by the Wikimedia Foundation.The
    English rock band the Kinks staged their first concert tou…The United
    Kingdom of Great Britain and Northern Ireland, co…Preceded by: Ken
    Livingstone: Succeeded by: Sadiq Khan: S…Thor: Love and Thunder is a
    2022 American superhero film b…Stranger Things is an American science
    fiction horror drama t…Penny Mordaunt - Wikipedia
    https://www.wikipedia.org/
    
    2: Wikipedia
    Wikipedia is a free-content online encyclopedia written and maintained
    by a community of volunteers, collectively known as Wikipedians, through
    open collaboration and using a wiki-based editing system called
    MediaWiki. Wikipedia is the largest and most-read reference work in
    history, and has consistently been one of the 10 most popular websites.
    Founded by Jimmy Wales and Larry Sanger on …
    https://en.wikipedia.org/wiki/Wikipedia

.
    
    ~> searx -nd -n 5 github markdown syntax
    
    1: Getting started with writing and formatting on GitHub
    https://docs.github.com/articles/markdown-basics
    
    2: Basic Syntax | Markdown Guide
    https://www.markdownguide.org/basic-syntax/
    
    3: Basic writing and formatting syntax - GitHub Docs
    https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax?ref=robert-mizen.ghost.io
    
    4: Using Markdown and Liquid in GitHub Docs
    https://docs.github.com/en/contributing/writing-for-github-docs/using-markdown-and-liquid-in-github-docs
    
    5: Learn Markdown Online | How to use markdown tutorial - GitHub …
    https://learn-markdown.github.io/
    


