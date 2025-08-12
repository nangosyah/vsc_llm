## Project Summary

This project uses open-source large language models (LLMs) on the Vlaams Super Computer to automatically generate lists of 10 common symptoms for diseases identified by ICD codes from the MIMIC-IV database.  
Structured outputs (JSONL/Parquet) enable downstream data analysis.

## Project Summary
This project uses open-source large language models (LLMs) on the Vlaams Supercomputer (VSC) to automatically generate lists of 10 common symptoms for diseases identified by ICD codes from the MIMIC-IV database. Structured outputs (JSONL/Parquet) enable straightforward downstream analysis.

## What this page provides

- A short, beginner-friendly tutorial on VSC: how to log in, set up Python, load modules, and submit jobs with SLURM.
- Ready-to-use template files (config file, example runner, and job script).

## How it works

You supply a list of ICD codes. The system queries an LLM for the typical symptoms for each code and saves the results in tidy files that you can analyze later.

## Prerequisites

- A VSC account
- A Python environment (conda or venv)
- An open-source model to use
- Your ICD code list
