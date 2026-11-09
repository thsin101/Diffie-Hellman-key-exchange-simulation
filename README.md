# Diffie-Hellman-key-exchange-simulation

dlp_bench.py — simulate a Diffie-Hellman key exchange, then break it, and
measure how the cost of breaking it grows.

Course project: Quantum-Safe Storage and Settlement.
Deliverable V, Unit 5 — Technological Infrastructure for Fintech.

# USAGE
Examples of usage are:

    python3 dlp_bench.py dh    --bits 16
    python3 dlp_bench.py break --bits 24
    python3 dlp_bench.py scale --from-bits 16 --to-bits 40 --out results.json
