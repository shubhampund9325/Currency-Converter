Currency Converter

Currency Converter is a web application designed to provide users with real-time currency conversion rates. It supports multiple currencies and offers an intuitive interface for quick and easy conversions.

Features
	•	Real-Time Conversion: Fetches the latest exchange rates for accurate conversions.
	•	Multiple Currency Support: Convert between various global currencies.
	•	Responsive Design: Optimized for both desktop and mobile devices.
	•	User-Friendly Interface: Clean and easy-to-navigate design.

Tech Stack
	•	Frontend: HTML, CSS, JavaScript
	•	Backend: Node.js with Express.js
	•	API: Exchange rate data fetched from a third-party API (e.g., Open Exchange Rates or Fixer.io)

Installation

Prerequisites
	•	Node.js installed on your system

Steps
	1.	Clone the repository:

git clone https://github.com/shubhampund9325/Currency-Converter.git  


	2.	Navigate to the project directory:

cd Currency-Converter  


	3.	Install dependencies:

npm install  


	4.	Set up environment variables:
Create a .env file in the root directory and configure the following:

API_KEY=your_currency_api_key  
PORT=5000  


	5.	Start the server:

npm start  


	6.	Open your browser and navigate to http://localhost:5000 to use the application.

Project Structure

Currency-Converter/  
├── public/          # Static files (HTML, CSS, JS)  
├── routes/          # API routes  
├── .env             # Environment configuration (not included in GitHub)  
├── server.js        # Main server file  
└── README.md        # Project documentation  

Future Enhancements
	•	Add support for historical currency data.
	•	Include charts for visual representation of exchange rates.
	•	Allow users to save favorite currency pairs.
	•	Integrate offline mode for recent conversion data.



Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests for review.

Contact

For any queries, reach out to:
Shubham
GitHub: shubhampund9325
