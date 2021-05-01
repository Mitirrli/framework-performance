$ ab -n10000 -c10 http://localhost:8080/

...

Concurrency Level:      10
Time taken for tests:   35.966 seconds
Complete requests:      10000
Failed requests:        0
Total transferred:      1720000 bytes
HTML transferred:       110000 bytes
Requests per second:    278.04 [#/sec] (mean)
Time per request:       35.966 [ms] (mean)
Time per request:       3.597 [ms] (mean, across all concurrent requests)
Transfer rate:          46.70 [Kbytes/sec] received