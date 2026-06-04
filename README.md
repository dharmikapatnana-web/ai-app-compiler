# AI App Compiler

A compiler-style AI system that converts natural language into validated executable application configurations.

---

# Architecture

User Prompt  
↓  
Intent Extraction  
↓  
System Design Layer  
↓  
Schema Generation  
↓  
Validation Engine  
↓  
Repair Engine  
↓  
Runtime Execution  
↓  
Generated Application  

---

# Features

- Multi-stage generation pipeline
- Deterministic structured outputs
- Validation and repair engine
- Cross-layer consistency checks
- Runtime-aware architecture
- Executable schema generation

---

# Pipeline Stages

## 1. Intent Extraction
Converts natural language into structured intent JSON.

## 2. System Design
Creates entities, flows, permissions, and architecture.

## 3. Schema Generation
Generates:
- UI schemas
- API schemas
- Database schemas
- Auth rules

## 4. Validation Layer
Checks:
- valid JSON
- schema consistency
- missing fields
- invalid mappings

## 5. Repair Engine
Repairs only failed components instead of retrying the entire generation process.

## 6. Runtime Execution
Generated schemas are converted into executable application components.

---

# Tech Stack

- Node.js
- Express.js
- React
- Prisma
- PostgreSQL
- OpenAI API

---

# Evaluation

The system was tested on:
- CRM systems
- LMS platforms
- Food delivery apps
- Edge-case prompts
- Conflicting requirements

---

# Goal

The objective of this project is to design a reliable AI software generation system focused on:
- consistency
- reliability
- deterministic generation
- execution awareness
