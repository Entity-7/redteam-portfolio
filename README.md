```diff
+    ______      __  _ __              _____
+   / ____/___  / /_(_) /___  __      /__  /
+  / __/ / __ \/ __/ / __/ / / /_______ / /
+ / /___/ / / / /_/ / /_/ /_/ /_______// /
+/_____/_/ /_/\__/_/\__/\__, /        /_/
+                      /____/
```

**Entity-7** — Final-year Cyber Security Science (FUTMINNA) · CRTS v2

Working repository for offensive lab research, custom tooling, and detection
telemetry. Everything here is built, tested, and verified in isolated
enterprise lab environments.

### Directory

├── attack-chains/          # End-to-end AD & segmented network compromise paths (MITRE ATT&CK mapped)
├── protocol-internals/     # Wire-level breakdowns: Kerberos, SMB, LDAP
├── tooling/                # Custom C2 implants, loaders, and enumeration utilities
├── detection-engineering/  # Sigma rules, Sysmon configs, and event telemetry per attack chain
└── reports/                # Redacted lab engagement reports


### Active work

- `protocol-internals/kerberos/` — AS-REQ/TGS-REQ ticket lifecycle, PAC validation, delegation edge cases
- `tooling/` — Sliver C2 infrastructure: beacon configs, HTTP redirectors, deployment templates
- `reports/` — engagement reports from live pentest work and CRTS v2 lab replication

### Scope

Lab-only. No live targets, no unpatched disclosures.

### Contact

- X: [@SpydrBytz](https://x.com/SpydrBytz)
- CRTS v2 — credential verification available on request
