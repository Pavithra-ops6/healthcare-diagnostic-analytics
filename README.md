Comprehensive Healthcare & Oncology Diagnostic Analytics

Executive Summary
This portfolio project demonstrates advanced Descriptive and Diagnostic Analytics applied to dual clinical datasets: a cardiovascular/metabolic health database and a dermatological oncology dataset. Designed to support data-driven healthcare informatics, this repository showcases a robust, job-ready data analysis workflow—from raw data ingestion and structural profiling to complex cohort segmentation and biometric correlation mapping.

Technical Stack
Language: Python
Data Manipulation: Pandas, NumPy
Statistical Visualization: Seaborn, Matplotlib
Environment: Jupyter Notebook

Analytical Methodology
1.Descriptive Analytics (Data Profiling & Baseline Metrics)
Data Ingestion & Integrity: Imported and validated large-scale datasets, ensuring clean data by screening for null values and duplicate records across 14,000+ combined clinical rows.
Statistical Summarization: Extracted core central tendencies (mean, standard deviation, quartiles) for critical biological markers including Blood Pressure, Sugar Levels, Cholesterol, and Lesion Diameter.
Extremes & Anomaly Detection: Identified critical outliers, such as the top 10 patients with critically elevated Sugar Levels and the bottom 10 patients by BMI.
Demographic Mapping: Visualized foundational population metrics using histograms for Age/Sugar distributions and pie charts for Gender breakdowns.

2.Diagnostic Analytics (Correlation & Cohort Segmentation)
Multivariate Correlation: Engineered correlation matrices and Seaborn `PairGrid` visualizations to quantify and map the mathematical relationships between height, weight, BMI, and vital signs.
Clinical Cohort Filtering: Dynamically sliced the data to isolate specific high-risk subsets, such as:
Patients exhibiting both elevated Cholesterol (>200) and Hypertension (Blood Pressure >140).
Overweight patients (BMI > 25) stratified by their specific clinical diagnosis (Diabetes vs. Heart Disease vs. Normal).
Dermatological patients segmented strictly by the absence or presence of a Family History of skin cancer.
Visual Diagnostics: Plotted targeted scatter plots (e.g., Age vs. Blood Pressure, Cholesterol vs. Diagnosis) and boxplots to visually diagnose how specific biometrics cluster around positive disease classifications.

Key Clinical Insights
Established a clear diagnostic baseline showing that the average Sugar Level for Diabetic patients (214.88) heavily skewed the overall population mean compared to Normal (129.45) and Heart Disease (129.71) cohorts.
Demonstrated that isolating populations by combining multiple risk factors (e.g., high BMI coupled with high Cholesterol) provides a more concentrated view of disease incidence across male and female subgroups.
Mapped the frequency of skin cancer diagnoses against specific physical and genetic markers (Mole Count, Asymmetry, and Family History), providing a statistical foundation for dermatological risk assessment.

Repository Contents

The master Jupyter Notebook containing the end-to-end Python codebase, diagnostic logic, and output visualizations.
Visualizations Directory: Contains exported analytical plots, including Gender demographic pie charts, diagnostic bar charts, and multi-variable scatter plots generated during the EDA phase.
