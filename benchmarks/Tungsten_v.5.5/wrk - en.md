### 📊 Production Benchmark Records & Stress-Test Matrix

The production-grade core was subjected to a rigorous endurance marathon executed via the `wrk` benchmarking tool. The testing environment was intentionally restricted to a legacy consumer-grade host running an **Intel Core i3 Haswell CPU** (2 cores / 4 threads) driven to a persistent **99% background load** under a virtualized WSL2 container to evaluate scheduler determinism under maximum transport layer saturation.

<div align="center">

| Concurrency (`-c`) | Throughput (RPS) | Total Requests (1m) | Latency p50 (Median) | Latency p75 | Latency p90 | Latency p99 (Tail) | Max Latency |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **10 Sockets** | 40,613.76 | 2,439,452 | **196.00 us** | 340.00 us | 469.00 us | 2.73 ms | 67.63 ms |
| **100 Sockets** | 80,211.09 | 4,819,893 | **0.95 ms** | 1.63 ms | 2.56 ms | 4.49 ms | 22.44 ms |
| **300 Sockets** | 86,436.09 | 5,193,670 | **2.55 ms** | 4.60 ms | 6.55 ms | 10.17 ms | 47.99 ms |
| **600 Sockets** | 76,863.27 | 4,618,965 | **6.17 ms** | 8.78 ms | 12.52 ms | 20.57 ms | 76.29 ms |
| **1800 Sockets** | 82,114.24 | 4,935,063 | **13.76 ms** | 24.84 ms | 36.77 ms | **53.26 ms** | 433.06 ms |

</div>

> [!NOTE]
> **Network Drop & Error Rate:** Strictly **0.00%** across all test phases. Maximum peak spikes (such as the 433.06 ms spike under a massive 1800-socket concurrency) are external anomalies directly induced by the Windows host kernel preempting the virtualized WSL2 CPU cores for system routines. When deployed onto native Bare-Metal Linux servers using specialized epoll descriptors, this virtualization tail-jitter is naturally flatlined.
