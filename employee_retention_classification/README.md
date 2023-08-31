# Employee Retention Classification

**Note:** The story, all names, characters, and incidents portrayed in this project are **fictitious**. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes.

## :label: Table of Contents (TOC)
- [File/Code Structure](#open_file_folder-filecode-structure)
- [Project Description](#memo-project-description)
- [Data Source](#mag_right-data-source)
- [Summary](#open_book-summary)
- [Result](#dart-result)
- [Tech Stack](#hammer_and_wrench-tech-stack)

---

## :open_file_folder: File/Code Structure

```bash
├── data
│   └── HR_capstone_dataset.csv
├── README.md
└── salifort_motors_capstone_project.ipynb
```

[Back to TOC](#label-table-of-contents-toc)

## :memo: Project Description

Background: Currently, there is a high rate of turnover among Salifort employees. (Note: In this context, turnover data includes both employees who choose to quit their job and employees who are let go). Salifort’s senior leadership team is concerned about how many employees are leaving the company. Salifort strives to create a corporate culture that supports employee success and professional development. Further, the high turnover rate is costly in the financial sense. Salifort makes a big investment in recruiting, training, and upskilling its employees. If Salifort could predict whether an employee will leave the company, and discover the reasons behind their departure, they could better understand the problem and develop a solution.

Goal: Create a classification model that predicts whether an employee leave or stay.

[Back to TOC](#label-table-of-contents-toc)

## :mag_right: Data Sources

Data is provided by the course.

[Back to TOC](#label-table-of-contents-toc)

## :open_book: Summary

1. Imports and Load Data
2. Data Exploration
3. Exploratory Data Analysis
4. Build Model
5. Evaluate Model
6. Model Results
7. Conclusion
8. Next Step

[Back to TOC](#label-table-of-contents-toc)

## :dart: Results

The classification model built performed very well with the following scores:

- Accuracy = 0.96
- Precision = 0.89
- Recall = 0.88
- F1 = 0.89
- ROC AUC = 0.93

The model only misclassified: 46 labels as stay instead of leave and 42 labels as leave instead of stay.

[Back to TOC](#label-table-of-contents-toc)

## :hammer_and_wrench: Tech Stack

Language: Python

Libraries: NumPy, pandas, Matplotlib, Seaborn, scikit-learn

Tool: Jupyter Lab

[Back to TOC](#label-table-of-contents-toc)