# MLB.TV Time Zone Converter for Greasemonkey, Tampermonkey, etc
Script to convert MLB TV times to other time zones

Converts to your local computer time zone by default, but can be overwritten to any other time zone you like by replacing the variable at the top of the script with the relevant TZ database name (see link below.)

As far as I can figure it should automatically account for daylight savings time, but I've never messed with Date/Time functions in JS before, so YMMV.

https://en.wikipedia.org/wiki/List_of_tz_database_time_zones

Tested with Tampermonkey in Chrome, Firefox, and Edge Chromium
