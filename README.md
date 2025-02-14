# ALU Regex Data Extraction - JesseWK100 

## Project Overview

This project is a web data extraction tool designed for a private organization. The application aggregates data from hundreds of pages and extracts relevant information using Regular Expressions (regex). The main goal is to validate and extract key data types such as:
- Email addresses
- URLs
- Phone numbers
- Credit card numbers
- Time in 12-hour and 24-hour formats

The project serves as a part of the final assignment for a Junior Full Stack Developer role, demonstrating proficiency in regex, data handling, and code documentation.

## Features

- Email Extraction: Validates common email formats including subdomains and multiple TLDs.
- URL Extraction: Supports both HTTP and HTTPS URLs with optional paths.
- Phone Number Extraction: Handles various phone number formats including parentheses, dashes, dots, and spaces.
- Credit Card Number Extraction: Recognizes numbers separated by spaces or dashes.
- Time Extraction: Validates both 24-hour and 12-hour (AM/PM) time formats.

## Setup Instructions

1. Clone the Repository:
   
   git clone https://github.com/JesseWK100/alu_regex-data-extraction-JesseWK100.git
   cd alu_regex-data-extraction-YourUsername

## Code Documentation & Edge Cases
Code Comments: The source code is thoroughly commented to explain regex choices and logic.

Edge Cases Considered:
Emails: Prevents invalid formats like consecutive dots or missing domain parts.
URLs: Only accepts valid HTTP/HTTPS URLs. Other protocols (e.g., FTP) are excluded.
Phone Numbers: Handles common separators; may need extension for formats without any delimiters.
Credit Card Numbers: Expects proper grouping. Adjustments may be needed for continuous digits.
Times: Ensures that hour and minute values fall within valid ranges.

## Summary & Future Enhancements
This project demonstrates the use of regular expressions for data validation and extraction in a web-based API environment. Future enhancements may include:

Extending regex patterns to handle more variations.
Incorporating unit tests using a framework like pytest.
Integrating the extraction logic into a full-stack web application for dynamic data processing.

## Team Details
Developer: Jesse Kisaale Walusansa
Email: j.walusansa@alustudent.com
Role: Junior Full Stack Developer (Individual Assignment)
