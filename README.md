# WatchGuardFireware

ASIM parsers to be used with Fireware devices.

- ASimNetworkSessionWatchGuardFireware: parse all the events (allowed and denied).
- ASimNetworkSessionWatchGuardFireware - Denied Events: parse only the denied events.

If you have deployed a Firecluster configuration (two or more devices in a failover structure), it will require a minor change to parse the "firecluster member" reporting the log (in the works).

Also, a version that will accept parameters is in the works.

It can be added to Microsoft Sentinel by using the following ASIM empty custom unifying parsers:
https://github.com/Azure/Azure-Sentinel/tree/master/ASIM/deploy/EmptyCustomUnifyingParsers
