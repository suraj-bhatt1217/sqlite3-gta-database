# SQLite GTA Database

This repository contains a Python script to create and populate an SQLite database with data related to the Grand Theft Auto (GTA) game series.

## Project Structure

- `create_gta_db.py`: The main script that creates and populates the SQLite database.
- `gta.db`: The SQLite database file created by the script.
- `requirements.txt`: List of dependencies required to run the script.

## Prerequisites

- Python 3.x
- SQLite3

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/sqlite-gta-database.git
    cd sqlite-gta-database
    ```

2. Create and activate a virtual environment (optional but recommended):

    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

Run the `create_gta_db.py` script to create and populate the `gta.db` SQLite database:

```sh
python create_gta_db.py
