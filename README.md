Vietnam National High School Exam 2018 – Data Analysis Project

This project analyzes the Vietnam National High School Exam dataset from 2018, which contains scores from more than one million candidates. The goal of the project is to clean and organize the dataset, examine the distribution of scores across subjects, explore statistical characteristics, visualize important patterns, study correlations between subjects, and compute composite scores for several common university admission blocks. The analysis provides a broad overview of student performance and highlights differences across subjects and regions.

The work includes several core steps. Data cleaning and standardization are performed by merging multiple sheets, converting data types, extracting province codes, and handling missing values. Descriptive statistics are calculated for each subject, including mean, median, mode and standard deviation. The analysis also examines score levels, such as the proportion of candidates scoring below one point, above five, above eight or above nine. Score distributions are visualized using histograms, boxplots and density plots. At the provincial level, average scores are aggregated and compared to reveal regional differences. A correlation study is carried out to understand how subjects relate to each other, particularly within natural sciences and social sciences groups. The project also constructs admission block scores such as A00, A01, C00 and D01, followed by exploratory analysis of their distributions.

Two main files are included in this repository. The Python script, exam_scores_2018_analysis.py, contains the entire data processing and analysis workflow. The file vietnam_exam_scores_2018_full_report.pdf provides a complete overview of the findings, including visualizations, summary tables and conclusions.

The project is implemented in Python using Pandas, NumPy, Matplotlib and Jupyter Notebook.

Key Findings

The analysis highlights several noteworthy observations. Score distributions tend to cluster around average levels across most subjects, with relatively few candidates achieving exceptionally high marks. Natural science subjects show stronger correlations with each other compared to social sciences, indicating that performance often aligns with a candidate’s academic strengths. Regional differences are visible in provincial averages, with some provinces consistently performing above the national mean. Admission block scores also vary in competitiveness, particularly in blocks with combinations of high-variance subjects.

Future Improvements

The project can be enhanced by expanding the range of visualizations, adding more advanced statistical tests, and incorporating predictive models to explore performance patterns across provinces or subjects. A comparison across multiple exam years would also provide deeper insight into long-term trends in student performance and educational outcomes.
