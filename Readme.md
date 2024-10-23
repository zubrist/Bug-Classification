# Bug Classification Project

## Overview

The Bug Classification Project aims to develop a robust machine learning model capable of automatically categorizing bug reports into predefined classes. The primary objective is to streamline the bug training process, allowing developers and project managers to focus on critical issues more effectively. By leveraging natural language processing (NLP) techniques and pre-trained models, this project enhances the efficiency of bug management systems.



# json Files

This repository contains documentation and issue tracking for the software project. It includes details on bug descriptions and version release notes.

## Contents

- **bug_descriptions.json**: A compilation of known issues and bugs with descriptions of their impact and expected behavior.
- **testFileforAttampt21.json**: Release notes detailing version history, including release dates and associated issues for each version.

## Bug Descriptions

The `bug_descriptions.json` file lists various bugs affecting the application. Each entry provides a brief description of the issue, including:

1. **Azure Data Import Issues**: Broken links in the Azure data import documentation.
2. **Capacity Insights Calculation**: Incorrect issue counts for Kanban teams when the 'Enhanced capacity distribution' feature is disabled.
3. **Mobile UI Issues**: Navigation bar overlaps with content on mobile devices, hindering usability.
4. **Login Errors**: Intermittent 500 Internal Server Errors affecting user logins.
5. **Input Validation**: The application allows negative values for age, which should be restricted.
6. **Reindexing Performance**: Slowed down full reindex process due to additional operations.
7. **Tooltip Display Issues**: HTML markup is shown in the issue status tooltip during page load.

## Version Release Notes

The `testFileforAttampt21.json` file provides a structured overview of the software's version history, detailing:

- **Version**: The specific version number.
- **Date of Release**: When the version was made available.
- **Issues**: A list of identified issues for each version, including descriptions and fixed versions where applicable.

### Example Entry

```json
{
    "version": "7.0.4",
    "date_of_release": "5 December 2015",
    "issue": [
        {
            "issue id": "JRASERVER-47726",
            "issue_description": "Version 7.0.3 of JIRA is unrecognized by Atlassian Marketplace",
            "fixed_version": "None"
        }
    ]
}
```


## Key Features
- **Bug Classification**: Classifies software bugs into categories (Functional, Usability/Workflow, Security, UI, Performance, Documentation).
- **Model Comparison**: Evaluates the performance of DeBERTaV3 against a supervised Multinomial Naive Bayes model.
- **Statistical Analysis**: Analyzes trends in bug fixing across multiple software releases.



# Step to reproduce the results
- Run the BugClassification.ipynb
- Run the clasifyByTrainning.ipynb
