# ITPM Assignment 1 – Transliteration Accuracy Testing

## Student Information

* Student Name: UBEYSINGHE U A D I
* Registration Number: IT23611542
* Module: IT3040 – ITPM
* Assignment: Assignment 1 – Option 1


## Project Description

This project tests the accuracy of the Chat Sinhala Transliteration function available at: https://www.pixelssuite.com/chat-translator

The objective is to identify negative test cases where the system fails to correctly convert chat-style Singlish input into Sinhala output.

All test cases are automated using Playwright with Python, and the results are recorded automatically in the provided Excel file.



## Prerequisites

* Python 3.12 (https://www.python.org/downloads/)
* Git (https://git-scm.com/download/win)


## Installation Steps

### Step 1 – Extract zip file

Extract zip file to D:\test_automation


### Step 2 – Install Required Packages

pip install -U pip
pip install playwright openpyxl
playwright install


## How to Run the Automation

python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open



## Expected Output

After execution:

* The Excel file will be automatically updated
* "Actual Output" column will be filled
* "Status" column will show Pass or Fail

Manually complete:

* Singlish input types covered
* Evidence or rationale for the input type covered


## Notes

* Only negative test cases are included for final submission
* Test Case IDs begin with "Neg_"
* The repository is public for lecturer access


## GitHub Repository Link

[https://github.com/dinujaubeysinghe/it23611542]
