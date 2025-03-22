# Assignment 3: Actionable Items

### Student Details

**Name:** Prayerson Chauhan  
**Student ID:** 8878082

---

## AI Training Data Requirements

This repository documents the key requirements for improving the training data used by the AI system. Each requirement includes detailed assumptions, validation methods, actionable tasks, and defined roles.

## Overview

- 15 Key Requirements
- Tasks assigned to appropriate roles such as Developers, Data Scientists, and Analysts
- Version-controlled updates for tracking and managing improvements

---

### 1. **As a Developer, I want to optimize the web scraping process to ensure data is collected efficiently.**

- **Description:** Improve the efficiency of the web scraping process to reduce the time and computational resources required for data collection.
- **Priority:** High
- **Assumptions & Validation:**
  - The current scraping process takes too long and consumes too many resources.
  - Validation can be done through performance monitoring tools and benchmarks.
- **Tasks:**
  1. Analyze the current scraping script for performance bottlenecks.
  2. Refactor the scraping logic to improve speed.
  3. Test the updated scraping process with large datasets to measure efficiency improvements.
- **Actionability:** This can be assigned to a developer specializing in data scraping and performance optimization.

---

### 2. **As a Data Scientist, I need to ensure that the data collected is balanced and free from biases.**

- **Description:** Implement methods to detect and correct biases in the scraped training data, ensuring balanced representation.
- **Priority:** High
- **Assumptions & Validation:**
  - The data may be imbalanced, leading to biased AI models.
  - Validation will involve analyzing data distribution and identifying underrepresented categories.
- **Tasks:**
  1. Develop algorithms to assess the balance of the dataset.
  2. Apply techniques like oversampling or undersampling to correct data imbalances.
  3. Continuously monitor and adjust data balance during scraping.
- **Actionability:** The data science team can take charge of creating and applying bias detection methods.

---

### 3. **As a Developer, I want to separate questions from answers in the dataset for better training data organization.**

- **Description:** Design a data categorization system to keep training questions separate from answers, as developers need distinct data sets for better model training.
- **Priority:** Medium
- **Assumptions & Validation:**
  - Combining questions and answers may reduce model accuracy.
  - Validation will involve comparing model performance using both combined and separate datasets.
- **Tasks:**
  1. Create a rule-based system or machine learning model to identify and separate questions from answers.
  2. Test and iterate the separation logic to ensure accuracy.
- **Actionability:** This requirement will be handled by a developer in collaboration with data scientists.

---

### 4. **As a Data Engineer, I want to automate the categorization process to ensure efficiency and reduce manual errors.**

- **Description:** Develop an automated categorization pipeline to classify the scraped data into predefined categories without manual intervention.
- **Priority:** High
- **Assumptions & Validation:**
  - Manual categorization is time-consuming and error-prone.
  - Automation will be validated through system tests and comparison of results with manual categorization.
- **Tasks:**
  1. Develop a machine learning model or rule-based algorithm for automatic categorization.
  2. Integrate the automated categorization process into the data scraping pipeline.
- **Actionability:** This task can be assigned to a data engineer with expertise in automation.

---

### 5. **As a Developer, I need to implement data versioning to track changes and ensure data integrity.**

- **Description:** Introduce data versioning to maintain a history of changes to the dataset and facilitate easy rollback if necessary.
- **Priority:** Medium
- **Assumptions & Validation:**
  - Without versioning, it’s difficult to track data changes.
  - Validation can be done through testing rollback scenarios and ensuring data accuracy after reverting to a previous version.
- **Tasks:**
  1. Implement a version control system for the dataset.
  2. Enable tracking of data changes and updates.
  3. Set up regular checkpoints to save versions of the dataset.
- **Actionability:** The data engineering team will manage the implementation of version control for datasets.

---

### 6. **As a Data Scientist, I want to monitor data quality automatically to detect errors in the dataset.**

- **Description:** Develop an automated system that checks for data quality issues such as missing values, duplicates, or inconsistencies.
- **Priority:** Medium
- **Assumptions & Validation:**
  - Data errors can affect model accuracy.
  - This will be validated through error detection metrics and system alerts.
- **Tasks:**
  1. Build an automated data quality checker for common data issues.
  2. Integrate the checker into the data pipeline to run after each scrape.
  3. Set up alerts for critical data quality problems.
- **Actionability:** The data science and engineering teams will collaborate to build this system.

---

### 7. **As a Developer, I need to implement security measures to ensure the safe collection and storage of data.**

- **Description:** Introduce security practices to protect sensitive data during the scraping process and while it’s being stored.
- **Priority:** High
- **Assumptions & Validation:**
  - Data privacy could be compromised during scraping.
  - Validation will be through security audits and testing for potential vulnerabilities.
- **Tasks:**
  1. Apply encryption methods for data storage.
  2. Ensure secure connections for web scraping using HTTPS and authentication.
  3. Conduct regular security audits.
- **Actionability:** The security team, in collaboration with developers, will implement these measures.

---
