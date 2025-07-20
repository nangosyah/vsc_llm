# Patient-Reported Symptom List Generation Using LLMs on VSC

## Project Overview

- Scalable generation of patient-reported symptom lists using open LLMs on the Vlaams Supercomputer (VSC)
- Focus: ICD-coded diseases from the MIMIC-IV clinical database
- Output: Lists of 10 common symptoms per disease, in JSONL/Parquet formats
- Use cases: Frequency mapping, ontology alignment, clinical data analysis

---

## Workflow Outline

1. **Data Preparation**
    - Select ICD-coded disease list from MIMIC-IV
    - Preprocess input for LLM prompting

2. **Symptom Generation**
    - Prompt open-source LLMs to generate 10 common symptoms per disease

3. **Output Handling**
    - Save results in structured formats (JSONL, Parquet)
    - Validate outputs for completeness and consistency

4. **Downstream Analysis**
    - Frequency mapping
    - Ontology alignment
    - Additional clinical research tasks

---

## Why This Pipeline?

- Scalable for large datasets
- Consistent output structure for easy comparison
- Ready for direct integration with analytics workflows

---

## Getting Started

- Clone the repository
- Review setup and configuration instructions (see Quarto `.qmd` files)
- Prepare ICD input and LLM prompt scripts
- Submit jobs on VSC using provided SLURM templates
- Collect, analyze, and interpret the output data

---

## Resources

- VSC User Portal: https://www.vscentrum.be/en/
- MIMIC-IV Database: https://physionet.org/content/mimiciv/2.2/
- VSC SLURM Guide: https://www.vscentrum.be/en/user-info/batch-jobs

---

## Citation

- If you use this pipeline, cite as:
    > "Patient-Reported Symptom List Generation Using LLMs on VSC."

---

## Contact

- For questions or contributions, open an issue or contact project maintainers


