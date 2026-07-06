# MEDUSA System Overview

This document provides a high-level overview of MEDUSA’s modular sensing and signal-processing architecture.

## Core Components
- Sensor Layer — raw data sources (physical or simulated)
- Ingestion Layer — buffering, timestamping, normalisation
- Processing Layer — filtering, fusion, GNSS-denial logic
- Analytics Layer — detection, classification, modelling
- Integration Layer — MOSA/OSA interfaces and ICDs
- Simulation Layer — synthetic data and scenario modelling
- Prototype Layer — early Python/C++ modules

## Data Flow Summary
Raw sensor data → ingestion → preprocessing → fusion → analytics → integration outputs.

## Purpose
To give DIU reviewers a clear understanding of MEDUSA’s internal structure and how each subsystem contributes to the overall capability.
