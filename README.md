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

### 8. **As a Developer, I want the system to scale efficiently to handle large datasets and high traffic.**

- **Description:** Design the system to handle large volumes of data and traffic without performance degradation.
- **Priority:** High
- **Assumptions & Validation:**
  - The system may struggle with large data loads.
  - Scalability will be validated through load testing and performance benchmarks.
- **Tasks:**
  1. Design the data pipeline to handle high traffic and large datasets.
  2. Use cloud solutions or distributed systems for data processing.
  3. Test the system’s performance under heavy loads.
- **Actionability:** This can be handled by a developer specializing in cloud computing and distributed systems.

---

### 9. **As a Developer, I want to ensure compliance with data privacy regulations like GDPR and CCPA.**

- **Description:** Implement features to ensure the system complies with global data privacy regulations to avoid legal issues.
- **Priority:** High
- **Assumptions & Validation:**
  - The system must respect user data privacy.
  - Validation will be done through legal reviews and compliance audits.
- **Tasks:**
  1. Implement consent management features for data collection.
  2. Ensure data anonymization for personal information.
  3. Conduct regular audits for GDPR/CCPA compliance.
- **Actionability:** The legal and development teams will collaborate on ensuring compliance.

---

### 10. **As a Developer, I want to provide real-time updates to the AI training data.**

- **Description:** Implement a system that allows real-time data scraping and updates to the dataset.
- **Priority:** High
- **Assumptions & Validation:**
  - Timely data updates are crucial for training AI models.
  - This will be validated by ensuring that the dataset is updated in real-time without delays.
- **Tasks:**
  1. Develop a real-time data collection mechanism.
  2. Integrate the real-time updates with the existing data pipeline.
  3. Test the system’s ability to handle live data updates.
- **Actionability:** This task can be managed by developers familiar with real-time data processing.

---

### 11. **As a Data Scientist, I need the system to categorize data into multiple predefined categories.**

- **Description:** Improve the data categorization to allow data to be categorized under multiple tags or labels.
- **Priority:** Medium
- **Assumptions & Validation:**
  - The current categorization system is too rigid.
  - Validation will be done through testing multi-tag categorization on sample datasets.
- **Tasks:**
  1. Modify the categorization algorithm to support multi-label classification.
  2. Test and optimize the categorization process for accuracy.
- **Actionability:** This can be handled by the data science team.

---

### 12. **As a Developer, I want to implement automated tests to verify the quality of the scraping process.**

- **Description:** Develop automated unit and integration tests for the scraping process to catch errors early.
- **Priority:** Medium
- **Assumptions & Validation:**
  - Without automated testing, errors in the scraping process can go unnoticed.
  - Validation will be through running tests and confirming no errors occur in scraping.
- **Tasks:**
  1. Write unit tests for scraping logic.
  2. Implement integration tests to ensure data flows correctly through the pipeline.
  3. Set up a continuous integration system to run tests automatically.
- **Actionability:** This task can be handled by developers with testing expertise.

---

### 13. **As a Developer, I want to improve the system’s performance when processing large amounts of scraped data.**

- **Description:** Enhance the system's ability to process large amounts of data quickly and efficiently.
- **Priority:** High
- **Assumptions & Validation:**
  - The system may face performance issues with large datasets.
  - Validation will be done through performance tests and stress testing.
- **Tasks:**
  1. Optimize database queries and data processing algorithms.
  2. Implement batch processing techniques for large datasets.
  3. Test performance with datasets of various sizes.
- **Actionability:** This can be managed by performance engineers and developers.

---

### 14. **As a Developer, I want to implement error logging and monitoring for the scraping system.**

- **Description:** Introduce logging and monitoring to track errors and performance issues in the scraping process.
- **Priority:** Medium
- **Assumptions & Validation:**
  - Without proper logging, it’s difficult to detect and fix errors.
  - Validation will be done by reviewing logs during testing.
- **Tasks:**
  1. Implement logging for scraping errors and warnings.
  2. Set up real-time monitoring tools to alert on critical issues.
  3. Create a dashboard for tracking system performance.
- **Actionability:** This can be assigned to a developer familiar with logging and monitoring tools.

---

### 15. **As a Data Scientist, I want to evaluate the dataset for quality and usability before using it for AI model training.**

- **Description:** Ensure that the data meets high-quality standards and is suitable for use in training AI models.
- **Priority:** High
- **Assumptions & Validation:**
  - Poor-quality data can lead to ineffective AI models.
  - Validation will be done by evaluating the model's performance on the dataset.
- **Tasks:**
  1. Review the dataset for completeness and consistency.
  2. Perform exploratory data analysis (EDA) to detect potential issues.
  3. Implement data cleansing processes where necessary.
- **Actionability:** The data science team will carry out the evaluation and cleansing process.

---
