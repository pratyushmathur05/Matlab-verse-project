# Water Usage Tracker
This project tracks water usage for different activities over time, visualizes the data using various charts, and allows users to input daily water consumption for activities like cooking, bathing, laundry, cleaning, and drinking. The application displays summary statistics, such as total and average usage, and provides interactive visualizations like bar charts, line graphs, and pie charts.

# Features
Simulated Water Usage: Automatically generates simulated water usage data for different activities.
User Input: Allows users to input their own water usage data for specific activities.
Data Visualization:
Bar chart showing total water usage by activity.
Line graph displaying water usage trends over time.
Pie chart depicting the proportion of water usage for each activity.
Stack plot visualizing the water usage breakdown over time.
Statistics: Displays total and average water usage for each activity.
User Management: Users can log in to track and manage their water usage data over time.
Technologies Used
Flask: Web framework for building the web application.
Pandas: Data manipulation and analysis library.
NumPy: Essential package for numerical computations.
Matplotlib: Data visualization library for generating various types of charts.
HTML/CSS: For rendering the web interface.

# Setup Instructions
Prerequisites
Make sure you have Python 3.6+ installed along with the following libraries:

bash
Copy code
pip install flask pandas numpy matplotlib
Running the Application
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/water-usage-tracker.git
cd water-usage-tracker
Set the FLASK_APP environment variable:
bash
Copy code
export FLASK_APP=app.py
Run the Flask application:
bash
Copy code
flask run
Open your browser and go to http://127.0.0.1:5000/ to access the application.
Folder Structure
app.py: Main Flask application file.
templates/: Contains HTML templates for rendering pages.
index.html: Main page where water usage data and charts are displayed.
login.html: Login page.
static/: Contains static files like images and generated charts (e.g., bar chart, line graph).
requirements.txt: List of dependencies for the project.
# How to Use
Login: Navigate to the login page and enter a username to start tracking your water usage.
Input Data: On the home page, input your daily water usage for different activities (cooking, bathing, laundry, cleaning, drinking).
View Data: View the updated water usage data in tabular form, along with visualizations for water usage over time.
Visualizations: The system will display bar charts, line graphs, and pie charts based on the input data.
Data Visualization
The following charts are generated based on the input data:

Bar Chart: Displays the total water usage for each activity over the specified time period.

Line Graph: Shows the trend of water usage for each activity over time.

Pie Chart: Displays the proportion of total water usage contributed by each activity.

Stack Plot: Visualizes the cumulative water usage for different activities over time.
