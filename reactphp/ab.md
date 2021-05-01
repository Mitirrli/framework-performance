$ ab -n10000 -c10 http://localhost:8080/

...

Concurrency Level:      10
Time taken for tests:   2.387 seconds
Complete requests:      10000
Failed requests:        0
Total transferred:      1350000 bytes
HTML transferred:       130000 bytes
Requests per second:    4188.99 [#/sec] (mean)
Time per request:       2.387 [ms] (mean)
Time per request:       0.239 [ms] (mean, across all concurrent requests)
Transfer rate:          552.26 [Kbytes/sec] received