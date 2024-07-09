# Brute Force Simulator

This project is a simple web application that simulates brute force attacks using a Python backend with Flask and a frontend built with HTML, CSS, and JavaScript. It provides options to test a directory brute-force and a password brute-force.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Setup

1. **Clone the repository**:
    ```sh
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Create a virtual environment**:
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
      ```sh
      .\venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```sh
      source venv/bin/activate
      ```

4. **Install dependencies**:
    ```sh
    pip install flask flask-cors
    ```

## Usage

### Starting the Backend Server

1. **Navigate to the project directory**:
    ```sh
    cd <repository_directory>
    ```

2. **Run the Flask application**:
    ```sh
    python app.py
    ```

### Accessing the Frontend

1. Open `index.html` in your preferred web browser.

### Testing the Application

1. Enter a password in the input field.
2. Click on "Password Brute Force" to simulate a password brute force attack.
3. Click on "Directory Brute Force" to simulate a directory brute force attack.
4. The results will be displayed below the buttons.

## File Structure

brute-force-simulator/
│
├── app.py          # Flask backend
├── index.html      # Frontend HTML
├── styles.css      # Frontend CSS
├── script.js       # Frontend JavaScript
├── README.md       # Project README file
└── requirements.txt# Python dependencies



## Technologies Used

- **Frontend**:
  - HTML
  - CSS
  - JavaScript

- **Backend**:
  - Python
  - Flask
  - Flask-CORS

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
