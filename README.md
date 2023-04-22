# Automated_AJCC_Conversion_Safranek
Please see the following document to understand how to use this conversion algorithm: https://drive.google.com/file/d/1mMeKoJ7YdHeBCPnxwMfb94LS8ATNGlqJ/view?usp=sharing

The automated tool is available at:
https://o2gwl8-conrad-safranek.shinyapps.io/ajcc_automated_conversion_safraneketal/ 


This conversion algorithm is outlined in "Automated AJCC Restaging for Oropharyngeal Cancer Research" by Safranek et. al. The algorithm converts human papillomavirus positive (HPV+) oropharyngeal squamous cell carcinoma (OPSCC) pathologically and clinically staged tumor (T), node (N), and metastasis (M) values from 7th to 8th edition American Joint Committee on Cancer (AJCC) staging criteria. It then applies the AJCC 8th edition criteria to convert TNM values to an updated pathological, clinical, and overall final OPSCC stage (see Figure 1 from Safranek et. al. for schematic overview of these steps).

To use this algorithm, upload a comma-separated values (CSV) file with the following columns and column header names, labeled exactly as they are listed in brackets below (e.g. 'record_id').
Record ID [record_id]: Unique identifier for each case (protected health information deidentification instructions included in Instructional PDF linked below).
Clinical Tumor Value [cT]: Tumor value for each case, according to clinical staging AJCC 7th edition criteria.
Clinical Node Value [cN]: Node value for each case, according to clinical staging AJCC 7th edition criteria.
Pathologic Tumor Value [pT]: Tumor value for each case, according to pathological staging AJCC 7th edition criteria.
Pathologic Node Value [pN]: Node value for each case, according to pathological staging AJCC 7th edition criteria.
Metastasis Value [M]: Metastasis value, according to clinical staging AJCC 7th edition criteria.
Number of positive lymph nodes [node_positive_num]: For cases that included a neck dissection, this is the number of lymph nodes that were positive.
