Small tool to help me keep track of what I do day to day as I'm pretty forgetful.

Overview of commands

## Add

Add an entry.

    clog -a "Adding readme for clog gist"

## Search

Search for a keyword (case insensitive)

    $ clog -s readme
    Thu-23-Jul-2020.log:17:50 - Adding readme for clog gist

## List

Show dates there are logs for.

    $ clog -l
    Thu-23-Jul-2020.log
    Wed-22-Jul-2020.log

## Display

Display all entries for Date specified

    $ clog -d Wed-22-Jul-2020.log
    17:42 - corrected check_openmanage so it criticals for failed raid batteries
    20:28 - created storage pools and zfs puppet bits

## Display All

Show all entries, with date headers.

    $ clog -c
    Thu-23-Jul-2020
    16:55 - fixed check_hp issue with service segfaulting
    Wed-22-Jul-2020
    17:42 - corrected check_openmanage so it criticals for failed raid batteries
    20:28 - created storage pools and zfs puppet bits

## Display today

Show the contents of todays log file.

    $ clog -t
    16:55 - fixed check_hp issue with service segfaulting

## Display yesterday

Show the contents of yesterdays log file (if there is one!).

    $ clog -y
    No log for yesterday.
