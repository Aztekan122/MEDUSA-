# MEDUSA System Glossary

This glossary defines key terms used throughout the MEDUSA system documentation.  
It ensures DIU reviewers have a consistent understanding of MEDUSA’s terminology, concepts, and operational language.

---

## 1. Ingestion
The process of receiving, validating, and normalising sensor data before preprocessing.

---

## 2. Preprocessing
Feature extraction, noise reduction, timestamp correction, and metadata preservation performed before fusion.

---

## 3. Fusion
The combination of multiple sensor inputs into a unified, coherent representation.

---

## 4. Confidence Weighting
A scoring mechanism that reflects the reliability of fused or analytic outputs under degraded or partial data conditions.

---

## 5. GNSS-Denial Mode
An operational mode activated when GPS/GNSS signals are unavailable or unreliable, using alternative alignment strategies.

---

## 6. Partial-Data Fusion
Fusion pathways that operate when one or more sensors are missing, degraded, or corrupted.

---

## 7. Dropout Detection
Mechanisms that identify when sensors fail, degrade, or stop producing valid data.

---

## 8. Degraded Mode
A fallback operational state where MEDUSA continues functioning with reduced capability due to sensor, network, or compute constraints.

---

## 9. ICD (Interface Control Document)
A versioned schema defining how modules and external systems communicate, ensuring interoperability.

---

## 10. Legacy Adapter
A compatibility layer enabling MEDUSA to interface with older or non‑standard systems.

---

## 11. Deployment Model
The environment in which MEDUSA operates: cloud, edge, embedded, or hybrid.

---

## 12. Behaviour Modelling
Analytics that infer patterns, trends, or behaviours from fused sensor data.

---

## 13. Distributed Pipeline
A multi-node processing architecture where ingestion, fusion, and analytics occur across multiple coordinated systems.

---

## 14. Deterministic Execution
A predictable, repeatable execution path used in embedded deployments with strict timing constraints.

---

## 15. Stress Testing
Simulation-driven evaluation of MEDUSA’s resilience under extreme or degraded conditions.

---

## 16. Versioning Discipline
The controlled process of updating ICDs, modules, and documentation while maintaining backward compatibility.

---

## Purpose
To provide DIU reviewers with a consistent terminology reference, ensuring clarity and alignment across all MEDUSA system documentation.
