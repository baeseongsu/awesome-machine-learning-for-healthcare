# Awesome Machine Learning for Healthcare

A curated list of machine learning papers for healthcare, with an emphasis on natural language processing, multimodal learning, electronic health records, medical agents, and clinical AI evaluation.

## Table of Contents

- [Large Language Models](#large-language-models)
- [Medical Agents](#medical-agents)
- [Synthetic Data Generation](#synthetic-data-generation)
- [Data Representation and Predictive Modeling](#data-representation-and-predictive-modeling)
- [Toward a Natural Language Interface for EHRs](#toward-a-natural-language-interface-for-ehrs)
- [Digital Scribing and Clinical Documentation](#digital-scribing-and-clinical-documentation)
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

## Digital Scribing and Clinical Documentation

### Reviews and Perspectives

2018
- [The digital scribe](https://www.nature.com/articles/s41746-018-0066-9) | npj Digital Medicine, 2018

2019
- [Challenges of developing a digital scribe to reduce clinical documentation burden](https://www.nature.com/articles/s41746-019-0190-1) | npj Digital Medicine, 2019

2021
- [The digital scribe in clinical practice: a scoping review and research agenda](https://www.nature.com/articles/s41746-021-00432-5) | npj Digital Medicine, 2021

2024
- [The Utility and Implications of Ambient Scribes in Primary Care](https://ai.jmir.org/2024/1/e57673/) | JMIR AI, 2024

2025
- [Real-World Evidence Synthesis of Digital Scribes Using Ambient Listening and Generative Artificial Intelligence for Clinician Documentation Workflows: Rapid Review](https://ai.jmir.org/2025/1/e76743) | JMIR AI, 2025
- [Beyond human ears: navigating the uncharted risks of AI scribes in clinical practice](https://www.nature.com/articles/s41746-025-01895-6) | npj Digital Medicine, 2025
- [Policy brief: ambient AI scribes and the coding arms race](https://www.nature.com/articles/s41746-025-02272-z) | npj Digital Medicine, 2025

2026
- [Barriers and opportunities of scaling ambient AI scribes for clinical documentation across diverse healthcare settings](https://www.nature.com/articles/s41746-026-02554-0) | npj Digital Medicine, 2026

### Dialogue-to-Note Generation

2020
- [Towards an Automated SOAP Note: Classifying Utterances from Medical Conversations](https://proceedings.mlr.press/v126/schloss20a.html) | MLHC' 20

2021
- [Towards Automating Medical Scribing: Clinic Visit Dialogue2Note Sentence Alignment and Snippet Summarization](https://aclanthology.org/2021.nlpmc-1.2/) | NLP-MC Workshop' 21
- [Generating SOAP Notes from Doctor-Patient Conversations Using Modular Summarization Techniques](https://aclanthology.org/2021.acl-long.384/) | ACL-IJCNLP' 21

2022
- [User-Driven Research of Medical Note Generation Software](https://aclanthology.org/2022.naacl-main.29/) | NAACL' 22

2023
- [An Empirical Study of Clinical Note Generation from Doctor-Patient Encounters](https://aclanthology.org/2023.eacl-main.168/) | EACL' 23

2024
- [Exploring Robustness in Doctor-Patient Conversation Summarization: An Analysis of Out-of-Domain SOAP Notes](https://aclanthology.org/2024.clinicalnlp-1.1/) | ClinicalNLP' 24

2025
- [Evaluation and practical application of prompt-driven ChatGPTs for EMR generation](https://www.nature.com/articles/s41746-025-01472-x) | npj Digital Medicine, 2025
- [Enhancing clinical documentation with voice processing and large language models: a study on the LAOS system](https://www.nature.com/articles/s41746-025-02170-4) | npj Digital Medicine, 2025

2026
- [Generating Synthetic Doctor-Patient Conversations for Long-form Audio Summarization](https://arxiv.org/abs/2604.06138) | arXiv, 2026/04

### Datasets and Benchmarks

2022
- [PriMock57: A Dataset Of Primary Care Mock Consultations](https://aclanthology.org/2022.acl-short.65/) | ACL' 22

2023
- [Aci-bench: a Novel Ambient Clinical Intelligence Dataset for Benchmarking Automatic Visit Note Generation](https://www.nature.com/articles/s41597-023-02487-3) | Scientific Data, 2023
- [Overview of the MEDIQA-Chat 2023 Shared Tasks on the Summarization & Generation of Doctor-Patient Conversations](https://aclanthology.org/2023.clinicalnlp-1.52/) | ClinicalNLP' 23

2025
- [MedSynth: Realistic, Synthetic Medical Dialogue-Note Pairs](https://arxiv.org/abs/2508.01401) | arXiv, 2025/08

### Ambient Scribe Deployment and Evaluation

2024
- [The association between use of ambient voice technology documentation during primary care patient encounters, documentation burden, and provider burnout](https://academic.oup.com/fampra/article/41/2/86/7261607) | Family Practice, 2024
- [The impact of nuance DAX ambient listening AI documentation: a cohort study](https://doi.org/10.1093/jamia/ocae022) | JAMIA, 2024
- [Use of an ambient artificial intelligence tool to improve quality of clinical documentation](https://doi.org/10.1016/j.fhj.2024.100157) | Future Healthcare Journal, 2024
- [Impact of a Digital Scribe System on Clinical Documentation Time and Quality: Usability Study](https://ai.jmir.org/2024/1/e60020/) | JMIR AI, 2024
- [Impact of an Artificial Intelligence-Based Solution on Clinicians' Clinical Documentation Experience: Initial Findings Using Ambient Listening Technology](https://link.springer.com/article/10.1007/s11606-024-08924-2) | Journal of General Internal Medicine, 2024
- [AI-Powered Clinical Documentation and Clinicians' Electronic Health Record Experience: A Nonrandomized Clinical Trial](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2823302) | JAMA Network Open, 2024

2025
- [An evaluation framework for ambient digital scribing tools in clinical applications](https://www.nature.com/articles/s41746-025-01622-1) | npj Digital Medicine, 2025
- [A framework to assess clinical safety and hallucination rates of LLMs for medical text summarisation](https://www.nature.com/articles/s41746-025-01670-7) | npj Digital Medicine, 2025
- [Ambient artificial intelligence scribes: physician burnout and perspectives on usability and documentation burden](https://doi.org/10.1093/jamia/ocae295) | JAMIA, 2025
- [Ambient artificial intelligence scribes: utilization and impact on documentation time](https://doi.org/10.1093/jamia/ocae304) | JAMIA, 2025
- [Clinician Experiences With Ambient Scribe Technology to Assist With Documentation Burden and Efficiency](https://doi.org/10.1001/jamanetworkopen.2024.60637) | JAMA Network Open, 2025
- [Physician Perspectives on Ambient AI Scribes](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2831866) | JAMA Network Open, 2025
- [Use of Ambient AI Scribes to Reduce Administrative Burden and Professional Burnout](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2839542) | JAMA Network Open, 2025
- [Ambient Documentation Technology in Clinician Experience of Documentation Burden and Burnout](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2837847) | JAMA Network Open, 2025
- [Use of an AI Scribe and Electronic Health Record Efficiency](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2839929) | JAMA Network Open, 2025
- [Ambient AI Scribes in Clinical Practice: A Randomized Trial](https://pubmed.ncbi.nlm.nih.gov/41497288/) | NEJM AI, 2025
- [A Pragmatic Randomized Controlled Trial of Ambient Artificial Intelligence to Improve Health Practitioner Well-Being](https://pubmed.ncbi.nlm.nih.gov/41625485/) | NEJM AI, 2025
- [Evaluating clinical AI summaries with large language models as judges](https://www.nature.com/articles/s41746-025-02005-2) | npj Digital Medicine, 2025
- [Ambient AI-assisted clinical documentation in surgical outpatient care: a preliminary study of usability, workflow, and patient experience](https://wjps.bmj.com/content/8/5/e001073) | World Journal of Pediatric Surgery, 2025
- [Ambient Artificial Intelligence Scribes: Learnings after 1 Year and over 2.5 Million Uses](https://catalyst.nejm.org/doi/10.1056/CAT.25.0040) | NEJM Catalyst, 2025

2026
- [Ambient Scribe Technology in Simulated Patient Encounters Across Specialties](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2843515) | JAMA Network Open, 2026
- [Vision-Enabled AI scribes reduce omissions in clinical conversations: evidence from simulated medication histories](https://www.nature.com/articles/s41746-026-02494-9) | npj Digital Medicine, 2026
- [Ambient Artificial Intelligence Scribes and Physician Financial Productivity](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2843524) | JAMA Network Open, 2026
- [Patient attitudes toward ambient artificial intelligence scribes in clinical care: insights from a cross-sectional study](https://doi.org/10.1093/jamia/ocaf218) | JAMIA, 2026
- [Listening to the note: clinician perspectives on ambient artificial intelligence scribes in medical documentation](https://doi.org/10.1093/jamia/ocaf214) | JAMIA, 2026
- [Comparing ambient scribes: a randomized crossover clinical trial addressing ambient scribe technologies' impact on physician burnout](https://doi.org/10.1093/jamia/ocag018) | JAMIA, 2026
- [Impact of an Ambient AI Scribe Among Clinicians and Patients: Real-World Prospective Observational Time-Motion Study](https://medinform.jmir.org/2026/1/e85580/) | JMIR Medical Informatics, 2026
- [Ambient scribe in general practice: a multi-perspective before-after longitudinal mixed-methods study](https://www.nature.com/articles/s41746-026-02454-3) | npj Digital Medicine, 2026
- [Use of AI scribes in UK primary care: a survey of general practitioners](https://www.nature.com/articles/s41746-026-02762-8) | npj Digital Medicine, 2026
- [Rapid Evaluation of Artificial Intelligence Technology Used for Ambient Dictation in Primary Care: Comparing the Quality of Documentation of Artificial Intelligence-Generated and Human-Produced Clinical Notes](https://www.acpjournals.org/doi/10.7326/ANNALS-25-02772) | Annals of Internal Medicine, 2026
- [Changes in Clinician Time Expenditure and Visit Quantity With Adoption of Artificial Intelligence-Powered Scribes: A Multisite Study](https://jamanetwork.com/journals/jama/fullarticle/2847319) | JAMA, 2026

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
