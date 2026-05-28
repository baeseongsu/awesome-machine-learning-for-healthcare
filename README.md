# Awesome Machine Learning for Healthcare

A curated list of machine learning papers for healthcare, with an emphasis on natural language processing, multimodal learning, electronic health records, medical agents, and clinical AI evaluation.

## Table of Contents

- [Large Language Models](#large-language-models)
- [Medical Agents](#medical-agents)
- [Synthetic Data Generation](#synthetic-data-generation)
- [Data Representation and Predictive Modeling](#data-representation-and-predictive-modeling)
- [Toward a Natural Language Interface for EHRs](#toward-a-natural-language-interface-for-ehrs)
- [Fact Checking](#fact-checking)
- [Medical Imaging](#medical-imaging)
- [Multimodal Large Language Models](#multimodal-large-language-models)

## Large Language Models

2022
- [MedMCQA: A Large-scale Multi-Subject Multi-Choice Dataset for Medical domain Question Answering](https://proceedings.mlr.press/v174/pal22a.html) | CHIL' 22

2023
- [Med-HALT: Medical Domain Hallucination Test for Large Language Models](https://aclanthology.org/2023.conll-1.21/) | CoNLL' 23
- [MEDITRON-70B: Scaling Medical Pretraining for Large Language Models](https://arxiv.org/abs/2311.16079) | arXiv, 2023/11

2024
- [Health-LLM: Large Language Models for Health Prediction via Wearable Sensor Data](https://proceedings.mlr.press/v248/kim24b.html) | CHIL' 24
- [K-QA: A Real-World Medical Q&A Benchmark](https://aclanthology.org/2024.bionlp-1.22/) | BioNLP' 24
- [Small language models learn enhanced reasoning skills from medical textbooks](https://www.nature.com/articles/s41746-025-01653-8) | npj Digital Medicine, 2025
- [Hippocrates: An Open-Source Framework for Advancing Large Language Models in Healthcare](https://openreview.net/forum?id=nSIEwsIT6r) | NeurIPS GenAI4Health Workshop' 24
- [MedReadMe: A Systematic Study for Fine-grained Sentence Readability in Medical Domain](https://aclanthology.org/2024.emnlp-main.958/) | EMNLP' 24

## Medical Agents

2023
- [MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning](https://aclanthology.org/2024.findings-acl.33/) | Findings of ACL' 24

2024
- [AI Hospital: Benchmarking Large Language Models in a Multi-agent Medical Interaction Simulator](https://aclanthology.org/2025.coling-main.680/) | COLING' 25
- [AgentMD: Empowering language agents for risk prediction with large-scale clinical tool learning](https://www.nature.com/articles/s41467-025-64430-x) | Nature Communications, 2025
- [MDAgents: An Adaptive Collaboration of LLMs for Medical Decision-Making](https://proceedings.neurips.cc/paper_files/paper/2024/hash/90d1fc07f46e31387978b88e7e057a31-Abstract-Conference.html) | NeurIPS' 24
- [Agent Hospital: A Simulacrum of Hospital with Evolvable Medical Agents](https://arxiv.org/abs/2405.02957) | arXiv, 2024/05
- [AgentClinic: a multimodal benchmark for tool-using clinical AI agents](https://www.nature.com/articles/s41746-026-02674-7) | npj Digital Medicine, 2026
- [DrHouse: An LLM-empowered Diagnostic Reasoning System through Harnessing Outcomes from Sensor Data and Expert Knowledge](https://doi.org/10.1145/3699765) | IMWUT, 2024
- [ClinicalLab: Aligning Agents for Multi-Departmental Clinical Diagnostics in the Real World](https://papers.neurips.cc/paper_files/paper/2025/hash/6a059625a6027aca18302803743abaa2-Abstract-Datasets_and_Benchmarks_Track.html) | NeurIPS Datasets and Benchmarks' 25
- [MMedAgent: Learning to Use Medical Tools with Multi-modal Agent](https://aclanthology.org/2024.findings-emnlp.510/) | Findings of EMNLP' 24
- [MEDCO: Medical Education Copilots Based on a Multi-agent Framework](https://doi.org/10.1007/978-3-031-91813-1_8) | ECCV Workshops' 24
- [Interactive Agents: Simulating Counselor-Client Psychological Counseling via Role-Playing LLM-to-LLM Interactions](https://arxiv.org/abs/2408.15787) | arXiv, 2024/08

## Synthetic Data Generation

2010
- [Data-driven approach for creating synthetic electronic medical records](https://doi.org/10.1186/1472-6947-10-59) | BMC Medical Informatics and Decision Making, 2010

2017
- [Generating Multi-label Discrete Patient Records using Generative Adversarial Networks](https://proceedings.mlr.press/v68/choi17a.html) | MLHC' 17

2023
- [EHRDiff: Exploring Realistic EHR Synthesis with Diffusion Models](https://openreview.net/forum?id=DIGkJhGeqi) | TMLR, 2024
- [Synthesize high-dimensional longitudinal electronic health records via hierarchical autoregressive language model](https://www.nature.com/articles/s41467-023-41093-0) | Nature Communications, 2023
- [EHR-Safe: generating high-fidelity and privacy-preserving synthetic electronic health records](https://www.nature.com/articles/s41746-023-00888-7) | npj Digital Medicine, 2023
- [LLMSYN: Generating Synthetic Electronic Health Records Without Patient-Level Data](https://proceedings.mlr.press/v252/hao24a.html) | MLHC' 24

## Data Representation and Predictive Modeling

2022
- [GenHPF: General Healthcare Predictive Framework for Multi-Task Multi-Source Learning](https://doi.org/10.1109/JBHI.2023.3327951) | IEEE JBHI, 2024

2024
- [REALM: RAG-Driven Enhancement of Multimodal Electronic Health Records Analysis via Large Language Models](https://arxiv.org/abs/2402.07016) | arXiv, 2024/02
- [EMERGE: Enhancing Multimodal Electronic Health Records Predictive Modeling with Retrieval-Augmented Generation](https://doi.org/10.1145/3627673.3679582) | CIKM' 24
- [EHRmonize: A Framework for Medical Concept Abstraction from Electronic Health Records using Large Language Models](https://doi.org/10.1007/978-3-031-82007-6_20) | AMAI Workshop @ MICCAI' 24

### Multimodal Representation Learning

2022
- [MedFuse: Multi-modal fusion with clinical time-series data and chest X-ray images](https://proceedings.mlr.press/v182/hayat22a.html) | MLHC' 22

2023
- [Learning Missing Modal Electronic Health Records with Unified Multi-modal Data Embedding and Modality-Aware Attention](https://proceedings.mlr.press/v219/lee23a.html) | MLHC' 23

2024
- [From Basic to Extra Features: Hypergraph Transformer Pretrain-then-Finetuning for Balanced Clinical Predictions on EHR](https://proceedings.mlr.press/v248/xu24a.html) | CHIL' 24
- [FlexCare: Leveraging Cross-Task Synergy for Flexible Multimodal Healthcare Prediction](https://doi.org/10.1145/3637528.3671974) | KDD' 24
- [MEDFuse: Multimodal EHR Data Fusion with Masked Lab-Test Modeling and Large Language Models](https://doi.org/10.1145/3627673.3679962) | CIKM' 24
- [Multimodal Patient Representation Learning with Missing Modalities and Labels](https://openreview.net/forum?id=Je5SHCKpPa) | ICLR' 24

## Toward a Natural Language Interface for EHRs

2015
- [Toward a Natural Language Interface for EHR Questions](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4525248/) | AMIA' 15

2016
- [Annotating Logical Forms for EHR Questions](https://aclanthology.org/L16-1598/) | LREC' 16

2017
- [A Semantic Parsing Method for Mapping Clinical Questions to Logical Forms](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5977685/) | AMIA' 17

2018
- [emrQA: A Large Corpus for Question Answering on Electronic Medical Records](https://aclanthology.org/D18-1258/) | EMNLP' 18

2019
- [Text-to-SQL Generation for Question Answering on Electronic Medical Records](https://doi.org/10.1145/3366423.3380120) | WWW' 20
- [Using FHIR to Construct a Corpus of Clinical Questions Annotated with Logical Forms and Answers](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7153115/) | AMIA' 19

2020
- [Dataset and Enhanced Model for Eligibility Criteria-to-SQL Semantic Parsing](https://aclanthology.org/2020.lrec-1.714/) | LREC' 20
- [Paraphrasing to improve the performance of Electronic Health Records Question Answering](https://pubmed.ncbi.nlm.nih.gov/32477685/) | AMIA' 20
- [Knowledge Graph-based Question Answering with Electronic Health Records](https://proceedings.mlr.press/v149/park21a.html) | MLHC' 21

2021
- [emrKBQA: A Clinical Knowledge-Base Question Answering Dataset](https://aclanthology.org/2021.bionlp-1.7/) | BioNLP' 21
- [Question Answering for Complex Electronic Health Records Database using Unified Encoder-Decoder Architecture](https://proceedings.mlr.press/v158/bae21a.html) | ML4H' 21

2022
- [Uncertainty-Aware Text-to-Program for Question Answering on Structured Electronic Health Records](https://proceedings.mlr.press/v174/kim22a.html) | CHIL' 22
- [DrugEHRQA: A Question Answering Dataset on Structured and Unstructured Electronic Health Records For Medicine Related Queries](https://aclanthology.org/2022.lrec-1.117/) | LREC' 22
- [Learning to Ask Like a Physician](https://aclanthology.org/2022.clinicalnlp-1.8/) | ClinicalNLP' 22
- [RadQA: A Question Answering Dataset to Improve Comprehension of Radiology Reports](https://aclanthology.org/2022.lrec-1.672/) | LREC' 22

2023
- [EHRSQL: A Practical Text-to-SQL Benchmark for Electronic Health Records](https://proceedings.neurips.cc/paper_files/paper/2022/hash/643e347250cf9289e5a2a6c1ed5ee42e-Abstract-Datasets_and_Benchmarks.html) | NeurIPS Datasets and Benchmarks' 22 | [Code](https://github.com/glee4810/EHRSQL)
- [LeafAI: query generator for clinical cohort discovery rivaling a human programmer](https://doi.org/10.1093/jamia/ocad149) | JAMIA, 2023
- [Toward a Neural Semantic Parsing System for EHR Question Answering](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10148366/) | AMIA' 23
- [quEHRy: a question answering system to query electronic health records](https://doi.org/10.1093/jamia/ocad050) | JAMIA, 2023
- [ECG-QA: A Comprehensive Question Answering Dataset Combined With Electrocardiogram](https://proceedings.neurips.cc/paper_files/paper/2023/hash/d0b67349dd16b83b2cf6167fb4e2be50-Abstract-Datasets_and_Benchmarks.html) | NeurIPS Datasets and Benchmarks' 23
- [MedAlign: A Clinician-Generated Dataset for Instruction Following with Electronic Medical Records](https://ojs.aaai.org/index.php/AAAI/article/view/30205) | AAAI' 24
- [Adapted large language models can outperform medical experts in clinical text summarization](https://doi.org/10.1038/s41591-024-02855-5) | Nature Medicine, 2024
- [Question Answering for Electronic Health Records: Scoping Review of Datasets and Models](https://doi.org/10.2196/53636) | JMIR, 2024
- [EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images](https://proceedings.neurips.cc/paper_files/paper/2023/hash/0c007ebef1d11fd48da6ce4f54687db6-Abstract-Datasets_and_Benchmarks.html) | NeurIPS Datasets and Benchmarks' 23 | [Code](https://github.com/baeseongsu/ehrxqa) | [PhysioNet](https://physionet.org/content/ehrxqa/1.0.0/)

2024
- [EHRAgent: Code Empowers Large Language Models for Few-shot Complex Tabular Reasoning on Electronic Health Records](https://aclanthology.org/2024.emnlp-main.1245/) | EMNLP' 24 | [Code](https://github.com/wshi83/EhrAgent)
- [EHRNoteQA: An LLM Benchmark for Real-World Clinical Practice Using Discharge Summaries](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e15c4afff22f12c4986c1fcb4e941e03-Abstract-Datasets_and_Benchmarks_Track.html) | NeurIPS Datasets and Benchmarks' 24 | [Code](https://github.com/ji-youn-kim/ehrnoteqa) | [PhysioNet](https://physionet.org/content/ehr-notes-qa-llms/1.0.0/)
- [A dataset and benchmark for hospital course summarization with adapted large language models](https://doi.org/10.1093/jamia/ocae312) | JAMIA, 2025

## Fact Checking

2020
- [Explainable Automated Fact-Checking for Public Health Claims](https://aclanthology.org/2020.emnlp-main.623/) | EMNLP' 20 | [Code](https://github.com/neemakot/Health-Fact-Checking)

2021
- [Evidence-based Fact-Checking of Health-related Claims](https://aclanthology.org/2021.findings-emnlp.297/) | Findings of EMNLP' 21 | [Code](https://github.com/sarrouti/healthver)

2024
- [HealthFC: Verifying Health Claims with Evidence-Based Medical Fact-Checking](https://aclanthology.org/2024.lrec-main.709/) | LREC-COLING' 24 | [Code](https://github.com/jvladika/HealthFC)
- [DOSSIER: Fact Checking in Electronic Health Records while Preserving Patient Privacy](https://proceedings.mlr.press/v252/zhang24a.html) | MLHC' 24 | [Code](https://github.com/amazon-science/DOSSIER)
- [EHRCon: Dataset for Checking Consistency between Unstructured Notes and Structured Tables in Electronic Health Records](https://proceedings.neurips.cc/paper_files/paper/2024/hash/a291dad965af9bc2e39ffeb2ca1c6dc0-Abstract-Datasets_and_Benchmarks_Track.html) | NeurIPS Datasets and Benchmarks' 24 | [Code](https://github.com/dustn1259/EHRCon) | [PhysioNet](https://physionet.org/content/ehrcon-consistency-of-notes/1.0.1/)
- [FactCheXcker: Mitigating Measurement Hallucinations in Chest X-ray Report Generation Models](https://openaccess.thecvf.com/content/CVPR2025/html/Heiman_FactCheXcker_Mitigating_Measurement_Hallucinations_in_Chest_X-ray_Report_Generation_Models_CVPR_2025_paper.html) | CVPR' 25 | [Code](https://github.com/rajpurkarlab/FactCheXcker)

2025
- [VeriFact: Verifying Facts in LLM-Generated Clinical Text with Electronic Health Records](https://arxiv.org/abs/2501.16672) | arXiv, 2025/01 | [Code](https://github.com/philipchung/verifact) | [PhysioNet](https://physionet.org/content/mimic-iii-ext-verifact-bhc/1.0.0/)

## Medical Imaging

### Medical Imaging Datasets

2019
- [MIMIC-CXR-JPG, a large publicly available database of labeled chest radiographs](https://arxiv.org/abs/1901.07042) | arXiv, 2019/01
- [MIMIC-CXR, a de-identified publicly available database of chest radiographs with free-text reports](https://www.nature.com/articles/s41597-019-0322-0) | Scientific Data, 2019

2023
- [Towards long-tailed, multi-label disease classification from chest X-ray: Overview of the CXR-LT challenge](https://www.sciencedirect.com/science/article/pii/S136184152400149X) | Medical Image Analysis, 2024

2024
- [Generalist foundation models from a multimodal dataset for 3D computed tomography](https://www.nature.com/articles/s41551-025-01599-y) | Nature Biomedical Engineering, 2026
- [Development of a large-scale grounded vision language dataset for chest CT analysis](https://www.nature.com/articles/s41597-025-05922-9) | Scientific Data, 2025
- [Shadow and Light: Digitally Reconstructed Radiographs for Disease Classification](https://arxiv.org/abs/2406.03688) | arXiv, 2024/06
- [MedTrinity-25M: A Large-scale Multimodal Dataset with Multigranular Annotations for Medicine](https://openreview.net/forum?id=IwgmgidYPS) | ICLR' 25

### Radiology Report Generation

2020
- [Combining Automatic Labelers and Expert Annotations for Accurate Radiology Report Labeling Using BERT](https://aclanthology.org/2020.emnlp-main.117/) | EMNLP' 20

2021
- [RadGraph: Extracting Clinical Entities and Relations from Radiology Reports](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/hash/c8ffe9a587b126f152ed3d89a146b445-Abstract-round1.html) | NeurIPS Datasets and Benchmarks' 21

2023
- [RadGraph2: Modeling Disease Progression in Radiology Reports via Hierarchical Information Extraction](https://proceedings.mlr.press/v219/khanna23a.html) | MLHC' 23
- [Evaluating progress in automatic chest X-ray radiology report generation](https://doi.org/10.1016/j.patter.2023.100802) | Patterns, 2023
- [Radiology-Aware Model-Based Evaluation Metric for Report Generation](https://arxiv.org/abs/2311.16764) | arXiv, 2023/11

2024
- [CheXagent: Towards a Foundation Model for Chest X-Ray Interpretation](https://openreview.net/forum?id=P3LOmrZWGR) | AAAI SSS Clinical FMs' 24
- [Evaluating GPT-4V (GPT-4 with Vision) on Detection of Radiologic Findings on Chest Radiographs](https://pubs.rsna.org/doi/10.1148/radiol.233270) | Radiology, 2024
- [LLM-RadJudge: Achieving Radiologist-Level Evaluation for X-Ray Report Generation](https://arxiv.org/abs/2404.00998) | arXiv, 2024/04
- [Dr-LLaVA: Visual Instruction Tuning with Symbolic Clinical Grounding](https://nips.cc/virtual/2024/106640) | NeurIPS MAR Workshop' 24
- [GREEN: Generative Radiology Report Evaluation and Error Notation](https://aclanthology.org/2024.findings-emnlp.21/) | Findings of EMNLP' 24

## Multimodal Large Language Models

2024
- [MediConfusion: Can you trust your AI radiologist? Probing the reliability of multimodal medical foundation models](https://openreview.net/forum?id=H9UnNgdq0g) | ICLR' 25
- [MMed-RAG: Versatile Multimodal RAG System for Medical Vision Language Models](https://openreview.net/forum?id=s5epFPdIW6) | ICLR' 25

2025
- [GMAI-VL-R1: Harnessing Reinforcement Learning for Multimodal Medical Reasoning](https://arxiv.org/abs/2504.01886) | arXiv, 2025/04
- [Systematic Evaluation of Large Vision-Language Models for Surgical Artificial Intelligence](https://arxiv.org/abs/2504.02799) | arXiv, 2025/04
