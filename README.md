# OnChainSignals
Real-time Ethereum indexer in Go that streams blocks/logs over WebSockets, normalizes events, and writes to Postgres with exactly-once upserts. Exposes gRPC + SSE/WS feeds; ships with Docker/AWS and Prometheus/Grafana; p95 publish latency &lt;200 ms (k6).
