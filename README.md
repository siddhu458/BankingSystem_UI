BankPro — Banking System UI (HTML + CSS)
BankPro is a static Banking Dashboard UI built using HTML and CSS only.
This project includes multiple structured pages such as Account Dashboard, Single Account Details, and Transactions Page with visually rich banking elements such as partner logos, newsletter, service cards, and a responsive layout.

Folder Structure
banking-ui/
│
├── index.html
├── accounts.html
├── single-account.html
├── transactions.html
│
├── assets/
│   ├── css/
│   │   └── style.css
│   └── images/
│       ├── banner.jpg
│       ├── partner1.png
│       ├── partner2.png
│       ├── partner3.png
│       ├── partner4.png
│       └── partner5.png


Pages Overview
index.html
Landing page of the project featuring:
-> Header with logo and navigation
-> Banner with title + subtitle
-> Welcome message and action buttons

accounts.html (Checkpoint 1 — Account Dashboard)
Contains:
-> Header + Banner
-> Account Filters
-> List of Accounts in Grid/Card Format
-> Hover effect that reveals “View Details”
-> Partner banks slider
-> Newsletter section

Services section
Footer
single-account.html (Checkpoint 2 — Account Details Page)
Contains:
-> Header + Banner
-> Account Information Panel
-> Static Action Buttons (Deposit / Withdraw / Transfer / Download Statement)
-> Transaction Table (static)
-> Partner banks, newsletter, services, footer
transactions.html
A simple static page for transaction records (demo-only)

Features Implemented
Feature	Description
Responsive Layout	Designed using CSS grid, flex & media queries
Hover Effects	Card highlight & dynamic button visibility
Newsletter Box	Email subscribe input (non-functional)
Partner Slider	Pure CSS marquee animation for logos
Financial Banner	Finance-themed hero banner
Services Section	3 static service info cards
Footer	Contact details + social icons

How to Run the Project
1. Download/clone the full folder
2. Make sure images are placed correctly under assets/images/
3. Open index.html in your browser

Tip: For best performance, run using a local server (VS Code “Live Server” extension).

Tech Stack
Technology	Purpose
HTML5	Structure
CSS3	Styling & layout
No JavaScript	All interactions are static
Future Enhancements (optional ideas)
Enhancement	Description
Login system	Add authentication using JS / backend
Real API data	Use backend to fetch accounts & transactions
Sorting & search	Make filters functional
Dark mode	Add color theme toggle
Role-based dashboard	Admin / user panels

Credits
Project design & development guide by *Siddhu Chaparthi*
Graphics and icons are generated/created for educational use.
