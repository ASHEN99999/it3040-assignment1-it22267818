Transliteration Accuracy Testing – IT3040 Assignment
Project Description

This project tests the accuracy of the Chat Sinhala transliteration feature available at:
https://www.pixelssuite.com/chat-translator

Prerequisites
Python 3.11 or above
Google Chrome
Installation Steps

pip install -U pip
pip install playwright openpyxl
playwright install

How to Run

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator"

Notes
The Excel file contains 50 negative test cases.
The script automatically fills Actual Output and Status.
