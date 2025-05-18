# Hackrx-5
## Overview

This project develops a solution to extract and digitize medical diagnoses from handwritten medical forms, aiming to improve the efficiency and accuracy of claims processing. The system consists of two levels:


Level 1: Recognize, identify, and extract medical diagnoses from handwritten forms, outputting them into an Excel sheet.

Level 2: Implement a post-extraction correction system to identify and fix inaccuracies in the extracted diagnoses.

## Features

Handwritten Text Recognition (Level 1): Identifies and extracts medical diagnoses from images of handwritten medical forms using Optical Character Recognition (OCR).

Data Extraction (Level 1): Outputs extracted diagnoses into an Excel sheet with a predefined format.

Post-Extraction Correction (Level 2): Corrects errors in extracted diagnoses to improve accuracy, particularly for ambiguous handwritten text (e.g., "GPLA / 36wks t 4days").

**Evaluation Metrics:**

Level 1: Fill rate (percentage of cases where a value was found) and accuracy (percentage of correctly extracted values).

Level 2: Accuracy of corrected diagnoses.

