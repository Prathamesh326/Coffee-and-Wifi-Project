# Coffee and Wifi Project

Welcome to the **Coffee and Wifi** project! This web application allows users to browse and add information about cafes, including details on coffee quality, WiFi strength, and power socket availability. The project leverages several web technologies to create an interactive and user-friendly experience.

## Features

- **Add Cafes**: Users can submit details about their favorite cafes, including name, location, opening and closing times, coffee rating, WiFi strength, and power socket availability.
- **View Cafes**: Users can view a list of all submitted cafes with the ability to see the location on Google Maps.
- **Data Storage**: Cafe details are stored in a CSV file, making it easy to manage and export data.

## Technologies Used

- **Flask**: A lightweight web framework for Python that powers the backend of the application.
- **Flask-Bootstrap**: An extension that integrates Bootstrap 5 into Flask applications for responsive and modern design.
- **Flask-WTF**: An extension that provides integration with WTForms, handling form rendering and validation.
- **WTForms**: A flexible forms validation and rendering library for Python web development.
- **CSV**: Used for storing and managing cafe data in a simple and accessible format.

## Project Structure

```
Coffee-and-Wifi-Project/
│
├── main.py                # The main application file containing routes and logic
├── templates/             # Folder containing HTML templates
│   ├── base.html          # Base template
│   ├── index.html         # Home page template
│   ├── add.html           # Add cafe form template
│   ├── cafes.html         # Cafes listing template
│
├── static/                # Folder for static files like CSS
│   └── css/
│       └── styles.css     # Custom styles
│
├── cafe-data.csv          # CSV file storing cafe data
│
└── README.md              # This file
```

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Prathamesh326/Coffee-and-Wifi-Project.git
   ```

2. **Navigate into the project directory**:
   ```bash
   cd Coffee-and-Wifi-Project
   ```

3. **Create and activate a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

4. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application**:
   ```bash
   python main.py
   ```

6. **Access the application**:
   Visit `http://127.0.0.1:5000/` in your web browser.

## Contributions

Contributions are welcome! If you find any issues or have ideas for improvements, please open an issue or submit a pull request.


Enjoy exploring and contributing to the Coffee and Wifi project! ☕💻
