# API_testcases


## OWASP API Security Test Cases

This repository contains test cases, payloads, and PoC scripts for the **OWASP API Security Top 10**.  
It is designed to provide reproducible security checks that demonstrate common API weaknesses.

## Project Goal
The OWASP API Security Top 10 highlights the most critical API risks.  
This repo provides **modular test cases** for each risk, including:
- Short description of the risk
- Example payloads
- PoC scripts
- Sample vulnerable results

## Repository Structure
- `categories.md` → Overview of the OWASP API Top 10.  
- `test-cases/` → Each folder corresponds to one OWASP API category.  
- `fuzz-templates/` → Shared payload libraries (SQL injection, JSON fuzzing, header injection).  
- `docs/` → Integration guide and safe testing practices.  

