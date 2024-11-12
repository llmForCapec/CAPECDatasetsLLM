# CAPEC_LLM_Datasets

This repository provides datasets generated from the **Common Attack Pattern Enumeration and Classification (CAPEC)** and their associated **Common Weakness Enumeration (CWE)**, as defined by the MITRE Corporation.

- **CAPEC**: [https://capec.mitre.org/](https://capec.mitre.org/)
- **CWE**: [https://cwe.mitre.org/](https://cwe.mitre.org/)

## Overview

The repository includes five directories, each containing code snippets in **JavaScript**, **Java**, and **Python** for designated CAPEC patterns and their associated weaknesses (CWE). Each directory represents a separate generation run using GPT models, aimed at testing the consistency and robustness of the outputs across iterations.

## Directory Structure

- **Directories**: Each of the five directories corresponds to a distinct test run and contains the generated datasets for CAPEC patterns and CWEs.
- **Code Snippets**: Inside each directory, code snippets are categorized by language (JavaScript, Java, Python) for ease of reference and analysis.

## Purpose

This repository is intended to support research into the consistency of generative language models in producing vulnerability-related datasets aligned with CAPEC and CWE classifications. By offering multiple runs of generated data, this dataset supports comparative analysis and validation studies across code types and languages.

---
