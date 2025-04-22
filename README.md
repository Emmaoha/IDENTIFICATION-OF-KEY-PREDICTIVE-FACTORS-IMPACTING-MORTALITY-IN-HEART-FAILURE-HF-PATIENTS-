# IDENTIFICATION-OF-KEY-PREDICTIVE-FACTORS-IMPACTING-MORTALITY-IN-HEART-FAILURE-HF-PATIENTS

IDENTIFICATION OF KEY PREDICTIVE FACTORS IMPACTING MORTALITY IN HEART FAILURE (HF) PATIENTS DATA 603 – STATISTICAL MODELLING WITH DATA with R

GROUP MEMBERS: Chibuzo Oha, Osei Agyei, Success Attoni, Stephen Anlagyei, and Cecil Oiku 

Most HF patients lack the knowledge on how to manage their lives to reduce the risk of mortality as a result of the disease. Medical practitioners are generally aware of the risk factors impacting mortality in HF patients. However, the knowledge and awareness of how these factors interplay to determine the overall health of the HF patient is still a subject for investigation, irrespective of the studies that abound in this area, given the non-unique solutions to modelling/predictive problems aggravated by the variety of inputs and analysis methods that abound. This study aims to add another data point for reference in the medical profession, thus enriching the information/knowledge base about possible top predictors of mortality in HF patients.
Overview
The overarching drive of the project is to add to the body of knowledge in this area. Thus, arming the medical industry, governments, individuals, and other stakeholders with pertinent information for further research, management of HF patients, management of personal health, etc. as may be necessary.
Goals & Research Questions
The goal of the study is to identify the top predictors of mortality in HF patients in relation to demographic information, vital signs, comorbidities, and properties of the blood measured in the laboratory.
Secondary objective and research questions include:
 What are the major risk indicators with respect to vital signs?
What are the key comorbidities in HF patients and the risk level with age?
What are the major relationships between the comorbidities in HF patients?
Data
The dataset used for this study is the MIMIC-III (Medical Information Mart for Intensive Care III) dataset. It is a large,
freely available database provided by the Massachusetts Institute of Technology (MIT), comprising de-identified health-related data associated with over forty thousand patients who stayed in critical care units (ICUs) of the Beth Israel Deaconess Medical Center between 2001 and 2012. The database includes information such as demographics, vital sign measurements, laboratory test results, mortality, etc. Links to this dataset are provided here:

 MIMIC III Website (https://mimic.mit.edu/docs/iii/ ), and on Kaggle at https://www.kaggle.com/datasets/asjad99/mimiciii
The MIMIC III database was populated with data acquired during routine hospital care. Data was downloaded from several sources, including:

 Archives from critical care information systems,

 Hospital electronic health record databases.

 Social Security Administration Death Master File.

Additional information was collected from hospital and laboratory health record system, including;

 patient demographics and in-hospital mortality.

 laboratory test results (for example, hematology, chemistry, and microbiology results).

 discharge summaries and reports of electrocardiogram and imaging studies.

 billing-related information such as International Classification of Disease, 9th Edition (ICD-9) codes, Diagnosis

Related Group (DRG) codes, and Current Procedural Terminology (CPT) codes.
A subset of this data set consisting of information on patients diagnosed with Heart Failure (HF) was mined from the main dataset and will underpin this project. This subset contains 1176 HF patients before cleaning and 51 features. Details of the features (field names are provided in Appendix 1). All features, but 2 futures (ID and group) were used in the investigation. The dependent variable was “outcome – 1: Dead, 0: Alive”, a categorical variable with 2 levels; hence the deployment of logistic regression.

![R](https://img.shields.io/badge/-R-3776AB?logo=R&logoColor=white&style=flat-square)
