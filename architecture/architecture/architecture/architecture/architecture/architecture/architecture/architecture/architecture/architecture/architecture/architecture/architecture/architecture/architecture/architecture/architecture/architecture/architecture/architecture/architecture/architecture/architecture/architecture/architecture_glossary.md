# MEDUSA Architecture Glossary

This glossary defines key terms used throughout MEDUSA’s architecture documentation.  
It provides DIU reviewers and integration partners with consistent terminology and eliminates ambiguity across modules, pipelines, and ICDs.

## A

### Adapter Module
A component that translates external system formats into MEDUSA-compliant ICD schemas.

### Analytics Module
A processing unit that performs classification, detection, behaviour modelling, or statistical inference.

## C

### Component Boundary
A stable architectural separation defining responsibilities and interfaces for a module.

### Confidence Score
A numerical measure indicating the reliability of an analytics output.

### Cloud Deployment
A deployment model using scalable compute resources for high-throughput analytics.

## D

### Data Fusion
The process of combining multi-sensor inputs into a unified feature representation.

### Degraded Mode
A fallback operational state triggered when sensors or pipelines experience partial failure.

### Distributed Pipeline
A processing pipeline executed across multiple nodes or compute environments.

## E

### Edge Deployment
A deployment model where processing occurs near sensors with reduced latency and limited compute.

### Embedded Deployment
A constrained deployment model using hardware-integrated modules with deterministic performance.

## F

### Feature Vector
A structured representation of sensor-derived features used by analytics modules.

### Fusion Engine
A module responsible for combining multi-sensor data streams into coherent fused outputs.

## G

### GNSS-Denial
An operational condition where GPS/GNSS signals are unavailable or unreliable.

### Governance Framework
The structured process controlling architectural evolution, ICD changes, and module certification.

## I

### ICD (Interface Control Document)
A versioned specification defining message formats, schemas, and communication rules between components.

### Ingestion Layer
The subsystem responsible for receiving, validating, and normalising sensor data.

## L

### Latency Budget
The maximum allowable processing time for a pipeline to meet real-time or near-real-time requirements.

## M

### Modularity
The architectural property enabling components to be replaced, upgraded, or extended without system-wide refactoring.

### MOSA / OSA
Modular Open Systems Approach / Open Systems Architecture — defence-aligned modularity standards.

## P

### Pipeline
A sequence of processing stages transforming raw sensor data into analytics outputs.

### Prototype Module
An early-stage component used for experimentation and drop-in replacement testing.

## R

### Resilience Pathway
A mechanism ensuring MEDUSA continues functioning under degraded or hostile conditions.

## S

### Scalability Model
A description of how MEDUSA expands across compute, data, and mission dimensions.

### Simulation Layer
A subsystem generating synthetic data and scenarios for validation and stress testing.

## T

### Technical Debt
Known architectural weaknesses or incomplete areas requiring future remediation.

### Timestamp Normalisation
The process of aligning inconsistent sensor timestamps for synchronised processing.

## Purpose
To give DIU reviewers and integration partners a clear, consistent vocabulary for understanding MEDUSA’s architecture.
