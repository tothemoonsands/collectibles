# Agent notes for collectibles

- Preserve the boundary between collectors, stored data, HTTP/UI code, and deployment settings. Keep credentials and production data out of source changes.
- Run `go test ./...` or focused package tests; build the affected target when practical.
