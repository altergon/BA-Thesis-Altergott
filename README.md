# BA-Thesis-Altergott
This is the repository for Nikolai Altergott's Bachelor Thesis

# Enhancing the Retail Investor: Do LLMs improve investment research for non-professionals?

**Type:** Bachelor's Thesis

**Author:** Nikolai Altergott (622882)

**1st Examiner:** Prof Dr. Lessmann 

**2nd Examiner:** Prof Dr. Mendling 

## Table of Content

- [Summary](#summary)
- [Working with the repo](#working-with-the-repo)
    - [Dependencies](#dependencies)
    - [Setup](#setup)
- [Reproducing results](#reproducing-results)
    - [Data](#data)
- [Project structure](#project-structure)

## Summary

This thesis investigates the extent to which Large Language Models (LLMs) can enhance the investment research process for non-professional retail investors, which is a rapidly growing understudied use case of LLMs. By employing a between-subjects experiment with 25 participants analyzing a curated 10-K report excerpt, the study empirically quantified the impact of LLM-generated summaries on investor understanding, confidence, and efficiency. The results indicate that while the intervention had no significant effect on factual recall due to a "ceiling effect" in the source material, it exerted a large, statistically significant positive influence on interpretative comprehension. Furthermore, the presence of an AI summary acted as a major catalyst for self-reported confidence, proving particularly effective in bridging the gap toward decision-making sufficiency. Surprisingly, the study found no significant improvement in efficiency, suggesting that the summary functioned as a supplemental cognitive resource rather than a time-saving shortcut for short tasks. Ultimately, the findings suggest that LLMs serve as a powerful "cognitive bridge" that democratizes financial analysis by aligning subjective certainty with objective comprehension, shifting the investor's role from raw data retrieval toward high-level strategic synthesis.

**Keywords**: Financial Analysis; LLMs; Decision-Support; Investment Research; AI.

**Full text**: [include a link that points to the full text of your thesis]
*Remark*: a thesis is about research. We believe in the [open science](https://en.wikipedia.org/wiki/Open_science) paradigm. Research results should be available to the public. Therefore, we expect dissertations to be shared publicly. Preferably, you publish your thesis via the [edoc-server of the Humboldt-Universität zu Berlin](https://edoc-info.hu-berlin.de/de/publizieren/andere). However, other sharing options, which ensure permanent availability, are also possible. <br> Exceptions from the default to share the full text of a thesis require the approval of the thesis supervisor.  

## Working with the repo

### Dependencies

- Python Version >= 3.9.6

### Setup

1. Clone this repository
```bash
git clone <(https://github.com/altergon/BA-Thesis-Altergott/)>
cd <BA-Thesis-Altergott>
```

2. Create an virtual environment and activate it
#### Windows
```bash
python -m venv venv
venv\Scripts\activate
```
#### macOS/Linux
```bash
python3 -m venv venv
source venv/bin/activate
```
3. Install dependecies
```bash
pip install pandas numpy matplotlib seaborn scipy ipykernel
```
## Reproducing results
1. Open Analysis.ipynb in VS Code.
2. Ensure the Jupyter Extension is installed in VS Code.
3. Select your Python interpreter/kernel (top right of the editor).
4. Click Run All to execute the pipeline.

### Data

Survey-Data-19_12_25.csv contains the survey data.


## Project structure

```bash
├── README.md
├── Analysis.ipynb                                  -- Analysis pipeline; produces all results
├── Survey-Data-19_12_25.csv                        -- Contains the data; is linked in the pipeline
├── Survey-Design.pdf                               -- Overview of the used survey/experiment design
```
