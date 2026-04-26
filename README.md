# NIST AI RMF Profile: Instructional Determinism & Repeatability (IDR)

# Overview
#This repository contains the IDR Profile, a technical implementation designed to bridge the NIST AI Risk Management Framework (AI RMF 1.0) with the evidentiary requirements of the U.S. Copyright Office.The primary objective is to mitigate Asset Devaluation by providing a forensic audit trail that distinguishes human creative expression from machine-generated "stochastic jitter".

# Key Features
- Instructional Lineage: Establishes a "Creative Ledger" to verify the human's role as the director of the work.
- Forensic Controls: Implements controls adapted from NIST SP 800-53, including AU-2 (Event Logging) and MA-1 (Repeatability).
- Quantitative Metrics: Defines a Repeatability Score to measure human vs. machine agency.
- Two-Tier Tolerance Model: Provides bit-for-bit match requirements for Tier 1 (Precision) assets and attribute locking for Tier 2 (Conceptual) assets.

# AI RMF Risk Mapping
This profile addresses specific economic and legal risks identified in the NIST MAP function:
- RISK-IP-01 (Authorship): Prevents the inability to prove authorship due to missing input logs.
- RISK-IP-02 (Enforceability Gap): Ensures assets are not deemed mere "products of a machine," which would render them ineligible for federal protection.

# The Authorship Evidence Bundle (AEB)
Compliant systems generate a cryptographically signed AEB containing:
- The Creative Ledger: Full prompt history.
- The IDR Report: Quantitative proof of the Repeatability Test.
- The Fixation Log: Timestamped record of the human's final expressive selection.

# Author
Joseph Donahue, IDAM05 Version 1.0 (Public Comment Draft) 
