1. Introduction

The AI Fashion Stylist is a simple rule-based outfit recommendation system.
The user enters a natural language description of the outfit they want, and the system:

Understands gender (male/female)

Detects style (casual/formal/party)

Generates an outfit recommendation

Optionally shows sample image paths

The system runs in Google Colab.


2. System Requirements
Hardware:

Any computer or laptop with internet access

Software:

Google Chrome / Edge / Firefox

Google Colab (no installation required)

Python Libraries:

Pillow

numpy

(Installed automatically through the notebook.)


How to Start the Application
Step 1 — Open the Project Notebook

Open the file:

AI_Fashion.ipynb


or click the Open in Colab button in your GitHub README.

Step 2 — Run All Cells

In Google Colab:

Click Runtime

Click Run all

The system will load and show:

=== AI Fashion Stylist ===
Type 'exit' to quit.

Step 3 — Enter an Outfit Request

When prompted with:

Describe the outfit you need:


Type a description such as:

“casual outfit for my sister”

“formal outfit for a male”

“party look for a boy”

“female casual university outfit”

Press Enter.

Step 4 — View the Recommendation

The system will display:

Logging information

Predicted category

A recommended outfit description

Optional image file paths

Example:

[11:29:10] Input: casual outfit for my sister
[11:29:10] Predicted: female_casual

RECOMMENDATION:
Female Casual: Wear denim jacket with cotton pants and white sneakers.


Step 5 — Exit the System

Type:

exit

and press Enter.

4. Features Included
✔ Natural Language Input

Users can describe any outfit in simple English.

✔ Gender Detection

The system identifies whether the outfit is for:

male

female

✔ Style Classification

Supported styles:

Casual

Formal

Party

✔ Rule-Based Recommendation

Each category has:

Templates

Outfit items

Optional sample images

✔ Modular Architecture

The system follows a 3-layer software architecture:

Data Layer

Application Layer

Presentation Layer

5. System Workflow

User enters a description

System preprocesses the text

Validator checks if input is valid

Classifier identifies gender + style

Recommendation engine generates outfit

Console prints the final output

6. Troubleshooting
❗ “Image not found”

Images are optional.
The system still works perfectly without images.

❗ Error: module not found

Run all notebook cells from the beginning.

❗ Wrong category detected

Use clearer keywords such as “casual”, “party”, “formal”, “male”, “female”, etc.


7. For Reviewers / Teachers

This project demonstrates:

Basic NLP (rule-based)

Software architecture layering

Data layer abstraction

Console-based user interface

Logging system (traceability)

Organized modular design

These are fully appropriate for a semester-level submission.


Name: Aimen Saeed
Roll Number: 22079  
Degree: BSCS  
Course: Semester Project  
Semester: 7th 


