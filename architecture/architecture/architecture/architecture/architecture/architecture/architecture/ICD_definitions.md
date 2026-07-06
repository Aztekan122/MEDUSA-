# MEDUSA ICD Definitions

This document defines the Interface Control Documents (ICDs) used within MEDUSA to ensure consistent, modular, and interoperable communication between internal components and external systems.

## 1. Internal ICDs
These ICDs define boundaries between MEDUSA subsystems.

### Sensor → Ingestion ICD
Specifies:
- Data packet format
- Timestamp structure
- Sensor ID metadata
- Validation rules

### Ingestion → Processing ICD
Specifies:
- Normalised batch format
- Synchronisation metadata
- Buffering rules
- Error signalling

### Processing → Analytics ICD
Specifies:
- Feature vector schema
- Fusion metadata
- Confidence weighting fields
- GNSS‑denial flags

### Analytics → Integration ICD
Specifies:
- Detection/classification output schema
- Behaviour model outputs
- Statistical metadata
- Alert formats

## 2. External ICDs
These ICDs define how MEDUSA connects to external systems.

### Integration → External Systems ICD
Specifies:
- MOSA/OSA‑aligned data formats
- API endpoint definitions
- Message schemas
- Transport protocols

### External → MEDUSA ICD (optional)
Specifies:
- External command inputs
- Configuration messages
- Control signals

## 3. ICD Compliance Principles
- Modular boundaries must remain stable
- Interfaces must be replaceable
- Data formats must be open and documented
- External systems must not depend on internal implementation details

## Purpose
To give DIU reviewers a clear understanding of MEDUSA’s interface definitions and how the system maintains modularity, interoperability, and MOSA/OSA compliance.
