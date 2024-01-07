# Calorie Counter

## Introduction
Calorie Counter is a Flask-based web application designed to help users track their daily calorie intake. The application allows users to add food entries, view a summary of their calorie consumption, and visualize their data through charts and tables.

## Features
- Add food entries with calorie counts.
- View all food entries in a tabular format.
- Filter entries based on date range.
- View total and average calorie intake.
- Visualize calorie data with interactive charts.

## Technologies
- Python
- Flask
- SQLite
- HTML/CSS
- JavaScript
- Chart.js

## Setup and Installation
To set up this project locally, follow these steps:

1. **Clone the Repository**
git clone https://github.com/lowvoltagenation/caloriecounter.git
cd caloriecounter

2. **Create and Activate a Virtual Environment (Optional)**
python -m venv venv
source venv/bin/activate # On Windows use venv\Scripts\activate

3. **Install Required Packages**
pip install -r requirements.txt

4. **Initialize the Database**
python init_db.py

5. **Run the Application**
python main.py

The application will be accessible at `localhost:5000`.

## Usage
After running the application, navigate to `localhost:5000` in your web browser. You can start by adding food items and their corresponding calorie values. Entries can be filtered by date for better insights.

## Contributing
Contributions to Calorie Counter are welcome! Feel free to submit pull requests or open issues to suggest improvements or add new features.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to all the contributors and developers who have worked on the technologies and tools used in this project.
   
