User Profile Creation - Web Prototype
Overview
This project is a prototype of a responsive webpage for creating a user profile. It allows users to input personal information, upload a profile picture, and generate a preview of their profile before submission.

This prototype was built as part of the coursework for Software Testing / Web Development.

Features
Core Functionality
Avatar Upload: Drag-and-drop or click to upload, with live circular preview and remove option
Personal Information Form:
Full Name 
Username with validation
Email Address with format validation
Bio with 150 character limit and live counter
Location
Website / Portfolio URL
Role / Profession dropdown (Developer, Designer, Student, Product Manager, etc.)
Skills Tags: Dynamic tag input system - type a skill and press Enter to add, click X to remove
Preferences: Toggle switches for Email Notifications and Public Profile visibility
Form Validation: Real-time visual feedback for required fields and invalid inputs
Success State: Profile summary card/modal after clicking "Create Profile"
UI/UX
Clean, modern design inspired by Linear / Notion / Dribbble
Fully responsive layout (2-column on desktop, stacked on mobile)
Micro-interactions: focus states, hover effects, smooth transitions
Accessible and user-friendly
Tech Stack
HTML5 - Semantic structure
Tailwind CSS (CDN) - Styling and responsive design
Vanilla JavaScript - Interactivity (no frameworks)
FileReader API for avatar preview
Dynamic tag creation
Form validation and character counter
Mock submission handling
Google Fonts - Inter - Typography
No backend or build tools required. Runs directly in the browser.

Project Structure
/user-profile-prototype
├── index.html          # Main prototype file (your artifact)
├── README.md           # This file
└── assets/ (optional)  # Images, icons if you add them
How to Run
Download or clone the repository
Open index.html in any modern browser (Chrome, Edge, Firefox)
No installation needed - Tailwind is loaded via CDN
bash
# If you want to run with a local server (optional)
npx serve .
# or
python -m http.server
How It Works
User enters details in the form on the right
User uploads an avatar on the left - JavaScript shows instant preview using FileReader
Skills are added dynamically to an array and rendered as removable pills
On clicking "Create Profile", JavaScript validates required fields
If valid, a success modal displays a summary card of the entered data
Screenshots
Add your screenshots here:

screenshot-desktop.png - Desktop view
screenshot-mobile.png - Mobile view
screenshot-success.png - Success state
You can take screenshots of the prototype I built for you.

Future Improvements
Connect to backend (Node.js / Firebase / Supabase) for real profile saving
Add password field with show/hide and strength meter
Add social links (LinkedIn, GitHub, Twitter)
Implement localStorage to persist data on refresh
Add dark mode toggle
Add unit tests (Jest) and E2E tests (Cypress)
Convert to React / Next.js component for production
Testing Considerations
For software testing course, you can test:

Functional: Does avatar upload work? Are required fields enforced?
Usability: Is it easy to use on mobile?
Validation: Invalid email, empty name, bio > 150 chars
Compatibility: Works on different browsers
Author
Name: Jones Sepuru
Date: August 2026
Licensed 
