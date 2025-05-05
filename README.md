# Dialogflow-based Pharmacy Chatbot Project

This repository contains the complete files for the Dialogflow-based pharmacy chatbot project. The chatbot assists customers with medicine inquiries, order placement, delivery requests, order tracking, FAQs, and feedback collection through an NLP-powered interface.

## 📁 Project Structure

├── src/ # All source code files

│ ├── backend/ # PHP scripts, MySQL database schema

│ └── frontend/ # HTML, CSS, JavaScript files

│ └── database/ # SQL dump (.sql file)

├── PPT/ # Final project presentation

│ └── Final_Presentation.pptx

├── Final_Report/ # Final report (FR)

│ └── Final_Report.pdf

├── SRS/ # Software Requirements Specification

│ └── SRS_Document.pdf

├── Design_Document/ # Design document

│ └── Design_Document.pdf

├── README.md # This file



## 🚀 How to Run the Project

### Prerequisites

- PHP >= 7.4
- MySQL/MariaDB
- Apache or any local server (e.g., XAMPP/WAMP)
- Dialogflow account

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/pharmacy-chatbot.git
   cd pharmacy-chatbot
Import the Database:

Go to src/database/

Import the .sql file into your MySQL server using phpMyAdmin or MySQL CLI.

Run the Backend:

Place the src/backend/ folder inside your web server’s root directory (e.g., htdocs for XAMPP).

Ensure your database credentials are correctly set in the backend PHP files.

Run the Frontend:

Open src/frontend/index.html in a browser.

Ensure the backend APIs are connected.

Integrate with Dialogflow:

Create intents in Dialogflow that match your use cases.

Connect webhook fulfillment to your backend API.

🧠 Project Features
Product information retrieval

Product availability check

Order and home delivery request handling

Order tracking and cancellation

FAQ support

Feedback submission

📄 Documents
PPT: Final project presentation

FR: Final report for submission

SRS: Software Requirements Specification

Design Document: System architecture and design overview

👤 Author
Name: BC210203055

vbnet
Copy
Edit
