🏨 Hotel Booking & Multi-Dataset Excel Cleaning<br>
<br>
Tools: Microsoft Excel — Flash Fill, Text to Columns, SUBSTITUTE, TRIM, PROPER, VALUE, FIND, LEFT, IF<br>
Datasets: 4 datasets, 25,000+ total rows cleaned<br>
Goal: Demonstrate real-world Excel data wrangling across multiple raw formats.<br>
<br>
📌 The Challenge<br>
<br>
Real-world data never comes clean. This project cleaned 4 completely different datasets — each with its own messy structure — using Excel's data-wrangling techniques.<br>
<br>
📂 Dataset 1 — Hotel Booking Data (1,030 rows)<br>
<br>
Raw format: All data stored in a single delimited string:<br>
<pre>
B001~Rahul Sharma~Delhi~CheckIn|01-03-26~CheckOut|03-03-26~Guests|2~₹4500~Confirmed
</pre>
<br>
<br>
Cleaned to: Booking ID, Guest Name, City, Check In, Check Out, Guests, Amount, Status<br>
<br>
Functions and tools used:<br>
• FIND to locate delimiters<br>
• LEFT and MID to extract fields<br>
• SUBSTITUTE to remove currency symbols (₹, INR, Rs)<br>
• TRIM to remove extra spaces<br>
• PROPER to standardise name formatting<br>
• VALUE to convert extracted text numbers to numeric form<br>
• Text to Columns for splitting pipe-delimited sections<br>
• Flash Fill for pattern-based extraction<br>
<br>
📂 Dataset 2 — Financial Transactions (14,039 rows)<br>
<br>
Pipe-delimited transaction records with inconsistent amount and label formats.<br>
Cleaned to: Transaction ID, Client Name, Business Type, Status, Amount<br>
<br>
📂 Dataset 3 — Employee Attendance (1,050 rows)<br>
<br>
Pipe-delimited records containing ID, Date, Title, Name, Department, Designation, In Time, Out Time.<br>
Cleaned into structured attendance sheet using Text to Columns and formatting functions.<br>
<br>
📂 Dataset 4 — Monthly Sales Report<br>
<br>
Multi-column format restructured using Pivot Tables and Group by Months for time-series analysis.<br>
<br>
🛠️ Excel Techniques Summary<br>
<br>
• Flash Fill (Ctrl+E) — pattern-based auto extraction<br>
• Text to Columns — splitting values by delimiter<br>
• SUBSTITUTE — removing junk characters and currency symbols<br>
• TRIM + PROPER — cleaning spaces and capitalization<br>
• VALUE — converting text numbers to numeric<br>
• FIND + LEFT/MID — precise extraction using character positions<br>
• IF — conditional classification<br>
• Pivot Tables — summary analysis for each cleaned dataset<br>
• Group by Months — monthly pivot breakdown<br>
• Table Format — dynamic range for all cleaned sheets<br>
<br>
📁 Files in This Repository<br>
<br>
• 205__Hotel_booking_data.xlsx — all 4 datasets (raw + cleaned outputs)<br>
• README.md — documentation<br>
