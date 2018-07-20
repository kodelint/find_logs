# Find_logs

[`find_logs.pl`](https://github.com/kodelint/find_logs/blob/master/find_logs.pl) script will find the logs within the **time range** provided from `access.log`.

- This supports both [nginx](http://nginx.com/) and [apache](https://github.com/apache/httpd)

#### _Usage_

```:perl
perl find_log.pl -s=16:55:03 -e=16:55:04 access.log
```
