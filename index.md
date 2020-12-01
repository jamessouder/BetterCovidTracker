## Welcome to Covid Tracker Backened

The backend is an API for the BetterCovidTracker. It uses the most current Johns Hopkins data to fill a backend SQLite3 database and power the API.

### Running the API
The API is written is python using the Flask framework. As a result the following are required:
 - Python 3.x
 - Flask 1.1.x

To run, Issue the following commands:
- venv/bin/activate
- export FLASK_APP=flaskr
- export FLASK_APP=development
- flask run

The server will run on port 5000.

### API Endpoints
/state/confirmed
/state/deaths
/state/confirmed/population
/state/deaths/population
/state/dpc (Deaths per Capita)
