# check_process_freshness
Check process start time

```perl
/usr/lib/nagios/plugins/check_process_freshness -h
check_process_freshness 1.0.0

This nagios plugin is free software, and comes with ABSOLUTELY NO WARRANTY. 
It may be used, redistributed and/or modified under the terms of the GNU 
General Public Licence (see http://www.fsf.org/licensing/licenses/gpl.txt).

Usage: check_process_freshness [ -v|--verbose ]
[ -c|--critical=<threshold> ] [ -w|--warning=<threshold> ]
[ -m|--message=<message> ] [ -s|--shortest] -p|--process <process_regex>

See https://www.monitoring-plugins.org/doc/guidelines.html#THRESHOLDFORMAT for thresholds

 -?, --usage
   Print usage information
 -h, --help
   Print detailed help screen
 -V, --version
   Print version information
 -w, --warning=SECONDS
 -c, --critical=SECONDS
 -m, --message=STRING
 -p, --process=STRING
 -s, --shortest, use shortest start time
 -v, --verbose
   Show details for command-line debugging (can repeat up to 3 times)
```
