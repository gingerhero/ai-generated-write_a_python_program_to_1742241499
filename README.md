# Sum Calculator Web App

A simple web application that calculates the sum of two numbers.

## Requirements

- Python 3.6 or higher
- Flask

## Installation

1. Clone this repository or download the files
2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   ```
3. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`
4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

1. Make sure your virtual environment is activated
2. Run the Flask application:
   ```
   python app.py
   ```
3. Open your web browser and navigate to `http://127.0.0.1:5000/`
4. Enter two numbers and click "Calculate Sum" to see the result

## Project Structure

- `app.py`: The main Flask application
- `templates/index.html`: HTML template for the web interface
- `static/style.css`: CSS styles for the web interface
- `requirements.txt`: List of Python dependencies
