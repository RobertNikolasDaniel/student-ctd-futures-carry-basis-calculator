# STUDENT CTD → FUTURES NET CARRY BASIS CALCULATOR

### Simple Fixed Income Student Project

This project is a simplified educational calculator designed to explore the relationship between:

* U.S. Treasury cash bonds (CTD)
* CME Treasury futures
* Conversion factors
* Net carry
* DV01-neutral hedging
* Futures basis intuition

The goal is NOT to replicate dealer infrastructure or institutional pricing systems.

The goal is to preserve the core economic mechanics of:

> CTD cash bonds converting into futures exposure through carry and conversion factors.

---

# What This Calculator Does

The calculator:

1. Takes a Cheapest-To-Deliver Treasury bond

2. Converts it into implied futures exposure

3. Calculates net carry:

   CTD Yield − SOFR / Repo Rate

4. Estimates:

   * implied futures spot
   * DV01 exposure
   * futures DV01 exposure
   * basis points / price points
   * simplified basis P/L

---

# Why This Matters

Most students learn:

* duration
* Treasury futures
* bond pricing

…but never see how these concepts connect together operationally.

This project attempts to bridge that gap using a simplified framework.

Key intuition:

* Treasury futures are structurally linked to deliverable cash bonds
* Conversion factors map cash bond exposure into futures exposure
* Carry matters
* DV01 neutrality matters more than raw notional size
* Basis economics emerge from financing and yield relationships

---

# Inputs

* CTD Clean Price
* CTD Modified Duration
* Conversion Factor
* CTD Yield
* SOFR / Repo Rate
* Days to Delivery

---

# Outputs

* Implied Futures Spot
* Net Carry Rate
* Net Carry Price Points
* CTD DV01
* Futures DV01
* Basis Points / Price Points
* Simplified Basis P/L

---

# Important Notes

This is a simplified educational model.

The calculator intentionally ignores:

* delivery optionality
* repo specialness
* convexity adjustments
* accrued interest timing precision
* CTD switching dynamics
* market microstructure distortions
* institutional pricing complexity

The objective is not perfect market replication.

The objective is:

> preserving correct directional intuition while remaining understandable to students.

---

# Educational Takeaway

The most important insight from this project is:

> Treasury futures are financed duration exposure derived from deliverable cash bonds.

And because of that:

* carry matters
* conversion factors matter
* hedge ratios matter
* DV01 neutrality matters

---

# Disclaimer

This project is for educational purposes only.

It is not investment advice, trading advice, or institutional pricing infrastructure.
