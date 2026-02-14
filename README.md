# Advanced Email Slicer Program (Python)

## Description
The Advanced Email Slicer Program is a Python-based utility that analyzes an email address and extracts meaningful components from it. The program validates the email format using regular expressions and then separates the email into its username, domain, domain name, and extension. This project demonstrates clean coding practices, input validation, and string manipulation in Python.

## Features
- Validates email format using regular expressions
- Extracts username from the email address
- Identifies full domain, domain name, and extension
- Handles multi-level domains such as .edu or .co.in
- Uses a modular, function-based structure
- Provides clear and readable console output

## Technologies Used
- Python 3
- Regular Expressions (re module)

## How It Works
1. The user inputs an email address.
2. The program validates the input using a regex pattern.
3. If valid, the email is split into:
   - Username
   - Full domain
   - Domain name
   - Extension
4. The extracted details are displayed in a structured format.
5. If invalid, an error message is shown.

## Example Input
student.ai@university.edu

## Example Output
Username: student.ai  
Domain: university.edu  
Domain Name: university  
Extension: edu  

## Project Structure
email_slicer.py  
README.md  

## How to Run
1. Ensure Python 3 is installed on the system.
2. Save the program as `email_slicer.py`.
3. Open a terminal or command prompt.
4. Run the program using:
   python email_slicer.py
5. Enter an email address when prompted.

## Use Cases
- Beginner to intermediate Python practice
- Understanding regex-based validation
- Mini project for portfolios or academic submissions
- Foundation for larger email-processing applications

## Future Enhancements
- Email provider detection
- GUI implementation using Tkinter
- Export results to CSV or JSON
- Batch processing of multiple emails
- Command-line arguments support

## Author
Himani Hassija
