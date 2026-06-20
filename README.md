# BeatClose proof log

Append-only log of hash commitments, published **before kickoff**.
Each batch file lists `commit_count, fixture_id, bet_type, commitment_hash, committed_at` (hashes only — picks stay secret until revealed at https://www.beatclose.com/proof).

Verify: recompute `sha256(canonical_str + salt)` from a revealed pick and match the hash here.
