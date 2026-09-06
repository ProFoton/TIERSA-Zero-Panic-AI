# Changelog

All notable changes to the TIERSA™ core will be documented in this file.

## - 2026-


## - 2026-09-06
### Added
- Initial core release of TIERSA™ Dynamic Mitigator.
- High-performance web metrics ingestion endpoint (`/metrics`).
- Preventive telemetry structure for GPU, HBM, CPU, CoWoS, and VRM wear.

### Performance
- Confirmed stability over 10,000,000 requests loop.
- Achieved **9,379.82 RPS** under high concurrency load (C=222) on a 2-core setup.
- Reached peak burst throughput of **10,061.03 RPS** (C=150).
