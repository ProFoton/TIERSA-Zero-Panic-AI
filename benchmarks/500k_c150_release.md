## 🚀 Post-Optimization Production Test: 500,000 Requests (150 Concurrency)

*   **Throughput:** 🔥 **9,896.11 #/sec** (mean) — *Up from 8,427.58 RPS before compiler profiles configuration (+17.4%)*
*   **Total Time Taken:** 50.525 seconds
*   **Failed Requests:** **0** (Flawless 100% stability)

### Optimization Impact
*   **Time per request (across concurrent):** **0.101 ms** (mean)
*   **Transfer Rate:** 4,841.75 Kbytes/sec received
*   **Core Efficiency:** Max internal processing latency capped at **27 ms** under continuous stress.

### Connection Times (ms)
```text
              min  mean[+/-sd] median   max
Connect:        0    7   2.8      7    1012
Processing:     0    8   2.6      8      27
Waiting:        0    6   2.3      6      19
Total:          1   15   2.7     16    1023
```

### Latency Distribution
*   **50%** ≤ 16 ms
*   **90%** ≤ 17 ms
*   **95%** ≤ 18 ms
*   **99%** ≤ 20 ms
*   **100%** ≤ 1023 ms (network link lag, internal core processing max was 27 ms)
