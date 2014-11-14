# karotz-kartozvmsniffer

## What is this all about ?

This is a simple set of script to log all the activities of /usr/karotz/bin/karotzVM binary for Karotz (OpenKarotz) project

## How does it work ?

Connects to stdin / stdout and log everything. On thing, take care: all the files must have "x" (executable) flag.

It also loggs the signals sent to the script (because, it seems that another process communicates with it)

