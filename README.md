EcoTrace: Carbon Footprint Tracker

EcoTrace is a web-based application designed to help individuals estimate their annual carbon footprint based on various lifestyle factors, including home energy, transportation, diet, waste, and consumption habits. It provides a breakdown of emissions by category, tracks historical footprint data, and offers personalized tips for reducing environmental impact.

Features
User Authentication: Simple login and sign-up functionality (client-side storage only).

Interactive Questionnaire: A comprehensive form covering various aspects of daily life that contribute to carbon emissions.

Progress Tracker: A visual progress bar to show questionnaire completion.

Carbon Footprint Calculation: Estimates annual CO2e emissions based on user inputs and predefined emission factors.

Detailed Breakdown: Presents a categorized breakdown of the calculated carbon footprint.

Historical Tracking: Stores and displays a history of calculated footprints, allowing users to monitor their progress over time.

Personalized Eco-Tips: Generates tailored advice and suggestions to help users reduce their environmental impact, specifically considering an Asia Pacific context.

Responsive Design: Optimized for various screen sizes, from mobile to desktop.

Data Visualization: Utilizes Chart.js to display carbon footprint breakdown and historical data visually.

Technologies Used
HTML5: For the basic structure of the web application.

CSS3 (Tailwind CSS): For modern, responsive, and aesthetically pleasing styling. Tailwind CSS is used via its CDN.

JavaScript (ES6+): For all interactive elements, form handling, carbon footprint calculations, data storage, and chart rendering.

Chart.js: A powerful JavaScript library for creating interactive charts and graphs.

How to Set Up and Run Locally
This project is a single HTML file, making it very easy to set up and run.

Save the file: Save the provided code as an .html file (e.g., index.html).

Open in Browser: Simply open the index.html file in your preferred web browser.

That's it! The application runs entirely client-side.

Usage
Authentication:

Sign Up: If you're a new user, click "Sign Up" to create an account with a username and password.

Login: Use your created credentials to log in. Your login status is maintained in sessionStorage.

Questionnaire:

Once logged in, you'll be directed to the "Questionnaire" section.

Fill in all the required fields accurately to get the most precise carbon footprint estimate.

The progress bar at the top will indicate your completion.

Calculate Footprint:

Click the "Calculate My Footprint" button at the bottom of the questionnaire.

Results:

The "Results" section will display your estimated annual carbon footprint in tonnes of CO2e.

View a breakdown of your emissions by category in a bar chart.

See your historical footprint data in a line chart, compared against the Asia Pacific average.

Read personalized eco-tips generated based on your inputs.

Navigation:

Use the tabs at the top to switch between "Authentication," "Questionnaire," and "Results" sections.

Click "Recalculate / Start Again" on the results page to clear your inputs and re-do the questionnaire.

Click "Logout" to end your session.

Data Storage
User Accounts: Usernames and passwords are stored locally in your browser's localStorage for demonstration purposes.

Carbon Footprint Data: Your most recent carbon footprint calculation and historical data are stored in sessionStorage (for the current session) and localStorage (for historical tracking across sessions for a logged-in user).

Note: Since data is stored in localStorage and sessionStorage, it is client-side and not persistent across different browsers or devices. This application is intended for personal tracking and demonstration.

Contributing
As this is a self-contained single-file project, direct contributions via pull requests might be limited. However, feel free to fork the repository and adapt it for your needs. If you find any bugs or have suggestions for improvements, please open an issue!
