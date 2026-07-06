# MEDUSA Component Interactions

This document describes how MEDUSA’s modular components interact, exchange data, and coordinate processing tasks.  
It provides a clear view of internal communication pathways and subsystem dependencies.

## 1. Sensor Layer → Ingestion Layer
Interaction:
- Sensors push raw data into ingestion buffers.
- Metadata (timestamps, IDs) is attached.
- Ingestion validates and normalises formats.

## 2. Ingestion Layer → Processing Layer
Interaction:
- Ingestion forwards synchronised data batches.
- Processing applies filtering, feature extraction, and GNSS-denial logic.
- Errors or anomalies are flagged back to ingestion.

## 3. Processing Layer → Analytics Layer
Interaction:
- Processed data is streamed into analytics modules.
- Analytics performs classification, detection, and modelling.
- Feedback loops allow analytics to request additional processing passes.

## 4. Analytics Layer → Integration Layer
Interaction:
- Analytics outputs are packaged into ICD-compliant formats.
- Integration exposes APIs and MOSA/OSA interfaces.
- External systems consume MEDUSA outputs.

## 5. Simulation Layer → All Layers
Interaction:
- Simulation can inject synthetic data into ingestion.
- It can emulate sensor behaviour for testing.
- It can stress-test analytics and integration under controlled conditions.

## 6. Prototype Layer → Processing & Analytics
Interaction:
- Prototype modules replace or augment processing/analytics components.
- Used for rapid experimentation and early feasibility testing.

## Purpose
To give DIU reviewers a clear understanding of how MEDUSA’s modular components coordinate and exchange information across the full system.
