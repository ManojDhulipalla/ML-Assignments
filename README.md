# ML-Assignments

## Table of Contents<!-- omit in toc -->
- [Student Info](#Student Info)
- [Short Description](#short description about assignment)
- [Video Link] (#Video explaining the code logic and flow)

---


## Overview

*sec-teradata-remediation-code* is a Spark Framework repository used by the Heritage Remediation project that reads S/4 Hana data from S3 and writes it to Teradata.

The Heritage Remediation architecture consists of YAML file-driven PySpark jobs that read data from S3, apply transformations (renaming columns, enforcing data types, and adding new columns), and load the data into Teradata tables. These jobs are orchestrated using the Managed Airflow Platform (MAP) and run on persistent EMR clusters via the NGAP platform - refer to the [sec-teradata-remedation-dags](https://github.nike.com/Transactional-Data-Products/sec-teradata-remediation-dags/) repository for Airflow DAG code/documentation.

![Spark Framework](readme-assets/img/spark_framework.png)

For more information, refer to this [Confluence page](https://confluence.nike.com/display/EDAORG/Data+Lifecycle+And+Orchestration).

---

