# BscKI-thesis
Code belonging to my thesis project - CV-Vacancy Matching for Data Scientists 

The implementation consists of 6 different Jupyter Notebooks. 
- Data_Handling: loads the CVs and vacancies used for the project
- Similarity: calculates similarity between various queries, e.g. CV and EDSF
- Competences: loads the EDSF files, creates bag-of-words, calculates similarity lists 
- Extract_career_path: implementation from Maijer (2018); additions are added using #ANOUK or in the cells below. Contains also the implementation of the job elaboration extraction, because this is implemented using the career path implementation
- Vacancy_job_extraction: calculates competence similarities, using the vacancy job implementation 
- Experiment: generates the results as mentioned in the thesis report 

Make sure all notebooks and the corresponding datasets are stored in the same directory. 
