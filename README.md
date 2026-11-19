### Open rail data tools for Great Britain

Small Python packages for the public data Britain's railway publishes:
timetables, fares, passenger counts, punctuality, the track network and
station usage. Each one reads a single source into plain tables, and
they are built to work together.

| Package | Reads | |
|---|---|---|
| [cif-timetable](https://github.com/rosedillon/cif-timetable) | Network Rail's CIF schedule feed | calling points, and trains per route |
| [rsp-fares-feed](https://github.com/rosedillon/rsp-fares-feed) | the RSP fares feed | every fare between two stations, cluster fares included |
| [rail-loading](https://github.com/rosedillon/rail-loading) | operators' passenger loading data (Rail Data Marketplace) | nine operators' counts in one schema |
| [hsp-client](https://github.com/rosedillon/hsp-client) | the Historic Service Performance API | how late trains actually ran |
| [orr-station-usage](https://github.com/rosedillon/orr-station-usage) | ORR tables 1410 and 1415 | entries, exits and interchanges by station and year |
| [track-distance](https://github.com/rosedillon/track-distance) | Network Rail's track model | distance along the rails |
| [bplan-geography](https://github.com/rosedillon/bplan-geography) | Network Rail's BPLAN extract | minimum running times between timing points |
| [tag-databook](https://github.com/rosedillon/tag-databook) | the DfT TAG Data Book | appraisal values without opening Excel |
| [rail-codes](https://github.com/rosedillon/rail-codes) | Network Rail's CORPUS | TIPLOC, CRS, NLC and STANOX lookups |

All are on PyPI (`pip install rail-codes`, and so on) and GPL-3.0.

They were split out of [ORTLA](https://github.com/rosedillon/ORTLA), a
model of passenger demand on individual trains built from open data.
