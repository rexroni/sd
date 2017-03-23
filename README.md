# sd
A CLI (command-line interface) to SpanishDict.com

## Description:
Did you know that SpanishDict downloads over 200KB for every word lookup?  What bloat! `sd` is a python script that reads those 200KB, parses out the junk, and nicely formats the most useful 90% of that content for your command line viewing pleasure.

## Dependencies
`sd` is a python 3 script built on BeautifulSoup 4.  BeautifulSoup 4 can be installed with `pip3 install beatifulsoup4`.  Check out the output of `sd cat`:

![example](https://raw.githubusercontent.com/rexroni/sd/master/example.png)

