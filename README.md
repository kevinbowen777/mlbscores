# mlbscores

mlbscores is a Python script that reads publicly available JSON data from mlb.com and prints out up-to-date scores, reduced box scores, or league standings.

## Usage

      usage: mlbscores [-h] [-b] [-f] [-s] [-y | -t | -tt] [teams [teams ...]]

      MLB scores utility

      positional arguments:

        teams

                       Show explicit teams only specified by space separated list of
                       case insensitive abbreviated names e.g. chc coL SF

      optional arguments:

            -h, --help  show this help message and exit
            -b          Show boxscore output for best games
            -c          Choose team to feature in schedule and save to file
            -f          Show full output for all games
            -s          Show current standings
            -y          Show for yesterday
            -t          Show for tomorrow
            -tt         Show for two days from now

## Customization

### Default team

By default, the team displayed at the top of the schedule is
set to the Seattle Mariners (SEA).

This can be changed by modifying line 27 of the script.

For example, to change from Seattle Mariners (SEA) to Chicago Cubs (CHC),
modify the line from:

    bestteams = ["SEA"]

      to

    bestteams = ["CHC"]

### Schedule/Score roll-over

By default, the daily and scored rollover at 6 AM local time.

This can be changed by modifying line 30 of the script.

For example, to change from 6AM to 1AM modify the line from:

    daytime_rollover = 6

      to

    daytime_rollover = 1
