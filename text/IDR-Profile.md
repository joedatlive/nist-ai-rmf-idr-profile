# [cite_start]NIST AI RMF PROFILE: ZERO DRAFT [cite: 1]
[cite_start]**Subject:** Instructional Determinism and Repeatability (IDR) for IP Attribution [cite: 2]  
[cite_start]**Version:** 1.0 (Public Comment Draft) [cite: 3]  
[cite_start]**Author:** Joseph Donahue, IDAM05 [cite: 4]  

## [cite_start]1.0 OBJECTIVE & SCOPE [cite: 5]
[cite_start]This Profile establishes a technical bridge between the NIST AI Risk Management Framework (AI RMF 1.0) and the evidentiary requirements of the U.S. Copyright Office. [cite: 6] [cite_start]The goal is to mitigate the risk of Asset Devaluation by providing a forensic audit trail that distinguishes human creative expression from machine-generated "stochastic jitter." [cite: 7]

### [cite_start]1.1 AI RMF CROSSWALK [cite: 8]
[cite_start]This Profile provides the technical implementation for the following AI RMF 1.0 / GenAI 600-1 Action IDs: [cite: 9]

* [cite_start]**MP-5.1-001:** Provides the TEVV (Testing, Evaluation, Verification, and Validation) methodology for "Content Provenance" by measuring Human Creative Control (HCC). [cite: 12]
* [cite_start]**MP-5.1-002:** Addresses "Information Integrity" harms by establishing a forensic baseline for authorship, mitigating the risk of unprotectable or "zombie" IP. [cite: 13]
* [cite_start]**MEASURE 2.11:** Provides the quantitative metric (Repeatability Score) for assessing the degree of human vs. machine agency in a generated output. [cite: 14]

## [cite_start]2.0 RISK MAPPING (NIST MAP FUNCTION) [cite: 15]
[cite_start]Organizations utilizing Generative AI systems shall categorize the following economic and legal risks: [cite: 16]

* [cite_start]**RISK-IP-01 (Information Integrity / Authorship).** [cite: 17] [cite_start]The failure to log the "Directed Input" sequence results in an inability to prove human authorship. [cite: 18]
* [cite_start]**RISK-IP-02 (Enforceability Gap):** Without a repeatability audit, an asset is deemed a "product of a machine," rendering it ineligible for federal protection and public-market enforcement. [cite: 19]

## [cite_start]3.0 CORE FORENSIC CONTROLS [cite: 20]
[cite_start]The following controls are adapted from NIST SP 800-53 (AU and MA Families) to serve the specific needs of Intellectual Property governance. [cite: 21]

### [cite_start]AU-2: INSTRUCTIONAL EVENT LOGGING [cite: 22]
* [cite_start]**Requirement:** The system must record a chronological "Creative Ledger" of all Directed Inputs. [cite: 24]
* [cite_start]**Audit Value:** Establishes the "Instructional Lineage" required by legal examiners to verify the human's role as the director of the work. [cite: 25]

### [cite_start]AU-3: DETERMINISTIC METADATA CONTENT [cite: 26]
* [cite_start]**Requirement:** Every log entry must include a "Deterministic Metadata Bundle" containing: [cite: 27]
    1. [cite_start]**Global Seed:** The specific starting point for the model's math. [cite: 28]
    2. [cite_start]**Temperature:** Verified settings (Targeting 0.0) to minimize autonomous machine "drift." [cite: 29]
    3. [cite_start]**Model Hash:** The specific version/build of the model used for that iteration. [cite: 30]

### [cite_start]MA-1: INSTRUCTIONAL DETERMINISM & REPEATABILITY (IDR) [cite: 31]
* [cite_start]**Requirement:** A quantitative measurement verifying that the "Directed Inputs" produce a consistent core output when re-run. [cite: 34]
* [cite_start]**Objective:** To forensically demonstrate that the AI functioned as a predictable instrument of execution (similar to a camera or a digital brush) rather than an autonomous creator. [cite: 35] [cite_start]This control serves as a TEVV practice for assessing the determinism of directed inputs. [cite: 36]

### [cite_start]IC-1: INSTRUCTIONAL CONSTRAINTS [cite: 37]
* [cite_start]**Requirement:** Explicit logging of "Negative Prompts" and constraints where the human actively limited model autonomy. [cite: 39]
* [cite_start]**Example:** Logging the command "Do not alter geometry" proves the human is the master and the model is the servant. [cite: 40]

## [cite_start]4.0 THE MEASUREMENT FRAMEWORK (STOCHASTIC TOLERANCE) [cite: 41]
[cite_start]To allow for the non-deterministic nature of LLMs without sacrificing legal standing, this profile implements a Two-Tier Tolerance Model: [cite: 42]

| Asset Class | Requirement | Metric |
| :--- | :--- | :--- |
| Tier 1 (Precision) | High Repeatability >95% | Bit-for-Bit match (Logos, UI, Engineering) |
| Tier 2 (Conceptual) | Instructional Consistency | Core Attribute Lock (Narrative, Logic, Themes) |

[cite_start][cite: 43]

## [cite_start]5.0 SYSTEM OUTPUT: AUTHORSHIP EVIDENCE BUNDLE (AEB) [cite: 44, 45]
[cite_start]The compliant system shall generate a cryptographically signed AEB for each protected asset: [cite: 46]

* [cite_start]**The Creative Ledger:** The full prompt history. [cite: 47]
* [cite_start]**The IDR Report:** Quantitative proof of the Repeatability Test. [cite: 48]
* [cite_start]**The Fixation Log:** A timestamped record of the human's final expressive selection. [cite: 49]
