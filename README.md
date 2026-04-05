🏨 Hotel Booking & Multi-Dataset Excel Cleaning

Tools: Microsoft Excel — Flash Fill · Text to Columns · SUBSTITUTE · TRIM · PROPER · VALUE · FIND · LEFT · IF
Datasets: 4 datasets · 25,000+ total rows cleaned
Goal: Demonstrate real-world Excel data wrangling across multiple raw formats

📌 The Challenge

Real-world data never comes clean. This project cleaned 4 completely different datasets — each with its own messy format — using Excel's data wrangling toolkit.

📂 Dataset 1 — Hotel Booking Data (1,030 rows)

Raw format: All data in ONE column as a delimited string:

B001~Rahul Sharma~Delhi~CheckIn|01-03-26~CheckOut|03-03-26~Guests|2~₹4500~Confirmed

Cleaned to: 8 separate columns: Booking ID · Guest Name · City · Check In · Check Out · Guests · Amount · Status

Functions used:

FIND — located delimiter positions
LEFT, MID — extracted each field
SUBSTITUTE — removed unwanted characters (₹, INR, Rs)
TRIM — removed extra spaces
PROPER — standardised name capitalisation
VALUE — converted extracted text numbers to numeric type
Text to Columns — split pipe-delimited sections
Flash Fill — auto-completed pattern-based extractions

📂 Dataset 2 — Financial Transactions (14,039 rows)

Pipe-delimited transaction records with company names, transaction IDs, and amounts in inconsistent formats.

Cleaned to: Transaction ID · Client Name · Business Type · Status · Amount

📂 Dataset 3 — Employee Attendance (1,050 rows)

Pipe-delimited employee records: ID · Date · Title · Name · Department · Designation · In Time · Out Time

📂 Dataset 4 — Monthly Sales Report

Multi-column format restructured with pivot tables and Group by Months for time-series analysis.

🛠️ Excel Techniques Summary

Technique	Used for
Flash Fill (Ctrl+E)	Pattern-based auto-extraction
Text to Columns	Splitting delimiter-separated values
SUBSTITUTE	Removing currency symbols and junk characters
TRIM + PROPER	Cleaning whitespace and capitalisation
VALUE	Converting text-numbers to numeric
FIND + LEFT/MID	Precise character-position extraction
IF	Conditional value assignment
Pivot Tables	Summary analysis on each cleaned dataset
Group by Months	Time-series pivot breakdown
Table Format	Applied to all cleaned outputs for dynamic range

📁 Files in this repo

File	Description
205__Hotel_booking_data.xlsx	All 4 datasets — raw + cleaned sheets
README.md	This file
