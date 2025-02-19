Step-by-Step Guide to Install and Deploy Vulnerable Code

Step 1: Set Up the Environment
    Install Python:
    
1. Download and install Python from python.org.
2. Ensure Python is added to your system PATH during installation.
3. Verify the installation by running:

        python --version

4. SQLite (it will be comes pre-installed with Python. No additional installation is required)

Step 2: Create a Database and Table
Open a terminal or command prompt.
Create a new Python script to set up the database (grab the setup_database.py on this repository and execute on your own server)
This will create a database file named example.db with a users table and some sample data.

Step 3: Install Flask (System-Wide)
If you want to install Flask system-wide, you can use the apt package manager:

    Update your package list:
    sudo apt update

    Install Flask:
    sudo apt install python3-flask

    Verify the installation:
    flask --version

Step 4: Write the Vulnerable Code
grab the v1 code on this repository

Step 5: Run the Vulnerable Code
Run the Flask application:

    python3 v1.py

Open your browser and navigate to http://127.0.0.1:5000/.
