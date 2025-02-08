# secure-otp-auth
A Python-based OTP verification system that generates a 6-digit OTP, sends it via email, and validates user input for secure authentication.


🚀 Project Overview
This project implements an OTP (One-Time Password) verification system in Python. The system generates a 6-digit OTP, sends it to the user's email, and validates the input provided by the user. The system ensures secure authentication by allowing a retry option in case of incorrect OTP entry.

📝 Problem Statement
The system performs the following steps:
1️⃣ Generates a random 6-digit OTP.
2️⃣ Sends the OTP to the user’s email address.
3️⃣ Prompts the user to enter the received OTP.
4️⃣ Validates the OTP and grants/denies access accordingly.

📌 Project Features
✅ OTP Generation – Securely generates a random 6-digit OTP.
✅ Email Integration – Simulates sending the OTP via email.
✅ User Prompt – Requests OTP input from the user.
✅ Verification System – Matches the entered OTP with the generated OTP.
✅ Error Handling – Provides user-friendly messages for incorrect OTPs.
✅ Retry Mechanism – Allows the user to retry on incorrect entries.


🛠 Technologies Used
1️⃣ Python
2️⃣ Random Module (for OTP generation)
3️⃣ Smtplib (for email sending simulation
