A SQL project aimed at locating sources of water shortages in different locations in Maji Ndogo

# Maji Ndogo Project
## Overview
The Maji Ndogo Project is a comprehensive initiative aimed at ensuring the sustainability and quality of water resources in underdeveloped regions. The project employs data-driven methodologies to monitor, audit, and report on water quality, as well as the effectiveness of water services across various locations.

## Project Structure
The project is divided into several phases, each focused on different aspects of data management and analysis:

- Data Collection: Field teams gather water quality data from various locations. This data includes subjective quality scores and detailed observations from local residents.

- Data Integration: The collected data is integrated into a central database, where it is organized and linked to relevant tables, such as locations, water sources, and employee assignments.

- Audit and Verification: An independent audit is conducted to verify the integrity of the data. The audit focuses on cross-referencing field data with stored records to ensure accuracy and to detect any discrepancies.

- Analysis and Reporting: Complex queries are developed to analyze the data, identify patterns, and detect any anomalies. Special attention is given to employee performance and the consistency of recorded water quality scores.

- Actionable Insights: The project culminates in actionable recommendations based on the analysis, with the goal of improving water services and ensuring data accuracy.

## Key Features
- Entity-Relationship Diagram (ERD) Analysis: The project includes a detailed ERD analysis to understand the structure and relationships within the database, crucial for linking records accurately.

- Error Detection and Correction: A significant focus is placed on detecting errors in data entry and correcting these to maintain high data integrity(Identifying discrepancies between employee-recorded scores and auditor-verified scores).

- Employee Performance Monitoring: Tracks the performance of individual employees, identifying those who consistently make errors or exhibit suspicious patterns in data recording.

- Corruption Detection: Queries are used to detect potential corruption by analyzing patterns in employee mistakes and cross-referencing them with audits.

## Database Structure
The core tables in the Maji Ndogo Project database include:

- Visits Table: Logs all visits to water locations, including timestamps and employee assignments.
- Water Quality Table: Stores water quality scores and related data.
- Employee Table: Contains information about employees, including their assigned tasks and performance metrics.
- Auditor Report Table: Houses the results of the independent audit, including re-evaluated water quality scores and any observations noted during the audit.

## Getting Started
To begin working with the Maji Ndogo Project:

- Clone the repository: git clone https://github.com/KobbyYawson/Maji-Ndogo-Water-Crises-Project.git
- Establish a connection with the sql file (md_water_services.sql) and run the analysis queries provided in the notebooks (.ipynb) to explore the data and generate reports.
- Review the results and recommendations to understand the current state of water quality and service effectiveness in the target regions.

