# NIST AI RMF PROFILE: ZERO DRAFT
**Subject:** Instructional Determinism and Repeatability (IDR) for IP Attribution
**Version:** 1.0 (Public Comment Draft)
**Author:** Joseph Donahue, IDAM05

---

## 1.0 OBJECTIVE & SCOPE
This Profile establishes a technical bridge between the NIST AI Risk Management Framework (AI RMF 1.0) and the evidentiary requirements of the U.S. Copyright Office. The goal is to mitigate the risk of Asset Devaluation by providing a forensic audit trail that distinguishes human creative expression from machine-generated "stochastic jitter."

### 1.1 AI RMF CROSSWALK
This Profile provides the technical implementation for the following AI RMF 1.0 / GenAI 600-1 Action IDs:

* MP-5.1-001: Provides the TEVV (Testing, Evaluation, Verification, and Validation) methodology for "Content Provenance" by measuring Human Creative Control (HCC).
* MP-5.1-002: Addresses "Information Integrity" harms by establishing a forensic baseline for authorship, mitigating the risk of unprotectable or "zombie" IP.
* MEASURE 2.11: Provides the quantitative metric (Repeatability Score) for assessing the degree of human vs. machine agency in a generated output.

---

## 2.0 RISK MAPPING (NIST MAP FUNCTION)
Organizations utilizing Generative AI systems shall categorize the following economic and legal risks:

* RISK-IP-01 (Information Integrity / Authorship). The failure to log the "Directed Input" sequence results in an inability to prove human authorship.
* RISK-IP-02 (Enforceability Gap): Without a repeatability audit, an asset is deemed a "product of a machine," rendering it ineligible for federal protection and public-market enforcement.

---

## 3.0 CORE FORENSIC CONTROLS
The following controls are adapted from NIST SP 800-53 (AU and MA Families) to serve the specific needs of Intellectual Property governance.

### AU-2: INSTRUCTIONAL EVENT LOGGING
* Requirement: The system must record a chronological "Creative Ledger" of all Directed Inputs.
* Audit Value: Establishes the "Instructional Lineage" required by legal examiners to verify the human's role as the director of the work.

### AU-3: DETERMINISTIC METADATA CONTENT
* Requirement: Every log entry must include a "Deterministic Metadata Bundle" containing:
    1. Global Seed: The specific starting point for the model's math.
    2. Temperature: Verified settings (Targeting 0.0) to minimize autonomous machine "drift."
    3. Model Hash: The specific version/build of the model used for that iteration.

### MA-1: INSTRUCTIONAL DETERMINISM & REPEATABILITY (IDR)
* Requirement: A quantitative measurement verifying that the "Directed Inputs" produce a consistent core output when re-run.
* Objective: To forensically demonstrate that the AI functioned as a predictable instrument of execution (similar to a camera or a digital brush) rather than an autonomous creator. This control serves as a TEVV practice for assessing the determinism of directed inputs.

### IC-1: INSTRUCTIONAL CONSTRAINTS
* Requirement: Explicit logging of "Negative Prompts" and constraints where the human actively limited model autonomy.
* Example: Logging the command "Do not alter geometry" proves the human is the master and the model is the servant.

---

## 4.0 THE MEASUREMENT FRAMEWORK (STOCHASTIC TOLERANCE)
To allow for the non-deterministic nature of LLMs without sacrificing legal standing, this profile implements a Two-Tier Tolerance Model:

| Asset Class | Requirement | Metric |
| :--- | :--- | :--- |
| Tier 1 (Precision) | High Repeatability >95% | Bit-for-Bit match (Logos, UI, Engineering) |
| Tier 2 (Conceptual) | Instructional Consistency | Core Attribute Lock (Narrative, Logic, Themes) |

---

## 5.0 SYSTEM OUTPUT: AUTHORSHIP EVIDENCE BUNDLE (AEB)
The compliant system shall generate a cryptographically signed AEB for each protected asset:

* The Creative Ledger: The full prompt history.
* The IDR Report: Quantitative proof of the Repeatability Test.
* The Fixation Log: A timestamped record of the human's final expressive selection.
