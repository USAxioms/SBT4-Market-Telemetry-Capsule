# SBT4 Reproducibility Capsule

## The Claim

**My system turns raw data into SBT4. SBT4 is superior to competing formats.**

This capsule proves it.

---

## How to Verify

```bash
# Step 1: Run the capsule
python scripts/run_capsule.py

# Step 2: Verify the output
python -m unittest tests/ -v

# Step 3: Inspect the report
cat results/verification_report.json
```

---

What You Will See

1. Raw input (4 files: JSON, CSV, TXT, HTML)
2. Transformation through the CSL math
3. SBT4 output (4 sealed files)
4. Comparison against 3 competitors
5. Verdict: SBT4 wins on 5 dimensions

---

The 5 Dimensions of Superiority

Dimension SBT4 Competitors
Precision WAD-18 (18 decimals) Float (11-15 decimals)
Integrity SHA-256 + Ed25519 None or partial
Timestamps Dual (exch + arr, ns) Single (ms)
Info Ceiling Declared bitmask Undeclared
Grounding 6 axioms Black box

---

Reproducibility

Every output is byte-identical across machines.

Run it yourself. The math is the proof.
