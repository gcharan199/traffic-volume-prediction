# Traffic Volume Prediction

This is a Flask web application that predicts traffic volume based on temperature, day of the week, location, and time of day using a linear regression model.

## Prerequisites

Ensure you have Python 3.6+ installed on your machine.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required Python packages using `pip`:

    ```bash
    pip install -r requirements.txt
    ```

3. Place your CSV file named `charan.csv` in the root directory of the project. Ensure the CSV file has the following columns:
    - `temperature`
    - `day_of_week`
    - `location`
    - `time_of_day`
    - `traffic_volume`

## Running the App

1. Run the Flask app:

    ```bash
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Usage

1. Enter the required details in the form:
    - Temperature
    - Day of the Week
    - Location
    - Time of Day

2. Click on the "Predict" button to get the predicted traffic volume.

## Project Structure

