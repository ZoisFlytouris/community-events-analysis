
# Community Events Performance Analysis

## Overview

Analysis of a Small Grants community events dataset tracking 50+ grant-funded events across multiple postcodes. The goal was to clean and validate the data, then use PivotTables and visualisations to identify attendance trends and performance patterns across different event types.

Tools used: Microsoft Excel, PivotTables, Charts

## Dataset

The dataset contains event-level records from the Small Grants 2021 program, including:


- Event type (Community Event, Family Friendly, Music Festival, Art & Culture, Community Awards, etc.)

- Applicant type (Community Group, Registered Charity, Small Business)

- Estimated vs actual number of attendees

- Event status (Held, Planned, Cancelled, Replacement, etc.)

- Location (postcode)

- Face-to-face and paid event flags

Note: Organisation names have been masked in the dataset for privacy.

## Data Cleaning

Before analysis, several data quality issues were identified and addressed:


- Spelling inconsistency: Corrected "Small Bus" to "Small Business" in the Applicant Type column to ensure consistent grouping
- Duplicate records: Identified records sharing the same Application ID but with differing estimated and actual attendance figures. These were retained rather than deleted, as the differing values indicated distinct events or event updates rather than true duplicates
- Blank fields: Several records contained blank values across the columns Event Face to Face, Paid Event, Event Type, and Postcode. As there was no way to reliably infer the correct values, these were left blank rather than filled with assumptions

## Analysis

PivotTables were used to summarise and compare attendance data across event types and applicant categories. Key areas explored:


- Total and average estimated vs actual attendees by event type
Attendance accuracy (how closely actual attendance matched estimates) across event categories
- Performance breakdown by applicant type and postcode
- Event status distribution (how many events were held, cancelled, or replaced)


Findings were visualised using Excel charts to make patterns easier to interpret.

## Key Finding

Community Events recorded the highest total estimated and actual attendance figures across all event types, suggesting they draw the broadest audience within this grants program. Attendance accuracy varied across event types, with some categories consistently over or underestimating turnout.

## Skills Demonstrated


- Data cleaning and validation in Excel
- Judgment-based decisions on ambiguous data (duplicates, blanks)
- PivotTable construction and summarisation
- Data visualisation and interpretation
- Translating raw data into findings suitable for reporting