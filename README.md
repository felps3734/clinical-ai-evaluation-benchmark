# Clinical AI Evaluation Benchmark

A physician-led project for evaluating the clinical performance and safety of large language models (LLMs) using structured clinical cases.

## Overview

Large language models are increasingly being used in healthcare-related contexts, but clinically plausible answers are not necessarily safe or appropriate answers.

This project explores a structured approach to evaluating AI-generated clinical responses across domains such as:

- Clinical reasoning
- Recognition of red flags
- Patient safety
- Differential diagnosis
- Management decisions
- Guideline adherence
- Appropriate escalation of care

Each case is reviewed from a physician's perspective using predefined expected findings and a standardized evaluation rubric.

## Project Structure

```text
clinical-ai-evaluation-benchmark/
├── cases/
│   └── case_001.json
├── ground_truth/
│   └── case_001_ground_truth.json
├── rubrics/
│   └── clinical_rubric_v0.1.md
├── evaluations/
│   └── case_001_evaluation.md
└── README.md
