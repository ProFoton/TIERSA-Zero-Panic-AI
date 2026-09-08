  12 threads and 400 connections
^C  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency     8.84ms    4.51ms  59.29ms   71.15%
    Req/Sec     3.79k   523.83    24.01k    91.41%
  Latency Distribution
     50%    8.18ms
     75%   11.36ms
     90%   14.96ms
     99%   21.40ms
  1446275 requests in 32.05s, 2.70GB read
Requests/sec:  45119.04
Transfer/sec:     86.14MB
dantes@DESKTOP-RL46525:~$  wrk -t10 -c500 -d60s --latency http://172.19.208.
225:8000/metrics
Running 1m test @ http://172.19.208.225:8000/metrics
  10 threads and 500 connections
  Thread Stats   Avg      Stdev     Max   +/- Stdev
    Latency    11.40ms    6.26ms 103.62ms   72.67%
    Req/Sec     4.48k   617.04    12.05k    81.84%
  Latency Distribution
     50%   10.40ms
     75%   14.99ms
     90%   19.45ms
     99%   29.33ms
  2677778 requests in 1.00m, 4.99GB read
Requests/sec:  44563.91
Transfer/sec:     85.08MB
