# Jonathan Jafari, DO

**Clinical & Health Informatics** · Master’s in Applied Health Informatics at Stony Brook University · Long Island, NY

Physician with 8+ years of experience in clinical review, medical research, medical necessity, and inpatient reimbursement appeals. My informatics portfolio brings together healthcare analytics, clinical decision-support prototypes, product ownership, and cloud/database coursework.

**Open to:** Clinical Informatics • Clinical Data Science • Decision-support product roles (remote/hybrid)

[Email](https://mail.google.com/mail/?view=cm&to=jjaf488@gmail.com) · [LinkedIn](https://www.linkedin.com/in/jonathanjafari/)

## Featured Work

### Appeal Assist — Insurance Denial Appeal Prototype
**Role:** Product Owner · **Context:** HHA 502 team project, Stony Brook University · **Status:** Prototype under review

Collaborated on an educational app that helps patients understand a fictional insurance denial and prepare an appeal draft. As Product Owner, led patient-journey mapping, user-story development, and product review. Applied clinical and insurance-appeals experience to assess accuracy, clarity, privacy safeguards, and usability. Conducted desktop and mobile testing and documented improvements for the team.

The application is a team effort. My contribution centers on product direction, requirements, and review. It uses fictional information and does not submit appeals; outstanding review items are documented in the patient journey.

[Try the app](https://claude.ai/artifact/VR9AuDDJbbA6e795AfNhYW) · [Team repository](https://github.com/tareq-stonybrook/vibe_coding) · [Project board](https://github.com/users/tareq-stonybrook/projects/1) · [Patient journey and testing](https://github.com/tareq-stonybrook/vibe_coding/issues/15)

### Sepsis Signals Coordinator
**Context:** Independent research project · **Status:** In progress; initial data exploration completed · **Tools:** Python, DuckDB, Jupyter, MIMIC-IV

Exploring ICU physiologic trajectories to investigate coordinated changes in vital signs and laboratory signals. Completed initial MIMIC-IV v3.1 exploration, queried clinical tables with DuckDB, identified signal definitions, extracted physiologic observations, and built time-aligned vital-sign trajectories.

This work is distinct from the Streamlit sepsis predictor below. Signal coordination and its potential role in clinical workflows remain research questions; clinical performance and utility have not been established. The source repository is private, and MIMIC-IV data are not distributed through this portfolio.

### Sepsis Risk Predictor — Clinician View
**Context:** Independent project · **Status:** Educational prototype · **Tools:** Python, Streamlit, pandas, scikit-learn

Built an interactive Streamlit prototype that estimates sepsis risk from vital signs and laboratory inputs. Combined a calibrated Random Forest model with rule-based alerts and presented risk probabilities, risk tiers, MAP and qSOFA calculations, and suggested next steps in a clinician-facing interface.

Demonstrates model integration and clinical decision-support interface design. Educational prototype only; not for clinical use.

[Repository and setup instructions](https://github.com/jonathanjafari/sepsis_project)

### Healthcare Claims Analysis
**Context:** HHA 507 coursework · **Deliverable:** Documented analysis notebook · **Tools:** Python, pandas, NumPy, Matplotlib, Seaborn

Loaded, cleaned, and combined claim-header, service-line, and diagnosis-code tables. Explored payer distribution, billing providers, diagnoses, procedure codes, service-line complexity, and charges by payer. Documented the workflow and visualized key patterns in a Jupyter notebook.

This is a descriptive analytics project, not a denial-prediction model or evidence of improved reimbursement outcomes.

[Repository and analysis](https://github.com/jonathanjafari/claims-analysis)

### NHANES Health Data Analysis — 2021–2023
**Context:** HHA 507 coursework · **Deliverable:** Statistical analysis notebook · **Tools:** R, Python, pandas, SciPy, statsmodels, Google Colab

Used R to convert SAS transport files and Python to clean, combine, and analyze demographic, behavioral, and health measures. Applied chi-square testing, Welch’s t-test, linear regression, Pearson correlation, and ANOVA, with written interpretations and limitations.

These are unweighted educational analyses of a complex survey, not population-representative estimates or causal findings.

[Repository and analysis](https://github.com/jonathanjafari/nhanes_inferential_2021_23)

### SBU Sports Analytics — Athlete Performance Analysis
**Role:** Team contributor · **Context:** HHA 507, Stony Brook University, 2025 · **Tools:** Python, SQL, pandas, MySQL

Contributed to a team analysis of athlete performance and sensor data. Developed data-exploration queries to examine dataset structure, missing identifiers, athlete and team coverage, and metrics across data sources. Collaborated with Amy Kim on developing and refining rule-based flags for changes in modified Reactive Strength Index (mRSI), jump height, and propulsive net impulse relative to athlete baselines and comparison values.

The team project combines data-quality assessment, visualization, and research-informed performance flags. These are exploratory indicators for review, not validated diagnoses of fatigue or injury risk.

[Team repository](https://github.com/amapuyan/SBU-Sports-Analytics-Project-2025) · [Data exploration contribution](https://github.com/amapuyan/SBU-Sports-Analytics-Project-2025/blob/main/part1_exploration.py) · [Collaborative flagging logic](https://github.com/amapuyan/SBU-Sports-Analytics-Project-2025/blob/main/part4_flags.py)

### Medical Codex Pipeline
**Context:** HHA 507 data-processing coursework · **Tools:** Python, pandas, regex

Developed a pipeline for working with standard clinical code sets, including diagnoses, procedures, laboratory tests, medications, and provider identifiers. Implemented source-specific processors, consistent CSV outputs, code-format validation, and logging. Repository outputs are demonstration samples capped at 100 rows per processor.

[Repository](https://github.com/jonathanjafari/medical-codex-pipeline)

## Cloud, Database & Application Engineering

These projects document hands-on coursework and technical demonstrations. Repository code, screenshots, and walkthroughs are the evidence of work; historical cloud endpoints may no longer be running.

| Project | Work demonstrated | Scope |
|---|---|---|
| [Cloud-Based Sepsis Early Warning Pipeline](https://github.com/jonathanjafari/final_project_sepsis) | Designed a GCP architecture covering ingestion, transformation, storage, and a proposed scoring workflow; documented security and cost considerations. Included a small Flask app that lists Cloud Storage objects when configured. | HHA 504 capstone: architecture design and integration prototype; not an implemented end-to-end prediction pipeline. |
| [Clinical Database Analysis with SQLite and pandas](https://github.com/jonathanjafari/sqlite_pandas_dbs) | Created and populated a clinical database; queried diagnoses, visits, demographics, and missing codes using Python, SQLite, and SQLAlchemy. | Coursework demonstrating SQL, data import, and validation. |
| [Multi-Cloud Serverless Functions](https://github.com/jonathanjafari/504_serverless_functions) | Implemented an educational HbA1c classification API and documented deployment and testing on Azure Functions and Google Cloud Functions. | Serverless API deployment exercise. |
| [MySQL on a VM vs. Managed Cloud SQL](https://github.com/jonathanjafari/HHA504_mysql_vm_vs_managed) | Compared self-managed and managed database setups; implemented Python connectivity demonstrations and documented configuration and operational differences. | HHA 504 database deployment coursework. |
| [Flask Deployment on Google Cloud](https://github.com/jonathanjafari/cloud_vm_networking_flask) | Deployed a basic Flask web app to a VM, configured networking and a firewall rule, and connected a custom domain. | Web deployment and networking exercise. |
| [Virtual Machine Lifecycle on Google Cloud & Oracle Cloud](https://github.com/jonathanjafari/gcp_oci_vm_start) | Documented VM creation, starting, stopping, termination, and cleanup with tutorial videos. | Cloud infrastructure exercise. |

## Additional Training & Visualization

- [Tableau Public visualization and Trailhead coursework](https://github.com/jonathanjafari/tableau_trailhead_basics): created a visualization of television viewership trends and documented training in data storytelling and Tableau’s data model.
- [MongoDB fundamentals](https://github.com/jonathanjafari/mongodb_badge_basics): completed introductory modules and reflected on relational versus document database structures.

## Skills Demonstrated Across These Projects

- **Healthcare and product:** clinical review, medical necessity and appeals, patient-journey mapping, user stories, usability testing, and requirements review.
- **Data and analysis:** Python, pandas, NumPy, SQL, DuckDB, SQLite, MySQL, statistical analysis, data cleaning, and visualization; R for data conversion.
- **Applications and models:** Streamlit, Flask, scikit-learn, and educational decision-support prototypes.
- **Cloud and workflow:** Google Cloud, Azure Functions, Oracle Cloud, SQLAlchemy, Jupyter/Colab, Git/GitHub, and technical documentation.
