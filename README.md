# sd
A CLI (command-line interface) to SpanishDict.com, a popular Spanish-English dictionary.

## Description:
Did you know that SpanishDict downloads over 200KB for every word lookup?  What bloat! `sd` is a python script that reads those 200KB, parses out the junk, and nicely formats the most useful 90% of that content for your command line viewing pleasure.

## Usage:
Translate a word with `sd <some word>`, or conjugate a verb with `sd conj <some verb>`.

Check out the output of `sd cat`:

![example](https://raw.githubusercontent.com/rexroni/sd/master/example.png)

Also check out the output of `sd conj tener` (colorized version of nick96's code):

![example2](https://raw.githubusercontent.com/rexroni/sd/master/example2.png)

## Dependencies
`sd` is a python 3 script built on "BeautifulSoup 4" and "Tabulate".  Dependencies can be installed by running `pip3 install beatifulsoup4` and `pip3 install tabulate` (you might need root priviledges on your system).

## Credit
The conjugation functionality was shamelessly stolen from github user nick96's "conjugate" project.

## Installation:
Installation is as simple as putting the `sd` script somewhere on your path.  On linux, `/usr/local/bin` would be a stanard place.
