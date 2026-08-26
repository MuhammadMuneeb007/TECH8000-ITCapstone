 
# Literature Review and Literature Synthesis

## Learning Objectives

By the end of this session, students should be able to:

- Explain the purpose of a literature review.
- Distinguish between an annotated bibliography and a literature review.
- Identify credible and relevant academic sources.
- Summarise, evaluate, and reflect on individual sources.
- Organise research papers into themes.
- Compare and contrast findings across multiple studies.
- Identify agreements, disagreements, limitations, and research gaps.
- Understand how AI and software can support literature discovery and synthesis.
- Evaluate automated literature-review tools.
- Validate AI-generated claims against original research sources.

---

# 1. What Is a Literature Review?

A **literature review** is a structured examination of existing research on a particular topic.

It does more than simply describe individual papers.

A literature review should:

- Integrate existing knowledge.
- Compare different studies.
- Identify important themes.
- Identify research trends.
- Discuss debates and disagreements.
- Evaluate existing evidence.
- Identify limitations.
- Identify gaps in the literature.
- Explain what further research is needed.
- Provide justification for a proposed project.

A good literature review answers questions such as:

- What is already known?
- What approaches have already been tried?
- What results have researchers obtained?
- Where do researchers agree?
- Where do researchers disagree?
- What limitations exist?
- What remains unsolved?
- Why is the proposed project necessary?

---

# 2. Why Do We Conduct a Literature Review?

A literature review allows researchers to participate in the **scholarly and intellectual discourse** surrounding a topic.

It helps researchers to:

- Understand the current state of knowledge.
- Avoid repeating existing work.
- Discover important or overlooked studies.
- Identify emerging research.
- Understand commonly used methodologies.
- Identify strengths and weaknesses of existing approaches.
- Identify unanswered questions.
- Develop stronger research questions.
- Justify a proposed project.
- Demonstrate understanding of the research area.

---

# 3. What Is an Annotated Bibliography?

An **annotated bibliography** contains references followed by information describing and evaluating each source.

Each annotation generally contains three components:

1. **Summary**
2. **Evaluation**
3. **Reflection**

---

## 3.1 Summary

The summary explains:

- What the paper investigated.
- What problem was addressed.
- What methods were used.
- What data were used.
- What the researchers found.

### Example

> Smith et al. investigated machine-learning algorithms for detecting phishing emails. The authors compared Random Forest, Support Vector Machine, and Logistic Regression models using a dataset containing 20,000 emails. Random Forest achieved the highest classification accuracy.

---

## 3.2 Evaluation

Evaluation considers the quality and reliability of the source.

Questions may include:

- Is the source peer reviewed?
- Is the publication recent?
- Is the methodology appropriate?
- Is the dataset sufficiently large?
- Are the experiments reproducible?
- Are the conclusions supported by the results?
- Are important limitations acknowledged?
- Is the journal or conference credible?

### Example

> The study provides a useful comparison of several machine-learning algorithms and uses a relatively large dataset. However, the models were evaluated using only one dataset, which may limit the generalisability of the results.

---

## 3.3 Reflection

Reflection explains how the source relates to your own project.

Questions include:

- How does this study relate to my research question?
- What can I learn from its methodology?
- Can I improve its approach?
- Does it reveal a limitation my project could address?
- Does it support the motivation for my project?

### Example

> This paper is relevant because it establishes baseline performance for traditional machine-learning methods. The proposed project could extend this research by evaluating transformer-based models and testing them across independent datasets.

---

# 4. Annotated Bibliography vs Literature Review

## Annotated Bibliography

An annotated bibliography normally considers sources separately.

```text
Paper A
↓
Summary
↓
Evaluation
↓
Reflection

Paper B
↓
Summary
↓
Evaluation
↓
Reflection

Paper C
↓
Summary
↓
Evaluation
↓
Reflection
````

Example:

> Paper A used Random Forest and achieved 89% accuracy.

> Paper B used a Transformer and achieved 94% accuracy.

> Paper C used a CNN and achieved 87% accuracy.

This describes individual studies.

---

## Literature Review

A literature review connects studies.

```text
Paper A ─┐
Paper B ─┼──► Compare
Paper C ─┤
Paper D ─┘
          │
          ▼
    Identify Themes
          │
          ▼
 Compare Similarities
          │
          ▼
 Compare Differences
          │
          ▼
Identify Limitations
          │
          ▼
 Identify Research Gaps
          │
          ▼
       Synthesis
```

Example:

> Recent phishing-detection research has increasingly shifted from traditional machine-learning methods toward deep-learning and transformer-based approaches. Although transformer models frequently achieve higher performance on benchmark datasets, several studies report reduced performance on independent datasets. This suggests that generalisability remains an important limitation.

---

# 5. Summary vs Synthesis

Consider the following studies:

| Study | Method        | Accuracy | Main Limitation              |
| ----- | ------------- | -------: | ---------------------------- |
| A     | Random Forest |      89% | Small dataset                |
| B     | Transformer   |      94% | Computationally expensive    |
| C     | Transformer   |      78% | Poor external generalisation |
| D     | CNN           |      87% | Class imbalance              |

## Summary

> Study A used Random Forest. Study B used a Transformer. Study C also used a Transformer. Study D used a CNN.

This is mainly **description**.

## Synthesis

> Transformer-based approaches generally reported stronger performance than conventional machine-learning methods. However, performance varied considerably between datasets, suggesting that their apparent advantage may depend on the evaluation dataset. Generalisation across independent datasets therefore remains unresolved.

Synthesis contains:

* Comparison
* Interpretation
* Similarities
* Differences
* Limitations
* Research gaps

---

# 6. Literature Review Process

```text
Research Question
      │
      ▼
Search Literature
      │
      ▼
Select Relevant Sources
      │
      ▼
Read Sources
      │
      ▼
Create Annotations
      │
      ▼
Group Sources
      │
      ▼
Identify Themes
      │
      ▼
Compare Studies
      │
      ▼
Identify Agreements
      │
      ▼
Identify Disagreements
      │
      ▼
Identify Limitations
      │
      ▼
Identify Research Gaps
      │
      ▼
Develop Narrative
      │
      ▼
Literature Review
```

---

# 7. Define the Research Question

Before searching, clearly define the problem.

A broad question:

> How is artificial intelligence used in cybersecurity?

may retrieve thousands of unrelated papers.

A focused question:

> How effective are transformer-based models for phishing-email detection compared with traditional machine-learning methods?

is easier to investigate.

---

# 8. Identify Search Terms

Break the research question into concepts.

Example:

```text
Concept 1:
Phishing

Concept 2:
Machine Learning

Concept 3:
Transformer

Concept 4:
Email Detection
```

Possible keywords:

```text
phishing
phishing detection
fraudulent email
malicious email

machine learning
deep learning
artificial intelligence

transformer
BERT
large language model
```

---

# 9. Academic Search Resources

Useful academic databases include:

* Google Scholar
* Semantic Scholar
* Scopus
* Web of Science
* IEEE Xplore
* ACM Digital Library
* PubMed
* SpringerLink
* ScienceDirect
* arXiv
* OpenAlex

For IT projects, commonly useful sources include:

* IEEE Xplore
* ACM Digital Library
* Google Scholar
* Semantic Scholar
* Scopus
* arXiv

---

# 10. Boolean Searching

## AND

Requires both concepts.

```text
phishing AND transformer
```

## OR

Allows alternative terminology.

```text
phishing OR "fraudulent email"
```

## NOT

Excludes unwanted topics.

```text
phishing NOT website
```

## Combined Query

```text
("phishing email" OR "malicious email")
AND
("machine learning" OR "deep learning")
AND
(transformer OR BERT)
```

---

# 11. Evaluating Sources

Not every search result should be included.

Consider the following.

## Relevance

Does the paper actually address the research question?

## Authority

Who conducted and published the research?

## Publication Type

Is it a:

* Peer-reviewed journal article?
* Conference paper?
* Preprint?
* Thesis?
* Technical report?
* Blog?
* Website?

## Recency

Is the research recent enough for the topic?

Fast-changing areas such as artificial intelligence may require very recent literature.

## Methodology

Are the methods appropriate?

## Dataset

Is the dataset suitable and sufficiently large?

## Evidence

Do the results support the conclusions?

## Reproducibility

Could another researcher reproduce the study?

---

# 12. Create an Evidence Table

An evidence table can make synthesis easier.

| Reference    | Problem               | Dataset   | Method        | Results | Strength         | Limitation          |
| ------------ | --------------------- | --------- | ------------- | ------- | ---------------- | ------------------- |
| Smith et al. | Phishing detection    | Dataset A | Random Forest | 89%     | Simple model     | Single dataset      |
| Lee et al.   | Phishing detection    | Dataset A | BERT          | 94%     | Strong accuracy  | Expensive           |
| Khan et al.  | Cross-domain phishing | Dataset B | BERT          | 78%     | External testing | Poor generalisation |
| Jones et al. | Email classification  | Dataset C | CNN           | 87%     | Efficient        | Class imbalance     |

---

# 13. Group Papers Into Themes

Do not organise the final literature review like this:

```text
Paper 1
Paper 2
Paper 3
Paper 4
```

Instead, organise papers around themes.

Example:

```markdown
## Traditional Machine-Learning Approaches

## Deep-Learning Approaches

## Transformer-Based Models

## Explainability

## Dataset and Evaluation Issues

## Generalisation Challenges
```

Several papers can be discussed within each theme.

---

# 14. Compare and Contrast Studies

Within each theme, consider:

## Similarities

* Do studies use similar methods?
* Do they reach similar conclusions?
* Do they use similar datasets?
* Do they report similar performance?

## Differences

* Different datasets?
* Different algorithms?
* Different evaluation metrics?
* Different results?
* Different assumptions?
* Different study populations?

## Contradictions

Studies may reach different conclusions.

Example:

> Smith et al. found that BERT significantly outperformed Random Forest, whereas Khan et al. reported only a small improvement when models were evaluated using an independent dataset.

A good literature review investigates **why** these results may differ.

---

# 15. Identify Research Gaps

A research gap represents something existing research has not adequately addressed.

## Data Gap

> Existing studies rely primarily on small datasets.

## Methodological Gap

> Few studies compare transformer models with recent ensemble methods.

## Evaluation Gap

> Models are frequently evaluated using only one dataset.

## Generalisation Gap

> Limited research evaluates models across independent datasets.

## Technology Gap

> Recent large language models have not been extensively evaluated.

## Population Gap

> Existing research focuses primarily on one population or country.

## Reproducibility Gap

> Source code and datasets are rarely publicly available.

---

# 16. Develop the Narrative

A literature review should tell a logical story.

```text
Traditional Approaches
        │
        ▼
Problems Identified
        │
        ▼
Deep Learning Introduced
        │
        ▼
Performance Improved
        │
        ▼
New Limitations Identified
        │
        ▼
Transformers Introduced
        │
        ▼
Current State of Research
        │
        ▼
Remaining Research Gap
        │
        ▼
Proposed Project
```

The literature should logically lead toward the motivation for the project.

---

# 17. Traditional Literature Review Workflow

```text
Research Question
        │
        ▼
Keywords
        │
        ▼
Database Search
        │
        ▼
Hundreds or Thousands of Papers
        │
        ▼
Remove Duplicates
        │
        ▼
Read Titles
        │
        ▼
Read Abstracts
        │
        ▼
Select Relevant Papers
        │
        ▼
Read Full Text
        │
        ▼
Take Notes
        │
        ▼
Create Evidence Table
        │
        ▼
Identify Themes
        │
        ▼
Write Literature Review
```

Modern software can automate parts of this process.

---

# 18. Automated Literature Review

Modern literature-review systems may use:

* Information retrieval
* Machine learning
* Natural language processing
* Semantic search
* Citation networks
* Active learning
* Embeddings
* Topic modelling
* Large language models
* Retrieval-Augmented Generation
* Knowledge graphs

Automation should normally **assist the researcher rather than replace the researcher**.

---

# 19. Modern Literature Review Workflow

```text
                 Research Question
                        │
                        ▼
                Literature Search
                 /            \
                /              \
       Keyword Search      Semantic Search
                               │
                               ▼
                       Citation Networks
                               │
                               ▼
                        Retrieve Papers
                               │
                               ▼
                        Deduplication
                               │
                               ▼
                     AI-Assisted Screening
                               │
                               ▼
                       Full-Text Parsing
                               │
                               ▼
                    Information Extraction
                               │
                               ▼
                       Evidence Matrix
                               │
                               ▼
                    Thematic Grouping
                               │
                               ▼
                    Compare Across Papers
                               │
                               ▼
                        AI Synthesis
                               │
                               ▼
                      Human Validation
                               │
                               ▼
                      Literature Review
```

---

# 20. Keyword Search vs Semantic Search

Traditional keyword search asks:

> Does this document contain the words in my query?

Semantic search asks:

> Does this document have a similar meaning to my query?

Example query:

```text
AI techniques for detecting fraudulent emails
```

Possible paper:

```text
Transformer-Based Identification of Phishing Messages
```

The exact words are different, but the meaning is similar.

---

# 21. How Semantic Search Works

Text is transformed into numerical representations called **embeddings**.

```text
"machine learning for phishing detection"
                │
                ▼
        Embedding Model
                │
                ▼
[0.18, -0.42, 0.71, 0.09, ...]
```

A research-paper abstract is converted in the same way.

```text
Paper Abstract
      │
      ▼
Embedding Model
      │
      ▼
[0.21, -0.39, 0.68, 0.12, ...]
```

Similarity measures such as **cosine similarity** can then determine whether two pieces of text are conceptually related.

---

# 22. Citation Networks

Scientific papers form networks.

```text
Paper A
   │
   ├──── cites ───► Paper B
   │
   └──── cites ───► Paper C

Paper D ─── cites ───► Paper A
```

Citation-based tools can use relationships such as:

* Direct citations
* Co-citation
* Bibliographic coupling
* Shared references
* Common authors
* Citation paths

---

# 23. Literature Mapping Tools

## ResearchRabbit

ResearchRabbit supports literature discovery using citation and author networks.

Typical workflow:

```text
Seed Paper
    │
    ▼
Find Similar Papers
    │
    ▼
Explore Citation Network
    │
    ▼
Add Relevant Papers
    │
    ▼
Receive Recommendations
```

Website:

```text
https://www.researchrabbit.ai/
```

---

## Connected Papers

Connected Papers generates visual graphs of related publications.

Useful for:

* Finding foundational studies.
* Finding related research.
* Discovering earlier work.
* Discovering later work.
* Exploring a research field.

Website:

```text
https://www.connectedpapers.com/
```

---

## Litmaps

Litmaps allows researchers to build and explore citation-based literature maps.

Useful for:

* Literature discovery.
* Citation tracking.
* Monitoring new publications.
* Building research maps.

Website:

```text
https://www.litmaps.com/
```

---

# 24. AI-Assisted Screening

Suppose a literature search retrieves:

```text
10,000 papers
```

but only:

```text
150 papers
```

are actually relevant.

Reading every abstract manually may be inefficient.

Machine-learning systems can rank papers according to their predicted relevance.

---

# 25. Active Learning

Active learning creates a feedback loop between a human reviewer and a machine-learning model.

```text
Human Labels Papers
        │
        ▼
Relevant / Not Relevant
        │
        ▼
Machine-Learning Model Learns
        │
        ▼
Rank Remaining Papers
        │
        ▼
Show Most Likely Relevant Paper
        │
        ▼
Human Labels It
        │
        ▼
Model Updates
        │
        └──────────► Repeat
```

The goal is to show relevant papers earlier and reduce unnecessary screening.

---

# 26. ASReview

**ASReview** is an open-source platform for AI-assisted systematic-review screening.

GitHub:

```text
https://github.com/asreview/asreview
```

Installation:

```bash
python -m venv literature-env
```

Windows:

```bash
literature-env\Scripts\activate
```

Linux/macOS:

```bash
source literature-env/bin/activate
```

Install:

```bash
pip install asreview
```

Launch:

```bash
asreview lab
```

ASReview can demonstrate:

* Classification
* Machine learning
* Active learning
* Ranking
* Human-in-the-loop AI
* Literature screening

---

# 27. Large Language Models for Literature Synthesis

Large language models can assist with:

* Summarising papers.
* Extracting information.
* Comparing findings.
* Identifying themes.
* Identifying limitations.
* Creating evidence tables.
* Detecting possible contradictions.
* Drafting synthesis paragraphs.

However, directly asking:

```text
"Tell me everything research says about phishing detection."
```

may result in:

* Missing important papers.
* Invented references.
* Incorrect claims.
* Unsupported conclusions.

A safer approach is **Retrieval-Augmented Generation (RAG)**.

---

# 28. Retrieval-Augmented Generation

RAG combines search with a language model.

```text
Question
   │
   ▼
Search Documents
   │
   ▼
Retrieve Relevant Evidence
   │
   ▼
Rank Evidence
   │
   ▼
Provide Evidence to LLM
   │
   ▼
Generate Answer
   │
   ▼
Provide Citations
```

Instead of relying only on the language model's internal knowledge, the model receives relevant source material.

---

# 29. Scientific RAG Workflow

```text
Research Question
       │
       ▼
Search Papers
       │
       ▼
Download Papers
       │
       ▼
Parse Documents
       │
       ▼
Split Into Chunks
       │
       ▼
Generate Embeddings
       │
       ▼
Store Embeddings
       │
       ▼
Ask Question
       │
       ▼
Retrieve Relevant Chunks
       │
       ▼
Rerank Evidence
       │
       ▼
LLM Reads Evidence
       │
       ▼
Generate Synthesis
       │
       ▼
Attach References
       │
       ▼
Human Validation
```

---

# 30. PaperQA2

PaperQA2 is an open-source system for scientific question answering and literature synthesis.

GitHub:

```text
https://github.com/Future-House/paper-qa
```

Installation:

```bash
python -m venv paperqa-env
```

Install:

```bash
pip install "paper-qa>=5"
```

Example:

```bash
pqa ask "What methods are used across these papers?"
```

Another example:

```bash
pqa ask "What limitations are repeatedly identified?"
```

PaperQA2 can demonstrate:

* Scientific RAG
* Document retrieval
* Embeddings
* Reranking
* LLM synthesis
* Citation grounding

---

# 31. Information Extraction

AI systems can convert information from papers into structured data.

Example:

```json
{
  "study": "Smith et al.",
  "year": 2025,
  "dataset": "PhishingEmailDataset",
  "sample_size": 20000,
  "method": "BERT",
  "accuracy": 0.94,
  "limitation": "Single dataset evaluation"
}
```

Repeating this across many papers creates an **evidence database**.

---

# 32. Evidence Matrix

```text
Paper A ──► Dataset ──► Method ──► Result ──► Limitation

Paper B ──► Dataset ──► Method ──► Result ──► Limitation

Paper C ──► Dataset ──► Method ──► Result ──► Limitation

                           │
                           ▼
                    Evidence Matrix
                           │
                           ▼
                        Synthesis
```

---

# 33. Automated Theme Detection

Suppose we collect 500 paper abstracts.

```text
500 Abstracts
      │
      ▼
Embedding Model
      │
      ▼
500 Vectors
      │
      ▼
Clustering Algorithm
      │
      ▼
Groups of Similar Papers
```

Possible groups:

```text
Cluster 1
Machine Learning

Cluster 2
Deep Learning

Cluster 3
Explainable AI

Cluster 4
Privacy

Cluster 5
Cybersecurity
```

These groups can help identify potential literature-review themes.

---

# 34. Topic Modelling

Topic modelling can identify recurring topics across large collections of documents.

Common approaches include:

* Latent Dirichlet Allocation (LDA)
* Non-negative Matrix Factorisation (NMF)
* BERTopic
* Embedding-based clustering

Example:

```text
Papers
  │
  ▼
Text Processing
  │
  ▼
Topic Model
  │
  ├──► Topic 1: AI, neural networks, classification
  │
  ├──► Topic 2: privacy, security, encryption
  │
  └──► Topic 3: users, usability, interfaces
```

---

# 35. Modern Literature Review Tools

| Tool             | Main Purpose                         |
| ---------------- | ------------------------------------ |
| Google Scholar   | Academic search                      |
| Semantic Scholar | Academic search and recommendations  |
| OpenAlex         | Scholarly data and APIs              |
| ResearchRabbit   | Literature discovery                 |
| Connected Papers | Citation-network exploration         |
| Litmaps          | Citation mapping                     |
| Scite            | Citation-context analysis            |
| Consensus        | AI-assisted research search          |
| Elicit           | Search, screening and extraction     |
| SciSpace         | Research-paper analysis              |
| ASReview         | AI-assisted screening                |
| Rayyan           | Systematic-review screening          |
| Covidence        | Systematic-review management         |
| EPPI-Reviewer    | Evidence synthesis                   |
| PaperQA2         | Scientific RAG                       |
| litsearchr       | Search-strategy development          |
| revtools         | Literature screening in R            |
| metagear         | Evidence synthesis and meta-analysis |

---

# 36. OpenAlex

OpenAlex provides a large open scholarly database.

Website:

```text
https://openalex.org/
```

It provides information about:

* Works
* Authors
* Institutions
* Sources
* Topics
* Publishers
* Funders
* Citations

Example IT application:

```text
User Enters Topic
      │
      ▼
OpenAlex API
      │
      ▼
Retrieve Papers
      │
      ▼
Filter by Date
      │
      ▼
Retrieve Abstracts
      │
      ▼
Generate Embeddings
      │
      ▼
Cluster Papers
      │
      ▼
Identify Themes
      │
      ▼
Display Literature Map
```

This could itself become an IT capstone project.

---

# 37. Semantic Scholar API

Semantic Scholar provides APIs for scholarly publications and recommendations.

Possible workflow:

```text
Seed Paper
    │
    ▼
Semantic Scholar API
    │
    ▼
Related Papers
    │
    ▼
Citation Information
    │
    ▼
Recommendation Engine
```

Documentation:

```text
https://api.semanticscholar.org/
```

---

# 38. litsearchr

`litsearchr` is an R package designed to support systematic search-strategy development.

GitHub:

```text
https://github.com/elizagrames/litsearchr
```

Installation:

```r
install.packages("remotes")

remotes::install_github(
  "elizagrames/litsearchr"
)
```

It can create keyword co-occurrence networks.

```text
             machine learning
               /          \
              /            \
          neural           deep
          network        learning
              \            /
               \          /
              classification
```

These relationships can help identify useful search terms.

---

# 39. revtools

`revtools` is an R package for evidence synthesis.

GitHub:

```text
https://github.com/mjwestgate/revtools
```

Installation:

```r
install.packages("revtools")
```

Load:

```r
library(revtools)
```

It supports:

* Importing references.
* Finding duplicates.
* Screening papers.
* Visualising literature.
* Organising evidence.

---

# 40. metagear

`metagear` provides tools supporting systematic review and meta-analysis workflows.

GitHub:

```text
https://github.com/cran/metagear
```

Installation:

```r
install.packages("metagear")
```

Load:

```r
library(metagear)
```

Simplified workflow:

```text
Search
  │
  ▼
Screen
  │
  ▼
Extract
  │
  ▼
Analyse
  │
  ▼
Meta-analysis
```

---

# 41. Scite

Scite helps researchers examine **how papers are cited**.

A paper may have:

```text
500 citations
```

but citation count alone does not indicate whether later research agrees with it.

Conceptually:

```text
Citation
   │
   ├──► Supporting
   │
   ├──► Contrasting
   │
   └──► Mentioning
```

Website:

```text
https://scite.ai/
```

---

# 42. Elicit

Elicit assists with several stages of evidence synthesis.

Typical workflow:

```text
Research Question
      │
      ▼
Find Papers
      │
      ▼
Screen Papers
      │
      ▼
Extract Information
      │
      ▼
Compare Studies
      │
      ▼
Synthesise Evidence
```

Website:

```text
https://elicit.com/
```

---

# 43. Research Software Is Not Research Evidence

A tool may help locate and analyse research, but the **original research paper remains the evidence**.

Example:

```text
AI says:

"Transformers improve accuracy by 15%."

             │
             ▼
Do not immediately use the claim
             │
             ▼
Open the cited paper
             │
             ▼
Check the experiment
             │
             ▼
Check the dataset
             │
             ▼
Check the metric
             │
             ▼
Confirm the reported result
```

---

# 44. Benchmarking Literature Review Software

A system should not be considered reliable simply because its output looks convincing.

Benchmarking compares software against a **gold standard**.

Suppose human reviewers have screened:

```text
1,000 papers
```

and identified:

```text
80 Relevant
920 Irrelevant
```

The AI system can be compared with these human decisions.

---

# 45. Confusion Matrix

|               | Human Relevant | Human Irrelevant |
| ------------- | -------------: | ---------------: |
| AI Relevant   |  True Positive |   False Positive |
| AI Irrelevant | False Negative |    True Negative |

---

# 46. Recall

Recall measures how many relevant papers were successfully identified.

[
Recall = \frac{TP}{TP + FN}
]

High recall is particularly important when missing an important paper could affect the conclusions of the review.

---

# 47. Precision

Precision measures how many papers predicted as relevant were actually relevant.

[
Precision = \frac{TP}{TP + FP}
]

---

# 48. F1 Score

F1 combines precision and recall.

[
F1 =
2 \times
\frac{Precision \times Recall}
{Precision + Recall}
]

---

# 49. Benchmarking Literature Synthesis

Evaluating generated synthesis is more difficult than evaluating classification.

Important evaluation criteria include:

| Measure                 | Question                                       |
| ----------------------- | ---------------------------------------------- |
| Retrieval Recall        | Did the tool find important papers?            |
| Retrieval Precision     | Were retrieved papers relevant?                |
| Extraction Accuracy     | Was information correctly extracted?           |
| Citation Accuracy       | Does the cited paper support the claim?        |
| Citation Completeness   | Are important claims properly referenced?      |
| Hallucination Rate      | Did the model invent information?              |
| Theme Coverage          | Were major themes identified?                  |
| Contradiction Detection | Were conflicting findings identified?          |
| Synthesis Quality       | Were studies compared and integrated?          |
| Reproducibility         | Can another researcher reproduce the workflow? |

---

# 50. SYNERGY Benchmark Dataset

The **SYNERGY dataset** can be used for evaluating systematic-review screening methods.

GitHub:

```text
https://github.com/asreview/synergy-dataset
```

Install:

```bash
pip install synergy-dataset
```

Download datasets:

```bash
python -m synergy_dataset get
```

List datasets:

```bash
synergy_dataset list
```

Possible benchmarking workflow:

```text
Existing Human Labels
       │
       ▼
Run Screening Algorithm
       │
       ▼
Rank Publications
       │
       ▼
Compare AI and Human Labels
       │
       ▼
Calculate Recall
       │
       ▼
Calculate Precision
       │
       ▼
Calculate Work Saved
```

---

# 51. Human-in-the-Loop Literature Review

The preferred approach is:

```text
AI
│
├──► Search Faster
│
├──► Prioritise Papers
│
├──► Extract Information
│
├──► Suggest Themes
│
└──► Generate Preliminary Synthesis

HUMAN
│
├──► Evaluate Sources
│
├──► Check Citations
│
├──► Interpret Evidence
│
└──► Decide Which Conclusions Are Justified
```

AI supports the researcher.

It does not remove researcher responsibility.

---

# 52. Risks of Automated Literature Reviews

## Hallucinated References

AI may generate papers that do not exist.

## Incorrect Citations

A real paper may be cited for a claim it does not support.

## Missing Important Papers

Search systems may fail to retrieve important literature.

## Publication Bias

Published evidence may already contain systematic bias.

## Database Bias

Different scholarly databases have different coverage.

## Recency Bias

Systems may over-prioritise recent research.

## Automation Bias

Users may trust AI-generated information without verification.

## Poor Synthesis

AI may simply summarise papers individually rather than integrate findings.

---

# 53. Good Use of AI

```text
AI Suggestion
      │
      ▼
Researcher Checks Source
      │
      ▼
Researcher Evaluates Methodology
      │
      ▼
Researcher Verifies Results
      │
      ▼
Researcher Integrates Evidence
```

---

# 54. Poor Use of AI

```text
Ask AI a Question
       │
       ▼
Copy Generated Paragraph
       │
       ▼
Submit Assignment
```

Problems include:

* Claims may be incorrect.
* References may not exist.
* Evidence may be misrepresented.
* Important studies may be missing.
* Critical analysis has not been demonstrated.

---

# 55. Recommended Capstone Literature Review Workflow

## Phase 1 — Define

1. Define the project problem.
2. Develop research questions.
3. Define the scope.
4. Identify search concepts.

## Phase 2 — Discover

5. Search multiple academic databases.
6. Use keyword searching.
7. Use semantic searching.
8. Explore citation networks.
9. Collect potentially useful literature.

## Phase 3 — Screen

10. Remove duplicates.
11. Review titles.
12. Review abstracts.
13. Apply inclusion criteria.
14. Apply exclusion criteria.
15. Select papers for full-text review.

## Phase 4 — Analyse

16. Read selected papers.
17. Create annotations.
18. Build an evidence table.
19. Evaluate research quality.
20. Record limitations.

## Phase 5 — Synthesise

21. Group papers into themes.
22. Compare methodologies.
23. Compare datasets.
24. Compare findings.
25. Identify agreements.
26. Identify contradictions.
27. Identify common limitations.
28. Identify research gaps.

## Phase 6 — Write

29. Develop thematic section headings.
30. Develop a logical narrative.
31. Support claims with references.
32. Explain how the literature motivates the project.

## Phase 7 — Validate

33. Check important claims.
34. Check citations.
35. Confirm references exist.
36. Confirm reported numbers.
37. Ensure AI-generated information matches the original source.

---

# 56. Example Literature Review Structure

```markdown
# Literature Review

## 1. Introduction

Explain the topic, research problem, and scope of the review.

## 2. Existing Approaches

Discuss the major approaches used in previous research.

## 3. Theme One

Compare several studies relating to the first major theme.

## 4. Theme Two

Compare several studies relating to the second major theme.

## 5. Current Technologies

Discuss important recent technologies and methodologies.

## 6. Limitations of Existing Work

Identify common weaknesses in previous studies.

## 7. Research Gap

Explain what remains unresolved.

## 8. Relevance to the Proposed Project

Explain how the proposed project addresses the identified gap.

## 9. Summary

Summarise the main conclusions from the literature.
```

---

# 57. From Annotation to Synthesis

## Step 1 — Individual Annotations

```text
Paper A:
Random Forest
89% accuracy
Single dataset

Paper B:
BERT
94% accuracy
High computational cost

Paper C:
BERT
78% accuracy on independent dataset
Poor generalisation
```

## Step 2 — Group the Papers

```text
Theme:
Machine Learning for Phishing Detection
```

## Step 3 — Compare the Papers

```text
A vs B:
BERT performs better on Dataset A.

B vs C:
BERT performance changes substantially across datasets.
```

## Step 4 — Identify the Gap

```text
Few studies investigate cross-dataset generalisation.
```

## Step 5 — Develop the Narrative

> Existing research demonstrates that transformer-based models can outperform conventional machine-learning approaches for phishing detection. However, reported performance varies substantially across datasets. While strong results have been demonstrated on individual benchmark datasets, considerably fewer studies investigate whether these models generalise to independent data. Cross-dataset generalisation therefore represents an important area for further investigation.

---

# 58. Key Difference

A literature review is **not**:

```text
Paper A said this.

Paper B said this.

Paper C said this.
```

A literature review asks:

```text
What do A + B + C collectively tell us?

Where do they agree?

Where do they disagree?

Why might their results differ?

What are their limitations?

What do we still not know?

How does our project address that gap?
```

---

# 59. Role of Modern AI

AI can help researchers:

```text
FIND
  │
  ▼
FILTER
  │
  ▼
ORGANISE
  │
  ▼
EXTRACT
  │
  ▼
COMPARE
  │
  ▼
SYNTHESISE
```

The researcher must still:

```text
VERIFY
  │
  ▼
EVALUATE
  │
  ▼
INTERPRET
  │
  ▼
JUSTIFY
```

---

# 60. Final Takeaway

> **An annotated bibliography describes individual sources.**

> **A literature review connects those sources into an evidence-based narrative.**

> **Literature synthesis compares and integrates evidence across multiple studies.**

> **AI can accelerate literature discovery, screening, extraction, and synthesis, but human validation remains essential.**

 
