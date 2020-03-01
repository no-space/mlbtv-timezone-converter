# MLB.TV Time Zone Converter for Greasemonkey, Tampermonkey, etc
A script to convert MLB.TV times to other time zones

[Greasy Fork Link](https://greasyfork.org/en/scripts/397120-mlb-tv-time-zone-converter)

Converts to your local computer time zone by default, but can be overwritten to any other time zone you like by replacing the variable at the top of the script with the relevant TZ database name ([link to Wiki page](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones
).) Script runs when you click your mouse on the MLB.TV Live Stream Schedule/Media Center page.

As far as I can figure it should automatically account for daylight savings time, but I've never messed with Date/Time functions in JS before, so YMMV.


Tested with Tampermonkey in Chrome, Firefox, and Edge Chromium

![Screenshot](https://preview.redd.it/jhysnk3x30k41.png?width=914&format=png&auto=webp&s=2a7aad439386d0876b971c3bea0eb8813cb48355)
