## Installation

#### Prerequisites
- Python 3.9 or higher
- PostgreSQL installed and running
- pip (Python package manager)
- Git

#### Steps
1. Clone the repository:
```bash
git clone https://github.com/SamJones56/vuln-bank-original.git
cd vuln-bank-original
```

2. Create and activate a virtual environment:
```bash
# On Windows
python -m venv venv
venv\Scripts\activate

# On Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Create necessary directories:
```bash
# On Windows
mkdir static\uploads

# On Linux/Mac
mkdir -p static/uploads
```

5. Modify the .env file:
   - Open .env and change DB_HOST from 'db' to 'localhost' for local PostgreSQL connection

6. Run the application:
```bash
# On Windows
python app.py

# On Linux/Mac
python3 app.py
```

Current environment variables:
```bash
DB_NAME=vulnerable_bank
DB_USER=postgres
DB_PASSWORD=postgres
DB_HOST=db  # Change to 'localhost' for local installation
DB_PORT=5432
```

### Database Setup
The application uses PostgreSQL. The database will be automatically initialized when you first run the application, creating:
- Users table
- Transactions table
- Loans table

### Accessing the Application
- Main application: `http://localhost:5000`
- API documentation: `http://localhost:5000/api/docs`

### Common Issues & Solutions

#### Windows
1. If you get "python not found":
   - Ensure Python is added to your system PATH
   - Try using `py` instead of `python`

2. Permission issues with uploads folder:
   - Run command prompt as administrator
   - Ensure you have write permissions in the project directory

#### Linux/Mac
1. Permission denied when creating directories:
   ```bash
   sudo mkdir -p static/uploads
   sudo chown -R $USER:$USER static/uploads
   ```

2. Port 5000 already in use:
   ```bash
   # Kill process using port 5000
   sudo lsof -i:5000
   sudo kill <PID>
   ```

#### PostgreSQL Issues

1. Connection refused:

   * Ensure PostgreSQL is running
   * Check credentials in `.env` file
   * Verify PostgreSQL port is not blocked

2. Authentication failed:

   * Make sure `DB_PASSWORD` in `.env` matches your Postgres user’s password.
   * Or reset the `postgres` user with:

     ```sql
     ALTER ROLE postgres WITH PASSWORD 'your_password';
     ```

3. Installation errors:

   * If you encounter any PostgreSQL errors, install via Chocolatey and set the password to `postgres`:

     ```powershell
     choco install postgresql --version=17.4.0 -y
     # Use the generated password, or immediately reset it:
     & 'C:\Program Files\PostgreSQL\17\bin\psql.exe' -U postgres -c "ALTER ROLE postgres WITH PASSWORD 'postgres';"
     ```

4. Database does not exist:

   * Create it manually with:

     ```sql
     CREATE DATABASE vulnerable_bank;
     ```
   * Or run:

     ```bash
     createdb -U postgres -h localhost vulnerable_bank
     ```
