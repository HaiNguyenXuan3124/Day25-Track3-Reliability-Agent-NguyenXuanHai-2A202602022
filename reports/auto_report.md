# Day 10 Reliability Final Report

## Metrics Summary

| Metric | Value |
|---|---:|
| total_requests | 300 |
| availability | 0.9967 |
| error_rate | 0.0033 |
| latency_p50_ms | 280.24 |
| latency_p95_ms | 316.49 |
| latency_p99_ms | 319.34 |
| fallback_success_rate | 0.9867 |
| cache_hit_rate | 0.6433 |
| circuit_open_count | 8 |
| recovery_time_ms | None |
| estimated_cost | 0.041716 |
| estimated_cost_saved | 0.193 |

## Chaos Scenarios

| Scenario | Status |
|---|---|
| primary_timeout_100 | pass |
| primary_flaky_50 | pass |
| all_healthy | pass |

## Analysis TODO(student)

Explain what failed, why the fallback path worked or did not work, and what you would change before production.