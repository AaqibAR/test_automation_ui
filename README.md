# test_automation_ui

Playwright automation script for IT3040 Assignment 1 - Option 2.

## Prerequisites
- Python 3.11 or higher
- Google Chrome browser

## Installation

1. Clone the repository and navigate into it
2. Install dependencies by running:
   pip3 install playwright openpyxl
3. Install browsers:
   playwright install

## Running the Test

python3 image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000

## Results
- The CSV result will be saved in execution_results.csv
- A screenshot will be saved in the results/ folder
